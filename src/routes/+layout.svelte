<script>
	import '../app.css';
</script>

<nav class="shadow slideIn">
	<div class="container flex items-center font-bold justify-center p-3 mx-auto text-gray-50">
		<img
			src="https://www.cins.rs/wp-content/themes/cins/assets/logo.png"
			alt="data harvest logo"
			class="h-7"
		/>
		<h3 class="ml-2 text-md mt-2">Slučaj Stražar</h3>
	</div>
</nav>

<slot />

<style>
	nav {
		background-color: #D2C0A7;
		position: fixed;
		top: 0;
		left: 0;
		right: 0;
		z-index: 100;
		width: 100%;
	}

	.slideIn {
		animation: slideIn ease 1s;
		-webkit-animation: slideIn ease 1s;
		-moz-animation: slideIn ease 1s;
		-o-animation: slideIn ease 1s;
		-ms-animation: slideIn ease 1s;
	}

	@keyframes slideIn {
		0% {
			transform: translateY(-100%);
		}
		100% {
			transform: translateY(0%);
		}
	}
</style>

