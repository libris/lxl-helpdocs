---
section: Generell beskrivning
title: Instans
order: 27
date: 2023-11-30
tags:
- instans
--- 

# Instans

| Innehåll  | | |
| ------ | ------ | ------ |
| [Inledning](#inledning) | | [Copyrightår](#copyrightår) | 
| [Instanstyp](#instanstyp) | | [Identifikator](#identifikator) | 
| [Utgivningssätt](#utgivningssätt)| | [Omfång](#omfång) | 
| [Medietyp](#medietyp) | | [Mått](#mått) |
| [Bärartyp](#bärartyp) | | [Övriga fysiska detaljer](#övriga-fysiska-detaljer) |
| [Titel](#titel)| | [Klassifikation](#klassifikation) | 
| [Upphovsuppgift](#upphovsuppgift) | | [Medföljande material](#medföljande-material)  |
| [Medverkan och funktion](#medverkan-och-funktion) | | [Seriemedlemskap](#seriemedlemskap) |
| [Upplageuppgift](#upplageuppgift) | | [Anmärkning](#anmärkning) |
| [Produktion](#produktion) | | [Innehållsförteckning](#innehållsförteckning) |
| [Huvudsakligt tillgängliggörande](#huvudsakligt-tillgängliggörande) | | [Annat bärarformat](#annat-bärarformat) |
| [Utgivning](#utgivning) | | [Elektronisk adress](#elektronisk-adress) |
| [Tillverkning](#tillverkning) | | [Sammanfattning av innehåll](#sammanfattning-av-innehåll) |


## Inledning
**VERSION 1.27**: Sammanfattning av innehåll (summary) ska endast ligga under Instans och inte under Verk.   
[Till Sammanfattning av innehåll i Metadatabyrån](https://metadatabyran.kb.se/beskrivning/generella-anvisningar---rda/verk-och-uttryck/sammanfattning-av-innehall).


En instans är en instans av ett verk, till exempel en viss utgåva av ett verk. Instans kallas också manifestation. Beskrivningen av instansen innehåller information som utgivning, bärartyp och omfång. Vissa egenskaper, till exempel ämne, klassifikation, språk och innehållstyp, knyts i stället till verket. Läs mer om [Verk](https://libris.kb.se/katalogisering/help/workflow-work).   

**Denna hjälptext beskriver de vanligaste egenskaperna under Instans.** 

  * För utförligare instruktioner om att lägga till eller ta bort egenskap, länka till entitet, skapa lokal entitet och om hur formuläret fungerar i övrigt, se Redigering i vänstermenyn
  * För information om katalogregler, skrivregler och övriga katalogiseringsanvisningar, [se Manifestation (Instans) - Metadatabyrån](https://metadatabyran.kb.se/beskrivning/generella-anvisningar---rda/manifestation-instans)
  * [Se även instruktionsfilmer](https://www.youtube.com/playlist?list=PLZVkEICvA5-GRT2oJQmLgq_2Pksx6zYPy)   

I de flesta fall ska informationen delas upp i olika egenskaper (jfr fält) och underliggande egenskaper (jfr delfält). I några undantagsfall är det nödvändigt att använda ISBD-interpunktion inom en egenskap, för att separera uppgifter. Dessa fall visas genom exempel nedan. I övriga fall, lägg inte in ISBD-interpunktion för att avsluta en egenskap. Använd vid behov klamrar inom en egenskap, enligt anvisningar i [Manifestation (Instans) - Metadatabyrån](https://metadatabyran.kb.se/beskrivning/generella-anvisningar---rda/manifestation-instans).  
För att lägga till egenskaper under Instans, klicka på plustecknet i redigeringsvyn (den stora runda plusikonen under Verktygsikonen) - Lägg till egenskaper under: Instans.  
![Lägg till egenskap under: Instans](plusegenskapinstans.png)  

Sök fram egenskapen och välj den genom att klicka på plustecknet vid egenskapens namn eller på egenskapens namn.    
![Sök fram och välj egenskap att lägga till](plusegenskapinstans2.png)  

### Instanstyp  
En instans är av en viss typ. Exempel på instanstyper är: Instans, Elektronisk, Arkiv, Handskrift, Ljudinspelning. För tryckta instanser är instanstyp inte angiven i förhandsposter och andra postinflöden, inte heller i äldre poster. Dessa poster har bara "Instans" som instanstyp men ingen specifik instanstyp. I mallarna för Bok (tryckt monografi), Noterad musik, Tryckt seriell resurs och Äldre tryck är dock instanstypen Tryck från och med version 1.15. Det är tillåtet men inte nödvändigt att byta instanstyp från Instans till specifik instanstyp.  En maskinell ändring till specifik instanstyp kommer att göras senare. För instruktioner om att byta instanstyp, [se Att använda verktyget](https://libris.kb.se/katalogisering/help/use-the-editor).  
När man skapar Instans eller Verk som lokal entitet under en egenskap behöver man inte välja Instans- eller Verkstyp.  

### Utgivningssätt    
* Utgivningssätt (issuanceType = 000/07)   
  Välj från lista.
 <br/>```Exempel:```
  * ```Monografisk resurs```
  * ```Seriell resurs```  

### Medietyp  
* Medietyp (mediaType/Mediatype = 337 #b)  
  Länka till entitet.
 <br/>```Exempel:```
  * ```c (= dator)```
  * ```n (= omedierad)```
  * ```s (= audio)```
  * ```v (= video)```   

[Om medietyper i Metadatabyrån](https://metadatabyran.kb.se/beskrivning/generella-anvisningar---rda/manifestation-instans/medietyp).

### Bärartyp  
* Bärartyp (carrierType/CarrierType = 338 #b)  
  Länka till entitet.  
  <br/>```Exempel:```
  * ```cr (= onlineresurs)```
  * ```nb (= ark)```
  * ```nc (= volym)```
  * ```sd (= ljudskiva) + d (= ljudskiva)```   

[Om bärartyper i Metadatabyrån](https://metadatabyran.kb.se/beskrivning/generella-anvisningar---rda/manifestation-instans/barartyp).  

### Titel   

#### Huvudtitel    
* Har titel/Titel/Huvudtitel (hasTitle/Title/mainTitle = 245 #a)  
  Skriv in uppgiften.    
 ```Exempel: En arbetsdag i skriftsamhället```  
För en titel som börjar med bestämd eller obestämd artikel, ska artikeln fileras bort. Ange fileringsvärde genom att lägga till fileringsvärde (plustecknet vid Titel - Lägg till egenskaper under: Titel) och ange en siffra.  
 ```Exempel: Huvudtitel: En arbetsdag i skriftsamhället, fileringsvärde: 3```  
 Se exempel på sidan [Filering av titel - Metadatabyrån](https://metadatabyran.kb.se/beskrivning/generella-anvisningar---rda/manifestation-instans/titel/filering-av-titel)

#### Övrig titelinformation (undertitel)
* Har titel/Titel/Övrig titelinformation (= Undertitel) (hasTitle/Title/subtitle = 245 #b)  
  Skriv in uppgiften. Om det finns flera undertitlar, skriv in dessa efter varandra i samma fält, åtskilda av mellanslag, kolon, mellanslag.    
```Exempel: ett etnografiskt perspektiv på skriftanvändning i vanliga yrken : småskrift utarbetad av Språkrådet```

För att ange originaltitel, se Verk/Har titel/Titel/Huvudtitel.  

#### Varianttitel   
För att lägga till varianttitel, klicka på plustecknet vid Har titel (lägg till titel) och välj typ Varianttitel. 
* Har titel/Varianttitel/Huvudtitel (hasTitle/VariantTitle/mainTitle = 246 #a)   
Används till exempel för felaktigheter och för att öka sökbarheten för titlar som innehåller exempelvis specialtecken, siffror eller oväntade stavningar av ord.    
  Skriv in uppgiften under Huvudtitel.    
  ```Exempel: Hierarchy in organizations```   
 I äldre poster kan titlar som innehåller exempelvis specialtecken, siffror eller oväntade stavningar av ord ligga i [Relation/Relation/Entitet/Verk/Har titel/Titel/Huvudtitel](#titel-alternativ-stavning) (= 740). Använd i stället Varianttitel.  

  För en titel som börjar med bestämd eller obestämd artikel, ska artikeln fileras bort. Lägg till fileringsvärde under Varianttitel och ange en siffra. Fileringsvärdet exporteras dock inte till marc eftersom indikator för fileringsvärde inte används i 246.  
 ```Exempel: Huvudtitel: En arbetsdag i skriftsamhället, fileringsvärde: 3```  
  [Se exempel på sidan Filering av titel - Metadatabyrån](https://metadatabyran.kb.se/beskrivning/generella-anvisningar---rda/manifestation-instans/titel/filering-av-titel)
* Har titel/Varianttitel/Övrig titelinformation (= Undertitel) (hasTitle/VariantTitle/subtitle = 246 #b)  
  Skriv in uppgiften under Övrig titelinformation. Om det finns flera undertitlar, skriv in dessa efter varandra inom samma egenskap, åtskilda av mellanslag, kolon, mellanslag.   
* Har titel/Varianttitel/Typanmärkning (hasTitle/VariantTitle/typeNote = 246 1/_ #i)  
 Anmärkningstext som i ett sökgränssnitt ska föregå varianttiteln. Används också för att ange typ av varianttitel som inte finns i listan, t ex Titelrubrik. Lägg vid behov till Typanmärkning (plustecknet vid Varianttitel - lägg till egenskaper under: Varianttitel, välj Typanmärkning).  
  Skriv in uppgiften.  
  ```Exempel: Titeln felstavad, korrekt titel:```       

#### Omslagstitel, Ryggtitel, Rubriktitel  
* Omslagstitel, Ryggtitel, Rubriktitel etc - lägg till Har titel och välj typ, till exempel Omslagstitel. Ange Huvudtitel, eventuell Övrig titelinformation och Typanmärkning, enligt mönstret för Omslagstitel, se nedan.      

#### Omslagstitel   
* Har titel/Omslagstitel/Huvudtitel (hasTitle/CoverTitle/mainTitle = 246 1/4 #a)  
 Skriv in uppgiften.        
* Har titel/Omslagstitel/Övrig titelinformation (= Undertitel) (hasTitle/CoverTitle/subtitle = 246 1/4 #b)   
  Skriv in uppgiften.    
  Om det finns flera undertitlar, skriv in dessa efter varandra i samma fält, åtskilda av mellanslag, kolon, mellanslag.  
  Exempel:  
 ![Omslagstitel](omslagstitel.png)   
  För att ange att omslagstiteln endast står på skyddsomslag, använd Varianttitel och lägg till Typanmärkning (plustecknet vid Varianttitel - lägg till egenskaper under: Varianttitel, välj Typanmärkning).  
  Skriv in uppgiften.
  <br/>```Exempel:```
  * ```Typanmärkning (246 #i): Skyddsomslag:```
  * ```Varianttitel/Huvudtitel (246 #a): På väg mot döden```
  * ```Övrig titelinformation (246 #b): en Cooper och Fry-deckare```  

#### Delbeteckning
* Har titel/Titel/Har del/Titeldel/Delbeteckning (hasTitle/Title/hasPart/TitlePart/partNumber = 245 #n)  
Lägg till Har del (hasPart) under Har titel/Titel. Under Har del, skapa Titeldel (TitlePart) som lokal entitet (skriv "titeldel" i rutan Skapa lokal entitet och välj * Titeldel). Titeldel läggs till under Har del. Klicka på Titeldel och det fälls ut.   
Om Har del/Titeldel/Deltitel redan finns, lägg till Delbeteckning under Titeldel (plustecknet vid Titeldel - Lägg till egenskaper under: Titeldel, välj Delbeteckning (partNumber)).   
Skriv in uppgiften under Delbeteckning.  
```Exempel: 1```   

#### Deltitel  
* Har titel/Titel/Har del/Titeldel/Deltitel (hasTitle/Title/hasPart/TitlePart/partName = 245 #p)  
Lägg till Har del (hasPart) under Har titel/Titel. Under Har del, skapa Titeldel (TitlePart) som lokal entitet (skriv "titeldel" i rutan Skapa lokal entitet och välj * Titeldel). Titeldel läggs till under Har del. Klicka på Titeldel och det fälls ut.  
Om Har del/Titeldel/Delbeteckning redan finns, lägg till Deltitel under Titeldel (plustecknet vid Titeldel - Lägg till egenskaper under: Titeldel, välj Deltitel (partName)).   
Skriv in uppgiften under Deltitel.  
Exempel:  
![Titeldel](titeldel.png)  

För att ange Delbeteckning och Deltitel i en annan ordning, till exempel en deltitel som har efterföljande delbeteckningar, upprepa Titeldel och ange Delbeteckning och Deltitel som det passar i det aktuella fallet.   

#### Parallelltitel  
Ange parallelltitel endast här. Upprepa inte parallelltiteln efter Har titel/Titel/Huvudtitel.   
* Har titel/Parallelltitel/Huvudtitel (hasTitle/ParallelTitle/mainTitle = 246 1/1 #a)   
Välj först Har titel, välj sedan typ Parallelltitel.    
Skriv in uppgiften under Huvudtitel.    
  ```Exempel: The Great Northern War explained```  
För en titel som börjar med bestämd eller obestämd artikel, ska artikeln fileras bort. Lägg till fileringsvärde och ange en siffra.

* Har titel/Parallelltitel/Övrig titelinformation (hasTitle/ParallelTitle/subTitle = 246 1/1 #b)   
Vid behov, lägg till Övrig titelinformation (subtitle) under Parallelltitel.  
  ```Exempel: Charles XII and the ideological address```  

### Titel alternativ stavning
* Relation/Relation/Entitet/Verk/Har titel/Titel/Huvudtitel   
(relationship/Relationship/entity/Work/hasTitle/Title/mainTitle = 740)  
Här angavs tidigare alternativ stavning av titlar, för att öka sökbarheten för titlar som innehåller exempelvis specialtecken, siffror eller oväntade stavningar av ord. **Använd i stället [Varianttitel](#varianttitel).** Bibliotek som önskar dubblera varianttitlar här kan göra det men det är inte nödvändigt.  

  För att lägga till en alternativ sökingång för titeln, klicka på plustecknet Lägg till egenskaper under: Instans och välj Relation. Lägg till Entitet (plustecknet vid Relation - lägg till egenskaper under: Relation). Skapa verk som lokal entitet (plustecknet vid Entitet - lägg till verk). Klicka i rutan Skapa lokal entitet, längst ner i sidorutan till höger, och välj Verk. Lägg till Har titel (plustecknet vid Verk - lägg till egenskaper under: Verk). 
Skriv in uppgiften under Huvudtitel.  

  För en titel som börjar med bestämd eller obestämd artikel, ska artikeln fileras bort. Ange fileringsvärde genom att lägga till fileringsvärde (plustecknet vid Titel - Lägg till egenskaper under: Titel) och ange en siffra.  
 ```Exempel: Huvudtitel: En arbetsdag i skriftsamhället, fileringsvärde: 3```  
[Se exempel på sidan Filering av titel - Metadatabyrån](https://metadatabyran.kb.se/beskrivning/generella-anvisningar---rda/manifestation-instans/titel/filering-av-titel)

### Upphovsuppgift
* Upphovsuppgift (responsibilityStatement = 245 #c)    
  Skriv in uppgiften.  
  ```Exempel: Tom Marcus ; översättning: Svante Skoglund```

### Medverkan och funktion
Från och med Libris version 1.33 kan du lägga till Medverkan och funktion även under Instans. Ange relationer till de agenter som medverkar till instansen. Ett exempel är utgivare och förordsförfattare.

* Medverkan och funktion/Medverkan/Agent/Organisation  
(contribution/Contribution/agent/Organization = 710 2/- #a)  
Länka till entitet.

* Medverkan och funktion/Medverkan/Funktion  
(contribution/Contribution/Contribution/role = 710 #4)  
Länka till entitet.

* Medverkan och funktion/Medverkan/Agent/Person
(contribution/Contribution/agent/Person = 700 1/- #a)  
Länka till entitet.

* Medverkan och funktion/Medverkan/Funktion  
(contribution/Contribution/contribution/role = 700 #4)  
Länka till entitet.
  
På id.kb.se listas funktioner:  
  * [Funktioner möjliga att använda endast på instans](https://id.kb.se/find?q=%2a&%40type=Role&and-domain.%40id=https%3A%2F%2Fid.kb.se%2Fvocab%2FInstance&_sort=_sortKeyByLang.sv) 
  * [Funktioner möjliga att använda på verk och instans](https://id.kb.se/find?q=%2a&%40type=Role&and-domain.%40id=https%3A%2F%2Fid.kb.se%2Fvocab%2FCreation&_sort=_sortKeyByLang.sv)  
  * [Funktioner möjliga att använda på instans och bestånd](https://id.kb.se/find?q=%2a&%40type=Role&and-domain.%40id=https%3A%2F%2Fid.kb.se%2Fvocab%2FEmbodiment&_sort=_sortKeyByLang.sv)
  * [Funktioner möjliga att använda på verk, instans och bestånd](https://id.kb.se/find?q=%2a&%40type=Role&and-domain.%40id=https%3A%2F%2Fid.kb.se%2Fvocab%2FEndeavour&_sort=_sortKeyByLang.sv)  

Medverkan och funktion som hör till verket ska även i fortsättningen ligga under Instans av / Verk.

För anvisningar och exempel, se [Relationer till agenter i Metadatabyrån](https://metadatabyran.kb.se/beskrivning/generella-anvisningar---rda/relationer/relationer-till-agenter)  

### Upplageuppgift
* Upplageuppgift (editionStatement = 250 #a)  
  Skriv in upplagebeteckning här.  
  ```Exempel: Första upplagan```  

### Produktion  
Uppgifter om Produktion anges endast för **opublicerade** resurser. För publicerat material, [se Utgivning.](#utgivning)  

* Produktion (production)  
  Används för opublicerade resurser. Välj Produktion i listan. Komplettera med egenskapen Huvudsakligt tillgängliggörande. Undantaget är samlingsposter. I dessa anges täckningstiden som Primär produktion med egenskaperna Startår och Slutår.  

#### Produktionsort 
*	Plats/Plats/Benämning (place/label = 264 -/0 #a)  
Ej obligatoriskt. Ange uppgiften som lokal entitet.

#### Producent
*	Agent/Agent/Benämning (agent/label = 264 -/0 #b)  
Ej obligatoriskt. Ange uppgiften som lokal entitet.

#### Produktionsår
*	Datum (date = 264 -/0 #c)  
Datum får innehålla text och interpunktionstecken.
<br/>```Exempel:```
  * ```[Ej efter 1900]```
  * ```[mellan 1780 och 1815?]```
  * ```1846```

### Huvudsakligt tillgängliggörande
*	Huvudsakligt tillgängliggörande (marc:primaryProvisionActivity)  
  Ta med Huvudsakligt tillgängliggörande när egenskapen Produktion används och det inte gäller en samlingspost. Egenskapen används även tillsammans med Utgivning i de fall årtal/datum är osäkert men tidigaste och senaste år kan anges.
  <br><br>Välj typ från lista. Använd alltid Primär produktion för opublicerat material, och Primär utgivning för utgivet material som har osäkert utgivningsår men där tidigaste och senaste år kan anges. I stillbildsmallen är Primär utgivning förvalt. Ändra till Primär produktion när opublicerat material beskrivs. 

#### Land
*	Land (country = 008/15-17)  
  Länka till entitet.  
  ```Exempel: Sverige (sw)``` 

#### År
*	År (year = 008/07-10).  
  År får endast innehålla siffror (0-9) och bokstaven u. Ange år, utan klamrar eller andra tecken, endast fyra positioner. Här anges produktionsår när detta enbart består av ett årtal. Här anges tidigaste år i de fall produktionsår/utgivningsår är osäkert men tidigaste och senaste utgivningsår/produktionsår är känt.  

#### Kompletterande datum
*	Kompletterande datum (other year = 008/07-10).  
Använd Kompletterande datum för material  med osäkert utgivningsår/produktionsår där tidigaste och senaste år kan anges. Får endast innehålla siffror (0-9). Ange senaste år, utan klamrar eller andra tecken, endast fyra positioner.

#### Typ av utgivningsdatum
*	Typ av utgivningsdatum. (marc/publicationStatus = 008/06)  
Använd egenskapen för material  med osäkert utgivningsår där tidigaste och senaste år kan anges.  
Välj typ Osäkert år från listan.   


#### Exempel på registrering av produktionsår för opublicerat material:
![Exempel på registrering av produktionsår för opublicerat material](produktion1.png)  


#### Exempel på osäkert utgivningsår där tidigaste och senaste år kan anges:
![Exempel på osäkert utgivningsår där tidigaste och senaste år kan anges](osakert_ar.png)  

### Utgivning  
* Utgivning (publication)  
  Välj typ från lista. För monografier, använd Primär utgivning.  
  I konverterade och maskininlästa poster finns det ibland två avsnitt: ett Primär utgivning med År och Land, och ett Utgivning med Plats, Agent och Datum. När man redigerar maskininlästa poster med två utgivningsavsnitt får man, om man bedömer det nödvändigt, flytta uppgifterna om Plats, Agent och Datum till avsnittet Primär utgivning och ta bort avsnittet Utgivning.   
NB inväntar en maskinell ändring av dessa poster och ändrar inte manuellt.    

#### Utgivningsplats
* Plats/Plats/Benämning (= Utgivningsort) (place/label = 264 -/1 #a)  
  Sök inte efter Plats som entitet. Skapa Plats som lokal entitet.  
  Skriv in uppgiften under Benämning.  
  ```Exempel: [Göteborg]```  

#### Utgivningsland  
* Land (country = 008/15-17)  
  Länka till entitet.  
  ```Exempel: Sverige (sw)``` 

#### Utgivarnamn
* Agent/Agent/Benämning (= Utgivarnamn) (agent/label = 264 -/1 #b)  
  Sök inte efter Agent som entitet. Skapa Agent som lokal entitet.  
  Skriv in uppgiften under Benämning.  
  ```Exempel: NoNa```   
  Om flera utgivare ska anges, lägg till Har del (hasPart) under Primär utgivning. Skapa Utgivning som lokal entitet. I rutan Skapa lokal entitet, skriv Utgivning och välj *** Utgivning. Upprepa Utgivning som lokal entitet genom att duplicera entiteten Utgivning.  
Ange Plats/Plats/Benämning och Agent/Agent/Benämning och vid behov Datum inom respektive utgivningsavsnitt (angående Datum, se anvisningar nedan). Samtliga utgivare med Plats och Agent ska ligga inom Har del/Utgivning.
Land, År och eventuellt Datum  ska ligga inom Primär utgivning.   
  [Se exempelpost i Libris katalogisering](https://libris.kb.se/katalogisering/w4rp4hlwtr5lctjr#it).

#### År och datum 
  * År (= Utgivningstid) (date = 008/07-10, 264 -/1 #c)  
  År får endast innehålla siffror (0-9) och bokstaven u. År ska endast förekomma inom Primär utgivning.  
  Ange utgivningsår, utan klamrar eller andra tecken, endast fyra positioner. Skriv in uppgiften.  
  För att ange ett år utan klamrar eller andra tecken, ange det endast här. Det kommer då att exporteras till både marcpostens 008/07-10 och 264 -/1 #c. För att ange årtal med klamrar eller andra tecken utöver fyra positioner, använd Datum.   
  Observera att År **måste** finnas med i beskrivningen, även om Datum finns med.  
  ```Exempel: 2017```  
  * Datum (= Utgivningstid) (date = 264 -/1 #c)  
  Datum får innehålla text och interpunktionstecken.  
  För att ange ett utgivningsdatum med fler än fyra positioner, till exempel ett klamrat årtal, skriv in det här. Det kommer att exporteras till marcpostens 264 -/1 #c.    
  Skriv in uppgiften.
  <br/>```Exempel:```
    * ```[2017]```
    * ```[mellan 1863 och 1866?]```

* Flera år (flerbandsverk)  
  Använd Startår och Slutår (inte År). Egenskaperna ska ligga i Primär utgivning. För ett avslutat flerbandsverk, där årtal inte behöver anges med klammer eller andra tecken utöver fyra positioner, räcker det att ange årtalen här. De exporteras då både som 008 och 264 #c. Bindestreck sätts automatiskt. För att få rätt kod i 008/06 (Typ av utgivningsdatum/Utgivningsstatus) vid MARC-export: lägg till Typ av utgivningsdatum (marc:publicationStatus) och välj ”Flera årtal (monografisk resurs)".  
 För ett pågående flerbandsverk, ange Slutår: 9999 samt Datum och bindestreck.    
 <br/>```Exempel pågående flerbandsverk:```
 * ```Startår: 2019```
 * ```Slutår: 9999```
 * ```Datum: 2019-```
 * ```Typ av utgivningsdatum: Flera årtal (monografisk resurs)``` 

 <br/>```Exempel avslutat flerbandsverk:```
 * ```Startår: 1999```
 * ```Slutår: 2017```
 * ```Typ av utgivningsdatum: Flera årtal (monografisk resurs)```

 <br/>```Exempel avslutat flerbandsverk, osäkert startår:```
 * ```Startår: 1753```
 * ```Slutår: 1756```
 * ```Datum: [1753?]-1756```
 * ```Typ av utgivningsdatum: Flera årtal (monografisk resurs)``` 

* Flera år (osäkra år)  
  [Se Huvudsakligt tillgänggliggörande/Kompletterande datum](#huvudsakligt-tillgangliggorande) .   


### Tillverkning 
* Tillverkning (manufacture)  

#### Tillverkningsplats (Tillverkningsort) 
* Plats/Plats/Benämning (place/label = 264 -/3 #a)  
  ```Exempel: Falun```  

#### Tillverkningsnamn  
* Agent/Agent/Benämning (agent/label = 264 -/3 #b)  
  Skriv in uppgiften.   
  ```Exempel: Scandbook```   

#### Tillverkningstid   
* Datum (= Tillverkningstid) (date = 264 -/3 #c)  
  Skriv in uppgiften. Klamra vid behov.
  <br/>```Exempel:```
  * ```2017```
  * ```[2017]```

### Copyrightår   
* Copyright/Copyright/Datum (copyright/Copyright/date = 264 -/4 #c)  
  Skriv in uppgiften. För att få fram copyrighttecknet, kopiera från exemplet nedan eller skriv Alt + 0169 på det numeriska tangentbordet.  
  [Se också hjälptexten Specialtecken](https://libris.kb.se/katalogisering/help/special-chars). Du kan t.ex. söka på teckenuppsättning i “Sök i windows” och öppna programmet, markera och kopiera tecknet och sedan klistra in det.  
  ```Exempel: ©2017``` 

### Identifikator 
* Identifikator (identifiedBy)  
  Välj typ från lista.  
  ```Exempel: ISBN```
* Identifikator/ISBN/Värde (identifiedBy/Isbn/value = 020 #a)  
  Skriv in uppgiften.  
  ```Exempel: 9789188107213```
* Identifikator/ISBN/Särskiljande tillägg (= Bestämning) (identifiedBy/qualifier = 020 #q)  
  Skriv in uppgiften.  
  ```Exempel: inbunden```  

För ogiltiga ISBN, använd Indirekt identifierad av, direkt under Instans. Använd inte Ogiltigt värde under Identifikator/ISBN (identifiedBy/marc:hiddenValue).  
För ISSN, se Tryckt seriell resurs. För andra identifikatorer, se respektive hjälptext.  

### Indirekt identifierad av  
Ange ogiltiga ISBN här och inte under Identifikator/ISBN/Ogiltigt värde. För ISSN, se Tryckt seriell resurs. För andra identifikatorer, se respektive hjälptext.  

* Indirekt identifierad av/ISBN  
  Välj typ från lista.  
  ```Exempel: ISBN```
* Indirekt identifierad av/ISBN/Värde (indirectlyIdentifiedBy/Isbn/value = 020 #z)  
  Skriv in uppgiften.  
  ```Exempel: 97891881072```
* Indirekt identifierad av/ISBN/Särskiljande tillägg (= Bestämning) (indirectlyIdentifiedBy/qualifier = 020 #q)  
  Skriv in uppgiften.  
  ```Exempel: inbunden``` 

### Omfång   
* Omfång/Omfång/Benämning (extent/Extent/label = 300 #a)   
  Skriv in uppgiften under Benämning. 
  <br/>```Exempel:```
  * ```319 sidor```
  * ```2 teckningar på 1 ark```
  * ```1 karta i 4 segment ```

### Mått 
* Mått/Mått/Benämning (hasDimensions/Dimensions/label = 300 #c)  
  Skriv in uppgiften under Benämning.
  <br/>```Exempel:```
  * ```24 cm```
  * ```34 x 27 cm och  37 x 27 cm, på ark 40 x 30 cm```

### Övriga fysiska detaljer   
* Övriga fysiska detaljer (physicalDetailsNote = 300 #b)     
  Skriv in uppgiften.  
  ```Exempel: illustrationer``` 

### Klassifikation  
**VERSION 1.19:**  
Några klassifikationssystem har flyttats från Verk till Instans i version 1.19. Det gäller:  
* LC-klassifikation (050)  
* NLM-klassifikation (060)  
* NAL–klassifikation (070)  

För SAB-klassifikation ska SAB-kod med medietillägg läggas in under Instans.  
För övrig klassifikation se [Verk](https://libris.kb.se/katalogisering/help/workflow-work).  

####	SAB-klassifikation med medietillägg  
*	Klassifikation/Klassifikation/Kod  
(classification/Classification/code = 084 0/4 #a)  
Skriv in uppgiften.  
```Exempel: Kc/VC```
*	Klassifikation/Ingår i system/Konceptsystem/Kod  
(classification/Classification/inScheme/ConceptScheme/code = 084 #2)  
```Exempel: kssb```
*	Klassifikation/Ingår i system/Konceptsystem/Version
(classification/Classification/inScheme/ConceptScheme/version = 084 #2)  
```Exempel: 8```

### Medföljande material
* Medföljs av/Instans/Instanstyp/Benämning (Bilagor) (accompaniedBy/Instance/type/label = 300 #e)   
Här anges medföljande material, som t ex bilagor. Lägg till Medföljs av. Skapa Instans som lokal entitet (skriv Instans i rutan Skapa lokal entitet och välj ** Instans). Man behöver inte välja Instanstyp här. Lägg till Benämning.     
Skriv in uppgiften.  
  ```Exempel: 10 mönsterark```  

### Seriemedlemskap
* Seriemedlemskap/Seriemedlemskap/Ingår i serie (seriesMembership/SeriesMembership/inSeries)  
  Avvakta med att skapa verk som länkade entiteter. Beskriv serien som lokal entitet, enligt följande instruktion.  
  *Nytt 2018-10-04:*   
  * Man måste inte längre fylla i två Seriemedlemskap för att vid export till MARC få ut både 490 och 830.  
  * Vid export till marc21 skapas både 490 och 830 (800/810) från Seriemedlemskap som saknar Serieuppgift (t ex gamla 440-fält). OBS. Hanteringen klarar de flesta fall bra, men det finns serier med deltitlar/delserier som kommer att exporteras fel (fel ordning mellan Delbeteckning och Deltitel, fel interpunktion). Om man stöter på sådana, och anser felet besvärande, får man gå in i posten och lägga till en korrekt Serieuppgift i rätt Seriemedlemskap. Då kommer 490 att skapas från det. (Finns det flera Seriemedlemskap behöver man komplettera alla, annars skapas bara 490 för den serien som har en ifylld Serieuppgift).  

#### Seriens titel (auktoriserad sökingång för serie)  
* Seriemedlemskap/Ingår i serie/Instans/Instanstyp/Instans av/Verk/Verkstyp/Har titel/Titel/Huvudtitel (seriesMembership/inSeries/Instance/type/Instanceof/Work/type/hasTitle/Title/mainTitle = 830 #a)  
  Ange den auktoriserade sökingången för serien här (gäller serier som har seriehuvudpost) i de fall den avviker från serieuppgiften. Om endast Serieuppgift men inte Ingår i serie/Instans: Instans av/Verk finns, t ex i en förhandspost från Bokinfo, fungerar det för närvarande bäst att skapa ett helt nytt seriemedlemskap och flytta över Serieuppgift dit. Ange sedan den auktoriserade sökingången för serien under Seriemedlemskap/Ingår i serie/Instans/Instanstyp/Instans av/Verk/Verkstyp/Har titel/Titel/Huvudtitel. Ta bort det första seriemedlemskapet så att endast ett seriemedlemskap återstår.  
Man behöver inte välja instans- och verkstyp här.  
  Skriv in uppgiften.   
  ```Exempel: Årstasällskapets för Fredrika Bremer-studier skriftserie```   

#### ISSN  
* Seriemedlemskap/Ingår i serie/Instans/Instanstyp/Identifikator/ISSN/Värde (seriesMembership/inSeries/Instance/type/identifiedBy/ISSN/Value) (490 #x, 830 #x)  
  Ange seriens ISSN. För äldre serier som saknar ISSN, men har ett LibrisIII-nummer ("99-nummer"), ange detta nummer här.
  Man behöver inte välja Instanstyp under Ingår i serie/Instans/Instanstyp.   
  Skriv in uppgiften.  
  ```Exempel: 1103-498X```     
 Felaktiga ISSN i en instans ska återges under [Anmärkning](#anmarkning). Se [Anmärkning om manifestationen - Metadatabyrån](https://metadatabyran.kb.se/beskrivning/generella-anvisningar---rda/manifestation-instans/anmarkning-om-manifestationen).

#### Serieuppgift  
* Seriemedlemskap/Serieuppgift (seriesMembership/seriesStatement = 490 #a)  
  Skriv in uppgiften.  
   ```Exempel: Årstasällskapets skriftserie```  

#### Numrering inom serie  
* Seriemedlemskap/Numrering inom serie (seriesMembership/seriesEnumeration = 490 #v, 830 #v)  
  Skriv in uppgiften.  
  ```Exempel: 8```  

#### Indikator för seriebiuppslag   
* Seriemedlemskap/Indikator för seriebiuppslag (marc:seriesTracingPolicy = 490 i1: 0/1)  
  Ange indikator 0 om endast serieuppgift samt eventuellt ISSN och eventuell numrering inom serie, men inte Ingår i serie/Instans/Instans av/Verk, anges.     
  Skriv in uppgiften.  
  ```Exempel: 0```   
  Ange indikator 1 om dessutom Ingår i serie/Instans/Instans av/Verk (830) anges.   
  ```Exempel: 1```   

### Anmärkning
* Anmärkning/Anmärkning/Benämning (hasNote/Note/label = 500 #a)  
  Skriv in allmänna anmärkningar här.  
  För att lägga till Anmärkning, välj Anmärkning (hasNote) och lägg till Anmärkning.  
  Skriv in uppgiften under Benämning.  

### Innehållsförteckning  
* Har innehållsförteckning/Innehållsförteckning/Benämning (tableofContents = 505 8/_)  
  För en enkel innehållsförteckning (505 #a), lägg till Har innehållsförteckning. Lägg därefter till Innehållsförteckning. Skriv in uppgiften under Benämning.     
  ```Exempel: Culture at home -- Culture and the global -- Global youth -- Global music -- Territories of global globalization.```  

* Har innehållsförteckning/Innehållsförteckning/Har del/Utökad innehållsförteckning/Benämning, Upphovsuppgift, Kommentar (tableofContents = 505 8/_ #t, #r, #g)    
För en utökad innehållsförteckning med titlar och upphovsuppgifter, lägg till Har innehållsförteckning (från Lägg till egenskaper under: Instans). Klicka på plustecknet under Har innehållsförteckning i vänstermenyn (Lägg till innehållsförteckning). Ta bort Benämning. Lägg till Har del (plustecknet vid Innehållsförteckning - Lägg till egenskaper under: Innehållsförteckning). Skriv Har del i sökrutan och välj det. Klicka på plustecknet vid Har del och välj Skapa lokal entitet. Skriv Utökad innehållsförteckning i rutan för Skapa lokal entitet och välj * Utökad innehållsförteckning. Utökad innehållsförteckning läggs till under Har del. Klicka på Utökad innehållsförteckning och det fälls ut. Lägg in titel under Benämning. Lägg in upphovsuppgift under Upphovsuppgift. Vid behov, lägg in Kommentar (med valfri information).  
Upprepa, för ytterligare titel (Benämning) + upphovsuppgift, genom att lägga till ytterligare en Utökad innehållsförteckning som lokal entitet (klicka på Duplicera entitet).  
 [Se exempelpost i Libris katalogisering](https://libris.kb.se/katalogisering/4mffks8g36rl8wm#it).

### Annat bärarformat
* Annat bärarformat (otherPhysicalFormat = 776)  
  Länka till utgåvan i annat bärarformat, till exempel från en tryckt utgåva till en elektronisk utgåva eller tvärtom.  
  [Annat bärarformat i Metadatabyrån](https://metadatabyran.kb.se/beskrivning/generella-anvisningar---rda/relationer/relaterade-resurser)

### Elektronisk adress
Använd egenskapen Elektronisk adress endast när ingen uppgift finns om vilken version länken går till (används normalt inte).  

#### Tillhörande media
**Om instansbeskrivningen gäller en elektronisk resurs**, använd Tillhörande media för att lägga in en elektronisk adress till resursen.
* Tillhörande media/Mediaobjekt/URI  
(associatedMedia/Mediaobject/uri = 856 4/0 #u)  
 Lägg till Tillhörande media. Tryck Enter (Lägg till mediaobjekt under Tillhörande media). Välj Skapa lokal entitet. Klistra in aktuell URL i egenskapen URI.
* Tillhörande media/Mediaobjekt/Offentlig anmärkning  
(associatedMedia/Mediaobject/marc:publicNote = 856 4/0 #z)   
 * Del av materialet som avses/Resurs/Benämning  
(appliesTo/Resource/label = 856 4/0 #3)  
  Vid behov, lägg till Del av material som avses under Mediaobjekt och skapa Resurs som lokal entitet. Lägg till Benämning.  

#### Annan relaterad resurs
**Om instansbeskrivningen inte gäller en elektronisk resurs**, använd Annan relaterad resurs för att lägga in en elektronisk adress till resursen i annat format. Gör i första hand en instansbeskrivning av den elektroniska resursen och använd Tillhörande media, i stället för att använda Annan relaterad resurs.  
* Annan relaterad resurs/Elektronisk/URI  
(marc:versionOfResource/Electronic/URI = 856 4/1 #u)  
Lägg till elektronisk under Annan relaterad resurs. Välj Skapa lokal entitet. Lägg till egenskapen URI. Klistra in aktuell URI.  
* Annan relaterad resurs/Elektronisk/Offentlig anmärkning  
(marc:versionOfResource/Electronic/marc:publicNote = 856 4/1 #z)  
Vid behov, lägg till Offentlig anmärkning. Skriv in anmärkningen.  
* Del av materialet som avses/Resurs/Benämning  
(appliesTo/Resource/label = 856 4/1 #3)  
Vid behov, lägg till Del av material som avses under Elektronisk och skapa Resurs som lokal entitet. Lägg till Benämning.   

#### Relaterad beskrivning eller innehåll
För att lägga in en elektronisk adress till en **relaterad resurs, till exempel delar, sammanfattningar (abstracts), innehållsförteckningar** eller andra resurser som på något sätt hör samman med den resurs som beskrivs i instansbeskrivningen, använd Relaterad beskrivning eller innehåll.
* Relaterad beskrivning eller innehåll/Dokument/URI  
(isPrimaryTopicOf/Dokument/marc:hostName = 856 4/2 #u)  
   Skapa Dokument som lokal entitet. Lägg till egenskapen URI. Klistra in aktuell URI.
* Relaterad beskrivning eller innehåll/Dokument/Offentlig anmärkning  
(isPrimaryTopicOf/Dokument/marc:publicNote = 856 4/2 #z)   
  Vid behov, lägg till Offentlig anmärkning. Skriv in anmärkningen.  
* Del av materialet som avses/Resurs/Benämning  
(appliesTo/Resource/label = 856 4/2 #3)  
  Vid behov, lägg till Del av material som avses under Relaterad beskrivning eller innehåll och skapa Dokument som lokal entitet. Lägg till Benämning.
  
### Sammanfattning av innehåll    
 * Sammanfattning av innehåll/Sammanfattning/Benämning (summary/Summary/label = 520 #a)  
 **VERSION 1.27**: Sammanfattning av innehåll (summary) ska endast ligga under Instans och inte under Verk.  
 Lägg till Sammanfattning av innehåll. Välj Sammanfattning av innehåll. Lägg till Sammanfattning.  
 Skriv in uppgiften under Benämning.  
  ```Exempel: Åtskilliga utdrag af framledne … Axel v. Fersens bref till f.d. konungen av Swerige, Gustaf Adolph, 1806```  
 [Till Sammanfattning av innehåll i Metadatabyrån](https://metadatabyran.kb.se/beskrivning/generella-anvisningar---rda/manifestation-instans/sammanfattning-av-innehall).  
 * Typ av sammanfattning/typ av innehållsbeskrivning (marc:summaryType = 520 ind1)  
 Sök fram och lägg till Typ av sammanfattning. Välj typ från lista.  
 ```Exempel: Ej preciserad``` 

#### Sammanfattningsspråk  
* Sammanfattning av innehåll/Sammanfattning/Språk (summary/Summary/language = 041 #b)  
Lägg till sammanfattningsspråk. Lägg till Sammanfattning. Ta bort Benämning. Länka till entiteten för sammanfattningens språk.  
  ```Exempel: Engelska```  
