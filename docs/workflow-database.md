---
section: Materialtyper
title: Databas/Webbplats
order: 36
date: 2020-08-19
tags:
- databas
- webbplats
- integrerande resurs
--- 

# Databas/webbplats
Denna hjälptext ger kortfattade instruktioner för de vanligaste egenskaperna vid beskrivning av onlinedatabaser och webbplatser (så kallade integrerande resurser). För utförliga instruktioner, se de generella hjälptexterna för Adminmetadata, Instans och Verk, se nedan.

Integrerande resurser kännetecknas av att uppdateringar (nytt och förändrat material) infogas som en integrerad del i helheten. I motsats till seriella resurser saknas därför alfanumeriska och/eller kronologiska beteckningar. Vid förändringar i huvudtiteln hos en integrerande resurs görs normalt ingen ny beskrivning. Istället ersätts huvudtiteln med den nya så att den aktuella versionen återspegles. 

**Observera dock att för integrerande resurser som har ISSN gäller andra regler.** Om huvudtiteln genomgår en större förändring tilldelas resursen ett nytt ISSN och en ny beskrivning görs. Om en integrerande resurs med svenskt ISSN byter huvudtitel, meddela [ISSN Sverige](https://www.kb.se/isbn-och-utgivning/issn-.html). 

Även andra egenskaper hos en integrerande resurs kan förändras och behöva uppdateras, t.ex. upphov och utgivare. För instruktioner om hur olika egenskaper uppdateras, se repektive egenskap.

[Inledning](#inledning) 

| [Adminmetadata](#adminmetadata) | [Instans](#instans) | [Verk](#verk) | 
| ----------- |  ----------- | ----------- | 
[Generell hjälptext för Adminmetadata](https://libris.kb.se/katalogisering/help/workflow-adminmetadata) | [Generell hjälptext för Instans](https://libris.kb.se/katalogisering/help/workflow-instance) | [Generell hjälptext för Verk](https://libris.kb.se/katalogisering/help/workflow-work) |
| [Databaser](#databaser) | [Identifikator](#identifikator) | [Verkets titel](#verkets-titel) | 
| | [Utgivningssätt](#utgivningssatt) | [Medverkan och funktion](#medverkan-och-funktion) |
| | [Medietyp](#medietyp) | [Språk](#sprak) |
| | [Bärartyp](#barartyp) | [Genre form](#genre-form) |
| | [Titel](#titel) | [Klassifikation](#klassifikation) |
| | [Upphovsuppgift](#upphovsuppgift) | [Ämne](https://libris.kb.se/katalogisering/help/workflow-general-sh) |
| | [Utgivning](#utgivning) | [Innehållstyp](#innehallstyp) |
| | [Tillhörande media](#tillhorande-media) | [Sammanfattning av innehåll](#sammanfattning-av-innehall) |
| | [Frekvens](#frekvens) |  |
| | [Alfabet](#alfabet) |  |
| | [Anmärkning](#anmarkning)| | 
| | [Behandling vid titeländring](#behandling-vid-titelandring)| | 


## Inledning
Beskrivningen av en elektronisk integrerande resurs, t.ex. en webbplats eller en databas, innehåller följande tre delar:  
* [Adminmetadata](https://libris.kb.se/katalogisering/help/workflow-adminmetadata) - administrativa data om instansbeskrivningen, såsom kontrollnummer och beskrivningsnivå
* [Instans](https://libris.kb.se/katalogisering/help/workflow-instance) - instans kan också kallas utgåva eller manifestation. Exempel på egenskaper under Instans är utgivningsplats, utgivare och startår, bärartyp, medietyp.
* [Verk](https://libris.kb.se/katalogisering/help/workflow-work) – återger egenskaper för det abstrakta verket såsom medverkan och funktion, ämne, klassifikation, språk och innehållstyp. Verksbeskrivningen ligger under rubriken Instans av verk.

Många av egenskaperna finns redan i mallen Databas/webbplats, andra kan behöva läggas till. För instruktioner om att lägga till eller ta bort egenskaper, länka till entitet, skapa lokal entitet och om hur formuläret fungerar i övrigt, se Redigering i vänstermenyn. För en förhandspost, använd gärna Berika från mall och välj Databas/webbplats.  

För information om katalogregler, skrivregler och övriga katalogiseringsanvisningar, [se Anvisningar för katalogisering - RDA](http://www.kb.se/rdakatalogisering/Anvisningar/Arbetsfloden/Tryckta-seriella-resurser/ "Anvisningar för katalogisering - RDA") och [RDA Toolkit](https://access.rdatoolkit.org/).

[Se även instruktionsfilmer på KB:s Youtubekanal](https://www.youtube.com/playlist?list=PLZVkEICvA5-GRT2oJQmLgq_2Pksx6zYPy).   

## Adminmetadata
[Använd generell hjälptext för Adminmetadata](https://libris.kb.se/katalogisering/help/workflow-adminmetadata).

### Databaser
De bibliotek som önskar kan använda databasposterna för att skapa och underhålla egna listor över de (avtalsbundna och fritt tillgängliga) databaser som är tillgängliga för användarna. För att underlätta detta bör databasposten kompletteras med koden DBAS i Bibliografikod och beståndspost upprättas även i de fall posten avser en fritt tillgänglig databas.

* Bibliografi/Bibliotek/Sigel (bibliography/Library/sigel = 042 #9)
</br>Skriv in koden.</br>
```DBAS```

## Instans
För att lägga till egenskaper under Instans, klicka på plustecknet i redigeringsvyn (den stora runda plusikonen under Verktygsikonen - Lägg till egenskaper under: Elektronisk). Sök fram egenskapen och välj den genom att klicka på plustecknet vid egenskapens namn.

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
  
### Utgivningssatt
* Utgivningssätt (issuanceType)  
  Välj från lista.  
  ```Integrerande resurs```
  
### Medietyp
* Medietyp (mediaType/Mediatype = 337 #b)  
  Länka till entiteten:  
  ```dator (= c)``` 
  
### Barartyp  
* Bärartyp (carrierType/CarrierType = 338 #b)  
  Länka till entiteten:</BR>
  ```onlineresurs (= c)```
   
  Om koden "r" (= fjärranslutning) behövs i 007/01 (= särskild bärarbeteckning) för bibliotekets lokala system, länka till entiteten:</BR>
  ```Onlineresurs (= r)```</BR>
  
  Om koden "o" (= onlineutgåva) behövs i 008/23 (= form för manifestationen) för bibliotekets lokala system, länka till entiteten:</br>
  ```Onlineutgåva (= o)```</BR>
  
### Titel 

#### Huvudtitel 
Notera att egenskapen Allmän medieterm (marc:mediaTerm = 245 #h) (= Medieterm) inte ska ingå i beskrivningar som görs enligt RDA.
* Har titel/Titel/Huvudtitel (hasTitle/Title/mainTitle = 245 #a)  
  Återge huvudtiteln som den förekommer i i den föredragna källan, [se RDA 2.2.2.4.2](http://access.rdatoolkit.org/rdachp2_rda2-9147.html).  
  ```Exempel: ARTbibliographies modern```  
  För en titel som börjar med bestämd eller obestämd artikel, ska artikeln fileras bort. Ange fileringsvärde genom att lägga till fileringsvärde (plustecknet vid Titel - Lägg till egenskaper under: Titel) och ange en siffra.  
[Se exempel i formathandboken för Libris/Voyager - Fileringsindikator](http://www.kb.se/katalogisering/Formathandboken/Fileringsindikator/)

Om en integrerande resurs byter huvudtitel görs normalt ingen ny beskrivning, [se RDA 2.3.2.12.3](http://access.rdatoolkit.org/rdachp2_rda2-3651.html). Ersätt den gamla titeln med den nya och ange den gamla huvudtiteln i Tidigare titel, se nedan. 

**Observera att för integrerande resurser som har ISSN gäller andra regler.** Om huvudtiteln genomgår en större förändring tilldelas resursen ett nytt ISSN och en ny beskrivning görs. Om en integrerande resurs med svenskt ISSN byter huvudtitel, meddela [ISSN Sverige](https://www.kb.se/isbn-och-utgivning/issn-.html).

#### Övrig titelinformation (undertitel)
* Har titel/Titel/Övrig titelinformation (hasTitle/Title/subtitle = 245 #b)  
Skriv in uppgiften under Övrig titelinformation. Om det finns flera undertitlar, skriv in dessa efter varandra i samma fält, åtskilda av mellanslag, kolon, mellanslag.

Om övrig titelinformation läggs till, tas bort eller ändras i resursen, uppdatera Övrig titelinformation så att den speglar aktuell version om det bedöms vara viktigt för identifikation eller åtkomst, [se RDA 2.3.4.7.3](http://access.rdatoolkit.org/rdachp2_rda2-3909.html).

#### Akronymer/Del av huvudtitel  
Används för akronymer som är en del av huvudtiteln.  
* Har titel/Del av huvudtitel/Huvudtitel (hasTitle/Titleportion/mainTitle = 245 0/- #a)  
  Skriv in uppgiften under Huvudtitel.  
  ```Exempel: ABM```
  
#### Parallelltitel
Ange parallelltitel här. Upprepa inte parallelltitel efter Har titel/Titel/Huvudtitel (245 #a) med interpunktion.
* Har titel/Parallelltitel/Huvudtitel (hasTitle/ParallelTitle/mainTitle = 246 1/1 #a)<br/>
För en titel som börjar med bestämd eller obestämd artikel, ska artikeln fileras bort. Lägg till fileringsvärde och ange en siffra.

Om en parallelltitel läggs till, tas bort eller ändras i resursen, uppdatera Parallelltitel så att den speglar aktuell version, [se RDA 2.3.3.5.3](http://access.rdatoolkit.org/rdachp2_rda2-3773.html). En tidigare parallelltitel som bedöms vara viktig för identifikation eller åtkomst kan ligga kvar och den nya parallelltiteln läggas till. Tidsintervall för den tidigare parallelltiteln kan preciseras under Täckning eller tillkomst.
* Har titel/Parallelltitel/Täckning eller tillkomst (hasTitle/ParallellTitle/coverage = 246 1/1 #f)<br/>
```Exempel: 2003-2008```

#### Varianttitel   
Används för stavningvarianter eller varianter av titeln som förekommer i resursen och som man vill göra sökbara. Vid förändringar i huvudtiteln, se Tidigare titel.
För att lägga till varianttitel, klicka på plustecknet vid Har titel (lägg till titel) och välj typ Varianttitel.  
* Har titel/Varianttitel/Huvudtitel (hasTitle/VariantTitle/mainTitle = 246 1/_ #a)  
  Skriv in uppgiften under Huvudtitel.    
  ```Exempel: ART bibliographies modern```   

#### Tidigare titel
Om resursen byter titel ange den tidigare titeln här. Tidsintervall kan preciseras under Täckning eller tillkomst (se nedan).   
* Har titel/Tidigare titel/Huvudtitel (hasTitle/FormerTitle/mainTitle = 247 1/0 #a)    

* Har titel/Tidigare Titel/Täckning eller tillkomst (hasTitle/FormerTitle/coverage = 246 #f)    
  ```Exempel: 2005-2009``` 
  
### Upphovsuppgift
* Upphovsuppgift (responsibilityStatement = 245 #c)

Om upphovsuppgiften ändras i resursen, uppdatera Upphovsuppgift så att den speglar aktuell version. Gör en anmärkning om den tidigare upphovsuppgiften, om det är viktigt för identifikation eller åtkomst, [se RDA 2.4.1.10.3](http://access.rdatoolkit.org/rdachp2_rda2-4776.html).
    
### Utgivning
* Utgivning  
Välj typ från lista. För databaser och webbplatser, använd Primär utgivning. 

#### Utgivningsland
* Land (country = 008/15-17)  
  Länka till entitet.  I mallen är "Sverige" förifyllt. Ändra vid behov. Länka till entitet.<br/>
  ```Exempel: Sverige (sw)```<br/>

Om utgivningslandet ändras i resursen, uppdatera Land så att det speglar aktuell version.
  
#### Utgivningsplats
* Plats/Plats/Benämning (= Utgivningsort) (place/label = 264 -/1 #a)<br/> 
  ```Exempel: Örebro```<br/> 

Om utgivningsorten ändras i resursen, uppdatera Plats så att den speglar aktuell version. Gör en anmärkning om tidigare utgivningsort om det är viktigt för identifikation eller åtkomst, [se RDA 2.8.1.5.3](http://access.rdatoolkit.org/rdachp2_rda2-6444.html).
  
#### Utgivarnamn
* Agent/Benämning (= Utgivarnamn) (agent/label = 264 -/1 #b)  

Om utgivarnamnet ändras i resursen, uppdatera Agent så ett den speglar aktuell version. Gör en anmärkning om tidigare utgivare om det är viktigt för identifikation eller åtkomst, [se RDA 2.8.1.5.3](http://access.rdatoolkit.org/rdachp2_rda2-6444.html).
    
#### År och datum 
För instruktioner om hur man anger utgivningstid för integrerande resurser, [se RDA 2.8.6.5](http://access.rdatoolkit.org/rdachp2_rda2-6867.html).
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
* Datum (date = 264 -/1 #c)  
  Datum får innehålla text och interpunktionstecken.  
  För att ange utgivningsdatum med fler än fyra positioner, till exempel klamrade årtal, skriv in det här. Det kommer att exporteras till marcpostens 264 -/1 #c.  
  För att ange år utan klamrar eller andra tecken, använd endast Startår och Slutår.  
  Skriv in uppgiften.
  <br/>```Exempel:```
  * ```[2012-2013]```
  * ```[1988-]```
  
### Tillhorande media
* Tillhörande media/Mediaobjekt/URI (associatedMedia/Mediaobject/uri = 856 4/0 #u)<br/>
  Använd Tillhörande media för **fritt tillgängliga resurser** för att lägga in en elektronisk adress till resursen. Lägg till Mediaobjekt under Tillhörande media. Välj Skapa lokal entitet. Lägg till egenskapen URI. Klistra in aktuell URI.
* Tillhörande media/Mediaobjekt/Offentlig anmärkning (associatedMedia/Mediaobject/marc:publicNote = 856 4/0 #z)<br/>
  Lägg till offentlig anmärkning.
  <br/>```Exempel: Fritt tillgänglig```

För **avtalsbundna resurser** ange URI för den leverantörsplattform genom vilken biblioteket har tillgång till resursen i beståndsposten. Instansbeskrivningen kan kompletteras med URI i Tillhörande media till databasens generella inloggningssida. Förtydliga med lämplig anmärkningsfras i Offentlig anmärkning, t.ex. "Inloggning krävs".

### Frekvens   
* Frekvens (frequency)  
  * Frekvensterm (008/18)  
    Länka till entitet.  
    ```Exempel: kontinuerligt (k = Continuously updated)```  
**Från och med version 1.7 behöver man inte längre ange "u" för okänd frekvens. Det skapas automatiskt vid marcexport om frekvens inte har angetts.**
  * Regelbundenhet (008/19)  
    **Från och med version 1.7 behöver man inte längre ange Regelbundenhet. "Inget försök att koda" skapas automatiskt vid marcexport.**
  
### Alfabet    
* Alfabet/skriftart (marc:alphabet = 008/33)   
  Länka till entitet.  
  ```Exempel: b (= Extended roman = Latinskt alfabet med diakriter och specialtecken (a-ö))```

### Anmarkning
* Anmärkning/Anmärkning/Benämning (hasNote/Note/label = 500 #a)  
För integrerande resurser med fjärråtkomst anges alltid datum för när resursen beskrevs.<br/>
```Exempel: Katalogiserad 2020-02-16```<br/>
Gör anmärkningar om t.ex. tidigare upphovsuppgift eller utgivare om det bedöms vara viktigt för identifikation eller åtkomst.<br/> 
```Exempel: Utgiven av Södertörns högskolebibliotek, 2009-2017```
  
### Behandling vid titelandring 
* Behandling vid titeländring (marc:typeOfEntry = 008/34)  
  Länka till entitet.  
  ```Exempel: 2 (= Integrating entry = Katalogposten avser integrerande resurs)```

## Verk
* Instans av Verk/Text (instanceOf/Work/Text)  
  Skapa verket som lokal entitet (bryt inte ut verket till en länkbar entitet). Vi rekommenderar att du skapar verket som lokal entitet under den första tiden som Nya Libris är i drift. Vi återkommer med anvisningar för att skapa verk som länkbara entiteter. Denna hjälptext beskriver exempel på verk som lokal entitet. Det betyder att du anger de uppgifter som listas här nedan, under Instans av Verk, utan att klicka på länksymbolen (Länka entitet) vid Instans av Verk.  
[Läs mer om Verk och Instans på Libris informationssidor på kb.se](https://www.kb.se/samverkan-och-utveckling/nytt-fran-kb/nyheter-samverkan-och-utveckling/2018-05-30-verk-och-instans-i-startversionen-av-nya-libris.html). 

För att lägga till egenskaper under Instans av Verk, klicka på plustecknet till höger om Instans av Verk - Lägg till egenskaper under: Text. Sök fram egenskapen och välj den genom att klicka på plustecknet vid egenskapens namn.

### Verkets titel
Ange vid behov den föredragna titeln för verket här. Normalt är dock den föredragna titeln för en integrerande resurs densamma som huvudtiteln och behöver därför inte anges i verksbeskrivningen. [För instruktioner om Föredragen titel för verk, se Konstruera sökingångar för verk och uttryck i Anvisningar för katalogisering - RDA](http://www.kb.se/rdakatalogisering/Anvisningar/Allmanna-anvisningar/Sokingangar-for-verk-och-uttryck/). 

#### Verk utan Primär medverkan
*	Uttryck av/Verk/Har titel/Titel/Huvudtitel (expressionOf/Work/hasTitle/Title/mainTitle (= 130 ‡a)  
Föredragen titel för ett verk utan Primär medverkan anges här.  

#### Verk med Primär medverkan
* Har titel/Titel/Huvudtitel (hasTitle/Title/mainTitle = 240 1/0 ‡a)</BR>
Föredragen titel för ett verk med primär medverkan med anges här.  

Om en föredragen titel för verket är angiven i verksbeskrivningen och huvudtiteln i den integrerande resursen ändras, uppdatera den föredragna titeln så att den speglar aktuell version, [se RDA 6.1.3.3.2](http://access.rdatoolkit.org/rdachp6_rda6-1930.html).

**Observera att för integrerande resurser som har ISSN gäller andra regler.** Om huvudtiteln genomgår en större förändring tilldelas resursen ett nytt ISSN och en ny beskrivning görs. Om en integrerande resurs med svenskt ISSN byter huvudtitel, meddela [ISSN Sverige](https://www.kb.se/isbn-och-utgivning/issn-.html).

### Medverkan och funktion  
Under Medverkan och funktion, ange relationer till de agenter som medverkar i verket. Relationer till utgivare (710) anges för närvarande också här.
[Följ instruktioner i hjälptexten Relationer till Agent](https://libris.kb.se/katalogisering/help/workflow-agent-org-instance)  
  
* Medverkan och funktion/Primär medverkan/Agent/Person (100 1/- #a)
* Medverkan och funktion/Primär medverkan/Agent/Organisation (110 2/- #a) 
* Medverkan och funktion/Primär medverkan/Funktion (100/110 #4)   
* Medverkan och funktion/Medverkan/Agent/Person (700 1/- #a) 
* Medverkan och funktion/Medverkan/Agent/Organisation (710 2/- #a)
* Medverkan och funktion/Medverkan/Agent/Funktion (700/710 #4)

Om en agent är angiven i Primär medverkan och det sker en förändring i upphovsansvaret för den integrerande resursen, uppdatera Primär medverkan så att den speglar aktuell version, [se RDA 6.1.3.3.1](http://access.rdatoolkit.org/rdachp6_rda6-1916.html).

Om en agent är angiven i Medverkan, t.ex. en utgivare, och utgivaren ändras eller om en ny utgivare tillkommer, lägg till utgivaren i en ny Medverkan om det bedöms vara viktigt för identifikation eller åtkomst.
  
### Sprak
* Språk (language = 008/35-37)  
  Länka till entitet. I mallen är "svenska" förifyllt. Ändra vid behov.<br/> 
  ```Exempel: svenska (swe)```  
   
### Genre form 
* Genre/form - saogf-termer (genreForm = 655 -/7 #a, #2 saogf)</br>
  Länka till entitet.
  <br/>```Exempel:```
  * ```Webbplatser```
  * ```Databaser```
  * ```Referensdatabaser```
  * ```Artikeldatabaser```
  
* Genre/form - Typ av fortlöpande resurs (genreForm/marc:Periodical = 008/21)  
  Välj Typ av fortlöpande resurs i listan över typer, under Genre/form. Trunkera genom att trycka på mellanslagstangenten eller med * i sökrutan. Välj rätt entitet genom att klicka på Lägg till. 
<br/>```Exempel:```
  * ```Databas (= d)```
  * ```Uppdaterande webbplats (= w)```
         
### Klassifikation  
#### DDK-klassifikation  

* Klassifikation/DDK-klassifikation/Kod (classification/ClassificationDdc/code = 082 0/4 #a)  
  Skriv in uppgiften.  
  ```Exempel: 327.12092```
* Klassifikation/DDK-klassifikation/Klassifikationsupplaga (classification/ClassificationDdc/edition = 082 #2)  
  ```Exempel: full```  
*  Parallell upplagebeteckning/Upplagespecifik upphovsuppgift (classification/ClassificationDdc/editionEnumeration = 082 #2)  
  ```Exempel: 23/swe```  
  
 För att lägga till DDK-klassifikation:  
  * Om posten har Klassifikation/Klassifikation (till exempel SAB-klassifikation) men saknar Klassifikation/DDK-klassifikation, lägg till ytterligare en förekomst av Klassifikation (plustecknet vid Klassifikation - lägg till klassifikation). Välj Skapa lokal entitet (längst ner i sidorutan till höger) och välj DDK-klassifikation. Skriv in uppgiften under Kod.  
  * Om posten helt saknar Klassifikation, lägg till Klassifikation genom att klicka på plustecknet vid Instans av Verk/Text (Lägg till egenskaper under: Text). Välj Klassifikation. Klicka på plustecknet vid Klassifikation (Lägg till klassifikation).  Välj Skapa lokal entitet (längst ner i sidorutan till höger) och välj DDK-klassifikation.  
   Skriv in uppgiften under Kod.  
  
#### Sekundär DDK-klassifikation  
Lägg till DDK-klassifikation (sekundär) genom att klicka på plusikonen vid Instans av Verk/Text (Lägg till egenskaper under: Text) och välja DDK-klassifikation (sekundär). Klicka sedan på plustecknet vid DDK-klassifikation (sekundär) (Lägg till ddk-klassifikation) och välj Skapa lokal entitet (längst ner i sidorutan till höger). Skriv in uppgiften under Kod.  
* Klassifikation/DDK-klassifikation/Kod (additionalClassificationDdc/ClassificationDdc/code = 083 0/- #a)  
  Skriv in uppgiften.  
  ```Exempel: 791.430233092```
* Klassifikation/DDK-klassifikation/Klassifikationsupplaga (classification/ClassificationDdc/edition = 083 #2)  
  ```Exempel: full```  
*  Parallell upplagebeteckning/Upplagespecifik upphovsuppgift (classification/ClassificationDdc/editionEnumeration = 083 #2)  
  ```Exempel: 23/swe``` 
   
#### SAB-klassifikation  
* SAB-klassifikation  
  För att lägga till annan klassifikation, till exempel SAB-klassifikation:  
  * Om posten har Klassifikation/DDK-klassifikation men saknar Klassifikation/Klassifikation (till exempel SAB-klassifikation), lägg till ytterligare en förekomst av Klassifikation (plustecknet vid Klassifikation - lägg till klassifikation). Välj Skapa lokal entitet (längst ner i sidorutan till höger) och välj Klassifikation. Skriv in uppgiften under Kod.  
  * Om posten helt saknar Klassifikation, lägg till Klassifikation genom att klicka på plustecknet vid Instans av Verk/Text (Lägg till egenskaper under: Text). Välj Klassifikation. Klicka på plustecknet vid Klassifikation (Lägg till klassifikation).  Välj Skapa lokal entitet (längst ner i sidorutan till höger) och välj Klassifikation.  
   Skriv in uppgiften under Kod.   
* Klassifikation/Klassifikation/Kod (classification/Classification/code = 084 0/4 #a)  
     Skriv in uppgiften.  
  ```Exempel: Sei-e```   
* Klassifikation/Ingår i system/Konceptsystem/Kod (classification/Classification/inScheme/ConceptScheme/code = 084 #2)  
 ```Exempel: kssb```  
* Klassifikation/Ingår i system/Konceptsystem/Version (classification/Classification/inScheme/ConceptScheme/version = 084 #2)  
 ```Exempel: 8``` 

### Amne  
[Se hjälptexten Ämnesord i Libris](https://libris.kb.se/katalogisering/help/workflow-general-sh) 
  
### Innehallstyp
* Innehållstyp (contentType/ContentType = 336 #b)  
  Länka till entitet.  
  ```Exempel: text (= txt)```

### Sammanfattning av innehall    
* Sammanfattning av innehåll/Sammanfattning/Benämning (summary/Summary/label = 520 #a)</BR>
Lägg till Sammanfattning av innehåll. Välj Sammanfattning av innehåll. Lägg till Sammanfattning. Skriv in uppgiften under Benämning.
     
* Typ av sammanfattning/typ av innehållsbeskrivning (marc:summaryType = 520 ind1)
Sök fram och lägg till Typ av sammanfattning. Välj typ från lista.
```Exempel: Ej preciserad```

