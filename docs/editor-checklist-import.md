---
section: Redigering
title: Checklista postimport
date: 2019-05-24
tags:
- redigering
- postimport
order: 12
---


# Checklista vid redigering av importerade poster

Poster som importeras till Libris från andra källor ska kontrolleras och vid behov rättas. Vid redigeringen bör olika anvisningar följas: 
- För poster gjorda enligt AACR2 eller annat regelverk än RDA, följ riktlinjerna för [Minimikrav på importerade bibliografiska poster](http://www.kb.se/katalogisering/Katalogisering/Minimikrav-pa-importerade-bibliografiska-poster/) i Katalogisatörens verktygslåda. 
- För poster gjorda enligt RDA, följ riktlinjerna för [Importerade poster](http://www.kb.se/rdakatalogisering/Postimport/) i Anvisningar för katalogisering (RDA) 

Ytterligare anvisningar hittas även i Katalogisatörens verktygslåda under de enskilda MARC21-fälten inom [Katalogisering](http://www.kb.se/katalogisering/Katalogisering/) och [Bibliografiska formatet](http://www.kb.se/katalogisering/Formathandboken/Bibliografiska-formatet/).  

Eftersom anvisningarna inte är anpassade till det nya katalogiseringsverktyget eller det nya formatet kan denna checklista användas som stöd vid redigering.  

OBS! Innan den importerade posten sparas i Libris syns de länkade entiteterna med den engelska benämningen. De får automatiskt den svenska benämningen efter att posten sparats. 

### Innehåll 

| [Adminmetadata](#adminmetadata) | [Instans](#instans) | [Verk](#verk) | 
| ----------- |  ----------- | ----------- | 
|  [Generell hjälptext för Adminmetadata](https://libris.kb.se/katalogisering/help/workflow-adminmetadata) | [Generell hjälptext för Instans](https://libris.kb.se/katalogisering/help/workflow-instance) | [Generell hjälptext för Verk](https://libris.kb.se/katalogisering/help/workflow-work) |
| [Identifikator](#identifikator) | [Identifikator och Indirekt identifierad av](#identifikator-och-indirekt-identifierad-av) | [Föredragen titel](#foredragen-titel) |
| [Beskrivningsnivå](#beskrivningsniva)| [Utgivningssätt](#utgivningssatt) | [Medverkan och funktion](#medverkan-och-funktion) |
| [Systemteknisk anmärkning](#systemteknisk-anmarkning) | [Medietyp och bärartyp](#medietyp-och-barartyp) | [Språk](#sprak) |
| [Skapad av](#skapad-av) | [Titel](#titel) | [Genre](#genre) |
| [Entry map](#entry-map) | [Upphovsuppgift](#upphovsuppgift) | [Ämne](#amne) |
| [Uppgraderad  eller importerad av](#uppgraderad-eller-importerad-av) | [Utgivning](#utgivning) | [Klassifikation](#klassifikation) |
| [Katalogiseringsregler](#katalogiseringsregler) | [Forväntad utgivningstid](#forvantad-utgivningstid) | [Innehållstyp](#innehallstyp) | 
| [Katalogiseringsspråk](#katalogiseringssprak) | [Omfång, övriga fysiska detaljer, mått](#omfang) |  |
| [Katalogiserande instans](#katalogiserande-instans) | [Seriemedlemskap](#seriemedlemskap) |  |
| [marcuncompleted och marcfailedfixedfields](#marcuncompleted-och-marcfailedfixedfields) | [Egenskaper som länkar till andra databaser och instanser som inte finns i Libris](#andra-databaser) |  | 
|  | [MARC-egenskaper](#MARC-egenskaper) |  |


## Adminmetadata 
Läs mer om egenskaperna under [Adminmetadata](https://libris.kb.se/katalogisering/help/workflow-adminmetadata). 

### Identifikator 
Identifikator/Lokal identifikator/Värde (identifiedBy/SystemNumber/value = 035 #a) 

- Systemnummer från andra bibliotek eller bibliotekskonsortier kan förekomma. Radera egenskaper som enbart innehåller numeriska tecken. Låt annars uppgiften stå.  

### Beskrivningsniva
Beskrivningsnivå (encodingLevel = 000/17) 

Vid postimport händer det att egenskapen saknar värde eller saknas helt. 
- Om egenskapen finns men saknar värde: 
  - Välj värde från listan 
  
- Om egenskapen saknas: 
  - Klicka på plustecknet Lägg till egenskaper under: Post 
  - Välj typ Beskrivningsnivå och välj värde från lista  

### Systemteknisk anmarkning 
Systemteknisk anmärkning/Benämning (technicalNote/label = 599 #a) 

- Låt anmärkningen om vilken källa posten importerats från ligga kvar 
- Vid uppgradering av förhandsposter och preliminära poster (då Beskrivningsnivån uppgraderas), ta bort anmärkningen om att posten är maskinellt skapad 

### Skapad av 
Skapad av/Organisation/Namn (descriptionCreator/Organization/name = 040 #a) 
 
För närvarande är förval vid postimport den sigel som importerat posten.  

### Entry map 
Entry map (marc:entryMap = 000/20-23) 

Kan förekomma i vissa importerade poster. 
- Radera egenskapen. 

### Uppgraderad eller importerad av 
Uppgraderad eller importerad av/Bibliotek/Sigel (descriptionUpgrader/Library/sigel = 040 #d) 

- Lägg alltid till uppgiften vid postimport. Om egenskapen saknas: 
  - Klicka på plustecknet Lägg till egenskaper under: Post och välj Uppgraderad eller importerad av 
  - Klicka på plustecknet Lägg till entitet och välj Skapa lokal entitet 
  - Välj Bibliotek och skriv in uppgiften under Sigel 
  
- Lägg även till sigel om ett annat bibliotek har importerat posten men du uppgraderar beskrivningsnivån. 

OBS! Egenskapen kan inte läggas till via funktionen Berika från mall.  

### Katalogiseringsregler 
Katalogiseringsregler (040 #e) 

- Vid postimport behöver katalogiseringsreglerna inte ändras till RDA men väljer man att göra det måste hela beskrivningen anpassas till RDA. 

OBS! Om egenskapen Katalogiseringsregler saknas och läggs till via funktionen Berika från mall, blir katalogiseringsreglerna automatiskt RDA. 

OBS! Läggs Katalogiseringsregler/RDA till för hand måste även egenskapen ”ISBD-interpunktion finns” läggas till. 

### Katalogiseringssprak 
Katalogiseringsspråk (descriptionLanguage = 040 #b) 

- Anges vid katalogisering enligt RDA. Kontrollera och rätta vid behov felaktiga värden.   

OBS! Om egenskapen läggs till med funktionen Berika från mall blir katalogiseringsspråket automatiskt angivet som svenska.   

### Katalogiserande instans 
Katalogiserande instans (marc:catalogingSource = 008/39) 

- Ändra inte postens ursprungliga kod. Saknas egenskapen: 
  - Klicka på plustecknet Lägg till egenskaper under: Post 
  - Välj Katalogiserande instans 
  - Klicka på plustecknet Lägg till entitet, sök fram och välj Annan verksamhet.

### marcuncompleted och marcfailedfixedfields 
Data som inte hanteras av systemet visas i MARC21-format som _marcuncompleted_ eller _marcfailedfixedfields_. 
- Kontrollera om det innehåller information som bör vara med i beskrivningen och radera sedan uppgifterna.

## Instans 
Läs mer om egenskaperna under [Instans](https://libris.kb.se/katalogisering/help/workflow-instance). 

### Identifikator och Indirekt identifierad av 
Identifikator/ISBN/Värde (identifiedBy/Isbn/value = 020 #a) 

Indirekt identifierad av/ISBN/Värde (indirectlyIdentifiedBy/Isbn/value = 020 #z) 

OBS! Anvisningarna som följer är upprättade med tanke på matchningsproblematik vid automatiska flöden och skiljer sig därför från RDA-anvisningarna. Arbete pågår med att se över egenskaperna och hitta lösningar på problemen.

Vid import från Andra källor innehåller posterna ofta flera olika ISBN, både för tryckt och elektronisk utgåva. För att inte skapa problem i Libris importflöden är det viktigt att tänka på följande: 
- Om det är svårt att belägga de ISBN som ligger i en katalogpost är det bättre att radera dem. Låt endast det som hör till resursen som ska katalogiseras ligga kvar. 
-	För en tryckt version får det inte finnas giltiga ISBN för en annan tryckt version i *Indirekt identifierad av*, utan enbart i *Identifikator*. Flytta ISBN för tryckta versioner till *Identifikator* och låt ISBN för elektroniska versioner ligga kvar under *Indirekt identifierad av*. 
- För elektroniska resurser gäller samma sak, fast tvärtom. Det får inte ligga giltiga ISBN för en annan elektronisk version under *Indirekt identifierad av*, utan där får endast ISBN för olika tryckta versioner ligga. 
- Ibland ligger samma ISBN, tiosiffrigt och/eller trettonsiffrigt, i både *Identifikator* och *Indirekt identifierad av*. Ta bort det/de ISBN som ligger fel. 
- Vid import kan det särskiljande tillägget (020 #q) som hör till det ISBN som matchas till *Indirekt identifierad av*, ibland hamna fel och lägga sig som Nothing/Särskiljande tillägg under *Identifikator*. Lägg till och fyll i Särskiljande tillägg under *Indirekt identifierad av*, kopplat till det ISBN det tillhör, och radera Nothing under *Identifikator*. 

### Utgivningssatt
Utgivningssätt (issuanceType) 

- Kontrollera att beskrivningen är korrekt. 

### Medietyp och barartyp 
Medietyp (mediaType/Mediatype = 337 #b) 

Bärartyp (carrierType/CarrierType = 338 #b) 

- Kontrollera att beskrivningen är korrekt och länka vid behov: 

  - Om beskrivningen innehåller koder och/eller termer på engelska behöver entiteterna inte länkas. Länk skapas automatiskt då instansen sparas. 
  - Om beskrivningen innehåller termer på annat språk än engelska måste entiteterna länkas.

### Titel 
Har titel/… (hasTitle/… = 24X) 

- Kontrollera att beskrivningen är korrekt. 

- OBS! Korrekt egenskap för undertitel (245 #b) är hasTitle/Title/subtitle men i importerade poster ligger den ibland istället i hasTitle/Title/titleRemainder. För att kontrollera om det är korrekt ställ markören på Övrig titelinformation och om _titleRemainder_ blir synligt istället för _subtitle_, ändra uppgiften: 
  - Klicka på Lägg till egenskaper under: Titel 
  - Välj Övrig titelinformation/subtitle och skriv in undertiteln 
  - Radera Övrig titelinformation/titleRemainder 
 
- Om Egenskapen _Titeln är sökelement_ finns med radera den. 

### Upphovsuppgift 
Upphovsuppgift (responsibilityStatement = 245 #c) 

- Vid postimport saknas ibland upphovsuppgiften. Om egenskapen saknas: 
  - Klicka på Lägg till egenskaper under: Instans 
  - Välj Upphovsuppgift och fyll i uppgiften 

### Utgivning 
Utgivning (publication = 008/07-10, 008/15-17, 260, 264 -/1) 

- Vid postimport medföljer ibland två avsnitt: Primär utgivning med År och Land, och Utgivning med Plats, Agent och Datum. Vid redigering: 
  - Flytta, om det bedöms nödvändigt, uppgifterna om Plats, Agent och Datum till Primär utgivning och ta bort Utgivning.  

- I andra fall finns endast avsnittet Utgivning med. Vid redigering: 
  - Klicka på plustecknet Lägg till entitet vid Utgivning 
  - Välj typ Primär utgivning 
  - Fyll i uppgifterna i Primär utgivning och, om det bedöms nödvändigt, ta bort Utgivning  

- Vid postimport förekommer ibland både År och Copyrightår inom Primär utgivning (= 008/06: t, 008/07-10, 008/11-14). Uppgiften läggs inte till vid primärkatalogisering men kan ligga kvar om den är korrekt. Vid RDA-katalogisering jämför med egenskapen Copyright/Copyright/Datum (= 264 -/4 #c). 

OBS! Om egenskapen Utgivning/Primär utgivning saknas och läggs till via funktionen Berika från mall, länkas utgivningslandet automatiskt till Sverige. Ändra vid behov. 

### Forvantad utgivningstid  
Förväntad utgivningstid (projectedProvisionDate = 263)  

Kan förekomma i preliminära poster. 
- Radera egenskapen.  

### Omfang
**Omfång, övriga fysiska detaljer, mått**  
- Kontrollera att beskrivningen är korrekt. 

### Seriemedlemskap 
Seriemedlemskap/Serieuppgift (seriesMembership/seriesStatement = 490 #a)

Seriemedlemskap/Ingår i serie/Instans av Verk/Verk/Har titel/Titel/Huvudtitel (seriesMembership/inSeries/InstanceofWork/Work/hasTitle/Title/mainTitle = 830 #a) 

- Ibland skapas det vid import två Seriemedlemskap, ett med _Serieuppgift_ och ett med _Ingår i serie_. Vid redigering kan man, om man bedömer det nödvändigt, slå ihop dem till ett. 

- Om ISSN är angivet i både 490 och 830 och/eller om volymbeteckningen är angiven på olika sätt i 490 och 830 i ursprungsposten, dubbleras dessa inom Seriemedlemskapet. Radera de dubblerade fälten.  

### Andra databaser
**Egenskaper som länkar till andra databaser och instanser som inte finns i Libris**  
Uppgifterna kan stå kvar:  
- Tillhörande media/Mediaobjekt (associatedMedia/Mediaobject = 856 4/0) 
- Annan relaterad resurs/Elektronisk (marc:versionOfResource/Electronic = 856 4/1) 
- Relaterad beskrivning eller innehåll/Dokument (isPrimaryTopicOf/Document = 856 4/2)  
  
Radera uppgifterna: 
- Beskriven av/Post/Kontrollnummer (= #w).Innehåller id:n för annan bibliografisk post i den databas man importerat från. Kan förekomma t.ex. i Annat bärarformat (otherPhysicalFormat = 776), i Seriemedlemskap (seriesMembership = 830). OBS! Kan även förekomma inom egenskaper i Instans av verk 

### MARC-egenskaper 
Data från MARC21-fält som inte har en motsvarighet i Libris visas som MARC:... (t.ex. MARC:HASTRANSLATEDTITLE).
- Låt egenskaperna ligga kvar.

## Instans av verk  
Läs mer om egenskaperna under [Verk](https://libris.kb.se/katalogisering/help/workflow-work). 

### Foredragen titel
**Föredragen titel**  
- Kontrollera att titelformen för föredragen titel stämmer med svensk praxis.

### Medverkan och funktion 
Läs mer under [Relationer till Agent](https://libris.kb.se/katalogisering/help/workflow-agent-org-instance). 
- Validera alltid namnformer och, vid behov, skapa auktoriteter enligt [Riktlinjer för löpande auktoritetsarbete i Libris](http://www.kb.se/dokument/Riktlinjer%20f%C3%B6r%20det%20l%C3%B6pande%20auktoritetsarbetet%20i%20Libris.pdf).  
- Länka till korrekt funktion. Om beskrivningen endast innehåller koder behöver entiteterna inte länkas, länk skapas automatiskt då instansen sparas. Om egenskapen saknas: 
  - Klicka på plustecknet Lägg till egenskaper under: Primär medverkan (eller Medverkan) 
  - Välj Funktion och länka 
 
### Sprak
#### Språk

Språk (language = 008/35-37 och 040 #a) 

- Kontrollera att beskrivningen är korrekt. 

OBS! Om egenskapen Språk saknas och läggs till via funktionen Berika från mall, länkas den automatiskt till svenska. Ändra vid behov. 

#### Originalversion 

Originalversion/Verk/Språk (originalversion/Work/language = 041 #h) 

- Kontrollera att beskrivningen är korrekt.  

### Genre 
#### Termer som motsvarar MARC21-koder i 008 

- Kontrollera att de länkade entiteterna är korrekta (Litterär genre, Festskrift m.m.) 

#### Genre/formtermer enligt Svenska ämnesord 

- Komplettera med tillämpliga termer för genre/form enligt [Riktlinjer för indexering med Svenska ämnesord](http://www.kb.se/dokument/Verktygsladan/Svenska%20%C3%A4mnesord/Riktlinjer/Riktlinjer%20SAO.pdf]) 

### Amne 
Läs mer om [Ämnesord i Libris](https://libris.kb.se/katalogisering/help/workflow-general-sh) 

#### Svenska ämnesord 
- Komplettera med tillämpliga ämnesord enligt [Riktlinjer för indexering med Svenska ämnesord](http://www.kb.se/dokument/Verktygsladan/Svenska%20%C3%A4mnesord/Riktlinjer/Riktlinjer%20SAO.pdf]). 

#### Agenter som ämne
Läs mer om agenter som ämne i hjälptexten [Relationer till Agent](https://libris.kb.se/katalogisering/help/workflow-agent-org-instance). 

- Validera namnformer. 

### Klassifikation 
Läs mer om Klassifikation i hjälptexten för [Verk](https://libris.kb.se/katalogisering/help/workflow-work). 

#### DDK-klassifikation 
- Lägg till klassifikationskod från DDK eller kontrollera att den befintliga koden är korrekt. Om kod läggs till eller ändras bör Parallell upplagebeteckning/Upplagespecifik upphovsuppgift vara ”23/swe”. 

  OBS! Egenskapen _Parallell upplagebeteckning_ går inte att lägga till manuellt. Om den saknas måste en en ny DDK-kod läggas till: 
  - Klicka på plustecknet Lägg till entitet vid Klassifikation 
  - Välj Skapa lokal entitet och välj DDK-klassifikation 
  - Fyll i uppgifterna och radera den ofullständiga DDK-klassifikationen 

#### SAB-klassifikation 
- Lägg till klassifikationskod.

### Innehallstyp 
Innehållstyp/Innehållstyp (contentType/ContentType = 336 #b) 

- Kontrollera att beskrivningen är korrekt och länka vid behov: 

  - Om beskrivningen innehåller koder och/eller termer på engelska behöver entiteterna inte länkas. Länk skapas automatiskt då instansen sparas. 
  - Om beskrivningen innehåller termer på annat språk än engelska måste entiteterna länkas.
