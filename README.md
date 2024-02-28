<h2>Kas ir API</h2>
<p>Veids ar kuru serveris mijedarbojas ar klientu</p>

<h2>Kā deklarēt mainīgo PHP valodā?</h2>
<p>$mainīgā_nosaukums = vērtība;</p>

<h2>Kādu arhitektūru izmanto Laravel, paskaidro kā tā strādā</h2>
<p>MVC - model, view controller. modelis ir datu struktūra, view ir datu izvade un controller ir datu apstrāde</p>
<p>controller saņem klienta pieprasījumu, tad paņem datus no modeļa un aizsūta lietotājam (view) </p>

<h2>Kas ir ORM, kāpēc to izmanto tīra SQL vietā?</h2>
<p>Objektu un relāciju kartēšana (ORM, O/RM un O/R kartēšanas rīks) datorzinātnē ir programmēšanas paņēmiens datu konvertēšanai starp relāciju datu bāzi un objektorientētas programmēšanas valodas kaudzi. Tādējādi faktiski tiek izveidota virtuālo objektu datu bāze, ko var izmantot programmēšanas valodā.</p>

<h2>Uzraksti Eloquent ORM pieprasījumu modelim User, kur nepieciešams iegūt visus
lietotājus kuriem reitings ir lielāks par 4.</h2>
<p>User::where('rating', '>', 4)->get();</p>