---
section: Materialtyper
title: Bidrag
order: 35
date: 2021-03-19
tags:
- Bidrag
- Artikel
--- 

# Bidrag
Denna hjälptext ger kortfattade instruktioner för de vanligaste egenskaperna vid beskrivning av bidrag, t.ex. artiklar i tidskrifter eller kapitel i en monografi. För mer utförliga instruktioner, se de generella hjälptexterna för Adminmetadata, Instans och Verk, se innehållsförteckningen nedan. Det finns två mallar för bidrag, en för bidrag i tryckta publikationer och en för bidrag i elektroniska publikationer. Hjälptexten ger instruktioner för båda typerna.

## Innehåll   

[Inledning](#inledning)

| [Adminmetadata](#adminmetadata) | [Instans](#instans) | [Verk](#verk) | 
| ----------- | ----------- |  ----------- |
| [Adminmetadata - Metadatabyrån](https://metadatabyran.kb.se/beskrivning/specialanvisningar/adminmetadata-i-libris) | [Generell hjälptext för Instans](https://libris.kb.se/katalogisering/help/workflow-instance) | [Generell hjälptext för Verk](https://libris.kb.se/katalogisering/help/workflow-work) |
| | [Utgivningssätt](#utgivningssätt) | [Verkets titel](#verkets-titel) |
| | [Medietyp](#medietyp) | [Medverkan och funktion](#medverkan-och-funktion) | 
| | [Bärartyp](#bärartyp) | [Språk](#språk)  |
| | [Titel](#titel) | [Genre/form](#genre-form) |
| | [Upphovsuppgift](#upphovsuppgift) |[Klassifikation](#klassifikation)|
| | [Utgivning](#utgivning) |[Ämne](#ämne) |
| | [Anmärkning](#anmärkning)| [Innehållstyp](#innehållstyp) |
| | [Tillhörande media](#tillhörande-media) | [Sammanfattning av innehåll](#sammanfattning-av-innehåll)  |
| | [Är del av](#är-del-av)| |
| | [Placering i värdpublikation](#placering-i-värdpublikation) | |


## Inledning
Beskrivningen av ett bidrag innehåller följande tre delar:  
* [Adminmetadata - Metadatabyrån](https://metadatabyran.kb.se/beskrivning/specialanvisningar/adminmetadata-i-libris) - administrativa data om instansbeskrivningen, såsom kontrollnummer och beskrivningsnivå
* [Instans](https://libris.kb.se/katalogisering/help/workflow-instance) - instans kan också kallas utgåva eller manifestation. Exempel på egenskaper under Instans är titel, upphov, utgivning och bärartyp.
* [Verk](https://libris.kb.se/katalogisering/help/workflow-work) – återger egenskaper för det abstrakta verket såsom medverkan och funktion, ämne, klassifikation, språk och innehållstyp. Verksbeskrivningen ligger under rubriken Instans av verk.

Om bidraget är publicerat i flera olika publikationer och man vill beskriva det får man antingen skapa en beskrivning för varje publicering eller också göra en anmärkning som talar om att bidraget är publicerat på flera ställen.

För att länkningen mellan värdpublikation och ingående delar ska fungera i Webbsök behöver posten för värdpublikationen märkas.
Märkningen görs genom att lägga in en Systemteknisk anmärkning i posten för värdpublikationen.</BR>

* Systemteknisk anmärkning/Benämning (technicalNote/label = 599 #a)</BR>
  Skriv in anmärkningen under Benämning.</BR>
  ```Indexeringslänk```

Många av egenskaperna finns redan i mallarna för  Bidrag, andra kan behöva läggas till. För instruktioner om att lägga till eller ta bort egenskaper, länka till entitet, skapa lokal entitet och om hur formuläret fungerar i övrigt, se Redigering i vänstermenyn. 

För information om katalogiseringsregler och Librispraxis, [se Metadatabyrån](https://metadatabyran.kb.se/) samt [se RDA Toolkit](https://original.rdatoolkit.org/). 

Se även [instruktionsfilmer på KB:s Youtubekanal](https://www.youtube.com/playlist?list=PLZVkEICvA5-GRT2oJQmLgq_2Pksx6zYPy).

## Adminmetadata
[Adminmetadata - Metadatabyrån](https://metadatabyran.kb.se/beskrivning/specialanvisningar/adminmetadata-i-libris).
* Kontrollera beskrivningsnivån. I mallen är standardvärdet Biblioteksnivå (normalvärde för Librisbiblioteken).  
**Observera: Om nivån är CIP-post eller preliminär post, ändra till annan nivå, annars kan ändringar skrivas över!**

## Instans
För att lägga till egenskaper under Instans, klicka på plustecknet i redigeringsvyn (den stora runda plusikonen under Verktygsikonen) - Lägg till egenskaper under: Tryck (för bidrag i tryckt publikation) eller Elektronisk (för bidrag i elektronisk publikation). Sök fram egenskapen och välj den genom att klicka på plustecknet vid egenskapens namn. 

### Utgivningssätt
* Utgivningssätt (issuanceType = 000/07)  
  Välj från lista:  
  ```Del av sammansatt resurs```</br>
Normalvärde för monografiska bidrag som t.ex. artiklar i en tidskrift/årsbok eller kapitel i en monografi. 

### Medietyp
* Medietyp (mediaType/Mediatype = 337 #b)  
  Länka till entitet.
  </br>```Exempel:```
  * ```omedierad, unmediated (kod = n)``` (bidrag i tryckt publikation)
  * ```dator, computer (kod = c)``` (bidrag i elektronisk publikation)<br/>

### Bärartyp
* Bärartyp (carrierType/CarrierType = 338 #b)  
  Länka till entitet:
  </br>```Exempel:```
   * ```volym, volume (kod = nc)``` (bidrag i tryckt publikation)
   * ```onlineresurs, online resource (kod = cr)``` (bidrag i elektronisk publikation) 

### Titel     
* Har titel/Titel/Huvudtitel (hasTitle/Title/mainTitle = 245 #a)</br>
  ```Exempel: Herrgårdsbyggnader i Mälardalen under 1700- och 1800-talet```
* Har titel/Titel/Övrig titelinformation (hasTitle/Title/subtitle = 245 #b)  
   ```Exempel: när, var och av vem?```

#### Varianttitel
* Har titel/Varianttitel/Huvudtitel (hasTitle/VariantTitle/mainTitle = 246 #a)

#### Delbeteckning och deltitel
* Har titel/Titel/Har del/Titeldel/Delbeteckning (hasTitle/Title/hasPart/TitlePart/partNumber = 245 #n)
* Har titel/Titel/Har del/Titeldel/Deltitel (hasTitle/Title/hasPart/TitlePart/partName = 245 #p)

#### Parallelltitel
Ange parallelltitel här. Upprepa inte parallelltitel efter Har titel/Titel/Huvudtitel (245 #a) med interpunktion.
* Har titel/Parallelltitel/Huvudtitel (hasTitle/ParallelTitle/mainTitle = 246 1/1 #a)
* Har titel/Parallelltitel/Övrig titelinformation (hasTitle/ParallelTitle/subTitle = 246 1/1 #b)

### Upphovsuppgift
* Upphovsuppgift (responsibilityStatement = 245 #c)<br/>
  ```Exempel: Johan Ahlner, Karin Kjellgren```

### Utgivning  
* Utgivning<br/>
  Välj typ från lista. För bidrag, använd Primär utgivning. 

#### Utgivningsland  
* Land (country = 008/15-17)  
  Länka till entitet.  
  ```Exempel: Sverige (sw)```

#### År
* Primär utgivning/Utgivning/År (date = 008/07-10, 264 -/1 #c)<br/>
År får endast innehålla siffror (0-9) och bokstaven u.

### Anmärkning
* Anmärkning/Anmärkning/Benämning (hasNote/Note/label = 500 #a)<br/>

### Tillhörande media 
* Tillhörande media/Mediaobjekt/URI (associatedMedia/Mediaobject/uri = 856 4/0 #u)  
Om instansbeskrivningen gäller en **fritt tillgänglig elektronisk artikel**, använd Tillhörande media för att lägga in en elektronisk adress till artikeln. Lägg till Mediaobjekt under Tillhörande media. Välj Skapa lokal entitet. Lägg till egenskapen URI. Klistra in aktuell URI.
* Tillhörande media/Mediaobjekt/Offentlig anmärkning  
(associatedMedia/Mediaobject/marc:publicNote = 856 4/0 #z)   
  Lägg till Offentlig anmärkning. 
   <br/>```Exempel:```
  * ```Fritt tillgänglig via tidskriftens webbplats``` 
  * ```Fritt tillgänglig``` 

Välj det mest beständiga länkmålet för fritt tillgängliga artiklar, i första hand en URI (t.ex. URN eller DOI), i andra hand en översiktssida från vilken artikeln är enkelt åtkomlig och i sista hand, länka direkt till den fritt tillgängliga resursen.

**För avtalsbundna eller endast lokalt tillgängliga elektroniska artiklar** ange URI i beståndsposten. Instansbeskrivningen kan kompletteras med URI i Tillhörande media till en generell inloggningssida för en resurs där artikeln ingår. Förtydliga med lämplig anmärkningsfras i Offentlig anmärkning, t.ex. "Inloggning krävs".  

### Är del av
Här anges värdpublikationen, d.v.s. den publikation som bidraget ingår i. Mallarna är förberedda för att beskriva värdpublikationen som lokal entitet men i första hand bör man länka till värdpublikationen. Värdpublikationen bör endast beskrivas som lokal entitet i de fall den inte har en post i Libris. 

I Libris rekommenderas att man för bidrag alltid länkar till eller beskriver årsbokens/tidskriftens huvudpost, även när en årsboksårgång eller ett tidskriftshäfte har en monografisk/tematisk karaktär (med egen, distinkt titel, fullständig titelsida o.s.v., eller en tematitel). 

#### Länka till värdpublikationen
* Är del av (isPartOf = 773)<br/>
För att länka till värdpublikationen, klicka på Länka entitet och sök fram värdpublikationen. Klicka sedan på Ersätt lokal entitet. <br/> 

#### Beskriva värdpublikationen som lokal entitet
Om värdpublikationen inte finns i Libris får man beskriva den som lokal entitet. 
Lägg till Instans som lokal entitet. Lägg sedan till egenskaper för värdpublikationen under Instans. 

##### Värdpublikation med primär medverkan
* Instans av Verk/Verk/Medverkan och funktion/Primär medverkan/Agent/Agent<br/>
Lägg till egenskapen Instans av verk och skapa Verk som lokal entitet. Under Verk, lägg till egenskapen Medverkan och funktion och välj typ Primär medverkan. Under Agent, lägg till Agent som lokal entitet.<br/> 
Skriv in uppgiften under Benämning. Använd korrekt namnform, [se Agenter som lokala entiteter - Metadatabyrån](https://metadatabyran.kb.se/auktoritetsarbete-och-agenter/agenter-i-libris#Agentersomlokalaentiteter).
    </br>```Exempel:```
    * ```Carlsson, Magnus```
    * ```Sverige. Socialtjänstkommittén```
    * ```International Congress on Military History (26 : Stockholm : 2000)```
* Instans av Verk/Verk/Medverkan och funktion/Primär medverkan/Funktion<br/>
Länka till entitet:<br/>
```Exempel: Författare, aut```

##### Övriga egenskaper för värdpublikationen
* Identifikator (identifiedBy = 773 #z ISBN, 773 #x ISSN)<br/>
Lägg till egenskapen Identifikator. Välj typ och ange värdpublikationens identifikator (om sådan finns) i Värde.
    </br>```Exempel:```
    * ```9789186949372```
    * ```0008-011X```

* Har titel/Titel/Huvudtitel (hasTitle/Title/mainTitle = 773 #t)<br/>
Lägg till egenskapen Har titel. Välj typ Titel.<br/> 
Om värdpublikationen är en monografi, ange huvudtitel och eventuellt övrig titelinformation åtskild med interpunktion i Huvudtitel. Om Övrig titelinformation ska anges eller inte är en bedömningsfråga. Huvudtiteln kan i vissa fall vara ganska intetsägande medan övrig titelinformation ger tydligare information om innehållet. Dessutom minskar risken för sammanblandning av verk med samma huvudtitel.</br>
```Exempel: Historia - ekonomi - forskning : fem rapporter om idrott : rapporter till Idrottsutredningen```<br/>
Om värdpublikationen är en årsbok eller tidskrift, ange nyckeltiteln (om värdpublikationen har ISSN), annars huvudtiteln.
    </br>```Exempel:```
    * ```Karolinska förbundets årsbok```
    * ```Barnboken (Online)```
* Uppgift om produktion, utgivning, distribution och eller tillverkning (provisionActivityStatement = 773 #d)<br/>
Om värdpublikationen är en monografi, lägg till egenskapen Uppgift om produktion, utgivning, distribution och/eller tillverkning.<br/>
Ange utgivningstiden för monografin.<br/>
```Exempel: 2002```

### Placering i värdpublikation
Utformningen av uppgifterna i denna egenskap bygger främst på boken Bibliografiska referenser, utarbetad av SIS - allmänna standardiseringsgruppen [av Sten Hedberg med stöd av en arbetsgrupp utsedd av SAB:s kommitté för katalogisering och klassifikation]. - Stockholm : Standardiseringskommissionen i Sverige (SIS), 1991.
* Del (part = 773 #g)<br/>
Här anges i vilken årgång och/eller nummer av värdpublikationen bidraget är publicerat och/eller paginering.

#### Bidrag i årsbok, tidskrift eller dagstidning
* Del (part = 773 #g)<br/>
Ange årgång och/eller nummer samt paginering.
    </br>```Exempel:```
    * ```2018, sidorna 215-217```
    * ```2019(87):2, sidorna 145-172```
    * ```2020-02-23```

När en årgång består av flera nummer anges också numret enligt exemplet: "2002(87):2" även om årgången har genomgående paginering.

#### Bidrag i monografi
* Del (part = 773 #g)<br/>
Ange paginering.<br/>
```Exempel: Sidorna 379-390```

## Verk 
För att lägga till egenskaper under Instans av Verk, klicka på plustecknet till höger om Instans av Verk och verkstypen. Sök fram egenskapen och välj den genom att klicka på plustecknet vid egenskapens namn.

[Läs mer om Verk och egenskaperna för Verk under den generella beskrivningen av Verk](https://libris.kb.se/katalogisering/help/workflow-work).

### Verkets titel 
Ange vid behov den föredragna titeln för verket. För instruktioner, se [Metadatabyrån - Föredragen titel för verket](https://metadatabyran.kb.se/beskrivning/generella-anvisningar---rda/verk-och-uttryck/foredragen-titel-for-verket). 

#### Verk med primär medverkan
* Har titel/Titel/Huvudtitel (hasTitle/Title/mainTitle = 240 1/0 #a)</BR> 
Föredragen titel för ett verk med Primär medverkan anges här.

#### Verk utan primär medverkan
*	Uttryck av/Verk/Har titel/Titel/Huvudtitel (expressionOf/Work/hasTitle/Title/mainTitle (= 130 #a)  
Föredragen titel för ett verk utan Primär medverkan anges här.

### Medverkan och funktion
Under Medverkan och funktion, ange relationer till de agenter som medverkar i verket. Följ instruktioner i [Relationer till agenter - Metadatabyrån](https://metadatabyran.kb.se/beskrivning/generella-anvisningar---rda/relationer/relationer-till-agenter). 
* Medverkan och funktion/Primär medverkan/Agent/Person (100 1/- #a)</br>
* Medverkan och funktion/Primär medverkan/Funktion (100 #4)</br>
* Medverkan och funktion/Medverkan/Agent/Person (700 1/- #a)</br>
* Medverkan och funktion/Medverkan/Agent/Funktion (700 #4)

### Språk 
* Språk (language = 008/35-37)</BR>
  Länka till entitet.  
  ```Exempel: svenska (swe)```</BR> 

#### Översättning  
För en artikel som är/innehåller en översättning, lägg till:  
* Anmärkning: Språk (marc:LanguageNote = 041 i1: 1)  
  Ange om resursen är/innehåller en översättning.
  **Från och med version 1.18 skapas uppgiften automatiskt.**

**Från och med version 1.18 anges originalspråk för översättningar under Översättning av, inte som tidigare under Originalversion. OBS! För närvarande ska titel och medverkan inte läggas till under Översättning av. Fortsätt att ange dem som tidigare direkt under Instans av verk.**

* Översättning av/Verk/Språk (translationOf/Work/language = 041 #h)  
  Ange originalspråk för översatt verk här. Lägg till Översättning av under Instans av verk, skapa Verk som lokal entitet. Du behöver inte välja verkstyp här. Lägg till Språk och länka till entitet.</BR>
  ```Exempel: engelska (eng)```  

För översättningar i flera led, använd egenskapen Intermediärt språk till översättningar.

### Genre form 
För anvisningar om hur man anger genre/form, [se hjälptexten Verk](https://libris.kb.se/katalogisering/help/workflow-work#genre): Genre form.
 
### Klassifikation  
För anvisningar om hur man anger klassifikation, [se Klassifikation i Metadatabyrån](https://metadatabyran.kb.se/klassifikation).

### Ämne  
* Ämne  
Länka  i första hand till entiteter för ämnesord. Följ [instruktionerna för Svenska ämnesord i Metadatabyrån](https://metadatabyran.kb.se/amnesord-och-genre-form/svenska-amnesord).  

### Innehållstyp
 * Innehållstyp/Innehållstyp (contentType/ContentType = 336 #b)   
  Länka till entiteten:</BR>
  ```text, text (kod = txt)```

### Sammanfattning av innehåll
 * Sammanfattning av innehåll/Sammanfattning/Benämning (summary/Summary/label = 520 #a)</BR>
Lägg till Sammanfattning av innehåll. Välj Sammanfattning av innehåll. Lägg till Sammanfattning. 
<br/>Skriv in uppgiften under Benämning.
 <br/>```Exempel: Om en planerad fredskonferens som aldrig kom till stånd```<br/> 
 * Typ av sammanfattning/typ av innehållsbeskrivning (marc:summaryType = 520 ind1)  
 Sök fram och lägg till Typ av sammanfattning. Välj typ från lista.<br/>
 ```Exempel: Ej preciserad```
