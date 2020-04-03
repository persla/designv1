---
---

# Analys av gymnasieskolors webbplatser i Stockholm utifrån ett desktop- och mobilläge


## Syfte

Syftet med den här rapporten är att analysera gymnasieskolors webbplatser i Stockholm utifrån ett desktop- och mobilläge gällande prestanda och design förändringar.

## Introduktion
Denna rapport utgör den andra delstudien av gymnasieskolors digitala plattformar. Det första undersökningen studerade skolornas webbplatser utifrån design och vilka trender som kan skönjas inom detta område när det gäller de undersökta objekten. Hela den rapporten finns tillgänglig under länken rapporter/kmom09-webbplatsdesign med titeln, “Analys av aktuell webbdesign hos gymnasieskolor i Stockholm”.
Bägge studierna utgår ifrån samma undersökta objekt och de intressenter som besöker webbplatserna utifrån, med det menas högstadieungdomar och deras föräldrar som besöker webbplatsen med syfte att bilda sig en bild av skolan och avgöra om det är ett intressant och relevant utbildningsalternativ.
Föreliggande studies fokus på design, prestanda och funktionalitet utifrån desktop- och mobilläge är relevant och intressant att studera eftersom ungdomar i sin strävan att söka efter information sker i till övervägande majoritet på mobilen. Därför blir förhållandet mellan desktop- och mobilläge intressant att undersöka närmare eftersom är skillnaderna stora kan det påverka beslutsunderlaget för eleverna när det väljer vilken gymnasieskola de ska gå på. Där är även prestandan och funktionaliteten av central betydelse, till exempel kan en lång nedladdningstid påverka intresset för webbplatsen, om den är bristfällig ur tillgänglighetssynpunkt kan de riskera att förlora presumtiva elever och om det finns brister i funktionaliteten som gör att webbplatsen inte renderas på ett korrekt sätt.

## Forskningsfrågor

Syftet med rapporten ska uppfyllas genom följande frågeställningar:

1. Vilken prestanda uppvisar webbplatserna i desktop- respektive mobilläge?

2. Vilka betyg och synpunkter får webbplatserna av testverktygen Lighthouse och PageSpeed Insights?

3. I vilken utsträckning påverkas designen på webbplatserna av att gå från desktop- till mobilläge?

## Urval
Orsaken till studiens fokus på webbplatser för gymnasieskolan är det fria skolvalet som har inneburit i praktiken att utbildning idag utgör en marknad och eleverna kunder som tar sin kommunala skolpeng med sig dit de väljer att studera. Det innebär att skolorna måste på något sätt marknadsföra sin verksamhet och där har webben en central funktion för att nå ut till blivande elever.
För att få ett tydligt fokus i studien har gymnasieskolor i Stockholm valts ut som har likartad programutbud. Dessutom finns både fristående och kommunala huvudmän med i studien. Detta har som syfte att skapa en så heltäckande bild som möjligt i denna begränsade studie.


Utifrån dessa aspekter har följande webbplatser valts ut i studien:

[Thorildsplans gymnasium(kommunal)](https://thorildsplansgymnasium.stockholm.se/).

[Södra Latins gymnasium(kommunal)](https://sodralatinsgymnasium.stockholm.se/).

[Affärsgymnasiet(fristående)](https://affarsgymnasiet.se/har-finns-vi/stockholm-2/).

[International IT College of Sweden(fristående)](https://initcollege.se/).


## Metod

För att uppnå studiens syfte har följande har sex olika mått använts enligt nedanstående definition:


<table>
  <tr>
   <td><strong>Kategori</strong>
   </td>
   <td><strong>Tid</strong>
   </td>
   <td><strong>Resurser</strong>
   </td>
   <td><strong>Storlek</strong>
   </td>
   <td><strong>Tillgänglighet</strong>
   </td>
   <td><strong>Bästa praktik</strong>
   </td>
   <td><strong>SEO</strong>
   </td>
  </tr>
  <tr>
   <td><strong>Definition</strong>
   </td>
   <td>Den tid det tar innan sidan är fullständigt interaktiv.
   </td>
   <td>Antal resurser som laddas för att rendera sidan
   </td>
   <td>Webbsidans totala storlek
   </td>
   <td>Betyg på webbsidans tillgänglighet Google Lighthouse
   </td>
   <td>Betyg på webbsidan
utifrån bästa praktik Google Lighthouse
   </td>
   <td>Betyg på webbsidan utifrån SEO Google Lighthouse
   </td>
  </tr>
  <tr>
   <td><strong>Mått</strong>
   </td>
   <td>Tid i sekunder/
(Betygsskala 0-100)
   </td>
   <td>Antal
   </td>
   <td>Mb
   </td>
   <td>Betygsskala 0-100
   </td>
   <td>Betygsskala 0-100
   </td>
   <td>Betygsskala 0-100
   </td>
  </tr>
  <tr>
   <td><strong>Verktyg/indikator</strong>
   </td>
   <td>Webb/
PageSpeed Insights
   </td>
   <td>Konsol/
Network/
requests
   </td>
   <td>Konsol/
Network/
resources
   </td>
   <td>Konsol/
Audits/
Lighthouse/
Accessibility
   </td>
   <td>Konsol/
Audits/
Lighthouse/
Best Practices
   </td>
   <td>Konsol/
Audits/
Lighthouse/
SEO
   </td>
  </tr>
</table>


Samtliga parametrar har mätts tre gånger  på respektive webbplats för att få en mer heltäckande bild av webbplatsens rendering. Resultatet presenteras som ett genomsnitt av dessa mätningar. Mätningarna är gjorda med tre mätverktyg PageSpeed Insights som är webbaserat, Network och Lighthouse som har använts utifrån konsolen. Från PageSpeed Insights har indikatorn tid till interaktivt tillstånd valts ut eftersom den tid det tar att rendera en sida är en betydelsefull faktor för uppfattningen om en webbplats. Från konsolens network har antalet resurser som krävs för att rendera sidan och webbsidans totala storlek valts ut som indikatorer eftersom de påverkar en webbsidas prestanda. Från lighthouse har följande indikatorer används, tillgänglighet som har till syfte att bedöma om webbplats är tillgänglig för och har förutsättningar att användas av alla människor, bäst praktik som undersöker hur väl webbplatskoden harmoniserar med rådande kodstandard och SEO som bland annat indikerar hur optimerad webbplats är för att kunna rankas bra i sökmotorer och hur mobilvänlig den är. Samtliga tid, tillgänglighet och SEO har både mätts i mobil- och desktopläge för att få ett jämförelsematerial med syfte att uppnå besvara rapportens frågeställningar.

Samtliga mätningar är gjorda i webbläsaren Chrome.

Metoden för att bedöma designens påverkan mellan de olika lägena har baserats på en bedömning av designelement utifrån desktop läget och därefter har eventuella skillnader identifierats vid övergången till mobilläge. Skärmklipp på webbplatserna i desktop- respektive mobilläge kommer att presenteras i resultatet.

## Resultat
Här nedan presenteras studiens resultat under två rubriker, Prestanda och Design desktop vs. mobil.

### Prestanda
Nedan kommer studiens mätvärden presenteras i form av en tabell som visar medelvärdet av de olika indikatorerna.


<table>
  <tr>
   <td><strong>Webbplats</strong>
   </td>
   <td><strong>Tid</strong>
<strong>desk(mobil)
/betyg</strong>
   </td>
   <td><strong>Resurser</strong>
   </td>
   <td><strong>Storlek</strong>
   </td>
   <td><strong>Tillgänglighet</strong>
<strong>desk(mobil)</strong>
   </td>
   <td><strong>Bästa praktik</strong>
<strong>desk(mobil)</strong>
   </td>
   <td><strong>SEO</strong>
<strong>desk(mobil)</strong>
   </td>
  </tr>
  <tr>
   <td><strong>Thorildsplans gymnasium</strong>
   </td>
   <td>2,6s(11,5s)/
88(42)
   </td>
   <td>66
   </td>
   <td>7.8 MB
   </td>
   <td>89(89)
   </td>
   <td>64(71)
   </td>
   <td>82(83)
   </td>
  </tr>
  <tr>
   <td><strong>Södra Latins gymnasium</strong>
   </td>
   <td>1,1s (7,2s)/
96(64)
   </td>
   <td>61
   </td>
   <td>1.9 MB
   </td>
   <td>89(88)
   </td>
   <td>64(64)
   </td>
   <td>82(84)
   </td>
  </tr>
  <tr>
   <td><strong>International IT College</strong>
   </td>
   <td>2,8s (16.9s)/
66(10)
   </td>
   <td>78
   </td>
   <td>5.5 MB
   </td>
   <td>80(80)
   </td>
   <td>71(71)
   </td>
   <td>100(99)
   </td>
  </tr>
  <tr>
   <td><strong>Affärsgymnasiet</strong>
   </td>
   <td>1,1s (15,5s)/
74(20)
   </td>
   <td>127
   </td>
   <td>5.0 MB
   </td>
   <td>87(90)
   </td>
   <td>71(71)
   </td>
   <td>82(77)
   </td>
  </tr>
  <tr>
   <td><strong>Medelvärde</strong>
   </td>
   <td>1,9s(12,8s)/
81(34)
   </td>
   <td>83
   </td>
   <td>5.0 MB
   </td>
   <td>86(87)
   </td>
   <td>68(69)
   </td>
   <td>87(86)
   </td>
  </tr>
</table>

Utifrån värdena i tabellen går det att utläsa att samtliga webbplatser renderas relativt snabbt i desktopläge. I tabellen går det också att konstatera att den tiden till interaktivt tillstånd varierar mellan desktop- och mobilläge på samtliga webbplatserna. Störst är skillnaden hos affärsgymnasiet där mobilläget är 15 gånger långsammare och minst är den på Södra Latins webbplats med en tidsdifferens på 6 sekunder. Trots den relativt snabba tiden till interaktivt tillstånd i desktopläge får alla utom södra latin, som får toppbetyg, medelbetyg när det gäller prestanda eftersom PageSpeed Insights även tar hänsyn till andra tidsaspekten i sin bedömning. Dessa betyg är särskilt alarmerande i mobilläge hos International IT College och Affärsgymnasiet som får klart underkänt på sin prestanda.  Märverktyget påpekar bland annat att bildstorlekarna och bildformaten är det stora problemet och gör att det tar tid för webbsidorna att rendera.

Antalet request som behövs för att ladda resurserna är relativt likartade hos de undersökta objekten. Den enda som avviker signifikant från mönstret är Affärsgymnasiet med nästan dubbelt så många request som medelvärdet för samtliga webbplatser.

När det gäller storleken på webbplatsen är bilden något spretigt där International IT College och Affärsgymnasiet har en storlek på ca 5 mb medans södra latin webbplats endast består 1,5 mb och Thorildsplans som är störst med  7,8 mb.

Tillgängligheten på samtliga webbplatser får klart godkänt både i mobil- och desktopläge. Det är endast International IT College som avviker med något lägre betyg. Lighthouse påpekar bland annat att den webbsidan inte har formelement med tillhörande etiketter, att länkar inte har signifikanta  namn och att bilderna inte har några alt attribut.

När det gäller bästa praktik så får samtliga webbplatser godkänt dock med det lägsta betygen i jämförelse med de andra betygsatta parametrarna på Lighthouse. Samtliga webbplatser får påpekande såsom länkar till cross-origin destinationer är inte säkra, att webbsidan inkluderar front-end JavaScript bibliotek med kända säkerhetsproblem och problem med https och http requests.

Betygen på SEO är klart godkänt för samtliga och där har vi undersökningens enda 100 poängare i from av International IT Colleges webbplats. De övriga får påpekande såsom att de saknar meta beskrivningar och att bilder saknar alt attribut.

### Design desktop vs. mobil
**Thorildsplans gymnasium**
[FIGURE caption="Thorildsplans gymnasium - desktop" src=image/theme/torhild.png&w=300&h=500&crop-to-fit&area=0,0,50,0&save-as=jpg&q=90&sharpen class="left"]
[FIGURE caption="Thorildsplans gymnasium - mobil" src=image/theme/mobil_gy/thorhild_mobil.png&w=300&h=500&save-as=jpg&q=90&sharpen ]

Header och navigeringen varierar mellan desktop och mobil. Där mobilläget har en klassisk hamburgermeny och  sökfunktion samt genvägar till innehållet på webbplatsen medans desktopläget visar en navbar med länkarna till webbplatsens olika delar. Stockholms Stads logga som är tydligt exponerad i desktopläget döljs i mobilläget. Flash-regionen har samma slide baserade bildinnehåll i bägge formaten. På desktop kan man se att webbplatsens main-del består av tre kolumner som sedermera  stackas från vänster till höger när man övergår till mobilt läge. Samma färgpalett används i bägge lägena.


**Södra Latins gymnasium**
[FIGURE caption="Södra Latins gymnasium - desktop" src=image/theme/sodralat.png&w=300&h=500&crop-to-fit&area=0,0,50,0&save-as=jpg&q=90&sharpen class="left"]
[FIGURE caption="Södra Latins gymnasium - mobil" src=image/theme/mobil_gy/latin_mobil.png&w=300&h=500&save-as=jpg&q=90&sharpen ]

I mobilläget på Södra Latins webbplats syns högst upp  genvägar till webbplatsens olika delar, en sökfunktion samt en klassisk hamburgermeny för länkar. I desktopläget finns en navigering med visuella länkar både internt inom webbplatsen och externt. I headern finns också en logga som saknas på den mobila skärmen. På desktop visas huvudinnehållet i två kolumner och på mobilen stackas de på varandra, där den vänstra kolumnens innehåll hamnar överst i flödet. Bildspelet i flash-regionen och färgschemat är samma för bägge skärmstorlekarna.

**Affärsgymnasiet**
[FIGURE caption="Affärsgymnasiet - desktop" src=image/theme/affarsgy.png&w=300&h=500&crop-to-fit&area=0,0,60,0&save-as=jpg&q=90&sharpen class="left" ]
[FIGURE caption="Affärsgymnasiet - mobil" src=image/theme/mobil_gy/affars_mobil.png&w=300&h=500&save-as=jpg&q=90&sharpen ]

Affärsgymnasiet framhäver sin logga högst upp i det mobila läget och den efterföljande navigeringen är en kombination mellan hamburgermeny och klickbara skroll listor medans desktop navigeringen har ett betydligt mer begränsat utrymme där loggan är mycket diskretare. På desktop är flash regionen bildrik medans den är betydligt anonymare på mobilen och det endast innehåller två bilder. Färgskalan bibehålls i övergången från desktop till mobil skärm. På det mobila enheten kan man längst ned innan man behöver scrolla(before the fold) finna en klickbar länk där det finns möjlighet att ta kontakt med skolan.

**International IT College of Sweden**
[FIGURE caption="International IT College of Sweden - desktop" src=image/theme/intcollege.png&w=300&h=500&crop-to-fit&area=0,0,60,0&save-as=jpg&q=90&sharpen class="left"]
[FIGURE caption="International IT College of Sweden - mobil" src=image/theme/mobil_gy/it_mobil.png&w=300&h=500&save-as=jpg&q=90&sharpen ]

I desktopläge består International IT College of Swedens header av en diskret logga och navigering till webbplatsens olika delar medans loggan lyfts fram på en central plats i mobilt läge och navigeringen består av en hamburgermeny. I desktop formatet består flash-regionen av en gruppbild och i mobilen visas en croppad sektion av samma bild. Färgpaletten bibehålls i bägge formaten. Den tvådelade kolumn indelningen i desktop stackas i mobilen. Samtliga element som finns på desktop återfinns också i det mobila läget.

## Slutsatser
Utifrån studiens resultat kan det konstateras att samtliga de undersökta webbplatserna snabbt kommer till ett interaktivt tillstånd vid desktopläge och besökaren kan på så sätt använda sig av webbplatsen efter ett kort tidsintervall. Tiderna ökar och betygen på prestanda sjunker dock signifikant när mätningarna görs i mobilläget, särskilt när det gäller friskolorna där bilder och olika designelement fördröjer laddningen betydligt mer än hos de kommunala aktörerna med deras  mer begränsade design.

Vidare kan det konstateras att tillgängligheten på majoriteten av webbplatserna är god och de synpunkter som framkom från mätverktygen är relaterat till otydliga element beskrivningar vilket påverkar informationen för de med nedsatt syn som får webbsidan uppläst för sig. När det gäller bästa praktik får samtliga webbplatser godkänt och erinranden som de får från mätverktyget är relaterade till externa resurser som kan leda till sårbarheter av olika slag. Vidare går de också konstatera att webbplatserna är någorlunda sökoptimerade och anpassade till mobilläge, dock saknar några av dessa meta attribut vilket kan höja antalet träffar vid en googlesökning.

I studien har det även framkommit att samtliga undersökta objekt använder sig av en hamburgermeny i mobilläge som navigering och en navbar i desktopläge. Alla använder sig av en flash-region med bilder för bägge skärmstorlekarna. Hos friskolorna varierar dock bilderna mellan de olika skärmarna. Friskolorna lyfter även fram sin logga i det mobila läget medans hos de kommunala visas den inte. Samtliga webbplatser behåller sin färgpalett i växlingen mellan skärmstorlekarna och använder sig av stackning av webbplatsens innehåll i det mobillaläget.

Sammanfattningsvis kan det konstateras att mobilen fungerar väl och ger en fullgod insikt och uppfattning för ungdomar om de olika skolorna i förhållande till vad som visas i laptopläget. Dock är prestandan sämre och designen betydligt mer kompakt vilket kan begränsa möjligheterna att få en komplett bild av verksamheten utifrån ett digitalt perspektiv. Således är det att föredra en undersökning av skolorna utifrån bägge skärmstorlekarna för att få en känsla för och bilda sig en uppfattning om de olika utbildningsalternativen för ungdomar och deras föräldrar.

## Övrigt

Författare Lars Persson
