---
section: Hjälptexter katalogisering
title: Tryckt seriell resurs
order: 24
date: 2019-02-04
tags:
- under arbete
- seriell resurs
- tidskrift
- monografiserie
--- 

## Tryckt seriell resurs

Denna hjälptext beskriver ett antal vanligt förekommande egenskaper, med utgångspunkt från exempel. För instruktioner om att länka till entitet, skapa lokal entitet och om hur formuläret fungerar i övrigt, se Redigering i vänstermenyn. För information om katalogregler, skrivregler och övriga katalogiseringsanvisningar, se [Anvisningar för katalogisering - RDA](http://www.kb.se/rdakatalogisering/Anvisningar/Arbetsfloden/Tryckta-seriella-resurser/ "Anvisningar för katalogisering - RDA").

Se även [instruktionsfilmer](https://www.youtube.com/playlist?list=PLZVkEICvA5-GRT2oJQmLgq_2Pksx6zYPy)   

I de flesta fall ska informationen delas upp i olika egenskaper (jfr fält) och underliggande egenskaper (jfr delfält). I några undantagsfall är det nödvändigt att använda ISBD-interpunktion i inom en egenskap, för att separera uppgifter. Dessa fall visas genom exempel nedan. I övriga fall, lägg inte in ISBD-interpunktion för att avsluta en egenskap (fält). Använd vid behov klamrar inom egenskap (fält), enligt Anvisningar för katalogisering - RDA.

I vissa fall fungerar det ännu inte fullt ut att lägga till alla uppgifter som beskrivs i denna hjälptext. Arbete pågår med förbättra gränssnittet. För att anmäla fel, använd detta [formulär](https://docs.google.com/forms/d/e/1FAIpQLSfOChJOGDoHUQguSF83F5XyTZiQL-yU47nvcqb6qwNT9GX7Aw/viewform). För att lämna synpunkter, använd detta [formulär](https://docs.google.com/forms/d/e/1FAIpQLSfOChJOGDoHUQguSF83F5XyTZiQL-yU47nvcqb6qwNT9GX7Aw/viewform).  

Innehåll:  

| [Adminmetadata](#adminmetadata) | [Instans](#instans) | [Verk](#verk) | 
| ------ | ----------- |  ----------- |
| [Skapad av](#skapad-av) | [Utgivningssätt](#utgivningssatt) | [Verkets titel](#verkets-titel) | 
| [Uppgraderad av](#uppgraderad-av) | [Nyckeltitel](#nyckeltitel)| [Språk](#sprak) |
| [Katalogiserande instans](#katalogiserande-instans) | [Titel](#titel) | [Alfabet](#alfabet) |
| [Poststatus](#poststatus) | [Identifikator](#identifikator) | [Medverkan och funktion](#medverkan-och-funktion) |
| [Systemnummer](#systemnummer) | [Utgivning](#utgivning) | [Genre](#genre) |
| [Katalogiseringsspråk](#katalogiseringssprak) | [Frekvens](#frekvens) | [Klassifikation](#klassifikation) |
| [Katalogiseringsregler](#katalogiseringsregler) | [Numrering av seriell resurs](#numrering-av-seriell-resurs) | [Ämne](#amne) |
| [Beskrivningsnivå](#beskrivningsniva) | [Omfång](#omfang) | [Innehållstyp](#innehallstyp) |
| [Bibliografikod](#bibliografikod) | [Medietyp](#medietyp) | [Länkfält - relationer under verk](#relationer-under-verk) |
| [Systemteknisk anmärkning](#systemteknisk-anmarkning) | [Bärartyp](#barartyp) | |
| | [Anmärkning](#anmarkning) | |
| | [Annat bärarformat](#annat-bararformat) | |


### Adminmetadata  
#### Skapad av, Uppgraderad av
* Skapad av/Organisation/Namn (descriptionCreator/Organization/name = 040 ‡a)  
  Förval: den sigel som skapat posten. Ska inte ändras.  
  ```Exempel: S```  
  
#### Uppgraderad av  
* Uppgraderad eller importerad av/Bibliotek/Sigel (descriptionUpgrader/Library/sigel = 040 ‡d)  
  Om beskrivningsnivån uppgraderas, lägg till denna uppgift. Vid postimport, lägg till uppgiften. Lägg inte till uppgiften när posten endast ändras utan att beskrivningsnivån uppgraderas.  
  För att lägga till Uppgraderad eller importerad av, klicka på plustecknet Lägg till egenskaper under: Post. Klicka på plustecknet till vänster vid Uppgraderad eller importerad av (Lägg till agent). Välj Skapa lokal entitet (längst ner i sidorutan till höger). Välj Bibliotek.  
  Lägg till Sigel (plustecknet Lägg till egenskap under: Bibliotek). Skriv in uppgiften.     
  ```Exempel: S``` 
  
#### Katalogiserande instans
* Katalogiserande instans (marc:catalogingSource = 008/39)  
  Normalvärdet för Libris-bibliotek är: Libris-bibliotek/Kooperativt katalogiseringsprogram
 (marc/CooperativeCatalogingProgram).   
  ```Exempel: Libris-bibliotek/Kooperativt katalogiseringsprogram```   
  För poster som skapas av NB (ej Bokinfoposter), ändra till Nationalbibliografi. För Bokinfo-poster, se nedan.  
  ```Exempel: Nationalbibliografi```   
  I Bokinfoposter och importerade poster, ändra inte postens ursprungliga kod.  
  ```Exempel: Annan verksamhet```  
  
#### Bibliografikod
* Bibliografi/Bibliotek/Sigel (bibliography/Library/sigel = 042 ‡9)  
  Observera att bibliografikod ska läggas endast av de bibliotek som arbetar med respektive bibliografi. Som exempel läggs bibliografikod NB endast av NB. För äldre tryck finns koderna COL, SOT och SB17 som används av alla bibliotek som katalogiserar äldre tryck. För en fullständig lista över sigler, se [Biblioteksdatabasen](https://biblioteksdatabasen.libris.kb.se/).  
  För att lägga till Bibliografi, klicka på plustecknet Lägg till egenskaper under: Post och välj Bibliografi. Klicka på Lägg till bibliotek (plustecknet vid Bibliografi), välj därefter Skapa lokal entitet (längst ner i sidorutan till höger).   
  Skriv in uppgiften under Sigel.  
  För att lägga in flera sigler, använd gärna Duplicera entitet och skriv in nästa sigel i den duplicerade entiteten.
 <br/>```Exempel:```
  * ```NB```
  * ```SAMB```
  
#### Systemnummer  
* Identifikator/Lokal identifikator/Värde (identifiedBy/SystemNumber/value = 035 ‡a)  
  Om ett systemnummer finns i förhandspost, till exempel Bokinfos systemnummer eller ett annat biblioteks eller bibliotekskonsortiums systemnummer, låt det vara kvar oförändrat.
  <br/>```Exempel:```
  * ```(BOKR)9789188107213```
  * ```(OCoLC)on1042213159```  
  
  För att lägga till ett lokalt systemnummer, till exempel ett DIVA-urn som systemnummer, lägg till Identifikator (plustecknet Lägg till egenskap under: Post, i Adminmetadata). Välj typ Systemnummer, under Lokal identifikator. Lägg till Värde (plustecknet vid Lokal identifikator). Fyll i aktuellt systemnummer.  
  ```Exempel: (DIVA)urn:nbn:se:su:diva-83163```  

För ISBN, se [Identifikator](#identifikator) under Instans.
  
#### Katalogiseringssprak  
* Katalogiseringsspråk (descriptionLanguage = 040 ‡b)  
  För att lägga till Katalogiseringsspråk, klicka på plustecknet Lägg till egenskaper under: Post.  
  Länka till entitet.  
  ```Exempel: svenska (swe)```

#### Katalogiseringsregler  
* Katalogiseringsregler (descriptionConventions = 040 ‡e)  
  För att lägga till Katalogiseringsregler, klicka på plustecknet Lägg till egenskaper under: Post.   
  För en post katalogiserad enligt RDA, sök fram och länka till entitet: "i" (= marc/Isbd). När man söker fram entiteten visas den som "i". I en sparad post visas samma entitet som "ISBD-interpunktion finns * i". När man skapar ny post från mall visas entiteten som "marc/Isbd". Alla är rätt.   
  Skapa också lokal entitet under Katalogiseringsregler. Klicka på plustecknet vid Katalogiseringsregler (Lägg till entitet). Välj Skapa lokal entitet (längst ner i sidorutan). Välj Katalogiseringsregler. Skriv in "rda" under Kod.      
  ```Exempel: marc/Isbd (länkad entitet) + lokal entitet, Kod: rda```

#### Beskrivningsniva  
* Beskrivningsnivå (encodingLevel = 000/17)  
För att lägga till Beskrivningsnivå, klicka på plustecknet Lägg till egenskaper under: Post.   
I samband med att du uppgraderar en Bokinfopost eller annan post med beskrivningsnivå: CIP-post eller Preliminär nivå, ändra beskrivningsnivå till annan nivå, annars kan ändringar skrivas över.  
I mallar är Miniminivå förvalt. Ändra vid behov.   
  Välj från lista.    
  ```Exempel: Biblioteksnivå```
  
#### Poststatus     
* Poststatus (000/05)  
  Uppdateras automatiskt. Ändra inte.
  <br/>```Exempel:```
  * ```Ny post```
  * ```Rättad eller reviderad post```
  
#### Systemteknisk anmarkning  
* Systemteknisk anmärkning/Benämning (technicalNote/label = 599 ‡a)  
För att lägga till Systemteknisk anmärkning, klicka på plustecknet Lägg till egenskaper under: Post, välj Systemteknisk anmärkning. Lägg till Systemteknisk anmärkning (plustecknet till vänster vid Systemteknisk anmärkning). Lägg till Benämning (plustecknet till höger vid Systemteknisk anmärkning).  
Låt anmärkning om postimport ligga kvar.  
```Exempel: Imported from: z3950cat.bl.uk:9909/BNB03U (Do not remove)``` 
 
Följande anmärkningar är under arbete och fungerar ännu inte fullt ut:  
 * Katalogisatörens anmärkning  
 * Anmärkning om katalogiseringskälla  


### Instans

#### Utgivningssatt
* Utgivningssätt (issuanceType)  
  Välj från lista.  
  ```Exempel: Seriell resurs```
  
#### Titel 

##### Nyckeltitel
* Har titel/Nyckeltitel/Huvudtitel (hasTitle/KeyTitle/mainTitle = 222 -/0 ‡a)  
För svenska seriella resurser ansvarar ISSN Sverige för nyckeltiteln.  
Skriv in uppgiften.  
 ```Exempel:  Kammarmusik-nytt ```
  
##### Huvudtitel    
* Har titel/Titel/Huvudtitel (hasTitle/Title/mainTitle = 245 ‡a)  
För att lägga till Har titel, klicka på plustecknet Lägg till egenskaper under: Post.  
  Återge huvudtiteln från titelsidan eller annan föredragen källa så som den förekommer i källan. se [Anvisningar för katalogisering - RDA](http://www.kb.se/rdakatalogisering/Anvisningar/Arbetsfloden/Tryckta-monografier/#huvudtitel "Anvisningar för katalogisering - RDA").  
  Skriv in uppgiften under Huvudtitel.      
  ```Exempel: Kammarmusik-nytt```  
  För en titel som börjar med bestämd eller obestämd artikel, ska artikeln fileras bort. Ange fileringsvärde genom att lägga till fileringsvärde (plustecknet vid Titel - Lägg till egenskaper under: Titel) och ange en siffra.  
 ```Exempel: Huvudtitel: Le bulletin France-Suède, fileringsvärde: 3```  
 Se exempel i formathandboken för Libris/Voyager: 
[Fileringsindikator]( http://www.kb.se/katalogisering/Formathandboken/Fileringsindikator/)
  
##### Övrig titelinformation (undertitel)
* Har titel/Titel/Övrig titelinformation (= Undertitel) (hasTitle/Title/subtitle = 245 ‡b)  
  Skriv in uppgiften under Övrig titelinformation. Om det finns flera undertitlar, skriv in dessa efter varandra i samma fält, åtskilda av mellanslag, kolon, mellanslag.   
  ```Exempel: Kammarmusikförbundets tidskrift```
  
##### Varianttitel   
Används till exempel för felaktigheter. Kan specificeras med Typanmärkning.  
För att lägga till varianttitel, klicka på plustecknet vid Har titel (lägg till titel) och välj typ Varianttitel.  
* Har titel/Varianttitel/Typanmärkning (hasTitle/VariantTitle/typeNote = 246 1/_ ‡i)  
 Anmärkningstext som i ett sökgränssnitt ska föregå varianttiteln. Används också för att ange typ av varianttitel som inte finns i listan, t ex Titelrubrik. Lägg vid behov till Typanmärkning (plustecknet vid Varianttitel - lägg till egenskaper under: Varianttitel, välj Typanmärkning).  
  Skriv in uppgiften.   
  ```Exempel: Titel felstavad i nummer 1 (2006):```  
* Har titel/Varianttitel/Huvudtitel (hasTitle/VariantTitle/mainTitle = 246 1/_ ‡a)  
  Skriv in uppgiften under Huvudtitel.    
  ```Exempel: Housing sarts```    
 
##### Akronymer/Del av huvudtitel  
Används för akronymer som är en del av huvudtiteln.  
* Har titel/Del av huvudtitel/Huvudtitel (hasTitle/Titleportion/mainTitle = 245 0/- ‡a)  
  Skriv in uppgiften under Huvudtitel.  
  ```Exempel: ACMO```  
  
 ##### Tidsbestämd titelvariant   
  Avser tidsbestämda titelvariationer. Volym/häfte och/eller tidsintervall preciseras under Täckning eller tillkomst (se nedan).   
* Har titel/Titelvariant/Huvudtitel (hasTitle/DistinctiveTitle/mainTitle = 246 ‡a)  
  Skriv in uppgiften under Huvudtitel.  
  ```Exempel: Hushållningssällskapets magasin```  
  
* Har titel/Titelvariant/Täckning eller tillkomst (hasTitle/DistinctiveTitle/coverage = 246 #f)  
  Skriv in uppgiften.  
  ```Exempel: 2011, nr 4-2012, nr 4``` 
  
#### Identifikator  
* Identifikator/Typ (identifiedBy)  
  Välj från lista.  
  ```Exempel: ISSN```   
* Identifikator/ISSN/Värde (identifiedBy/Issn/value = 022 ‡a)  
  Skriv in uppgiften.  
  ```Exempel: 2001-2721```  
* Identifikator/Felaktigt ISSN (identifiedBy/marc:incorrectIssn = 022 ‡y)  
  Skriv in uppgiften.   
  ```Exempel: 1653-2945```   
  
#### Utgivning
* Utgivning  
  Välj typ från lista. För seriella resurser med endast en utgivare, använd Primär utgivning.  
  
  För en seriell resurs som byter utgivare, låt Primär utgivning ligga kvar (för den första utgivningsperioden). Lägg till Utgivning för att beskriva nästa utgivningsperiod. Lägg till Sekvens av uppgifter under Utgivning och välj Nuvarande/senaste utgivare. Vid behov, ändra uppgift om Sekvens av uppgifter för mellanliggande utgivningsperioder.  
  
##### Utgivningsplats
* Plats/Plats/Benämning (= Utgivningsort) (place/label = 264 -/1 ‡a)  
  För att lägga till Plats, klicka på plustecknet vid Primär utgivning (lägg till egenskaper under Primär utgivning) och välj Plats. Sök inte efter Plats som entitet. I rutan Skapa lokal entitet, längst ner i sidorutan till höger, skriv Plats och välj det.   
  Skriv in uppgiften under Benämning.    
  ```Exempel: [Göteborg]```
  
##### Utgivningsland
* Land (country = 008/15-17)  
  Länka till entitet.  
  ```Exempel: Sverige (sw)```
  
##### Utgivarnamn
* Agent/Benämning (= Utgivarnamn) (agent/label = 264 -/1 ‡b)  
  För att lägga till Agent, klicka på Lägg till egenskaper under Primär utgivning och välj Agent. Sök inte efter Agent som entitet. I rutan Skapa lokal entitet, längst ner i sidorutan till höger, skriv Agent och välj det.       
  Skriv in uppgiften under Benämning.  
  ```Exempel: NoNa```  
  Om flera utgivare ska anges, lägg till Har del (hasPart) under Primär utgivning. Skapa Utgivning som lokal entitet (plustecknet vid Har del - Lägg till entitet). I rutan Skapa lokal entitet, längst ner i sidorutan till höger, skriv Utgivning och välj *** Utgivning. Upprepa Utgivning som lokal entitet genom att duplicera entiteten Utgivning.  
Ange Plats/Plats/Benämning och Agent/Agent/Benämning och vid behov Datum inom respektive utgivningsavsnitt (angående Datum, se anvisningar nedan). Samtliga utgivare med Plats och Agent ska ligga inom Har del/Utgivning.
Land, År och eventuellt Datum  ska ligga inom Primär utgivning.  
  Se [exempel](https://libris.kb.se/katalogisering/w4rp4hlwtr5lctjr#it).  
  
##### År och datum    
* Startår (startYear = 008/7-10)  
  Startår får endast innehålla siffror (0-9) och bokstaven u. Startår ska endast förekomma inom Primär utgivning.  
  För att ange ett startår utan klamrar eller andra tecken, ange det endast här. Det kommer då att exporteras till både marcpostens 08/07-10 och 264 -/1 ‡c. Bindestreck sätts automatiskt. För att ange årtal med klamrar eller andra tecken utöver fyra positioner, använd Datum. 
  För att lägga till Startår, klicka på plustecknet vid Primär utgivning (Lägg till egenskaper under: Primär utgivning) och välj Startår.  
  Skriv in uppgiften.  
   ```Exempel: 2011```  
* Slutår (endYear = 008/11-14)  
  Slutår får endast innehålla siffror (0-9) och bokstaven u. Slutår ska endast förekomma inom Primär utgivning.  
  För att ange ett slutår utan klamrar eller andra tecken, ange det endast här. Det kommer då att exporteras till både marcpostens 08/11-14 och 264 -/1 ‡c. Bindestreck sätts automatiskt. För att ange årtal med klamrar eller andra tecken utöver fyra positioner, använd Datum.   
  Om slutår inte anges, sätts utgivningsstatus (008/06) automatiskt till "c = Utgivning pågår".  
  Om slutår anges, sätts utgivningsstatus (008/06) automatiskt till "d = Utgivning avslutad".  
   För att lägga till Slutår, klicka på plustecknet vid Primär utgivning (Lägg till egenskaper under: Primär utgivning) och välj Startår.  
  Skriv in uppgiften.  
  ```Exempel: 2013```     
  För att ange slutår för senaste utgivningsperiod (264 -/3 ‡c), notera först vilket startåret för utgivningsperioden är, ta bort Startår och lägg till Datum. Skriv in hela datumangivelsen med startår och slutår (se nedan under Datum).    
* Datum (date = 264 -/1 ‡c)  
  Datum får innehålla text och interpunktionstecken.  
  För att ange utgivningsdatum med fler än fyra positioner, till exempel klamrade årtal, skriv in det här. Det kommer att exporteras till marcpostens  264 -/1 ‡c.  
  För att ange år utan klamrar eller andra tecken, använd endast Startår och Slutår.  
  Skriv in uppgiften.
  <br/>```Exempel:```
  * ```2012-2013```
  * ```[1988-]```

#### Frekvens   
* Frekvens (frequency)  
  * Frekvensterm (008/18)  
    Länka till entitet.  
    ```Exempel: var tredje månad (q = quarterly)```  
  * Regelbundenhet (008/19)  
    Länka till entitet.  
    ```Exempel: regelbunden (r = regular)``` 
    
#### Numrering av seriell resurs  
* Har numrering av seriell resurs/Numrering av seriell resurs/Benämning  
  (hasNumberingofSerials/NumberingofSerials/label = 362 0/- ‡a)  
  Skriv in uppgiften under Benämning.    
  ```Exempel: 2011: 4-2013: 2```

#### Medietyp
* Medietyp (mediaType/Mediatype = 337 ‡b)  
  Länka till entitet.  
  ```Exempel:  n (= omedierad)``` 
  
#### Barartyp  
* Bärartyp (carrierType/CarrierType = 338 ‡b)  
  Länka till entitet.  
  ```Exempel:  nc (= volym)```

#### Anmarkning
* Anmärkning/Anmärkning/Benämning (hasNote/Note/label = 500 ‡a)  
  Skriv in allmänna anmärkningar här.  
  Skriv in uppgiften under Benämning.  
 
#### Annat bararformat  
För seriella resurser, skapa Instans som lokal entitet under Annat bärarformat i stället för att länka direkt till annan instans. Att länka till annan instans ger felaktiga delfältskoder, vilket inte är tillåtet vid export till ISSN IC. 
* Annat bärarformat/Instans/Har titel/Titel/Huvudtitel (otherPhysicalFormat/Instance/hasTitle/Title/mainTitle = 776 ‡t)  
Lägg till Annat bärarformat. Skapa Instans som lokal entitet. Lägg till Har titel och välj Titel. Skriv in titeln under Huvudtitel.  
* Annat bärarformat/Instans/Identifikator/ISSN/Värde (otherPhysicalFormat/Instance/identifiedBy/ISSN/value = 776 ‡x)  
Lägg till Identifikator och välj ISSN. Skriv in ISSN under Värde.  
 Typanmärkning i samband med Annat bärarformat kan för närvarande inte läggas till.
  Beskriven av/Post/Kontrollnummer, motsvarande delfält w, är för närvarande låst för redigering. Det går därmed inte att lägga till fältet eller redigera det i befintliga beskrivningar.  

### Verk

* Instans av Verk/Text (instanceOf/Work/Text)  
  Skapa verket som lokal entitet (bryt inte ut verket till en länkbar entitet). Vi rekommenderar att du skapar verket som lokal entitet under den första tiden som Nya Libris är i drift. Vi återkommer med anvisningar för att skapa verk som länkbara entiteter. Denna hjälptext beskriver exempel på verk som lokal entitet. Det betyder att du anger de uppgifter som listas här nedan, under Instans av Verk, utan att klicka på länksymbolen (Länka entitet) vid Instans av Verk/Text.  
Läs mer om [Verk och Instans](https://librisbloggen.kb.se/2018/05/30/verk-och-instans-i-startversionen/).  

* Uttryck av/Verk/Har titel/Huvudtitel (hasExpression/Work/hasTitle/mainTitle = 130 0/- ‡a)  
  Under Instans av Verk/Text, lägg till Uttryck av (plustecknet vid Instans av Verk/Text - Lägg till egenskaper under: Text, välj Uttryck av).  
Skapa verk som lokal entitet (plustecknet vid Uttryck av - Lägg till verk, välj Skapa lokal entitet, längst ner i sidorutan till höger), skriv "verk" i rutan Skapa lokal entitet. Klicka på Verk. Det läggs till under Uttryck av. Klicka på plustecknet vid Verk (Lägg till egenskaper under: Verk) och välj Har titel. Välj Titel. Ta bort Övrig titelinformation.    
Skriv in uppgiften under Huvudtitel.  
```Exempel:  Architecture (Paris. 1888)```  
  
* Behandling vid titeländring (marc:typeOfEntry = 008/34)  
  Länka till entitet.  
  ```Exempel: 0 (= Successive entry = Titeländring ger upphov till ny post)```
  
#### Medverkan och funktion     
* Medverkan och funktion  
  Läs mer:  
  [Auktoritetsgruppens rekommendationer](https://kundo.se/org/librisxl/d/kbs-auktoritetsgrupp-informerar-jraz/)   
  [Lägga till Agent - Organisation](https://libris.kb.se/katalogisering/help/workflow-agent-org-instance)  
  
* Medverkan och funktion/Medverkan/Agent (contribution/Contribution/agent = 710 2/- ‡a)  
  Länka till entitet. Börja alltid med att söka efter om agenten redan finns. Vid behov, skapa ny entitet för agent (se Skapa ny agent i hjälpsektionen). I undantagsfall, skapa lokal entitet.  
  ```Exempel: Riksförbundet Sveriges kammarmusikarrangörer```  
* Medverkan och funktion/Medverkan/Agent/Funktion (contribution/Contribution/agent/role = 710 ‡4)   
  Länka till entitet. Klicka på plustecknet vid Funktion (Lägg till funktion) och sök fram funktionskod. Skriv in kod eller utskriven form i sökrutan eller tryck på mellanslagstangenten för att se alla koder. Välj kod genom att klicka på plustecknet vid koden eller på koden.    
För en sorterad lista på koder, se Formathandboken för Libris/Voyager: [Funktions- och relationskoder](http://www.kb.se/katalogisering/Formathandboken/Funktionskoder/)    
  ```Exempel:  Utgivare (pbl = publisher)```
  
#### Genre 
##### Typ av fortlöpande resurs  
* Genre/form - typ av fortlöpande resurs (genreForm/marc:Periodical = 008/21)  
  Länka till entitet.  
  För att söka efter entiteter inom Typ av fortlöpande resurs, välj Typ av fortlöpande resurs i listan över typer, under Genre/form. Trunkera genom att trycka på mellanslagstangenten eller med * i sökrutan. Välj rätt entitet genom att klicka på Lägg till.  
  ```Exempel: p (Tidskrift = marc/Periodical)```  

#### Klassifikation  
* DDK-klassifikation  
  För att lägga till DDK-klassifikation:  
  * Om posten har Klassifikation/Klassifikation (till exempel SAB-klassifikation) men saknar Klassifikation/DDK-klassifikation, lägg till ytterligare en förekomst av Klassifikation (plustecknet vid Klassifikation - lägg till klassifikation). Välj Skapa lokal entitet (längst ner i sidorutan till höger) och välj DDK-klassifikation. Skriv in uppgiften under Kod.  
  * Om posten helt saknar Klassifikation, lägg till Klassifikation genom att klicka på plustecknet vid Instans av Verk/Text (Lägg till egenskaper under: Text). Välj Klassifikation. Klicka på plustecknet vid Klassifikation (Lägg till klassifikation).  Välj Skapa lokal entitet (längst ner i sidorutan till höger) och välj DDK-klassifikation.  
   Skriv in uppgiften under Kod.  

* Klassifikation/DDK-klassifikation/Kod (classification/ClassificationDdc/code = 082 0/4 ‡a)  
  Skriv in uppgiften.  
  ```Exempel: 327.12092```
* Klassifikation/DDK-klassifikation/Klassifikationsupplaga (classification/ClassificationDdc/edition = 082 ‡2)  
  ```Exempel: full```  
*  Parallell upplagebeteckning/Upplagespecifik upphovsuppgift (classification/ClassificationDdc/editionEnumeration = 082 ‡2)  
  ```Exempel: 23/swe```  
  
##### Sekundär DDK-klassifikation  
Lägg till DDK-klassifikation (sekundär) genom att klicka på plusikonen vid Instans av Verk/Text (Lägg till egenskaper under: Text) och välja DDK-klassifikation (sekundär).  
Klicka sedan på plustecknet vid DDK-klassifikation (sekundär) (Lägg till ddk-klassifikation) och välj Skapa lokal entitet (längst ner i sidorutan till höger). Skriv in uppgiften under Kod.  
* Klassifikation/DDK-klassifikation/Kod (additionalClassificationDdc/ClassificationDdc/code = 083 0/- ‡a)  
  Skriv in uppgiften.  
  ```Exempel: 791.430233092```
* Klassifikation/DDK-klassifikation/Klassifikationsupplaga  
  (classification/ClassificationDdc/edition = 083 ‡2)  
  ```Exempel: full```  
*  Parallell upplagebeteckning/Upplagespecifik upphovsuppgift  
 (classification/ClassificationDdc/editionEnumeration = 083 ‡2)  
  ```Exempel: 23/swe``` 
   
##### SAB-klassifikation  
* SAB-klassifikation  
  För att lägga till annan klassifikation, till exempel SAB-klassifikation:  
  * Om posten har Klassifikation/DDK-klassifikation men saknar Klassifikation/Klassifikation (till exempel SAB-klassifikation), lägg till ytterligare en förekomst av Klassifikation (plustecknet vid Klassifikation - lägg till klassifikation). Välj Skapa lokal entitet (längst ner i sidorutan till höger) och välj Klassifikation. Skriv in uppgiften under Kod.  
  * Om posten helt saknar Klassifikation, lägg till Klassifikation genom att klicka på plustecknet vid Instans av Verk/Text (Lägg till egenskaper under: Text). Välj Klassifikation. Klicka på plustecknet vid Klassifikation (Lägg till klassifikation).  Välj Skapa lokal entitet (längst ner i sidorutan till höger) och välj Klassifikation.  
   Skriv in uppgiften under Kod.   
* Klassifikation/Klassifikation/Kod (classification/Classification/code = 084 0/4 ‡a)  
     Skriv in uppgiften.  
  ```Exempel: Sei-e```   
* Klassifikation/Termlista/Termlista/Kod (classification/Classification/inScheme/ConceptScheme/code = 084 ‡2)  
 ```Exempel: kssb```  
* Klassifikation/Termlista/Termlista/Version (classification/Classification/inScheme/ConceptScheme/version = 084 ‡2)  
 ```Exempel: 8``` 
 
#### Amne  
 * Ämne  
  Läs mer:  
  [Länka ämnesord](https://libris.kb.se/katalogisering/help/workflow-linked-entity-sh)   
  [Sammansatt, ej auktoriserat ämnesord](https://libris.kb.se/katalogisering/help/workflow-non-auth-sh)   
  [Kontrollerat, ej auktoriserat ämnesord](https://libris.kb.se/katalogisering/help/workflow-controlled-non-auth-sh)   
  [Okontrollerat ämnesord](https://libris.kb.se/katalogisering/help/workflow-uncontrolled-sh)

##### Allmänt ämnesord  
* Ämne/Sao-term (subject = 650 -/7 ‡a, ‡2 sao)   
  Länka till entitet.  
  ```Exempel: Kammarmusik```  
   
##### Allmänt ämnesord med underindelning   
Länka i första hand till färdiga sammansatta termer som entiteter. I övriga fall, skapa Sammansatt term som lokal entitet. (Plustecknet vid Ämne - Lägg till entitet, välj Skapa lokal entitet, längst ner i sidorutan till höger. Skriv Sammansatt term i rutan Skapa lokal entitet, välj * Sammansatt term).  
* Ämne/Sammansatt term/Termlista (subject/ComplexSubject/inScheme = ‡2 sao)   
  Under Termlista, sök fram och länka till entiteten "sao". (Plustecknet vid Termlista - Lägg till termlista, skriv sao i sökrutan Lägg till entitet, välj sao genom att klicka på plustecknet vid Svenska ämnesord (SAO), sao).  
  ```Exempel: sao```   
* Ämne/Sammansatt term/Termkomponenter/Allmänt ämnesord  
 (subject/ComplexSubject/termComponentList = 650 -/7 ‡a)      
  Under Termkomponenter, sök fram och länka till entiteten för det allmänna ämnesordet. (Plustecknet vid Termkomponenter - Lägg till entitet, välj typ Allmänt ämnesord, skriv sökbegrepp för ämnesordet i sökrutan Lägg till entitet, välj entitet genom att klicka på plustecknet vid entiteten - Lägg till.)      
  ```Exempel: Varumärken```    
* Ämne/Sammansatt term/Termkomponenter/Underindelning för allmänt ämnesord  
 (subject/ComplexSubject/termComponentList = 650 ‡x)   
  Under Termkomponenter, sök fram och länka till entiteten för det allmänna ämnesordet. (Plustecknet vid Termkomponenter - Lägg till entitet, välj typ Underindelning för allmänt ämnesord, skriv sökbegrepp för ämnesordet i sökrutan Lägg till entitet, välj entitet genom att klicka på plustecknet vid entiteten - Lägg till.)  
  ```Exempel: juridik och lagstiftning```   
  
##### Geografiskt ämnesord  
* Geografiskt ämnesord (subject = 651 -/4 ‡a)  
  Sök fram och länka till entitet.  
  I undantagsfall, skapa lokal entitet och skriv in uppgiften.  
  ```Exempel: Sverige```
  
##### Geografiskt ämnesord med geografisk underindelning  
Skapa Sammansatt term som lokal entitet. (Plustecknet vid Ämne - Lägg till entitet, välj Skapa lokal entitet, längst ner i sidorutan till höger. Skriv Sammansatt term i rutan Skapa lokal entitet, välj * Sammansatt term).  
* Ämne/Sammansatt term/Termlista (subject/ComplexSubject/inScheme = ‡2 sao)   
  Under Termlista, sök fram och länka till entiteten "sao". (Plustecknet vid Termlista - Lägg till termlista, skriv sao i sökrutan Lägg till entitet, välj sao genom att klicka på plustecknet vid Svenska ämnesord (SAO), sao).  
  ```Exempel: sao```  
* Ämne/Sammansatt term/Termkomponenter/Geografiskt ämnesord/Föredragen benämning  
 (subject/ComplexSubject/termComponentList/Geographic/prefLabel)  
 Under Termkomponenter, skapa Geografiskt ämnesord som lokal entitet. (Plustecknet vid Termkomponenter - Lägg till entitet. I  rutan Skapa lokal entitet, längst ner i sidorutan till höger, skriv Geografiskt ämnesord och välj det). Skriv in det geografiska ämnesordet under Föredragen benämning.    
  ```Exempel: Tyskland```  
* Ämne/Sammansatt term/Termkomponenter/Underindelning för geografisk term/Föredragen benämning   
 (subject/ComplexSubject/termComponentList/GeographicSubdivision/prefLabel)  
  Under Termkomponenter, skapa Underindelning för geografisk term som lokal entitet. (Plustecknet vid Termkomponenter - Lägg till entitet. I rutan Skapa lokal entitet, längst ner i sidorutan till höger, skriv Underindelning för geografisk term och välj det). Skriv in termen för den geografiska underindelningen under Föredragen benämning.  
  ```Exempel: Bonn``` 
   
##### Ämnesord Organisation  
* Ämne/Agent/Organisation (subject/agent/Organization = 610 2/- ‡a)  
Länka till entitet. Börja alltid med att söka efter om agenten redan finns. Vid behov, skapa ny entitet för agent (se Skapa ny agent i hjälpsektionen). I undantagsfall, skapa lokal entitet.   
```Exempel: Svenska Röda korset```  
Läs mer:  
  [Auktoritetsgruppens rekommendationer](https://kundo.se/org/librisxl/d/kbs-auktoritetsgrupp-informerar-jraz/)   
  [Lägga till Agent - Organisation](https://libris.kb.se/katalogisering/help/workflow-agent-org-instance)   

#### Genre 
##### Typ av fortlöpande resurs  
* Genre/form - typ av fortlöpande resurs (genreForm/marc:Periodical = 008/21)  
  Länka till entitet.  
  För att söka efter entiteter inom Typ av fortlöpande resurs, välj Typ av fortlöpande resurs i listan över typer, under Genre/form. Trunkera genom att trycka på mellanslagstangenten eller med * i sökrutan. Välj rätt entitet genom att klicka på Lägg till.  
  ```Exempel: p (Tidskrift = marc/Periodical)```  
  
 ##### Konferenspublikation  
* Genre/form – konferenspublikation (genreForm = 008/29)  
  Länka till entitet.  
  För att söka efter entiteter inom Konferenspublikation, välj Konferenspublikation i listan över typer, under Genre/form. Trunkera genom att trycka på mellanslagstangenten eller med * i sökrutan. Välj rätt entitet genom att klicka på Lägg till.  
  ```Exempel: Ja, resursen härrör från konferens```      
     
#### Sprak
* Språk (language = 008/35-37)  
  Länka till entitet.  
  ```Exempel: svenska (swe)```  
   För att ange att texten är på flera språk, t ex parallelltext, ange ytterligare en språkkod genom att klicka på plustecknet vid Språk (Lägg till språk) och söka fram ytterligare en entitet för ett språk och länka till den.  
  
#### Alfabet    
* Alfabet/skriftart (marc:alphabet = 008/33)   
  Länka till entitet.  
  ```Exempel: b (= Extended roman = Latinskt alfabet med diakriter och specialtecken (a-ö))```
  
#### Innehallstyp
* Innehållstyp (contentType/ContentType = 336 ‡b)  
  Länka till entitet.  
  ```Exempel: text (txt)```
  
#### Relationer under verk
* Länkfält/relationer under verk: Fortsätter (780 0/0), Fortsättes av (785 0/0), Ersätter (780 0/2), med flera -   
  konstrueras enligt följande mönster. Ange relationen, skapa verket som lokal instans och skapa en lokal instans av verket, ange egenskaper för instansen, till exempel titel och identifikator, se nedan.  
  Under Instans av Verk, lägg till egenskaper genom att klicka på plustecknet vid Instans av Verk/Text (Lägg till egenskaper under: Text). Välj till exempel Fortsätter (eller Fortsättes av eller annan relation) och lägg till det. Skapa ett verk som lokal entitet genom att klicka på plustecknet vid Fortsätter. Klicka på Skapa lokal entitet. Välj Verk i listan. Skapa en instans av verket genom att klicka på plustecknet vid Verk (Lägg till egenskaper under: Verk) och lägg till Har instans. Klicka på plustecknet vid Har instans och skapa instansen som lokal entitet (klicka på Skapa lokal entitet och välj Instans). 
  
* Fortsätter/Verk/Har instans/Instans/Har titel/Titel (780 0/0 ‡t)  
  För att lägga till titel under Fortsätter, Fortsättes av, Ersätter, med flera:  
  Klicka på plustecknet vid Instans (Lägg till egenskaper under: Instans) och lägg till Har titel. Välj Titel. Ta bort Övrig titelinformation. Under Huvudtitel, skriv in uppgiften.  
```Exempel: Aktuellt magazin```  
  
* Fortsätter/Verk/Har instans/Instans/Identifikator/ISSN/Värde (780 0/0 ‡x)  
 För att lägga till ISSN för den resurs man länkar till, under Fortsätter, Fortsättes av, Ersätter, med flera, klicka på plustecknet vid Instans (lägg till egenskaoer under: Instans) och lägg till Identifikator (identifiedBy). Välj typ ISSN. Skriv in ISSN under Värde.  
```Exempel: 1402-1250```

* Fortsätter/Verk/Har instans/Instans/Beskriven av/Post/Kontrollnummer (780 0/0 ‡w)  
  Beskriven av/Post/Kontrollnummer, motsvarande delfält w, är för närvarande låst för redigering. Det går därmed inte att lägga till egenskapen eller redigera den i befintliga beskrivningar.  

  Hör följer ett urval av de relationer som kan läggas till, enligt samma mönster som Fortsätter (se ovan), under Instans av Verk:  
  
  Fortsätter (continues = 780 0/0)  
  Fortsätter delvis (continuesInPartBy = 780 0/1)  
  Föregående (precededBy = 780 0/2)  
  Ersätter delvis (precededInPartBy = 780 0/3)  
  Sammanslagen med (mergerOf = 780 0/4)  (se [Exempel](https://libris.kb.se/katalogisering/5ng67r2h49lzkl9#it))  
  Har införlivat (absorbed = 780 0/5)  
  Har delvis införlivat (absorbedInPart = 780 0/6)  
  Separerad från (separatedFrom = 780 0/7)  
  
  Fortsättes av (continuedBy = 785 0/0)  
  Fortsättes delvis av (continuedInPartBy = 785 0/1)  
  Efterföljande (succeededBy = 785 0/2)  
  Ersättes delvis av (succeededInPartBy = 785 0/3)  
  Har uppgått i (absorbedBy = 785 0/4)  
  Har delvis uppgått i (absorbedInPartBy = 785 0/5)  
  Uppdelat på (splitInto = 785 0/6)  
  Sammanslagen till (mergedToForm = 785 0/7)  (se [Exempel](https://libris.kb.se/katalogisering/tb4vcdf54hzlsr3#it))  
