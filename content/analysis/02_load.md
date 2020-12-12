---
Description: This is my analysis page for kmom05.
Template: kmom
---

<div class="kmom-nav kmom menu" id="my-nav">
<a href="javascript:void(0);" class="iconen" onclick="kmomNavbar()">
    <i class="fa fa-bars farg"></i>
</a>
<a href="01_colors">Analysis 1</a>
<a href="02_load">Analysis 2</a>
<a href="03_design_principles">Analysis 3</a>
</div>

<div class="kmom">
<h1>Analysis 2</h1>
<br>
<h3>Load time</h3>
<p>
Denna anayls handlar om att ta 3 olika webbplatser och testa hur snabb laddningstid de har och om de innehåller några saker som kan förbättras, med tanke på laddningtid och användbarhet.
</p>
<br>
<h3>Urval</h3>
<p>
Jag valde att använda samma webbplatser som på första analysen, IF, Svedea och Folksam. Detta för att kunna göra en full analys av dess sida, samt så vill man inte att det ska ta långt tid att köpa eller hitta information om försäkringar. 
<br>Det flesta människor vill bara att de delarna ska fungera och inte behöva tänka så mycket på försäkringar.
<h4>Folksam</h4>

<img src="../assets/img/analysis/folksam.jpg" alt="Bild på Folksams hemsida"><br>
<h4>Svedea</h4>

<img src="../assets/img/analysis/svedea.jpg" alt="Bild på Svedea hemsida"><br>
<h4>IF</h4>

<img src="../assets/img/analysis/if.jpg" alt="Bild på IF hemsida"><br>
</p>
<br>
<h3>Metod</h3>
<p>
För att analysera dessa sidors laddningstid använder jag mig utav ett verktyg som heter Google Pagespeed. Denna sida ger än ett övergripande prestationspoäng på sidan som man valt att analysera. Man får även ut mätvärden från några specifika områden som detta verktyg testar för att få fram prestandan på sidan.
<br>
Jag använde mig även utav LibreOffice Calc för att sammanställa all data som jag fick av Google Pagespeed på de webbsidor jag valt att analysera.
</p>
<br>
<h3>Resultat</h3>
<a href="%base_url%/assets/doc/laddningstid-analys2.pdf" target="_blank">Resultat</a>
<br><br>
<p>
På Google Pagespeed ger den tips på IF:s hemsida att bland annat ta bort resurser som blockerar renderingen, läs in viktiga resurser i förväg och ta bort oanvänd CSS. Om man kollar på förslaget med att ta bort resurser som blockerar renderingen, där uppskattar Google Pagespeed att IF skulle kunna spara in 0,94 sekunder. Vilket skulle göra väldigt stor skillnad. Kollar man på förslaget med att läsa in viktiga resurser i förväg kan de spara in 0,8 sekunder även på denna del samt om de skulle ta bort oanvänd CSS skulle de kunna spara 0,72 sekunder. Lägger man ihop dessa har man hela 2,46 sekunder som IF skulle kunna spara in på onödiga rader kod som bara ligger och drar ner prestandan.
<br><br>
På Svedeas sida ger Google Pagespeed tips om att bland annat även här ta bort resurser som blockerar renderingen och ta bort oanvänd CSS. Om Svedea skulle ta bort sina resurser som blockerar renderingen skulle det spara hela 0,83 sekunder samt om de tar bort oanvänd CSS skulle det spara dem 0,6 sekunder. Lägger man ihop denna tid skulle Google Pagespeeds tips kunna spara Svedea 1,43 sekunder.
<br><br>
Kollar man på Folksams sida ger Google Pagespeed tips om att bland annat ta bort Javascript som inte används och även här ta bort resurser som blockerar renderingen. Båda dessa tips skulle kunna spara 0,4 sekunder vardera om man åtgärdade. Det är hela 0,8 sekunder som onödig kod drar ner på Folksams prestanda.
</p>
<br>
<h3>Analys</h3>
<p>
Som man kan se i resultat dokumentet så ligger alla sidorna väldigt nära varandra när det kommer till laddningstid, poäng samt hur "bra" sidorna är på dess mobilversion.
<br><br>
Något som alla sidorna har gemensamt är att de mer eller mindre har massa onödiga resurser som blockerar renderingen och därmed drar ner prestandan väldigt mycket för sidorna. Detta är något som skulle vara bra för dem att kolla på och fixa, då på IFs sida utgör denna del hela 0,94 sekunder vilket kan göra en väldigt stor skillnad. Svedea och IF har båda CSS kod som inte används någonstans i koden, vilket bara är onödig kod att ha samt, beroende på hur mycket det rör sig om, även drar ner prestandan för dess sida.
<br><br>
Detta skulle man kunna göra en liknelse till på Folksams sida som har Javascript kod som inte används på något sätt. Även detta är väldigt onödig kod då den inte bidrar med något syfte och kräver bara mer för datorn att läsa vilket drar ner prestandan för hela sidan.
<br><br>
Om jag själv skulle välja vill jag gärna inte att det ska ta mer än 2-3 sekunder att komma in på en hemsida. Skulle det gå över till 4 sekunder eller mer skulle jag tycka att det går mer långsamt att komma in på sidan i fråga.
<br><br>
Kollar man på sidorna som jag valt skulle jag ranka dem med Folksam först, på plats 2 ligger IF samt sist Svedeas sida. Jag rankade dem på detta sätt på grund utav att Folksam är den snabbaste sidan av de alla, samt så har Folksam det bästa prestanda värde av de alla 3. Folksams sida har även inte så jätte mycket som den fick tips på att behöva åtgärda för att förbättra sin laddningstid. De har samlagt 2 saker som skulle kunna generera 0,8 sekunder.
<br><br>
IF fick landa på plats nr 2 då dess sida har näst snabbast laddningstid samt så laddar de inte in så väldigt många resurser, vilket både Folksam och Svedea har betydligt fler av. Dock har IF flest tips, hela 5 st, på hur de skulle kunna förbättra sin prestanda och totalt låg dessa tillsammans på hela 3,01 sekunder som de skulle kunna spara in på onödig kod i dess hemsida. Men trots att de har all denna onödiga kod ligger de ändå inte sist på laddningstiden men det drar ner dess prestanda värde till plats nr 2 av de alla 3 sidorna.
<br><br>
Svedea fick där med landa på plats nr 3 då de har sämst prestanda värde, längsta laddningstid samt laddar in flest antal resurser.
<br><br>
Alla 3 sidorna går ändå in under min satta gräns på 2-3 sekunder. Svedea som har längsta laddningstiden ligger på ett snitt av 2,24 sekunder vilket inte alls är särskillt lång tid enligt mig. Så allt som allt tycker jag inte att man märker av dessa millisekunder då det rör sig om ett span på snabbaste sidan på 2,1 sekunder till den långsamaste på 2,24 sekunder. Alla sidorna är snabba när man är inne på dem och navigerar sig runt på dess olika sidor.
</p>
<br>
<h3>Referenser</h3>
<p>
<a href="https://www.folksam.se/">Folksam</a>
<br>
<a href="https://www.svedea.se/">Svedea</a>
<br>
<a href="https://www.if.se/privat">IF</a>
<br>
<a href="https://developers.google.com/speed/pagespeed/insights/">Google Pagespeed</a>
</p>
<br>
<h3>Övrigt</h3>
<p>
Skriven av Daniella Forslund.
</p>
</div>
