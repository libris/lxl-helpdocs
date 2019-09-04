---
section: Materialtyper
title: Musik-CD
order: 48
date: 2019-09-04
tags:
- under arbete
- musik-CD
- ljudinspelning
--- 

## Musik-CD - ljudinspelning 
Beskrivningen av en musik-CD innehåller följande tre delar:  
* [Adminmetadata](https://libris.kb.se/katalogisering/help/workflow-adminmetadata) - administrativa data om instansbeskrivningen, såsom kontrollnummer och beskrivningsnivå
* [Instans](https://libris.kb.se/katalogisering/help/workflow-instance) - instans kan också kallas utgåva eller manifestation. Exempel på egenskaper under Instans är utgivningsplats, utgivare och utgivningsår, bärartyp, omfång.
* [Verk](https://libris.kb.se/katalogisering/help/workflow-work) – återger egenskaper för det abstrakta verket såsom medverkan och funktion (t.ex. författare), ämne, klassifikation, språk och innehållstyp. Verksbeskrivningen ligger under rubriken Instans av verk.

Denna hjälptext ger kortfattade instruktioner för de vanligaste egenskaperna för musik-CD. För utförliga instruktioner, se de generella hjälptexterna för Adminmetadata, Instans och Verk, se ovan.

Många av egenskaperna finns redan i mallen Musik-CD - ljudinspelning, andra kan behöva läggas till. För instruktioner om att lägga till eller ta bort egenskaper, länka till entitet, skapa lokal entitet och om hur formuläret fungerar i övrigt, se Redigering i vänstermenyn. För en förhandspost, använd gärna Berika från mall och välj Musik-CD.

För information om katalogregler och Librispraxis, se [Anvisningar för katalogisering - RDA](https://www.kb.se/rdakatalogisering/ "Anvisningar för katalogisering - RDA"). samt [RDA Toolkit](https://access.rdatoolkit.org/).

I de flesta fall ska informationen delas upp i olika egenskaper (jfr fält) och underliggande egenskaper (jfr delfält). I några undantagsfall är det nödvändigt att använda ISBD-interpunktion inom en egenskap, för att separera uppgifter. Dessa fall visas genom exempel nedan. I övriga fall, lägg INTE in ISBD-interpunktion för att avsluta en egenskap. Använd vid behov klamrar inom egenskap, enligt Anvisningar för katalogisering - RDA.

NOTERA att för utgivna fysiska ljudinspelningar (=fonogram) är hela den utgivna resursen godkänd källa. Uppgifterna får tas utan prioritetsordning från det ställe där de anses vara bäst. Denna Librispraxis, [KB SP 2.2.2.4.1](http://access.rdatoolkit.org/kbspchp2_kbsp2-51.html), bygger på IASA Cataloguing Rules och är en avvikelse från [RDA 2.2.2.4.1](http://access.rdatoolkit.org/rdachp2_rda2-2904.html).

Se även [instruktionsfilmer](https://www.youtube.com/playlist?list=PLZVkEICvA5-GRT2oJQmLgq_2Pksx6zYPy)  

### Innehåll  

| [Adminmetadata](#adminmetadata) | [Instans](#instans) | [Verk](#verk) | 
| ----------- |  ----------- | ----------- | 
|  [Generell hjälptext för Adminmetadata](https://libris.kb.se/katalogisering/help/workflow-adminmetadata) | [Generell hjälptext för Instans](https://libris.kb.se/katalogisering/help/workflow-instance) | [Generell hjälptext för Verk](https://libris.kb.se/katalogisering/help/workflow-work) |
| | [Utgivningssätt](#utgivningssatt) | [Verkets titel](#verkets-titel) |
| | [Medietyp](#medietyp) | [Relationer till ingaende verk och andra verk](#relationer-till-ingaende-verk-och-andra-verk) |
| | [Bärartyp](#barartyp) | [Medverkan och funktion](#medverkan-och-funktion) |
| | [Titel](#titel) | [Språk](#sprak)  |
| | [Upphovsuppgift](#upphovsuppgift) | [Genre](#genre) |
| | [Upplageuppgift](#upplageuppgift) | [Klassifikation](#klassifikation) |
| | [Utgivning](#utgivning) | [Målgrupp](#malgrupp)  |
| | [Copyright- eller p-år](#copyright-eller-p-ar) | [Innehållstyp](#innehallstyp) |
| | [Identifikator](#identifikator) | [Inspelning](#inspelning) | 
| | [Omfång](#omfang) | [Anmärkning om medverkande](#anmarkning-om-medverkande) |  
| | [Övriga fysiska detaljer](#ovriga-fysiska-detaljer) | [Sammanfattning av innehåll](#sammanfattning-av-innehall)  |
| | [Medföljande material](#medfoljande-material) | |
| | [Seriemedlemskap](#seriemedlemskap) | | 
| | [Innehållsförteckning](#innehallsforteckning) | | 
| | [Anmärkning](#anmarkning) | | 

### Instans
  För att lägga till egenskaper under Instans, klicka på plustecknet i redigeringsvyn (den stora runda plusikonen under Verktygsikonen - Lägg till egenskaper under: Instans). Sök fram egenskapen och välj den genom att klicka på plustecknet vid egenskapens namn.  

#### Utgivningssatt
  * Utgivningssätt (issuanceType)   
  Välj från lista.  
  ```Exempel: Monografisk resurs```
  
#### Medietyp
  * Medietyp (mediaType/Mediatype = 337 #b)  
  Länka till entitet.  
  ```Exempel: audio, s```
  
#### Barartyp
  * Bärartyp (carrierType/CarrierType = 338 #b)
  <br/>Välj Bärartyp i listan över typer. Länka till entitet.
  <br/>```Exempel: audio disc, sd```</BR>
  Om koden "d" (= ljudskiva) behövs i 007/01 (= särskild bärarbeteckning) för bibliotekets lokala system länka även till entiteten marc/SoundDisc.</BR>
  ```Exempel: marc/SoundDisc```
  
#### Titel
  Notera att egenskapen Allmän medieterm (marc:mediaTerm = 245 #h) (= Medieterm) inte ska ingå i beskrivningar som görs enligt RDA.

##### Huvudtitel    
  * Har titel/Titel/Huvudtitel (hasTitle/Title/mainTitle = 245 #a)  
  Återge huvudtiteln som den förekommer i källan, se [Librispraxis 2.2.2.4.1](http://access.rdatoolkit.org/kbspchp2_kbsp2-51.html).</BR> 
  ```Exempel: En schlager i Sverige```  
  För en titel som börjar med bestämd eller obestämd artikel, ska artikeln fileras bort. Ange fileringsvärde genom att lägga till fileringsvärde (plustecknet vid Titel - Lägg till egenskaper under: Titel) och ange en siffra.  
  ```Exempel: Huvudtitel: En schlager i Sverige, fileringsvärde: 3```  
  Se exempel i formathandboken för Libris/Voyager: 
[Fileringsindikator]( http://www.kb.se/katalogisering/Formathandboken/Fileringsindikator/)

  För att ange Föredragen titel, se Verk/Har titel/Titel/Huvudtitel.  

##### Övrig titelinformation (undertitel)
  * Har titel/Titel/Övrig titelinformation (= Undertitel) (hasTitle/Title/subtitle = 245 #b)  
  Skriv in uppgiften.  
  ```Exempel: original motion picture soundtrack```  
  Om det finns flera undertitlar, skriv in dem efter varandra i samma fält, åtskilda av mellanslag, kolon, mellanslag.  
  ```Exempel: fler progglåtar : rariteter för den inbitne samlaren```

##### Varianttitel   
  En varianttitel är en titel förknippad med resursen som skiljer sig från den titel som angivits som huvudtitel, se [RDA 2.3.6](http://access.rdatoolkit.org/rdachp2_rda2-4004.html). Här anges t.ex. varianter för titlar som innehåller specialtecken, siffror eller oväntade stavningar av ord</BR>
  För att lägga till varianttitel, klicka på plustecknet vid Har titel (lägg till titel) och välj typ Varanttitel.
  * Har titel/Varianttitel/Huvudtitel (hasTitle/VariantTitle/mainTitle = 246 #a)   
    Skriv in uppgiften under Huvudtitel.    
    ```Exempel: Live at M.```  

  För en huvudtitel på ett annat språk eller i en annan skriftart, se Parallelltitel nedan.

  Om huvudtiteln är felstavad i källan anges en korrekt form av titeln som en varianttitel. Notera dock att för utgivna fysiska fonogram är hela resursen godkänd källa, utan prioritetsordning, se [Librispraxis 2.2.2.4.1](http://access.rdatoolkit.org/kbspchp2_kbsp2-51.html). Det innebär att man vanligen kan hitta en korrekt form av titeln och ange den som huvudtitel.

  En varianttitel kan specificeras med en Typanmärkning, en anmärkningstext som i ett sökgränssnitt ska föregå varanttiteln. För att lägga till en Typanmärkning, klicka på plustecknet vid Varianttitel (Lägg till egenskaper under: Varianttitel) och välj Typanmärkning.

  * Har titel/Varianttitel/Typanmärkning (hasTitle/VariantTitle/typeNote = 246 1/_ #i)  
  ```Exempel: Titeln felstavad, korrekt titel:```   
    
##### Delbeteckning och deltitel
  För anvisningar om hur man anger delbeteckning och deltitel, se hjälptexten [Instans](https://libris.kb.se/katalogisering/help/workflow-instance#titel) under rubriken Titel. 

##### Parallelltitel  
  Ange parallelltitel här. Upprepa inte parallelltitel efter Har titel/Titel/Huvudtitel (245 #a) med interpunktion.   
  * Har titel/Parallelltitel/Huvudtitel (hasTitle/ParallelTitle/mainTitle = 246 1/1 #a)   
  Välj först Har titel, välj sedan typ Parallelltitel.  
  Skriv in uppgiften under Huvudtitel.     
  ```Exempel: The doors of death, fileringsvärde: 4```  
  * Har titel/Parallelltitel/Övrig titelinformation (hasTitle/ParallelTitle/subTitle = 246 1/1 #b)   
  Vid behov, lägg till Övrig titelinformation (subtitle) under Parallelltitel.   
  ```Exempel: for computer and soprano```  
  
#### Upphovsuppgift
  * Upphovsuppgift (responsibilityStatement = 245 #c)  
  Skriv in uppgiften.
  <br/>```Exempel:```
    * ```Pray for Locust```
    * ```Steve Dobrogosz, Anna Christoffersson```

#### Upplageuppgift
  * Upplageuppgift (editionStatement = 250 #a)</BR>
  Skriv in upplagebeteckning här. Följ resursens formulering.  
  ```Exempel: Limiterad upplaga```  
  
#### Utgivning  
  * Utgivning (publication)  
  Välj typ från lista. För monografisk resurs, använd Primär utgivning.  
  I konverterade och maskininlästa poster finns det ibland två avsnitt: ett Primär utgivning med År och Land, och ett Utgivning med Plats,        Agent och Datum. När man redigerar maskininlästa poster med två utgivningsavsnitt får man, om man bedömer det nödvändigt, flytta uppgifterna om Plats, Agent och Datum till avsnittet Primär utgivning och ta bort avsnittet Utgivning. (NB inväntar en maskinell ändring av dessa poster och ändrar inte manuellt.)
  
  Vid postimport: I importerade poster förekommer ibland både År och Copyrightår inom Utgivning (= 008/06: t, 008/07-10: År och 008/11-14: Copyrightår). Låt uppgiften ligga kvar oförändrad. Om posten är katalogiserad enligt RDA kan även Copyright/Copyright/Datum (copyright/Copyright/date = 264 -/4 #c) finnas med.
 
##### Utgivningsplats
  * Plats/Plats/Benämning (= Utgivningsort) (place/label = 264 -/1 #a)  
  Sök inte efter Plats som entitet. Skapa Plats som lokal entitet.     
  Skriv in uppgiften under Benämning. Klamra vid behov.</br>
  ```Exempel: Malmö```  
  
##### Utgivningsland  
  * Land (country = 008/15-17)  
  Länka till entitet.  
  ```Exempel: Sverige (sw)``` 
  
##### Utgivarnamn
  * Agent/Agent/Benämning (= Utgivarnamn) (agent/label = 264 -/1 #b)  
  Sök inte efter Agent som entitet. Skapa Agent som lokal entitet.       
  Skriv in uppgiften under Benämning.  
  ```Exempel: Dead End Exit Records```  
  
  Om flera utgivare ska anges, lägg till Har del (hasPart) under Primär utgivning. Skapa Utgivning som lokal entitet. I rutan Skapa lokal entitet, längst ner i sidorutan till höger, skriv Utgivning och välj *** Utgivning. Upprepa Utgivning som lokal entitet genom att duplicera entiteten Utgivning. 
  Ange Plats/Plats/Benämning och Agent/Agent/Benämning inom respektive utgivningsavsnitt. Samtliga utgivare med Plats och Agent ska ligga inom Har del/Utgivning.  
  Land, År och eventuellt Datum ska ligga inom Primär utgivning.  
  Se [exempel](https://libris.kb.se/katalogisering/w4rp4hlwtr5lctjr#it).
  
##### År och datum 
  * År (= Utgivningstid) (date = 008/07-10, 264 -/1 #c)  
    År får endast innehålla siffror (0-9) och bokstaven u. År ska endast förekomma inom Primär utgivning.  
    Utgivningsår anges här, utan klamrar eller andra tecken - endast fyra positioner. Det kommer då att exporteras till både marcpostens 08/07-10 och 264 -/1 #c.  
  ```Exempel: 2017```  
  
  Observera att År måste finnas med i beskrivningen, även om Datum finns med.</br>
  
  För att ange årtal med klamrar eller andra tecken utöver fyra positioner, använd Datum.  
  * Datum (= Utgivningstid) (date = 264 -/1 #c)  
    Datum får innehålla text och interpunktionstecken.  
    Utgivningsdatum med fler än fyra positioner, till exempel ett klamrat årtal, anges här. Det kommer att exporteras till marcpostens  264 -/1 #c.
  <br/>```Exempel:```
    * ```[2017]```
    * ```[mellan 2003 och 2005?]```

  För att ange ett år utan klamrar eller andra tecken, använd År.  

  För att ange ett osäkert utgivningsdatum där endast tidigaste och senaste årtal kan anges, följ exempel i hjälptexten [Instans](https://libris.kb.se/katalogisering/help/workflow-instance#produktion) under rubriken Produktion: Huvudsakligt tillgängliggörande.  
  
* Flera år (flerbandsverk)  
 För anvisningar om hur man anger flera år (flerbandsverk), se hjälptexten [Instans](https://libris.kb.se/katalogisering/help/workflow-instance#utgivning): Utgivning. 

 Läs mer om [År och Datum](https://kundo.se/org/librisxl/d/falt-for-utgivningsar/)  
  
#### Copyright- eller p-ar
  För fonogram anges alltid copyright- eller p-år, även om det sammanfaller med utgivningsår, se [Librispraxis 2.11](http://access.rdatoolkit.org/kbspchp2_kbsp2-1030.html).</BR>
* Copyright/Copyright/Datum (copyright/Copyright/date = 264 -/4 #c)  
  Det går bara att ange ett år här, så om både copyright- och p-år förekommer på resursen ange det senaste p-året.
  För att få fram copyrighttecknet eller tecknet för p-år, kopiera från exemplet nedan eller skriv Alt + 184.  
  Se också [Specialtecken](https://libris-dev.kb.se/katalogisering/help/search-04-special-chars). Du kan t ex söka på teckenuppsättning i “Sök i windows” och öppna programmet, markera och kopiera tecknet och sedan klistra in det.  
  Skriv in uppgiften.
  <br/>```Exempel:```
    * ```©2017```
    * ```℗2017```  
     
#### Identifikator
Flera typer av identifikatorer kan finnas på ljudinspelningar. I mallen för musik-CD är Utgivningsnummer (ljudinspelning) och EAN förvalda.

##### Utgivningsnummer (ljudinspelning)
  * Identifikator (identifiedBy)<br/>
  Välj typ från lista.
  <br/>```Exempel: Utgivningsnummer (ljudinspelning)```
  * Identifikator/Utgivningsnummer (ljudinspelning)/Värde (identifiedBy/AudioIssueNumber/value = 028 #a)<br/>
  Ange identifikator som det förekommer i resursen.
  <br/>```Exempel: DEERCD016```
  * Identifikator/Agent/Organisation/Namn (= Utgivare) (identifiedBy/agent/Organization/name = 028 #b)<br/>
  Ange utgivarens namn.
  <br/>```Exempel: Dead End Exit Records```<br/>
  * Identifikator/Särskiljande tillägg (= Bestämning) (identifiedBy/qualifier = 020 #q)  
  Ange eventuell bestämning.    
  
##### EAN
  * Identifikator (identifiedBy)  
  Välj typ från lista.  
  ```Exempel: EAN```
  * Identifikator/EAN/Värde (identifiedBy/EAN/value = 024 #a)<br/>
  Ange identifikator.<br/>
  ```Exempel: 7320470195826```  
   
#### Omfang
  Ange antal enheter samt typ av enhet, se [RDA 3.4.1.3](http://access.rdatoolkit.org/rdachp3_rda3-2098.html) samt [Librispraxis för Alternativ](http://access.rdatoolkit.org/kbspchp3_kbsp3-95.html). Ange speltid (inom parentes) efter omfång när uppgiften är lätt åtkomlig. 
  * Omfång/Omfång/Benämning (extent/Extent/label = 300 #a)   
  Skriv in uppgiften under Benämning.  
  ```Exempel: 1 CD (1 tim., 12 min.) ```  
  
#### Ovriga fysiska detaljer   
  * Övriga fysiska detaljer (other physical details = 300 #b)     
  Skriv in uppgiften.  
  ```Exempel: mono```
  
#### Medfoljande material
  * Medföljs av/Instans/Benämning (Bilagor) (accompaniedBy/Instance/label = 300 #e)   
  Här anges medföljande material, som t ex bilagor. Lägg till Medföljs av. Skapa Instans som lokal entitet (skriv Instans i rutan Skapa lokal entitet och välj ** Instans.)</br> 
  Lägg till Benämning. Skriv in uppgiften.  
   ```Exempel: Sångtexter och kommentarer i bilaga```  
    
#### Seriemedlemskap
  * Seriemedlemskap/Seriemedlemskap/Ingår i serie (seriesMembership/SeriesMembership/inSeries)  
  För anvisningar om hur man anger Seriemedlemskap, se hjälptexten [Instans](https://libris.kb.se/katalogisering/help/workflow-instance#seriemedlemskap) under rubriken Seriemedlemskap. 
   
#### Innehallsforteckning  
  * Har innehållsförteckning/Innehållsförteckning/Benämning (tableofContents = 505 8/_)  
  För en enkel innehållsförteckning (505 ‡a), lägg till Har innehållsförteckning. Lägg därefter till Innehållsförteckning. Skriv in uppgiften under Benämning.
  <br/>```Exempel:```
    * ```Symfoni, nr 1, op. 45, d-moll ; Serenad, op. 36, d-moll```
    * ```Don't Deceive Me (Fats Domino) -- Cheatin' Woman (Frankie Ford) -- Honey Hush (Joe Turner) -- Diddy-Y-Diddy-O (Roy Brown) -- Whirlaway (Allen Toussaint) -- Cha Dooky Doo (Art Neville) -- Real Gone Party (Ruth & Al) -- Chickee Wah Wah (Bobby Marchan) --There'll Be No Backin' Out (Mickey & Sylvia) -- That's All I Need To Know (Sam Cooke) -- Carry On (Jerry Byrne)```

   * Har innehållsförteckning/Innehållsförteckning/Har del/Utökad innehållsanmärkning/Benämning, Upphovsuppgift, Kommentar (tableofContents = 505 8/0 #t, #r, #g)  
  För att skapa en utökad innehållsanmärkning med titlar och upphovsuppgifter, se Hjälptexten för Instans:
  https://libris.kb.se/katalogisering/help/workflow-instance#innehallsforteckning
  
#### Anmarkning
  * Anmärkning/Anmärkning/Benämning (hasNote/Note/label = 500 #a)  
  Gör allmänna anmärkningar här.  
  För att lägga till Anmärkning, klicka på plustecknet i redigeringsvyn (den stora runda ikonen i verktygsmenyn - Lägg till egenskaper under: Ljudinspelning) och välj Anmärkning (hasNote). Lägg till Anmärkning.  
  Skriv in uppgiften under Benämning.</BR> 
  ```Tidigare utgiven 1997```  
  
#### Relaterad beskrivning eller innehall
  * Relaterad beskrivning eller innehåll/Dokument/URI (isPrimaryTopicOf/Dokument/uri = 856 4/2 #u)</BR>
  Länka till delar, sammanfattningar, innehållsförteckningar eller andra resurser som på något sätt hör samman med den resurs som beskrivs.</BR>
  Lägg till Relaterad beskrivning eller innehåll. Skapa Dokument som lokal entitet. Lägg till egenskapen URI. Klistra in aktuell länk.
  
### Verk   
#### Instans av Verk/Musik
  * Instans av Verk/Musik (instanceOf/Work/Audio)  
  Skapa verket som lokal entitet (bryt inte ut verket till en länkbar entitet). Denna hjälptext beskriver exempel på verk som lokal entitet. Det betyder att du anger de uppgifter som listas här nedan, under Instans av Verk, utan att klicka på länksymbolen (Länka entitet) vid Instans av Verk/Musik.  
  Läs mer om [Verk och Instans](https://librisbloggen.kb.se/2018/05/30/verk-och-instans-i-startversionen/).  

  För att lägga till egenskaper under Instans av Verk/Musik, klicka på plustecknet vid Instans av Verk/Musik - Lägg till egenskaper under: Musik. Sök fram egenskapen och välj den genom att klicka på plustecknet vid egenskapens namn.  

#### Verkets titel
  Ange vid behov den föredragna titeln för verket här. Följ [Anvisningar för katalogisering - RDA](http://www.kb.se/rdakatalogisering/Anvisningar/Allmanna-anvisningar/Sokingangar-for-verk-och-uttryck "Anvisningar för katalogisering - RDA"). 

##### Verkets titel - verk med primär medverkan
  Föredragen titel för ett verk med primär medverkande ska anges i Har titel/Titel/Huvudtitel .</BR>
  * Har titel/Titel/Huvudtitel (hasTitle/Title/mainTitle = 240 1/0 #a)  
    Ange den föredragna titeln för verket här, vid behov. Pregnanta titlar för musik anges ofilerade. Skriv in uppgiften. 
  <br/>```Exempel:```
    * ```La traviata```
    * ```Symfoni```
    * ```Pianomusik```  
  
  Använd även Huvudtitel för *hela* den föredragna titeln då ordningen mellan uppgifterna i Har titel, Tonart, Version och språk för översättning blir felaktig i MARC-förhandsgranskningen, eller om den föredragna titeln är svår eller omöjlig att uttrycka med enbart dessa fält.
  <br/>```Exempel:```
    * ```Sonater och partitor, violin, BWV 1001-1006. Partita, nr 1, h-moll```
    * ```Kvartett, stråkar, nr 13, D. 804, op. 29:1, a-moll, "Rosamunde". Entr'acte```
  
  * Delbeteckning (hasTitle/Title/mainTitle/partNumber = 240 1/0 #n)  
  Ange numreringar för verket här, vid behov. Skriv in uppgiften.
  <br/>```Exempel:```
    * ```nr 96, Hob. I:96```
    * ```nr 3, op. 90```
  
  * Deltitel (hasTitle/Title/mainTitle/partName = 240 1/0 #p)       
    Lägg till eventuell deltitel genom att klicka på plustecknet vid Titel (lägg till fält under: Titel), välj Deltitel.
    Skriv in uppgiften.
  <br/>```Exempel:```
    * ```Di Provenza il mar```
    * ```Allegro```

  * Specificering i form av grupptitel (hasTitle/Title/mainTitle/marc:formSubheading = 240 1/0 #k)   
    Grupptitlar, exempelvis ”Pianomusik. Urval”, används då Instansen innehåller flera verk av samma tonsättare. Grupptiteln kompletteras med individuella sökingångar för dessa verk (i Relation/Verk).  
    Lägg till eventuell grupptitel genom att klicka på plustecknet vid Titel (lägg till fält under: Titel), välj Specificering i form av grupptitel. Skriv in uppgiften.  
     ```Exempel: Urval```  

  * Besättning för framförande (musicMedium = 240 ‡m)  
  Ange besättning. Skriv in uppgiften.
  <br/>```Exempel:```
    * ```orkester```
    * ```klarinett, piano```
    * ```blandad kör```
      
  * Tonart (240 1/0 ‡r)       
    Ange tonart. Skriv in uppgiften.  
    ```Exempel: fiss-moll```  
    
  * Version (240 1/0 ‡o)        
    Ange eventuellt arrangemang. Skriv in uppgiften.  
     ```Exempel: arr. röst, piano```  

##### Verkets titel - verk utan primär medverkan
  Föredragen titel för ett verk utan primär medverkande ska anges i Uttryck av verk/Verk/Har titel/Huvudtitel.</BR>
  *	Uttryck av/Verk/Har titel/Titel/Huvudtitel (expressionOf/Work/hasTitle/Title/mainTitle (= 130 #a)  
  Under Instans av Verk, lägg till Uttryck av. Skapa verk som lokal entitet (plustecknet vid Uttryck av - Lägg till verk, välj Skapa lokal  entitet, längst ner i sidorutan till höger), välj Verk. Lägg till Har titel. Välj Titel. Skriv in uppgiften under Huvudtitel.
  *	Uttryck av/Verk/Har titel/Titel/Deltitel (expressionOf/Work/hasTitle/Title/partName = 130 #p)  
  Lägg till eventuell deltitel (plustecknet vid Titel - lägg till egenskaper under: Titel, välj Deltitel).
  *	Uttryck av/Verk/Har titel/Titel/Delbeteckning (expressionOf/Work/hasTitle/Title/partName = 130 #n)  
  Lägg till eventuell delbeteckning (plustecknet vid Titel - lägg till egenskaper under: Titel, välj Delbeteckning).  
  *	Uttryck av/Verk/Språk/Språk/Benämning (expressionOf/Work/language/Language/label = 130 #l)  
  Lägg till eventuell benämning på språk som ska ingå i den föredragna titeln. Klicka på plustecknet vid Verk (Lägg till egenskaper under:  Verk) och välj Språk. Klicka på plustecknet vid Språk (Lägg till språk) och välj Skapa lokal entitet. Lägg till Benämning (plustecknet vid  Språk - Lägg till egenskaper under: Språk, välj Benämning. Ange språket i klartext. Denna klartext - verkets (översättningens) språk - visas som ett tillägg till verkets titel i marcpostens 130 ‡l.</BR>

#### Relationer till ingaende verk och andra verk

##### Verk som ingår i det beskrivna verket
  För att ange verk som ingår i det beskrivna verket motsvarande fält 700 1/2 #a, #d, #t (analytisk sökingingång för verk med primär medverkande) eller 730 0/2 #a (analytisk sökingång för verk utan primär medverkande) i marc:  
  Under Instans av Verk/Musik, lägg till Har del. Skapa verk som lokal entitet. Lägg till Har titel och välj Titel. Ange föredragen titel i Huvudtitel.</br>
  Lägg till eventuell deltitel och delbeteckning.
  För ingående verk med primär medverkande, lägg till Medverkan och funktion/Primär medverkan enligt anvisningarna nedan under Medverkan och funktion: Primär medverkan.  
  
  För utförligare instruktioner, se även hjälptexten [Relationer till delar och verk](https://libris.kb.se/katalogisering/help/workflow-agent-relation).

##### Relationer till andra verk  
  För att ange verk som är relaterade, men inte ingår i det beskrivna verket, motsvarande fält 700 1/- #a, #d, #t (icke-analytisk sökingingång för verk med primär medverkande) eller 730 0/_ #a (icke-analytisk sökingång för verk utan primär medverkande) i marc: 
  Under Instans av Verk/Musik, lägg till Relation. Välj typ Relation. Lägg till Entitet och välj Entitet. Skapa verk som lokal entitet. Lägg till Har titel och välj Titel. Ange föredragen titel i Huvudtitel.</br> 
  Lägg till eventuell deltitel och delbeteckning. 
  För ingående verk med primär medverkande, lägg till Medverkan och funktion/Primär medverkan enligt anvisningarna nedan under Medverkan och funktion: Primär medverkan. 

  För utförligare instruktioner, se även hjälptexten [Relationer till delar och verk](https://libris.kb.se/katalogisering/help/workflow-agent-relation).

#### Medverkan och funktion  
  * Medverkan och funktion  
  Under Medverkan och funktion, ange relationer till de agenter som medverkar i verket samt funktionskod för respektive agent.  Relationer till utgivare (710) anges för närvarande också här.</BR>
  För ytterligare instruktioner om hur man anger relationer till agenter, se: [Relationer till Agent](https://libris.kb.se/katalogisering/help/workflow-agent-org-instance).</BR>
  Se även: [Auktoritetsgruppens rekommendationer](https://kundo.se/org/librisxl/d/kbs-auktoritetsgrupp-informerar-jraz/).  
  
##### Primär medverkan
  * Medverkan och funktion/Primär medverkan/Agent/Person (contribution/PrimaryContribution/agent/Person = 100 1/- #a)  
  Länka till entitet. Börja alltid med att söka efter om agenten redan finns. Vid behov, skapa ny entitet för agent (se Skapa ny agent i hjälpsektionen). I undantagsfall, skapa lokal entitet.
<br/>```Exempel: Persson, Peps, 1946-```  
  * Medverkan och funktion/Primär medverkan/Funktion (contribution/PrimaryContribution/role = 100 #4)  
  Länka till entitet. Klicka på plustecknet vid Funktion (Lägg till funktion) och sök fram funktionskod. Skriv in kod eller utskriven form i sökrutan eller tryck på mellanslagstangenten för att se alla koder. Välj kod genom att klicka på plustecknet vid koden eller på koden.    
  För en sorterad lista på koder, se Formathandboken för Libris/Voyager: [Funktions- och relationskoder](http://www.kb.se/katalogisering/Formathandboken/Funktionskoder/)  
  ```Exempel: Framförande, prf (=Exekutör)```

##### Medverkan
  * Medverkan och funktion/Medverkan/Agent/Person (contribution/agent/Person = 700 1/- #a)  
  Länka till entitet. Börja alltid med att söka efter om agenten redan finns. Vid behov, skapa ny entitet för agent (se Skapa ny agent i hjälpsektionen). I undantagsfall, skapa lokal entitet.   
  ```Exempel: Skoglund, Bosse, 1936-```  
  * Medverkan och funktion/Medverkan/Funktion (contribution/role = 700 #4)  
  Länka till entitet. Klicka på plustecknet vid Funktion (Lägg till funktion) och sök fram funktionskod. Skriv in kod eller utskriven form i sökrutan eller tryck på mellanslagstangenten för att se alla koder. Välj kod genom att klicka på plustecknet vid koden eller på koden.    
För en sorterad lista på koder, se Formathandboken för Libris/Voyager: [Funktions- och relationskoder](http://www.kb.se/katalogisering/Formathandboken/Funktionskoder/)    
  ```Exempel: Producent, pro```  

#### Sprak 
  * Språk (language = 008/35-37)  
  Ange det talade språket eller sjungna språket här.  
  Länka till entitet.  
  ```Exempel: svenska (swe)```  
  Ange flera språk genom att klicka på plustecknet vid Språk (Lägg till språk) och sök fram rätt entitet för språket. Länka till entitet. 
  
#### Genre  
  Länka till entitet. För att söka efter entiteter inom Genre/form, klicka på plustecknet vid Genre/form (lägg till entitet). I Lägg till entitet, välj typ i listan över typer. Skriv in sökbegrepp. Trunkera genom att trycka på mellanslagstangenten eller med * i sökrutan. Välj entitet genom att klicka på plustecknet vid entiteten (Lägg till). Vid behov, välj ytterligare entiteter i listan. 

  Under Genre/form, ange dels saogf-termer (genre/form-termer enligt Svenska ämnesord), dels termer som motsvarar marc-koder i 008. För att länka till saogf-termer, välj Genre/form i listan (det första alternativet under Alla). För att länka till termer som motsvarar marc-koder i 008, se övriga rubriker. 

##### Saogf-termer  
  * Genre/form – saogf-termer (genreForm = 655 -/7 #a, #2 saogf)  
 Välj Genre/form i listan över typer. Avgränsa till saogf-termer genom att skriva "saogf" efter söktermen. Länka till entitet.
<br/>```Exempel:```
    * ```Musikinspelningar```
    * ```Reggae```

  Se [instruktionsfilm](https://www.youtube.com/watch?v=wrqs310Nt0M&list=PLZVkEICvA5-GRT2oJQmLgq_2Pksx6zYPy&index=7)  

#### Klassifikation  
  För anvisningar om hur man anger Klassifikation, se hjälptexten [Verk](https://libris.kb.se/katalogisering/help/workflow-work#klassifikation) under rubriken Klassifikation.
   
#### Malgrupp     
  * Målgrupp (intendedAudience = 008/22)  
  Länka till entitet.  
  ```Exempel: j (= barn- och ungdom, 0-16 år)```  

  För att lägga till Målgruppsanmärkning (Målgrupp/Målgrupp/Benämning), se hjälptexten för [Instans](https://libris-dev.kb.se/katalogisering/help/workflow-instance#malgruppsanmarkning) under rubriken Målgruppsanmärkning.

#### Innehallstyp
  * Innehållstyp/Innehållstyp (contentType/ContentType = 336 #b)   
  Länka till entitet.  
  ```Exempel: term/rda/PerformedMusic```  
 
#### Inspelning
Under inspelning kan man såväl göra anmärkning om inspelningens tid, plats och omständigheter som ange kodade uppgifter om inspelningstid och inspelningsplats.

##### Anmärkning om inspelningens tid, plats och omständigheter.
* Inspelning/Inspelning/Benämning (capture/Inspelning/label = 518 #a)</BR>
 Skriv in uppgiften under Benämning.</BR>
   ```Exempel: Inspelad 2010 i Konserthuset, Stockholm```

##### Kodade uppgifter om inspelningstid och inspelningsplats.
* Inspelning/Inspelning/Datum (capture/Inspelning/date = 033 #a)</BR>
  Under Inspelning, lägg till Inspelning som lokal entitet genom att klicka på plustecknet, Lägg till entitet.
  Lägg till Datum genom att klicka på plustecknet, Lägg till egenskaper under: Inspelning. Skriv in uppgiften.</BR>
    ```Exempel: 2010```

* Inspelning/Inspelning/Plats/Plats/Benämning (capture/Inspelning/place/Plats = 033 #p)</BR>
  Klicka igen på plustecknet, Lägg till egenskaper under: Inspelning. Lägg till Plats.
  Under Plats, lägg till Plats som lokal entitet genom att klicka på plustecknet, Lägg till entitet.
  Klicka på plustecknet bredvid Plats, Lägg till egenskaper under Plats och lägg till Benämning. Skriv in uppgiften.</BR>
   ```Exempel: Stockholm```
  
#### Anmarkning om medverkande
  * Anmärkning/Anmärkning om medverkande/Benämning (hasNote/marc:ParticipantOrPerformerNote/label = 511 #a)  
 Ange namn på medverkande följt av instrumentnamn och/eller röstläge.  
  ```Exempel: Mats Gustafsson, flutephone, tenorsaxofon ; David Grubbs, harmonium```
  
#### Sammanfattning av innehall    
  * Sammanfattning av innehåll/Sammanfattning/Benämning (summary/Summary/label = 520 #a)  
  Lägg till Sammanfattning av innehåll. Välj Sammanfattning av innehåll. Lägg till Sammanfattning. Skriv in uppgiften under Benämning.
  <br/>```Exempel:```
    * ```60 trallar från Dalarna```
    * ```Musik från filmen The star```

  * Typ av innehållsbeskrivning/sammanfattning (marc:summaryType = 520 ind1)  
  Sök fram och lägg till Typ av innehållsbeskrivning/sammanfattning (plustecknet vid Sammanfattning - lägg till egenskaper under: Sammanfattning). Välj typ från lista.  
 ```Exempel: Ej preciserad```

