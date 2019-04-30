---
section: Redigering
title: Checklista postimport
date: 2019-04-29
tags:
- redigering
- postimport
order: 12
---


# Checklista vid redigering av importerade poster

Denna checklista kan användas vid redigering av importerade poster från Andra källor.  

Beroende på vilka katalogiseringsregler som har använts i den post man importerat bör olika anvisningar följas: 
- För poster gjorda enligt AACR2, följ riktlinjerna för [Minimikrav på importerade bibliografiska poster](http://www.kb.se/katalogisering/Katalogisering/Minimikrav-pa-importerade-bibliografiska-poster/) i Katalogisatörens verktygslåda. 
- För poster gjorda enligt RDA, följ riktlinjerna för [Importerade poster](http://www.kb.se/rdakatalogisering/Postimport/) i Anvisningar för katalogisering (RDA) 

Ytterligare anvisningar hittas även i Katalogisatörens verktygslåda under de enskilda MARC21-fälten inom [Katalogisering](http://www.kb.se/katalogisering/Katalogisering/) och [Bibliografiska formatet](http://www.kb.se/katalogisering/Formathandboken/Bibliografiska-formatet/).  

Eftersom anvisningarna inte är anpassade till det nya katalogiseringsverktyget eller det nya formatet följer här en lista på de viktigaste sakerna att tänka på. 

OBS! Innan den importerade posten sparas i Libris syns de länkade entiteterna med den engelska benämningen. De får automatiskt den svenska benämningen efter att posten sparats. 

### Innehåll 

| [Adminmetadata](#adminmetadata) | [Instans](#instans) | [Verk](#verk) | 
| ----------- |  ----------- | ----------- | 
|  [Generell hjälptext för Adminmetadata](https://libris.kb.se/katalogisering/help/workflow-adminmetadata) | [Generell hjälptext för Instans](https://libris.kb.se/katalogisering/help/workflow-instance) | [Generell hjälptext för Verk](https://libris.kb.se/katalogisering/help/workflow-work) |
| [Beskrivningsnivå](#beskrivningsniva) | [Titel](#titel) | [Språk och litterär genre](#sprak-och-litterar-genre) |
| [Skapad av](#skapad-av) | [Upphovsuppgift](#upphovsuppgift) | [Medverkan och funktion](#medverkan-och-funktion) |
| [Uppgraderad  eller importerad av](#uppgraderad-eller-importerad-av) | [Utgivning](#utgivning) | [Föredragen titel](#titel) |
| [Katalogiseringsregler](#katalogiseringsregler) | [Omfång, övriga fysiska detaljer, mått](#omfang) |  [Svenska amnesord och genre](#svenska-amnesord-och-genre) |
| [Katalogiseringsspråk](#katalogiseringssprak) | [Egenskaper som länkar till andra databaser och instanser som inte finns i Libris](#andra-databaser) | [Klassifikation](#klassifikation)  | 
| [Katalogiserande instans](#katalogiserande-instans) | [Identifikator och Indirekt identifierad av](#identifikator-och-indirekt-identifierad-av) |  |
| [Systemteknisk anmärkning](#systemteknisk-anmarkning) | [Seriemedlemskap](#seriemedlemskap) | |
| [Entry map](#entry-map) | | | 
| [Systemnummer](#systemnummer) | | | 
| [marcuncompleted och marcfailedfixedfields](#marcuncompleted-och-marcfailedfixedfields) | | |


## Adminmetadata 
Läs mer om egenskaperna under [Adminmetadata](https://libris.kb.se/katalogisering/help/workflow-adminmetadata). 
### Beskrivningsnivå 
Beskrivningsnivå (encodingLevel = 000/17) 

Vid postimport händer det att egenskapen saknar värde eller saknas helt. 
Om egenskapen finns men saknar värde: 
- Välj värde från listan 
Om egenskapen saknas: 
- Klicka på plustecknet Lägg till egenskaper under: Post 
- Välj typ Beskrivningsnivå och välj värde från lista  

### Skapad av 
Skapad av/Organisation/Namn (descriptionCreator/Organization/name = 040 #a) 
 
Förval vid postimport: den sigel som importerat posten.   

### Uppgraderad eller importerad av 
Uppgraderad eller importerad av/Bibliotek/Sigel (descriptionUpgrader/Library/sigel = 040 #d) 

Lägg alltid till uppgiften vid postimport. För att lägga till egenskapen: 
- Klicka på plustecknet Lägg till egenskaper under: Post och välj Uppgraderad eller importerad av 
- Klicka på plustecknet Lägg till entitet och välj Skapa lokal entitet 
- Välj Bibliotek och skriv in uppgiften under Sigel 
Lägg även till sigel om ett annat bibliotek har importerat posten men du uppgraderar beskrivningsnivån. 

OBS! Egenskapen kan inte läggas till via funktionen Berika från mall.  

### Katalogiseringsregler 
Katalogiseringsregler (040 #e) 

Vid postimport behöver katalogiseringsreglerna inte ändras till RDA men väljer man att göra det måste hela beskrivningen anpassas till RDA. 

OBS! Om egenskapen Katalogiseringsregler saknas och läggs till via funktionen Berika från mall, blir katalogiseringsreglerna automatiskt RDA. 

OBS! Läggs Katalogiseringsregler/RDA till för hand måste även egenskapen ”ISBD-interpunktion finns” läggas till. 

### Katalogiseringssprak 
Katalogiseringsspråk (descriptionLanguage = 040 #b) 

Anges vid katalogisering enligt RDA. Låt uppgiften stå. 

OBS! Om egenskapen läggs till med funktionen Berika från mall blir katalogiseringsspråket automatiskt angivet som svenska. Radera eller ändra vid behov. 

### Katalogiserande instans 
Katalogiserande instans (marc:catalogingSource = 008/39) 

Ändra inte postens ursprungliga kod. Saknas egenskapen:  
- Klicka på plustecknet Lägg till egenskaper under: Post 
- Välj Katalogiserande instans 
- Klicka på plustecknet Lägg till entitet, sök fram och välj Annan verksamhet.

### Systemteknisk anmarkning 
Systemteknisk anmärkning/Benämning (technicalNote/label = 599 #a) 

- Låt anmärkningen om vilken källa posten importerats från ligga kvar 
- Vid uppgradering av förhandsposter och preliminära poster (då Beskrivningsnivån uppgraderas), ta bort anmärkningen om att posten är maskinellt skapad 

### Entry map 
Entry map (marc:entryMap = 000/20-23) 

Kan förekomma i vissa importerade poster. Radera egenskapen. 

### Systemnummer 
Identifikator/Lokal identifikator/Värde (035 #a) 

Systemnummer från andra bibliotek eller bibliotekskonsortier kan förekomma. Låt uppgiften stå. 

### marcuncompleted och marcfailedfixedfields 
Data som inte hanteras av systemet visas i MARC21-format som marcuncompleted eller marcfailedfixedfields. Kontrollera om det innehåller information som bör vara med i beskrivningen och radera sedan uppgifterna.

## Instans 
Läs mer om egenskaperna under [Instans](https://libris.kb.se/katalogisering/help/workflow-instance). 

### Titel 
Har titel/… (hasTitle/… = 24X) 

Kontrollera att beskrivningen är korrekt. 

OBS! Korrekt egenskap för undertitel (245 #b) är hasTitle/Title/subtitle men i importerade poster ligger den ibland istället i hasTitle/Title/titleRemainder. 
För att kontrollera om det är korrekt ställ markören på Övrig titelinformation och om titleRemainder blir synligt istället för subtitle, ändra uppgiften: 
- Klicka på Lägg till egenskaper under: Titel 
- Välj Övrig titelinformation/subtitle och skriv in undertiteln 
- Radera Övrig titelinformation/titleRemainder 

### Upphovsuppgift 
Upphovsuppgift (responsibilityStatement = 245 #c) 

Vid postimport saknas ibland upphovsuppgiften. Om egenskapen saknas: 
- Klicka på Lägg till egenskaper under: Instans 
- Välj Upphovsuppgift och fyll i uppgiften 

### Utgivning 
Utgivning (publication = 008/07-10, 008/15-17, 260, 264 -/1) 

Vid postimport medföljer ibland två avsnitt: Primär utgivning med År och Land, och Utgivning med Plats, Agent och Datum. Vid redigering: 
- Flytta, om det bedöms nödvändigt, uppgifterna om Plats, Agent och Datum till Primär utgivning och ta bort Utgivning.  

I andra fall finns endast avsnittet Utgivning med. Vid redigering: 
- Klicka på plustecknet Lägg till entitet vid Utgivning 
- Välj typ Primär utgivning 
- Fyll i uppgifterna i Primär utgivning och ta sedan bort Utgivning  

Vid postimport förekommer ibland både År och Copyrightår inom Primär utgivning (= 008/06: t, 008/07-10: År och 008/11-14: Copyrightår). Låt uppgiften ligga kvar oförändrad. Ej att förväxla med egenskapen Copyright/Copyright/Datum (= 264 -/4 #c). 

OBS! Om egenskapen Utgivning/Primär utgivning saknas och läggs till via funktionen Berika från mall, länkas utgivningslandet automatiskt till Sverige. Ändra vid behov. 

### Omfang
**Omfång, övriga fysiska detaljer, mått**  
Kontrollera att beskrivningen är korrekt. 

### Andra databaser
**Egenskaper som länkar till andra databaser och instanser som inte finns i Libris**  
Låt uppgifterna stå:  
- Tillhörande media/Mediaobjekt (associatedMedia/Mediaobject = 856 4/0) 
- Annan relaterad resurs/Elektronisk (marc:versionOfResource/Electronic = 856 4/1) 
- Relaterad beskrivning eller innehåll/Dokument (isPrimaryTopicOf/Document = 856 4/2)  
Radera uppgifterna: 
- Beskriven av/Post/Kontrollnummer (= #w).Innehåller id:n för annan bibliografisk post i den databas man importerat från. Kan förekomma t.ex. i Annat bärarformat (otherPhysicalFormat = 776), i Seriemedlemskap (seriesMembership = 830). OBS! Kan även förekomma inom egenskaper i Instans av verk 

### Identifikator och Indirekt identifierad av 
Identifikator/ISBN/Värde (identifiedBy/Isbn/value = 020 #a) och Indirekt identifierad av/ISBN/Värde (indirectlyIdentifiedBy/Isbn/value = 020 #z) 

OBS! Måste ses över! Anvisningarna nedan är upprättade med tanke på matchningsproblematik vid automatiska flöden. Behov av att kunna lägga felaktiga ISBN i Indirekt identifierad av finns. 

Vid import från Andra källor kan posterna ibland innehålla flera olika ISBN, både för tryckt och elektronisk utgåva. För att inte skapa problem i Libris importflöden är det viktigt att tänka på följande: 
- Endast ISBN för den beskrivna utgåvan ska ligga i Identifikator/ISBN/Värde (020 #a). Låt endast värden för två utgåvor ligga kvar om det ena syftar på inbunden och det andra på häftad utgåva. 
-	För en tryckt bok får det inte finnas ISBN för en annan tryckt version i Indirekt identifierad av/ISBN/Värde (020 #z), utan enbart i Identifierad av/ISBN/Värde (020 #a). Flytta ISBN för tryckta versioner till Identifierad av och låt ISBN för elektroniska versioner ligga kvar under Indirekt identifierad av. 
- För elektroniska resurser gäller samma sak, fast tvärtom: Det får inte ligga ISBN för en annan elektronisk version under Indirekt identifierad av, utan där får endast ISBN för olika tryckta versioner ligga. 
- Ibland ligger samma ISBN, tiosiffrigt och/eller trettonsiffrigt, i både Identifikator/ISBN/Värde (020 #a) och Indirekt identifierad av/ISBN/Värde (020 #z). Ta bort ISBN från Indirekt identifierad av och låt det ligga kvar under Identifikator/ISBN/Värde. 
- Om det ligger ISBN till andra utgåvor i Indirekt identifierad av/ISBN/Värde (020 #z), kan det särskiljande tillägget (020 #q) ibland hamna fel, under Identifikator/Nothing/Särskiljande tillägg. Lägg till det särskiljande tillägget under Indirekt identifierad av/ISBN, kopplat till det värde det gäller, och radera Nothing/Särskiljande tillägg under Identifikator. 

OBS! Om det är svårt att belägga de ISBN som ligger i en katalogpost är det bättre att radera dem. Låt endast de som hör till resursen som ska katalogiseras vara kvar. 

### Seriemedlemskap 
Seriemedlemskap/Serieuppgift (seriesMembership/seriesStatement = 490 #a) och Seriemedlemskap/Ingår i serie/Instans av Verk/Verk/Har titel/Titel/Huvudtitel (seriesMembership/inSeries/InstanceofWork/Work/hasTitle/Title/mainTitle = 830 #a) 
- Om motsvarande fält 490 #a och 830 #a matchar, läggs de vid import i samma Seriemedlemskap. 
- Om de inte matchar, skapas två Seriemedlemskap: ett med enbart Seriemedlemskap/Serieuppgift (490 #a) och ett med enbart Seriemedlemskap/Ingår i serie/Instans av Verk/Verk/Har titel/Titel/Huvudtitel (830 #a). 

När man redigerar importerade poster med två Seriemedlemskap kan man, om man bedömer det nödvändigt, slå ihop dem till ett. 

OBS! Om ISSN finns i både 490 och 830 och om volymbeteckningen är angiven på olika sätt i 490 och 830, dubbleras dessa inom Seriemedlemskapet. Radera en av de dubblerade ISSN- och/eller voIymbeteckningarna.  

## Instans av verk  
Läs mer om egenskaperna under [Verk](https://libris.kb.se/katalogisering/help/workflow-work). 

### Sprak och litterar genre
**Språk, litterär genre m.m.**   
Kontrollera att beskrivningen är korrekt. 

OBS! Om egenskapen Språk (language = 008/35-37) saknas och läggs till via funktionen Berika från mall, länkas den automatiskt till svenska. Ändra vid behov. 

### Medverkan och funktion 
Läs mer under [Relationer till Agent](https://libris.kb.se/katalogisering/help/workflow-agent-org-instance). 
- Validera alltid namnformer och, vid behov, skapa auktoriteter enligt [Riktlinjer för löpande auktoritetsarbete i Libris](http://www.kb.se/dokument/Riktlinjer%20f%C3%B6r%20det%20l%C3%B6pande%20auktoritetsarbetet%20i%20Libris.pdf)  
- Lägg till funktionskoder (#4) för medverkande agenter om de inte finns eller om endast funktionstermer (#e) finns. Funktionstermerna kan ligga kvar oförändrade. 
 
### Titel
**Föredragen titel**  
Kontrollera att titelformen för föredragen titel stämmer med svensk praxis. 

### Svenska amnesord och genre
**Svenska ämnesord och Genre/formtermer**  
Lägg till Svenska ämnesord och Genre/formtermer enligt
[Riktlinjer för indexering med Svenska ämnesord](http://www.kb.se/katalogisering/Svenska-amnesord/riktlinjer/) 

### Klassifikation 
Läs mer om Klassifikation i hjälptexten för [Verk](https://libris.kb.se/katalogisering/help/workflow-work). 

#### DDK-klassifikation 
Lägg till klassifikationskod från DDK eller kontrollera att den befintliga koden är korrekt. Efter kontroll ändra Parallell upplagebeteckning/Upplagespecifik upphovsuppgift till ”23/swe”. 

OBS! Egenskapen Parallell upplagebeteckning går inte att lägga till manuellt. Om den saknas måste en ny DDK-kod läggas till: 
- Klicka på plustecknet Lägg till entitet vid Klassifikation 
- Välj Skapa lokal entitet och välj DDK-klassifikation 
- Fyll i uppgifterna och radera den ofullständiga DDK-klassifikationen 

#### SAB-klassifikation 
För att lägga till klassifikationskod: 
- Klicka på Lägg till entitet (plustecknet vid Klassifikation) 
- Välj Skapa lokal entitet och välj Klassifikation 
- Fyll i uppgifterna 
