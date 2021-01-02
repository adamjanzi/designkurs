---
Title: Load
Template: kmom
---

<div class="kmom-container">
<div class="kmom-sidebar">
<a href="01_colors"><p class="sidebar-notchosen">Analysis: Colors</p></a>  
<a href="02_load"><p class="sidebar-chosen">Analysis: Load</p></a>  
<a href="03_design_principles"><p class="sidebar-notchosen">Analysis: Design Principles</p></a>  
</div> 
<div class="kmom-mainpage">
<h2>Analysis: Load</h2>
<p>I denna uppgiften så analyserar jag tre olika webbplatser utifrån deras laddningstid och användbarhet. Målet med detta är att jämföra webbplatsernas laddningstid med varandra och se vad som kan förbättras och hur, med användbarhet i åtanke.</p>

<h3>Urval</h3>  

<p>De webbplatser jag har valt att analysera kommer alla från samma kategori precis som i min förra analys, nämligen musik. Webbplatserna tillhör tre olika rock/metalband ('Leprous', 'Agent Fresco' och 'Epica'). Jag valde denna typ av webbplatser då jag själv är aktiv musiker i den sfären och kan relatera till de stilistiska valen. Det kändes dessutom rimligt att välja webbplatser som existerar i samma sfär, istället för tre olika webbplatser, just för att kunna jämföra. Anledningen till varför jag väljer samma typ av webbplatser som i min förra analys är för att få en helhetsbild i samband med min tidigare analys och analysen som följer denna. Både Leprous och Agent Fresco analyseras i min tidigare analys. Mobius, som jag analyserade i min tidigare analys, har jag valt att byta ut i denna analys mot Epica, då Mobius webbplats inte uppfyllde uppgiftens kriterier (Mobius webbplats består enbart av en webbsida).</p>

<h3>Metod</h3>  

<p>Analysen jag har gjort följer givetvis kraven i uppgiften, där jag helt enkelt kollar laddningstiden och användbarheten för vardera webbplats och jämför dessa med varandra. De verktyg som jag har använt under analysen är Google PageSpeed och DevTools fliken Network, för att snabbt och enkelt kunna mäta laddningstiden, antalet resurser som laddas samt sidans totala storlek, på tre sidor på vardera webbplats. Jag använder även Google Kalkylark för att spara min data där. De tre sidorna för varje webbplats som jag har valt är startsidan, Tour/Tour Dates samt Contact/Connect. Jag har valt samma typ av sidor för de tre webbplatserna för att enkelt kunna göra en intressant jämförelse däremellan.</p>

<h3>Resultat</h3>  
<br>

<a target="_blank" href="https://www.leprous.net/"><h4>leprous.net</h4></a>
<br>

<img src="../assets/img/leprous.jpg" class="websiteimg" alt="Leprous.net">

<a target="_blank" href="https://docs.google.com/spreadsheets/d/1hAAB1juw95jCcWbEuaXxJrrRBIO7OsCi6rZhynjw-54/edit?usp=sharing"><p class="sidebar-notchosen">Raw Analysis Data</p></a> 

<a target="_blank" href="https://www.leprous.net/"><p class="sidebar-notchosen">Link to Homepage</p></a>
<a target="_blank" href="https://www.leprous.net/tours.html"><p class="sidebar-notchosen">Link to Tour Dates</p></a>
<a target="_blank" href="https://www.leprous.net/contact.html"><p class="sidebar-notchosen">Link to Contact</p></a>

<p>Leprous är ett progressivt rock/metalband från Norge. Bandet är väl etablerade och förväntas därför ha en väl uppbygd webbplats. Webbplatsen får generellt bra betyg för både mobile och desktop, vilket inte är förvånande med tanke på bandets status. Det är snarare förväntat. Som vi kan se i den råa datan så hamnar betygen för desktop alltid över 90 i den råa datan. Detsamma gäller dock inte för mobile.</p>

<p>Trots bandets status så kan vi självklart se utifrån betyget att det finns rum för förbättring.
För startsidan på webbplatsen så finns det en tydlig åtgärd och det är att använda andra format för bilderna. De som rekommenderas är JPEG 2000 och JPEG XR bland annat.
Detta kan spara 1.36s på desktop och 7.8s på mobile. Som vi kan se så är detta alltså mest kritiskt för mobile, där en hel mängd tid kan sparas på detta. För mobile så kan bilderna även komprimeras bättre för att spara mer tid.
För Tour Dates sidan så ser vi en annan åtgärd som rekommenderas, nämligen "eliminate render-blocking resources". För desktop så kan detta spara 0.47s och för mobile så kan detta spara 1.78s. Återigen så är det åtgärden för mobile som är mer kritisk i detta fall. Detta går i sin grund ut på att ladda det som är kritiskt först och vänta lite med att ladda det som inte är kritiskt. Sånt som inte är kritiskt är sånt som till exempel inte är synligt direkt. För mobile så rekommenderas även att använda andra bildformat för att spara lite extra tid, precis som på startsidan.
För Contact sidan så händer inget nytt gällande åtgärder på desktop. På mobile däremot så får vi ännu en ny rekommenderad åtgärd. Utöver de två åtgärder från Tour Dates sidan, så rekommenderas det även att man tar bort JavaScript som inte används. Detta kan spara 0.6s.
För denna webbplats så handlar det alltså för det mesta om att spara plats och tid via bilderna, mestadels på den mobila delen.</p>

<a target="_blank" href="https://www.agentfresco.is/"><h4>agentfresco.is</h4></a>
<br>

<img src="../assets/img/agent fresco.jpg" class="websiteimg" alt="Leprous.net">

<a target="_blank" href="https://docs.google.com/spreadsheets/d/1izNHtU0BIe9TWgBmxaM68CLTzDeBphGc-oWsyzFHGxI/edit?usp=sharing"><p class="sidebar-notchosen">Raw Analysis Data</p></a> 

<a target="_blank" href="https://www.agentfresco.is/"><p class="sidebar-notchosen">Link to Homepage</p></a>
<a target="_blank" href="https://www.agentfresco.is/tour-dates"><p class="sidebar-notchosen">Link to Tour Dates</p></a>
<a target="_blank" href="https://www.agentfresco.is/contact"><p class="sidebar-notchosen">Link to Contact</p></a>

<p>Agent Fresco är ett progressivt rockband från Island. Likt Leprous så är Agent Fresco ett väl etablerat band och förväntas därför ha en viss standard på deras webbplats.
Det vi genast ser är att webbplatsen är acceptabel/bra på desktop och katastrofal på mobile, gällande laddningstiden. Detta är väldigt oväntat, speciellt då detta är ett modernt band som riktar sig mot ungdomar, där en webbplats som är väl anpassad för mobile nästan är ett krav.</p>

<p>Det är en väldig överraskning att se att denna webbplats får ett så dåligt betyg på laddningstiden gällande mobile. Det finns en del åtgärder som rekommenderas och detta är mest kritiskt när det gäller startsidan. I detta fall så handlar det om att göra sig av med JavaScript och CSS som inte används. På mobile så kan detta spara in totalt 8.55s. Att dessutom prioritera att ladda det som är kritiskt först kan också spara tid. Dessa åtgärder gäller både mobile och desktop.
Enbart på mobile så kan dessutom bilderna justeras i storlek samt i formatet för att spara upp till 1s.
De ovan nämnda åtgärderna gällande oanvänd JavaScript och CSS samt prioritering kring laddning av det som är mer kritiskt gäller även för Tour Dates sidan, både för mobile och desktop.
På mobile så kan detta spara in 5.97s.
Exakt samma sak gäller Contact sidan också, där detta kan spara in 5.55s på mobile.
I sin helhet så handlar det mest om att rensa kod i detta fall.</p>

<a target="_blank" href="https://www.epica.nl/home"><h4>epica.nl</h4></a>
<br>

<img src="../assets/img/epica.png" class="websiteimg" alt="Epica.nl">

<a target="_blank" href="https://docs.google.com/spreadsheets/d/1wI-UZlD-hMSPM_YCfghuI1e_LjMMxcYpMewqR2YPe8Q/edit?usp=sharing"><p class="sidebar-notchosen">Raw Analysis Data</p></a> 

<a target="_blank" href="https://www.epica.nl/home"><p class="sidebar-notchosen">Link to Homepage</p></a>
<a target="_blank" href="https://www.epica.nl/tour"><p class="sidebar-notchosen">Link to Tour Dates</p></a>
<a target="_blank" href="https://www.epica.nl/contact"><p class="sidebar-notchosen">Link to Contact</p></a>

<p>Epica är ett symfoniskt metalband från Holland och är ett av de största banden i världen i sin genre. Då detta band är ett av de större metalbanden som existerar så förväntas de hålla en väldigt hög standard. Som syns på deras webbplats så är denna webbplats mycket mer omfattande än de tidigare webbplatserna, med tanke på hur stort detta band är. Om detta inte är strukturerat på ett bra sätt så kan webbplatsen kräva omfattande åtgärder för laddningstiden. Det visar sig att laddningstiden inte är så bra på denna webbplats. Det är någorlunda acceptabelt för desktop, men illa för mobile. I detta fall är det också väldigt oväntat med tanke på hur väl etablerat detta band är.</p>

<p>Startsidan är nog den sidan som ligger sämst till av de tre valda sidorna på webbplatsen.
Precis som med de tidigare nämnda webbplatserna så är mobile den svagare länken mellan mobile och desktop. På startsidan så är bilderna det stora problemet, både för mobile och desktop. 
För bilderna så rekommenderas det att de använder sig utav ett annat format, så som JPEG 2000 eller JPEG XR. Det finns även flertalet bilder som inte kan hittas.
Det rekommenderas även att lägga rätt storlekar på bilderna samt att ladda de bilder som inte visas direkt senare än de mer kritiska bilderna. Allt detta gäller både mobile och desktop, där vi kan spara 12s på desktop och 102.6s på mobile.
På Tour sidan så är det inte alls lika illa, men det finns även här rum för förbättringar. Förutom att ändra format på bilderna så rekommenderas det även att ladda de kritiska resurserna först. Här stöter vi även på en ny typ av åtgärd, som har med servern att göra, där responstiden från servern tar lite för långt tid. Detta kan ske om till exempel serverns hårdvara är utdaterad. Dessa åtgärder kan spara oss 4.67s på desktop och 11.16s på mobile.
På Connect sidan så handlar det precis som tidigare om att ändra formatet på bilderna, samt att ladda det som är kritiskt först.
Som vi ser här då så handlar det alltså till stor del om bilderna, med fokus på mobile.</p>

<h3>Analys</h3>  

<p>Det mest överraskande resultatet under denna analys var att se trenden att få sämre resultat på mobile, där jag hade förväntat mig att webbplatser för moderna metalband skulle fokusera mer på mobile. Den mest förekommande åtgärden som dök upp för dessa tre webbplatser och dess sidor var att uppdatera formatet för bilderna. Detta verkar vara något som är lätt att åtgärda och som kan spara mycket tid. En annan åtgärd som dök upp flertalet gånger, dock på en lite mindre skala ibland, var att rensa JavaScript och CSS som inte används.
Dessa åtgärder känns givna oavsett om de sparar tid eller inte då de kan bidra till en renare struktur. Men en annan åtgärd som dök upp ofta som är direkt kopplad till laddningstiden är att endast ladda det som är kritiskt först och ladda resten efteråt, när kärnan är igång. Denna åtgärd rekommenderades för flertalet av sidorna för alla webbplatser i analysen och kan leda till mycket sparat tid.</p>

<p>Denna analysen öppnar upp för diskussionen om mobile versus desktop. Mina tankar går då till vad som är mer aktuellt för företagen i fråga. Och som sagt, med tanke på att dessa företag är unga och moderna metalband så hade jag förväntat mig att de fokuserade lite mer på mobile än på desktop. Å andra sidan så får man fråga sig om webbplatserna riktar sig mot fans eller mot folk som arbetar i branschen. Fans är förmodligen mer benägna att besöka sidan via mobil, medans branschfolk givetvis oftast arbetar på en dator. Detta är ingen ursäkt, då man bör till exempel rensa bort JavaScript och CSS som inte används oavsett vad. Men det kanske är en förklaring till varför webbplatserna är mer fokuserade på desktop än på mobile. Oavsett om detta är sant eller ej, så leds mina tankar till syfte vid webbdesign. Vem riktar sig webbplatsen mot och varför. Det är viktigt att anpassa sin design och struktur samt sitt mål till målgruppen i fråga.</p>

<p>Om jag ska rangordna de tre webbplatserna utifrån resultat så skulle listan se ut på det här sättet:
1. leprous.net
2. agentfresco.is
3. epica.nl</p>

<p>Anledningen till denna rangordning är tydlig i mitt tycke. Leprous hade utan tvekan den webbplats som fick bäst betyg på både mobile och desktop. Svårigheten låg i rangordningen låg mellan Agent Fresco och Epica. Trots att Agent Fresco fick snäppet sämre betyg än Epica så satte jag Agent Fresco före Epica då webbplatsen tillhörande Agent Fresco upplevdes mycket snabbare än Epica, både på mobile och på desktop. Epica har redan en tung webbplats i grunden, så med dess dåliga betyg på laddningstiden så blev laddningstiden och tyngden för märkbar och nästan frustrerande.</p>

<p>För min del så uppfattar jag själv att en webbplats är långsam om den laddar längre än 2 sekunder. Webbplatserna för Agent Fresco och Leprous klarar den gränsen, då de laddar webbplatserna snabbt, trots att Leprous webbplats har en laddningsskärm. Webbplatsen för Epica (startsidan) tar dock otroligt lång tid att ladda, helt klart mer än 2 sekunder i vissa fall.
Webbplatsen för Epica känns dessutom inte alls så snabb när man navigerar på den. Det känns nästan klumpigt och man vill helst inte välja andra menyval då man är förberedd på en lång laddningstid.
När det gäller webbplatsen för Agent Fresco däremot så är det raka motsatsen. Trots att denna webbplats fick så dåligt betyg så känns det väldigt smidigt att navigera på webbplatsen. Detta i samband med dess stilrena design gör att webbplatsen känns fräsch och inte alls klumpig.
Leprous webbplats hamnar någonstans mittemellan. Den känns fräsch i sin design, men att navigera på webbplatsen känns någorlunda klumpigt. Det går fortfarande att ta sig runt, men inte så smidigt som jag skulle önska.</p>

<p>Överlag så överraskade det mig hur dessa webbplatser som jag hade förväntat mig att de skulle vara moderna, inte alls var moderna och hade flertalet brister. Definitivt inte det jag förväntade mig av aktuella och moderna band.</p>

<h3>Referenser</h3>  
<a href="https://www.leprous.net/" target="_blank"><p>leprous.net</p></a>
<a href="https://www.agentfresco.is/" target="_blank"><p>agentfresco.is</p></a>
<a href="https://www.epica.nl/home" target="_blank"><p>epica.nl/home</p></a>
<a href="https://developers.google.com/speed/pagespeed/insights/" target="_blank"><p>PageSpeed</p></a>

<h3>Övrigt</h3>  

<p>Mitt namn är Adam Janzi och denna rapport är skriven enbart av mig.</p>
</div>
</div>