---
section: Materialtyper
title: E-bok
order: 42
date: 2019-06-28
tags:
- under arbete
- e-bok
- e-bokskatalogisering
---


## E-bok

### Innehåll

[Inledning](#inledning)

| [Adminmetadata](#adminmetadata) | [Instans](#instans) | [Verk](#verk) | 
| ----------- |  ----------- | ----------- | 
|  [Generell hjälptext för Adminmetadata](https://libris.kb.se/katalogisering/help/workflow-adminmetadata) | [Generell hjälptext för Instans](https://libris.kb.se/katalogisering/help/workflow-instance) | [Generell hjälptext för Verk](https://libris.kb.se/katalogisering/help/workflow-work) |
| | [Utgivningssätt](#utgivningssatt) | [Verkets titel](#verkets-titel) |
| | [Medietyp](#medietyp) | [Medverkan och funktion](#medverkan-och-funktion) |
| | [Bärartyp](#barartyp) | [Språk](#sprak) |
| | [Titel](#titel) | [Relationer till ingående verk och andra verk](#relationer-till-ingaende-verk-och-andra-verk)  |
| | [Upphovsuppgift](#upphovsuppgift) | [Genre](#genre) | 
| | [Upplageuppgift](#upplageuppgift) | [Klassifikation](#klassifikation) |
| | [Utgivning](#utgivning) | [Ämne](https://libris.kb.se/katalogisering/help/workflow-general-sh) |
| | [Copyrightår](#copyrightar) | [Målgrupp](#malgrupp) | 
| | [Identifikator](#identifikator) | [Innehållstyp](#innehallstyp) | 
| | [Omfång](#omfang) | [Sammanfattning av innehåll](#sammanfattning-av-innehall) |
| | [Övriga fysiska detaljer](#ovriga-fysiska-detaljer) | [Anmärkning om akademisk avhandling](#anmarkning-om-akademisk-avhandling) |
| | [Seriemedlemskap](#seriemedlemskap) | |
| | [Anmärkning](#anmarkning) |
| | [Digital karaktäristika](#digital-karaktaristika) | |
| | [Annat bärarformat](#annat-bararformat) | |
| | [Elektronisk adress](#elektronisk-adress) | | 
| | [Målgruppsanmärkning](#malgruppsanmarkning) | |


### Inledning
Beskrivningen av en e-bok innehåller följande tre delar:  
* [Adminmetadata](https://libris.kb.se/katalogisering/help/workflow-adminmetadata) - administrativa data om instansbeskrivningen, såsom kontrollnummer och beskrivningsnivå.
* [Instans](https://libris.kb.se/katalogisering/help/workflow-instance) - instans kan också kallas utgåva eller manifestation. Exempel på egenskaper under Instans är utgivningsplats, utgivare och utgivningsår, bärartyp, omfång.
* [Verk](https://libris.kb.se/katalogisering/help/workflow-work) – återger egenskaper för det abstrakta verket såsom medverkan och funktion (t.ex. författare), ämne, klassifikation, språk och innehållstyp. Verksbeskrivningen ligger under rubriken Instans av verk.

Denna hjälptext ger kortfattade instruktioner för de vanligaste egenskaperna vid beskrivning av en e-bok. För utförliga instruktioner, se de generella hjälptexterna för Adminmetadata, Instans och Verk, se ovan.  

Många av egenskaperna finns redan i mallen E-bok, andra kan behöva läggas till. För instruktioner om att lägga till eller ta bort egenskaper, länka till entitet, skapa lokal entitet och om hur formuläret fungerar i övrigt, se Redigering i vänstermenyn. För en förhandspost, använd gärna Berika från mall och välj E-bok.  

För information om katalogregler och Librispraxis, se [Anvisningar för katalogisering - RDA](http://www.kb.se/rdakatalogisering/ "Anvisningar för katalogisering - RDA") och [RDA Toolkit](https://access.rdatoolkit.org/).

Se även [instruktionsfilmer](https://www.youtube.com/playlist?list=PLZVkEICvA5-GRT2oJQmLgq_2Pksx6zYPy).   

### Adminmetadata
Använd generell hjälptext för [Adminmetadata](https://libris.kb.se/katalogisering/help/workflow-adminmetadata).

* Kontrollera beskrivningsnivån. I mallen är standardvärdet Biblioteksnivå (normalvärde för Librisbiblioteken). Ändra vid behov.
**Observera: Om nivån är CIP-post eller preliminär post, ändra till annan nivå, annars kan ändringar skrivas över!** 

### Instans
För att lägga till egenskaper under Instans, klicka på plustecknet i redigeringsvyn (den stora runda plusikonen under Verktygsikonen) - Lägg till egenskaper under: Elektronisk.  Sök fram egenskapen och välj den genom att klicka på plustecknet vid egenskapens namn eller på egenskapens namn.    

Läs mer om egenskaperna under [Instans](https://libris.kb.se/katalogisering/help/workflow-instance).  

#### Utgivningssatt 
* Utgivningssätt (issuanceType)   
  Välj från lista.  
  ```Exempel: Monografisk resurs```
  
#### Medietyp
* Medietyp (mediaType/Mediatype = 337 #b)  
  Länka till entiteten:  
  ```dator, computer, c```
  
#### Barartyp
* Bärartyp (carrierType/CarrierType = 338 #b)  
  Länka till entiteten:  
  ```onlineresurs, online resource, cr```</BR>
  
  Om koden "r" (= fjärranslutning) behövs i 007/01 (= särskild bärarbeteckning) för bibliotekets lokala system, länka till entiteten:</BR>
  ```Onlineresurs, r```</BR>
  
  Om koden "o" (= onlineutgåva) behövs i 008/23 (= form för manifestationen) för bibliotekets lokala system, länka till entiteten:</br>
  ```Onlineutgåva, o```</BR>
  
#### Titel
Notera att egenskapen Allmän medieterm (marc:mediaTerm = 245 #h) (= Medieterm) inte ska ingå i beskrivningar som görs enligt RDA.

* Har titel/Titel/Huvudtitel (hasTitle/Title/mainTitle = 245 #a)</br>
Återge huvudtiteln som den förekommer i källan, se [RDA 2.2.2.4.2](http://access.rdatoolkit.org/rdachp2_rda2-2904.html).</br>
För en titel som börjar med bestämd eller obestämd artikel, ska artikeln fileras bort. Ange fileringsvärde genom att lägga till fileringsvärde (plustecknet vid Titel - Lägg till egenskaper under: Titel) och ange en siffra.</br> 
Se exempel i formathandboken för Libris/Voyager: [Fileringsindikator](http://www.kb.se/katalogisering/Formathandboken/Fileringsindikator/)

* Har titel/Titel/Övrig titelinformation (hasTitle/Title/subtitle = 245 #b)

För en parallell huvudtitel på ett annat språk eller i en annan skriftart, se [Parallelltitel](#parallelltitel).<br/>

För att ange Föredragen titel, se Verk/Har titel/Titel/Huvudtitel.  

##### Titel - alternativ stavning
* Relation/Relation/Entitet/Verk/Har titel/Titel/Huvudtitel  
(relationship/Relationship/entity/Work/hasTitle/Title/mainTitle = 740)  
Används inte. Se Varianttitel (246).  

##### Varianttitel
* Har titel/Varianttitel/Huvudtitel (hasTitle/VariantTitle/mainTitle = 246 #a)

##### Omslagstitel   
* Har titel/Omslagstitel/Huvudtitel (hasTitle/CoverTitle/mainTitle = 246 1/4 #a)
* Har titel/Omslagstitel/Övrig titelinformation (hasTitle/CoverTitle/subtitle = 246 1/4 #b)

 ##### Ryggtitel   
* Har titel/Ryggtitel/Huvudtitel (hasTitle/SpineTitle/mainTitle = 246 1/8 #a)
* Har titel/Ryggtitel/Övrig titelinformation (hasTitle/SpineTitle/subtitle = 246 1/8 #b)

##### Delbeteckning
* Har titel/Titel/Har del/Titeldel/Delbeteckning (hasTitle/Title/hasPart/TitlePart/partNumber = 245 #n)

##### Deltitel  
* Har titel/Titel/Har del/Titeldel/Deltitel (hasTitle/Title/hasPart/TitlePart/partName = 245 #p)

##### Parallelltitel
* Har titel/Parallelltitel/Huvudtitel (hasTitle/ParallelTitle/mainTitle = 246 1/1 #a)
* Har titel/Parallelltitel/Övrig titelinformation (hasTitle/ParallelTitle/subTitle = 246 1/1 #b)

#### Upphovsuppgift
* Upphovsuppgift (responsibilityStatement = 245 #c)

#### Upplageuppgift
* Upplageuppgift (editionStatement = 250 #a)

#### Utgivning  
* Primär utgivning/Utgivning (publication/PrimaryPublication)  

##### Utgivningsplats
* Primär utgivning/Utgivning/Plats/Plats/Benämning (place/label = 264 -/1 #a)

##### Utgivningsland  
* Primär utgivning/Utgivning/Land (country = 008/15-17)

##### Utgivarnamn
* Primär utgivning/Utgivning/Agent/Agent/Benämning (agent/label = 264 -/1 #b)

##### År och datum 
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

#### Copyrightar   
* Copyright/Copyright/Datum (copyright/Copyright/date = 264 -/4 #c)  

#### Identifikator 
##### ISBN
* Identifikator/ISBN/Värde (identifiedBy/Isbn/value = 020 #a)  
* Identifikator/Särskiljande tillägg  (identifiedBy/qualifier = 020 #q)  
Notera att felaktigt eller ogiltigt ISBN ska anges under [Indirekt identifierad av](#indirekt-identifierad-av). Använd inte Ogiltigt värde. 

##### URN, DOI, handle
URN, DOI och handle anges i Identifikator/Identifikator/Värde med standardnummer eller standardkod specificerad i en Typanmärkning. 
* Identifikator/Identifikator/Värde (identifiedBy/Identifier/value = 024 7/- #a</BR>
  Skriv in uppgiften under Värde.</BR>
  ```Exempel: urn:nbn:se:su:diva-83163``` 
* Identifikator/Identifikator/Typanmärkning (identifiedBy/Identifier/typeNote = 024 7/- #2)</BR>
  För att specificera typ av standardnummer eller standardkod, lägg till Typanmärkning.</BR>
  Skriv in uppgiften.
  <br/>```Exempel:```
    * ```urn```
    * ```doi```
    * ```hdl```
    
#### Indirekt identifierad av  
Felaktigt eller ogiltigt ISBN ska anges här. Använd inte Ogiltigt värde under Identifikator/ISBN.  

* Indirekt identifierad av/ISBN/Värde (indirectlyIdentifiedBy/Isbn/value = 020 #z)
* Indirekt identifierad av/Särskiljande tillägg (= Bestämning) (indirectlyIdentifiedBy/qualifier = 020 #q)

#### Omfang 
Ange antal enheter samt typ av enhet, se [RDA 3.4.1.3](http://access.rdatoolkit.org/rdachp3_rda3-2098.html). Ange även antal underenheter, t.ex. sidor, inom parentes efter antal enheter och typ, se [RDA 3.4.1.7.5](http://access.rdatoolkit.org/rdachp3_rda3-2245.html). 
* Omfång/Omfång/Benämning (extent/Extent/label = 300 #a)<br>
 Skriv in uppgiften under Benämning.  
  ```Exempel:   1 onlineresurs (239 sidor)```  

#### Ovriga fysiska detaljer   
* Övriga fysiska detaljer (other physical details = 300 #b)

#### Seriemedlemskap
* Seriemedlemskap/Seriemedlemskap/Ingår i serie  

##### Seriens titel (auktoriserad sökingång för serie)  
* Seriemedlemskap/Ingår i serie/Instans av Verk/Verk/Har titel/Titel/Huvudtitel  
(seriesMembership/inSeries/InstanceofWork/Work/hasTitle/Title/mainTitle = 830 #a)

##### ISSN  
* Seriemedlemskap/Ingår i serie/Instans/Identifikator/ISSN/Värde  
(seriesMembership/inSeries/Instance/identifiedBy/ISSN/Value = 490 #x, 830 #x)</br>
Felaktiga ISSN i en instans ska återges under [Anmärkning](#anmarkning). Se [Anvisningar för Katalogisering (RDA), Series ISSN](http://www.kb.se/rdakatalogisering/Anvisningar/Arbetsfloden/Tryckta-monografier/#series_issn). 

##### Serieuppgift  
* Seriemedlemskap/Serieuppgift (seriesMembership/seriesStatement = 490 #a)

##### Numrering inom serie  
* Seriemedlemskap/Numrering inom serie (seriesMembership/seriesEnumeration = 490 #v, 830 #v)

##### Indikator för seriebiuppslag   
* Seriemedlemskap/Indikator för seriebiuppslag (marc:seriesTracingPolicy = 490 i1: 0/1)

##### Författarserie
* Seriemedlemskap/Ingår i serie/Instans/Instans av Verk/Verk/Har titel/Titel/Huvudtitel  
(seriesMembership/inSeries/Instance/InstanceOf/Work/hasTitle/Title/mainTitle = 800 #t)  
  ```Exempel: Millenium```   
* Seriemedlemskap/Ingår i serie/Instans/Instans av Verk/Verk/Medverkan och funktion/Primär medverkan/Agent/Person     (seriesMembership/inSeries/Instance/InstanceOf/Work/contribution/PrimaryContribution/Agent/Person = 800 #a)  
Lägg till Medverkan och funktion under Verk (inom Seriemedlemskap) genom att klicka på plustecknet vid Verk (Lägg till egenskaper under: Verk). Välj Medverkan och funktion. Välj Primär medverkan. Lägg till Agent.   
Följ dessa instruktioner:  
  [Relationer till Agent](https://libris.kb.se/katalogisering/help/workflow-agent-org-instance)  
 ```Exempel: Larsson, Stieg, 1954-2004```  
  Vid behov, skapa ny agent, se [Skapa ny agent](https://libris.kb.se/katalogisering/help/workflow-agent-person-new). I undantagsfall, skapa lokal entitet.   
  
##### Numrering inom serie   
* Seriemedlemskap/Numrering inom serie (seriesMembership/seriesEnumeration = 800 #v)  
  Skriv in uppgiften.  
  ```Exempel: 1```  
  
#### Anmarkning
* Anmärkning/Anmärkning/Benämning (hasNote/Note/label = 500 #a)

#### Digital karaktaristika
* Digital karaktärisitika/Kodningsformat/Benämning</br> 
(digitalCharacteristic/EncodingFormat/label = 347 #b)</BR>
  Ange kodningsformat här, se [RDA 3.19.3.3](http://access.rdatoolkit.org/rdachp3_rda3-5264.html). 
  Skriv in uppgiften under Benämning.</BR>
  ```Exempel: PDF```

#### Annat bararformat
* Annat bärarformat (otherPhysicalFormat = 776)  
  För att länka till en utgåva i annat format, till exempel en tryckt utgåva, lägg till Annat bärarformat (Lägg till egenskaper, välj   Annat bärarformat). Sök upp och länka till instansen. Klicka på plustecknet vid Annat bärarformat (Lägg till instans). I sidorutan under Lägg till entitet/Instans, skriv in id eller annat sökbegrepp. Välj instansen genom att klicka på plustecknet vid instansen eller på instansens titel. Om instansen som länken går till har identifikator (ISBN), skapas i marcexporten 776 #t (Titel) och #z (Identifikator). I webbsök ger detta en länk i högermenyn under rubriken Sök vidare/Andra versioner.   
* Annat bärarformat/Typanmärkning (776 #i)  
  Typanmärkning i samband med Annat bärarformat kan för närvarande inte läggas till.  
* Annat bärarformat/Beskriven av/Post/Kontrollnummer (776 #w)  
  Beskriven av/Post/Kontrollnummer, motsvarande delfält w, är för närvarande låst för redigering. Det går därmed inte att lägga till egenskapen eller redigera den i befintliga beskrivningar.  
  
#### Elektronisk adress
Använd egenskapen Elektronisk adress endast när ingen uppgift finns om vilken version länken går till (används normalt inte).

##### Tillhörande media
* Tillhörande media/Mediaobjekt/URI (associatedMedia/Mediaobject/uri = 856 4/0 #u)</br>
Använd Tillhörande media för att lägga in en elektronisk adress till den besrivna resursen. Lägg till Mediaobjekt under Tillhörande media. Välj Skapa lokal entitet. Lägg till egenskapen URI. Klistra in aktuell URI.
* Tillhörande media/Mediaobjekt/Offentlig anmärkning (associatedMedia/Mediaobject/marc:publicNote = 856 4/0 #z)</br>
Vid behov, lägg till Offentlig anmärkning. Skriv in anmärkningen.
* Del av materialet som avses/Resurs/Benämning (appliesTo/Resource/label = 856 4/0 #3)</br>
Vid behov, lägg till Del av material som avses under Mediaobjekt och skapa Resurs som lokal entitet. Lägg till Benämning.

#### Malgruppsanmarkning  
* Målgrupp/Målgrupp/Benämning (intendedAudience/IntendedAudience/label = 521 #a)  
Observera att kodning av målgrupp, motsvarande 008/22, ska registreras under Instans av Verk/Genre.  

### Verk
För att lägga till egenskaper under Instans av verk, klicka på plustecknet till höger om Instans av verk och verkstypen. Sök fram egenskapen och välj den genom att klicka på plustecknet vid egenskapens namn.  

Läs mer om egenskaperna under [Verk](https://libris.kb.se/katalogisering/help/workflow-work).  

#### Instans av verk
* Instans av verk/Text (instanceOf/Work/Text)  
För en e-bok är verkstypen Text.  

#### Verkets titel
Ange den föredragna titeln för verket här, vid behov. Följ anvisningarna under [Konstruera sökingångar för verk och uttryck](http://www.kb.se/rdakatalogisering/Anvisningar/Allmanna-anvisningar/Sokingangar-for-verk-och-uttryck/) i Anvisningar för katalogisering - RDA. Föredragen titel ska anges för översättningar och för verk som har givits ut under olika titlar på samma språk. En föredragen titel ska också anges om olika verk har samma auktoriserade sökingång. 

##### Verk med Primär medverkan
* Har titel/Titel/Huvudtitel (hasTitle/Title/mainTitle = 240 1/0 #a)  
 Föredragen titel för ett verk med primär medverkan anges här.  

##### Verk utan Primär medverkan
*	Uttryck av/Verk/Har titel/Titel/Huvudtitel (expressionOf/Work/hasTitle/Title/mainTitle = 130 #a)</br>
 Föredragen titel för ett verk utan primär medverkan anges här.
 
#### Medverkan och funktion
Följ dessa instruktioner: [Relationer till Agent](https://libris.kb.se/katalogisering/help/workflow-agent-org-instance) 

##### Primär medverkan  
* Medverkan och funktion/Primär medverkan/Agent/Person  
(contribution/PrimaryContribution/agent/Person = 100 1/- #a)
* Medverkan och funktion/Primär medverkan/Agent/Organisation (110 2/-)
* Medverkan och funktion/Primär medverkan/Agent/Jurisdiktion (110 1/-)
* Medverkan och funktion/Primär medverkan/Funktion  
(contribution/PrimaryContribution/role = 100, 110 #4)

##### Medverkan
* Medverkan och funktion/Medverkan/Agent/Person  
(contribution/agent/Person = 700 1/- #a)
* Medverkan och funktion/Medverkan/Agent/Organisation (710 2/-)
* Medverkan och funktion/Medverkan/Agent/Jurisdiktion (710 1/-)
* Medverkan och funktion/Medverkan/Funktion  
(contribution/PrimaryContribution/role = 700, 710 #4)

#### Sprak 
* Språk (language = 008/35-37)</br>
Ange textens språk här. För en text på svenska, länka till svenska. För att ange originalspråk för ett översatt verk, se Originalversion/Verk/Språk.  

##### Översättning 
* Anmärkning: Språk (marc:LanguageNote = 041 i1: 1)  
  Ange om resursen är/innehåller en översättning. För att lägga till uppgiften, klicka på plustecknet vid Instans av verk och välj Anmärkning: Språk. Välj fras från lista.</br> 
  ```Exempel: objektet är/innehåller översättning```   
* Originalversion/Verk/Språk (originalversion/Work/language = 041 ‡h)  
  Ange det språk som en texten är översatt från. För en text som är översatt från engelska till svenska, ange engelska här. Klicka på plustecknet vid Instans av verk, välj Originalversion, klicka på plustecknet vid Originalversion, välj Skapa lokal entitet. Skriv Verk i rutan för Skapa lokal entitet och välj * Verk. Lägg till Språk under verk. Sök fram språkentiteten och länka.  
  ```Exempel: engelska (eng)```  
För översättningar i flera led, länka först till det mellanliggande språket och därefter till originalspråket.  

För en översättning ska språket också läggas till i klartext i marcpostens delfält #l, som ett tillägg till verkets titel.  
**Från och med version 1.7 skapas språktillägget automatiskt i 240 #l.** 

Om översättningen saknar Primär medverkan, ange språket som ska visas i klartext här:  
Uttryck av/Verk/Språk (Language/label = 130 #l)  
Länka till entitet. 

##### Sammanfattningsspråk
Se [Sammanfattning av innehåll](#sammanfattning-av-innehall).

#### Språkanmärkning     
* Anmärkning/Anmärkning om språk/Anmärkning: Språk/Benämning  
(hasNote/marc:LanguageNote/marc:LanguageNote/label = 546 #a)  
Anmärkningen finns i mallen E-bok och kan läggas till med hjälp av Berikning från mall. Det går ännu inte att lägga till egenskapen från Lägg till egenskaper.

#### Relationer till ingaende verk och andra verk

##### Relationer till ingående verk 
* Ingående verk med primär medverkan (700 1/2 #a, ǂd, ǂt)  
  Se [Relationer till delar och verk](https://libris.kb.se/katalogisering/help/workflow-agent-relation).  

* Ingående verk utan primär medverkan (730 0/2 #a)</br> 
  Har del/Verk/Har titel/Titel  
  Om det ingående verket är en översättning, lägg till Språk/Språk/Benämning under Verk.

##### Relationer till andra verk  
  * Relationer till andra verk med primär medverkan (700 1/- #a, ǂd, ǂt)  
  Se [Relationer till delar och verk](https://libris.kb.se/katalogisering/help/workflow-agent-relation).

*  Relationer till andra verk utan primär medverkan  
   Relation/Relation/Entitet/Entitet/Verk/Har titel/Titel (730 0/_)  
   Om det ingående verket är en översättning, lägg till Språk/Språk/Benämning under Verk.

#### Genre
* Genre/form – saogf-termer (genreForm = 655 -/7 #a, #2 saogf)  
 Välj Genre/form i listan över typer.  
 
* Genre/form – termer som motsvarar marc-koder i 008  
Välj någon av övriga rubriker i listan.

##### Biografiskt material  
* Genre/form – biografiskt material (genreForm = 008/34)  
  Välj Biografiskt material i listan över typer. Länka till entitet.  
  ```Exempel: a (= självbiografi)```  
  
##### Festskrift     
* Genre/form – festskrift (genreForm = 008/30)  
  Välj Festskrift i listan över typer. Länka till entitet.    
  ```Exempel: Ja, resursen är en festskrift```    
  
##### Litterär genre  
* Genre/form – litterär genre (genreForm = 008/33)  
  Välj Litterär genre i listan över typer. Länka till entitet.  
  ```Exempel: f (= roman)```
   
##### Konferenspublikation       
* Genre/form – konferenspublikation (genreForm = 008/29)  
  Välj Konferenspublikation i listan över typer. Länka till entitet.         
  ```Exempel: Ja, resursen härrör från konferens```   
     
##### Akademisk avhandling      
* Genre/form – akademisk avhandling (genreForm = 008/24-27)  
  Välj Innehåll, i listan över typer. Skriv "avhandling" i sökrutan. Länka till entitet.      
  ```Exempel: Akademisk avhandling```  
  Se även [Anmärkning om akademisk avhandling](#anmarkning-om-akademisk-avhandling).  

###### Exempel på användning av Genre/form
Under Genre/form, ange dels saogf-termer (genre/form-termer enligt Svenska ämnesord), dels termer som motsvarar marc-koder i 008.  
För att länka till saogf-termer, välj Genre/form i listan (det första alternativet under Alla).  
För att länka till termer som motsvarar marc-koder i 008, se övriga rubriker. De vanligaste finns under rubriken Föreslagna.  

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
Se även [Svenska ämnesords översikt över Allmänna genreform-termer](http://www.kb.se/katalogisering/Svenska-amnesord/genrer-form/Allmanna-genreformtermer/).  
Litterär genre (008/33): Ej skönlitterärt verk  

**Festskrift**  
Genre/form (saogf-term, 655): Festskrifter  
Festskrift (008/30): Ja, resursen är en festskrift  
Litterär genre (008/33): Ej skönlitterärt verk  

**Akademisk avhandling**  
Genre/form (saogf-term, 655): Avhandlingar  
Innehåll (008/24-27): Avhandling

#### Klassifikation  
* Klassifikation/DDK-klassifikation/Kod  
(classification/ClassificationDdc/code = 082 0/4 #a)

* Klassifikation/DDK-klassifikation/Klassifikationsupplaga  
(classification/ClassificationDdc/edition = 082 i1)

* Parallell upplagebeteckning/Upplagespecifik upphovsuppgift  
(classification/ClassificationDdc/editionEnumeration = 082 #2)

##### Sekundär DDK-klassifikation 
* DDK-klassifikation (sekundär)/Klassifikation/DDK-klassifikation/Kod   
(additionalClassificationDdc/ClassificationDdc/code = 083 0/- #a)

* Klassifikation/DDK-klassifikation/Klassifikationsupplaga  
(classification/ClassificationDdc/edition = 083 i1)

* Parallell upplagebeteckning/Upplagespecifik upphovsuppgift  
(classification/ClassificationDdc/editionEnumeration = 083 #2)

##### SAB-klassifikation  
* Klassifikation/Klassifikation/Kod  
(classification/Classification/code = 084 0/4 #a)

* Klassifikation/Termlista/Termlista/Kod  
(classification/Classification/inScheme/ConceptScheme/code = 084 #2)

* Klassifikation/Termlista/Termlista/Version  
(classification/Classification/inScheme/ConceptScheme/version = 084 #2)

#### Amne  
* [Ämne](https://libris.kb.se/katalogisering/help/workflow-general-sh)  

#### Malgrupp     
* Målgrupp (008/22)
<br/>```Exempel:```
  * ```Barn och ungdom (0-16 år) (008/22: j)```  
  Normalvärde för barn- och ungdomslitteratur.
  
  * ```Barn (ca 10-12 år)/Läromedel (008/22: c)```  
  Normalvärde för läromedel avsedda för skolbruk (till och med gymnasiet).  

 Målgruppsanmärkning (Målgrupp/Målgrupp/Benämning), se Instans.  

#### Innehallstyp
* Innehållstyp/Innehållstyp (contentType/ContentType = 336 #b)   
```Exempel: text (txt)```

  För att lägga till ytterligare innehållstyp, till exempel "sti" = stillbild för en bilderbok med både text och bild, länka till ytterligare en entitet.
  I äldre poster har ytterligare innehållstyp lagts i Har del/Verk. Dessa behöver inte ändras.

#### Sammanfattning av innehall
* Sammanfattning av innehåll/Sammanfattning/Benämning (summary/Summary/label = 520 #a)</br>
Lägg till Sammanfattning av innehåll. Välj Sammanfattning av innehåll. Lägg till Sammanfattning.
Skriv in uppgiften under Benämning.</br>
```Exempel: Åtskilliga utdrag af framledne … Axel v. Fersens bref till f.d. konungen av Swerige, Gustaf Adolph, 1806```

* Typ av sammanfattning/typ av innehållsbeskrivning (marc:summaryType = 520 ind1)</br>
Sök fram och lägg till Typ av sammanfattning. Välj typ från lista.</br>
```Exempel: Ej preciserad```

##### Sammanfattningsspråk
* Sammanfattning av innehåll/Sammanfattning/Språk (summary/Summary/language = 041 #b)</br>
Lägg till sammanfattningsspråk. Lägg till Sammanfattning. Ta bort Benämning. Länka till entiteten för sammanfattningens språk.<br>
```Exempel: Engelska```
  
#### Anmarkning om akademisk avhandling    
* Anmärkning om akademisk avhandling/Anmärkning om akademisk avhandling/Benämning (dissertation/Dissertation/label = 502 #a)</br>
Lägg till Anmärkning om akademisk avhandling. Skapa lokal entitet.
Skriv in anmärkningen under Benämning.
```Exempel: Diss. Umeå : Umeå universitet, 2018```
