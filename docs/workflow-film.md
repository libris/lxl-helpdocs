---
section: Materialtyper
title: Film
order: 44
date: 2021-09-29
tags:
- film
- filmkatalogisering
- videoinspelning
---

# Film
Denna hjälptext ger kortfattade instruktioner för de vanligaste egenskaperna för film - videoinspelning (DVD eller Blu-Ray). För utförliga instruktioner, se de generella hjälptexterna för Adminmetadata, Instans och Verk, se nedan.

## Innehåll  

| [Adminmetadata](#adminmetadata) | [Instans](#instans) | [Verk](#verk) | 
| ----------- |  ----------- | ----------- |
|  [Adminmetadata - Metadatabyrån](https://metadatabyran.kb.se/beskrivning/specialanvisningar/adminmetadata-i-libris) | [Generell hjälptext för Instans](https://libris.kb.se/katalogisering/help/workflow-instance) | [Generell hjälptext för Verk](https://libris.kb.se/katalogisering/help/workflow-work) |
| | [Utgivningssätt](#utgivningssätt) | [Verkets titel](#verkets-titel) |
| | [Medietyp](#medietyp) | [Medverkan och funktion](#medverkan-och-funktion) |
| | [Bärartyp](#bärartyp) | [Språk](#språk) |
| | [Titel](#titel) | [Relationer till ingående verk och andra verk](#relationer-till-ingående-verk-och-andra-verk) |
| | [Upphovsuppgift](#upphovsuppgift) | [Genre/form](#genre-form) |
| | [Upplageuppgift](#upplageuppgift) | [Klassifikation](#klassifikation) |
| | [Utgivning](#utgivning) | [Ämne](#ämne)  |
| | [Copyrightår](#copyrightår) | [Målgrupp](#målgrupp) |
| | [Identifikator](#identifikator) | [Innehållstyp](#innehållstyp) |
| | [Omfång](#omfång) | [Bild- och filmtexter](#bild--och-filmtexter)|
| | [Speltid](#speltid) | [Inspelning](#inspelning) |
| | [Övriga fysiska detaljer](#övriga-fysiska-detaljer) | [Anmärkningar](#anmärkningar) |
| | [Medföljande material](#medföljande-material) | [Sammanfattning av innehåll](#sammanfattning-av-innehåll)  |
| | [Videokarakteristika](#videokarakteristika) | |
| | [Seriemedlemskap](#seriemedlemskap) | |
| | [Målgruppsanmärkning](#målgruppsanmärkning) | |
| | [Innehållsförteckning](#innehållsförteckning) | |
| | [Systemkrav och mediespecifika uppgifter](#systemkrav-och-mediespecifika-uppgifter) | |
| | [Anmärkning](#anmärkning) | |
| | [Elektronisk adress](#elektronisk-adress) | |

## Inledning
Beskrivningen av en film innehåller följande tre delar:  
* [Adminmetadata - Metadatabyrån](https://metadatabyran.kb.se/beskrivning/specialanvisningar/adminmetadata-i-libris) - administrativa data om instansbeskrivningen, såsom kontrollnummer och beskrivningsnivå.
* [Instans](https://libris.kb.se/katalogisering/help/workflow-instance) - instans kan också kallas utgåva eller manifestation. Exempel på egenskaper under Instans är utgivningsplats, utgivare och utgivningsår, bärartyp, omfång.
* [Verk](https://libris.kb.se/katalogisering/help/workflow-work) – återger egenskaper för det abstrakta verket såsom medverkan och funktion (t.ex. författare), ämne, klassifikation, språk och innehållstyp. Verksbeskrivningen ligger under rubriken Instans av verk.

Många av egenskaperna finns redan i mallen Film - videoinspelning, andra kan behöva läggas till. För instruktioner om att lägga till eller ta bort egenskaper, länka till entitet, skapa lokal entitet och om hur formuläret fungerar i övrigt, se Redigering i vänstermenyn. För en förhandspost, använd gärna Berika från mall och välj Film.  

För information om katalogregler och Librispraxis, se [Metadatabyrån](https://metadatabyran.kb.se/) samt se [RDA Toolkit](https://original.rdatoolkit.org/). Notera att för utgivna rörliga bilder är hela den utgivna resursen godkänd källa. Uppgifterna får tas utan prioritetsordning från det ställe där de anses vara bäst. [Denna Librispraxis, KB SP 2.2.2.3](http://access.rdatoolkit.org/kbspchp2_kbsp2-38.html), bygger på IASA Cataloguing Rules och är en avvikelse från [RDA 2.2.2.3](http://access.rdatoolkit.org/rdachp2_rda2-2892.html).

Se även [instruktionsfilmer på KB:s Youtubekanal](https://www.youtube.com/playlist?list=PLZVkEICvA5-GRT2oJQmLgq_2Pksx6zYPy).  

## Adminmetadata
[Adminmetadata - Metadatabyrån](https://metadatabyran.kb.se/beskrivning/specialanvisningar/adminmetadata-i-libris)

* Kontrollera beskrivningsnivån. I mallen är standardvärdet Biblioteksnivå (normalvärde för Librisbiblioteken). Ändra vid behov.
**Observera: Om nivån är CIP-post eller preliminär post, ändra till annan nivå, annars kan ändringar skrivas över!** 

## Instans
För att lägga till egenskaper under Instans, klicka på plustecknet i redigeringsvyn (den stora runda plusikonen under Verktygsikonen - Lägg till egenskaper under: Videoinspelning). Sök fram egenskapen och välj den genom att klicka på plustecknet vid egenskapens namn.  

### Utgivningssätt
* Utgivningssätt (issuanceType)  
  Välj från lista.  
  ```Exempel: Monografisk resurs```

### Medietyp
* Medietyp (mediaType/Mediatype = 337 #b)  
  Länka till entiteten:  
  ```Video, v (= video)```

### Bärartyp
* Bärartyp (carrierType/CarrierType = 338 #b)  
  Välj Bärartyp i listan över typer.
  Länka till entiteten:  
  ```Videodisc, vd (= videoskiva)```  

### Titel  
Notera att egenskapen Allmän medieterm (marc:mediaTerm = 245 #h) (= Medieterm) inte ska ingå i beskrivningar som görs enligt RDA. 

#### Huvudtitel    
* Har titel/Titel/Huvudtitel (hasTitle/Title/mainTitle = 245 #a)  
  Återge huvudtiteln som den förekommer i källan, se [Librispraxis 2.2.2.3](http://access.rdatoolkit.org/kbspchp2_kbsp2-38.html). 
  <br/>Om titeln förekommer i källan på mer än ett språk eller i mer än en skriftart, se [RDA 2.3.2.4](http://access.rdatoolkit.org/rdachp2_rda2-3375.html) samt [Librispraxis för RDA 2.3.2.4](http://access.rdatoolkit.org/kbspchp2_kbsp2-84.html).  
 ```Exempel: The beguiled```  
    För en titel som börjar med bestämd eller obestämd artikel, ska artikeln fileras bort. Ange fileringsvärde genom att lägga till fileringsvärde (plustecknet vid Titel - Lägg till egenskaper under: Titel) och ange en siffra.  
 ```Exempel: Huvudtitel: The Beguiled, fileringsvärde: 4```  
Se exempel på sidan [Filering av titel - Metadatabyrån](https://metadatabyran.kb.se/beskrivning/generella-anvisningar---rda/manifestation-instans/titel/filering-av-titel).

För att ange föredragen titel, se Verk/Har titel/Titel/Huvudtitel.  

#### Övrig titelinformation (undertitel)
* Har titel/Titel/Övrig titelinformation (= Undertitel) (hasTitle/Title/subtitle = 245 #b)  
  Skriv in uppgiften. Om det finns flera undertitlar, skriv in dessa efter varandra i samma fält, åtskilda av mellanslag, kolon, mellanslag. 
  <br/>```Exempel: mer om modelljärnvägar : allt samlaren behöver veta```

#### Varianttitel
En varianttitel är en titel förknippad med resursen som skiljer sig från den titel som angivits som huvudtitel, se [RDA 2.3.6](http://access.rdatoolkit.org/rdachp2_rda2-4004.html). Här anges t.ex. varianter för titlar som innehåller specialtecken, siffror eller oväntade stavningar av ord.
<br/>För att lägga till varianttitel, klicka på plustecknet vid Har titel (lägg till titel) och välj typ Varianttitel.  
  * Har titel/Varianttitel/Huvudtitel (hasTitle/VariantTitle/mainTitle = 246 #a)<br/> 
 Skriv in uppgiften i Huvudtitel.    
  ```Exempel: Cool girls```<br/>

För en parallell huvudtitel på ett annat språk eller i en annan skriftart, se [Parallelltitel](#parallelltitel).<br/>

Om huvudtiteln är felstavad i källan anges en korrekt form av titeln som varianttitel. Notera dock att för utgivna rörliga bilder är hela resursen godkänd källa, utan prioritetsordning, se [Librispraxis för RDA 2.2.2.3](http://access.rdatoolkit.org/kbspchp2_kbsp2-38.html). Det innebär att man vanligen kan hitta en korrekt form av titeln och ange den som huvudtitel.<br/>

En varianttitel kan specificeras med en Typanmärkning, en anmärkningstext som i ett sökgränssnitt ska föregå varianttiteln. För att lägga till en Typanmärkning, klicka på plustecknet vid Varianttitel (Lägg till egenskaper under: Varianttitel) och välj Typanmärkning. 
  * Har titel/Varianttitel/Typanmärkning (hasTitle/VariantTitle/typeNote = 246 1/_ ‡i)<br/> 
   ```Exempel: Titeln felstavad, korrekt titel:```   

#### Delbeteckning och deltitel
För anvisningar om hur man anger delbeteckning och deltitel, se [Metadatabyrån: Titlar på delar, sektioner eller supplement](https://metadatabyran.kb.se/beskrivning/generella-anvisningar---rda/manifestation-instans/titel#h-Titlarpadelarsektionerellersupplement).

#### Parallelltitel  
Ange parallelltitel här. Upprepa inte parallelltitel efter Har titel/Titel/Huvudtitel (245 ‡a) med interpunktion.   
* Har titel/Parallelltitel/Huvudtitel (hasTitle/ParallelTitle/mainTitle = 246 1/1 ‡a)   
Välj först Har titel, välj sedan typ Parallelltitel.      
Skriv in uppgiften i Huvudtitel.     
  ```Exempel: Räddarna```</br>
För en titel som börjar med bestämd eller obestämd artikel, ska artikeln fileras bort. Lägg till fileringsvärde och ange en siffra.
* Har titel/Parallelltitel/Övrig titelinformation (hasTitle/ParallelTitle/subTitle = 246 1/1 ‡b)   
Vid behov, lägg till Övrig titelinformation (subtitle) under Parallelltitel.  
  ```Exempel: berättelser om mod```  

### Upphovsuppgift
* Upphovsuppgift (responsibilityStatement = 245 ‡c)</BR>
  <br/>```Exempel:```
     * ```written, produced and directed by Hilary Ng'weno```
     * ```av Astrid Lindgren ; producent: Waldemar Bergendahl ; regi: Lasse Hallström```

### Upplageuppgift
* Upplageuppgift (editionStatement = 250 ‡a)</BR>
  Skriv in upplagebeteckning här. 
 <br/>```Exempel: Limited edition```  

### Utgivning  
Följ [Librispraxis för RDA 2.8](http://access.rdatoolkit.org/kbspchp2_kbsp2-590.html) och ange distributionsuppgifter i avsnittet för utgivning. I filmbranschen är distributör motsvarigheten till utgivare. Produktionsland och produktionsår anges tills vidare i [Anmärkning](#anmärkning).
* Utgivning (publication)  
  Välj typ från lista. För monografisk resurs, använd Primär utgivning.  
  I konverterade och maskininlästa poster finns det ibland två avsnitt: ett Primär utgivning med År och Land, och ett Utgivning med Plats, Agent och Datum. När man redigerar maskininlästa poster med två utgivningsavsnitt får man, om man bedömer det nödvändigt, flytta uppgifterna om Plats, Agent och Datum till avsnittet Primär utgivning och ta bort avsnittet Utgivning.   
NB inväntar en maskinell ändring av dessa poster och ändrar inte manuellt.  
  Vid postimport: I importerade poster förekommer ibland både År och Copyrightår inom Utgivning (= 008/06: t, 008/07-10: År och 008/11-14: Copyrightår). Låt uppgiften ligga kvar oförändrad.      
Om posten är katalogiserad enligt RDA kan även Copyright/Copyright/Datum (copyright/Copyright/date = 264 -/4 ‡c) finnas med.

#### Utgivningsplats
* Plats/Plats/Benämning (= Utgivningsort) (place/label = 264 -/1 ‡a)  
Sök inte efter Plats som entitet. Skapa Plats som lokal entitet. Skriv in uppgiften under Benämning. Klamra vid behov.</br> 
  ```Exempel: [Stockholm]```  

#### Utgivningsland  
* Land (country = 008/15-17)  
  Länka till entitet.  
  ```Exempel: Sverige (sw)``` 

#### Utgivarnamn
* Agent/Agent/Benämning (= Utgivarnamn) (agent/label = 264 -/1 ‡b)  
Sök inte efter Agent som entitet. Skapa agent som lokal entitet. Skriv in uppgiften under Benämning.  
  ```Exempel: Njutafilms```   
 Om flera utgivare ska anges, lägg till Har del (hasPart) under Primär utgivning. Skapa Utgivning som lokal entitet. I rutan Skapa lokal entitet, skriv Utgivning och välj *** Utgivning. Upprepa Utgivning som lokal entitet genom att duplicera entiteten Utgivning.
Ange Plats/Plats/Benämning och Agent/Agent/Benämning inom respektive utgivningsavsnitt. Samtliga utgivare med Plats och Agent ska ligga inom Har del/Utgivning. Land, År och eventuellt Datum ska ligga inom Primär utgivning.</br>
  Se [exempel i Libris katalogisering](https://libris.kb.se/katalogisering/w4rp4hlwtr5lctjr#it).

#### År och datum 
  * År (= Utgivningstid) (date = 008/07-10, 264 -/1 ‡c)  
  År får endast innehålla siffror (0-9) och bokstaven u. År ska endast förekomma inom Primär utgivning.  
  Utgivningsår anges här, utan klamrar eller andra tecken - endast fyra positioner. Det kommer då att exporteras till både marcpostens 08/07-10 och 264 -/1 ‡c.</br>
  ```Exempel: 2017```</br>
 
 Observera att År måste finnas med i beskrivningen, även om datum finns med.</br>
  
  För att ange årtal med klamrar eller andra tecken utöver fyra positioner, använd Datum.
  * Datum (= Utgivningstid) (date = 264 -/1 ‡c)  
  Datum får innehålla text och interpunktionstecken.  
  Utgivningsdatum med fler än fyra positioner, till exempel ett klamrat årtal, anges här. Det kommer att exporteras till marcpostens  264 -/1 ‡c.
  <br/>```Exempel:```
     * ```[2017]```
     * ```[mellan 2003 och 2005?]```

För att ange ett år utan klamrar eller andra tecken, använd År.

För att ange ett osäkert utgivningsdatum där endast tidigaste och senaste årtal kan anges, följ exempel i hjälptexten [Instans](https://libris.kb.se/katalogisering/help/workflow-instance#produktion): Produktion: Huvudsakligt tillgängliggörande. 
  
* Flera år (flerbandsverk)  
 För anvisningar om hur man anger flera år (flerbandsverk), se hjälptexten [Instans](https://libris.kb.se/katalogisering/help/workflow-instance#utgivning): Utgivning. 
 
 Läs mer om Utgivningstid i [Metadatabyrån: Utgivningstid](https://metadatabyran.kb.se/beskrivning/generella-anvisningar---rda/manifestation-instans/utgivningsuppgift#h-Utgivningstid).

### Copyrightår
För film anges alltid copyrightår, även om det sammanfaller med utgivningsår/distributionsår, se [Librispraxis 2.11](http://access.rdatoolkit.org/kbspchp2_kbsp2-1030.html).
* Copyright/Copyright/Datum (copyright/Copyright/date = 264 -/4 ‡c)  
  Skriv in uppgiften. För att få fram ©, kopiera härifrån eller sök på teckenuppsättning i “Sök i windows” och öppna programmet, markera och kopiera tecknet och sedan klistra in det.  
  Se också [Specialtecken](https://libris.kb.se/katalogisering/help/special-chars). 
<br/>```Exempel: ©2017```

### Identifikator
Flera typer av identifikatorer kan finnas på film. I mallen för Utgivningsnummer (videoinspelning) och EAN förvalda.

#### Utgivningsnummer (videoinspelning)
* Identifikator (identifiedBy)  
  Välj typ från lista.  
  ```Exempel: Utgivningsnummer (videoinspelning)```
* Identifikator/Utgivningsnummer (videoinspelning)/Värde (identifiedBy/VideoRecordingNumber/value = 028 ‡a)<br/>
  Ange utgivningsnumret som det förekommer i resursen.<br/>
  ```Exempel: NF780```
* Identifikator/Agent/Organisation/Namn (= Utgivare) (identifiedBy/agent/Organization/name = 028 ‡b)<br/> 
  Ange utgivarens namn.<br/>
  ```Exempel: Njutafilms```
* Identifikator/Särskiljande tillägg (= Bestämning) (identifiedBy/qualifier = 020 ‡q)<br/>
  Ange eventuell bestämning.<br/>

#### EAN
* Identifikator (identifiedBy)  
  Välj typ från lista.  
  ```Exempel: EAN```
* Identifikator/EAN/Värde (identifiedBy/EAN/value = 024 ‡a)<br/>
  Ange identifikator.<br/>
  ```Exempel: 5705535059701```

För anvisningar om hur man anger ISBN, se hjälptexten [Instans](https://libris.kb.se/katalogisering/help/workflow-instance#identifikator): Identifikator

### Omfång  
Ange antal enheter samt typ av enhet, se [RDA 3.4.1.3](http://access.rdatoolkit.org/rdachp3_rda3-2098.html) samt [Librispraxis för Alternativ](http://access.rdatoolkit.org/kbspchp3_kbsp3-95.html). Ange speltid (inom parentes) efter omfång när uppgiften är lätt åtkomlig.
* Omfång/Omfång/Benämning (extent/Extent/label = 300 ‡a)<br/>
Skriv in uppgiften under Benämning.
  <br/>```Exempel:```
     * ```1 DVD-video (2 tim., 7 min.)```
     * ```1 Blu-ray Disc (1 tim., 40 min.)```

### Speltid
* Speltid/speltid/Värde (hasDuration/Duration/Value = 306 #a)</br>
  Vid behov anges speltid här i kodad form.
  Skriv in uppgiften under Värde enligt formen TTMMSS.</br>
  Om sekunder inte är kända ange 00.</br>
  ```Exempel: 011200```

### Övriga fysiska detaljer   
* Övriga fysiska detaljer (other physical details = 300 ‡b)  
  ```Exempel: stum, svartvit```

### Medföljande material
* Medföljs av/Instans/Benämning (Bilagor) (accompaniedBy/Instance/label = 300 ‡e)   
Här anges medföljande material, som t ex bilagor. Lägg till Medföljs av. Skapa Instans som lokal entitet (skriv Instans i rutan Skapa lokal entitet och välj ** Instans).</br> 
Lägg till Benämning. Skriv in uppgiften.
<br/>```Exempel: 1 häfte (10 sidor)``` 

### Videokarakteristika
* Videokarakteristika (videoCharacteristics = 007/04)
  <BR/>Länka till entitet. 
Här anges format, antingen DVD eller Blu-ray Disc.
  <br/>```Exempel:```<br/>
     * ```DVD, v```<br/>
     * ```Blu-ray Disc, s```

### Seriemedlemskap
För anvisningar om hur man anger Seriemedlemskap, se hjälptexten [Instans](https://libris.kb.se/katalogisering/help/workflow-instance#seriemedlemskap): Seriemedlemskap. 

### Målgruppsanmärkning  
* Målgrupp/Målgrupp/Benämning (intendedAudience/IntendedAudience/label = 521 ‡a)  
Lägg till Målgrupp. Skapa Målgrupp som lokal entitet (skriv målgrupp i rutan Skapa lokal entitet och välj det). Skriv in uppgiften under Benämning.<BR/> 
```Exempel: Barntillåten```  

Notera att kodning av målgrupp, motsvarande 008/22, ska anges i [Målgrupp](#malgrupp) under Instans av Verk. 

### Innehållsförteckning  
För anvisningar om hur man lägger till olika typer av innehållsförteckningar, se hjälptexten [Instans](https://libris.kb.se/katalogisering/help/workflow-instance#innehallsforteckning): Innehållsförteckning.

### Systemkrav och mediespecifika uppgifter
Här kan systemkrav och mediespecifika uppgifter som inte framgår någon annanstans i beskrivningen anges. Ange uppgiften som den är presenterad i resursen.
* Har anmärkning: Systemkrav och mediespecifika uppgifter/Anmärkning: Systemkrav och mediespecifika uppgifter/Anmärkningstext (marc:hasSystemDetailsNote = 538 #a)
  </BR>```Exempel: Systemkrav: Region 2 ; bildformat: 16:9 (2.35:1 ); ljudformat: Dolby digital 5.1```

### Anmärkning
* Anmärkning/Anmärkning/Benämning (hasNote/Note/label = 500 ‡a)   
  Skriv in allmänna anmärkningar här. Här anges tills vidare produktionsland och produktionsår. 
  </BR>För att lägga till Anmärkning, välj Anmärkning (hasNote). Skriv in uppgiften under Benämning. Använd föredragen namnform för produktionsland, se Librispraxis, 16.2.2.3. 
   <br/>```Exempel:```<br/> 
   * ```Produktion: Förenta staterna, 1972```<br/>
   * ```Produktion: Storbritannien, 2018```

### Elektronisk adress
#### Relaterad beskrivning eller innehall
* Relaterad beskrivning eller innehåll/Dokument/Värddator (namn) (isPrimaryTopicOf/Dokument/marc:hostName = 856 4/2 ‡u)</BR>
  För att lägga in elektronisk adress till en relaterad resurs, till exempel delar, sammanfattningar, innehållsförteckningar eller andra resurser som på något sätt hör samman med den resurs som beskrivs i instansbeskrivningen, använd Relaterad beskrivning eller innehåll. Skapa Dokument som lokal entitet. Lägg till egenskapen URI. Klistra in aktuell URI .</BR>
* Relaterad beskrivning eller innehåll/Dokument/Offentlig anmärkning (isPrimaryTopicOf/Dokument/marc:publicNote = 856 4/0 ‡z)</br>
  Vid behov, lägg till Offentlig anmärkning. Skriv in anmärkningen.

## Verk
För att lägga till egenskaper under Instans av verk, klicka på plustecknet till höger om Instans av verk och verkstypen. Sök fram egenskapen och välj den genom att klicka på plustecknet vid egenskapens namn.

Läs mer om egenskaperna under generell beskrivning av [Verk](https://libris.kb.se/katalogisering/help/workflow-work).  

Läs mer om Verk och Instans på [Libris informationssidor på kb.se](https://www.kb.se/samverkan-och-utveckling/nytt-fran-kb/nyheter-samverkan-och-utveckling/2018-05-30-verk-och-instans-i-startversionen-av-nya-libris.html).</BR> 

### Instans av verk
* Instans av verk/Rörlig bild (instanceOf/Work/MovingImage)  
För en film är verkstypen Rörlig bild.  

### Verkets titel 
Ange vid behov den föredragna titeln för verket här. För instruktioner, se [Metadatabyrån - Föredragen titel för verket](https://metadatabyran.kb.se/beskrivning/generella-anvisningar---rda/verk-och-uttryck/foredragen-titel-for-verket).

#### Verk utan Primär medverkan
*	Uttryck av/Verk/Har titel/Titel/Huvudtitel (expressionOf/Work/hasTitle/Title/mainTitle (= 130 ‡a)  
Film har sällan en primär medverkande. För att en agent ska räknas som primär medverkande ska denne vara ansvarig för alla aspekter kopplade till skapandet av filmen. 
Ange den föredragna titeln i Huvudtitel.  
```Exempel: Gomorra (tv-serie)```    
Tillägget inom parentes (tv-serie) görs för att skilja tv-serien Gomorra från filmen Gomorra.</br> 
Läs mer om [Tillägg till auktoriserade sökingångar för verk](https://metadatabyran.kb.se/beskrivning/generella-anvisningar---rda/konstruktion-av-sokingangar-for-verk-och-uttryck/tillagg-till-auktoriserade-sokingangar-for-verk) i Metadatabyrån.</BR>

#### Verk med primär medverkan
* Har titel/Titel/Huvudtitel (hasTitle/Title/mainTitle = 240 1/0 ‡a)</BR>
Det är ovanligt att film har primär medverkan. För att en agent ska räknas som primär medverkande ska denne vara ansvarig för alla aspekter kopplade till skapandet av filmen. 
Ange den föredragna titeln i Huvudtitel.

### Medverkan och funktion
[Följ instruktioner i hjälptexten Relationer till Agent](https://libris.kb.se/katalogisering/help/workflow-agent-org-instance) 

#### Primär medverkan
* Medverkan och funktion/Primär medverkan/Agent/Person (contribution/PrimaryContribution/agent/Person = 100 1/- ‡a)  
 ```Exempel: Moore, Andy, 1956-```
* Medverkan och funktion/Primär medverkan/Funktion (contribution/PrimaryContribution/role = 100 ‡4)  
  ```Exempel: relator/fmk (= filmskapare)```</br>

#### Medverkan
* Medverkan och funktion/Medverkan/Agent/Person (contribution/agent/Person = 700 1/- ‡a)   
  ```Exempel: Wechselman, Maj, 1942-```  
* Medverkan och funktion/Medverkan/Funktion (contribution/role = 700 ‡4)  
  ```Exempel: relator/drt (= regissör)```</br>

### Språk 
* Språk (language = 008/35-37)</BR>
  Ange det talade eller sjungna språket här.</BR>
  För film som saknar ljudinnehåll (eller med ljud, men utan språkligt innehåll) ange "icke-språkligt medium".</BR>
  För en film som är dubbad ange dubbningens språk här. Om resursen innehåller både originalversionen och en eller flera dubbade versioner, ange originalversionens språk först och sedan språk/språken för dubbningen/dubbningarna.</BR>
  Länka till entitet.  
  ```Exempel: engelska (eng)``` 
 </BR>Ange flera språk genom att klicka på plustecknet vid Språk (Lägg till språk) och sök fram rätt entitet för språket.</BR>
  Länka till entitet. 

För språk i bild- och filmtexter, samt i textskyltar i stumfilm, se egenskapen [Bild- och filmtexter](#bild-och-filmtexter).

#### Översättning  
För en film som är dubbad, lägg till:  
* Anmärkning: Språk (marc:LanguageNote = 041 i1: 1)  
  Ange om resursen är/innehåller en översättning.  
**Från och med version 1.18 skapas uppgiften automatiskt.** 

**Från och med version 1.18 anges originalspråk för översättningar under Översättning av, inte som tidigare under Originalversion. OBS! För närvarande ska titel och medverkan inte läggas till under Översättning av. Fortsätt att ange dem som tidigare direkt under Instans av verk.**   

* Översättning av/Verk/Språk (translationOf/Work/language = 041 #h)  
  Filmens originalspråk anges här. För en engelsk film som är dubbad till svenska, ange engelska här. Lägg till Översättning av under Instans av verk, skapa Verk som lokal entitet. Du behöver inte välja verkstyp här. Lägg till Språk och länka till entitet.  
```Exempel: engelska (eng)``` 

### Relationer till ingående verk och andra verk
#### Relationer till ingående verk
* Ingående verk utan Medverkan och funktion/Primär medverkan Har del/Verk/Har titel/Titel (730 0/2 #a)</br> 
  Om det ingående verket är en översättning, lägg till Språk/Språk/Benämning under Verk.
  
* Ingående verk med primär medverkan (700 1/2 #a, ǂd, ǂt)  
  Se hjälptexten [Relationer till delar och verk](https://libris.kb.se/katalogisering/help/workflow-agent-relation).  

#### Relationer till andra verk
* Relationer till andra verk utan Medverkan och funktion/Primär medverkan
 Relation/Relation/Entitet/Entitet/Verk/Har titel/Titel (730 0/_ #a)</br>
 Om det ingående verket är en översättning, lägg till Språk/Språk/Benämning under Verk.
  
* Relationer till andra verk med primär medverkan (700 1/- #a, ǂd, ǂt)  
  Se hjälptexten [Relationer till delar och verk](https://libris.kb.se/katalogisering/help/workflow-agent-relation).

### Genre form 
För utförliga anvisningar om hur man anger genre/form, se hjälptexten [Verk](https://libris.kb.se/katalogisering/help/workflow-work#genre): Genre form.

#### Genre/form - saogf-termer
* Genre/form – saogf-termer (genreForm = 655 -/7 #a, #2 saogf)</br>
 Länka till entitet.
  <br/>```Exempel:```<br/> 
   * ```Spelfilmer```<br/> 
   * ```Dokumentärfilmer```

### Klassifikation
För anvisningar om hur man anger klassifikation, se hjälptexten [Verk](https://libris.kb.se/katalogisering/help/workflow-work#klassifikation): Klassifikation.

### Ämne  
* Ämne  
  Länka i första hand till entiteter för ämnesord. [Följ instruktionerna under Ämnesord i Libris](https://libris.kb.se/katalogisering/help/workflow-general-sh).  

### Målgrupp     
 * Målgrupp (intendedAudience = 008/22)  
  Länka till entitet.  
  ```Exempel: j (= barn- och ungdom, 0-16 år)```</br> 
  Normalvärde för film som riktar sig till barn och ungdom.

För att lägga till Målgruppsanmärkning (Målgrupp/Målgrupp/Benämning), se [Målgruppsanmärkning](#Malgruppsanmarkning) under Instans.

### Bild- och filmtexter 
 * Bild- och filmtexter (marc:subtitlesOrCaptions/marc:SubtitlesOrCaptions/language = 041 #j)</BR>
 Ange språk i eventuella bild- och filmtexter.</BR>
 Länka till entitet.
   ```Exempel: svenska (swe)```</BR> 
 Ange ytterligare språk genom att klicka på plustecknet vid Språk (Lägg till språk) och sök fram rätt entitet för språket.</BR>
 Länka till entitet.   
   ```Exempel: engelska (eng)``` 

### Innehållstyp
 * Innehållstyp/Innehållstyp (contentType/ContentType = 336 #b)   
  Länka till någon av entiteterna:</BR>
   * ```Two-dimensional moving image, tdi (= tvådimensionell rörlig bild)```
   * ```Three-dimensional moving image, tdm (= tredimensionell rörlig bild)``` 

### Inspelning
Under inspelning kan man såväl göra anmärkning om inspelningens tid, plats och omständigheter som ange kodade uppgifter om inspelningstid och inspelningsplats.

#### Anmärkning om inspelningens tid, plats och omständigheter.
* Inspelning/Inspelning/Benämning (capture/Inspelning/label = 518 #a)</BR>
 Skriv in uppgiften under Benämning.</BR>
   ```Exempel: Inspelad 2010 i Konserthuset, Stockholm```

#### Kodade uppgifter om inspelningstid och inspelningsplats.
* Inspelning/Inspelning/Datum (capture/Inspelning/date = 033 #a)</BR>
  Under Inspelning, lägg till Inspelning som lokal entitet genom att klicka på plustecknet, Lägg till entitet.
  Lägg till Datum genom att klicka på plustecknet, Lägg till egenskaper under: Inspelning. Skriv in uppgiften.</BR>
    ```Exempel: 2010```

* Inspelning/Inspelning/Plats/Plats/Benämning (capture/Inspelning/place/Plats = 033 #p)</BR>
  Klicka igen på plustecknet, Lägg till egenskaper under: Inspelning. Lägg till Plats.
  Under Plats, lägg till Plats som lokal entitet genom att klicka på plustecknet, Lägg till entitet.
  Klicka på plustecknet bredvid Plats, Lägg till egenskaper under Plats och lägg till Benämning. Skriv in uppgiften.</BR>
   ```Exempel: Stockholm```

### Anmärkningar
#### Anmärkning om språk
 * Anmärkning/Anmärkning om språk/Benämning (hasNote/marc:LanguageNote/marc:LanguageNote/label = 546 #a)  
  ```Exempel: Tal på engelska. Dubbad till svenska, finska, norska. Textad på engelska, svenska, finska och norska.```  

#### Anmärkning om medverkande
 * Anmärkning/Anmärkning om medverkande/Benämning (hasNote/marc:ParticipantOrPerformerNote/label = 511 #a)
  ```Exempel: Skådespelare: Nicole Kidman, Kirsten Dunst, Elle Fanning```

### Sammanfattning av innehåll
* Sammanfattning av innehåll/Sammanfattning/Benämning (summary/Summary/label = 520 #a)</BR>
Lägg till Sammanfattning av innehåll. Välj Sammanfattning av innehåll. Lägg till Sammanfattning. Skriv in uppgiften under Benämning.
</br>```Exempel: Historien utspelar sig under amerikanska inbördeskriget på en internatskola för flickor i södern. När de avskärmade unga kvinnorna tar in en skadad fiendesoldat och ger honom skydd och vård stiger den sexuella spänningen, farliga rivaliteter bildas och tabun bryts i en oväntad vändning.```

 * Typ av sammanfattning/typ av innehållsbeskrivning (marc:summaryType = 520 ind1)  
 Sök fram och lägg till Typ av sammanfattning. Välj typ från lista.  
 ```Exempel: Ej preciserad``` 
