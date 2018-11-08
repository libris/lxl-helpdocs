
## Musiktryck

Denna hjälptext beskriver ett antal vanligt förekommande egenskaper, med utgångspunkt från exempel. För instruktioner om att länka till entitet, skapa lokal entitet och om hur formuläret fungerar i övrigt, se Redigering i vänstermenyn. För information om katalogregler, skrivregler och övriga katalogiseringsanvisningar, se [Anvisningar för katalogisering - RDA](http://www.kb.se/rdakatalogisering/Anvisningar/Arbetsfloden/Tryckta-monografier/ "Anvisningar för katalogisering - RDA").

Se även [instruktionsfilmer](https://www.youtube.com/playlist?list=PLZVkEICvA5-GRT2oJQmLgq_2Pksx6zYPy)  

I de flesta fall ska informationen delas upp i olika egenskaper (jfr fält) och underliggande egenskaper (jfr delfält). I några undantagsfall är det nödvändigt att använda ISBD-interpunktion i inom en egenskap, för att separera uppgifter. Dessa fall visas genom exempel nedan. I övriga fall, lägg inte in ISBD-interpunktion för att avsluta en egenskap (fält). Använd vid behov klamrar inom egenskap (fält), enligt Anvisningar för katalogisering - RDA.

I vissa fall fungerar det ännu inte fullt ut att lägga till alla uppgifter som beskrivs i denna hjälptext. Arbete pågår med förbättra gränssnittet. För att anmäla fel, använd detta formulär för [felrapportering](https://docs.google.com/forms/d/e/1FAIpQLSfOChJOGDoHUQguSF83F5XyTZiQL-yU47nvcqb6qwNT9GX7Aw/viewform). För att lämna synpunkter, använd detta formulär för  [ändringsförslag](https://docs.google.com/forms/d/e/1FAIpQLScgz_0enebhBn6uB8xvowkDBB4ax_dbvaobLSFfqFMoty6eQg/viewform).  


### Innehåll   

| [Adminmetadata](#adminmetadata) | [Instans](#instans) | [Verk](#verk) | 
| ------ | ----------- |  ----------- |
| [Skapad av](#skapad-av) | [Utgivningssätt](#utgivningssatt) | [Verkets titel](#verkets-titel) |
| [Uppgraderad eller importerad av](#uppgraderad-eller-importerad-av) | [Titel](#titel) | [Språk](#sprak) |
| [Katalogiserande instans](#katalogiserande-instans) | [Upphovsuppgift](#upphovsuppgift) | [Medverkan och funktion](#medverkan-och-funktion) |
| [Poststatus](#poststatus) | [Identifikator](#identifikator) | [Klassifikation](#klassifikation) |
| [Systemnummer](#systemnummer) | [Upplageuppgift](#upplageuppgift) | [Ämne](#amne) |
| [Katalogiseringsspråk](#katalogiseringssprak) | [Utgivning](#utgivning) | [Genre](#genre) |
| [Katalogiseringsregler](#katalogiseringsregler) | [Tillverkning](#tillverkning) | [Innehållstyp](#innehallstyp) |
| [Beskrivningsnivå](#beskrivningsniva) | [Copyrightår](#copyrightar) | |
| [Bibliografikod](#bibliografikod) | [Omfång](#omfang) | |
| [Systemteknisk anmärkning](#systemteknisk-anmarkning) | [Övriga fysiska detaljer](#ovriga-fysiska-detaljer) | |
| | [Mått](#matt) | |
| | [Bilagor](#bilagor) | |
| | [Medietyp](#medietyp) | |
| | [Bärartyp](#barartyp) | |
|  | [Seriemedlemskap](#seriemedlemskap) | |
| | [Anmärkning](#anmarkning) | |
|  | [Innehållsanmärkning](#innehallsanmarkning) | |
| | [Målgruppsanmärkning](#malgruppsanmarkning) | |
| | [Annat bärarformat](#annat-bararformat) | | 


### Adminmetadata  
#### Skapad av  
* Skapad av/Organisation/Namn (descriptionCreator/Organization/name = 040 ‡a)  
  Förval: den sigel som skapat posten. Ska inte ändras.  
  ```Exempel: BOKR```  
  Vid postimport: för närvarande hamnar det importerande bibliotekets sigel här. Detta kommer att ses över.  
  
#### Uppgraderad eller importerad av  
* Uppgraderad eller importerad av/Bibliotek/Sigel (descriptionUpgrader/Library/sigel = 040 ‡d)  
  Om beskrivningsnivån uppgraderas, lägg till denna uppgift. Vid postimport, lägg till uppgiften. Lägg inte till uppgiften när posten endast ändras utan att beskrivningsnivån uppgraderas.  
  För att lägga till Uppgraderad eller importerad av, klicka på plustecknet Lägg till egenskaper under: Post. Klicka på plustecknet till vänster vid Uppgraderad eller importerad av (Lägg till agent). Välj Skapa lokal entitet (längst ner i sidorutan till höger). Välj Bibliotek.  
  Lägg till Sigel (plustecknet Lägg till egenskap under: Bibliotek). Skriv in uppgiften.     
  ```Exempel: S```  
  
#### Entry map  
* Entry map (marc:entryMap = 000/20-23)  
I vissa importerade poster förekommer Entry map. Låt det vara kvar oförändrat.  

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
  ```Exempel: (BOKR)9789188107213```  
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
I samband med att du uppgraderar en Bokinfopost eller annan post med beskrivningsnivå: CIP-post (000/17: 8) eller Preliminär nivå (000/17: 5), ändra beskrivningsnivå till någon annan nivå (vanligen Miniminivå, Biblioteksnivå eller Nationalbibliografisk nivå), annars kan ändringar skrivas över.  
Vid postimport kan beskrivningsnivå ibland saknas eller sakna värde. Lägg då dit beskrivningsnivå och välj värde.    
I mallar är Miniminivå förvalt. Ändra vid behov.  
  Välj från lista.    
  ```Exempel: Biblioteksnivå```  
  
#### Translitterering
* Institution som gjort translitterering (marc:transcribingAgency = 040 ‡c)  
   Sigel för det bibliotek som translittererat posten till maskinläsbar form. Låt det vara kvar oförändrat.  
   
#### Poststatus     
* Poststatus (recordStatus = 000/05)  
  Uppdateras automatiskt. Ändra inte.
  <br/>```Exempel:```
  * ```Ny post```
  * ```Rättad eller reviderad post```
 
#### Systemteknisk anmarkning  
* Systemteknisk anmärkning/Benämning (technicalNote/label = 599 ‡a)  
För att lägga till Systemteknisk anmärkning, klicka på plustecknet Lägg till egenskaper under: Post, välj Systemteknisk anmärkning. Lägg till Systemteknisk anmärkning (plustecknet till vänster vid Systemteknisk anmärkning). Lägg till Benämning (plustecknet till höger vid Systemteknisk anmärkning).  
Låt anmärkning om postimport ligga kvar.  
```Exempel: Imported from: z3950cat.bl.uk:9909/BNB03U (Do not remove)```  

  I samband med att du uppgraderar en Bokinfopost eller annan post med beskrivningsnivå: CIP-post eller Preliminär nivå, ändra beskrivningsnivå till annan nivå, annars kan ändringar skrivas över. Ta därefter bort systemteknisk anmärkning med innehåll:  
```Exempel: Maskinellt genererad post. Ändra kod för fullständighetsnivå (leader/17), annars kommer manuellt gjorda ändringar att försvinna.```   
 
Följande anmärkningar är under arbete och fungerar ännu inte fullt ut:  
 * Katalogisatörens anmärkning  
 * Anmärkning om katalogiseringskälla  
 

### Instans
#### Utgivningssatt
* Utgivningssätt (issuanceType)  
  Välj från lista.  
  ```Exempel: Monografisk resurs```
  
#### Medietyp
* Medietyp (mediaType/Mediatype = 337 ‡b)  
  Länka till entitet.  
  ```Exempel: n (= omedierad)```  
  
#### Barartyp
* Bärartyp (carrierType/CarrierType = 338 ‡b)  
  Länka till entitet.  
  ```Exempel: nc (= volym)```  
  
#### Titel  

##### Huvudtitel    
* Har titel/Titel/Huvudtitel (hasTitle/Title/mainTitle = 245 ‡a)  
  För att lägga till Har titel, klicka på plustecknet Lägg till egenskaper under: Post.  
  Återge huvudtiteln från titelsidan eller annan föredragen källa så som den förekommer i källan. se [Anvisningar för katalogisering - RDA](http://www.kb.se/rdakatalogisering/Anvisningar/Arbetsfloden/Tryckta-monografier/#huvudtitel "Anvisningar för katalogisering - RDA").  
  Skriv in uppgiften.
  <br/>```Exempel:```
  * ```Lichtbogen```
  * ```Quartett Nr. 2 op. 92 für 2 Violinen, Viola und Violoncello```  
  För en titel som börjar med bestämd eller obestämd artikel, ska artikeln fileras bort. Ange fileringsvärde genom att lägga till fileringsvärde (plustecknet vid Titel - Lägg till egenskaper under: Titel) och ange en siffra.  
  ```Exempel: Huvudtitel: The best of Heavy metal, fileringsvärde: 4```  
  Se exempel i formathandboken för Libris/Voyager: 
[Fileringsindikator](http://www.kb.se/katalogisering/Formathandboken/Fileringsindikator/)

##### Övrig titelinformation (undertitel)
* Har titel/Titel/Övrig titelinformation (= Undertitel) (hasTitle/Title/subtitle = 245 ‡b)  
  Skriv in uppgiften. Om det finns flera undertitlar, skriv in dessa efter varandra i samma fält, åtskilda av mellanslag, kolon, mellanslag.
  <br/>```Exempel:```
  * ```for nine musicians and live electronics```
  * ```auf kabardinische Themen```
  
För att ange föredragen titel (=uniform titel), se Verk/Har titel/Titel/Huvudtitel.  

För Varianttitel och andra titelvarianter, se hjälptexten för Tryckt monografi:
[Varianttitel](https://libris.kb.se/katalogisering/help/workflow-print-monograph#titel-varianttitel)
  
#### Upphovsuppgift
* Upphovsuppgift (responsibilityStatement = 245 ‡c)  
  För att lägga till upphovsuppgift, klicka på plustecknet Lägg till egenskaper under: Instans.  
  Vid postimport: i vissa importerade poster saknas upphovsuppgift. Lägg då till det.   
  Skriv in uppgiften.
  <br/>```Exempel:```
  * ```Kaija Saariaho```
  * ```Sergej Prokofjew```
  * ```Ludwig van Beethoven ; herausgegeben von Rainer Cadenbach```
  
#### Upplageuppgift  
* Upplageuppgift (editionStatement = 250 ‡a)  
  Skriv in upplagebeteckning här. Om de anges i källan ange även uppgifter om musikalietyp (partitur, klaverutdrag) och sättning (låg/hög röst) här.
  <br/>```Exempel:```
  * ```New edition```
  * ```Urtext```
  * ```Voix élevée```
  * ```Vocal score```    
* Påföljande upplageuppgift (editionStatementRemainder = 250 ‡b)  
Skriv in uppgifter som följer omedelbart efter upplagebeteckningen här.  
  ```Exempel: prepared by Imogen Holst & Colin Matthews```  

#### Utgivning  
* Utgivning (publication)  
  Välj typ från lista. För monografier, använd Primär utgivning.     
  I konverterade och maskininlästa poster finns det ibland två avsnitt: ett Primär utgivning med År och Land, och ett Utgivning med Plats, Agent och Datum. När man redigerar maskininlästa poster med två utgivningsavsnitt får man, om man bedömer det nödvändigt, flytta uppgifterna om Plats, Agent och Datum till avsnittet Primär utgivning och ta bort avsnittet Utgivning.   
NB inväntar en maskinell ändring av dessa poster och ändrar inte manuellt.    
  Vid postimport: I importerade poster förekommer ibland både År och Copyrightår inom Utgivning (= 008/06: t, 008/07-10: År och 008/11-14: Copyrightår). Låt uppgiften ligga kvar oförändrad.      
Om posten är katalogiserad enligt RDA kan även Copyright/Copyright/Datum (copyright/Copyright/date = 264 -/4 ‡c) finnas med.  
 
 ##### Utgivningsplats  
 * Plats/Plats/Benämning (= Utgivningsort) (place/label = 264 -/1 ‡a)  
  För att lägga till Plats, klicka på plustecknet vid Primär utgivning (lägg till egenskaper under Primär utgivning) och välj Plats. Sök inte efter Plats som entitet. I rutan Skapa lokal entitet, längst ner i sidorutan till höger, skriv Plats och välj det.   
  Skriv in uppgiften under Benämning. Klamra vid behov.  
  ```Exempel: [Wiesbaden]```  
 
 ##### Utgivarnamn  
  * Agent/Agent/Benämning (= Utgivarnamn) (agent/label = 264 -/1 ‡b)  
  För att lägga till Agent, klicka på Lägg till egenskaper under Primär utgivning och välj Agent. Sök inte efter Agent som entitet. I rutan Skapa lokal entitet, längst ner i sidorutan till höger, skriv Agent och välj det.       
  Skriv in uppgiften under Benämning.  
  ```Exempel: Breitkopf & Härtel```   
  Om flera utgivare ska anges, lägg till Har del (hasPart) under Primär utgivning. Skapa Utgivning som lokal entitet (plustecknet vid Har del - Lägg till entitet). I rutan Skapa lokal entitet, längst ner i sidorutan till höger, skriv Utgivning och välj *** Utgivning. Upprepa Utgivning som lokal entitet genom att duplicera entiteten Utgivning.  
Ange Plats/Plats/Benämning och Agent/Agent/Benämning och vid behov Datum inom respektive utgivningsavsnitt (angående Datum, se anvisningar nedan). Samtliga utgivare med Plats och Agent ska ligga inom Har del/Utgivning.
Land, År och eventuellt Datum ska ligga inom Primär utgivning.  
  Se [exempel](https://libris.kb.se/katalogisering/w4rp4hlwtr5lctjr#it).
  
 ##### År och datum 
  * År (= Utgivningstid) (date = 008/07-10, 264 -/1 ‡c)  
  År får endast innehålla siffror (0-9) och bokstaven u. År ska endast förekomma inom Primär utgivning.  
  Ange utgivningsår, utan klamrar eller andra tecken, endast fyra positioner. Skriv in uppgiften.  
  För att ange ett år utan klamrar eller andra tecken, ange det endast här. Det kommer då att exporteras till både marcpostens 08/07-10 och 264 -/1 ‡c. För att ange årtal med klamrar eller andra tecken utöver fyra positioner, använd Datum.  
  ```Exempel: 2017```  
  * Datum (= Utgivningstid) (date = 264 -/1 ‡c)  
  Datum får innehålla text och interpunktionstecken.  
  För att ange ett utgivningsdatum med fler än fyra positioner, till exempel ett klamrat årtal, skriv in det här. Det kommer att exporteras till marcpostens  264 -/1 ‡c. Skriv in uppgiften.  
  För att ange ett år utan klamrar eller andra tecken, använd endast År.  
  Skriv in uppgiften.
  <br/>```Exempel:```
    * ```[2017]```
    * ```[mellan 1863 och 1866?]```
  
* Flera år (flerbandsverk)  
  Använd Startår och Slutår (inte År). För att lägga till Startår och Slutår, klicka på plustecknet vid Primär utgivning (Lägg till egenskaper under: Primär utgivning) och välj Startår respektive Slutår. Egenskaperna ska ligga i avsnittet Primär utgivning. Om årtalen anges utan klammer eller andra tecken utöver fyra positioner, räcker det att ange årtalen här. De exporteras då både som 008 och 264 ‡c. Bindestreck sätts automatiskt. För att få rätt kod i 008/06 (Typ av utgivningsdatum/Utgivningsstatus) vid MARC-export: lägg till Typ av utgivningsdatum (marc:publicationStatus) (klicka på plustecknet vid Primär utgivning) och välj ”Flera årtal (monografisk resurs)".
 <br/>```Exempel:```
  * ```Startår: 1999```
  * ```Slutår: 2017```
  * ```Typ av utgivningsdatum: Flera årtal (monografisk resurs)``` 

 Läs mer om [År och Datum](https://kundo.se/org/librisxl/d/falt-for-utgivningsar/)  
 
##### Utgivningsland  
 * Land (country = 008/15-17)  
  Länka till entitet.  
  ```Exempel: Sverige (sw)```  
  
#### Tillverkning 
* Tillverkning (manufacture)  

##### Tillverkningsplats (Tillverkningsort) 
* Plats/Plats/Benämning (place/label = 264 -/3 ‡a)  
  ```Exempel: Falun```  
##### Tillverkningsnamn  
* Agent/Agent/Benämning (agent/label = 264 -/3 ‡b)  
  Skriv in uppgiften.   
  ```Exempel: Scandbook```   
##### Tillverkningstid   
* Datum (= Tillverkningstid) (date = 264 -/3 ‡c)  
  Skriv in uppgiften. Klamra vid behov.
  <br/>```Exempel:```
  * ```2017```
  * ```[2017]```
  
#### Copyrightar   
* Copyright/Copyright/Datum (copyright/Copyright/date = 264 -/4 ‡c)  
  För musiktryck anges alltid copyrightår om det skiljer sig från utgivningstid (om de sammanfaller anges endast utgivningsår). Ange endast senaste copyrightåret.  
  Skriv in uppgiften. För att få fram copyrighttecknet, kopiera från exemplet nedan eller skriv Alt + 184.  
  Se också [Specialtecken](https://libris-dev.kb.se/katalogisering/help/search-04-special-chars). Du kan t ex söka på teckenuppsättning i “Sök i windows” och öppna programmet, markera och kopiera tecknet och sedan klistra in det.  
  ```Exempel: ©2017```  

#### Identifikator 
* Identifikator (identifiedBy)  
  Välj typ från lista.  
  ```Exempel: ISBN```
* Identifikator/ISBN/Värde (identifiedBy/Isbn/value = 020 ‡a)  
  Skriv in uppgiften.  
  ```Exempel: 9789188107213```
* Identifikator/Särskiljande tillägg (= Bestämning) (identifiedBy/qualifier = 020 ‡q)  
  Skriv in uppgiften.  
  ```Exempel: inbunden```  

För ogiltiga ISBN, använd Indirekt identifierad av, direkt under Instans. Använd inte Ogiltigt värde under Identifikator/ISBN (identifiedBy/marc:hiddenValue).  
  
* Identifikator/ISMN/Värde (identifiedBy/ISMN/value = 024 2 _ ‡a)
  Skriv in uppgiften.  
  ```Exempel: 9790006466641```  
* Identifikator/Plåtnummer/Värde (identifiedBy/MusicPlate/value = 028 2 1 ‡a)  
  Skriv in uppgiften.  
  ```Exempel: N.M.S. 1090```
* Identifikator/Editionsnummer  
  o Värde (identifiedBy/MusicPublisherNumber/value = 028 3 1 ‡a)
  Skriv in uppgiften.  
  ```Exempel: HN 6027```  
  o Agent/organisation/namn (identifiedBy/MusicPublisherNumber/agent/Organization/name = 028 3 1 ‡b)  
  Skriv in förlagets namn, om det anges i omedelbar anslutning till editionsnumret.  
  ```Exempel: Henle```

#### Indirekt identifierad av  
Ange ogiltiga ISBN här och inte under Identifikator/ISBN/Ogiltigt värde.  
Lägg till genom att klicka på Lägg till egenskaper under: Instans, sök upp "Indirekt identifierad av" och klicka på termen.
* Indirekt identifierad av/ISBN (indirectlyIdentifiedBy/ISBN = 020 ‡z)  
  Välj typ från lista.  
  ```Exempel: ISBN```  
* Indirekt identifierad av/ISBN/Värde (indirectlyIdentifiedBy/Isbn/value = 020 ‡a)    
  Skriv in uppgiften.  
  ```Exempel: 97891881072```  
* Indirekt identifierad av/Särskiljande tillägg (= Bestämning) (indirectlyIdentifiedBy/qualifier = 020 ‡q)   
  Skriv in uppgiften.  
  ```Exempel: inbunden```  

#### Omfang   
* Omfång/Omfång/Benämning (extent/Extent/label = 300 ‡a)  
  Skriv in uppgiften. 
  <br/>```Exempel:```
  * ```112 sidor```
  * ```1 partitur (ix, 43 sidor)```
  * ```1 klaverutdrag (18 sidor) + 2 stämmor```
    
#### Ovriga fysiska detaljer
* Övriga fysiska detaljer (other physical details = 300 ‡b)  
  Skriv in uppgiften.  
  ```Exempel: faksimil```  

#### Matt 
* Mått/Mått/Benämning (hasDimensions/Dimensions/label = 300 ‡c)  
  Skriv in uppgiften.  
  ```Exempel: 24 cm```  
  
#### Bilagor
* Tillsammans med/Instans/Benämning (Bilagor) (accompaniedBy/Instance/label = 300 ‡e) 
För att lägga till Tillsammans med, klicka på plustecknet Lägg till egenskaper under: Post och välj Tillsammans med. Skapa Instans som lokal entitet. (Plustecknet vid Tillsammans med, välj Skapa lokal entitet, längst ner i sidorutan till höger, skriv Instans och välj ** Instans.) Lägg till Benämning (plustecknet vid Instans - Lägg till egenskaper under: Instans).    
Skriv in uppgiften.  
  ```Exempel: 1 CD```  

#### Seriemedlemskap
* Seriemedlemskap/Seriemedlemskap/Ingår i serie (seriesMembership/SeriesMembership/inSeries)  
  Avvakta med att skapa verk som länkade entiteter. Beskriv serien som lokal entitet, enligt följande instruktion.  
  *Nytt 2018-10-04:*   
  * Man måste inte längre fylla i två Seriemedlemskap för att vid export till MARC få ut både 490 och 830.  
  * Vid export till marc21 skapas både 490 och 830 (800/810) från Seriemedlemskap som saknar Serieuppgift (t ex gamla 440-fält). OBS. Hanteringen klarar de flesta fall bra, men det finns serier med deltitlar/delserier som kommer att exporteras fel (fel ordning mellan Delbeteckning och Deltitel, fel interpunktion). Om man stöter på sådana, och anser felet besvärande, får man gå in i posten och lägga till en korrekt Serieuppgift i rätt Seriemedlemskap. Då kommer 490 att skapas från det. (Finns det flera Seriemedlemskap behöver man komplettera alla, annars skapas bara 490 för den serien som har en ifylld Serieuppgift).  

Läs mer om [Seriemedlemskap](https://kundo.se/org/librisxl/d/uppgifter-om-seriemedlemskap-saknas-i-marc-export/)  
     
##### Seriens titel (auktoriserad sökingång för serie)  
* Seriemedlemskap/Ingår i serie/Instans av Verk/Verk/Har titel/Titel/Huvudtitel (seriesMembership/inSeries/InstanceofWork/Work/hasTitle/Title/mainTitle = 830 ‡a)  
  Ange den auktoriserade sökingången för serien här (gäller serier som har seriehuvudpost) i de fall den avviker från serieuppgiften. Om endast Serieuppgift men inte Ingår i serie/Instans av Verk/Verk finns, t ex i en förhandspost från Bokinfo, fungerar det för närvarande bäst att skapa ett helt nytt seriemedlemskap och flytta över Serieuppgift dit. Ange sedan den auktoriserade sökingången för serien under Seriemedlemskap/Ingår i serie/Instans av Verk/Verk/Har titel/Titel/Huvudtitel. Ta bort det första seriemedlemskapet så att endast ett seriemedlemskap återstår.  
  Skriv in uppgiften.   
  ```Exempel: Neue Ausgabe sämtlicher Werke. Serie 2, Kammermusik```  
##### ISSN  
* Seriemedlemskap/Ingår i serie/Instans/Identifikator/ISSN/Värde (seriesMembership/inSeries/Instance/identifiedBy/ISSN/Value) (490 ‡x, 830 ‡x)  
  Skriv in uppgiften.  
  ```Exempel: 1103-498X```     
##### Serieuppgift  
* Seriemedlemskap/Serieuppgift (seriesMembership/seriesStatement = 490 ‡a)  
  Skriv in uppgiften.  
   ```Exempel: Neue Ausgabe sämtlicher Werke. Serie 2, Kammermusik```   
##### Numrering inom serie  
* Seriemedlemskap/Numrering inom serie (seriesMembership/seriesEnumeration = 490 ‡v, 830 ‡v)  
  Skriv in uppgiften.  
  ```Exempel: 8```  
##### Indikator för seriebiuppslag   
* Seriemedlemskap/Indikator för seriebiuppslag (marc:seriesTracingPolicy = 490 i1: 0/1)  
  Ange indikator 0 om endast serieuppgift samt eventuellt ISSN och eventuell numrering inom serie ska anges (om det inte finns en seriehuvudpost).   
  Skriv in uppgiften.  
  ```Exempel: 0```   
  Ange indikator 1 om dessutom Instans/Instans av Verk/Verk (830) anges (om det finns en seriehuvudpost).   
  ```Exempel: 1```   

*Seriemedlemskap, vid postimport:* Om fält 490 ‡a och 830 ‡a matchar, läggs de vid import i samma Seriemedlemskap. Om de inte matchar, skapas två Seriemedlemskap: ett med Seriemedlemskap/Serieuppgift och ett med Seriemedlemskap/Ingår i serie/Instans av Verk/Verk/Har titel/Titel/Huvudtitel.  
När man redigerar importerade poster med två Seriemedlemskap får man, om man bedömer det nödvändigt, slå ihop dem till ett genom att lägga till Serieuppgift och Indikator för seriebiuppslag i det Seriemedlemskap som innehåller Seriemedlemskap/Ingår i serie/Instans av Verk/Verk/Har titel/Titel/Huvudtitel.  
Om man försöker göra tvärt om och lägga till Instans av Verk i ett Seriemedlemskap så orsakar en bugg att detta kopplas till Instans av Verk/Text (överst i beskrivningen) och det går sedan inte att ändra. I dessa fall måste Seriemedlemskapet tas bort i sin helhet och ett nytt läggas till och fyllas i.  
OBS! Om ISSN finns i både 490 och 830 och om volymbeteckningen är angiven på olika sätt i 490 och 830, dubbleras dessa inom Seriemedlemskapet. Radera en av de dubblerade ISSN- och/eller voIymbeteckningarna.  
  
#### Anmarkning
* Anmärkning/Anmärkning/Benämning (hasNote/Note/label = 500 ‡a)   
  Skriv in allmänna anmärkningar här.    
  Skriv in uppgiften.
  <br/>```Exempel:```
  * ```Med realiserad, ej besiffrad, b.c.-stämma```
  * ```Noter med övnings-cd typ ”Music minus one”```
  * ```Speltid: 21 min.```

#### Innehallsanmarkning  
* Har innehållsförteckning/Innehållsförteckning/Benämning (tableofContents = 505 8/_)  
  Musik- och teaterbiblioteket rekommenderar enkel innehållsanmärkning för musiktryck.  
  För en enkel innehållsanmärkning (505 ‡a), lägg till Har innehållsförteckning (från Lägg till egenskaper under: Instans). Lägg därefter till Innehållsförteckning (plustecknet under Har innehållsförteckning i vänstermenyn). Skriv in uppgiften under Benämning. 
  <br/>```Exempel:```
  * ```Concerto nach italienischem Gusto, BWV 971 ; Ouverture nach französischer Art, BWV 831 ; Appendix: Ouverture in c, BWV 831a```
  * ```Chain of fools / Donald Covay -- A deeper love / David Cole, Robert Clivilles -- Do right woman, do right man / Chips Moman, Dan Penn -- I knew you were waiting (for me) / Dennis Morgan, Simon Climie```

* Har innehållsförteckning/Innehållsförteckning/Har del/Utökad innehållsanmärkning/Benämning/Upphovsuppgift (tableofContents = 505 8/0 ‡t, ‡r)  
  För en utökad innehållsanmärkning med titlar och upphovsuppgifter. Musik- och teaterbiblioteket rekommenderar dock enkel innehållsanmärkning för musiktryck.  
  Klicka på på pilen vid Innehållsförteckning: {Namnlös} för att fälla ut Utökad innehållsanmärkning med Benämning och Upphovsuppgift. Lägg in titel under Benämning och upphov under Upphovsuppgift.  
  För att lägga till ytterligare en Utökad innehållsanmärkning med titel (Benämning) och Upphovsuppgift som lokal entitet, klicka på Duplicera entitet.

#### Malgruppsanmarkning
* Målgrupp/Målgrupp/Benämning (intendedAudience/IntendedAudience/label = 521 ‡a)   
  För att lägga till målgruppsanmärkning, klicka på plustecknet Lägg till egenskaper under: Instans och välj Målgrupp.  
Skapa Målgrupp som lokal entitet (plustecknet vid Målgrupp - Lägg till målgrupp. I rutan Skapa lokal entitet, längst ner i sidorutan till höger, skriv Målgrupp och välj det). Skriv in uppgiften under Benämning.      
  ```Exempel: För årskurs 1```  
Observera att kodning av målgrupp, motsvarande 008/22, ska registreras under Instans av Verk/Genre.  

#### Annat bararformat
* Annat bärarformat (otherPhysicalFormat = 776)  
  För att länka till en utgåva i annat format, till exempel en elektronisk utgåva, lägg till Annat bärarformat (Lägg till egenskaper, välj Annat bärarformat). Sök upp och länka till instansen. Klicka på plustecknet vid Annat bärarformat (Lägg till instans). I sidorutan under Lägg till entitet/Instans, skriv in id eller annat sökbegrepp. Välj instansen genom att klicka på plustecknet vid instansen eller på instansens titel. Om instansen som länken går till har identifikator (ISBN), skapas i marcexporten 776 #t (Titel) och #z (Identifikator). I webbsök ger detta en länk i högermenyn under rubriken Sök vidare/Andra versioner.   
  
  Om andra delfält i 776 önskas, skapa istället Instans som lokal entitet och lägg till önskade egenskaper.  
  Om särskild anmärkningstext önskas, som ersätter frasen "Andra versioner", skapa Instans som lokal entitet och lägg till Typanmärkning (= (776 ‡i) samt Har titel/Titel och Identifikator/ISBN/Värde. Beskriven av/Post/Kontrollnummer, motsvarande delfält w, är för närvarande låst för redigering. Det går därmed inte att lägga till egenskapen eller redigera det i befintliga beskrivningar.  


### Verk   

#### Instans av Verk/Musiktryck  
* Instans av Verk/Text (instanceOf/Work/NotatedMusic)  
  Skapa verket som lokal entitet (bryt inte ut verket till en länkbar entitet). Vi rekommenderar att tills vidare skapa verket som lokal entitet. Vi återkommer med anvisningar för att skapa verk som länkbara entiteter. Denna hjälptext beskriver exempel på verk som lokal entitet. Det betyder att du anger de uppgifter som listas här nedan, under Instans av Verk, utan att klicka på länksymbolen (Länka entitet) vid Instans av Verk/Noterad musik.  
Läs mer om [Verk och Instans](https://librisbloggen.kb.se/2018/05/30/verk-och-instans-i-startversionen/).  

#### Verkets titel
 
Ange den föredragna titeln för verket här, vid behov. Följ [Anvisningar för katalogisering - RDA](http://www.kb.se/rdakatalogisering/Anvisningar/Allmanna-anvisningar/Sokingangar-for-verk-och-uttryck "Anvisningar för katalogisering - RDA"). Pregnanta titlar för musik anges ofilerade enligt svensk musikbibliotekstradition.  

##### Verkets titel
* Har titel/Titel/Huvudtitel (hasTitle/Title/mainTitle = 240 1/0 ‡a)  
  Ange den föredragna titeln för verket här, vid behov. Pregnanta titlar för musik anges ofilerade. Skriv in uppgiften.
  <br/>```Exempel:```
  * ```La traviata```
  * ```Symfoni```
  * ```Pianomusik```
 
  Ange besättning i Huvudtitel efter form/genre/pregnant titel.
  <br/>```Exempel:```
  * ```Kvartett, stråkar```
  * ```Fosterlandspsalm, röst, orkester```
  
  Använd även Huvudtitel för *hela* den föredragna titeln då ordningen mellan uppgifterna i Har titel, Tonart, Version och språk för översättning blir felaktig i MARC-förhandsgranskningen, eller om den föredragna titeln är svår eller omöjlig att uttrycka med enbart dessa fält.  
  <br/>```Exempel:```
  * ```Sonater och partitor, violin, BWV 1001-1006. Partita, nr 1, h-moll```
  * ```Kvartett, stråkar, nr 13, D. 804, op. 29:1, a-moll, "Rosamunde". Entr'acte```
  
* Delbeteckning (hasTitle/Title/mainTitle/partNumber = 240 1/0 ‡n)  
Ange numreringar för verket här, vid behov. Skriv in uppgiften.
  <br/>```Exempel:```
  * ```nr 96, Hob. I:96```
  * ```nr 3, op. 90```
  
* Deltitel (hasTitle/Title/mainTitle/partName = 240 1/0 ‡p)       
Lägg till eventuell deltitel genom att klicka på plustecknet vid Titel (lägg till fält under: Titel), välj Deltitel.
Skriv in uppgiften.
  <br/>```Exempel:```
  * ```Di Provenza il mar```
  * ```Allegro```

* Specificering i form av grupptitel (hasTitle/Title/mainTitle/marc:formSubheading = 240 1/0 ‡k)   
Grupptitlar, exempelvis ”Pianomusik. Urval”, används då Instansen innehåller flera verk av samma tonsättare. Grupptiteln kompletteras med individuella sökingångar för dessa verk (i Relation/Verk).  
Lägg till eventuell grupptitel genom att klicka på plustecknet vid Titel (lägg till fält under: Titel), välj Specificering i form av grupptitel. Skriv in uppgiften.  
  ```Exempel: Urval```  

* Tonart (240 1/0 ‡r)       
Ange tonart. Skriv in uppgiften.  
  ```Exempel: Fiss-moll```  

* Version (240 1/0 ‡o)        
Ange eventuellt arrangemang. Skriv in uppgiften.  
  ```Exempel: arr. röst, piano```  
         
##### Verkets titel - huvuduppslag
För att ange "Originaltitel" för ett verk utan primär medverkande, t ex Bibeln, motsvarande fält 130, se [Hjälptext Tryckt monografi](https://libris.kb.se/katalogisering/help/workflow-print-monograph#verkets-titel) 

##### Verkets titel - analytisk sökingång  
För att ange verk som ingår i det beskrivna verket motsvarande fält 730 0/2 (analytisk sökingång), se [Hjälptext Tryckt monografi](https://libris.kb.se/katalogisering/help/workflow-print-monograph#verkets-titel)  

##### Verkets titel - relaterade verk  
För att ange verk som är relaterade, men inte ingår i det beskrivna verket, motsvarande fält 730 0/_ (icke-analytisk sökingång), se [Hjälptext Tryckt monografi](https://libris.kb.se/katalogisering/help/workflow-print-monograph#verkets-titel) 

#### Medverkan och funktion  
* Medverkan och funktion  
  Läs mer:  
  [Auktoritetsgruppens rekommendationer](https://kundo.se/org/librisxl/d/kbs-auktoritetsgrupp-informerar-jraz/)   
  [Lägga till Agent - Organisation](https://libris.kb.se/katalogisering/help/workflow-agent-org-instance)  
  
* Medverkan och funktion/Primär medverkan/Agent/Person (contribution/PrimaryContribution/agent/Person = 100 1/- ‡a)  
  Länka till entitet. Börja alltid med att söka efter om agenten redan finns. Vid behov, skapa ny entitet för agent (se Skapa ny agent i hjälpsektionen). I undantagsfall, skapa lokal entitet.   
 ```Exempel: Maier-Röntgen, Amanda, 1853-1894```  
* Medverkan och funktion/Primär medverkan/Funktion (contribution/PrimaryContribution/role = 100 ‡4)  
  Länka till entitet. Klicka på plustecknet vid Funktion (Lägg till funktion) och sök fram funktionskod. Skriv in kod eller utskriven form i sökrutan eller tryck på mellanslagstangenten för att se alla koder. Välj kod genom att klicka på plustecknet vid koden eller på koden.    
För en sorterad lista på koder, se Formathandboken för Libris/Voyager: [Funktions- och relationskoder](http://www.kb.se/katalogisering/Formathandboken/Funktionskoder/)  
  ```Exempel: relator/composer (= Kompositör, tonsättare, cmp)```  
* Medverkan och funktion/Medverkan/Agent/Person (contribution/agent/Person = 700 1/- ‡a)  
  Länka till entitet. Börja alltid med att söka efter om agenten redan finns. Vid behov, skapa ny entitet för agent (se Skapa ny agent i hjälpsektionen). I undantagsfall, skapa lokal entitet.   
  ```Exempel: Boye, Karin, 1900-1941```  
* Medverkan och funktion/Medverkan/Funktion (contribution/role = 700 ‡4)  
  Länka till entitet. Klicka på plustecknet vid Funktion (Lägg till funktion) och sök fram funktionskod. Skriv in kod eller utskriven form i sökrutan eller tryck på mellanslagstangenten för att se alla koder. Välj kod genom att klicka på plustecknet vid koden eller på koden.    
För en sorterad lista på koder, se Formathandboken för Libris/Voyager: [Funktions- och relationskoder](http://www.kb.se/katalogisering/Formathandboken/Funktionskoder/)
  <br/>```Exempel:```
  * ```Sångtext/lyr```
  * ```Redaktör/edt```
  
#### Sprak 
* Språk (language = 008/35-37)  
  För instrumentalmusik, ange Icke-språkligt medium (=language/zxx). För texter till musik, ange textens språk. För en text på svenska, ange svenska. För att ange originalspråk för ett översatt verk, se Originalversion/Verk/Språk.  
  Länka till entitet.
  <br/>```Exempel:```
  * ```language/zxx```
  * ```svenska (swe)```  
  För att ange att texten är på flera språk, t ex parallelltext, ange ytterligare en språkkod genom att klicka på plustecknet vid Språk (Lägg till språk) och söka fram ytterligare en entitet för ett språk och länka till den.  

##### Översättning  
För en översättning, ange även:  
* Språk/Språk/Benämning (Language/label = 240 ‡l)  
  Lägg till ytterligare en förekomst av Språk, under Språk (klicka på plustecknet vid Språk), skapa lokal entitet (klicka på Skapa lokal entitet längst ner i sidorutan till höger och lägg till Benämning (klicka på Lägg till egenskaper under: Språk).   
  Skriv in språket i klartext. Denna klartext - verkets (översättningens) språk - visas som ett tillägg till verkets titel i marcpostens 240 ‡l.  
  ```Exempel: Svenska```  

* Anmärkning: Språk (marc:LanguageNote = 041 i1: 1)  
  Ange om resursen är/innehåller en översättning.  
  För att lägga till uppgiften, klicka på plustecknet vid Instans av verk/Text och välj Anmärkning: Språk. Välj fras från lista.    
  ```Exempel: objektet är/innehåller översättning```  
  
* Originalversion/Verk/Språk (originalversion/Work/language = 041 ‡h)  
  Ange det språk som en översatt text är översatt från. För en text som är översatt från engelska till svenska, ange engelska här.   
  Klicka på Lägg till egenskaper under: Text, välj Originalversion, klicka på plustecknet vid Originalversion, välj Skapa lokal entitet (längst ner i sidorutan). Skriv Verk i rutan för Skapa lokal entitet och välj * Verk. Klicka på plustecknet vid Verk (Lägg till egenskaper under: Verk) och välj Språk. Klicka på plustecknet vid Språk. Sök fram språkentiteten och länka.  
  ```Exempel: engelska (eng)```  
För översättningar i flera led, länka först till det mellanliggande språket och därefter till originalspråket.  
  
###### Texten delvis översatt  
(041 0/- #a + 041 1/- #a #h)  
* Språk (language = 008/35-37) +
   Anmärkning: Språk: Objektet är/innehåller ej översättning (marc:languageNote = 041 0/- #a)   
* Har del/Verk/Språk (hasPart/Work/language = 041 ‡a) +  
  Anmärkning: Språk: Objektet är/innehåller översättning (marc:languageNote 041 1/-) +  
  Originalversion/Verk/Språk (originalVersion/Work/language = 041 ‡h)  
  För att ange att texten delvis är översatt, till exempel när en publikation innehåller parallelltext på två språk och den ena texten är en översättning: ange först Språk under Instans av Verk/Text (se Språk ovan). Sök fram och länka till entiteten för det språk som inte är en översättning. Klicka sedan på plustecknet vid Verk - Lägg till egenskap under: Text och välj Anmärkning: Språk. Välj Objektet är/innehåller ej översättning.   
 Lägg sedan till Har del under Instans av Verk/Text. Skapa verk som lokal entitet (plustecknet vid Har del - Lägg till resurs. I rutan Skapa lokal entitet, längst ner i sidorutan till höger, skriv Verk och välj ++++ Verk.) Klicka på plustecknet vid den lokala entiteten Verk (Lägg till egenskaper under: Verk) och välj Språk. Sök fram och länka till entiteten för språket som texten är översatt till. Under den lokala entiteten Verk, lägg till Anmärkning: Språk och ange att resursen är/innehåller en översättning. Under Har del, lägg till Originalversion/Verk/Språk (se ovan under Översättning). Länka till entiteten för språket som resursen delvis är en översättning från.  

#### Genre  
##### Saogf-termer  
* Genre/form – saogf-termer (genreForm = 655 -/7 ‡a, ‡2 saogf)  
  Här anges såväl besättning som genre/form. Länka till entitet.  
  För att söka efter entiteter inom saogf-termer, välj Genre/form i listan över typer, under Genre/form. Trunkera genom att trycka på mellanslagstangenten eller med * i sökrutan. Välj rätt entitet genom att klicka på plustecknet vid entiteten eller på entiteten.
  <br/>```Exempel:```
  * ```Piano```
  * ```Blandad kör```
  * ```Menuetter```  
  Se [instruktionsfilm](https://www.youtube.com/watch?v=wrqs310Nt0M&list=PLZVkEICvA5-GRT2oJQmLgq_2Pksx6zYPy&index=7)  
  
#### Klassifikation 
* DDK-klassifikation  
  För att lägga till DDK-klassifikation:  
  * Om posten har Klassifikation/Klassifikation (till exempel SAB-klassifikation) men saknar Klassifikation/DDK-klassifikation, lägg till ytterligare en förekomst av Klassifikation (plustecknet vid Klassifikation - lägg till egenskaper under: KLassifikation). Välj Skapa lokal entitet (längst ner i sidorutan till höger) och välj DDK-klassifikation. Skriv in uppgiften under Kod.  
  * Om posten helt saknar Klassifikation, lägg till Klassifikation genom att klicka på den runda egenskap-knappen i verktygsmenyn (Lägg till egenskaper under: Instans). Välj Klassifikation. Klicka på plustecknet under Klassifikation (Lägg till Klassifikation). Välj Skapa lokal entitet (längst ner i sidorutan till höger) och välj DDK-klassifikation.  
   Skriv in uppgiften under Kod.  

* Klassifikation/DDK-klassifikation/Kod (classification/ClassificationDdc/code = 082 0/4 ‡a)  
  Skriv in uppgiften.  
  ```Exempel: 782.5```  
* Klassifikation/DDK-klassifikation/Klassifikationsupplaga  
  (classification/ClassificationDdc/edition = 082 ‡2)  
  ```full```  
*  Parallell upplagebeteckning/Upplagespecifik upphovsuppgift  
 (classification/ClassificationDdc/editionEnumeration = 082 ‡2)  
   ```Exempel: 23/swe```  
  
##### SAB-klassifikation  
* SAB-klassifikation  
  För att lägga till annan klassifikation, till exempel SAB-klassifikation:  
  * Om posten har Klassifikation/DDK-klassifikation men saknar Klassifikation/Klassifikation (till exempel SAB-klassifikation), lägg till ytterligare en förekomst av Klassifikation (plustecknet vid Klassifikation - lägg till egenskaper under: KLassifikation). Välj Skapa lokal entitet (längst ner i sidorutan till höger) och välj Klassifikation. Skriv in uppgiften under Kod.  
  * Om posten helt saknar Klassifikation, lägg till Klassifikation genom att klicka på den runda egenskap-knappen i verktygsmenyn (Lägg till egenskaper under: Instans). Välj Klassifikation. Klicka på plustecknet under Klassifikation (Lägg till egenskaper under: Klassifikation). Välj Skapa lokal entitet (längst ner i sidorutan till höger) och välj Klassifikation.  
   Skriv in uppgiften under Kod.  
* Klassifikation/Klassifikation/Kod (classification/Classification/code = 084 0/4 ‡a)  
     Skriv in uppgiften.  
  ```Exempel: Xpbc```   
* Klassifikation/Termlista/Termlista/Kod (classification/Classification/inScheme/ConceptScheme/code = 084 ‡2)  
 ```Exempel: kssb```  
* Klassifikation/Termlista/Termlista/Version (classification/Classification/inScheme/ConceptScheme/version = 084 ‡2)  
 ```Exempel: 8``` 

#### Amne  
* Ämne  
  För samlingar där den geografiska eller kronologiska aspekten är framhävd får genre/form/besättning kompletteras med geografiska eller kronologiska ämnesord (i separata fält). Titel "French piano music" kan alltså indexeras med Piano och Frankrike.  
  Lägg till Ämne genom att klicka på plustecknet vid Noterad musik, sök upp Ämne och klicka på plustecknet vid termen. Klicka sedan på plustecknet vid Ämne och välj typ i listan Alla typer: Geografiskt ämnesord eller kronologiskt ämnesord. Sök upp ämnesordet, t ex Frankrike, och länka till entitet genom att klicka på plustecknet vid termen.
  Läs mer:  
  [Länka ämnesord](https://libris.kb.se/katalogisering/help/workflow-linked-entity-sh)   
  [Sammansatt, ej auktoriserat ämnesord](https://libris.kb.se/katalogisering/help/workflow-non-auth-sh)   
  [Kontrollerat, ej auktoriserat ämnesord](https://libris.kb.se/katalogisering/help/workflow-controlled-non-auth-sh)   
  [Okontrollerat ämnesord](https://libris.kb.se/katalogisering/help/workflow-uncontrolled-sh)  

##### Geografiskt ämnesord  
* Geografiskt ämnesord (subject = 651 -/4 ‡a)  
  Sök fram och länka till entitet.  
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
   
##### Kronologiskt ämnesord
* Ämne/Kronologiskt ämnesord (subject = 648 7/- ‡a, ‡2 sao)  
Länka till entitet. Om du inte får träff vid sökning på entiteter, pröva att söka på första ledet i ett sammansatt ord, t ex "1800" istället för "1800-talet".   
 ```Exempel: 1800-talet```  
  
##### Anmärkning om notationssystem och språk
* Anmärkning: Språk/Anmärkning om språk/Notationssystem /Notation/Benämning (hasNote/marc:LanguageNote/hasNotation/Notation/label = 546 ‡b)
  <br/>```Exempel:```
  * ```Traditionell västerländsk notskrift```
  * ```Grafisk notation```  
* Anmärkning/Anmärkning om språk/Anmärkning: Språk/Benämning (hasNote/marc:LanguageNote/marc:LanguageNote/label = 546 ‡a)
  <br/>```Exempel:```
  * ```Sångtext på hebreiska```
  * ```Kritiska kommentarer på svenska och engelska```  
 
#### Målgrupp     
 * Målgrupp (intendedAudience = 008/22)  
  Länka till entitet.  
  Trunkera genom att trycka på mellanslagstangenten eller med * i sökrutan. Välj rätt entitet genom att klicka på plustecknet vid entiteten eller på entiteten.    
  ```Exempel: j (= barn- och ungdom, 0-16 år)```  
  
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
  
#### Innehallstyp
* Innehållstyp/Innehållstyp (contentType/ContentType = 336 ‡b)  
  Länka till entitet.  
  ```Exempel: term/rda/NotatedMusic```  
  För att lägga till ytterligare innehållstyp, till exempel "sti" = stillbild för en bilderbok med både text och bild, lägg till Har del under Instans av Verk, från plustecknet vid Text (Lägg till egenskaper under: Noterad musik). Skapa därefter Verk som lokal entitet genom att klicka på plustecknet vid Har del (Lägg till resurs). Välj Skapa lokal entitet och välj därefter ++ Verk i listan. Lägg därefter till Innehållstyp från plustecknet vid Verk (Lägg till egenskaper under: Verk). Sök fram och länka till entitet.  

#### Relation
* Relation (Relationship = 700 1/_ )
  Här anges ingående verk om instansen manifesterar fler än ett verk, med föredragna titlar och medverkande.  
  För att ange verk som ingår i det beskrivna verket, klicka på pilen vid Relation och skriv in uppgifterna enligt instruktionerna nedan. För att ange ytterligare verk klicka på ikonen med dubbla fyrkanter till höger om Relation (Duplicera entitet).  
  
##### Verk/Har titel/Titel
* Huvudtitel (hasTitle/Title/mainTitle = 700 1/_ ‡a)  
  Ange den föredragna titeln för verket här, vid behov. Pregnanta titlar för musik anges ofilerade. Skriv in uppgiften.
  <br/>```Exempel:```
  * ```La traviata```
  * ```Symfoni```
         
* Delbeteckning (hasTitle/Title/mainTitle = 700 1/_  ‡n)  
  Ange numreringar för verket här, vid behov. Skriv in uppgiften.
  <br/>```Exempel:```
  * ```nr 96, Hob. I:96```
  * ```nr 3, op. 90```
         
* Uttryck av/Verk/Har titel/Titel/Deltitel (expressionOf/Work/hasTitle/Title/partName = 700 1/_ ‡p)  
  Lägg till eventuell deltitel genom att klicka på plustecknet vid Titel (lägg till fält under: Titel), välj Deltitel. Skriv in uppgiften.
  <br/>```Exempel:```
  * ```Di Provenza il mar```
  * ```Allegro```

  Använd Huvudtitel för hela den föredragna titeln då ordningen mellan uppgifterna i Har titel, Tonart, Version, Besättning och språk för översättning blir felaktig i MARC-förhandsgranskningen, eller om den föredragna titeln är svår eller omöjlig att uttrycka med enbart dessa fält.
  <br/>```Exempel:```
  * ```Sonater och partitor, violin, BWV 1001-1006. Partita, nr 1, h-moll```
  * ```Kvartett, stråkar, nr 13, D. 804, op. 29:1, a-moll, "Rosamunde". Entr'acte```
        
* Verk/Tonart (700 1/_ ‡r) 
  Ange tonart. Skriv in uppgiften.  
  ```Exempel: Fiss-moll```  

* Verk/Version (700 1/_ ‡o)  
Ange eventuellt arrangemang.  
Skriv in uppgiften.  
  ```Exempel: arr. röst, piano```  

* Verk/Primär medverkan/Agent/Person (contribution/PrimaryContribution/agent/Person = 700 1/_ ‡a)
  Länka till entitet. Börja alltid med att söka efter om agenten redan finns. Vid behov, skapa ny entitet för agent (se Skapa ny agent i hjälpsektionen). I undantagsfall, skapa lokal entitet.   
  ```Exempel: Maier-Röntgen, Amanda, 1853-1894```  

* Verk/Besättning för framförande (700 1/_ ‡m)  
  Ange besättning. Skriv in uppgiften.
  <br/>```Exempel:```
  * ```orkester```
  * ```klarinett, piano```
  * ```blandad kör```
      
* Verk/Språk/Språk/Benämning (Language/label = 700 1/_ ‡l)  
  Språk för översättning. Lägg till en förekomst av Språk under Relation/Verk genom att klicka på plustecknet vid Verk. Sök fram Språk i sidorutan, klicka på termen och sedan på Skapa lokal entitet. Lägg till Benämning (klicka på Lägg till egenskaper under: Språk).  
  Skriv in språket i klartext. Denna klartext - verkets (översättningens) språk - visas som ett tillägg till verkets titel i marcpostens 700 1/_ ‡l.  
  ```Exempel: Svenska```  
