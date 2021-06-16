---
section: Materialtyper
title: E-bok
order: 42
date: 2021-06-16
tags:
- e-bok
- e-bokskatalogisering
---


# E-bok
Denna hjälptext ger kortfattade instruktioner för de vanligaste egenskaperna vid beskrivning av en e-bok. För utförliga instruktioner, se de generella hjälptexterna för Adminmetadata, Instans och Verk, se nedan.

## Innehåll

[Inledning](#inledning)

| [Adminmetadata](#adminmetadata) | [Instans](#instans) | [Verk](#verk) | 
| ----------- |  ----------- | ----------- |
|  [Adminmetadata - Metadatabyrån](https://metadatabyran.kb.se/beskrivning/specialanvisningar/adminmetadata-i-libris) | [Generell hjälptext för Instans](https://libris.kb.se/katalogisering/help/workflow-instance) | [Generell hjälptext för Verk](https://libris.kb.se/katalogisering/help/workflow-work) |
| | [Utgivningssätt](#utgivningss-tt) | [Verkets titel](#verkets-titel) |
| | [Medietyp](#medietyp) | [Medverkan och funktion](#medverkan-och-funktion) |
| | [Bärartyp](#bärartyp) | [Språk](#språk) |
| | [Titel](#titel) | [Relationer till ingående verk och andra verk](#relationer-till-ingående-verk-och-andra-verk)  |
| | [Upphovsuppgift](#upphovsuppgift) | [Genre/form](#genre-form) | 
| | [Upplageuppgift](#upplageuppgift) | [Klassifikation](#klassifikation) |
| | [Utgivning](#utgivning) | [Ämne](https://libris.kb.se/katalogisering/help/workflow-general-sh) |
| | [Copyrightår](#copyrightår) | [Målgrupp](#målgrupp) | 
| | [Identifikator](#identifikator) | [Innehållstyp](#innehållstyp) | 
| | [Omfång](#omfång) | [Sammanfattning av innehåll](#sammanfattning-av-innehåll) |
| | [Övriga fysiska detaljer](#övriga-fysiska-detaljer) | [Anmärkning om akademisk avhandling](#anmärkning-om-akademisk-avhandling) |
| | [Seriemedlemskap](#seriemedlemskap) | |
| | [Anmärkning](#anmärkning) |
| | [Digital karakteristika](#digital-karakteristika) | |
| | [Annat bärarformat](#annat-bärarformat) | |
| | [Elektronisk adress](#elektronisk-adress) | | 
| | [Målgruppsanmärkning](#målgruppsanmärkning) | |


## Inledning
Beskrivningen av en e-bok innehåller följande tre delar:  
* [Adminmetadata - Metadatabyrån](https://metadatabyran.kb.se/beskrivning/specialanvisningar/adminmetadata-i-libris) - administrativa data om instansbeskrivningen, såsom kontrollnummer och beskrivningsnivå.
* [Instans](https://libris.kb.se/katalogisering/help/workflow-instance) - instans kan också kallas utgåva eller manifestation. Exempel på egenskaper under Instans är utgivningsplats, utgivare och utgivningsår, bärartyp, omfång.
* [Verk](https://libris.kb.se/katalogisering/help/workflow-work) – återger egenskaper för det abstrakta verket såsom medverkan och funktion (t.ex. författare), ämne, klassifikation, språk och innehållstyp. Verksbeskrivningen ligger under rubriken Instans av verk.

Många av egenskaperna finns redan i mallen E-bok, andra kan behöva läggas till. För instruktioner om att lägga till eller ta bort egenskaper, länka till entitet, skapa lokal entitet och om hur formuläret fungerar i övrigt, se Redigering i vänstermenyn. För en förhandspost, använd gärna Berika från mall och välj E-bok.  

För information om katalogregler och Librispraxis, se [Metadatabyrån](https://metadatabyran.kb.se/) och [RDA Toolkit](https://original.rdatoolkit.org/).

Se även [instruktionsfilmer på KB:s Youtubekanal](https://www.youtube.com/playlist?list=PLZVkEICvA5-GRT2oJQmLgq_2Pksx6zYPy).   

## Adminmetadata
[Adminmetadata - Metadatabyrån](https://metadatabyran.kb.se/beskrivning/specialanvisningar/adminmetadata-i-libris)

* Kontrollera beskrivningsnivån. I mallen är standardvärdet Biblioteksnivå (normalvärde för Librisbiblioteken). Ändra vid behov.
**Observera: Om nivån är CIP-post eller preliminär post, ändra till annan nivå, annars kan ändringar skrivas över!** 

## Instans
För att lägga till egenskaper under Instans, klicka på plustecknet i redigeringsvyn (den stora runda plusikonen under Verktygsikonen) - Lägg till egenskaper under: Elektronisk.  Sök fram egenskapen och välj den genom att klicka på plustecknet vid egenskapens namn eller på egenskapens namn.    

Läs mer om [egenskaperna under Instans](https://libris.kb.se/katalogisering/help/workflow-instance).  

### Utgivningssätt 
* Utgivningssätt (issuanceType)   
  Välj från lista.  
  ```Exempel: Monografisk resurs```

### Medietyp
* Medietyp (mediaType/Mediatype = 337 #b)  
  Länka till entiteten:  
  ```dator, computer, c```

### Bärartyp
* Bärartyp (carrierType/CarrierType = 338 #b)  
  Länka till entiteten:  
  ```onlineresurs, online resource, cr```</BR>
  
  Om koden "r" (= fjärranslutning) behövs i 007/01 (= särskild bärarbeteckning) för bibliotekets lokala system, länka till entiteten:</BR>
  ```Onlineresurs, r```</BR>
  
  Om koden "o" (= onlineutgåva) behövs i 008/23 (= form för manifestationen) för bibliotekets lokala system, länka till entiteten:</br>
  ```Onlineutgåva, o```</BR>

### Titel
Notera att egenskapen Allmän medieterm (marc:mediaTerm = 245 #h) (= Medieterm) inte ska ingå i beskrivningar som görs enligt RDA.

* Har titel/Titel/Huvudtitel (hasTitle/Title/mainTitle = 245 #a)</br>
Återge huvudtiteln som den förekommer i källan, se [RDA 2.2.2.4.2](http://access.rdatoolkit.org/rdachp2_rda2-2904.html).</br>
För en titel som börjar med bestämd eller obestämd artikel, ska artikeln fileras bort. Ange fileringsvärde genom att lägga till fileringsvärde (plustecknet vid Titel - Lägg till egenskaper under: Titel) och ange en siffra.</br> 
Se exempel på sidan [Filering av titel - Metadatabyrån](https://metadatabyran.kb.se/beskrivning/generella-anvisningar---rda/manifestation-instans/titel/filering-av-titel)

* Har titel/Titel/Övrig titelinformation (hasTitle/Title/subtitle = 245 #b)

För en parallell huvudtitel på ett annat språk eller i en annan skriftart, se [Parallelltitel](#parallelltitel).<br/>

För att ange Föredragen titel, se Verk/Har titel/Titel/Huvudtitel.  

#### Titel - alternativ stavning
* Relation/Relation/Entitet/Verk/Har titel/Titel/Huvudtitel  
(relationship/Relationship/entity/Work/hasTitle/Title/mainTitle = 740)  
Används inte. Se Varianttitel (246).  

#### Varianttitel
* Har titel/Varianttitel/Huvudtitel (hasTitle/VariantTitle/mainTitle = 246 #a)

#### Omslagstitel   
* Har titel/Omslagstitel/Huvudtitel (hasTitle/CoverTitle/mainTitle = 246 1/4 #a)
* Har titel/Omslagstitel/Övrig titelinformation (hasTitle/CoverTitle/subtitle = 246 1/4 #b)

#### Ryggtitel   
* Har titel/Ryggtitel/Huvudtitel (hasTitle/SpineTitle/mainTitle = 246 1/8 #a)
* Har titel/Ryggtitel/Övrig titelinformation (hasTitle/SpineTitle/subtitle = 246 1/8 #b)

#### Delbeteckning
* Har titel/Titel/Har del/Titeldel/Delbeteckning (hasTitle/Title/hasPart/TitlePart/partNumber = 245 #n)

#### Deltitel  
* Har titel/Titel/Har del/Titeldel/Deltitel (hasTitle/Title/hasPart/TitlePart/partName = 245 #p)

#### Parallelltitel
* Har titel/Parallelltitel/Huvudtitel (hasTitle/ParallelTitle/mainTitle = 246 1/1 #a)
* Har titel/Parallelltitel/Övrig titelinformation (hasTitle/ParallelTitle/subTitle = 246 1/1 #b)

### Upphovsuppgift
* Upphovsuppgift (responsibilityStatement = 245 #c)

### Upplageuppgift
* Upplageuppgift (editionStatement = 250 #a)

### Utgivning  
* Primär utgivning/Utgivning (publication/PrimaryPublication)  

#### Utgivningsplats
* Primär utgivning/Utgivning/Plats/Plats/Benämning (place/label = 264 -/1 #a)

#### Utgivningsland  
* Primär utgivning/Utgivning/Land (country = 008/15-17)

#### Utgivarnamn
* Primär utgivning/Utgivning/Agent/Agent/Benämning (agent/label = 264 -/1 #b)

#### År och datum 
**År**
* Primär utgivning/Utgivning/År (date = 008/07-10, 264 -/1 #c)  
 År får endast innehålla siffror (0-9) och bokstaven u.  
 Observera att År **måste** finnas med i beskrivningen, även om Datum finns med.   

**Datum**
* Primär utgivning/Utgivning/Datum (date = 264 -/1 #c)  
  Datum får innehålla text och interpunktionstecken. till exempel klamrar och frågetecken.  
  Datum används endast när man förutom årtal ska använda andra tecken än siffror och bokstaven u.  
  
**Flera år (flerbandsverk):**  
Använd Startår och Slutår (inte År).
* Primär utgivning/Utgivning/Startår (008/07-10 + 264 -/1 #c)  
* Primär utgivning/Utgivning/Slutår (008/11-14 + 264 -/1 #c) 

### Copyrightår   
* Copyright/Copyright/Datum (copyright/Copyright/date = 264 -/4 #c)  

### Identifikator 
#### ISBN
* Identifikator/ISBN/Värde (identifiedBy/Isbn/value = 020 #a)  
* Identifikator/Särskiljande tillägg  (identifiedBy/qualifier = 020 #q)  
Notera att felaktigt eller ogiltigt ISBN ska anges under [Indirekt identifierad av](#indirekt-identifierad-av). Använd inte Ogiltigt värde. 

#### URN, DOI, handle
* Identifikator/URN/Värde (identifiedBy/URN/value = 024 7/- #a</BR>
Lägg till entitet under Identifikator och välj typ av identifikator i rullgardinsmenyn, till exempel URN, DOI eller Hdl (Handle).  
Lägg in identifikatorn under Värde.  
```Exempel: Identifikator/URN/Värde: urn:nbn:se:su:diva-83163``` 

### Indirekt identifierad av  
Felaktigt eller ogiltigt ISBN ska anges här. Använd inte Ogiltigt värde under Identifikator/ISBN.  

* Indirekt identifierad av/ISBN/Värde (indirectlyIdentifiedBy/Isbn/value = 020 #z)
* Indirekt identifierad av/Särskiljande tillägg (= Bestämning) (indirectlyIdentifiedBy/qualifier = 020 #q)

### Omfång 
Ange antal enheter samt typ av enhet, se [RDA 3.4.1.3](http://access.rdatoolkit.org/rdachp3_rda3-2098.html). Ange även antal underenheter, t.ex. sidor, inom parentes efter antal enheter och typ, se [RDA 3.4.1.7.5](http://access.rdatoolkit.org/rdachp3_rda3-2245.html). 
* Omfång/Omfång/Benämning (extent/Extent/label = 300 #a)<br>
 Skriv in uppgiften under Benämning.  
  ```Exempel:   1 onlineresurs (239 sidor)```  

### Övriga fysiska detaljer   
* Övriga fysiska detaljer (other physical details = 300 #b)

### Seriemedlemskap
* Seriemedlemskap/Seriemedlemskap/Ingår i serie  

#### Seriens titel (auktoriserad sökingång för serie)  
* Seriemedlemskap/Ingår i serie/Instans av Verk/Verk/Har titel/Titel/Huvudtitel  
(seriesMembership/inSeries/InstanceofWork/Work/hasTitle/Title/mainTitle = 830 #a)

#### ISSN  
* Seriemedlemskap/Ingår i serie/Instans/Identifikator/ISSN/Värde  
(seriesMembership/inSeries/Instance/identifiedBy/ISSN/Value = 490 #x, 830 #x)</br>
Felaktiga ISSN i en instans ska återges under [Anmärkning](#anmärkning). Se även [Serieuppgift - Metadatabyrån](https://metadatabyran.kb.se/beskrivning/generella-anvisningar---rda/manifestation-instans/serieuppgift). 

#### Serieuppgift  
* Seriemedlemskap/Serieuppgift (seriesMembership/seriesStatement = 490 #a)

#### Numrering inom serie  
* Seriemedlemskap/Numrering inom serie (seriesMembership/seriesEnumeration = 490 #v, 830 #v)

#### Indikator för seriebiuppslag   
* Seriemedlemskap/Indikator för seriebiuppslag (marc:seriesTracingPolicy = 490 i1: 0/1)

#### Författarserie
* Seriemedlemskap/Ingår i serie/Instans/Instans av Verk/Verk/Har titel/Titel/Huvudtitel  
(seriesMembership/inSeries/Instance/InstanceOf/Work/hasTitle/Title/mainTitle = 800 #t)  
  ```Exempel: Millenium```   
* Seriemedlemskap/Ingår i serie/Instans/Instans av Verk/Verk/Medverkan och funktion/Primär medverkan/Agent/Person     (seriesMembership/inSeries/Instance/InstanceOf/Work/contribution/PrimaryContribution/Agent/Person = 800 #a)  
Lägg till Medverkan och funktion under Verk (inom Seriemedlemskap) genom att klicka på plustecknet vid Verk (Lägg till egenskaper under: Verk). Välj Medverkan och funktion. Välj Primär medverkan. Lägg till Agent.   
 ```Exempel: Larsson, Stieg, 1954-2004```  
  Vid behov, skapa ny agent. I undantagsfall, skapa lokal entitet. Se [Agenter i Libris - Metadatabyrån](https://metadatabyran.kb.se/auktoritetsarbete-och-agenter/agenter-i-libris) 

#### Numrering inom serie   
* Seriemedlemskap/Numrering inom serie (seriesMembership/seriesEnumeration = 800 #v)  
  Skriv in uppgiften.  
  ```Exempel: 1```  

### Anmärkning
* Anmärkning/Anmärkning/Benämning (hasNote/Note/label = 500 #a)

### Digital karakteristika
  * Digital karakteristika/Kodningsformat/Benämning (digitalCharacteristic/EncodingFormat/label = 347#b)</BR>
Ange kodningsformat här, se [RDA 3.19.3.3](http://access.rdatoolkit.org/rdachp3_rda3-5189.html).</BR>
Lägg till Digital karakteristika. Lägg till Kodningsformat som lokal entitet. Skriv in uppgiften under Benämning.</BR>
  ```Exempel: PDF```

### Annat bärarformat
* Annat bärarformat (otherPhysicalFormat = 776)  
  Länka till utgåvan i annat bärarformat, till exempel från en tryckt utgåva till en elektronisk utgåva eller tvärtom.  
  [Annat bärarformat i Metadatabyrån](https://metadatabyran.kb.se/beskrivning/generella-anvisningar---rda/relationer/relaterade-resurser)

### Elektronisk adress
Använd egenskapen Elektronisk adress endast när ingen uppgift finns om vilken version länken går till (används normalt inte).

#### Tillhörande media
* Tillhörande media/Mediaobjekt/URI (associatedMedia/Mediaobject/uri = 856 4/0 #u)</br>
Använd Tillhörande media för att lägga in en elektronisk adress till den besrivna resursen. Lägg till Mediaobjekt under Tillhörande media. Välj Skapa lokal entitet. Lägg till egenskapen URI. Klistra in aktuell URI.
* Tillhörande media/Mediaobjekt/Offentlig anmärkning (associatedMedia/Mediaobject/marc:publicNote = 856 4/0 #z)</br>
Vid behov, lägg till Offentlig anmärkning. Skriv in anmärkningen.
* Del av materialet som avses/Resurs/Benämning (appliesTo/Resource/label = 856 4/0 #3)</br>
Vid behov, lägg till Del av material som avses under Mediaobjekt och skapa Resurs som lokal entitet. Lägg till Benämning.

### Målgruppsanmärkning  
* Målgrupp/Målgrupp/Benämning (intendedAudience/IntendedAudience/label = 521 #a)  
Observera att kodning av målgrupp, motsvarande 008/22, ska registreras under Instans av Verk/Genre.  

## Verk
För att lägga till egenskaper under Instans av verk, klicka på plustecknet till höger om Instans av verk och verkstypen. Sök fram egenskapen och välj den genom att klicka på plustecknet vid egenskapens namn.  

Läs mer om [egenskaperna under generell beskrivning av Verk](https://libris.kb.se/katalogisering/help/workflow-work).  

Läs mer om [Verk och Instans på Libris informationssidor på kb.se](https://www.kb.se/samverkan-och-utveckling/nytt-fran-kb/nyheter-samverkan-och-utveckling/2018-05-30-verk-och-instans-i-startversionen-av-nya-libris.html).</BR> 

### Instans av verk
* Instans av verk/Text (instanceOf/Work/Text)  
För en e-bok är verkstypen Text.  

### Verkets titel
Ange den föredragna titeln för verket här, vid behov. För instruktioner, se [Metadatabyrån - Föredragen titel för verket](https://metadatabyran.kb.se/beskrivning/generella-anvisningar---rda/verk-och-uttryck/foredragen-titel-for-verket).

#### Verk med Primär medverkan
* Har titel/Titel/Huvudtitel (hasTitle/Title/mainTitle = 240 1/0 #a)  
 Föredragen titel för ett verk med primär medverkan anges här.  

#### Verk utan Primär medverkan
*	Uttryck av/Verk/Har titel/Titel/Huvudtitel (expressionOf/Work/hasTitle/Title/mainTitle = 130 #a)</br>
 Föredragen titel för ett verk utan primär medverkan anges här.

### Medverkan och funktion
Följ instruktioner i [Relationer till Agenter - Metadatabyrån](https://metadatabyran.kb.se/beskrivning/generella-anvisningar---rda/relationer/relationer-till-agenter) 

#### Primär medverkan  
* Medverkan och funktion/Primär medverkan/Agent/Person  
(contribution/PrimaryContribution/agent/Person = 100 1/- #a)
* Medverkan och funktion/Primär medverkan/Agent/Organisation (110 2/-)
* Medverkan och funktion/Primär medverkan/Agent/Jurisdiktion (110 1/-)
* Medverkan och funktion/Primär medverkan/Funktion  
(contribution/PrimaryContribution/role = 100, 110 #4)

#### Medverkan
* Medverkan och funktion/Medverkan/Agent/Person  
(contribution/agent/Person = 700 1/- #a)
* Medverkan och funktion/Medverkan/Agent/Organisation (710 2/-)
* Medverkan och funktion/Medverkan/Agent/Jurisdiktion (710 1/-)
* Medverkan och funktion/Medverkan/Funktion  
(contribution/role = 700, 710 #4)

### Språk 
* Språk (language = 008/35-37)</br>
Ange textens språk här. För en text på svenska, länka till svenska. För att ange att texten är på flera språk, länka till ytterligare en språkkod.
För att ange originalspråk för ett översatt verk, se Översättning, nedan.

#### Översättning 
* Anmärkning: Språk (marc:LanguageNote = 041 i1: 1)  
  Ange om resursen är/innehåller en översättning. 
</br>**Från och med version 1.18 skapas uppgiften automatiskt.**

**Från och med version 1.18 anges originalspråk för översättningar under Översättning av, inte som tidigare under Originalversion. OBS! För närvarande ska titel och medverkan inte läggas till under Översättning av. Fortsätt att ange dem som tidigare direkt under Instans av verk.**

* Översättning av/Verk/Språk (translationOf/Work/language = 041 ‡h) 
Ange originalspråk för ett översatt verk här.
Lägg till Översättning av under Instans av verk, skapa Verk som lokal entitet. Du behöver inte välja verkstyp här. Lägg till Språk och länka till entitet.</br>
  ```Exempel: engelska (eng)```  

För översättningar i flera led, använd egenskapen Intermediärt språk till översättningar.  

#### Sammanfattningsspråk
Se [Sammanfattning av innehåll](#sammanfattning-av-innehall).

### Språkanmärkning     
* Anmärkning/Anmärkning om språk/Anmärkning: Språk/Benämning  
(hasNote/marc:LanguageNote/marc:LanguageNote/label = 546 #a)  
Anmärkningen finns i mallen E-bok och kan läggas till med hjälp av Berikning från mall. Det går ännu inte att lägga till egenskapen från Lägg till egenskaper.

### Relationer till ingaende verk och andra verk
För instruktioner, se [Ingående verk/uttryck - Metadatabyrån](https://metadatabyran.kb.se/beskrivning/generella-anvisningar---rda/relationer/ingaende-verk-uttryck)

### Genre form
För anvisningar om hur man anger genre/form, se [hjälptexten Verk](https://libris-stg.kb.se/katalogisering/help/workflow-work#genre-form).

##### Exempel på användning av Genre/form
**Roman**  
Exempel: Haag, Martina: Det är något som inte stämmer  
Genre/form (saogf-term, 655): Självbiografiska skildringar, Romaner  
Litterär genre (008/33): Roman  

**Diktsamling**  
Exempel: Hallgren, Hanna: Vinterresan  
Genre/form (saogf-term, 655): Poesi  
Litterär genre (008/33): Dikter

**Bilderbok för barn**  
Genre/form (barngf-term, 655): Bilderböcker  
Genre/form (barngf-term, 655): Barn- och ungdomslitteratur  
Litterär genre (008/33): Skönlitterärt verk, genre ej angiven

**Fackbok för barn**  
Genre/form (barngf-term, 655): Faktaböcker   
Litterär genre (008/33): Ej skönlitterärt verk

**Biografi**  
Genre/form (saogf-term, 655): Biografi  
Biografiskt material (008/34): Biografi över en individ  
Litterär genre (008/33): Ej skönlitterärt verk

**Självbiografi**  
Genre/form (saogf-term, 655): Självbiografier  
Biografiskt material (008/34): Självbiografisk text, Självbiografi  
Litterär genre (008/33): Ej skönlitterärt verk

**Fackbok, ej biografi**  
Genre/form (saogf-term, 655): Lämpliga saogf-termer.  
Se även Svenska ämnesords översikt över [Allmänna genre/formtermer i Metadatabyrån](https://metadatabyran.kb.se/amnesord-och-genre-form/svenska-amnesord-genre-form/allmanna-genre-formtermer).  
Litterär genre (008/33): Ej skönlitterärt verk  

**Festskrift**  
Genre/form (saogf-term, 655): Festskrifter  
Festskrift (008/30): Ja, resursen är en festskrift  
Litterär genre (008/33): Ej skönlitterärt verk  

**Akademisk avhandling**  
Genre/form (saogf-term, 655): Avhandlingar  
Innehåll (008/24-27): Avhandling

### Klassifikation  
För anvisningar om hur man anger klassifikation, se [Klassifikation - Metadatabyrån](https://metadatabyran.kb.se/klassifikation).

### Ämne  
* Se [instruktioner för Svenska ämnesord i Metadatabyrån](https://metadatabyran.kb.se/amnesord-och-genre-form/svenska-amnesord)  

### Målgrupp     
* Målgrupp (008/22)
<br/>```Exempel:```
  * ```Barn och ungdom (0-16 år) (008/22: j)```  
  Normalvärde för barn- och ungdomslitteratur.
  
  * ```Barn (ca 10-12 år)/Läromedel (008/22: c)```  
  Normalvärde för läromedel avsedda för skolbruk (till och med gymnasiet).  

 Målgruppsanmärkning (Målgrupp/Målgrupp/Benämning), se Instans.  

### Innehållstyp
* Innehållstyp/Innehållstyp (contentType/ContentType = 336 #b)   
```Exempel: text (txt)```

  För att lägga till ytterligare innehållstyp, till exempel "sti" = stillbild för en bilderbok med både text och bild, länka till ytterligare en entitet.
  I äldre poster har ytterligare innehållstyp lagts i Har del/Verk. Dessa behöver inte ändras.

### Sammanfattning av innehåll
* Sammanfattning av innehåll/Sammanfattning/Benämning (summary/Summary/label = 520 #a)</br>
Lägg till Sammanfattning av innehåll. Välj Sammanfattning av innehåll. Lägg till Sammanfattning.
Skriv in uppgiften under Benämning.</br>
```Exempel: Åtskilliga utdrag af framledne … Axel v. Fersens bref till f.d. konungen av Swerige, Gustaf Adolph, 1806```

* Typ av sammanfattning/typ av innehållsbeskrivning (marc:summaryType = 520 ind1)</br>
Sök fram och lägg till Typ av sammanfattning. Välj typ från lista.</br>
```Exempel: Ej preciserad```

#### Sammanfattningsspråk
* Sammanfattning av innehåll/Sammanfattning/Språk (summary/Summary/language = 041 #b)</br>
Lägg till sammanfattningsspråk. Lägg till Sammanfattning. Ta bort Benämning. Länka till entiteten för sammanfattningens språk.<br>
```Exempel: Engelska```

### Anmärkning om akademisk avhandling    
* Anmärkning om akademisk avhandling/Anmärkning om akademisk avhandling/Benämning (dissertation/Dissertation/label = 502 #a)</br>
Lägg till Anmärkning om akademisk avhandling. Skapa lokal entitet.
Skriv in anmärkningen under Benämning.
```Exempel: Diss. Umeå : Umeå universitet, 2018```
