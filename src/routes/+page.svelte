<script>
	import FlourishScroller from '../components/FlourishScroller.svelte';
	import NewsArticle from './NewsArticle.svelte';
	let steps = [
		'<b>Šta se sve desilo u slučaju Stražar: Od skrivene imovine do postupaka koji su pali.</b>',
		'<i>U julu 2021. godine carinici na beogradskom aerodromu zaplenili su sliku Stražar Paje Jovanovića od jednog putnika koji je nije prijavio. Kada je CINS otkrio da je reč o gradskom funkcioneru, neki postupci su pokrenuti i ubrzo okončani, a pitanja o njegovoj imovini i poreklu novca za sliku su ostala neodgovorena.</i>',
		'<b>16. jul 2021.</b> <br> <br> Carina saopštava da su dan ranije na aerodromu <i>Nikola Tesla</i> zaplenili umetničku sliku Stražar čuvenog srpskog slikara Paje Jovanovića koju je jedan putnik pokušao bez prijavljivanja da unese u zemlju. <br><br> Kako su rekli tada, slika je pronađena kod jednog 39-godišnjeg Beograđanina koji je doputovao iz Beča. <br><br> Kod njega je nađeno i 15 i po hiljada evra koje nije prijavio.',
		'Nakon zaplene, tadašnji zamenik gradonačelnika Beograda Goran Vesić na svom Fejsbuku objavljuje da je i Grad Beograd bio zainteresovan da kupi ovu sliku, ali da je taj plan bio tajna jer bi da se za to znalo porasla cena. Na Fejsbuku je otkrio i da je navodno zamolio jednu zapadnu kompaniju da kupi sliku i pokloni je Muzeju grada Beograda, kao i da je ta firma bila spremna da za Stražara izdvoji do 50.000 evra.',
		'Uprkos zapleni, u objavi je najavio i konačno odredište ove slike, odnosno da će se ona ipak naći u Muzeju grada Beograda: <br> <br> <i>Kako bi naš narod rekao nije kome je rečeno nego kome je suđeno.</i>',
		'<b>21. septembar 2021.</b> <br> <br>CINS <a href="https://www.cins.rs/slucaj-strazar-kolekcionar-iz-gradske-uprave/">objavljuje</a> da je misteriozni putnik kome je zaplenjena slika zapravo gradski sekretar za komunalne i stambene poslove Grada Beograda Nikola Kovačević. <br><br>U izjavi za CINS Kovačević je rekao da nije pokušao da sakrije sliku, već da je prišao cariniku kako bi ga pitao šta da radi jer ima kulturno dobro.<br><br><i>„Kao kada dolazite u Egipat i donosite delove piramide i kažete ’draga moja zemljo, evo doneo sam iz druge zemlje delove piramide’“</i>, izjavio je on.',
		'Tvrdio je i da je slika kupljena novcem koji je njegova supruga dobila od prodaje nekretnine, a koji je prijavljen Agenciji za sprečavanje korupcije: <br> <br><i>„Novac je legalno zarađen, nalazio se na računu moje supruge i nema nikakve veze sa mojom platom“. </i> <br> <br> Protiv Kovačevića su nakon zaplene podnete dve prekršajne prijave – jedna jer carini nije prijavio sliku, a druga zbog neprijavljivanja preko 15 hiljada evra gotovine koju je nosio prilikom ulaska u zemlju. <br> <br> On je tada za CINS rekao da „apsolutno treba da plati prekršajnu kaznu“ i da će slika da ostane u porodici.',
	];
</script>

<FlourishScroller flourish_id="1970761" {steps} />

<NewsArticle />
