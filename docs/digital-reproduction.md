---
section: Materialtyper
title: Digital reproduktion
order: 39
date: 2021-06-16
tags:
- digital reproduktion
- digitalisering
---

# Digital reproduktion
Denna hjälptext ger kortfattade instruktioner för de vanligaste egenskaperna vid beskrivning av en digital reproduktion av ett fysiskt original, t.ex. monografi, bild, karta, äldre tryck. Det finns en mall för Digital reproduktion då alla värden behöver anges manuellt. För att dra maximal nytta av funktionaliteten är rekommendationen att man använder funktionen Skapa digital reproduktion i verktygsmenyn i posten för ett fysiskt original som används som utgångspunkt. Då genereras en ny post för den digitala reproduktionen med förvalda värden där endast en del behöver kompletteras manuellt. Mallen är skapad för tryckt text så för andra typer av fysiska original behöver justeringar göras av de förvalda värdena.

I de fall egenskaperna finns beskrivna i generell hjälptext upprepas inte informationen här utan istället finns en länk till relevant hjälptext. Egenskaper som är specifika för digital reproduktion redovisas däremot enbart här.

## Innehåll   

[Inledning](#inledning)

| [Adminmetadata](#adminmetadata) | [Instans](#instans) | [Verk](#verk) | [Bestånd](#bestånd)
| ----------- | ----------- |  ----------- | ----------- |
| [Adminmetadata - Metadatabyrån](https://metadatabyran.kb.se/beskrivning/specialanvisningar/adminmetadata-i-libris) | [Generell hjälptext för Instans](https://libris.kb.se/katalogisering/help/workflow-instance) | [Generell hjälptext för Verk](https://libris.kb.se/katalogisering/help/workflow-work) | [Generell hjälptext för Bestånd](https://libris.kb.se/katalogisering/help/workflow-holding)
| [Bibliografi](#bibliografi) | [Instanstyp](#instanstyp) | | [Innehas av](#innehas-av) |
| [Beskrivningsnivå](#beskrivningsnivå)| [Reproduktion av](#reproduktion-av) | | [Anmärkning](#anmärkning) |
| [Anmärkning](#anmärkning) | [Identifikator](#identifikator) | | [Katalogisatörens anmärkning](#katalogisatörens-anmärkning)|
| | [Utgivningssätt](#utgivningssätt) | | |
| | [Medietyp](#medietyp) | | |
| | [Bärartyp](#bärartyp) | | |
| | [Produktion](#produktion) | | |
| | [Indirekt identifierad av](#indirekt-identifierad-av) | | |
| | [Digital karakteristika](#digital-karakteristika) | | |
| | [Tillhörande media](#tillhörande-media) | | |
| | [Villkor för användning och åtkomst](#villkor-för-användning-och-åtkomst) | | |
| | [Relaterad beskrivning eller innehåll](#relaterad-beskrivning-eller-innehåll) | | |
| | [Anmärkning](#anmärkning)| |



## Inledning
Beskrivningen av en digital reproduktion innehåller följande tre delar:  
* [Adminmetadata](https://libris.kb.se/katalogisering/help/workflow-adminmetadata) - administrativa data om instansbeskrivningen, såsom kontrollnummer och beskrivningsnivå
* [Instans](https://libris.kb.se/katalogisering/help/workflow-instance) - instans kan också kallas utgåva eller manifestation. Exempel på egenskaper under Instans för ett bidrag är titel, upphov och utgivning.
* [Verk](https://libris.kb.se/katalogisering/help/workflow-work) – återger egenskaper för det abstrakta verket såsom medverkan och funktion, ämne, klassifikation, språk och innehållstyp. Verksbeskrivningen ligger under rubriken Instans av verk.

För instruktioner om att lägga till eller ta bort egenskaper, länka till entitet, skapa lokal entitet och om hur formuläret fungerar i övrigt, se Redigering i vänstermenyn. 

För information om katalogiseringsregler och Librispraxis, [se Metadatabyrån](https://metadatabyran.kb.se/) samt [se RDA Toolkit](https://access.rdatoolkit.org/). 

[Se även instruktionsfilmer på KB:s Youtubekanal](https://www.youtube.com/playlist?list=PLZVkEICvA5-GRT2oJQmLgq_2Pksx6zYPy).

## Adminmetadata
[Adminmetadata - Metadatabyrån](https://metadatabyran.kb.se/beskrivning/specialanvisningar/adminmetadata-i-libris)

### Bibliografi
* Bibliografi/Bibliotek/Sigel (bibliography/Library/sigel = 042 #9)
<br/>I mallen är DIGI ifyllt. Korrigera/komplettera vid behov.

### Beskrivningsnivå 
* Beskrivningsnivå (encodingLevel = 000/17)
<br/>Kontrollera beskrivningsnivån. I mallen är standardvärdet Biblioteksnivå (normalvärde för Librisbiblioteken).

### Anmärkning
* Anmärkning/Anmärkning om katalogiseringskälla/Benämning (hasNote/marc:SourceOfDescriptionNote/label = 588 #a)
<br/>```Exempel: S: Digitaliserat vardagstryck```

## Instans
[Se generell hjälptext för Instans](https://libris.kb.se/katalogisering/help/workflow-instance)

För att lägga till egenskaper under Instans, klicka på plustecknet i redigeringsvyn (den stora runda plusikonen under Verktygsikonen) - Lägg till egenskaper under: Elektronisk. Sök fram egenskapen och välj den genom att klicka på plustecknet vid egenskapens namn. 

### Instanstyp
* Instanstyp
<br/>Förval i mallen: Elektronisk

### Reproduktion av
* Reproduktion av (ReproductionOf = 776 #a #s #t #z #w)
<br/>Länk till fysiskt original då funktionen Skapa digital reproduktion använts.

Saknas länk får man manuellt länka till det fysiska originalet. Klicka på plustecknet inom Reproduktion av, sidorutan Lägg til entitet öppnas. Sök efter och länka till korrekt instans.

### Identifikator
* Identifikator/URN/Värde (identifiedBy/URN/value = 024 7/- #a #2)
<br/>Välj typ av Identifikator, t.ex. DOI, Hdl eller URN i rullgardinsmenyn. Ange identifikator.
<br/>```Exempel:```
<br/>```Identifikator/URN/Värde: urn:nbn:se:kb:dig-17390055```

### Utgivningssätt
* Utgivningssätt (issuanceType = 008/07)  
<br/>Förval i mallen: Monografisk resurs
<br/>Ändra vid behov

### Medietyp
* Medietyp (mediaType/Mediatype = 337 #b)
<br/>Förval i mallen: Computer 

### Bärartyp
* Bärartyp (carrierType/CarrierType = 338 #b)  
I mallen är följande entiteter länkade:
<br/> * onlineresurs, online resource, cr
<br/> * Onlineresurs, r (Nödvändig om koden  "r" (= fjärranslutning) behövs i 007/01 (= särskild bärarbeteckning) för bibliotekets lokala system)
<br/> * Onlineutgåva, o (Nödvändig om koden "o" (= onlineutgåva) behövs i 008/23 (= form för manifestationen) för bibliotekets lokala system)

### Produktion 
* Produktion/Digital produktion/Typanmärkning/Plats/Agent/Datum (production/DigitalReproduction/typeNote/place/agent/date = 533 #a #b #c #d)
<br/>```Exempel:``` 
<br/>```Typanmärkning: Digitalt faksimil``` 
<br/>```Plats/Benämning: Stockholm```
<br/>```Agent/Benämning: Kungliga biblioteket```
<br/>```Datum: 2020```

### Indirekt identifierad av
* Indirekt identifierad av/ISBN/Värde (indirectlyIdentifiedBy/ISBN/value = 020 #z)
<br/>ISBN hämtas från den fysiska förlagan (om sådant förekommer). Uppgiften är ifylld då funktionen Skapa digital reproduktion används.

### Digital karakteristika
* Digital karakteristika/Kodningsformat/Benämning (digitalCharacteristics/EncodingFormat/label = 347 #b)
Ange kodningsformat här, se RDA 3.19.3.3. Ej obligatorisk uppgift, men om kodningsformat anges ska det göras här och inte i en anmärkning.
<br/>```Exempel:``` 
<br/>```Kodningsformat/Benämning: pdf```
<br/>```Kodningsformat/Benämning: jpeg```
<br/>```Kodningsformat/Benämning: tiff```

### Tillhörande media
* Tillhörande media/Mediaobjekt/Katalogisatörens anmärkning/Offentlig anmärkning/URI (associatedMedia/cataloguersNote/marc:publicNote/uri = 856 #u #x #z)
<br/>```Exempel:``` 
<br/>```Katalogisatörens anmärkning: [Anmärkning]``` 
<br/>```Offentlig anmärkning: Fritt tillgänglig via Kungliga biblioteket```
<br/>```URI: http://urn.kb.se/resolve?urn=urn:nbn:se:kb:eod-1600793```

### Villkor för användning och åtkomst
* Villkor för användning och åtkomst/Användningsvillkor/Benämning (usageAndAccessPolicy/UsePolicy/label = 540 #a)
<br/>```Exempel:``` 
<br/>```Benämning: CC0``` 

### Relaterad beskrivning eller innehåll
* Relaterad beskrivning eller innehåll/Dokument/Katalogisatörens anmärkning/Offentlig anmärkning/URI (isPrimaryTopicOf/Document/cataloguersNote/marc:publicNote/uri = 856 #u #x #z)
<br/>```Exempel:```
<br/>```Katalogisatörens anmärkning: digipic``` 
<br/>```Offentlig anmärkning: tumnagelbild``` 
<br/>```URI: http://weburn.kb.se/tumnaglar/24/001655024,1,i,1.jpg```

### Anmärkning
* Anmärkning/Anmärkning/Benämning (hasNote/Note/label = 500 #a)
<br/>```Exempel:```
<br/>```Digitaliserat exemplar``` 
<br/>```Fritt tillgängligt via Internet``` 

## Verk 
[För information om egenskaperna, se den generella beskrivningen av Verk](https://libris.kb.se/katalogisering/help/workflow-work)

För att lägga till egenskaper under Instans av Verk, klicka på plustecknet till höger om Instans av Verk och verkstypen. Sök fram egenskapen och välj den genom att klicka på plustecknet vid egenskapens namn.

## Bestånd
För information om egenskaperna, [se den generella hjälptexten för Beståndsregistrering](https://libris.kb.se/katalogisering/help/workflow-holding) eller [Enkel beståndsregistrering](https://libris.kb.se/katalogisering/help/workflow-holding-simple).

### Innehas av
* Innehas av (heldBy = 852 #b)
<br/>Inloggad sigel.

### Anmärkning
* Anmärkning/Anmärkning/Benämning (hasNote/Note/label = 852 #z)
<br/>```Exempel:``` 
<br/>```Digitaliserat exemplar``` 

### Katalogisatörens anmärkning
* Katalogisatörens anmärkning (cataloguersNote = 852 #x) 
<br/>```Exempel:``` 
<br/>```[kbdkart = KB-specifik statistikkod]``` 
