---
section: Materialtyper
title: Tryckt seriell resurs
order: 55
date: 2020-06-22
tags:
- seriell resurs
- tidskrift
- monografiserie
--- 

# Tryckt seriell resurs
Denna hjälptext ger kortfattade instruktioner för de vanligaste egenskaperna för en tryckt seriell resurs. För utförliga instruktioner, se de generella hjälptexterna för Adminmetadata, Instans och Verk, se nedan.

[Inledning](#inledning) 

| [Adminmetadata](#adminmetadata) | [Instans](#instans) | [Verk](#verk) | 
| ----------- |  ----------- | ----------- | 
[Generell hjälptext för Adminmetadata](https://libris.kb.se/katalogisering/help/workflow-adminmetadata) | [Generell hjälptext för Instans](https://libris.kb.se/katalogisering/help/workflow-instance) | [Generell hjälptext för Verk](https://libris.kb.se/katalogisering/help/workflow-work) |
| | [Utgivningssätt](#utgivningssatt) | [Medverkan och funktion](#medverkan-och-funktion) | 
| | [Medietyp](#medietyp) | [Språk](#sprak) |
| | [Bärartyp](#barartyp) | [Genre/form](#genre-form) |
| | [Titel](#titel) | [Klassifikation](#klassifikation) |
| | [Utgivning](#utgivning) | [Ämne](https://libris.kb.se/katalogisering/help/workflow-general-sh) |
| | [Identifikator](#identifikator) | [Innehållstyp](#innehallstyp) |
| | [Frekvens](#frekvens) | [Verkets titel](#verkets-titel) |
| | [Numrering av seriell resurs](#numrering-av-seriell-resurs) | |
| | [Alfabet](#alfabet) | |
| | [Behandling vid titeländring](#behandling-vid-titelandring) |  |
| | [Anmärkning](#anmarkning)| |
| | [Relationer](#relationer) | | 


**NYTT FRÅN VERSION 1.17.2:** Relationer (länkfält), till exempel Fortsätter, Fortsättes av, Ersätter, med flera, har flyttats från Verk till Instans.

## Inledning
Beskrivningen av en tryckt seriell resurs innehåller följande tre delar:  
* [Adminmetadata](https://libris.kb.se/katalogisering/help/workflow-adminmetadata) - administrativa data om instansbeskrivningen, såsom kontrollnummer och beskrivningsnivå
* [Instans](https://libris.kb.se/katalogisering/help/workflow-instance) - instans kan också kallas utgåva eller manifestation. Exempel på egenskaper under Instans är utgivningsplats, utgivare och utgivningsår, bärartyp, omfång.
* [Verk](https://libris.kb.se/katalogisering/help/workflow-work) – återger egenskaper för det abstrakta verket såsom medverkan och funktion (t.ex. författare), ämne, klassifikation, språk och innehållstyp. Verksbeskrivningen ligger under rubriken Instans av verk.

Många av egenskaperna finns redan i mallen Tryckt seriell resurs, andra kan behöva läggas till. För instruktioner om att lägga till eller ta bort egenskaper, länka till entitet, skapa lokal entitet och om hur formuläret fungerar i övrigt, se Redigering i vänstermenyn. För en förhandspost, använd gärna Berika från mall och välj Tryckt seriell resurs.  

För information om katalogregler, skrivregler och övriga katalogiseringsanvisningar, [se Anvisningar för katalogisering - RDA](http://www.kb.se/rdakatalogisering/Anvisningar/Arbetsfloden/Tryckta-seriella-resurser/ "Anvisningar för katalogisering - RDA") och [RDA Toolkit](https://access.rdatoolkit.org/).

[Se även instruktionsfilmer på KB:s Youtubekanal](https://www.youtube.com/playlist?list=PLZVkEICvA5-GRT2oJQmLgq_2Pksx6zYPy).   

## Adminmetadata
[Använd generell hjälptext för Adminmetadata](https://libris.kb.se/katalogisering/help/workflow-adminmetadata).

## Instans

### Utgivningssatt
* Utgivningssätt (issuanceType)  
  Välj från lista.  
  ```Exempel: Seriell resurs```
  
### Medietyp
* Medietyp (mediaType/Mediatype = 337 #b)  
  Länka till entitet.  
  ```Exempel:  n (= omedierad)``` 
  
### Barartyp  
* Bärartyp (carrierType/CarrierType = 338 #b)  
  Länka till entitet.  
  ```Exempel:  nc (= volym)```
  
### Titel 

#### Nyckeltitel
* Har titel/Nyckeltitel/Huvudtitel    
(hasTitle/KeyTitle/mainTitle = 222 -/0 #a)  
För svenska seriella resurser ansvarar ISSN Sverige för nyckeltiteln.  
Skriv in uppgiften.  
 ```Exempel:  Kammarmusik-nytt ```
 
* Har titel/Nyckeltitel/Särskiljande tillägg  
(hasTitle/KeyTitle/qualifier = 222 #b)  
Skriv in uppgiften, inom parentes.  
```Exempel: (Brämhult)```
  
#### Huvudtitel    
* Har titel/Titel/Huvudtitel (hasTitle/Title/mainTitle = 245 #a)  
För att lägga till Har titel, klicka på plustecknet Lägg till egenskaper under: Instans.  
  Återge huvudtiteln från titelsidan eller annan föredragen källa så som den förekommer i källan. [Se Anvisningar för katalogisering - RDA](http://www.kb.se/rdakatalogisering/Anvisningar/Arbetsfloden/Tryckta-seriella-resurser/#huvudtitel_seriell  "Anvisningar för katalogisering - RDA").  
  Skriv in uppgiften under Huvudtitel.      
  ```Exempel: Kammarmusik-nytt```  
  För en titel som börjar med bestämd eller obestämd artikel, ska artikeln fileras bort. Ange fileringsvärde genom att lägga till fileringsvärde (plustecknet vid Titel - Lägg till egenskaper under: Titel) och ange en siffra.  
 ```Exempel: Huvudtitel: Le bulletin France-Suède, fileringsvärde: 3```  
 [Se exempel i formathandboken för Libris/Voyager - Fileringsindikator](http://www.kb.se/katalogisering/Formathandboken/Fileringsindikator/)
  
#### Övrig titelinformation (undertitel)
* Har titel/Titel/Övrig titelinformation (= Undertitel) (hasTitle/Title/subtitle = 245 #b)  
  Skriv in uppgiften under Övrig titelinformation. Om det finns flera undertitlar, skriv in dessa efter varandra i samma fält, åtskilda av mellanslag, kolon, mellanslag.   
  ```Exempel: Kammarmusikförbundets tidskrift```
  
#### Varianttitel   
Används till exempel för felaktigheter och tillfälliga variationer/mindre förändringar i huvudtiteln. Felaktigheter kan specificeras med Typanmärkning och tillfälliga variationer/mindre förändringar i huvudtiteln kan preciseras med Täckning och tillkomst. 
För att lägga till varianttitel, klicka på plustecknet vid Har titel (lägg till titel) och välj typ Varianttitel.  
* Har titel/Varianttitel/Typanmärkning (hasTitle/VariantTitle/typeNote = 246 1/_ #i)  
 Anmärkningstext som i ett sökgränssnitt ska föregå varianttiteln. Används också för att ange typ av varianttitel som inte finns i listan, t ex Titelrubrik. Lägg vid behov till Typanmärkning (plustecknet vid Varianttitel - lägg till egenskaper under: Varianttitel, välj Typanmärkning).  
  Skriv in uppgiften.   
  ```Exempel: Titel felstavad i nummer 1 (2006):```  
* Har titel/Varianttitel/Huvudtitel (hasTitle/VariantTitle/mainTitle = 246 1/_ #a)  
  Skriv in uppgiften under Huvudtitel.    
  ```Exempel: Housing sarts```    

#### Tidsbestämd titelvariant   
Avser tidsbestämda titelvariationer. Volym/häfte och/eller tidsintervall preciseras under Täckning eller tillkomst (se nedan).   
* Har titel/Varianttitel/Huvudtitel (hasTitle/VariantTitle/mainTitle = 246 1/_ #a)    
  Skriv in uppgiften under Huvudtitel.  
  ```Exempel: Hushållningssällskapets magasin```  
  
* Har titel/Titelvariant/Täckning eller tillkomst (hasTitle/DistinctiveTitle/coverage = 246 #f)  
  Skriv in uppgiften.  
  ```Exempel: 2011, nr 4-2012, nr 4``` 
  
#### Delbeteckning
* Har titel/Titel/Har del/Titeldel/Delbeteckning (hasTitle/Title/hasPart/TitlePart/partNumber = 245 #n)  
 
##### Deltitel  
* Har titel/Titel/Har del/Titeldel/Deltitel (hasTitle/Title/hasPart/TitlePart/partName = 245 #p)

#### Akronymer/Del av huvudtitel  
Används för akronymer som är en del av huvudtiteln.  
* Har titel/Del av huvudtitel/Huvudtitel (hasTitle/Titleportion/mainTitle = 245 0/- #a)  
  Skriv in uppgiften under Huvudtitel.  
  ```Exempel: ACMO```  
    
### Utgivning
* Utgivning  
  Välj typ från lista. För seriella resurser med endast en utgivare, använd Primär utgivning.  
  
  För en seriell resurs som byter utgivare, låt Primär utgivning ligga kvar (för den första utgivningsperioden). Lägg till Utgivning för att beskriva nästa utgivningsperiod. Lägg till Sekvens av uppgifter under Utgivning och välj Nuvarande/senaste utgivare. Vid behov, ändra uppgift om Sekvens av uppgifter för mellanliggande utgivningsperioder.  
  
#### Utgivningsplats
* Plats/Plats/Benämning (= Utgivningsort) (place/label = 264 -/1 #a)  
  För att lägga till Plats, klicka på plustecknet vid Primär utgivning (lägg till egenskaper under Primär utgivning) och välj Plats. Sök inte efter Plats som entitet. I rutan Skapa lokal entitet, längst ner i sidorutan till höger, skriv Plats och välj det.   
  Skriv in uppgiften under Benämning.    
  ```Exempel: [Göteborg]```
  
#### Utgivningsland
* Land (country = 008/15-17)  
  Länka till entitet.  
  ```Exempel: Sverige (sw)```
  
#### Utgivarnamn
* Agent/Benämning (= Utgivarnamn) (agent/label = 264 -/1 #b)  
  För att lägga till Agent, klicka på Lägg till egenskaper under Primär utgivning och välj Agent. Sök inte efter Agent som entitet. I rutan Skapa lokal entitet, längst ner i sidorutan till höger, skriv Agent och välj det.       
  Skriv in uppgiften under Benämning.  
  ```Exempel: NoNa```  
  Om flera utgivare ska anges, lägg till Har del (hasPart) under Primär utgivning. Skapa Utgivning som lokal entitet (plustecknet vid Har del - Lägg till entitet). I rutan Skapa lokal entitet, längst ner i sidorutan till höger, skriv Utgivning och välj *** Utgivning. Upprepa Utgivning som lokal entitet genom att duplicera entiteten Utgivning.  
Ange Plats/Plats/Benämning och Agent/Agent/Benämning och vid behov Datum inom respektive utgivningsavsnitt (angående Datum, se anvisningar nedan). Samtliga utgivare med Plats och Agent ska ligga inom Har del/Utgivning.
Land, År och eventuellt Datum  ska ligga inom Primär utgivning.  
  [Se exempelpost i Libris katalogisering](https://libris.kb.se/katalogisering/w4rp4hlwtr5lctjr#it).  
  
#### År och datum    
* Startår (startYear = 008/7-10)  
  Startår får endast innehålla siffror (0-9) och bokstaven u. Startår ska endast förekomma inom Primär utgivning.  
  För att ange ett startår utan klamrar eller andra tecken, ange det endast här. Det kommer då att exporteras till både marcpostens 08/07-10 och 264 -/1 #c. Bindestreck sätts automatiskt. För att ange årtal med klamrar eller andra tecken utöver fyra positioner, använd Datum. 
  För att lägga till Startår, klicka på plustecknet vid Primär utgivning (Lägg till egenskaper under: Primär utgivning) och välj Startår.  
  Skriv in uppgiften.  
   ```Exempel: 2011```  
* Slutår (endYear = 008/11-14)  
  Slutår får endast innehålla siffror (0-9) och bokstaven u. Slutår ska endast förekomma inom Primär utgivning.  
  För att ange ett slutår utan klamrar eller andra tecken, ange det endast här. Det kommer då att exporteras till både marcpostens 08/11-14 och 264 -/1 #c. Bindestreck sätts automatiskt. För att ange årtal med klamrar eller andra tecken utöver fyra positioner, använd Datum.   
  Om slutår inte anges, sätts utgivningsstatus (008/06) automatiskt till "c = Utgivning pågår".  
  Om slutår anges, sätts utgivningsstatus (008/06) automatiskt till "d = Utgivning avslutad".  
   För att lägga till Slutår, klicka på plustecknet vid Primär utgivning (Lägg till egenskaper under: Primär utgivning) och välj Startår.  
  Skriv in uppgiften.  
  ```Exempel: 2013```     
  För att ange slutår för senaste utgivningsperiod (264 -/3 #c), notera först vilket startåret för utgivningsperioden är, ta bort Startår och lägg till Datum. Skriv in hela datumangivelsen med startår och slutår (se nedan under Datum).    
* Datum (date = 264 -/1 #c)  
  Datum får innehålla text och interpunktionstecken.  
  För att ange utgivningsdatum med fler än fyra positioner, till exempel klamrade årtal, skriv in det här. Det kommer att exporteras till marcpostens  264 -/1 #c.  
  För att ange år utan klamrar eller andra tecken, använd endast Startår och Slutår.  
  Skriv in uppgiften.
  <br/>```Exempel:```
  * ```2012-2013```
  * ```[1988-]```
  
### Identifikator  
* Identifikator/Typ (identifiedBy)  
  Välj från lista.  
  ```Exempel: ISSN```   
* Identifikator/ISSN/Värde (identifiedBy/Issn/value = 022 #a)  
  Skriv in uppgiften.  
  ```Exempel: 2001-2721```  
* Identifikator/Felaktigt ISSN (identifiedBy/marc:incorrectIssn = 022 #y)  
  Skriv in uppgiften.   
  ```Exempel: 1653-2945```   
  
### Frekvens   
* Frekvens (frequency)  
  * Frekvensterm (008/18)  
    Länka till entitet.  
    ```Exempel: var tredje månad (q = quarterly)```  
**Från och med version 1.7 behöver man inte längre ange "u" för okänd frekvens. Det skapas automatiskt vid marcexport om frekvens inte har angetts.**
  * Regelbundenhet (008/19)  
    **Från och med version 1.7 behöver man inte längre ange Regelbundenhet. "Inget försök att koda" skapas automatiskt vid marcexport.**
    
### Numrering av seriell resurs  
* Har numrering av seriell resurs/Numrering av seriell resurs/Benämning  
  (hasNumberingofSerials/NumberingofSerials/label = 362 0/- #a)  
  Skriv in uppgiften under Benämning.    
  ```Exempel: 2011: 4-2013: 2```
  
### Alfabet    
* Alfabet/skriftart (marc:alphabet = 008/33)   
  Länka till entitet.  
  ```Exempel: b (= Extended roman = Latinskt alfabet med diakriter och specialtecken (a-ö))```
  
### Behandling vid titelandring 
* Behandling vid titeländring (marc:typeOfEntry = 008/34)  
  Länka till entitet.  
  ```Exempel: 0 (= Successive entry = Titeländring ger upphov till ny post)```

### Anmarkning
* Anmärkning/Anmärkning/Benämning (hasNote/Note/label = 500 #a)  
  Skriv in allmänna anmärkningar här.  
  Skriv in uppgiften under Benämning.  

### Relationer
För relationer (länkfält): Annat bärarformat (776), Fortsätter (780 0/0), Fortsättes av (785 0/0), Ersätter (780 0/2), med flera: 
sök fram och lägg till egenskapen (relationen) genom att klicka på plustecknet i verktygsmenyn. För seriella resurser, skapa lokal entitet i stället för att länka. Att länka till annan instans ger felaktiga delfältskoder, vilket inte är tillåtet vid export till ISSN IC (Internationella ISSN-centralen).  

* Annat bärarformat (776)
  Annat bärarformat/Instans/Instanstyp/Har titel/Titel/Huvudtitel (otherPhysicalFormat/Instance/type/hasTitle/Title/mainTitle = 776 #t)  
Lägg till Annat bärarformat. Skapa Instans som lokal entitet. Man behöver inte välja Instanstyp här. Lägg till Har titel och välj Titel. Skriv in titeln under Huvudtitel.  
* Annat bärarformat/Instans/Instanstyp/Identifikator/ISSN/Värde (otherPhysicalFormat/Instance/type/identifiedBy/ISSN/value = 776 #x)  
Lägg till Identifikator och välj ISSN. Skriv in ISSN under Värde.  
 Typanmärkning i samband med Annat bärarformat kan för närvarande inte läggas till.
  Beskriven av/Post/Kontrollnummer, motsvarande delfält w, är för närvarande låst för redigering. Det går därmed inte att lägga till fältet eller redigera det i befintliga beskrivningar.   

* Övriga relationer (länkfält): Fortsätter (780 0/0), Fortsättes av (785 0/0), Ersätter (780 0/2), med flera:  
följ mönstret för Fortsätter, se nedan.
 
* Fortsätter/Instans/Instanstyp/Har titel/Titel/Huvudtitel (continues/Instance/type/hasTitle/Title/mainTitle = 780 0/0 #t)  
 För att lägga till titel under Fortsätter, Fortsättes av, Ersätter, med flera:  
 Skapa Instans som lokal entitet. Man behöver inte välj Instanstyp här. Lägg till Har titel. Välj Titel. Skriv in uppgiften under Huvudtitel.
 <br/>```Exempel:```
  * ```Aktuellt magazin```
  * ```Medlemstidning (Svenska Schweisshundklubben)```
  
* Fortsätter/Instans/Instanstyp/Identifikator/ISSN/Värde (continues/Instance/type/identifiedBy/ISSN/value = 780 0/0 #x)  
  Lägg till Identifikator vid Instans. Välj typ ISSN. Skriv in ISSN under Värde.  
```Exempel: 1402-1250```  

Exempel:  

![Exempel på relationen Fortsättes av för seriell resurs](fortsatter_seriell.png)  

* Fortsätter/Instans/Instanstyp/Beskriven av/Post/Kontrollnummer (continues/Instance/type/describedBy = 780 0/0 #w)  
  Beskriven av/Post/Kontrollnummer, motsvarande delfält w, är för närvarande låst för redigering. Det går därmed inte att lägga till egenskapen eller redigera den i befintliga beskrivningar.  

  Hör följer ett urval av de relationer som kan läggas till, enligt samma mönster som Fortsätter (se ovan):  
  
  Fortsätter (continues = 780 0/0)  
  Fortsätter delvis (continuesInPartBy = 780 0/1)  
  Föregående (precededBy = 780 0/2)  
  Ersätter delvis (precededInPartBy = 780 0/3)  
  Sammanslagen med (mergerOf = 780 0/4) [Se exempelpost i Libris katalogisering](https://libris.kb.se/katalogisering/5ng67r2h49lzkl9#it))  
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
  Sammanslagen till (mergedToForm = 785 0/7) [Se exempelpost i Libris katalogisering](https://libris.kb.se/katalogisering/tb4vcdf54hzlsr3#it))  
  

## Verk
* Instans av Verk/Text (instanceOf/Work/Text)  
  Skapa verket som lokal entitet (bryt inte ut verket till en länkbar entitet). Vi rekommenderar att du skapar verket som lokal entitet under den första tiden som Nya Libris är i drift. Vi återkommer med anvisningar för att skapa verk som länkbara entiteter. Denna hjälptext beskriver exempel på verk som lokal entitet. Det betyder att du anger de uppgifter som listas här nedan, under Instans av Verk, utan att klicka på länksymbolen (Länka entitet) vid Instans av Verk/Text.  
[Läs mer om Verk och Instans på Libris informationssidor på kb.se](https://www.kb.se/samverkan-och-utveckling/nytt-fran-kb/nyheter-samverkan-och-utveckling/2018-05-30-verk-och-instans-i-startversionen-av-nya-libris.html).  

### Medverkan och funktion     
[Följ instruktioner i hjälptexten Relationer till Agent](https://libris.kb.se/katalogisering/help/workflow-agent-org-instance)  
  
* Medverkan och funktion/Medverkan/Agent (contribution/Contribution/agent = 710 2/- #a)  
  Länka till entitet. Börja alltid med att söka efter om agenten redan finns. Vid behov, skapa ny entitet för agent (se Skapa ny agent i hjälpsektionen). I undantagsfall, skapa lokal entitet.  
  ```Exempel: Riksförbundet Sveriges kammarmusikarrangörer```  
* Medverkan och funktion/Medverkan/Agent/Funktion (contribution/Contribution/agent/role = 710 #4)   
  Länka till entitet. Klicka på plustecknet vid Funktion (Lägg till funktion) och sök fram funktionskod. Skriv in kod eller utskriven form i sökrutan eller tryck på mellanslagstangenten för att se alla koder. Välj kod genom att klicka på plustecknet vid koden eller på koden.    
För en sorterad lista på koder, [se Formathandboken för Libris/Voyager - Funktions- och relationskoder](http://www.kb.se/katalogisering/Formathandboken/Funktionskoder/)    
  ```Exempel:  Utgivare (pbl = publisher)```
  
### Sprak
* Språk (language = 008/35-37)  
  Länka till entitet.  
  ```Exempel: svenska (swe)```  
   För att ange att texten är på flera språk, t ex parallelltext, ange ytterligare en språkkod genom att klicka på plustecknet vid Språk (Lägg till språk) och söka fram ytterligare en entitet för ett språk och länka till den.  
   
### Genre form 
#### Typ av fortlöpande resurs  
* Genre/form - typ av fortlöpande resurs (genreForm/marc:Periodical = 008/21)  
  Länka till entitet.  
  För att söka efter entiteter inom Typ av fortlöpande resurs, välj Typ av fortlöpande resurs i listan över typer, under Genre/form. Trunkera genom att trycka på mellanslagstangenten eller med * i sökrutan. Välj rätt entitet genom att klicka på Lägg till.  
I mallen för Tryckt seriell resurs ligger Tidskrift. Vid behov, ändra till Monografiserie eller Dagstidning.
<br/>```Exempel:```
  * ```p (Tidskrift = marc/Periodical)```
  * ```m (Monografiserie = marc/MonographicSeries```
  * ```n (Dagstidning = marc/Newspaper```
         
### Klassifikation  
* DDK-klassifikation  
  För att lägga till DDK-klassifikation:  
  * Om posten har Klassifikation/Klassifikation (till exempel SAB-klassifikation) men saknar Klassifikation/DDK-klassifikation, lägg till ytterligare en förekomst av Klassifikation (plustecknet vid Klassifikation - lägg till klassifikation). Välj Skapa lokal entitet (längst ner i sidorutan till höger) och välj DDK-klassifikation. Skriv in uppgiften under Kod.  
  * Om posten helt saknar Klassifikation, lägg till Klassifikation genom att klicka på plustecknet vid Instans av Verk/Text (Lägg till egenskaper under: Text). Välj Klassifikation. Klicka på plustecknet vid Klassifikation (Lägg till klassifikation).  Välj Skapa lokal entitet (längst ner i sidorutan till höger) och välj DDK-klassifikation.  
   Skriv in uppgiften under Kod.  

* Klassifikation/DDK-klassifikation/Kod  
(classification/ClassificationDdc/code = 082 0/4 #a)  
  Skriv in uppgiften.  
  ```Exempel: 327.12092```
* Klassifikation/DDK-klassifikation/Klassifikationsupplaga  
(classification/ClassificationDdc/edition = 082 #2)  
  ```Exempel: full```  
*  Parallell upplagebeteckning/Upplagespecifik upphovsuppgift  
(classification/ClassificationDdc/editionEnumeration = 082 #2)  
  ```Exempel: 23/swe```  
  
#### Sekundär DDK-klassifikation  
Lägg till DDK-klassifikation (sekundär) genom att klicka på plusikonen vid Instans av Verk/Text (Lägg till egenskaper under: Text) och välja DDK-klassifikation (sekundär).  
Klicka sedan på plustecknet vid DDK-klassifikation (sekundär) (Lägg till ddk-klassifikation) och välj Skapa lokal entitet (längst ner i sidorutan till höger). Skriv in uppgiften under Kod.  
* Klassifikation/DDK-klassifikation/Kod (additionalClassificationDdc/ClassificationDdc/code = 083 0/- #a)  
  Skriv in uppgiften.  
  ```Exempel: 791.430233092```
* Klassifikation/DDK-klassifikation/Klassifikationsupplaga  
  (classification/ClassificationDdc/edition = 083 #2)  
  ```Exempel: full```  
*  Parallell upplagebeteckning/Upplagespecifik upphovsuppgift  
 (classification/ClassificationDdc/editionEnumeration = 083 #2)  
  ```Exempel: 23/swe``` 
   
#### SAB-klassifikation  
* SAB-klassifikation  
  För att lägga till annan klassifikation, till exempel SAB-klassifikation:  
  * Om posten har Klassifikation/DDK-klassifikation men saknar Klassifikation/Klassifikation (till exempel SAB-klassifikation), lägg till ytterligare en förekomst av Klassifikation (plustecknet vid Klassifikation - lägg till klassifikation). Välj Skapa lokal entitet (längst ner i sidorutan till höger) och välj Klassifikation. Skriv in uppgiften under Kod.  
  * Om posten helt saknar Klassifikation, lägg till Klassifikation genom att klicka på plustecknet vid Instans av Verk/Text (Lägg till egenskaper under: Text). Välj Klassifikation. Klicka på plustecknet vid Klassifikation (Lägg till klassifikation).  Välj Skapa lokal entitet (längst ner i sidorutan till höger) och välj Klassifikation.  
   Skriv in uppgiften under Kod.   
* Klassifikation/Klassifikation/Kod  
(classification/Classification/code = 084 0/4 #a)  
     Skriv in uppgiften.  
  ```Exempel: Sei-e```   
* Klassifikation/Ingår i system/Konceptsystem/Kod  
(classification/Classification/inScheme/ConceptScheme/code = 084 #2)  
 ```Exempel: kssb```  
* Klassifikation/Ingår i system/Konceptsystem/Version  
(classification/Classification/inScheme/ConceptScheme/version = 084 #2)  
 ```Exempel: 8``` 

#### Konferenspublikation  
* Genre/form – konferenspublikation (genreForm = 008/29)  
  Länka till entitet.  
  För att söka efter entiteter inom Konferenspublikation, välj Konferenspublikation i listan över typer, under Genre/form. Trunkera genom att trycka på mellanslagstangenten eller med * i sökrutan. Välj rätt entitet genom att klicka på Lägg till.  
  ```Exempel: Ja, resursen härrör från konferens```      
   
### Amne  
[Se hjälptexten Ämnesord i Libris](https://libris.kb.se/katalogisering/help/workflow-general-sh) 
  
### Innehallstyp
* Innehållstyp (contentType/ContentType = 336 #b)  
  Länka till entitet.  
  ```Exempel: text (txt)```
  
### Verkets titel
* Uttryck av/Verk/Har titel/Huvudtitel (hasExpression/Work/hasTitle/mainTitle = 130 0/- #a)  
  Under Instans av Verk/Text, lägg till Uttryck av (plustecknet vid Instans av Verk/Text - Lägg till egenskaper under: Text, välj Uttryck av).  
Skapa verk som lokal entitet (plustecknet vid Uttryck av - Lägg till verk, välj Skapa lokal entitet, längst ner i sidorutan till höger), skriv "verk" i rutan Skapa lokal entitet. Klicka på Verk. Det läggs till under Uttryck av. Klicka på plustecknet vid Verk (Lägg till egenskaper under: Verk) och välj Har titel. Välj Titel. Ta bort Övrig titelinformation.    
Skriv in uppgiften under Huvudtitel.  
```Exempel:  Architecture (Paris. 1888)```
