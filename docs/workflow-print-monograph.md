---
section: Materialtyper
title: Tryckt monografi
order: 54
date: 2020-06-22
tags:
- monografi
--- 

# Tryckt monografi
Denna hjälptext ger kortfattade instruktioner för de vanligaste egenskaperna för en tryckt monografi - bok. För utförliga instruktioner, se de generella hjälptexterna för Adminmetadata, Instans och Verk, se nedan.  

[Inledning](#inledning) 


| [Adminmetadata](#adminmetadata) | [Instans](#instans) | [Verk](#verk) | 
| ----------- |  ----------- | ----------- |
|  [Generell hjälptext för Adminmetadata](https://libris.kb.se/katalogisering/help/workflow-adminmetadata) | [Generell hjälptext för Instans](https://libris.kb.se/katalogisering/help/workflow-instance) | [Generell hjälptext för Verk](https://libris.kb.se/katalogisering/help/workflow-work) |
| | [Utgivningssätt](#utgivningssatt) | [Verkets titel](#verkets-titel) |
| | [Medietyp](#medietyp) | [Medverkan och funktion](#medverkan-och-funktion) |
| | [Bärartyp](#barartyp) | [Relationer till ingående verk och andra verk](#relationer-till-ingaende-verk-och-andra-verk) |
| | [Titel](#titel) | [Språk](#sprak) |
| | [Upphovsuppgift](#upphovsuppgift) | [Genre/form](#genre-form) | 
| | [Upplageuppgift](#upplageuppgift) | [Klassifikation](#klassifikation) |
| | [Utgivning](#utgivning) | [Ämne](https://libris.kb.se/katalogisering/help/workflow-general-sh) |
| | [Tillverkning](#tillverkning) | [Målgrupp](#malgrupp) | 
| | [Copyrightår](#copyrightar) | [Innehållstyp](#innehallstyp) | 
|  | [Identifikator](#identifikator) | [Sammanfattning av innehåll](#sammanfattning-av-innehall) |
| | [Omfång](#omfang) | [Anmärkning om akademisk avhandling](#anmarkning-om-akademisk-avhandling) |
| | [Övriga fysiska detaljer](#ovriga-fysiska-detaljer) | |
| | [Mått](#matt) | |
| | [Medföljande material](#medfoljande-material) | |
| | [Seriemedlemskap](#seriemedlemskap) | |
| | [Anmärkning](#anmarkning) | | 
| | [Innehållsförteckning](#innehallsforteckning) | |
| | [Målgruppsanmärkning](#malgruppsanmarkning) | |
| | [Annat bärarformat](#annat-bararformat) | |

## Inledning
Beskrivningen av en tryckt monografi innehåller följande tre delar:  
* [Adminmetadata](https://libris.kb.se/katalogisering/help/workflow-adminmetadata) - administrativa data om instansbeskrivningen, såsom kontrollnummer och beskrivningsnivå
* [Instans](https://libris.kb.se/katalogisering/help/workflow-instance) - instans kan också kallas utgåva eller manifestation. Exempel på egenskaper under Instans är utgivningsplats, utgivare och utgivningsår, bärartyp, omfång.
* [Verk](https://libris.kb.se/katalogisering/help/workflow-work) – återger egenskaper för det abstrakta verket såsom medverkan och funktion (t.ex. författare), ämne, klassifikation, språk och innehållstyp. Verksbeskrivningen ligger under rubriken Instans av verk.

Många av egenskaperna finns redan i mallen Tryckt monografi (Bok), andra kan behöva läggas till. För instruktioner om att lägga till eller ta bort egenskaper, länka till entitet, skapa lokal entitet och om hur formuläret fungerar i övrigt, se Redigering i vänstermenyn. För en förhandspost, använd gärna Berika från mall och välj Bok.  

För information om katalogregler, skrivregler och övriga katalogiseringsanvisningar, [se Anvisningar för katalogisering - RDA](http://www.kb.se/rdakatalogisering/Anvisningar/Arbetsfloden/Tryckta-monografier/ "Anvisningar för katalogisering - RDA") och [RDA Toolkit](https://access.rdatoolkit.org/).

[Se även instruktionsfilmer på KB:s Youtubekanal](https://www.youtube.com/playlist?list=PLZVkEICvA5-GRT2oJQmLgq_2Pksx6zYPy).   

## Adminmetadata
[Använd generell hjälptext för Adminmetadata](https://libris.kb.se/katalogisering/help/workflow-adminmetadata).

* Kontrollera beskrivningsnivån. I mallen är standardvärdet Biblioteksnivå (normalvärde för Librisbiblioteken). Ändra vid behov.
**Observera: Om nivån är CIP-post eller preliminär post, ändra till annan nivå, annars kan ändringar skrivas över!** 


## Instans
För att lägga till egenskaper under Instans, klicka på plustecknet i redigeringsvyn (den stora runda plusikonen under Verktygsikonen) - Lägg till egenskaper under: Instans.  
![Lägg till egenskap under: Instans](plusegenskapinstans.png)  

Sök fram egenskapen och välj den genom att klicka på plustecknet vid egenskapens namn eller på egenskapens namn.    
![Välj egenskap](plusegenskapinstans2.png)  

[Läs mer om egenskaperna i den generella hjälptexten för Instans](https://libris.kb.se/katalogisering/help/workflow-instance).  

### Utgivningssatt 
* Utgivningssätt (issuanceType)   
  Välj från lista.  
  ```Exempel: Monografisk resurs```
  
### Medietyp
* Medietyp (mediaType/Mediatype = 337 #b)  
  Länka till entitet.  
  ```Exempel: n (= omedierad)```
  
### Barartyp 
* Bärartyp (carrierType/CarrierType = 338 #b)  
  Länka till entitet.  
  ```Exempel: nc (= volym)```
  
### Titel
* Har titel/Titel/Huvudtitel (hasTitle/Title/mainTitle = 245 #a)
* Har titel/Titel/Övrig titelinformation (hasTitle/Title/subtitle = 245 #b)

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

#### Titel - alternativ stavning
* Relation/Relation/Entitet/Verk/Har titel/Titel/Huvudtitel  
(relationship/Relationship/entity/Work/hasTitle/Title/mainTitle = 740)  
Används inte. Se Varianttitel (246).  

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
  
### Tillverkning 

#### Tillverkningsplats (Tillverkningsort) 
* Tillverkning/Plats/Plats/Benämning (place/label = 264 -/3 #a)  

#### Tillverkningsnamn  
* Tillverkning/Agent/Agent/Benämning (agent/label = 264 -/3 #b)  

### Copyrightar   
* Copyright/Copyright/Datum (copyright/Copyright/date = 264 -/4 #c)  

### Identifikator 
* Identifikator/ISBN/Värde (identifiedBy/Isbn/value = 020 #a)  
* Identifikator/Särskiljande tillägg  (identifiedBy/qualifier = 020 #q)  
Notera att felaktigt eller ogiltigt ISBN ska anges under Indirekt identifierad av. Använd inte Ogiltigt värde.  

### Indirekt identifierad av  
Felaktigt eller ogiltigt ISBN ska anges här. Använd inte Ogiltigt värde under Identifikator/ISBN.  

* Indirekt identifierad av/ISBN/Värde (indirectlyIdentifiedBy/Isbn/value = 020 #z)
* Indirekt identifierad av/Särskiljande tillägg (= Bestämning) (indirectlyIdentifiedBy/qualifier = 020 #q)

### Omfang   
* Omfång/Omfång/Benämning (extent/Extent/label = 300 #a)

### Ovriga fysiska detaljer   
* Övriga fysiska detaljer (other physical details = 300 #b)
 
### Matt 
* Mått/Mått/Benämning (hasDimensions/Dimensions/label = 300 #c)

### Medfoljande material
* Medföljs av/Instans/Instanstyp/Benämning (accompaniedBy/Instance/type/label = 300 #e)  
Här anges medföljande material, som t ex bilagor.  

### Seriemedlemskap
* Seriemedlemskap/Seriemedlemskap/Ingår i serie  

#### Seriens titel (auktoriserad sökingång för serie)  
* Seriemedlemskap/Ingår i serie/Instans/Instans av Verk/Verk/Verkstyp/Har titel/Titel/Huvudtitel  
 (seriesMembership/inSeries/InstanceofWork/Work/type: Work/hasTitle/Title/mainTitle = 830 #a)  

#### ISSN  
* Seriemedlemskap/Ingår i serie/Instans/Instanstyp/Identifikator/ISSN/Värde  
 (seriesMembership/inSeries/Instance/identifiedBy/ISSN/Value) (490 #x, 830 #x)
Felaktiga ISSN i en instans ska återges under [Anmärkning](#anmarkning). [Se Anvisningar för katalogisering (RDA), Series ISSN](http://www.kb.se/rdakatalogisering/Anvisningar/Arbetsfloden/Tryckta-monografier/#series_issn).  

#### Serieuppgift  
* Seriemedlemskap/Serieuppgift (seriesMembership/seriesStatement = 490 #a)

#### Numrering inom serie  
* Seriemedlemskap/Numrering inom serie (seriesMembership/seriesEnumeration = 490 #v, 830 #v)

#### Indikator för seriebiuppslag   
* Seriemedlemskap/Indikator för seriebiuppslag (marc:seriesTracingPolicy = 490 i1: 0/1)

#### Författarserie
* Seriemedlemskap/Ingår i serie/Instans/Instanstyp/Instans av Verk/Verk/Verkstyp/Har titel/Titel/Huvudtitel  
(seriesMembership/inSeries/Instance/type/InstanceOf/Work/type/hasTitle/Title/mainTitle = 800 #t)  
  ```Exempel: Millenium```   
  Man behöver inte välja verks- och instanstyp här.  
* Seriemedlemskap/Ingår i serie/Instans/Instanstyp/Instans av Verk/Verk/Verkstyp/Medverkan och funktion/Primär medverkan/Agent/Person     (seriesMembership/inSeries/Instance/type/InstanceOf/Work/type/contribution/PrimaryContribution/Agent/Person = 800 #a)  
Lägg till Medverkan och funktion under Verk (inom Seriemedlemskap) genom att klicka på plustecknet vid Verk (Lägg till egenskaper under: Verk). Välj Medverkan och funktion. Välj Primär medverkan. Lägg till Agent.   
[Följ instruktioner i hjälptexten Relationer till Agent](https://libris.kb.se/katalogisering/help/workflow-agent-org-instance)  
 ```Exempel: Larsson, Stieg, 1954-2004```  
  Vid behov, skapa ny agent, [se hjälptexten Skapa ny agent](https://libris.kb.se/katalogisering/help/workflow-agent-person-new). I undantagsfall, skapa lokal entitet.   
  
#### Numrering inom serie   
* Seriemedlemskap/Numrering inom serie (seriesMembership/seriesEnumeration = 800 #v)  
  Skriv in uppgiften.  
  ```Exempel: 1```  
  
### Anmarkning
* Anmärkning/Anmärkning/Benämning (hasNote/Note/label = 500 #a)

### Innehallsforteckning
* Har innehållsförteckning/Innehållsförteckning/Benämning (tableofContents = 505 8/_)  
 
* Har innehållsförteckning/Innehållsförteckning/Har del/Utökad innehållsanmärkning/Benämning/Upphovsuppgift  
(tableofContents = 505 8/0 #t, #r)  

### Malgruppsanmarkning  
* Målgrupp/Målgrupp/Benämning (intendedAudience/IntendedAudience/label = 521 #a)  
Observera att kodning av målgrupp, motsvarande 008/22, ska registreras under Instans av Verk/Genre.  

### Annat bararformat
* Annat bärarformat (otherPhysicalFormat = 776)  
Länka till instans.


## Verk
För att lägga till egenskaper under Instans av verk, klicka på plustecknet till höger om Instans av verk och verkstypen.  
![Instans av verk](instansavverk.png)  

Sök fram egenskapen och välj den genom att klicka på plustecknet vid egenskapens namn.  

![Instans av verk egenskap](instansavverkegenskap.png)  

[Läs mer om egenskaperna under den generella beskrivningen av Verk](https://libris.kb.se/katalogisering/help/workflow-work).  

## Instans av verk
* Instans av verk/Text (instanceOf/Work/Text)  
För en tryckt monografi är verkstypen Text.  

### Verkets titel
Ange den föredragna titeln för verket här, vid behov. [Följ Anvisningar för katalogisering - RDA](http://www.kb.se/rdakatalogisering/Anvisningar/Allmanna-anvisningar/Sokingangar-for-verk-och-uttryck "Anvisningar för katalogisering - RDA").  
Ange föredragen titel för översättningar, för verk som har givits ut under olika titlar på samma språk eller när samma titel har använts för olika verk.   

#### Verk med Primär medverkan
* Har titel/Titel/Huvudtitel (hasTitle/Title/mainTitle = 240 1/0 #a)  
 "Originaltitel" för ett verk med Medverkan och funktion/Primär medverkan anges här.  

#### Verk utan Primär medverkan
*	Uttryck av/Verk/Har titel/Titel/Huvudtitel (expressionOf/Work/hasTitle/Title/mainTitle = 130 #a)
 "Originaltitel" för ett verk utan Medverkan och funktion/Primär medverkan anges här.
 
### Relationer till ingaende verk och andra verk

#### Relationer till ingående verk 
* Ingående verk med Primär medverkan (700 1/2 #a, ǂd, ǂt)  
  [Se hjälptexten Relationer till delar och verk](https://libris.kb.se/katalogisering/help/workflow-agent-relation).  

* Ingående verk utan Medverkan och funktion/Primär medverkan 
  Har del/Verk/Har titel/Titel (730 0/2 #a)  
  Om det ingående verket är en översättning, lägg till Språk/Språk/Benämning under Verk.

#### Relationer till andra verk  
  * Relationer till andra verk med Primär medverkan (700 1/- #a, ǂd, ǂt)  
  [Se hjälptexten Relationer till delar och verk](https://libris.kb.se/katalogisering/help/workflow-agent-relation).

*  Relationer till andra verk utan Medverkan och funktion/Primär medverkan  
   Relation/Relation/Entitet/Entitet/Verk/Har titel/Titel (730 0/_)  
   Om det ingående verket är en översättning, lägg till Språk/Språk/Benämning under Verk.

### Medverkan och funktion
[Följ instruktioner i hjälptexten Relationer till Agent](https://libris.kb.se/katalogisering/help/workflow-agent-org-instance)  
  
* Medverkan och funktion/Primär medverkan/Agent/Person  
(contribution/PrimaryContribution/agent/Person = 100 1/- #a)

* Medverkan och funktion/Primär medverkan/Funktion  
(contribution/PrimaryContribution/role = 100 #4)

* Medverkan och funktion/Medverkan/Agent/Person  
(contribution/agent/Person = 700 1/- #a)

* Medverkan och funktion/Medverkan/Agent/Organisation (710 2/-)

* Medverkan och funktion/Medverkan/Agent/Jurisdiktion (710 1/-)

### Sprak 
* Språk (language = 008/35-37)  
  Ange textens språk. För en text på svenska, länka till svenska.   
  Länka till entitet.  
  ```Exempel: svenska (swe)```   
  För att ange att texten är på flera språk, länka till ytterligare en språkkod.  
  För att ange originalspråk för ett översatt verk, se Översättning, nedan. 
  
#### Översättning   
* Anmärkning: Språk (marc:LanguageNote = 041 i1: 1)  
  Ange om resursen är/innehåller en översättning.  Välj fras från listan.  
  
* Originalversion/Verk/Språk (originalversion/Work/language = 041 #h)  
  Ange originalspråk för ett översatt verk här.   
Lägg till Originalversion under Instans av verk, skapa Verk som lokal entitet. Du behöver inte välja verkstyp här. Lägg till Språk och länka till entitet.  
 För översättningar i flera led, länka först till det mellanliggande språket och därefter till originalspråket.  

För en översättning ska översättningens språk också läggas till i klartext i marcpostens delfält #l, som ett tillägg till verkets titel.  

Om översättningen är ett verk som har Primär medverkan, ska språket läggas till i 240 #l.  
**Från och med version 1.7 skapas språktillägget automatiskt, för 240 #l.**   

Om översättningen är ett anonymt verk, det vill säga saknar Primär medverkan, ange språket som ska visas i klartext här:  
Uttryck av/Verk/Språk (Language/label = 130 #l)  
Länka till entitet.  
Om översättningen är ett ingående verk, ange språket som ska visas i klartext här:  
Har del/Verk/Språk (Language/label = 730 #l)  
Länka till entitet.  
  
#### Sammanfattningsspråk  
Se Sammanfattning av innehåll   

#### Språkanmärkning     
* Anmärkning/Anmärkning om språk/Anmärkning: Språk/Benämning  
(hasNote/marc:LanguageNote/marc:LanguageNote/label = 546 #a)  
Anmärkningen finns i mallen Tryckt monografi och kan läggas till med hjälp av Berikning från mall. Det går ännu inte att lägga till egenskapen från Lägg till egenskaper.

### Genre form
* Genre/form – saogf-termer (genreForm = 655 -/7 #a, #2 saogf)  
 Välj Genre/form i listan över typer.  
 
* Genre/form – termer som motsvarar marc-koder i 008  
Välj någon av övriga rubriker i listan.

#### Biografiskt material  
* Genre/form – biografiskt material (genreForm = 008/34)  
  Välj Biografiskt material i listan över typer. Länka till entitet.  
  ```Exempel: a (= självbiografi)```  
  
#### Festskrift     
* Genre/form – festskrift (genreForm = 008/30)  
  Välj Festskrift i listan över typer. Länka till entitet.    
  ```Exempel: Ja, resursen är en festskrift```    
  
#### Litterär genre  
* Genre/form – litterär genre (genreForm = 008/33)  
  Välj Litterär genre i listan över typer. Länka till entitet.  
  ```Exempel: f ( = roman)```
   
#### Konferenspublikation       
* Genre/form – konferenspublikation (genreForm = 008/29)  
  Välj Konferenspublikation i listan över typer. Länka till entitet.         
  ```Exempel: Ja, resursen härrör från konferens```   
     
#### Akademisk avhandling      
* Genre/form – akademisk avhandling (genreForm = 008/24-27)  
  Välj Innehåll, i listan över typer. Skriv "avhandling" i sökrutan. Länka till entitet.      
  ```Exempel: Akademisk avhandling```  
  [Se även Anmärkning om akademisk avhandling](#anmarkning-om-akademisk-avhandling).  

#### Exempel på användning av Genre/form
Under Genre/form, ange dels saogf-termer (genre/form-termer enligt Svenska ämnesord), dels termer som motsvarar marc-koder i 008.  
För att länka till saogf-termer, välj Genre/form i listan (det första alternativet under Alla).  
För att länka till termer som motsvarar marc-koder i 008, se övriga rubriker. De vanligaste finns under rubriken Föreslagna.  
![Exempel lägg till genre/form](genre_exempel.png)  

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
[Se även Svenska ämnesords översikt över Allmänna genre/formtermer](http://www.kb.se/katalogisering/Svenska-amnesord/genrer-form/Allmanna-genreformtermer/).  
Litterär genre (008/33): Ej skönlitterärt verk  

**Festskrift**  
Genre/form (saogf-term, 655): Festskrifter  
Festskrift (008/30): Ja, resursen är en festskrift  
Litterär genre (008/33): Ej skönlitterärt verk  

**Akademisk avhandling**  
Genre/form (saogf-term, 655): Avhandlingar  
Innehåll (008/24-27): Avhandling

### Klassifikation  
* Klassifikation/DDK-klassifikation/Kod  
(classification/ClassificationDdc/code = 082 0/4 #a)

* Klassifikation/DDK-klassifikation/Klassifikationsupplaga  
(classification/ClassificationDdc/edition = 082 i1)

* Parallell upplagebeteckning/Upplagespecifik upphovsuppgift  
(classification/ClassificationDdc/editionEnumeration = 082 #2)

#### Sekundär DDK-klassifikation 
* DDK-klassifikation (sekundär)/Klassifikation/DDK-klassifikation/Kod   
(additionalClassificationDdc/ClassificationDdc/code = 083 0/- #a)

* Klassifikation/DDK-klassifikation/Klassifikationsupplaga  
(classification/ClassificationDdc/edition = 083 i1)

* Parallell upplagebeteckning/Upplagespecifik upphovsuppgift  
(classification/ClassificationDdc/editionEnumeration = 083 #2)

#### SAB-klassifikation  
* Klassifikation/Klassifikation/Kod  
(classification/Classification/code = 084 0/4 #a)

* Klassifikation/Ingår i system/Konceptsystem/Kod  
(classification/Classification/inScheme/ConceptScheme/code = 084 #2)

* Klassifikation/Ingår i system/Konceptsystem/Version  
(classification/Classification/inScheme/ConceptScheme/version = 084 #2)

### Amne  
* [Se hjälptexten Ämnesord i Libris](https://libris.kb.se/katalogisering/help/workflow-general-sh).  

### Malgrupp     
* Målgrupp (008/22)
<br/>```Exempel:```
  * ```Barn och ungdom (0-16 år) (008/22: j)```  
  Normalvärde för barn- och ungdomslitteratur.
  
  * ```Barn (ca 10-12 år)/Läromedel (008/22: c)```  
  Normalvärde för läromedel avsedda för skolbruk (till och med gymnasiet).  

 Målgruppsanmärkning (Målgrupp/Målgrupp/Benämning), se Instans.  

### Innehallstyp
* Innehållstyp/Innehållstyp (contentType/ContentType = 336 #b)   
```Exempel: text (txt)```

  För att lägga till ytterligare innehållstyp, till exempel "sti" = stillbild för en bilderbok med både text och bild, länka till ytterligare en entitet.   
I äldre poster har ytterligare innehållstyp lagts i Har del/Verk. Dessa behöver inte ändras.

### Sammanfattning av innehall  
* Sammanfattning av innehåll/Sammanfattning/Benämning (summary/Summary/label = 520 #a)

#### Sammanfattningsspråk  
* Sammanfattning av innehåll/Sammanfattning/Språk (summary/Summary/language = 041 #b)    

### Anmarkning om akademisk avhandling    
* Anmärkning/Anmärkning om akademisk avhandling/Benämning  
(dissertation/Dissertation/label = 502 #a)
