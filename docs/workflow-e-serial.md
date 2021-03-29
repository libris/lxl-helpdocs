---
section: Materialtyper
title: Elektronisk seriell resurs
order: 43
date: 2021-03-17
tags:
- seriell resurs
- e-tidskrift
- elektronisk tidskrift
- elektronisk monografiserie
--- 

# Elektronisk seriell resurs
Denna hjälptext ger kortfattade instruktioner för de vanligaste egenskaperna för en elektronisk seriell resurs, t ex en e-tidskrift. För utförliga instruktioner, se de generella hjälptexterna för Adminmetadata, Instans och Verk, se nedan.

[Inledning](#inledning) 

| [Adminmetadata](#adminmetadata) | [Instans](#instans) | [Verk](#verk) | 
| ----------- |  ----------- | ----------- |
|  [Adminmetadata - Metadatabyrån](https://metadatabyran.kb.se/beskrivning/specialanvisningar/adminmetadata-i-libris) | [Generell hjälptext för Instans](https://libris.kb.se/katalogisering/help/workflow-instance) | [Generell hjälptext för Verk](https://libris.kb.se/katalogisering/help/workflow-work) |
| | [Identifikator](#identifikator) | [Verkets titel](#verkets-titel) |
| | [Utgivningssätt](#utgivningssätt) | [Medverkan och funktion](#medverkan-och-funktion) | 
| | [Medietyp](#medietyp) | [Språk](#språk) |
| | [Bärartyp](#bärartyp) | [Genre/form](#genre-form) |
| | [Titel](#titel) | [Klassifikation](#klassifikation) |
| | [Utgivning](#utgivning) | [Ämne](https://libris.kb.se/katalogisering/help/workflow-general-sh) |
| | [Tillhörande media](#tillhörande-media) | [Innehållstyp](#innehållstyp) |
| | [Anmärkning](#anmärkning)| |
| | [Frekvens](#frekvens) | |
| | [Alfabet](#alfabet) | |
| | [Behandling vid titeländring](#behandling-vid-titeländring) |  |
| | [Numrering av seriell resurs](#numrering-av-seriell-resurs)| |
| | [Relationer](#relationer) | | 



## Inledning
Beskrivningen av en elektronisk seriell resurs innehåller följande tre delar:  
* [Adminmetadata - Metadatabyrån](https://metadatabyran.kb.se/beskrivning/specialanvisningar/adminmetadata-i-libris) - administrativa data om instansbeskrivningen, såsom kontrollnummer och beskrivningsnivå
* [Instans](https://libris.kb.se/katalogisering/help/workflow-instance) - instans kan också kallas utgåva eller manifestation. Exempel på egenskaper under Instans är utgivningsplats, utgivare och utgivningsår och bärartyp.
* [Verk](https://libris.kb.se/katalogisering/help/workflow-work) – återger egenskaper för det abstrakta verket såsom medverkan och funktion, ämne, klassifikation, språk och innehållstyp. Verksbeskrivningen ligger under rubriken Instans av verk.

Många av egenskaperna finns redan i mallen Elektronisk seriell resurs, andra kan behöva läggas till. För instruktioner om att lägga till eller ta bort egenskaper, länka till entitet, skapa lokal entitet och om hur formuläret fungerar i övrigt, se Redigering i vänstermenyn. För en förhandspost, använd gärna Berika från mall och välj Elektronisk  seriell resurs.  

För information om katalogiseringsregler och Librispraxis, se [Seriella resurser i Metadatabyrån](https://metadatabyran.kb.se/beskrivning/materialtyper/seriella-resurser) samt se [RDA Toolkit](https://access.rdatoolkit.org/).

Se även [instruktionsfilmer på KB:s Youtubekanal](https://www.youtube.com/playlist?list=PLZVkEICvA5-GRT2oJQmLgq_2Pksx6zYPy).   

## Adminmetadata
[Adminmetadata - Metadatabyrån](https://metadatabyran.kb.se/beskrivning/specialanvisningar/adminmetadata-i-libris)

## Instans
För att lägga till egenskaper under Instans, klicka på plustecknet i redigeringsvyn (den stora runda plusikonen under Verktygsikonen) - Lägg till egenskaper under: Elektronisk. Sök fram egenskapen och välj den genom att klicka på plustecknet vid egenskapens namn eller på egenskapens namn.

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

### Utgivningssätt
* Utgivningssätt (issuanceType)  
  Välj från lista:  
  ```Seriell resurs```

### Medietyp
* Medietyp (mediaType/Mediatype = 337 #b)  
  Länka till entiteten:  
  ```dator, computer (kod = c)``` 

### Bärartyp  
* Bärartyp (carrierType/CarrierType = 338 #b)  
  Länka till entiteten:  
  ```onlineresurs, online resource (kod = cr)```

 Om koden "r" (= fjärranslutning) behövs i 007/01 (= särskild bärarbeteckning) för bibliotekets lokala system, länka till entiteten:</BR>
  ```Onlineresurs, r```</BR>
  
 Om koden "o" (= onlineutgåva) behövs i 008/23 (= form för manifestationen) för bibliotekets lokala system, länka till entiteten:</br>
  ```Onlineutgåva, o```</BR>

### Titel
Observera att egenskapen Allmän medieterm (marc:mediaTerm = 245 #h) (= Medieterm) inte ska ingå i beskrivningar som görs enligt RDA.

#### Nyckeltitel
* Har titel/Nyckeltitel/Huvudtitel    
(hasTitle/KeyTitle/mainTitle = 222 -/0 #a)  
För svenska seriella resurser ansvarar ISSN Sverige för nyckeltiteln.  
Skriv in uppgiften.  
 ```Exempel:  Advokaten```

* Har titel/Nyckeltitel/Särskiljande tillägg  
(hasTitle/KeyTitle/qualifier = 222 #b)  
Skriv in uppgiften, inom parentes.  
```Exempel: (Stockholm. Online)```

#### Huvudtitel    
* Har titel/Titel/Huvudtitel (hasTitle/Title/mainTitle = 245 #a)  
  Återge huvudtiteln som den förekommer i källan, se [RDA 2.2.2.4.2.](http://access.rdatoolkit.org/rdachp2_rda2-9147.html)<br/>
  ```Exempel: Advokaten```  
  För en titel som börjar med bestämd eller obestämd artikel, ska artikeln fileras bort. Ange fileringsvärde genom att lägga till fileringsvärde (plustecknet vid Titel - Lägg till egenskaper under: Titel) och ange en siffra.   
 Se exempel på sidan [Filering av titel - Metadatabyrån](https://metadatabyran.kb.se/beskrivning/generella-anvisningar---rda/manifestation-instans/titel/filering-av-titel)

#### Övrig titelinformation
* Har titel/Titel/Övrig titelinformation (hasTitle/Title/subtitle = 245 #b)  
  Om det finns flera undertitlar, skriv in dessa efter varandra i samma fält, åtskilda av mellanslag, kolon, mellanslag.   
  ```Exempel: tidskrift för Sveriges Advokatsamfund```

#### Varianttitel   
Används till exempel för felaktigheter och tillfälliga variationer/mindre förändringar i huvudtiteln. Felaktigheter kan specificeras med Typanmärkning och tillfälliga variationer/mindre förändringar i huvudtiteln kan preciseras med Täckning och tillkomst. 
För att lägga till varianttitel, klicka på plustecknet vid Har titel (lägg till titel) och välj typ Varianttitel.  
* Har titel/Varianttitel/Typanmärkning (hasTitle/VariantTitle/typeNote = 246 1/_ #i)  
 Anmärkningstext som i ett sökgränssnitt ska föregå varianttiteln. Används också för att ange typ av varianttitel som inte finns i listan, t ex Titelrubrik. Lägg vid behov till Typanmärkning (plustecknet vid Varianttitel - lägg till egenskaper under: Varianttitel, välj Typanmärkning).   
  ```Exempel: Titel felstavad i nummer 1 (2006):```  
* Har titel/Varianttitel/Huvudtitel (hasTitle/VariantTitle/mainTitle = 246 1/_ #a)     
  ```Exempel: Housing sarts```    

#### Tidsbestämd titelvariant   
Avser tidsbestämda titelvariationer. Volym/häfte och/eller tidsintervall preciseras under Täckning eller tillkomst (se nedan).   
* Har titel/Varianttitel/Huvudtitel (hasTitle/VariantTitle/mainTitle = 246 1/_ #a)      
  ```Exempel: Hushållningssällskapets magasin```  
 
* Har titel/Varianttitel/Täckning eller tillkomst (hasTitle/DistinctiveTitle/coverage = 246 #f)   
  ```Exempel: 2011, nr 4-2012, nr 4``` 

#### Delbeteckning
* Har titel/Titel/Har del/Titeldel/Delbeteckning (hasTitle/Title/hasPart/TitlePart/partNumber = 245 #n)  

#### Deltitel  
* Har titel/Titel/Har del/Titeldel/Deltitel (hasTitle/Title/hasPart/TitlePart/partName = 245 #p)

#### Akronymer/Del av huvudtitel  
Används för akronymer som är en del av huvudtiteln.  
* Har titel/Del av huvudtitel/Huvudtitel (hasTitle/Titleportion/mainTitle = 245 0/- #a)  
  ```Exempel: ACMO```  

### Utgivning
* Utgivning  
  Välj typ från lista. För seriella resurser med endast en utgivare, använd Primär utgivning.  

  För en seriell resurs som byter utgivare, låt Primär utgivning ligga kvar (för den första utgivningsperioden). Lägg till Utgivning för att beskriva nästa utgivningsperiod. Lägg till Sekvens av uppgifter under Utgivning och välj Nuvarande/senaste utgivare. Vid behov, ändra uppgift om Sekvens av uppgifter för mellanliggande utgivningsperioder. 

#### Utgivningsland
* Land (country = 008/15-17)  
  Länka till entitet.<br/>
  ```Exempel: Sverige (sw)```<br/>

#### Utgivningsplats
* Plats/Plats/Benämning (= Utgivningsort) (place/label = 264 -/1 #a)  
  För att lägga till Plats, klicka på plustecknet vid Primär utgivning (lägg till egenskaper under Primär utgivning) och välj Plats. Sök inte efter Plats som entitet. I rutan Skapa lokal entitet, längst ner i sidorutan till höger, skriv Plats och välj det.       
  ```Exempel: [Göteborg]```

#### Utgivarnamn
* Agent/Benämning (= Utgivarnamn) (agent/label = 264 -/1 #b)  
  För att lägga till Agent, klicka på Lägg till egenskaper under Primär utgivning och välj Agent. Sök inte efter Agent som entitet. I rutan Skapa lokal entitet, längst ner i sidorutan till höger, skriv Agent och välj det.         
  ```Exempel: Sveriges advokatsamfund```  
  Om flera utgivare ska anges, lägg till Har del (hasPart) under Primär utgivning. Skapa Utgivning som lokal entitet (plustecknet vid Har del - Lägg till entitet). I rutan Skapa lokal entitet, längst ner i sidorutan till höger, skriv Utgivning och välj *** Utgivning. Upprepa Utgivning som lokal entitet genom att duplicera entiteten Utgivning.  
Ange Plats/Plats/Benämning och Agent/Agent/Benämning och vid behov Datum inom respektive utgivningsavsnitt (angående Datum, se anvisningar nedan). Samtliga utgivare med Plats och Agent ska ligga inom Har del/Utgivning.
Land, År och eventuellt Datum  ska ligga inom Primär utgivning.  
  [Se exempelpost i Libris katalogisering](https://libris.kb.se/katalogisering/w4rp4hlwtr5lctjr#it).  

#### År och datum    
* Startår (startYear = 008/7-10)  
  Startår får endast innehålla siffror (0-9) och bokstaven u. Startår ska endast förekomma inom Primär utgivning.  
  För att ange ett startår utan klamrar eller andra tecken, ange det endast här. Det kommer då att exporteras till både marcpostens 08/07-10 och 264 -/1 #c. Bindestreck sätts automatiskt. För att ange årtal med klamrar eller andra tecken utöver fyra positioner, använd Datum. 
  För att lägga till Startår, klicka på plustecknet vid Primär utgivning (Lägg till egenskaper under: Primär utgivning) och välj Startår.    
   ```Exempel: 2011```  
* Slutår (endYear = 008/11-14)  
  Slutår får endast innehålla siffror (0-9) och bokstaven u. Slutår ska endast förekomma inom Primär utgivning.  
  För att ange ett slutår utan klamrar eller andra tecken, ange det endast här. Det kommer då att exporteras till både marcpostens 08/11-14 och 264 -/1 #c. Bindestreck sätts automatiskt. För att ange årtal med klamrar eller andra tecken utöver fyra positioner, använd Datum.   
  Om slutår inte anges, sätts utgivningsstatus (008/06) automatiskt till "c = Utgivning pågår".  
  Om slutår anges, sätts utgivningsstatus (008/06) automatiskt till "d = Utgivning avslutad".  
   För att lägga till Slutår, klicka på plustecknet vid Primär utgivning (Lägg till egenskaper under: Primär utgivning) och välj Slutår.  
  ```Exempel: 2013```     
  För att ange slutår för senaste utgivningsperiod (264 -/3 #c), notera först vilket startåret för utgivningsperioden är, ta bort Startår och lägg till Datum. Skriv in hela datumangivelsen med startår och slutår (se nedan under Datum).    
* Datum (date = 264 -/1 #c)  
  Datum får innehålla text och interpunktionstecken.  
  För att ange utgivningsdatum med fler än fyra positioner, till exempel klamrade årtal, skriv in det här. Det kommer att exporteras till marcpostens  264 -/1 #c.  
  För att ange år utan klamrar eller andra tecken, använd endast Startår och Slutår.  
  ```Exempel:```
  * ```[2012-2013]```
  * ```[1988-]```

### Tillhörande media 
* Tillhörande media/Mediaobjekt/URI (associatedMedia/Mediaobject/uri = 856 4/0 #u)  
Om instansbeskrivningen gäller en **fritt tillgänglig elektronisk resurs**, använd Tillhörande media för att lägga in en elektronisk adress till resursen. Lägg till Mediaobjekt under Tillhörande media. Välj Skapa lokal entitet. Lägg till egenskapen URI. Klistra in aktuell URI.
* Tillhörande media/Mediaobjekt/Offentlig anmärkning  
(associatedMedia/Mediaobject/marc:publicNote = 856 4/0 #z)   
  Lägg till Offentlig anmärkning. 
   <br/>```Exempel: Fritt tillgänglig via tidskriftens webbplats``` 

**För avtalsbundna eller endast lokalt tillgängliga elektroniska resurser** ange URI i beståndsposten. Instansbeskrivningen kan kompletteras med URI i Tillhörande media till en generell inloggningssida för resursen. Förtydliga med lämplig anmärkningsfras i Offentlig anmärkning, t.ex. "Inloggning krävs".  

### Anmärkning
* Anmärkning/Anmärkning/Benämning (hasNote/Note/label = 500 #a)  
  Skriv in allmänna anmärkningar här.  
  Skriv in uppgiften under Benämning.  

### Frekvens   
* Frekvens (frequency)  
  * Frekvensterm (008/18)  
    Länka till entitet.  
    ```Exempel: var tredje månad (q = quarterly)```  
**Från och med version 1.7 behöver man inte längre ange "u" för okänd frekvens. Det skapas automatiskt vid marcexport om frekvens inte har angetts.**
  * Regelbundenhet (008/19)  
    **Från och med version 1.7 behöver man inte längre ange Regelbundenhet. "Inget försök att koda" skapas automatiskt vid marcexport.**

### Alfabet    
* Alfabet/skriftart (marc:alphabet = 008/33)   
  Länka till entitet.  
  ```Exempel: b (= Extended roman = Latinskt alfabet med diakriter och specialtecken (a-ö))```

### Behandling vid titeländring 
* Behandling vid titeländring (marc:typeOfEntry = 008/34)  
  Länka till entiteten:<br/> 
  ```Exempel: 0 (= Successive entry = Titeländring ger upphov till ny post)```

### Numrering av seriell resurs  
* Har numrering av seriell resurs/Numrering av seriell resurs/Benämning  
  (hasNumberingofSerials/NumberingofSerials/label = 362 0/- #a)   
  ```Exempel: 2011, 4-2013, 2```

### Relationer
För relationer (länkfält): Annat bärarformat (776), Fortsätter (780 0/0), Fortsättes av (785 0/0), med flera: 
sök fram och lägg till egenskapen (relationen) genom att klicka på plustecknet i verktygsmenyn (Lägg till egenskaper). Sök sedan fram och lägg till den seriella resursen som länken ska gå till.  

![Annat bärarformat 776](776elektroniskseriell.png)

Här följer ett urval av de relationer som kan läggas till:  

Fortsätter (continues = 780 0/0)  
Fortsätter delvis (continuesInPartBy = 780 0/1)  
Föregående (precededBy = 780 0/2)  
Ersätter delvis (precededInPartBy = 780 0/3)  
Sammanslagen med (mergerOf = 780 0/4) ([Se exempelpost i Libris katalogisering](https://libris.kb.se/katalogisering/5ng67r2h49lzkl9#it)  
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
Sammanslagen till (mergedToForm = 785 0/7) ([Se exempelpost i Libris katalogisering](https://libris.kb.se/katalogisering/tb4vcdf54hzlsr3#it)   

Använd Anmärkning (500) för att vid behov förtydliga typen av relation.

## Verk
* Instans av Verk/Text (instanceOf/Work/Text)

För att lägga till egenskaper under Instans av Verk, klicka på plustecknet till höger om Instans av Verk och verkstypen. Sök fram egenskapen och välj den genom att klicka på plustecknet vid egenskapens namn.

Läs mer om Verk och egenskaperna för Verk under [den generella beskrivningen av Verk](https://libris.kb.se/katalogisering/help/workflow-work).

### Verkets titel
Ange vid behov den föredragna titeln för verket. För instruktioner, se [Metadatabyrån - Föredragen titel för verket](https://metadatabyran.kb.se/beskrivning/generella-anvisningar---rda/verk-och-uttryck/foredragen-titel-for-verket). 

#### Verk utan Primär medverkan
*	Uttryck av/Verk/Har titel/Titel/Huvudtitel (expressionOf/Work/hasTitle/Title/mainTitle (= 130 ‡a)  
Föredragen titel för ett verk utan Primär medverkan anges här.  

#### Verk med Primär medverkan
* Har titel/Titel/Huvudtitel (hasTitle/Title/mainTitle = 240 1/0 ‡a)</BR>
Föredragen titel för ett verk med Primär medverkan med anges här.  

### Medverkan och funktion     
Följ instruktioner i [hjälptexten Relationer till Agent](https://libris.kb.se/katalogisering/help/workflow-agent-org-instance)  

* Medverkan och funktion/Medverkan/Agent (contribution/Contribution/agent = 710 2/- #a)  
  Länka till entitet. Börja alltid med att söka efter om agenten redan finns. Vid behov, skapa ny entitet för agent (se Skapa ny agent i hjälpsektionen). I undantagsfall, skapa lokal entitet.  
  ```Exempel: Sveriges advokatsamfund```  
* Medverkan och funktion/Medverkan/Agent/Funktion (contribution/Contribution/agent/role = 710 #4)   
  Länka till entitet. Klicka på plustecknet vid Funktion (Lägg till funktion) och sök fram funktionskod. Skriv in kod eller utskriven form i sökrutan eller tryck på mellanslagstangenten för att se alla koder. Välj kod genom att klicka på plustecknet vid koden eller på koden.    
För en sorterad lista på koder, se [Formathandboken för Libris/Voyager - Funktions- och relationskoder](https://katalogverk.kb.se/katalogisering/Formathandboken/Funktionskoder/index.html)    
  ```Exempel:  Utgivare (pbl = publisher)```

### Språk
* Språk (language = 008/35-37)  
  Länka till entitet.  
  ```Exempel: svenska (swe)```  
   För att ange att texten är på flera språk, t ex parallelltext, ange ytterligare en språkkod genom att klicka på plustecknet vid Språk (Lägg till språk) och söka fram ytterligare en entitet för ett språk och länka till den.  

### Genre form 
#### Typ av fortlöpande resurs  
* Genre/form - typ av fortlöpande resurs (genreForm/marc:Periodical = 008/21)  
  Länka till entitet.  
  För att söka efter entiteter inom Typ av fortlöpande resurs, välj Typ av fortlöpande resurs i listan över typer, under Genre/form. Trunkera genom att trycka på mellanslagstangenten eller med * i sökrutan. Välj rätt entitet genom att klicka på Lägg till. I mallen för Tryckt seriell resurs ligger Tidskrift. Vid behov, ändra.
<br/>```Exempel:```
  * ```p (Tidskrift = marc/Periodical)```
  * ```m (Monografiserie = marc/MonographicSeries```

### Klassifikation  
För anvisningar om hur man anger klassifikation, se hjälptexten [Verk](https://libris.kb.se/katalogisering/help/workflow-work#klassifikation): Klassifikation.

### Ämne  
Se hjälptexten [Ämnesord i Libris](https://libris.kb.se/katalogisering/help/workflow-general-sh) 

### Innehållstyp
* Innehållstyp (contentType/ContentType = 336 #b)  
  Länka till entitet.  
  ```Exempel: text, text (kod = txt)```
