Titel på rapporten
=======================

I den här rapporten granskar vi tre hemsidor och mäter hur snabbt de laddas och om det finns möjlighet att förbättra hemsidans laddningstid och användbarhet.  

Urval
-----------------------

Författaren valde att fortsätta granska de tre Te och Kaffe hemsidorna som analyserades i kmom04.  
Tehuset JAVA, Skandinavisk Te och Kaffe handel och Bönor och Blad.

Metod
-----------------------

På respektive hemsidas homepage, index sida, analyserades de olika request och loadtime parametrarna i devtools network.  
Detta gjordes tre gånger per hemsida, resultaten dokumenterades i google kalkylark (som är liknande microsoft excel) och ett medelvärde av detta dokumenterades.  
Hemsidornas homepage analyserades i PageSpeed Insights, dokumenterades i google kalkylark och ett medelvärde dokumenterades.  
Skärmbilder av PageSpeed togs och kan ses nedan, klicka på bilden för att se hela skärmbilden.  

Resultat
-----------------------

**Devtool network**  
Tehuset JAVA har i genomsnitt 132 resurser varav 66,6 av dessa är bilder. Bilderna tar upp 2,9 MB av sidans totala storlek på 6,83 MB - ca 42%.  
Skandinavisk Te och Kaffe handeln hade betydligt färre resurser, 69 och 9 av dessa var bilder. Sidans totala storlek är 2,1 MB och bilderna tog upp 340 kB av detta, ca 16%.  
Bönor och Blad hade flest antal resurser. 186,3 och 128,3 av dessa var bilder. Sidans totala storlek är 4,8 MB. Bilder tog upp 1,4 MB av detta, ca 29%.  


**Insamlad data**  
  
<div class="iframeyou">
    <iframe width="700" height="300" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vQbI6JLJclrWjcc6-WepYcjFfJ5g93dXi2FombXGv4pm1atxQ8KS5D-LuxmX1Mnf1GAVr_YMF-xoEW3/pubhtml?widget=true&amp;headers=false"></iframe>  
</div>
  
Klicka på bilden nedan för att se all insamlad data.
<a href="%base_url%/image/datanetwork.png" target="_blank">
    <picture>
        <source media="(min-width:721px)" srcset="%base_url%/image/datanetwork.png?w=50%&q=25&area=0,8,50,0">
        <source media="(min-width:500px)" srcset="%base_url%/image/datanetwork.png?q=25">
        <img src="%base_url%/assets/img/datanetwork.png" alt="screenshot of collected data in excel">
    </picture>
</a>
**PageSpeed Insights**  

**Tehuset JAVA**  
  
Hemsidan fick 72 poäng av 100 möjliga i prestanda på desktop och 37 poäng på mobil. Sidan har ett speed index på 2,9 s för desktop och 5,8 s för mobilen.   
Pagespeed analysen visade att det fanns många möjligheter att optimera sidan. Några av dessa inkluderar: använda bilder i rätt storlek och använd ett modernare bildformat som WebP och AVIF.  
Tehuset JAVAs desktop sida blev inte godkänd av Core Web Vitals.  
Andra anmärkningar var att bildelement saknade alt attribut, undvika ett stort DOM-träd, undvik enorm nätverksbelastning och 29% av tryckmålen på mobil inte hade en lämplig storlek. Kontrasten mellan bakgrundsfärgen och förgrundsfärgen var inte tillräckligt stor enligt pagespeed.  
  
<picture>
    <source media="(min-width:721px)" srcset="%base_url%/image/javaload.png?w=25%&q=50">
    <source media="(min-width:500px)" srcset="%base_url%/image/javaload.png?w=25%&q=50">
    <img src="%base_url%/assets/img/javaload.png" alt="screenshot of tehuset java homepage">
</picture>
  
PageSpeed: Desktop  
<a href="%base_url%/image/speedjava.png" target="_blank">
    <picture>
        <source media="(min-width:721px)" srcset="%base_url%/image/speedjava.png?area=0,20,84,20">
        <source media="(min-width:500px)" srcset="%base_url%/image/speedjava.png?area=0,25,84,25">
        <img src="%base_url%/assets/img/speedjava.png" alt="screenshot of ">
    </picture>
</a>
  
PageSpeed: mobile  
<a href="%base_url%/image/speedjavamobil.png" target="_blank">
    <picture>
        <source media="(min-width:721px)" srcset="%base_url%/image/speedjavamobil.png?area=0,20,84,20">
        <source media="(min-width:500px)" srcset="%base_url%/image/speedjavamobil.png?area=0,25,84,25">
        <img src="%base_url%/assets/img/speedjavamobil.png" alt="screenshot of ">
    </picture>
</a>
  
**Skandinavisk Te och Kaffe handeln**  
  
Hemsidan klarade sig bättre än föregående hemsida med 92 poäng i prestanda på desktop och 80 poäng på mobil.  
Speed index ligger på 1,2 s för desktop respektive 3,7 s för mobil.  
Även här tycker PageSpeed analysen att det finns förbättringspotential genom att använda rätt bildstorlek, ett modernare bildformat och koda bilderna effektivt.  
Andra anmärkningar var att ett stort DOM-träd återfanns, enorm nätverksbelastning, vissa bildelement saknade alt attribut, kontrasten mellan bakgrundfärg och förgrundsfärg var inte tillräckligt stor.  

  
<picture>
    <source media="(min-width:721px)" srcset="%base_url%/image/teochkaffe1.png?w=25%&q=50">
    <source media="(min-width:500px)" srcset="%base_url%/image/teochkaffe1.png?w=25%&q=50">
    <img src="%base_url%/assets/img/teochkaffe1.png" alt="screenshot of te och kaffe handel homepage">
</picture>  
  
PageSpeed: Desktop  
<a href="%base_url%/image/speedteokaffedator.png" target="_blank">
    <picture>
        <source media="(min-width:721px)" srcset="%base_url%/image/speedteokaffedator.png?area=0,20,84,20">
        <source media="(min-width:500px)" srcset="%base_url%/image/speedteokaffedator.png?area=0,25,84,25">
        <img src="%base_url%/assets/img/speedteokaffedator.png" alt="screenshot of ">
    </picture>
</a>
  
PageSpeed: mobile  
<a href="%base_url%/image/speedteokaffemobil.png" target="_blank">
    <picture>
        <source media="(min-width:721px)" srcset="%base_url%/image/speedteokaffemobil.png?area=0,20,84,20">
        <source media="(min-width:500px)" srcset="%base_url%/image/speedteokaffemobil.png?area=0,25,84,25">
        <img src="%base_url%/assets/img/speedteokaffemobil.png" alt="screenshot of ">
    </picture>
</a>
  
**Bönor och Blad**  
  
Hemsidan fick 56 poäng på desktop och 34 poäng på mobil, vilket är de lägsta mätvärdet i prestanda för mobila enheter i detta urval.  
Speed index ligger på 1,8 s för desktop och 6,7 s för mobil.  
PageSpeed menar att det finns förbättringspotential. Framförallt skjuta upp inläsning av bildobjekt som inte visas på den mobila skärmen och ta bort resurser som blockar rendering, samt ta bort JavaScript som inte används.  
Andra problemområden var stort DOM-träd, enorm nätverksbelastning, minska arbetsbelastning på modertråden, vissa bildelement saknar width, height och alt attribut. Kontrasten mellan bakgrund ochförgrund är inte här heller tillräckligt stor. 
På mobila enheter så var 25% av tryckmålen inte i en lämlig storlek.  

<picture>
    <source media="(min-width:721px)" srcset="%base_url%/image/bonoroblad1.png?w=25%&q=50">
    <source media="(min-width:500px)" srcset="%base_url%/image/bonoroblad1.png?w=25%&q=50">
    <img src="%base_url%/assets/img/bonoroblad1.png" alt="screenshot of bönor och blad homepage">
</picture>  
  
PageSpeed: Desktop  
<a href="%base_url%/image/speedbonorobladdator.png" target="_blank">
    <picture>
        <source media="(min-width:721px)" srcset="%base_url%/image/speedbonorobladdator.png?area=0,20,84,20">
        <source media="(min-width:500px)" srcset="%base_url%/image/speedbonorobladdator.png?area=0,25,84,25">
        <img src="%base_url%/assets/img/speedbonorobladdator.png" alt="screenshot of ">
    </picture>
</a>
  
PageSpeed: mobile  
<a href="%base_url%/image/speedbonorobladmobil.png" target="_blank">
    <picture>
        <source media="(min-width:721px)" srcset="%base_url%/image/speedbonorobladmobil.png?area=0,20,84,20">
        <source media="(min-width:500px)" srcset="%base_url%/image/speedbonorobladmobil.png?area=0,25,84,25">
        <img src="%base_url%/assets/img/speedbonorobladmobil.png" alt="screenshot of ">
    </picture>
</a>

  
Analys
-----------------------

Av de tre granskade hemsidorna så hade Skandinavisk Te och Kaffe handeln högst prestanda både på desktop och mobil. De hade även minst antal resurser, minsta totala sidstorleken på 2,1 MB och minsta andelen bilder på 340 kB, ca 16%.  
Det fanns dock förbättringspotential för den här sidan. Precis som för Tehuset JAVA vars bildobjekt tar upp ca 42% av hemsidans totala storlek, så kan hemsidan förbättras genom att optimera bildobjekten. Bättre storlek, bättre format.  
Bönor och blad fick ingen anmärkning på bildstorleken eller bildformatet, däremot fick de en anmärkning om inte alla bildelement hade width och height.  
Den vanligaste förbättringsåtgärden stod klart - optimera dina bildobjekts storlek och filformat.  
  
Baserat på den insamlade mätdatan ser jag den solklara vinnaren, **Skandinavisk Te och Kaffe handeln**. Med det bästa speed index på 1,2 s för desktop och 3,7 s på mobil var de överlägset etta i den kategorin. De hade den högsta prestandan med 92 poäng respektive 80 poäng. De hade den minsta hemsidan med sina 2,1 MB och minst andel bilder på 340 kB.  
Tehuset JAVA kommer på andraplats med den näst högsta prestandan, största sidan med sina 6,83 MB, trots att de har lägst betyd av alla i bästa metoder. Ca 42% av hemsidans totalastorlek upptas av bilder och det finns där en stor förbättringspotential genom att optimera bildobjekten.  
På sista plats hamnar Bönor och Blad som är den näst största sidan med 4,8 MB, har högst speed index på mobil, lägst prestanda och inga anmärkningar på bildoptimering utöver att bildobjekten saknar alt attribut, width och height. Bönor och Blad har full pot, 100% i bästa metoder men ändå låg prestanda. Här finns det mycket att förbättra.   
  
För mobila enheter så anses ett speed index på 0-3,4 sekunder som snabbt medan ett värde på över 5,8 sekunder anses vara långsamt.  
Jag känner att jag har lite mer tollerans för att vänta på att hemsidor ska laddas när jag sitter vid dator, på mobilen däremot, där vill jag att det ska gå fort.  
Bönor och Blad med sina 6,7 sekunder speed index och Tehuset JAVAs 5,8 sekunder för mobila enheter är orimligt lång tid att vänta. På mobila enheter så tror jag att 4 sekunder är rimligt.  
Hemsidorna klarade sig bättre på desktop med resultat mellan 1,2 - 2,9 sekunder, vilket är helt acceptabelt.

Referenser
-----------------------
  
https://www.tehusetjava.se/  
https://teochkaffehandel.se/  
https://bonorochblad.se/  
  
https://pagespeed.web.dev/  
https://developer.chrome.com/en/docs/lighthouse/performance/speed-index/#how-lighthouse-determines-your-speed-index-score  

Övrigt
-----------------------

Rapporten skrevs av Anja22.