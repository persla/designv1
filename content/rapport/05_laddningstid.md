---
---

# Prestanda hos svenska nyhetssajter
Detta innehåll är skrivet i markdown och du hittar innehållet i filen `content/rapport/05_laddningstid.md`.
## Syfte

Syftet med den här rapporten är att analysera prestandan hos ett urval av svenska nyhetssajter


## Urval

Orsaken till studiens fokus på nyhetssajter är deras centrala funktion i en demokrati som en förmedlare av nyheter, debatt och en försvarare av det fria ordet. Detta gör att det har en stor betydelse att medborgarna går in på dessa sidor och stannar kvar för att ta del av innehållet. Där har laddningstiden betydelsefull funktion, eftersom undersökningar visar att viljan att stanna kvar på en webbplats har en signifikant korrelation med den tid det tar för en sida att ladda och bli tillgänglig för besökaren. Ju längre tid den tar ju större sannolikhet är det att användaren går vidare till en annan webbplats.[1]

Följande nyhetssajter har valts ut som objekt i denna studie:



1. Aftonbladet
2. DN
3. Expressen

Urvalet är baserat på idgs.se topplista över Sveriges bästa sajter och nättjänster 2019 där dessa sajter hamnar på topp tre i kategorin nyheter enligt rangordningen ovan. Bedömningen är gjord utifrån design, tillgänglighet och antalet  unika besökare. Dessa tre nyhetssajters framträdande roll i det digitala mediebruset gör att de har en central funktion för den svenska demokratin, och därmed är det betydelsefullt och intressant att studera hur mycket resurser som krävs för att rendera sidans innehåll och hur lång tid det tar för sidan att bli tillgänglig för användaren.


## Metod

För att uppnå studiens syfte har följande har fem olika mått använts enligt nedanstående definition:


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
   <td><strong>Betyg/Mobil</strong>
   </td>
   <td><strong>Betyg/desktop</strong>
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
   <td>Betygsättning av webbsidan utifrån mobil på PageSpeed Insights
   </td>
   <td>Betygsättning av webbsidan utifrån desktop på PageSpeed Insights
   </td>
  </tr>
  <tr>
   <td><strong>Mått</strong>
   </td>
   <td>Tid i sekunder
   </td>
   <td>Antal
   </td>
   <td>Mb
   </td>
   <td>Betygsskala 0-100
   </td>
   <td>Betygsskala 0-100
   </td>
  </tr>
  <tr>
   <td><strong>Verktyg</strong>
   </td>
   <td>Devtools - Network
   </td>
   <td>Devtools - Network
   </td>
   <td>Devtools - Network
   </td>
   <td>PageSpeed Insights
   </td>
   <td>PageSpeed Insights
   </td>
  </tr>
</table>


Samtliga parametrar har mätts tre gånger på olika sidor på respektive nyhetssajt(hemsidan, sportsektionen och kulturdelen) för att få en mer heltäckande bild av webbplatsens rendering. Resultatet presenteras som ett genomsnitt av dessa mätningar. En av studiens utmaning var att hantera nedladdningstiden och antalet resurser. Det visade sig att dessa nyhetssajter har en kontinuerlig laddning och blir aldrig riktigt “färdigladdade”. Detta orsakas framförallt av den omfattande förekomsten av rörliga reklaminslag på respektive nyhetssajt. För att hantera denna utmaningen har den första fullständiga renderingen använts som utgångspunkt för mätningarna i devtools.

Samtliga mätningar är gjorda i webbläsaren Chrome och studiens rådata finns tillgängligt [här](https://docs.google.com/spreadsheets/d/1AsjAWGirPjgnjzF5oFw6OLZVbsz2jbWSJvuTpR4JGMs/edit?usp=sharing).


## Resultat

Nedan kommer studiens resultat presenteras i form av en tabell som visar medelvärdet av de olika indikatorerna
för respektive webbplats samt för samtliga objekt.

Bild på webbplatserna
[FIGURE caption="dn.se" src=image/dn1.png?w=180 class="right"]
[FIGURE caption="expressen.se" src=image/expressen1.png?w=180 class="right"]
[FIGURE caption="aftonbladet.se" src=image/aftonbladet1.png?w=180 class="right" ]



<table>
  <tr>
   <td><strong>Webbplats</strong>
   </td>
   <td><strong>Tid</strong>
   </td>
   <td><strong>Resurser</strong>
   </td>
   <td><strong>Storlek</strong>
   </td>
   <td><strong>Betyg/Mobil</strong>
   </td>
   <td><strong>Betyg/desktop</strong>
   </td>
  </tr>
  <tr>
   <td>Aftonbladet
   </td>
   <td><p style="text-align: right">
<em>6,7</em></p>

   </td>
   <td><p style="text-align: right">
<em>142</em></p>

   </td>
   <td><p style="text-align: right">
<em>7,2</em></p>

   </td>
   <td><p style="text-align: right">
<em>33</em></p>

   </td>
   <td><p style="text-align: right">
<em>56</em></p>

   </td>
  </tr>
  <tr>
   <td>Expressen
   </td>
   <td><p style="text-align: right">
<em>6,7</em></p>

   </td>
   <td><p style="text-align: right">
<em>220</em></p>

   </td>
   <td><p style="text-align: right">
<em>3,3</em></p>

   </td>
   <td><p style="text-align: right">
<em>66</em></p>

   </td>
   <td><p style="text-align: right">
<em>86</em></p>

   </td>
  </tr>
  <tr>
   <td>DN
   </td>
   <td><p style="text-align: right">
<em>7,1</em></p>

   </td>
   <td><p style="text-align: right">
<em>76</em></p>

   </td>
   <td><p style="text-align: right">
<em>2,7</em></p>

   </td>
   <td><p style="text-align: right">
<em>74</em></p>

   </td>
   <td><p style="text-align: right">
<em>88</em></p>

   </td>
  </tr>
  <tr>
   <td><strong><em>Medelvärde</em></strong>
   </td>
   <td><p style="text-align: right">
<strong><em>6,8</em></strong></p>

   </td>
   <td><p style="text-align: right">
<strong><em>146</em></strong></p>

   </td>
   <td><p style="text-align: right">
<strong><em>4,4</em></strong></p>

   </td>
   <td><p style="text-align: right">
<strong><em>58</em></strong></p>

   </td>
   <td><p style="text-align: right">
<strong><em>77</em></strong></p>

   </td>
  </tr>
</table>


Samtliga undersökta objekts laddningstid ligger inom ett tidsspann mellan 6,7 och 7,1 sekunder. Antalet resurser som krävs för att rendera sidorna är spridd, expressen har flest med 220 medans DN har 76 och Aftonbladet ligger där emellan. Storleken på webbsidan är också divergerande mellan DNs 2,7 och nästa det tredubbla för Aftonbladet. Gemensam nämnare för samtliga undersökta webbsidor är att de tenderar ha högre betyg på PageSpeed Insights när det gäller desktop än mobil. Störst är skillnaden hos Aftonbladet och minst hos DN.  Betygen varierar signifikant, från Aftonbladets mobilabetyg 33 till DNs desktopbetyg på 88.


## Analys

Utifrån studiens resultat kan det konstateras att de största nyhetssajterna i Sverige renderar långsamt, vilket gör att det tar lång tid för användaren att få tillgång till fullständig interaktivitet på webbsidan, vilket i sin tur riskerar att besökarna tar sig vidare till sidor som har en snabbare nedladdningstid, vilket på sikt riskerar urholka demokratin. Detta gäller inte minst ungdomar som tenderar att snabbt gå vidare om inte sidorna responderar på ett snabbt och effektivt sätt.

Den enskilt största faktorn bakom denna långa nedladdningstid är de resurskrävande reklaminslagen på nyhetssajterna. För att kunna driva en nyhetssajt krävs det inkomster och eftersom tiden för prenumerationer är förbi (även om det finns betalningstjänster på sajterna) är nyhetstjänsterna hänvisade till reklamintäkter som huvudsaklig finansieringskälla och därmed riskera man att hamna i en ond cirkel, där reklaminslagen blir mer och mer  resurskrävande med ökade nedladdningstider som följd och risken för att de lättrörliga besökarna flyr ökar.

Ett annat intressant resultat från studien är de relativt låga betygen från PageSpeed Insights när det gäller mobilprestanda. Där den långa nedladdningstiderna är den största enskilt förklarande faktorn. Aftonbladet är sämst i klassen och får underkänt med ett snittbetyg på 33. Men även de andra får kritik och har stora utmaningar för att behålla besökarna, där ungdomarna är en stor grupp som uteslutande använder mobilen för att ta del  av nyheter. Utifrån studiens resultat är det relevant att väcka frågan om dessa medieföretag har hör talas om mobile first design.

Viktigt att nämna är att trots studiens resultat där Aftonbladet prestera sämst bland de undersökta objekten så är det den populäraste källan till nyheter bland ungdomar enligt ungdomsbarometern[2]. På grund av denna studies begränsade omfattningen så kommer orsakerna till detta fenomen inte analyseras närmare, men det kan vara ett intressant tema att undersöka vidare i en annan studie.

För att öka effektiviteten gällande renderingen kan nyhetssajter kan de göra följande:



1.  Ändra bildformatet till text WebP som ofta ger bättre komprimering än PNG eller JPEG. Det gör att nedladdningen går snabbare och ger minskad dataförbrukning. Använd även bilder med rätt storlek.
2. Låt dolda bilder läsas in med lat inläsning efter att alla viktiga resurser är inlästa så att tiden till interaktivt tillstånd minskar.
3.  Minska tiden det tar att tolka, kompilera och köra JS-kod. Det brukar hjälpa att minska storleken på JS-resurserna som skickas.
4.  Ta bort oanvänd CSS.Ta bort regler som inte används från formatmallar och skjut upp inläsning av CSS som inte används för innehåll ovanför mitten för att minska onödig nätverksaktivitet.

Min rangordning baseras i huvudsak på betygen på PageSpeed Insights eftersom tidsaspekten bland objekten är i stort sett densamma. DN hamnar på första plats eftersom den har de högsta betyget både när det gäller mobil och desktop på PageSpeed Insights på andra plats hamnar Expressen som har de näst bästa betygen och sist hamnar Aftonbladet framförallt beroende på deras låga betyg för mobil.

Idealt vore om en nyhetssajt skulle laddas på 2-3 sekunder så att användaren snabbt får tillgång till hela sidan både på desktop och mobil, där har de olika objekten mycket kvar att arbeta med för att uppnå den prestandan. Det är emellertid nödvändigt att de arbetar med det fortlöpande för att nyhetsflödet på nätet ska vara lättillgängligt för användare.


## Referenser

[1][https://unbounce.com/landing-pages/7-page-speed-stats-for-marketers/](https://unbounce.com/landing-pages/7-page-speed-stats-for-marketers/)

[2][https://www.aftonbladet.se/nyheter/a/5VoxnO/aftonbladet-framsta-nyhetskallan-bland-sveriges-unga](https://www.aftonbladet.se/nyheter/a/5VoxnO/aftonbladet-framsta-nyhetskallan-bland-sveriges-unga)


## Övrigt

Författare Lars Persson
