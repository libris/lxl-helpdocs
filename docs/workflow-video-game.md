---
section: Materialtyper
title: Datorspel
order: 38
date: 2021-03-17
tags:
- datorspel
- TV-spel
--- 

# Datorspel
Denna hjälptext ger kortfattade instruktioner för de vanligaste egenskaperna vid beskrivning av datorspel - multimedia. För mer utförliga instruktioner, se de generella hjälptexterna för Adminmetadata, Instans och Verk, se innehållsförteckningen nedan.

## Innehåll   

[Inledning](#inledning)

| [Adminmetadata](#adminmetadata) | [Instans](#instans) | [Verk](#verk) | 
| ----------- | ----------- |  ----------- |
| [Adminmetadata - Metadatabyrån](https://metadatabyran.kb.se/beskrivning/specialanvisningar/adminmetadata-i-libris) | [Generell hjälptext för Instans](https://libris.kb.se/katalogisering/help/workflow-instance) | [Generell hjälptext för Verk](https://libris.kb.se/katalogisering/help/workflow-work) |
| | [Identifikator](#identifikator) | [Verkets titel](#verkets-titel)  |
| | [Utgivningssätt](#utgivningssätt) | [Medverkan och funktion](#medverkan-och-funktion) |
| | [Medietyp](#medietyp) | [Språk](#spr-k) |
| | [Bärartyp](#b-rartyp) | [Relationer till ingående verk och andra verk](#relationer-till-ing-ende-verk-och-andra-verk) |
| | [Titel](#titel) | [Genre/form](#genre-form) |
| | [Upphovsuppgift](#upphovsuppgift) | [Klassifikation](#klassifikation) |
| | [Upplageuppgift](#upplageuppgift) | [Ämne](#-mne) |
| | [Utgivning](#utgivning) | [Målgrupp](#m-lgrupp) |
| | [Copyrightår](#copyright-r) | [Innehållstyp](#inneh-llstyp)  |
| | [Omfång](#omf-ng) | [Anmärkningar](#anm-rkningar) |
| | [Övriga fysiska detaljer](#-vriga-fysiska-detaljer) | [Sammanfattning av innehåll](#sammanfattning-av-inneh-ll) |
| | [Medföljande material](#medf-ljande-material) | |
| | [Seriemedlemskap](#seriemedlemskap) | |
| | [Målgruppsanmärkning](#m-lgruppsanm-rkning) | |
| | [Systemkrav](#systemkrav) | |
| | [Anmärkning](#anm-rkning) | |
| | [Systemkrav och mediespecifika uppgifter](#systemkrav-och-mediespecifika-uppgifter) | |


## Inledning
Beskrivningen av ett datorspel innehåller följande tre delar:  
* [Adminmetadata - Metadatabyrån](https://metadatabyran.kb.se/beskrivning/specialanvisningar/adminmetadata-i-libris) - administrativa data om instansbeskrivningen, såsom kontrollnummer och beskrivningsnivå
* [Instans](https://libris.kb.se/katalogisering/help/workflow-instance) - instans kan också kallas utgåva eller manifestation. Exempel på egenskaper under Instans är utgivare, bärartyp och omfång.
* [Verk](https://libris.kb.se/katalogisering/help/workflow-work) – återger egenskaper för det abstrakta verket såsom medverkan och funktion, ämne, klassifikation, språk och innehållstyp. Verksbeskrivningen ligger under rubriken Instans av verk.

Många av egenskaperna finns redan i mallen Datorspel - multimedia, andra kan behöva läggas till. För instruktioner om att lägga till eller ta bort egenskaper, länka till entitet, skapa lokal entitet och om hur formuläret fungerar i övrigt, se Redigering i vänstermenyn. För en förhandspost, använd gärna Berika från mall och välj Datorspel.  

För information om katalogiseringsregler och Librispraxis, se [Metadatabyrån](https://metadatabyran.kb.se/) samt se [RDA Toolkit](https://original.rdatoolkit.org/). Notera att för datorspel är hela den utgivna resursen föredragen källa. Uppgifterna får tas utan prioritetsordning från det ställe där de anses vara bäst. Denna [Librispraxis, KB SP 2.2.2.4.1](http://access.rdatoolkit.org/kbspchp2_kbsp2-51.html), bygger på IASA Cataloguing Rules och är en avvikelse från [RDA 2.2.2.4.1](http://access.rdatoolkit.org/rdachp2_rda2-8983.html). 

Se även [instruktionsfilmer på KB:s Youtubekanal](https://www.youtube.com/playlist?list=PLZVkEICvA5-GRT2oJQmLgq_2Pksx6zYPy).

## Adminmetadata
[Adminmetadata - Metadatabyrån](https://metadatabyran.kb.se/beskrivning/specialanvisningar/adminmetadata-i-libris)  
* Kontrollera beskrivningsnivån. I mallen är standardvärdet Biblioteksnivå (normalvärde för Librisbiblioteken). Ändra vid behov.
**Observera: Om nivån är CIP-post eller preliminär post, ändra till annan nivå, annars kan ändringar skrivas över!** 

## Instans
För att lägga till egenskaper under Instans, klicka på plustecknet i redigeringsvyn (den stora runda plusikonen under Verktygsikonen) - Lägg till egenskaper under: Elektronisk). Sök fram egenskapen och välj den genom att klicka på plustecknet vid egenskapens namn.  

### Identifikator
Flera typer av identifikatorer kan finnas på datorspel. I mallen är EAN och Utgivningsnummer (annat) förvalda.

#### EAN
* Identifikator (identifiedBy)  
  Välj typ från lista.  
  ```Exempel: EAN```
* Identifikator/EAN/Värde (identifiedBy/EAN/value = 024 #a)<br/>
  Ange identifikator.<br/>
  ```Exempel: 5705535059701```

#### Utgivningsnummer (annat)
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

För anvisningar om hur man anger ISBN, se [hjälptexten Instans](https://libris.kb.se/katalogisering/help/workflow-instance#identifikator): Identifikator
   
### Utgivningssätt
* Utgivningssätt (issuanceType)  
  Välj från lista.  
  ```Exempel: Monografisk resurs```

### Medietyp
* Medietyp (mediaType/Mediatype = 337 #b)  
  Länka till entiteten:
  </br>```dator, computer (kod = c)```  

### Bärartyp
* Bärartyp (carrierType/CarrierType = 338 #b)  
  För ett datorspel på DVD-ROM eller Blu-ray Disc, länka till entiteten:
  </br>```datorskiva, computer disc (kod = cd)```
  
  För ett datorspel på minneskort, länka till entiteten:
  </br>```datorminnesmodul, computer chip cartridge, cb (kod = cb)```   

### Titel 
Titlar för datorspel kan vara svåra att bestämma. Ibland består de av ett franchisenamn följt av ett nummer och/eller en annan titel. I resursen anges ofta den andra titeln på en ny rad och i ett annat typsnitt. Rekommenderad praxis är att ange alla dessa titlar tillsammans i egenskapen huvudtitel, inte som huvudtitel och övrig titelinformation eller huvudtitel och deltitel/delbeteckning. Lägg till interpunktion om det behövs för tydlighet, se [RDA 1.7.3](http://access.rdatoolkit.org/rdachp1_rda1-808.html). 
<br/>```Exempel: Need for speed - Undercover```
<br/> Ange endast en titel som övrig titelinformation om det klart framgår att den är underordnad huvudtiteln och inte är nödvändig för att särskilja titeln från andra titlar med samma franchisenamn.

#### Huvudtitel  
Observera att egenskapen Allmän medieterm (marc:mediaTerm = 245 #h) (= Medieterm) inte ska ingå i beskrivningar som görs enligt RDA. 
* Har titel/Titel/Huvudtitel (hasTitle/Title/mainTitle = 245 #a)  
  Återge huvudtiteln som den förekommer i källan, se [Librispraxis 2.2.2.4.1](http://access.rdatoolkit.org/kbspchp2_kbsp2-51.html). 
  <br/>```Exempel: SimCity 4 - Rush hour expansion```  
  För en titel som börjar med bestämd eller obestämd artikel, ska artikeln fileras bort. Ange fileringsvärde genom att lägga till fileringsvärde (plustecknet vid Titel - Lägg till egenskaper under: Titel) och ange en siffra.   
  ```Exempel: Huvudtitel: The hip hop dance experience, fileringsvärde: 4```  
 Se exempel på sidan [Filering av titel - Metadatabyrån](https://metadatabyran.kb.se/beskrivning/generella-anvisningar---rda/manifestation-instans/titel/filering-av-titel).

#### Övrig titelinformation
Ange endast en titel som övrig titelinformation om det klart framgår att den är underordnad huvudtiteln och inte är nödvändig för att särskilja titeln från andra titlar med samma franchisenamn, se även [instruktioner under Titel](#titel).
* Har titel/Titel/Övrig titelinformation (= Undertitel) (hasTitle/Title/subtitle = 245 #b)  
Om det finns flera undertitlar, skriv in dessa efter varandra i samma fält, åtskilda av mellanslag, kolon, mellanslag.<br/>  

#### Varianttitel
En varianttitel är en titel förknippad med resursen som skiljer sig från den titel som angivits som huvudtitel, se [RDA 2.3.6](http://access.rdatoolkit.org/rdachp2_rda2-4004.html). Här anges t.ex. varianter för titlar som innehåller specialtecken, siffror eller oväntade stavningar av ord.
<br/>För att lägga till varianttitel, klicka på plustecknet vid Har titel (lägg till entitet) och välj typ Varianttitel.  
  * Har titel/Varianttitel/Huvudtitel (hasTitle/VariantTitle/mainTitle = 246 #a)
<br/>Skriv in uppgiften i Huvudtitel.
<br/>```Exempel: Pro evolution soccer 2014```

För en parallell huvudtitel på ett annat språk eller i en annan skriftart, se [Parallelltitel](#Parallelltitel).<br/>

Om huvudtiteln är felstavad i källan anges en korrekt form av titeln som varianttitel. Notera dock att för datorspel är hela resursen godkänd källa, utan prioritetsordning, se [Librispraxis för RDA 2.2.2.4.1](http://access.rdatoolkit.org/kbspchp2_kbsp2-51.html). Det innebär att man vanligen kan hitta en korrekt form av titeln och ange den som huvudtitel.<br/>

En varianttitel kan specificeras med en Typanmärkning, en anmärkningstext som i ett sökgränssnitt ska föregå varianttiteln. För att lägga till en Typanmärkning, klicka på plustecknet vid Varianttitel (Lägg till egenskaper under: Varianttitel) och välj Typanmärkning. 
  * Har titel/Varianttitel/Typanmärkning (hasTitle/VariantTitle/typeNote = 246 1/_ #i)<br/> 
   ```Exempel: Titeln felstavad, korrekt titel:```</br>

#### Delbeteckning och deltitel
För anvisningar om hur man anger delbeteckning och deltitel, se [Metadatabyrån](https://metadatabyran.kb.se/beskrivning/generella-anvisningar---rda/manifestation-instans/titel).<br/>  

#### Parallelltitel  
Ange parallelltitel här. Upprepa inte parallelltitel efter Har titel/Titel/Huvudtitel (245 #a) med interpunktion.   
<br/> * Har titel/Parallelltitel/Huvudtitel (hasTitle/ParallelTitle/mainTitle = 246 1/1 #a)   
<br/> * Har titel/Parallelltitel/Övrig titelinformation (hasTitle/ParallelTitle/subTitle = 246 1/1 #b  

### Upphovsuppgift  
Många datorspel saknar en tydlig upphovsuppgift. Ange endast upphovsuppgift när det klart framgår av resursen att det är en upphovsuppgift, t.ex. om ett namn på en agent föregås av "by" eller "av".  
* Upphovsuppgift (responsibilityStatement = 245 #c)  
  ```Exempel: developed by Revolution Software```

### Upplageuppgift
* Upplageuppgift (editionStatement = 250 #a)
  <br/>```Exempel: Version 1.2```<br/>

### Utgivning  
* Utgivning   
  Välj typ från lista. För monografisk resurs, använd Primär utgivning.  

#### Utgivningsland  
* Land (country = 008/15-17)  
  Länka till entitet.  
  ```Exempel: Förenta staterna (xxu)```  

#### Utgivningsplats
* Plats/Plats/Benämning (= Utgivningsort) (place/label = 264 -/1 #a)  
  ```Exempel: Burbank, California```  

#### Utgivarnamn
* Agent/Agent/Benämning (= Utgivarnamn) (agent/label = 264 -/1 #b)  
  ```Exempel: Insomniac Games```  

#### År och datum 
* År (= Utgivningstid) (date = 008/07-10, 264 -/1 #c)  
  År får endast innehålla siffror (0-9) och bokstaven u. 
  Observera att År **måste** finnas med i beskrivningen, även om datum finns med.   

* Datum (= Utgivningstid) (date = 264 -/1 #c)  
  Datum får innehålla text och interpunktionstecken, till exempel klamrar och frågetecken.  
  Datum används endast när man förutom årtal ska använda andra tecken än siffror och bokstaven u.

[Läs mer om utgivningstid i Metadatabyrån](https://metadatabyran.kb.se/beskrivning/generella-anvisningar---rda/manifestation-instans/utgivningsuppgift).
  

### Copyrightår
För datorspel anges alltid copyrightår, även om det sammanfaller med utgivningsår/distributionsår, se [Librispraxis 2.11 i RDA Toolkit](http://access.rdatoolkit.org/kbspchp2_kbsp2-1030.html).
* Copyright/Copyright/Datum (copyright/Copyright/date = 264 -/4 #c)  
  Skriv in uppgiften. För att få fram ©, kopiera härifrån eller sök på teckenuppsättning i “Sök i windows” och öppna programmet, markera och kopiera tecknet och sedan klistra in det.  
  Se också [hjälptexten Specialtecken](https://libris.kb.se/katalogisering/help/special-chars). 
<br/>```Exempel: ©2017```  

### Omfång  
Ange antal enheter samt typ av enhet, se [RDA 3.4.1.3](http://access.rdatoolkit.org/rdachp3_rda3-2098.html) samt se [Librispraxis i RDA Toolkit för Alternativ](http://access.rdatoolkit.org/kbspchp3_kbsp3-95.html). 
* Omfång/Omfång/Benämning (extent/Extent/label = 300 #a)  
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

### Övriga fysiska detaljer   
* Övriga fysiska detaljer (other physical details = 300 #b)  
  ```Exempel: ljud, svartvit```
  

### Medföljande material
* Medföljs av/Instans/Benämning (Bilagor) (accompaniedBy/Instance/label = 300 #e)   
Här anges medföljande material, som t ex bilagor. Lägg till Medföljs av. Skapa Instans som lokal entitet (skriv Instans i rutan Skapa lokal entitet och välj ** Instans). Lägg till Benämning. Skriv in uppgiften.
 <br/>```Exempel:```
   * ```1 handledning (36 sidor)``` 
   * ```1 handledning (4 sidor) + spelkontroll i form av gitarr```


### Seriemedlemskap
För anvisningar om hur man anger seriemedlemskap, se [Metadatabyrån](https://metadatabyran.kb.se/beskrivning/generella-anvisningar---rda/manifestation-instans/serieuppgift).<br/>
Franchisenamn ska inte anges som serieuppgift, se [Titel](#titel).


### Målgruppsanmärkning  
* Målgrupp/Målgrupp/Benämning (intendedAudience/IntendedAudience/label = 521 #a)  
Lägg till Målgrupp. Skapa målgrupp som lokal entitet (skriv målgrupp i rutan Skapa lokal entitet och välj det).<BR/>
Skriv in uppgiften under Benämning. Åldersnivån kan om så önskas, preciseras enligt [PEGI - Pan European Game Information](https://pegi.info).<BR/>
```Exempel: PEGI 12```  

Notera att kodning av målgrupp, motsvarande 008/22, ska anges i [Målgrupp](#målgrupp) under Instans av Verk.


### Systemkrav
Det är obligatoriskt i Libris att ange konsol här. 
* Systemkrav/Modell/Benämning (systemRequirement/MachineModel/label = 753 #a)</BR>
Skriv in uppgiften under Benämning.  
```Exempel: XBox 360```<BR/>

Konsol kan även, om så önskas, för att uppgiften ska bli synlig i lokala system, anges inom parentes efter [omfång](#omfång) eller i egenskapen [Systemkrav och mediespecifika uppgifter](#systemkrav-och-mediespecifika-uppgifter).


### Anmärkning
* Anmärkning/Anmärkning/Benämning (hasNote/Note/label = 500 #a)   
  Skriv in allmänna anmärkningar här. För att lägga till Anmärkning, välj Anmärkning (hasNote) och lägg till.
  Skriv in uppgiften under Benämning.<BR/>
```Exempel: Avsett för 1-7 spelare, 1-2 spelare i nätverk```  
  

### Systemkrav och mediespecifika uppgifter
Här kan systemkrav och mediespecifika uppgifter som inte framgår någon annanstans i beskrivningen anges. Ange uppgiften som den är presenterad i resursen. Uppgift om konsol ska alltid anges i egenskapen [Systemkrav](#Systemkrav). Om så önskas, för att den ska bli synlig i i lokala system, kan uppgift om konsol även anges här eller inom parentes efter [Omfång](#Omfång).
* Har anmärkning: Systemkrav och mediespecifika uppgifter/Anmärkning: Systemkrav och mediespecifika uppgifter/Anmärkningstext        (marc:hasSystemDetailsNote = 538 #a)</BR>
```Exempel: Systemkrav: 50 GB minimum på hårddisken ; dualshok 4 ; stöd för remote play```  


## Verk 
För att lägga till egenskaper under Instans av verk, klicka på plustecknet till höger om Instans av verk och verkstypen. Sök fram egenskapen och välj den genom att klicka på plustecknet vid egenskapens namn.

Läs mer om egenskaperna under [generell beskrivning av Verk](https://libris.kb.se/katalogisering/help/workflow-work).  

Läs mer om [Verk och Instans på Libris informationssidor på kb.se](https://www.kb.se/samverkan-och-utveckling/nytt-fran-kb/nyheter-samverkan-och-utveckling/2018-05-30-verk-och-instans-i-startversionen-av-nya-libris.html). 


### Instans av verk (instanceOf/Work)
* Instans av verk/Multimedia (instanceOf/Work/Multimedia)  
För ett datorspel är verkstypen Multimedia.  


### Verkets titel 
Ange vid behov den föredragna titeln för verket här. För instruktioner, se [Metadatabyrån - Föredragen titel för verket](https://metadatabyran.kb.se/beskrivning/generella-anvisningar---rda/verk-och-uttryck/foredragen-titel-for-verket).


#### Verk utan primär medverkan
*	Uttryck av/Verk/Har titel/Titel/Huvudtitel (expressionOf/Work/hasTitle/Title/mainTitle (= 130 #a)  
Datorspel har sällan en primär medverkande. Ofta är det två eller flera agenter (programmerare, utvecklare etc.) som är gemensamt ansvariga för att ha skapat verket. För att en agent ska räknas som primär medverkande ska denne vara ansvarig för alla aspekter kopplade till skapandet av datorspelet. 
Ange  den föredragna titeln i Huvudtitel.  
```Exempel:  Prototype (datorspel)```</BR>
Tillägget inom parentes (datorspel) görs för att skilja datorspelet Prototype från filmen Prototype.</BR> 
Läs mer om [tillägg till föredragna titlar för verk i Metadatabyrån](https://metadatabyran.kb.se/beskrivning/generella-anvisningar---rda/verk-och-uttryck/foredragen-titel-for-verket/tillagg-till-foredragna-titlar-for-verk).</BR>


#### Verk med primär medverkan
* Har titel/Titel/Huvudtitel (hasTitle/Title/mainTitle = 240 1/0 #a)</BR>
Det är ovanligt att datorspel har primär medverkan. Ofta är det två eller flera agenter (programmerare, utvecklare etc.) som är gemensamt ansvariga för att ha skapat verket. För att en agent ska räknas som primär medverkande ska denne vara ansvarig för alla aspekter kopplade till skapandet av datorspelet. 
Ange den föredragna titeln i Huvudtitel.


### Medverkan och funktion
Följ instruktioner i [Relationer till agenter - Metadatabyrån](https://metadatabyran.kb.se/beskrivning/generella-anvisningar---rda/relationer/relationer-till-agenter) 
 

#### Primär medverkan
* Medverkan och funktion/Primär medverkan/Agent/Person 
</BR>(contribution/PrimaryContribution/agent/Person = 100 1/- #a)
* Medverkan och funktion/Primär medverkan/Agent/Organisation 
</BR>(contribution/PrimaryContribution/agent/Organisation = 110 2/-)
* Medverkan och funktion/Primär medverkan/Funktion
</BR>(contribution/PrimaryContribution/role = 100, 110 #4)


#### Medverkan
* Medverkan och funktion/Medverkan/Agent/Person  
(contribution/agent/Person = 700 1/- #a)
* Medverkan och funktion/Medverkan/Agent/Organisation
</BR>(contribution/agent/Organisation = 710 2/-)
* Medverkan och funktion/Medverkan/Funktion  
(contribution/role = 700, 710 #4)
 

#### Funktioner som saknar funktionskod
Utbudet av funktionskoder för agenter kopplade till datorspel är fortarande ganska begränsat. För att ange en funktion som inte har en motsvarande funktionskod, klicka på plustecknet vid Funktion (Lägg till funktion) och sedan på Skapa lokal entitet. Klicka på plustecknet Lägg till egenskaper under: Funktion och välj Benämning. Skriv in önskad term. Värdet exporteras till 7XX #e.</BR>
```Exempel: spelutvecklare```
  

### Språk 
* Språk (language = 008/35-37)</BR>
  Länka till entitet.  
  ```Exempel: engelska (eng)``` 
  </BR>Ange flera språk genom att klicka på plustecknet vid Språk (Lägg till språk) och sök fram entitet för språket.</BR>
  Länka till entitet. 
För att ange originalspråk för ett översatt verk, se Översättning, nedan. 
  
#### Översättning  
För datorspel som är/innehåller en översättning, lägg till:  
* Anmärkning: Språk (marc:LanguageNote = 041 i1: 1)  
  Ange om resursen är/innehåller en översättning.  
**Från och med version 1.18 skapas uppgiften automatiskt.**
  
**Från och med version 1.18 anges originalspråk för översättningar under Översättning av, inte som tidigare under Originalversion. OBS! För närvarande ska titel och medverkan inte läggas till under Översättning av. Fortsätt att ange dem som tidigare direkt under Instans av verk.**
  
* Översättning av/Verk/Språk (translationOf/Work/language = 041 #h)  
  Ange originalspråk för översatt verk här. Lägg till Översättning av under Instans av verk, skapa Verk som lokal entitet. Du behöver inte välja verkstyp här. Lägg till Språk och länka till entitet.</BR> 
  ```Exempel: japanska (jpn)```  
  
För översättningar i flera led, använd egenskapen Intermediärt språk till översättningar.


### Relationer till ingående verk och andra verk
För instruktioner, se [Ingående verk/uttryck - Metadatabyrån](https://metadatabyran.kb.se/beskrivning/generella-anvisningar---rda/relationer/ingaende-verk-uttryck)


### Genre form 
För utförliga anvisningar om hur man anger genre/form, se [hjälptexten Verk](https://libris.kb.se/katalogisering/help/workflow-work#genre): Genre form.
 
* Genre/form – saogf-termer (genreForm = 655 -/7 #a, #2 saogf)</br> 
Länka till entiteten:</br> 
 ```Datorspel```

För datorspel ska typ av fil (= 008/26) anges med termen Dataspel, g i Genre/form.

* Genre/form - termer som motsvarar marc-koder i 008</br> 
Välj Typ av fil.
Länka till entiteten:</br>
 ```Dataspel, g```
  
  
### Klassifikation  
För anvisningar om hur man anger klassifikation, se [Klassifikation i Metadatabyrån](https://metadatabyran.kb.se/klassifikation).
 

### Ämne  
* Ämne  
  Länka  i första hand till entiteter för ämnesord. Följ instruktionerna för [Svenska ämnesord i Metadatabyrån](https://metadatabyran.kb.se/amnesord-och-genre-form/svenska-amnesord).   


### Målgrupp     
 * Målgrupp (intendedAudience = 008/22)  
  Länka till entitet.  
  ```Exempel: j (= barn- och ungdom, 0-16 år)```</br> 
  Normalvärde för spel som riktar sig till barn och ungdom.

För att lägga till Målgruppsanmärkning (Målgrupp/Målgrupp/Benämning), se [Målgruppsanmärkning](#Målgruppsanmärkning) under Instans.
 

### Innehållstyp
 * Innehållstyp/Innehållstyp (contentType/ContentType = 336 #b)   
  Länka till entiteten:</BR>
  ```datorprogram, computer program (kod = cop)```
  

### Anmärkningar
#### Anmärkning om språk
 * Anmärkning/Anmärkning om språk/Benämning (hasNote/marc:LanguageNote/marc:LanguageNote/label = 546 #a)  
  ```Exempel: Tal och text på engelska. Manual på svenska.```  

### Sammanfattning av innehåll
 * Sammanfattning av innehåll/Sammanfattning/Benämning (summary/Summary/label = 520 #a)</BR>
Lägg till Sammanfattning av innehåll. Välj Sammanfattning av innehåll. Lägg till Sammanfattning. 
 Skriv in uppgiften under Benämning.
     
 * Typ av sammanfattning/typ av innehållsbeskrivning (marc:summaryType = 520 ind1)  
 Sök fram och lägg till Typ av sammanfattning. Välj typ från lista.  
 ```Exempel: Ej preciserad```
