---
section: Materialtyper
title: Datorspel
order: 40
date: 2020-02-06
tags:
- under arbete
- datorspel
- TV-spel
--- 

## Datorspel - multimedia

### Innehåll   

[Inledning](#inledning)

| [Adminmetadata](#adminmetadata) | [Instans](#instans) | [Verk](#verk) | 
| ----------- | ----------- |  ----------- |
| [Generell hjälptext för Adminmetadata](https://libris.kb.se/katalogisering/help/workflow-adminmetadata) | [Generell hjälptext för Instans](https://libris.kb.se/katalogisering/help/workflow-instance) | [Generell hjälptext för Verk](https://libris.kb.se/katalogisering/help/workflow-work) |
| | [Utgivningssätt](#utgivningssatt) | [Verkets titel](#verkets-titel) |
| | [Medietyp](#medietyp) | [Medverkan och funktion](#medverkan-och-funktion) |
| | [Bärartyp](#barartyp) | [Språk](#sprak) |
| | [Titel](#titel) | [Relationer till ingående verk och andra verk](#relationer-till-ingaende-verk-och-andra-verk) |
| | [Upphovsuppgift](#upphovsuppgift) |  [Genre/form](#genre-form) |
| | [Upplageuppgift](#upplageuppgift) | [Klassifikation](#klassifikation)|
| | [Utgivning](#utgivning) | [Ämne](#amne) |
| | [Copyrightår](#copyrightar) |  [Målgrupp](#malgrupp)  |
| | [Identifikator](#identifikator) | [Innehållstyp](#innehallstyp)  |
| | [Omfång](#omfang) | [Anmärkningar](#anmarkningar) |
| | [Övriga fysiska deltajer](#ovriga-fysiska-detaljer) | [Sammanfattning av innehåll](#sammanfattning-av-innehall) |
| | [Medföljande material](#medfoljande-material) | |
| | [Seriemedlemskap](#seriemedlemskap) | |
| | [Målgruppsanmärkning](#malgruppsanmarkning) | |
| | [Systemkrav](#systemkrav) | |
| | [Anmärkning](#anmarkning) | |
| | [Systemkrav och mediespecifika uppgifter](#systemkrav-och-mediespecifika-uppgifter) | |


### Inledning
Beskrivningen av ett datorspel innehåller följande tre delar:  
* [Adminmetadata](https://libris.kb.se/katalogisering/help/workflow-adminmetadata) - administrativa data om instansbeskrivningen, såsom kontrollnummer och beskrivningsnivå
* [Instans](https://libris.kb.se/katalogisering/help/workflow-instance) - instans kan också kallas utgåva eller manifestation. Exempel på egenskaper under Instans är utgivningsplats, utgivare och utgivningsår, bärartyp, omfång.
* [Verk](https://libris.kb.se/katalogisering/help/workflow-work) – återger egenskaper för det abstrakta verket såsom medverkan och funktion, ämne, klassifikation, språk och innehållstyp. Verksbeskrivningen ligger under rubriken Instans av verk.

Denna hjälptext ger kortfattade instruktioner för de vanligaste egenskaperna för ett datorspel. För utförliga instruktioner, se de generella hjälptexterna för Adminmetadata, Instans och Verk, se ovan.  

Många av egenskaperna finns redan i mallen Datorspel - multimedia, andra kan behöva läggas till. För instruktioner om att lägga till eller ta bort egenskaper, länka till entitet, skapa lokal entitet och om hur formuläret fungerar i övrigt, se Redigering i vänstermenyn. För en förhandspost, använd gärna Berika från mall och välj Datorspel.  

För information om katalogregler och Librispraxis, se [Anvisningar för katalogisering - RDA](http://www.kb.se/rdakatalogisering/ "Anvisningar för katalogisering - RDA") samt [RDA Toolkit](https://access.rdatoolkit.org/). Notera att för datorspel är hela den utgivna resursen föredragen källa. Uppgifterna får tas utan prioritetsordning från det ställe där de anses vara bäst. Denna Librispraxis, [KB SP 2.2.2.4.1](http://access.rdatoolkit.org/kbspchp2_kbsp2-51.html), bygger på IASA Cataloguing Rules och är en avvikelse från [RDA 2.2.2.4.1](http://access.rdatoolkit.org/rdachp2_rda2-8983.html). 

Se även [instruktionsfilmer](https://www.youtube.com/playlist?list=PLZVkEICvA5-GRT2oJQmLgq_2Pksx6zYPy).

### Adminmetadata
Använd generell hjälptext för [Adminmetadata](https://libris.kb.se/katalogisering/help/workflow-adminmetadata).
* Kontrollera beskrivningsnivån. I mallen är standardvärdet Biblioteksnivå (normalvärde för Librisbiblioteken). Ändra vid behov.
**Observera: Om nivån är CIP-post eller preliminär post, ändra till annan nivå, annars kan ändringar skrivas över!** 

### Instans
För att lägga till egenskaper under Instans, klicka på plustecknet i redigeringsvyn (den stora runda plusikonen under Verktygsikonen) - Lägg till egenskaper under: Elektronisk). Sök fram egenskapen och välj den genom att klicka på plustecknet vid egenskapens namn.  

#### Utgivningssatt
* Utgivningssätt (issuanceType)  
  Välj från lista.  
  ```Exempel: Monografisk resurs```

#### Medietyp
* Medietyp (mediaType/Mediatype = 337 #b)  
  Länka till entiteten:
  </br>```computer, c (= dator)```
  
#### Barartyp
* Bärartyp (carrierType/CarrierType = 338 #b)  
  För ett datorspel på DVD-ROM eller Blu-ray Disc, länka till entiteten:
  </br>```computer disc, cd (= datorskiva)```
  
  För ett datorspel på minneskort, länka till entiteten:
  </br>```computer chip cartridge, cb (= datorminnesmodul)```
  
#### Titel 
Titlar för datorspel kan vara svåra att bestämma. Ibland består de av ett franchisenamn följt av ett nummer och/eller en annan titel. I resursen anges ofta den andra titeln på en ny rad och i ett annat typsnitt. Rekommenderad praxis är att ange alla dessa titlar tillsammans i egenskapen huvudtitel, inte som huvudtitel och övrig titelinformation eller huvudtitel och deltitel/delbeteckning. Lägg till interpunktion om det behövs för tydlighet, [RDA 1.7.3](http://access.rdatoolkit.org/rdachp1_rda1-808.html). 
<br/>```Exempel: Need for speed - Undercover```
<br/> Ange endast en titel som övrig titelinformation om det klart framgår att den är underordnad huvudtiteln och inte är nödvändig för att särskilja titeln från andra titlar med samma franchisenamn.
  
Notera att egenskapen Allmän medieterm (marc:mediaTerm = 245 #h) (= Medieterm) inte ska ingå i beskrivningar som görs enligt RDA. 

##### Huvudtitel    
* Har titel/Titel/Huvudtitel (hasTitle/Title/mainTitle = 245 #a)  
  Återge huvudtiteln som den förekommer i källan, se [Librispraxis 2.2.2.4.1](http://access.rdatoolkit.org/kbspchp2_kbsp2-51.html). 
  </br>```Exempel: SimCity 4 - Rush hour expansion```  
  </br>För en titel som börjar med bestämd eller obestämd artikel, ska artikeln fileras bort. Ange fileringsvärde genom att lägga till fileringsvärde (plustecknet vid Titel - Lägg till egenskaper under: Titel) och ange en siffra.   
  </br>```Exempel: Huvudtitel: The hip hop dance experience, fileringsvärde: 4```  
 Se exempel i formathandboken för Libris/Voyager: 
[Fileringsindikator](http://www.kb.se/katalogisering/Formathandboken/Fileringsindikator/).

För att ange föredragen titel, se Verk/Har titel/Titel/Huvudtitel.  

##### Övrig titelinformation (undertitel)
Ange endast en titel som övrig titelinformation om det klart framgår att den är underordnad huvudtiteln och inte är nödvändig för att särskilja titeln från andra titlar med samma franchisenamn, se även instruktioner under [Titel](#titel).
* Har titel/Titel/Övrig titelinformation (= Undertitel) (hasTitle/Title/subtitle = 245 #b)  
  Skriv in uppgiften. Om det finns flera undertitlar, skriv in dessa efter varandra i samma fält, åtskilda av mellanslag, kolon,          mellanslag. 
  
##### Varianttitel
En varianttitel är en titel förknippad med resursen som skiljer sig från den titel som angivits som huvudtitel, se [RDA 2.3.6](http://access.rdatoolkit.org/rdachp2_rda2-4004.html). Här anges t.ex. varianter för titlar som innehåller specialtecken, siffror eller oväntade stavningar av ord.
<br/>För att lägga till varianttitel, klicka på plustecknet vid Har titel (lägg till entitet) och välj typ Varianttitel.  
  * Har titel/Varianttitel/Huvudtitel (hasTitle/VariantTitle/mainTitle = 246 #a)
<br/>Skriv in uppgiften i Huvudtitel.
</br>```Exempel: Pro evolution soccer 2014```

För en parallell huvudtitel på ett annat språk eller i en annan skriftart, se [Parallelltitel](#Parallelltitel).<br/>

Om huvudtiteln är felstavad i källan anges en korrekt form av titeln som varianttitel. Notera dock att för datorspel är hela resursen godkänd källa, utan prioritetsordning, se [Librispraxis för RDA 2.2.2.4.1](http://access.rdatoolkit.org/kbspchp2_kbsp2-51.html). Det innebär att man vanligen kan hitta en korrekt form av titeln och ange den som huvudtitel.<br/>

En varianttitel kan specificeras med en Typanmärkning, en anmärkningstext som i ett sökgränssnitt ska föregå varianttiteln. För att lägga till en Typanmärkning, klicka på plustecknet vid Varianttitel (Lägg till egenskaper under: Varianttitel) och välj Typanmärkning. 
  * Har titel/Varianttitel/Typanmärkning (hasTitle/VariantTitle/typeNote = 246 1/_ #i)<br/> 
   ```Exempel: Titeln felstavad, korrekt titel:```   
   
##### Delbeteckning och deltitel
För anvisningar om hur man anger delbeteckning och deltitel, se hjälptexten [Instans](https://libris.kb.se/katalogisering/help/workflow-instance#titel): Titel. 
  
##### Parallelltitel  
Ange parallelltitel här. Upprepa inte parallelltitel efter Har titel/Titel/Huvudtitel (245 #a) med interpunktion.   
* Har titel/Parallelltitel/Huvudtitel (hasTitle/ParallelTitle/mainTitle = 246 1/1 #a)   
Välj först Har titel, välj sedan typ Parallelltitel. Skriv in uppgiften i Huvudtitel.</br> 
För en titel som börjar med bestämd eller obestämd artikel, ska artikeln fileras bort. Lägg till fileringsvärde och ange en siffra. 
* Har titel/Parallelltitel/Övrig titelinformation (hasTitle/ParallelTitle/subTitle = 246 1/1 #b)   
Vid behov, lägg till Övrig titelinformation (subtitle) under Parallelltitel.  
     
#### Upphovsuppgift
Många datorspel saknar en tydlig upphovsuppgift. Ange endast upphovsuppgift när det klart framgår av resursen att det är en upphovsuppgift, t.ex. om ett namn på en agent föregås av "by" eller "av".
* Upphovsuppgift (responsibilityStatement = 245 #c)<BR/>
  ```Exempel: developed by Revolution Software```
  
#### Upplageuppgift
* Upplageuppgift (editionStatement = 250 #a)
  <BR/>Skriv in upplagebeteckning här. 
  <br/>```Exempel: Version 1.2```  
  
#### Utgivning  
* Utgivning (publication)  
  Välj typ från lista. För monografisk resurs, använd Primär utgivning. 
  I konverterade och maskininlästa poster finns det ibland två avsnitt: ett Primär utgivning med År och Land, och ett Utgivning med Plats, Agent och Datum. När man redigerar maskininlästa poster med två utgivningsavsnitt får man, om man bedömer det nödvändigt, flytta uppgifterna om Plats, Agent och Datum till avsnittet Primär utgivning och ta bort avsnittet Utgivning.   
NB inväntar en maskinell ändring av dessa poster och ändrar inte manuellt.<BR/>
Vid postimport: I importerade poster förekommer ibland både År och Copyrightår inom Utgivning (= 008/06: t, 008/07-10: År och 008/11-14: Copyrightår). Låt uppgiften ligga kvar oförändrad.<BR/>
Om posten är katalogiserad enligt RDA kan även Copyright/Copyright/Datum (copyright/Copyright/date = 264 -/4 #c) finnas med.
 
##### Utgivningsplats
* Plats/Plats/Benämning (= Utgivningsort) (place/label = 264 -/1 #a)  
  Sök inte efter Plats som entitet. Skapa Plats som lokal entitet. Skriv in uppgiften under Benämning. Klamra vid behov.</br> 
  ```Exempel: [Burbank, California]```  
  
##### Utgivningsland  
* Land (country = 008/15-17)  
  Länka till entitet.  
  ```Exempel: Förenta staterna (xxu)``` 
  
##### Utgivarnamn
* Agent/Agent/Benämning (= Utgivarnamn) (agent/label = 264 -/1 #b)  
  Sök inte efter Agent som entitet. Skapa Agent som lokal entitet. Skriv in uppgiften under Benämning.  
  ```Exempel: Insomniac Games```    
  Om flera utgivare ska anges, lägg till Har del (hasPart) under Primär utgivning. Skapa Utgivning som lokal entitet. I rutan Skapa lokal entitet, skriv Utgivning och välj *** Utgivning. Upprepa Utgivning som lokal entitet genom att duplicera entiteten Utgivning. Ange Plats/Plats/Benämning och Agent/Agent/Benämning inom respektive utgivningsavsnitt. Samtliga utgivare med Plats och Agent ska ligga inom Har del/Utgivning. Land, År och eventuellt Datum ska ligga inom Primär utgivning.  
  Se [exempel](https://libris.kb.se/katalogisering/w4rp4hlwtr5lctjr#it).
  
##### År och datum 
  * År (= Utgivningstid) (date = 008/07-10, 264 -/1 #c)  
  År får endast innehålla siffror (0-9) och bokstaven u. År ska endast förekomma inom Primär utgivning.  
  Utgivningsår anges här, utan klamrar eller andra tecken - endast fyra positioner. Det kommer då att exporteras till både marcpostens 08/07-10 och 264 -/1 #c.</br>
  ```Exempel: 2017```</br>
 
 Observera att År måste finnas med i beskrivningen, även om datum finns med.</br>
  
  För att ange årtal med klamrar eller andra tecken utöver fyra positioner, använd Datum.
  * Datum (= Utgivningstid) (date = 264 -/1 #c)  
  Datum får innehålla text och interpunktionstecken.  
  Utgivningsdatum med fler än fyra positioner, till exempel ett klamrat årtal, anges här. Det kommer att exporteras till marcpostens 264 -/1 #c.
<br/>```Exempel:```
   * ```[2017]``` 
   * ```[mellan 2003 och 2005?]```

För att ange ett år utan klamrar eller andra tecken, använd År.

För att ange ett osäkert utgivningsdatum där endast tidigaste och senaste årtal kan anges, följ exempel i hjälptexten [Instans](https://libris.kb.se/katalogisering/help/workflow-instance#produktion): Produktion: Huvudsakligt tillgängliggörande. 
  
* Flera år (flerbandsverk)  
 För anvisningar om hur man anger flera år (flerbandsverk), se hjälptexten [Instans](https://libris.kb.se/katalogisering/help/workflow-instance#utgivning): Utgivning. 
 
 Läs mer om [År och Datum](https://kundo.se/org/librisxl/d/falt-for-utgivningsar/)  
  
#### Copyrightar
För datorspel anges alltid copyrightår, även om det sammanfaller med utgivningsår/distributionsår, se [Librispraxis 2.11](http://access.rdatoolkit.org/kbspchp2_kbsp2-1030.html).
* Copyright/Copyright/Datum (copyright/Copyright/date = 264 -/4 #c)  
  Skriv in uppgiften. För att få fram ©, kopiera härifrån eller sök på teckenuppsättning i “Sök i windows” och öppna programmet, markera och kopiera tecknet och sedan klistra in det.  
  Se också [Specialtecken](https://libris-dev.kb.se/katalogisering/help/search-04-special-chars). 
<br/>```Exempel: ©2017```
    
#### Identifikator
Flera typer av identifikatorer kan finnas på datorspel. I mallen är Utgivningsnummer (annat) och EAN förvalda.

##### Utgivningsnummer (annat)
* Identifikator (identifiedBy)  
  Välj typ från lista.  
  ```Exempel: Utgivningsnummer (annat)```
* Identifikator/Utgivningsnummer (annat)/Värde (identifiedBy/VideoRecordingNumber/value = 028 5/1 #a)<br/>
  Ange utgivningsnumret som det förekommer i resursen.<br/>
  ```Exempel: 7303903501```
* Identifikator/Agent/Organisation/Namn (= Utgivare) (identifiedBy/agent/Organization/name = 028 5/1 #b)<br/> 
  Ange utgivarens namn.<br/>
  ```Exempel: Electronic Arts```
* Identifikator/Särskiljande tillägg (= Bestämning) (identifiedBy/qualifier = 020 #q)<br/>
  Ange eventuell bestämning.<br/>
  
##### EAN
* Identifikator (identifiedBy)  
  Välj typ från lista.  
  ```Exempel: EAN```
* Identifikator/EAN/Värde (identifiedBy/EAN/value = 024 #a)<br/>
  Ange identifikator.<br/>
  ```Exempel: 5705535059701```

För anvisningar om hur man anger ISBN, se hjälptexten [Instans](https://libris.kb.se/katalogisering/help/workflow-instance#identifikator): Identifikator
   
#### Omfang  
Ange antal enheter samt typ av enhet, se [RDA 3.4.1.3](http://access.rdatoolkit.org/rdachp3_rda3-2098.html) samt [Librispraxis för Alternativ](http://access.rdatoolkit.org/kbspchp3_kbsp3-95.html). 
* Omfång/Omfång/Benämning (extent/Extent/label = 300 #a)<br/>
Skriv in uppgiften under Benämning.
 <br/>```Exempel:```
   * ```1 DVD-ROM``` 
   * ```1 Blu-ray Disc```
   * ```1 minneskort```

* Om så önskas, för att uppgiften ska bli synlig i lokala system, kan konsol anges inom parentes efter omfång.
 <br/>```Exempel:```
   * ```1 DVD-ROM (Xbox 360)```
   * ```1 Blu-Ray Disc (Playstation 4)```
   * ```1 minneskort (Nintendo Switch)```
   
Notera att det är obligatoriskt att ange konsol i egenskapen [Systemkrav](#systemkrav).
  
#### Ovriga fysiska detaljer   
* Övriga fysiska detaljer (other physical details = 300 #b)  
  ```Exempel: ljud, svartvit```
  
#### Medfoljande material
* Medföljs av/Instans/Benämning (Bilagor) (accompaniedBy/Instance/label = 300 #e)   
Här anges medföljande material, som t ex bilagor. Lägg till Medföljs av. Skapa Instans som lokal entitet (skriv Instans i rutan Skapa lokal entitet och välj ** Instans). Lägg till Benämning. Skriv in uppgiften.
 <br/>```Exempel:```
   * ```1 handledning (36 sidor)``` 
   * ```1 handledning (4 sidor) + spelkontroll i form av gitarr```

#### Seriemedlemskap
För anvisningar om hur man anger seriemedlemskap, se hjälptexten [Instans](https://libris.kb.se/katalogisering/help/workflow-instance#seriemedlemskap): Seriemedlemskap.<br/>
Franchisenamn ska inte anges som serieuppgift, se [Titel](#titel).

#### Malgruppsanmarkning  
* Målgrupp/Målgrupp/Benämning (intendedAudience/IntendedAudience/label = 521 #a)  
Lägg till Målgrupp. Skapa målgrupp som lokal entitet (skriv målgrupp i rutan Skapa lokal entitet och välj det).<BR/>
Skriv in uppgiften under Benämning. Åldersnivån kan om så önskas, preciseras enligt [PEGI](https://pegi.info), Pan European Game Information.<BR/>
```Exempel: PEGI 12```  

Notera att kodning av målgrupp, motsvarande 008/22, ska anges i [Målgrupp](#malgrupp) under Instans av Verk.

#### Systemkrav
Det är obligatoriskt i Libris att ange konsol här. 
* Systemkrav/Modell/Benämning (systemRequirement/MachineModel/label = 753 #a)</BR>
Skriv in uppgiften under Benämning.  
```Exempel: XBox 360```<BR/>

Konsol kan även, om så önskas, för att uppgiften ska bli synlig i lokala system, anges inom parentes efter [omfång](#omfang) eller i egenskapen [Systemkrav och mediespecifika uppgifter](#systemkrav-och-mediespecifika-uppgifter).

#### Anmarkning
* Anmärkning/Anmärkning/Benämning (hasNote/Note/label = 500 #a)   
  Skriv in allmänna anmärkningar här. För att lägga till Anmärkning, välj Anmärkning (hasNote) och lägg till.
  Skriv in uppgiften under Benämning.<BR/>
```Exempel: Avsett för 1-7 spelare, 1-2 spelare i nätverk```  
  
#### Systemkrav och mediespecifika uppgifter
Här kan systemkrav och mediespecifika uppgifter som inte framgår någon annanstans i beskrivningen anges. Ange uppgiften som den är presenterad i resursen. Uppgift om konsol ska alltid anges i egenskapen [Systemkrav](#Systemkrav). Om så önskas, för att den ska bli synlig i i lokala system, kan uppgift om konsol även anges här eller inom parentes efter [Omfång](#Omfang).
* Har anmärkning: Systemkrav och mediespecifika uppgifter/Anmärkning: Systemkrav och mediespecifika uppgifter/Anmärkningstext        (marc:hasSystemDetailsNote = 538 #a)</BR>
```Exempel: Systemkrav: 50 GB minimum på hårddisken ; dualshok 4 ; stöd för remote play```  

### Verk 
#### Instans av verk (instanceOf/Work)
Skapa verket som lokal entitet (bryt inte ut verket till en länkbar entitet). Denna hjälptext beskriver exempel på verk som lokal entitet. Det betyder att du anger de uppgifter som listas här nedan, under Instans av Verk, utan att klicka på länksymbolen (Länka entitet) vid Instans av Verk.  
  Läs mer om [Verk och Instans](https://librisbloggen.kb.se/2018/05/30/verk-och-instans-i-startversionen/).</BR> 

För att lägga till egenskaper under Instans av Verk, klicka på plustecknet till höger om Instans av Verk - Lägg till egenskaper under: Multimedia. Sök fram egenskapen och välj den genom att klicka på plustecknet vid egenskapens namn.

#### Verkets titel 
Ange vid behov den föredragna titeln för verket här. Följ anvisningarna under [Konstruera sökingångar för verk och uttryck](http://www.kb.se/rdakatalogisering/Anvisningar/Allmanna-anvisningar/Sokingangar-for-verk-och-uttryck/) i Anvisningar för katalogisering - RDA.

##### Verkets titel - verk utan primär medverkan
Datorspel har sällan en primär medverkande. För att en agent ska räknas som primär medverkande ska denne vara ansvarig för alla aspekter kopplade till skapandet av datorspelet. Föredragen titel för ett verk utan primär medverkan ska anges i Uttryck av/Verk/Har titel/Titel/Huvudtitel. 
*	Uttryck av/Verk/Har titel/Titel/Huvudtitel (expressionOf/Work/hasTitle/Title/mainTitle (= 130 #a)  
Under Instans av Verk, lägg till egenskapen Uttryck av. Skapa verk som lokal entitet (plustecknet vid Uttryck av - Lägg till verk, välj Skapa lokal entitet, längst ner i sidorutan till höger), välj Verk. Det läggs till under Uttryck av. Lägg till Har titel. Välj Titel. 
Ange  den föredragna titeln i Huvudtitel.  
```Exempel:  Prototype (datorspel)```</BR>
Tillägget inom parentes (datorspel) görs för att skilja datorspelet Prototype från filmen Prototype.</BR> 
Läs mer om [Tillägg till auktoriserade sökingångar för verk](http://www.kb.se/rdakatalogisering/Anvisningar/Allmanna-anvisningar/Sokingangar-for-verk-och-uttryck/#tillaggtillauktsokingforverk) i Anvisningar för katalogisering (RDA).</BR>
För en titel som börjar med bestämd eller obestämd artikel, ska artikeln fileras bort. Ange fileringsvärde genom att lägga till fileringsvärde och ange en siffra.  
*	Uttryck av/Verk/Har titel/Titel/Deltitel (expressionOf/Work/hasTitle/Title/partName = 130 #p)  
Lägg till eventuell deltitel (plustecknet vid Titel - lägg till egenskaper under: Titel, välj Deltitel).  
*	Uttryck av/Verk/Har titel/Titel/Delbeteckning (expressionOf/Work/hasTitle/Title/partName = 130 #n)  
Lägg till eventuell delbeteckning (plustecknet vid Titel - lägg till egenskaper under: Titel, välj Delbeteckning).  
*	•	Uttryck av/Verk/Språk (expressionOf/Work/language = 130 #l)
Lägg till eventuellt språk som ska ingå i sökingången. Klicka på plustecknet vid Verk (Lägg till egenskaper under: Verk) och välj Språk. Klicka på plustecknet vid Språk (Lägg till språk) och sök fram språkentiteten och länka. Språket visas då som ett tillägg till verkets titel i marcpostens 130 #l.

##### Verkets titel - verk med primär medverkan
Det är ovanligt att datorspel har primär medverkan. För att en agent ska räknas som primär medverkande ska denne vara ansvarig för alla aspekter kopplade till skapandet av datorspelet. Föredragen titel för ett verk med primär medverkan ska anges i Har titel/Titel/Huvudtitel.
* Har titel/Titel/Huvudtitel (hasTitle/Title/mainTitle = 240 1/0 #a)</BR> 
Ange den föredragna titeln i Huvudtitel.
För en titel som börjar med bestämd eller obestämd artikel, ska artikeln fileras bort. Ange fileringsvärde genom att lägga till fileringsvärde och ange en siffra.  
* Har titel/Titel/Deltitel (hasTitle/Title/partName = 240 1/0 #p)</BR> 
Lägg till eventuell deltitel (plustecknet vid Titel - lägg till egenskaper under: Titel, välj Deltitel).</BR>
* Har titel/Titel/Delbeteckning (hasTitle/Title/partNumber = 240 1/0 #n)</BR>
Lägg till eventuell delbeteckning (plustecknet vid Titel - lägg till egenskaper under: Titel, välj Delbeteckning).</BR> 
* Språk/Språk/Benämning (language/Language/label = 240 #l)</BR>
**Från och med version 1.7 skapas språktillägget automatiskt, för 240 #l. Språktillägget skapas även när det inte är en översättning. Det kommer att korrigeras i en kommande release av Libris katalogisering.**

#### Medverkan och funktion
* Medverkan och funktion  
  Under Medverkan och funktion, ange relationer till de agenter som medverkar i verket samt funktionskod för respektive agent.  Relationer till utgivare (710) anges för närvarande också här.</BR>
  För ytterligare instruktioner om hur man anger relationer till agenter, se: [Relationer till Agent](https://libris.kb.se/katalogisering/help/workflow-agent-org-instance).</BR>
  Se även: [Auktoritetsgruppens rekommendationer](https://kundo.se/org/librisxl/d/kbs-auktoritetsgrupp-informerar-jraz/).   
  
##### Primär medverkan
Det är ovanligt att datorspel har primär medverkande. Ofta är det två eller flera agenter (programmerare, utvecklare etc.) som är gemensamt ansvariga för att ha skapat verket. För att en agent ska räknas som primär medverkande ska denne vara ansvarig för alla aspekter kopplade till skapandet av datorspelet.  
* Medverkan och funktion/Primär medverkan/Agent/Person (contribution/PrimaryContribution/agent/Person = 100 1/- #a)  
  Länka till entitet. Börja alltid med att söka efter om agenten redan finns. Vid behov, skapa ny entitet för agent (se Skapa ny agent i hjälpsektionen). I undantagsfall, skapa lokal entitet.   
* Medverkan och funktion/Primär medverkan/Funktion (contribution/PrimaryContribution/role = 100 #4)  
  Länka till entitet. Klicka på plustecknet vid Funktion (Lägg till funktion) och sök fram funktionskod. Skriv in kod eller utskriven form i sökrutan eller tryck på mellanslagstangenten för att se alla koder. Välj kod genom att klicka på plustecknet vid koden eller på koden.    
För en sorterad lista på koder, se Formathandboken för Libris/Voyager: [Funktions- och relationskoder](http://www.kb.se/katalogisering/Formathandboken/Funktionskoder/)  

##### Medverkan
* Medverkan och funktion/Medverkan/Agent (contribution/agent = 700 1/- #a)  
  Länka till entitet. Börja alltid med att söka efter om agenten redan finns. Vid behov, skapa ny entitet för agent (se Skapa ny agent i hjälpsektionen). I undantagsfall, skapa lokal entitet.   
  ```Exempel: Sydow, Max von, 1929-```  
* Medverkan och funktion/Medverkan/Funktion (contribution/role = 700 #4)  
  Länka till entitet. Klicka på plustecknet vid Funktion (Lägg till funktion) och sök fram funktionskod. Skriv in kod eller utskriven form i sökrutan eller tryck på mellanslagstangenten för att se alla koder. Välj kod genom att klicka på plustecknet vid koden eller på koden.</BR> 
```Exempel: Röst, tal, spk```  
För en sorterad lista på koder, se Formathandboken för Libris/Voyager: [Funktions- och relationskoder](http://www.kb.se/katalogisering/Formathandboken/Funktionskoder/) 
 
##### Funktioner som saknar funktionskod
Utbudet av funktionskoder för agenter kopplade till datorspel är fortarande ganska begränsat. För att ange en funktion som inte har en motsvarande funktionskod, klicka på plustecknet vid Funktion (Lägg till funktion) och sedan på Skapa lokal entitet. Klicka på plustecknet Lägg till egenskaper under: Funktion och välj Benämning. Skriv in önskad term. Värdet exporteras till 7XX #e.</BR>
```Exempel: Spelutvecklare```
  
#### Sprak 
* Språk (language = 008/35-37)</BR>
  Länka till entitet.  
  ```Exempel: engelska (eng)``` 
  </BR>Ange flera språk genom att klicka på plustecknet vid Språk (Lägg till språk) och sök fram entitet för språket.</BR>
  Länka till entitet.  
  
##### Översättning  
För datorspel som är/innehåller en översättning, lägg till:  
* Anmärkning: Språk (marc:LanguageNote = 041 i1: 1)  
  Ange om resursen är/innehåller en översättning.  
  För att lägga till uppgiften, klicka på plustecknet vid Instans av verk/Multimedia och välj Anmärkning: Språk. Välj fras från lista.  
  ```Exempel: objektet är/innehåller översättning```   
* Originalversion/Verk/Språk (originalversion/Work/language = 041 #h)  
  Ange originalspråk här. Klicka på plustecknet vid Instans av Verk, välj Originalversion, klicka på plustecknet vid Originalversion, välj Skapa lokal entitet. Skriv Verk i rutan för Skapa lokal entitet och välj * Verk. Lägg till Språk under verk. Sök fram språkentiteten och länka.  
  ```Exempel: japanska (jpn)```  

#### Relationer till ingaende verk och andra verk
##### Verk som ingår i det beskrivna verket
För att ange verk som ingår i det beskrivna verket motsvarande fält 700 1/2 #a, #d, #t (analytisk sökingingång för verk med primär medverkan) eller 730 0/2 #a (analytisk sökingång för verk utan primär medverkan):  
Under Instans av Verk, lägg till Har del. Skapa verk som lokal entitet. Lägg till Har titel och välj Titel. Ange föredragen titel i Huvudtitel.</br>
Lägg till eventuell deltitel, delbeteckning och språk som ska ingå i sökingången. (För att lägga till språk, klicka på plustecknet vid Verk (Lägg till egenskaper under: Verk) och välj Språk. Klicka på plustecknet vid Språk (Lägg till språk) och sök fram språkentiteten och länka. Språket visas då som ett tillägg till verkets titel i marcpostens 700 eller 730 #l.)</br>
För ingående verk med primär medverkan, lägg till Medverkan och funktion/Primär medverkan enligt anvisningarna under [Medverkan och funktion](#medverkan-och-funktion): Primär medverkan.</br>
För utförligare instruktioner, se även hjälptexten [Relationer till delar och verk](https://libris.kb.se/katalogisering/help/workflow-agent-relation).

##### Relationer till andra verk  
För att ange verk som är relaterade, men inte ingår i det beskrivna verket, motsvarande fält 700 1/- #a, #d, #t (icke-analytisk sökingingång för verk med primär medverkan) eller 730 0/_ #a (icke-analytisk sökingång för verk utan primär medverkan): 
Under Instans av Verk, lägg till Relation. Välj typ Relation. Lägg till Entitet och välj Entitet. Skapa verk som lokal entitet. Lägg till Har titel och välj Titel. Ange föredragen titel i Huvudtitel.</br> 
Lägg till eventuell deltitel, delbeteckning och språk som ska ingå i sökingången. (För att lägga till språk, klicka på plustecknet vid Verk (Lägg till egenskaper under: Verk) och välj Språk. Klicka på plustecknet vid Språk (Lägg till språk) och sök fram språkentiteten och länka. Språket visas då som ett tillägg till verkets titel i marcpostens 700 eller 730 #l.)</br>
För ingående verk med primär medverkan, lägg till Medverkan och funktion/Primär medverkan enligt anvisningarna under [Medverkan och funktion](#medverkan-och-funktion): Primär medverkan.</br>
För utförligare instruktioner, se även hjälptexten [Relationer till delar och verk](https://libris.kb.se/katalogisering/help/workflow-agent-relation).
   
#### Genre form 
För utförliga anvisningar om hur man anger genre/form, se hjälptexten [Verk](https://libris.kb.se/katalogisering/help/workflow-work#genre): Genre form.
 
* Genre/form – saogf-termer (genreForm = 655 -/7 #a, #2 saogf)</br> 
Länka till entiteten:</br> 
 ```Datorspel```

För datorspel ska typ av fil (= 008/26) anges med termen Dataspel, g i Genre/form.

* Genre/form - termer som motsvarar marc-koder i 008</br> 
Välj Typ av fil.
Länka till entiteten:</br>
 ```Dataspel, g```
    
#### Klassifikation  
För anvisningar om hur man anger klassifikation, se hjälptexten [Verk](https://libris.kb.se/katalogisering/help/workflow-work#klassifikation): Klassifikation.
 
#### Amne  
* Ämne  
  Länka  i första hand till entiteter för ämnesord. Följ instruktionerna under:  
  [Ämnesord i Libris](https://libris.kb.se/katalogisering/help/workflow-general-sh).   

#### Malgrupp     
 * Målgrupp (intendedAudience = 008/22)  
  Länka till entitet.  
  ```Exempel: j (= barn- och ungdom, 0-16 år)```</br> 
  Normalvärde för spel som riktar sig till barn och ungdom.

För att lägga till Målgruppsanmärkning (Målgrupp/Målgrupp/Benämning), se [Målgruppsanmärkning](#Malgruppsanmarkning) under Instans.
 
#### Innehallstyp
 * Innehållstyp/Innehållstyp (contentType/ContentType = 336 #b)   
  Länka till entiteten:</BR>
  ```Computer program, cop (= datorprogram)```
  
#### Anmarkningar
##### Anmärkning om språk
 * Anmärkning/Anmärkning om språk/Benämning (hasNote/marc:LanguageNote/marc:LanguageNote/label = 546 #a)  
  ```Exempel: Tal och text på engelska. Manual på svenska.```  

#### Sammanfattning av innehall
 * Sammanfattning av innehåll/Sammanfattning/Benämning (summary/Summary/label = 520 #a)</BR>
Lägg till Sammanfattning av innehåll. Välj Sammanfattning av innehåll. Lägg till Sammanfattning. 
 Skriv in uppgiften under Benämning.
     
 * Typ av sammanfattning/typ av innehållsbeskrivning (marc:summaryType = 520 ind1)  
 Sök fram och lägg till Typ av sammanfattning. Välj typ från lista.  
 ```Exempel: Ej preciserad```  
    
