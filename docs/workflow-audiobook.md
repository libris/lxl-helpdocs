---
section: Materialtyper
title: Ljudbok
order: 47
date: 2020-05-14
tags:
- under arbete
- ljudbok
--- 

# Ljudbok
Denna hjälptext ger kortfattade instruktioner för de vanligaste egenskaperna för en ljudbok - ljudinspelning (tillgänglig på CD eller MP3-CD). För utförliga instruktioner, se de generella hjälptexterna för Adminmetadata, Instans och Verk, se nedan.

## Innehåll  

[Inledning](#inledning)

| [Adminmetadata](#adminmetadata) | [Instans](#instans) | [Verk](#verk) | 
| ----------- | ----------- |  ----------- |
| [Generell hjälptext för Adminmetadata](https://libris.kb.se/katalogisering/help/workflow-adminmetadata) | [Generell hjälptext för Instans](https://libris.kb.se/katalogisering/help/workflow-instance) | [Generell hjälptext för Verk](https://libris.kb.se/katalogisering/help/workflow-work) |
| | [Utgivningssätt](#utgivningssatt) | [Verkets titel](#verkets-titel) |
| | [Medietyp](#medietyp) | [Medverkan och funktion](#medverkan-och-funktion) |
| | [Bärartyp](#barartyp) | [Språk](#sprak) |
| | [Titel](#titel) | [Relationer till ingående verk och andra verk](#relationer-till-ingaende-verk-och-andra-verk) |
| | [Upphovsuppgift](#upphovsuppgift) | [Genre/form](#genre-form) |
| | [Upplageuppgift](#upplageuppgift) | [Klassifikation](#klassifikation) |
| | [Utgivning](#utgivning) | [Ämne](#amne) |
| | [Copyrightår eller p-år](#copyrightar-eller-p-ar) | [Målgrupp](#malgrupp) |
| | [Identifikator](#identifikator) |[Innehållstyp](#innehallstyp) |
| | [Omfång](#omfang) | [Anmärkning om medverkande](#anmarkning-om-medverkande) |
| | [Övriga fysiska detaljer](#ovriga-fysiska-detaljer) | [Sammanfattning av innehåll](#sammanfattning-av-innehall)  |
| | [Medföljande material](#medfoljande-material) | |
| | [Seriemedlemskap](#seriemedlemskap) | | 
| | [Innehållsförteckning](#innehallsforteckning) | | 
| | [Anmarkning](#anmarkning) | |
| | [Kodningsformat](#kodningsformat) | | 

## Inledning
Beskrivningen av en ljudbok innehåller följande tre delar:  
* [Adminmetadata](https://libris.kb.se/katalogisering/help/workflow-adminmetadata) - administrativa data om instansbeskrivningen, såsom kontrollnummer och beskrivningsnivå
* [Instans](https://libris.kb.se/katalogisering/help/workflow-instance) - instans kan också kallas utgåva eller manifestation. Exempel på egenskaper under Instans är utgivningsplats, utgivare och utgivningsår, bärartyp, omfång.
* [Verk](https://libris.kb.se/katalogisering/help/workflow-work) – återger egenskaper för det abstrakta verket såsom medverkan och funktion (t.ex. författare), ämne, klassifikation, språk och innehållstyp. Verksbeskrivningen ligger under rubriken Instans av verk.

Många av egenskaperna finns redan i mallen Ljudbok, andra kan behöva läggas till. För instruktioner om att lägga till eller ta bort egenskaper, länka till entitet, skapa lokal entitet och om hur formuläret fungerar i övrigt, se Redigering i vänstermenyn. För en förhandspost, använd gärna Berika från mall och välj Ljudbok.  

För information om katalogregler och Librispraxis, [se Anvisningar för katalogisering - RDA](http://www.kb.se/rdakatalogisering/ "Anvisningar för katalogisering - RDA") samt [RDA Toolkit](https://access.rdatoolkit.org/). Notera att för utgivna fonogram är hela resursen godkänd källa. Uppgifterna får tas utan prioritetsordning från det ställe där de anses vara bäst. [Denna Librispraxis, KB SP 2.2.2.4.1](http://access.rdatoolkit.org/kbspchp2_kbsp2-51.html), bygger på IASA Cataloguing Rules och är en avvikelse från [RDA 2.2.2.4.1](http://access.rdatoolkit.org/rdachp2_rda2-2904.html). 

[Se även instruktionsfilmer på KB:s Youtubekanal](https://www.youtube.com/playlist?list=PLZVkEICvA5-GRT2oJQmLgq_2Pksx6zYPy).

## Adminmetadata
[Använd generell hjälptext för Adminmetadata](https://libris.kb.se/katalogisering/help/workflow-adminmetadata).
* Kontrollera beskrivningsnivån. I mallen är standardvärdet Biblioteksnivå (normalvärde för Librisbiblioteken). Ändra vid behov.
**Observera: Om nivån är CIP-post eller preliminär post, ändra till annan nivå, annars kan ändringar skrivas över!** 

## Instans
För att lägga till egenskaper under Instans, klicka på plustecknet i redigeringsvyn (den stora runda plusikonen under Verktygsikonen - Lägg till egenskaper under: Ljudinspelning). Sök fram egenskapen och välj den genom att klicka på plustecknet vid egenskapens namn.  

### Utgivningssatt
* Utgivningssätt (issuanceType)   
  Välj från lista.  
  ```Exempel: Monografisk resurs```
  
### Medietyp
* Medietyp (mediaType/Mediatype = 337 #b)  
  Länka till entiteten:  
  ```Audio, s (= audio)```
  
### Barartyp
* Bärartyp (carrierType/CarrierType = 338 #b)  
  Välj Bärartyp i listan över typer.
  Länka till entiteten:</br>
  ```Audio disc, sd (= ljudskiva)```</BR>
  
  Om koden "d" (= ljudskiva) behövs i 007/01 (= särskild bärarbeteckning) för bibliotekets lokala system länka även till entiteten: </BR>
  ```Ljudskiva, d```
  
### Titel
Notera att egenskapen Allmän medieterm (marc:mediaTerm = 245 #h) (= Medieterm) inte ska ingå i beskrivningar som görs enligt RDA.

#### Huvudtitel    
* Har titel/Titel/Huvudtitel (hasTitle/Title/mainTitle = 245 #a)  
  Återge huvudtiteln som den förekommer i källan, [se Librispraxis 2.2.2.4.1](http://access.rdatoolkit.org/kbspchp2_kbsp2-51.html).</BR> 
 ```Exempel: Den frusna elden```  
För en titel som börjar med bestämd eller obestämd artikel, ska artikeln fileras bort. Ange fileringsvärde genom att lägga till fileringsvärde (plustecknet vid Titel - Lägg till egenskaper under: Titel) och ange en siffra.  
 ```Exempel: Huvudtitel: Den frusna elden, fileringsvärde: 4```  
 [Se exempel i formathandboken för Libris/Voyager - Fileringsindikator]( http://www.kb.se/katalogisering/Formathandboken/Fileringsindikator/)

För att ange Föredragen titel, se Verk/Har titel/Titel/Huvudtitel.  

#### Övrig titelinformation (undertitel)
* Har titel/Titel/Övrig titelinformation (= Undertitel) (hasTitle/Title/subtitle = 245 #b)  
  Skriv in uppgiften. Om det finns flera undertitlar, skriv in dessa efter varandra i samma fält, åtskilda av mellanslag, kolon, mellanslag.    
 ```Exempel: C-byråns kvinnliga agenter under andra världskriget : en dokumentär spionberättelse```

#### Varianttitel   
En varianttitel är en titel förknippad med resursen som skiljer sig från den titel som angivits som huvudtitel, [se RDA 2.3.6](http://access.rdatoolkit.org/rdachp2_rda2-4004.html). Här anges t.ex. varianter för titlar som innehåller specialtecken, siffror eller oväntade stavningar av ord.</BR>
För att lägga till varianttitel, klicka på plustecknet vid Har titel (lägg till titel) och välj typ Varanttitel.
* Har titel/Varianttitel/Huvudtitel (hasTitle/VariantTitle/mainTitle = 246 #a)   
  Skriv in uppgiften i Huvudtitel.    
 ```Exempel: Hierarchy in organizations```  

För en parallell huvudtitel på ett annat språk eller i en annan skriftart, [se Parallelltitel](#parallelltitel).

Om huvudtiteln är felstavad i källan anges en korrekt form av titeln som en varianttitel. Notera dock att för utgivna fonogram är hela resursen godkänd källa, utan prioritetsordning, [se Librispraxis 2.2.2.4.1](http://access.rdatoolkit.org/kbspchp2_kbsp2-51.html). Det innebär att man vanligen kan hitta en korrekt form av titeln och ange den som huvudtitel.

En varianttitel kan specificeras med en Typanmärkning, en anmärkningstext som i ett sökgränssnitt ska föregå varanttiteln. För att lägga till en Typanmärkning, klicka på plustecknet vid Varianttitel (Lägg till egenskaper under: Varianttitel) och välj Typanmärkning.

* Har titel/Varianttitel/Typanmärkning (hasTitle/VariantTitle/typeNote = 246 1/_ #i)  
  ```Exempel: Titeln felstavad, korrekt titel:```   
    
#### Delbeteckning och deltitel
För anvisningar om hur man anger delbeteckning och deltitel, [se hjälptexten Instans](https://libris.kb.se/katalogisering/help/workflow-instance#titel): Titel. 
  
#### Parallelltitel  
Ange parallelltitel här. Upprepa inte parallelltitel efter Har titel/Titel/Huvudtitel (245 #a) med interpunktion.   
* Har titel/Parallelltitel/Huvudtitel (hasTitle/ParallelTitle/mainTitle = 246 1/1 #a)   
Välj först Har titel, välj sedan typ Parallelltitel.      
Skriv in uppgiften i Huvudtitel.     
  ```Exempel: The Great Northern War explained```</br>
  För en titel som börjar med bestämd eller obestämd artikel, ska artikeln fileras bort. Lägg till fileringsvärde och ange en siffra.
* Har titel/Parallelltitel/Övrig titelinformation (hasTitle/ParallelTitle/subTitle = 246 1/1 #b)
Vid behov, klicka även på plustecknet vid Parallelltitel och lägg till Övrig titelinformation (subtitle).  
  ```Exempel: Charles XII and the ideological address```  
  
### Upphovsuppgift
* Upphovsuppgift (responsibilityStatement = 245 #c)  
  ```Exempel: Tom Marcus ; översättning: Svante Skoglund```
  
### Upplageuppgift
* Upplageuppgift (editionStatement = 250 #a)</BR>
  Skriv in upplagebeteckning här.  
  ```Exempel: Första upplagan```  
  
### Utgivning  
* Utgivning (publication)  
  Välj typ från lista. För monografisk resurs, använd Primär utgivning.  
  I konverterade och maskininlästa poster finns det ibland två avsnitt: ett Primär utgivning med År och Land, och ett Utgivning med Plats, Agent och Datum. När man redigerar maskininlästa poster med två utgivningsavsnitt får man, om man bedömer det nödvändigt, flytta uppgifterna om Plats, Agent och Datum till avsnittet Primär utgivning och ta bort avsnittet Utgivning.   
NB inväntar en maskinell ändring av dessa poster och ändrar inte manuellt.    
  Vid postimport: I importerade poster förekommer ibland både År och Copyrightår inom Utgivning (= 008/06: t, 008/07-10: År och 008/11-14: Copyrightår). Låt uppgiften ligga kvar oförändrad.      
Om posten är katalogiserad enligt RDA kan även Copyright/Copyright/Datum (copyright/Copyright/date = 264 -/4 #c) finnas med.
 
#### Utgivningsplats
* Plats/Plats/Benämning (= Utgivningsort) (place/label = 264 -/1 #a)  
  Sök inte efter Plats som entitet. Skapa Plats som lokal entitet. Skriv in uppgiften under Benämning. Klamra vid behov.</br>
  ```Exempel: [Malmö]```  
  
#### Utgivningsland  
* Land (country = 008/15-17)  
  Länka till entitet.  
  ```Exempel: Sverige (sw)``` 
  
#### Utgivarnamn
* Agent/Agent/Benämning (= Utgivarnamn) (agent/label = 264 -/1 #b)  
  Sök inte efter Agent som entitet. Skapa Agent som lokal entitet. Skriv in uppgiften under Benämning.  
  ```Exempel: Bokfabriken```   
  Om flera utgivare ska anges, lägg till Har del (hasPart) under Primär utgivning. Skapa Utgivning som lokal entitet. I rutan Skapa lokal entitet, skriv Utgivning och välj *** Utgivning. Upprepa Utgivning som lokal entitet genom att duplicera entiteten Utgivning. Ange Plats/Plats/Benämning och Agent/Agent/Benämning inom respektive utgivningsavsnitt. Samtliga utgivare med Plats och Agent ska ligga inom Har del/Utgivning. Land, År och eventuellt Datum ska ligga inom Primär utgivning.  
  [Se exempelpost i Libris katalogisering](https://libris.kb.se/katalogisering/w4rp4hlwtr5lctjr#it).
  
#### År och datum 
  * År (= Utgivningstid) (date = 008/07-10, 264 -/1 #c)  
  År får endast innehålla siffror (0-9) och bokstaven u. År ska endast förekomma inom Primär utgivning.  
  Utgivningsår anges här, utan klamrar eller andra tecken - endast fyra positioner. Det kommer då att exporteras till både marcpostens 08/07-10 och 264 -/1 #c.</br>
  ```Exempel: 2017```</br>
 
 Observera att År måste finnas med i beskrivningen, även om datum finns med.</br>
  
  För att ange årtal med klamrar eller andra tecken utöver fyra positioner, använd Datum.
  * Datum (= Utgivningstid) (date = 264 -/1 #c)  
  Datum får innehålla text och interpunktionstecken.  
  Utgivningsdatum med fler än fyra positioner, till exempel ett klamrat årtal, anges här. Det kommer att exporteras till marcpostens  264 -/1 #c.
   <br/>```Exempel:```
    * ```[2017]```
    * ```[mellan 2003 och 2005?]``` 

För att ange ett år utan klamrar eller andra tecken, använd År.

För att ange ett osäkert utgivningsdatum där endast tidigaste och senaste årtal kan anges, [följ exempel i hjälptexten Instans](https://libris.kb.se/katalogisering/help/workflow-instance#produktion): Produktion: Huvudsakligt tillgängliggörande. 
  
* Flera år (flerbandsverk)  
 För anvisningar om hur man anger flera år (flerbandsverk), [se hjälptexten Instans](https://libris.kb.se/katalogisering/help/workflow-instance#utgivning): Utgivning. 
 
 [Läs mer om År och Datum i inlägg på Supportforum för nya Libris](https://kundo.se/org/librisxl/d/falt-for-utgivningsar/)  
  
### Copyrightar eller p-ar
För fonogram anges alltid copyright- eller p-år, även om det sammanfaller med med utgivningsår, [se Librispraxis 2.11](http://access.rdatoolkit.org/kbspchp2_kbsp2-1030.html). Det går bara att ange ett år här, så om både copyright- och p-år förekommer i resursen ange det senaste p-året.</br>
* Copyright/Copyright/Datum (copyright/Copyright/date = 264 -/4 #c)  
  Skriv in uppgiften. För att få fram © eller ℗, kopiera härifrån eller sök på teckenuppsättning i “Sök i windows” och öppna programmet, markera och kopiera tecknet och sedan klistra in det.
   <br/>```Exempel:```
    * ```©2017```
    * ```℗2017```
     
### Identifikator 
Flera typer av identifikatorer kan finnas på ljudböcker. I mallen är Utgivningsnummer (ljudinspelning) och ISBN förvalda.
#### Utgivningsnummer (ljudinspelning)
* Identifikator (identifiedBy)<br/>
  Välj typ från lista.
  <br/>```Exempel: Utgivningsnummer (ljudinspelning)```
* Identifikator/Utgivningsnummer (ljudinspelning)/Värde (identifiedBy/AudioIssueNumber/value = 028 #a)<br/>
  Ange utgivningsnumret som det förekommer i resursen.
  <br/>```Exempel: NA242512```
* Identifikator/Agent/Organisation/Namn (= Utgivare) (identifiedBy/agent/Organization/name = 028 #b)<br/>
  Ange utgivarens namn.
  <br/>```Exempel: Naxos AudioBooks```<br/>
* Identifikator/Särskiljande tillägg (= Bestämning) (identifiedBy/qualifier = 020 #q)  
  Ange eventuell bestämning.    
  
#### ISBN
* Identifikator (identifiedBy)  
  Välj typ från lista.  
  ```Exempel: ISBN```
* Identifikator/ISBN/Värde (identifiedBy/Isbn/value = 020 #a)  
  Ange identifikator.  
  ```Exempel: 9789188107213```
* Identifikator/Särskiljande tillägg (= Bestämning) (identifiedBy/qualifier = 020 #q)  
  Ange eventuell bestämning.  

För ogiltiga ISBN, använd Indirekt identifierad av, direkt under Instans. Använd inte Ogiltigt värde under Identifikator/ISBN (identifiedBy/marc:hiddenValue).  
  
### Indirekt identifierad av  
Ange ogiltiga ISBN här och inte under Identifikator/ISBN/Ogiltigt värde. 
* Indirekt identifierad av/ISBN (indirectlyIdentifiedBy/ISBN = 020 #z)  
  Välj typ från lista.  
  ```Exempel: ISBN```
* Indirekt identifierad av/ISBN/Värde (indirectlyIdentifiedBy/Isbn/value = 020 #a)  
  Skriv in uppgiften.  
  ```Exempel: 97891881072```
* Indirekt identifierad av/Särskiljande tillägg (= Bestämning) (indirectlyIdentifiedBy/qualifier = 020 #q)  
  Ange eventuell bestämning.  
    
### Omfang
Ange antal enheter samt typ av enhet, [se RDA 3.4.1.3](http://access.rdatoolkit.org/rdachp3_rda3-2098.html) samt [Librispraxis för Alternativ](http://access.rdatoolkit.org/kbspchp3_kbsp3-95.html). Ange speltid (inom parentes) efter omfång när uppgiften är lätt åtkomlig. 
* Omfång/Omfång/Benämning (extent/Extent/label = 300 #a)   
  Skriv in uppgiften under Benämning.  
  ```Exempel: 11 CD (13 tim., 30 min.) ```

Om filformatet är MP3 ska det inte anges här utan i Digital karakteristika/Kodningsformat/Benämning, [se Kodningsformat](#kodningsformat).

För att uppgiften om filformat ska vara synlig i Libris Webbsök eller i den lokala bibliotekskatalogen, ange den även i en anmärkning, [se Anmärkning](#anmarkning).
  
### Ovriga fysiska detaljer   
* Övriga fysiska detaljer (other physical details = 300 #b)     
  ```Exempel: stereo```
  
### Medfoljande material
* Medföljs av/Instans/Benämning (Bilagor) (accompaniedBy/Instance/label = 300 #e)   
Här anges medföljande material, t ex bilagor. Lägg till Medföljs av. Skapa Instans som lokal entitet (skriv Instans i rutan Skapa lokal entitet och välj ** Instans). Lägg till Benämning. Skriv in uppgiften. 
<br/>```Exempel: 1 bildhäfte (20 sidor)```<br/> 
Ibland medföljer en extra MP3-CD (med samma ISBN) vid distribution och försäljning av CD-ljudböcker.
<br/>```Exempel: 1 MP3-CD```

### Seriemedlemskap
För anvisningar om hur man anger Seriemedlemskap, [se hjälptexten Instans](https://libris.kb.se/katalogisering/help/workflow-instance#seriemedlemskap): Seriemedlemskap. 
   
### Innehallsforteckning  
För anvisningar om hur man lägger till olika typer av innehållsförteckningar, [se hjälptexten Instans](https://libris.kb.se/katalogisering/help/workflow-instance#innehallsforteckning): Innehållsförteckning.

### Anmarkning
* Anmärkning/Anmärkning/Benämning (hasNote/Note/label = 500 #a)  
  Skriv in allmänna anmärkningar här.  
  För att lägga till Anmärkning, välj Anmärkning (hasNote). Skriv in uppgiften under Benämning.</BR> 
  ```Exempel:```
  * ```Inläst ur: Stockholm : Bonnier, 2012. ISBN 978-91-0-012761-9```
  * ```MP3```
  
### Kodningsformat
  * Digital karakteristika/Kodningsformat/Benämning (digitalCharacteristic/EncodingFormat/label = 347#b)</BR>
Ange filformat här.</BR>
Lägg till Digital karakteristika. Lägg till Kodningsformat som lokal entitet. Skriv in uppgiften under Benämning.</BR>
  ```Exempel: MP3```
  
## Verk   

### Instans av Verk (instanceOf/Work)  
 Skapa verket som lokal entitet (bryt inte ut verket till en länkbar entitet). Denna hjälptext beskriver exempel på verk som lokal entitet. Det betyder att du anger de uppgifter som listas här nedan, under Instans av Verk, utan att klicka på länksymbolen (Länka entitet) vid Instans av Verk.</br>
[Läs mer om Verk och Instans på Libris informationssidor på kb.se](https://www.kb.se/samverkan-och-utveckling/nytt-fran-kb/nyheter-samverkan-och-utveckling/2018-05-30-verk-och-instans-i-startversionen-av-nya-libris.html).  

För att lägga till egenskaper under Instans av Verk, klicka på plustecknet till höger om Instans av Verk - Lägg till egenskaper under: Ljud. Sök fram egenskapen och välj den genom att klicka på plustecknet vid egenskapens namn.  

### Verkets titel
 
Ange vid behov den föredragna titeln för verket här. [Följ anvisningarna under Konstruera sökingångar för verk och uttryck i Anvisningar för katalogisering - RDA](http://www.kb.se/rdakatalogisering/Anvisningar/Allmanna-anvisningar/Sokingangar-for-verk-och-uttryck/). Föredragen titel ska anges för översättningar och för verk som har givits ut under olika titlar på samma språk. En föredragen titel ska också anges om olika verk har samma auktoriserade sökingång. 

#### Verkets titel - verk med primär medverkan
Föredragen titel för ett verk med primär medverkan ska anges i Har titel/Titel/Huvudtitel .</BR>
* Har titel/Titel/Huvudtitel (hasTitle/Title/mainTitle = 240 1/0 #a)</br>
Ange den föredragna titeln i Huvudtitel.</br>
  ```Exempel: Iliaden```  
  För en titel som börjar med bestämd eller obestämd artikel, ska artikeln fileras bort. Ange fileringsvärde genom att lägga till fileringsvärde och ange en siffra.  
* Har titel/Titel/Deltitel (hasTitle/Title/partName = 240 1/0 #p)</BR> 
Lägg till eventuell deltitel (plustecknet vid Titel - lägg till egenskaper under: Titel, välj Deltitel).</BR>
* Har titel/Titel/Delbeteckning (hasTitle/Title/partNumber = 240 1/0 #n)</BR>
Lägg till eventuell delbeteckning (plustecknet vid Titel - lägg till egenskaper under: Titel, välj Delbeteckning).</BR> 
  ```Exempel: Bok 1-6```<br/>
* Språk/Språk/Benämning (language/Language/label = 240 #l)</BR>
**Från och med version 1.7 skapas språktillägget automatiskt, för 240 #l. Språktillägget skapas även när det inte är en översättning. Det kommer att korrigeras i en kommande release av Libris katalogisering.**
 
#### Verkets titel - verk utan primär medverkan
Föredragen titel för ett verk utan primär medverkan ska anges i Uttryck av verk/Verk/Har titel/Huvudtitel .</BR>
*	Uttryck av/Verk/Har titel/Titel/Huvudtitel (expressionOf/Work/hasTitle/Title/mainTitle (= 130 #a)  
Under Instans av Verk, lägg till egenskapen Uttryck av. Skapa verk som lokal entitet (plustecknet vid Uttryck av - Lägg till verk, välj Skapa lokal entitet, längst ner i sidorutan till höger), välj Verk. Det läggs till under Uttryck av. Lägg till Har titel. Välj Titel. Ange den föredragna titeln i Huvudtitel.</br>
  ```Exempel: Bibeln```</br>
För en titel som börjar med bestämd eller obestämd artikel, ska artikeln fileras bort. Ange fileringsvärde genom att lägga till fileringsvärde och ange en siffra.  
*	Uttryck av/Verk/Har titel/Titel/Deltitel (expressionOf/Work/hasTitle/Title/partName = 130 #p)  
Lägg till eventuell deltitel (plustecknet vid Titel - lägg till egenskaper under: Titel, välj Deltitel).</br>
```Exempel: Nya testamentet```</br>
*	Uttryck av/Verk/Har titel/Titel/Delbeteckning (expressionOf/Work/hasTitle/Title/partName = 130 #n)  
Lägg till eventuell delbeteckning (plustecknet vid Titel - lägg till egenskaper under: Titel, välj Delbeteckning).  
*	•	Uttryck av/Verk/Språk (expressionOf/Work/language = 130 #l)
Lägg till eventuellt språk som ska ingå i sökingången. Klicka på plustecknet vid Verk (Lägg till egenskaper under: Verk) och välj Språk. Klicka på plustecknet vid Språk (Lägg till språk) och sök fram språkentiteten och länka. Språket visas då som ett tillägg till verkets titel i marcpostens 130 #l.

### Medverkan och funktion  
* Medverkan och funktion</br>
  Under Medverkan och funktion, ange relationer till de agenter som medverkar i verket samt funktionskod för respektive agent. Relationer till utgivare (710) anges för närvarande också här.</br>
  För ytterligare instruktioner om hur man anger relationer till agenter, se: [Relationer till Agent](https://libris.kb.se/katalogisering/help/workflow-agent-org-instance).</BR>
  [Se även Auktoritetsgruppens rekommendationer på Supportforum för nya Libris](https://kundo.se/org/librisxl/d/kbs-auktoritetsgrupp-informerar-jraz/). 
  
#### Primär medverkan
* Medverkan och funktion/Primär medverkan/Agent/Person (contribution/PrimaryContribution/agent/Person = 100 1/- #a)  
  Länka till entitet. Börja alltid med att söka efter om agenten redan finns. Vid behov, skapa ny entitet för agent: [se hjälptext Skapa ny agent](https://libris.kb.se/katalogisering/help/workflow-agent-person-new)). I undantagsfall, skapa lokal entitet.
<br/>```Exempel: Lindgren, Astrid, 1907-2002```
  
* Medverkan och funktion/Primär medverkan/Funktion (contribution/PrimaryContribution/role = 100 #4)  
  Länka till entitet. Klicka på plustecknet vid Funktion (Lägg till funktion) och sök fram funktionskod. Skriv in kod eller utskriven form i sökrutan eller tryck på mellanslagstangenten för att se alla koder. Välj kod genom att klicka på plustecknet vid koden eller på koden.</br> 
  ```Exempel: relator/author (= författare)```</br>
För en sorterad lista på koder, [se Formathandboken för Libris/Voyager - Funktions- och relationskoder](http://www.kb.se/katalogisering/Formathandboken/Funktionskoder/)  

#### Medverkan
* Medverkan och funktion/Medverkan/Agent/Person (contribution/agent/Person = 700 1/- #a)  
  Länka till entitet. Börja alltid med att söka efter om agenten redan finns. Vid behov, skapa ny entitet för agent: [se hjälptext Skapa ny agent](https://libris.kb.se/katalogisering/help/workflow-agent-person-new)). I undantagsfall, skapa lokal entitet.
  ```Exempel: Sauk, Stefan, 1955-```  
* Medverkan och funktion/Medverkan/Funktion (contribution/role = 700 #4)  
  Länka till entitet. Klicka på plustecknet vid Funktion (Lägg till funktion) och sök fram funktionskod. Skriv in kod eller utskriven form i sökrutan eller tryck på mellanslagstangenten för att se alla koder. Välj kod genom att klicka på plustecknet vid koden eller på koden.</br>
  ```Exempel: relator/nrt (= berättare, inläsare)```</br> 
För en sorterad lista på koder, [se Formathandboken för Libris/Voyager - Funktions- och relationskoder](http://www.kb.se/katalogisering/Formathandboken/Funktionskoder/)     

### Sprak 
* Språk (language = 008/35-37)  
  Ange det talade språket här. För att ange originalspråk för ett översatt verk, se Originalversion/Verk/Språk.  
  Länka till entitet.  
  ```Exempel: svenska (swe)```  
  Ange flera språk genom att klicka på plustecknet vid Språk (Lägg till språk) och sök fram rätt entitet för språket.</BR>
  Länka till entitet. 
  
#### Översättning 
* Anmärkning: Språk (marc:LanguageNote = 041 i1: 1)  
  Ange om resursen är/innehåller en översättning.  
  För att lägga till uppgiften, klicka på plustecknet vid Instans av verk och välj Anmärkning: Språk. Välj fras från lista</BR>
  ```Exempel: objektet är/innehåller översättning```   
* Originalversion/Verk/Språk (originalversion/Work/language = 041 #h)  
  Ange det språk som texten är översatt från. För en text som är översatt från engelska till svenska, ange engelska här.   
  Klicka på plustecknet vid Instans av Verk, välj Originalversion, klicka på plustecknet vid Originalversion, välj Skapa lokal entitet. Skriv Verk i rutan för Skapa lokal entitet och välj * Verk. Lägg till Språk under verk. Sök fram språkentiteten och länka.  
  ```Exempel: engelska (eng)```  
För översättningar i flera led, länka först till det mellanliggande språket och därefter till originalspråket. 

### Relationer till ingaende verk och andra verk
#### Verk som ingår i det beskrivna verket 
För att ange verk som ingår i det beskrivna verket, motsvarande fält 700 1/2 #a, #d, #t (analytisk sökingingång för verk med primär medverkan) eller 730 0/2 #a (analytisk sökingång för verk utan primär medverkan):  
Under Instans av Verk, lägg till Har del. Skapa verk som lokal entitet. Lägg till Har titel och välj Titel. Ange föredragen titel i Huvudtitel.</br> 
Lägg till eventuell deltitel, delbeteckning och språk som ska ingå i sökingången. (För att lägga till språk, klicka på plustecknet vid Verk (Lägg till egenskaper under: Verk) och välj Språk. Klicka på plustecknet vid Språk (Lägg till språk) och sök fram språkentiteten och länka. Språket visas då som ett tillägg till verkets titel i marcpostens 700 eller 730 #l.)</br> 
För ingående verk med primär medverkan, lägg till Medverkan och funktion/Primär medverkan enligt anvisningarna under [Medverkan och funktion](#medverkan-och-funktion) : Primär medverkan. 
För utförligare instruktioner, [se även hjälptexten Relationer till delar och verk](https://libris.kb.se/katalogisering/help/workflow-agent-relation).

#### Relationer till andra verk
För att ange verk som är relaterade, men inte ingår i det beskrivna verket, motsvarande fält 700 1/- #a, #d, #t (icke-analytisk sökingingång för verk med primär medverkan) eller 730 0/_ #a (icke-analytisk sökingång för verk utan primär medverkan) i marc: 
Under Instans av Verk, lägg till Relation. Välj typ Relation. Lägg till Entitet och välj Entitet. Skapa verk som lokal entitet. Lägg till Har titel och välj Titel. Ange föredragen titel i Huvudtitel.</br> 
Lägg till eventuell deltitel, delbeteckning och språk som ska ingå i sökingången. (För att lägga till språk, klicka på plustecknet vid Verk (Lägg till egenskaper under: Verk) och välj Språk. Klicka på plustecknet vid Språk (Lägg till språk) och sök fram språkentiteten och länka. Språket visas då som ett tillägg till verkets titel i marcpostens 700 eller 730 #l.)</br>
För ingående verk med primär medverkan, lägg till Medverkan och funktion/Primär medverkan enligt anvisningarna under [Medverkan och funktion](#medverkan-och-funktion) : Primär medverkan.
För utförligare instruktioner, [se även hjälptexten Relationer till delar och verk](https://libris.kb.se/katalogisering/help/workflow-agent-relation).
  
### Genre form 
För utförliga anvisningar om hur man anger genre/form, [se hjälptexten Verk:](https://libris.kb.se/katalogisering/help/workflow-work#genre-form) Genre form.

* Genre/form – saogf-termer (genreForm = 655 -/7 #a, #2 saogf)</br>
Länka till entiteten:</br>
```Ljudböcker```

* Genre/form – termer som motsvarar marc-koder i 008</br>
Välj Typ av genre för text till ljudupptagning (ej musik).</br>
Länka till entitet.</br>
```Exempel: Skönlitterär prosa, f```

### Klassifikation  
För anvisningar om hur man anger klassifikation, [se hjälptexten Verk:](https://libris.kb.se/katalogisering/help/workflow-work#klassifikation) Klassifikation.
   
### Amne
* Ämne  
  Länka  i första hand till entiteter för ämnesord. [Följ instruktionerna under Ämnesord i Libris](https://libris.kb.se/katalogisering/help/workflow-general-sh).   
  
### Malgrupp     
 * Målgrupp (intendedAudience = 008/22)  
  Länka till entitet.  
  ```Exempel: j (= barn- och ungdom, 0-16 år)```
    </br>Normalvärde för barn- och ungdomslitteratur.
 
För att lägga till Målgruppsanmärkning (Målgrupp/Målgrupp/Benämning), [se Målgruppsanmärkning](#Malgruppsanmarkning) under Instans.

### Innehallstyp
* Innehållstyp/Innehållstyp (contentType/ContentType = 336 #b)   
  Länka till entiteteten: 
  </br>```SpokenWord, spw (= tal)```  
  
### Anmarkning om medverkande
 * Anmärkning/Anmärkning om medverkande/Benämning (hasNote/marc:ParticipantOrPerformerNote/label = 511 #a)
   </br>```Exempel: Inläsare: Gunilla Röör```
  
### Sammanfattning av innehall    
* Sammanfattning av innehåll/Sammanfattning/Benämning (summary/Summary/label = 520 #a)</BR>
Lägg till Sammanfattning av innehåll. Välj Sammanfattning av innehåll. Lägg till Sammanfattning. Skriv in uppgiften under Benämning.
     
 * Typ av sammanfattning/typ av innehållsbeskrivning (marc:summaryType = 520 ind1)  
 Sök fram och lägg till Typ av sammanfattning. Välj typ från lista.  
 ```Exempel: Ej preciserad```
