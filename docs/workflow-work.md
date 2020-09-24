---
section: Generell beskrivning
title: Verk
order: 26
date: 2020-09-24
tags:
- verk
--- 

# Verk


| Innehåll  |  |  | 
| ----------- |  ----------- |  ----------- |
| [Inledning](#inledning)  |  | [Klassifikation](#klassifikation) | 
| [Verkstyp](#verkstyp)  |  | [Ämne](https://libris.kb.se/katalogisering/help/workflow-general-sh) | 
| [Verkets titel](#verkets-titel) |  | [Målgrupp](#malgrupp) | 
| [Relationer till ingående verk och andra verk](#relationer-till-ingaende-verk-och-andra-verk) |  | [Innehållstyp](#innehallstyp) | 
| [Medverkan och funktion](#medverkan-och-funktion) |  | [Sammanfattning av innehåll](#sammanfattning-av-innehall) | 
| [Språk](#sprak) |  |  [Anmärkning om akademisk avhandling](#anmarkning-om-akademisk-avhandling) | 
| [Genre/form](#genre-form) |  |  | 

**VERSION 1.19:** Mallen för att skapa nytt verk bör inte användas. Läs viktig information om arbetet med att bryta ut och länka till verk:</br>
[Länkning till verk i Libris](https://www.kb.se/samverkan-och-utveckling/nytt-fran-kb/nyheter-samverkan-och-utveckling/2020-09-22-lankning-till-verk-i-libris.html)! 

## Inledning
Beskrivningen av ett verk innehåller information som ämne, klassifikation, språk och innehållstyp. Ett verk kan ha en eller flera instanser, till exempel olika upplagor och utgåvor. Vissa egenskaper, till exempel utgivning, bärartyp och omfång, beskrivs i stället under instans. [Läs mer om Instans](https://libris.kb.se/katalogisering/help/workflow-instance).  

Skapa verket som lokal entitet (bryt inte ut verket till en länkbar entitet). Denna hjälptext beskriver exempel på verk som lokal entitet. Det betyder att du anger de uppgifter som listas här nedan under Instans av verk utan att klicka på länksymbolen (Länka entitet) vid Instans av verk. [Läs mer om Verk och Instans på Libris informationssidor på kb.se](https://www.kb.se/samverkan-och-utveckling/nytt-fran-kb/nyheter-samverkan-och-utveckling/2018-05-30-verk-och-instans-i-startversionen-av-nya-libris.html).  

**Denna hjälptext beskriver de vanligaste egenskaperna under Instans av verk.** 

  * För utförligare instruktioner om att lägga till och ta bort egenskaper, länka till entitet, skapa lokal entitet och om hur formuläret fungerar, se Redigering i vänstermenyn
  * För information om katalogregler, skrivregler och övriga katalogiseringsanvisningar, [se Anvisningar för katalogisering - RDA](https://www.kb.se/rdakatalogisering/ "Anvisningar för katalogisering - RDA")
  * [Se även instruktionsfilmer](https://www.youtube.com/playlist?list=PLZVkEICvA5-GRT2oJQmLgq_2Pksx6zYPy)

I de flesta fall ska informationen delas upp i olika egenskaper (jfr fält) och underliggande egenskaper (jfr delfält). I några undantagsfall är det nödvändigt att använda ISBD-interpunktion inom en egenskap, för att separera uppgifter. Dessa fall visas genom exempel nedan. I övriga fall, lägg inte in ISBD-interpunktion för att avsluta en egenskap (fält). 

## Verkstyp
Ett verk är av en viss typ. Exempel på verkstyper är: text, ljud, stillbild, rörlig bild, multimedia, karta. För instruktioner om att byta verkstyp, [se Att använda verktyget](https://libris.kb.se/katalogisering/help/use-the-editor).  

Från version 1.19 av katalogiseringsverktyget är verkstyperna försedda med illustrerande ikoner:
![Ikoner för de olika verksyperna](verkstypsikoner.png)

När man skapar Instans eller Verk som lokal entitet under en egenskap behöver man inte välja Instans- eller Verkstyp.
   
## Instans av verk
* Instans av verk (instanceOf/Work)  
  
För att lägga till egenskaper under Instans av verk, klicka på plustecknet till höger om Instans av verk och verkstypen.  
![Lägg till egenskaper under Instans av verk](instansavverk.png)  

Sök fram egenskapen och välj den genom att klicka på plustecknet vid egenskapens namn.  

![Sök fram och lägg till egenskap](instansavverkegenskap.png)  

 
### Verkets titel
Ange den föredragna titeln för verket här, vid behov. [Följ Anvisningar för katalogisering - RDA](http://www.kb.se/rdakatalogisering/Anvisningar/Allmanna-anvisningar/Sokingangar-for-verk-och-uttryck "Anvisningar för katalogisering - RDA").  
Ange föredragen titel för översättningar, för verk som har givits ut under olika titlar på samma språk eller när samma titel har använts för olika verk.   

#### Verkets titel
##### Verk med Primär medverkan
* Har titel/Titel/Huvudtitel (hasTitle/Title/mainTitle = 240 1/0 #a)  
  "Originaltitel" för ett verk med Medverkan och funktion/Primär medverkan anges här.  
  Skriv in uppgiften.  
  ```Exempel: Soldier spy```  
  För en titel som börjar med bestämd eller obestämd artikel, ska artikeln fileras bort. Lägg till fileringsvärde och ange en siffra.  

##### Verk utan Primär medverkan
*	Uttryck av/Verk/Verkstyp/Har titel/Titel/Huvudtitel (expressionOf/Work/type: Work/hasTitle/Title/mainTitle = 130 #a)  
 "Originaltitel" för ett verk utan Medverkan och funktion/Primär medverkan anges här.
Under Instans av Verk, lägg till Uttryck av. Skapa verk som lokal entitet (skriv "verk" i rutan Skapa lokal entitet och välj verk). Man behöver inte välja verkstyp här. Lägg till Har titel. Välj Titel.
Skriv in uppgiften under Huvudtitel.  
```Exempel: Bibeln``` 
*	Uttryck av/Verk/Verkstyp/Har titel/Titel/Deltitel  
(expressionOf/Work/type: Work/hasTitle/Title/partName = 130 #p)  
Lägg till eventuell deltitel.    
Skriv in uppgiften.  

### Relationer till ingaende verk och andra verk

#### Relationer till ingående verk  
* Ingående verk med Primär medverkan (700 1/2 #a, #d, #t)  
  [Se Relationer till delar och verk](https://libris.kb.se/katalogisering/help/workflow-agent-relation).  
* Ingående verk utan Medverkan och funktion/Primär medverkan (730 0/2 #a, #l, analytisk sökingång)  
  Under Instans av Verk, lägg till Har del. Skapa verk som lokal entitet. Man behöver inte välja verkstyp här. Lägg till Har titel och välj Titel. Om det ingående verket är en översättning, lägg till Språk under Verk och länka till entitet.   
 
#### Relationer till andra verk  
* Relationer till andra verk med Primär medverkan (700 1/- #a, #d, #t)  
   [Se Relationer till delar och verk](https://libris.kb.se/katalogisering/help/workflow-agent-relation).
*  Relationer till andra verk utan Medverkan och funktion/Primär medverkan (730 0/_ , icke-analytisk sökingång)  
   Under Instans av Verk, lägg till Relation. Välj typ Relation. Lägg till Entitet och välj Entitet. Skapa verk som lokal entitet. Man behöver inte välja verkstyp här. Lägg till Har titel och välj Titel. Om det relaterade verket är en översättning, lägg till Språk under Verk och länka till entitet.  
  
### Medverkan och funktion  
* Medverkan och funktion  
  Under Medverkan och funktion, ange relationer till de agenter som medverkar i verket, till exempel författare, översättare, illustratörer samt funktionskod för respektive agent. Relationer till utgivare (710) anges för närvarande också här.   
  [Följ instruktioner i hjälptexten Relationer till Agent](https://libris.kb.se/katalogisering/help/workflow-agent-org-instance)  
    
* Medverkan och funktion/Primär medverkan/Agent/Person  
(contribution/PrimaryContribution/agent/Person = 100 1/- #a)   
  Länka till entitet. [Se Relationer till Agent](https://libris.kb.se/katalogisering/help/workflow-agent-org-instance).  
 
* Medverkan och funktion/Primär medverkan/Funktion  
(contribution/PrimaryContribution/role = 100 #4)  
  Länka till entitet. [Se Relationer till Agent](https://libris.kb.se/katalogisering/help/workflow-agent-org-instance).  
  
* Medverkan och funktion/Medverkan/Agent/Person  
(contribution/agent/Person = 700 1/- #a)  
  Länka till entitet. [Se Relationer till Agent](https://libris.kb.se/katalogisering/help/workflow-agent-org-instance).  
  
* Medverkan och funktion/Medverkan/Agent/Organisation  
(contribution/agent/Organisation = 710 2/- #a, #4 pbl)  
  Länka till entitet. [Se Relationer till Agent](https://libris.kb.se/katalogisering/help/workflow-agent-org-instance). 
  
* Medverkan och funktion/Medverkan/Agent/Jurisdiktion  
(contribution/agent/Jurisdiktion = 710 1/- #a, #4 pbl)   
  Länka till entitet. [Se Relationer till Agent](https://libris.kb.se/katalogisering/help/workflow-agent-org-instance). 

### Sprak 
* Språk (language = 008/35-37)  
  Ange textens språk. För en text på svenska, länka till svenska.   
  Länka till entitet.  
  ```Exempel: svenska (swe)```   
  För att ange att texten är på flera språk, länka till ytterligare en språkkod.  
  För att ange originalspråk för ett översatt verk, se Översättning, nedan. 
  
#### Översättning   
* Anmärkning: Språk (marc:LanguageNote = 041 i1: 1)  
```Exempel: objektet är/innehåller översättning```  
**Från och med version 1.18 skapas uppgiften automatiskt.** 
    
**Från och med version 1.18 anges originalspråk för översättningar under Översättning av, inte som tidigare under Originalversion. OBS! För närvarande ska titel och medverkan inte läggas till under Översättning av. Fortsätt att ange dem som tidigare direkt under Instans av verk.**   
* Översättning av/Verk/Verkstyp/Språk (translationOf/Work/type: Work/language = 041 #h)  
  Ange det språk som en översatt text är översatt från. För en text som är översatt från engelska till svenska, ange engelska här.   
  Klicka på plustecknet vid Instans av verk, välj Översättning av, klicka på plustecknet vid Översättning av, välj Skapa lokal entitet. Skriv Verk i rutan för Skapa lokal entitet och välj * Verk. Man behöver inte välja verkstyp här. Ange originalspråk genom att länka till språk här.  
  ![Uppgift om originalversionens språk](translationof.png)  
   
För översättningar i flera led, använd egenskapen Intermediärt språk till översättningar.  
![Intermediärt språk](intermediate_language.png)  
 
För en översättning ska översättningens språk också läggas till i klartext i marcpostens delfält #l, som ett tillägg till verkets titel.  

Om översättningen är ett verk som har Primär medverkan, ska språket läggas till i 240 #l.  
**Från och med version 1.7 skapas språktillägget automatiskt, för 240 #l.**   

Om översättningen är ett anonymt verk, det vill säga saknar Primär medverkan, ange språket som ska visas i klartext här:  
Uttryck av/Verk/Verkstyp/Språk (Language/label = 130 #l)  
Länka till entitet.  
Om översättningen är ett ingående verk, ange språket som ska visas i klartext här:  
Har del/Verk/Verkstyp/Språk (Language/label = 730 #l)  
Länka till entitet.  
  
##### Parallelltext  
(008/35-37 + 041 #a + #a)  
* Språk (language = 008/35-37) +
   Anmärkning: Språk: Objektet är/innehåller ej översättning (marc:languageNote = 041 0/- #a)  
   Ange det första språket genom att länka till språket, under Språk. Länka till ytterligare ett språk för parallelltexten. Ange sedan om parallelltexten är en översättning. Klicka på plustecknet vid Verk och välj Anmärkning: Språk. Välj Objektet är/innehåller ej översättning.    
   
##### Parallelltext och texten delvis översatt 
(008/35-37 + 041 0/- #a + 041 1/- #a #h)  
* Språk (language = 008/35-37) +
   Anmärkning: Språk: Objektet är/innehåller ej översättning (marc:languageNote = 041 0/- #a)   
* Har del/Verk/Verkstyp/Språk (hasPart/Work/type: Work/language = 041 #a) +  
  Anmärkning: Språk: Objektet är/innehåller översättning (marc:languageNote 041 1/-) +  
  Översättning av/Verk/Verkstyp/Språk (translationOf/Work/type: Work/language = 041 #h) 
  
  För att ange att texten delvis är översatt, till exempel när en publikation innehåller parallelltext där den ena texten är en översättning: Lägg först till Språk under Instans av verk. Sök fram och länka till det språk som inte är en översättning. Klicka sedan på plustecknet vid Verk och välj Anmärkning: Språk. Välj Objektet är/innehåller ej översättning.   
 Lägg till Har del under Instans av verk. Skapa verk som lokal entitet. Man behöver inte välja verkstyp här. Lägg till Språk under Verk. Sök fram och länka till språket som texten är översatt till. Lägg till Anmärkning: Språk och ange att resursen är/innehåller en översättning. Under Har del/Verk, lägg till Översättning av/Verk/Verkstyp/Språk (se ovan under Översättning). Länka till språket som resursen delvis är en översättning från.  
 
#### Sammanfattningsspråk  
Se Sammanfattning av innehåll   
  
#### Anmärkning om språk    
* Anmärkning/Anmärkning om språk/Benämning  
(hasNote/marc:LanguageNote/label = 546 #a)  
  ```Exempel: Parallelltext på svenska och engelska```  
Anmärkningen finns i vissa mallar och kan läggas till med hjälp av Berikning från mall. Det går ännu inte att lägga till egenskapen från Lägg till egenskaper.  
  
### Genre form
Länka till entiteter.  
 För att söka efter entiteter inom Genre/form, klicka på plustecknet vid Genre/form (lägg till entitet). Skriv in sökbegrepp. Vid behov, välj typ. Trunkera genom att trycka på mellanslagstangenten eller med * i sökrutan. Välj entitet genom att klicka på plustecknet vid entiteten (Lägg till). Vid behov, välj ytterligare entiteter i listan.  
 [Se instruktionsfilm Lägga till Genre/form](https://youtu.be/aAMzfkh_ycA)  
 
Under Genre/form, ange dels termer som motsvarar marc-koder i 008, dels saogf-termer (genre/form-termer enligt Svenska ämnesord).  

![Lägga till genre/form](genre_exempel.png) 

#### Marc-koder i 008
För att länka till genretermer som motsvarar marc-koder i 008, välj rubrik under Föreslagna (eller vid behov välj en annan rubrik längre ner i listan). Trunkera med * för att se listan över typer under varje rubrik. Länka till entitet.  
 
##### Konferenspublikation       
* Genre/form – konferenspublikation (genreForm = 008/29)       
  ```Exempel: Ja, resursen härrör från konferens```   
     
##### Festskrift     
* Genre/form – festskrift (genreForm = 008/30)     
  ```Exempel: Ja, resursen är en festskrift```    
  
##### Litterär genre  
* Genre/form – litterär genre (genreForm = 008/33)    
  ```Exempel: f ( = roman)```
  
##### Biografiskt material  
* Genre/form – biografiskt material (genreForm = 008/34)   
  ```Exempel: a (= självbiografi)```  
   
##### Akademisk avhandling      
* Genre/form – akademisk avhandling (genreForm = 008/24-27)  
 Skriv "avhandling" i sökrutan.  
 ```Exempel: Akademisk avhandling```  
  [Se även Anmärkning om akademisk avhandling](#anmarkning-om-akademisk-avhandling).  
    
#### Saogf-termer  
* Genre/form – saogf-termer (genreForm = 655 -/7 #a, #2 saogf)  
Sök direkt efter genre/form-termer i sökrutan. Länka till entitet.   
 ```Exempel: Självbiografier```  
 Träfflistan vid sökning på entiteter är för närvarande inte sorterad. Var därför uppmärksam på att det finns liknande genre/form-termer med olika listkoder, till exempel saogf, barngf, gmgpc/swe. Välj kod från rätt lista. För att söka på koder från en specifik lista, lägg till listkoden efter sökordet och mellanslag, t.ex. "tecknade serier saogf". För att söka fram en barngf-term, lägg på motsvarande sätt till koden barngf efter säkordet, t.ex. "bilderböcker barngf".  
[Mer information om listkoder](http://www.kb.se/katalogisering/Svenska-amnesord/genrer-form/).  

### Klassifikation  
**VERSION 1.19:**  
Vissa klassifikationssystem har sedan version 1.19 flyttats till [Instans](https://libris.kb.se/katalogisering/help/workflow-instance).  
Kvar under Verk är DDK, Sekundär DDK-klassifikation, UDK samt SAB.  

* DDK-klassifikation  
  För att lägga till DDK-klassifikation:  
  * Om posten har Klassifikation/Klassifikation (till exempel SAB-klassifikation) men saknar Klassifikation/DDK-klassifikation, lägg till ytterligare en förekomst av Klassifikation (plustecknet vid Klassifikation - lägg till klassifikation). Välj Skapa lokal entitet och välj DDK-klassifikation. Skriv in uppgiften under Kod.  
  * Om posten helt saknar Klassifikation, lägg till Klassifikation genom att klicka på plustecknet till höger om Instans av verk och verkstypen. Välj Klassifikation. Klicka på plustecknet vid Klassifikation (Lägg till klassifikation). Välj Skapa lokal entitet och välj DDK-klassifikation.  
   Skriv in uppgiften under Kod.  

* Klassifikation/DDK-klassifikation/Kod  
(classification/ClassificationDdc/code = 082 0/4 #a)  
  Skriv in uppgiften.  
  ```Exempel: 327.12092```
* Klassifikation/DDK-klassifikation/Klassifikationsupplaga  
(classification/ClassificationDdc/edition = 082 i1)  
  ```Exempel: full```  
*  Parallell upplagebeteckning/Upplagespecifik upphovsuppgift  
(classification/ClassificationDdc/editionEnumeration = 082 #2)  
  ```Exempel: 23/swe```  
  
#### Sekundär DDK-klassifikation  
Lägg till DDK-klassifikation (sekundär) genom att klicka på plustecknet till höger om Instans av verk och verkstypen och välja DDK-klassifikation (sekundär).  
Klicka sedan på plustecknet vid DDK-klassifikation (sekundär) (Lägg till ddk-klassifikation) och välj Skapa lokal entitet. Skriv in uppgiften under Kod.  
* Klassifikation/DDK-klassifikation/Kod  
(additionalClassificationDdc/ClassificationDdc/code = 083 0/- #a)  
  Skriv in uppgiften.  
  ```Exempel: 791.430233092```
* Klassifikation/DDK-klassifikation/Klassifikationsupplaga  
  (classification/ClassificationDdc/edition = 083 i1)  
  ```Exempel: full```  
*  Parallell upplagebeteckning/Upplagespecifik upphovsuppgift   
 (classification/ClassificationDdc/editionEnumeration = 083 #2)  
  ```Exempel: 23/swe``` 
   
#### SAB-klassifikation  
**VERSION 1.19:**  SAB-klassifikation har sedan version 1.19 delvis placerats under [Instans](https://libris.kb.se/katalogisering/help/workflow-instance).  
Det som har flyttats till Instans är när SAB-koden har tillägg för medietyp, t ex Kc/VK. Kvar under Verk finns SAB utan medietillägg.   

* SAB-klassifikation  
  För att lägga till annan klassifikation, till exempel SAB-klassifikation:  
  * Om posten har Klassifikation/DDK-klassifikation men saknar Klassifikation/Klassifikation (till exempel SAB-klassifikation), lägg till ytterligare en förekomst av Klassifikation (plustecknet vid Klassifikation - lägg till klassifikation). Välj Skapa lokal entitet och välj Klassifikation. Skriv in uppgiften under Kod.  
  * Om posten helt saknar Klassifikation, lägg till Klassifikation genom att klicka på plustecknet till höger om Instans av verk och verkstypen. Välj Klassifikation. Klicka på plustecknet vid Klassifikation (Lägg till klassifikation). Välj Skapa lokal entitet och välj Klassifikation.  
   Skriv in uppgiften under Kod.   
* Klassifikation/Klassifikation/Kod  
(classification/Classification/code = 084 0/4 #a)  
     Skriv in uppgiften.  
  ```Exempel: Sei-e```   
  För barnlitteratur ska målgrupp läggas till efter SAB-koden.  
```Exempel: Prab,uf```  
* Klassifikation/Ingår i system/Konceptsystem/Kod  
(classification/Classification/inScheme/ConceptScheme/code = 084 #2)  
 ```Exempel: kssb```  
* Klassifikation/Ingår i system/Konceptsystem/Version  
(classification/Classification/inScheme/ConceptScheme/version = 084 #2)  
 ```Exempel: 8```  
  
### Amne  
* [Se hjälptexten Ämnesord i Libris](https://libris.kb.se/katalogisering/help/workflow-general-sh)  
  
### Malgrupp     
* Målgrupp (intendedAudience = 008/22)  
 Länka till entitet.
 <br/>```Exempel:```
  * ```Barn och ungdom (0-16 år) (008/22: j)```  
  Normalvärde för barn- och ungdomslitteratur.
  
  * ```Barn (ca 10-12 år)/Läromedel (008/22: c)```  
  Normalvärde för läromedel avsedda för skolbruk (till och med gymnasiet).  

  För att lägga till Målgruppsanmärkning (Målgrupp/Målgrupp/Benämning), [se generell hjälptext för Instans](https://libris.kb.se/katalogisering/help/workflow-instance).  

### Innehallstyp
* Innehållstyp/Innehållstyp (contentType/ContentType = 336 #b)   
  Länka till entitet.
  <br/>```Exempel:```
  * ```kartografisk bild (cri)```
  * ```framförd musik (prm)```
  * ```stillbild (sti)```
  * ```text (txt)```
 <br>[Läs mer om innehållstyper](http://www.kb.se/katalogisering/Formathandboken/innehallstyper/innehall/).
  
 För att lägga till ytterligare innehållstyp, till exempel "sti" = stillbild för en bilderbok med både text och bild, länka till ytterligare en entitet. Välj Innehållstyp i listan (i stället för "Föreslagna typer").    
I äldre poster har ytterligare innehållstyp lagts i Har del/Verk. Dessa behöver inte ändras.   
  
### Sammanfattning av innehall    
 * Sammanfattning av innehåll/Sammanfattning/Benämning (summary/Summary/label = 520 #a)  
Lägg till Sammanfattning av innehåll. Välj Sammanfattning av innehåll. Lägg till Sammanfattning.  
 Skriv in uppgiften under Benämning.  
  ```Exempel: Åtskilliga utdrag af framledne … Axel v. Fersens bref till f.d. konungen av Swerige, Gustaf Adolph, 1806```  
  
 * Typ av sammanfattning/typ av innehållsbeskrivning (marc:summaryType = 520 ind1)  
 Sök fram och lägg till Typ av sammanfattning. Välj typ från lista.  
 ```Exempel: Ej preciserad``` 
 
#### Sammanfattningsspråk  
* Sammanfattning av innehåll/Sammanfattning/Språk (summary/Summary/language = 041 #b)  
Lägg till sammanfattningsspråk. Lägg till Sammanfattning. Ta bort Benämning. Länka till entiteten för sammanfattningens språk.  
  ```Exempel: Engelska```
  
### Anmarkning om akademisk avhandling    
* Anmärkning/Anmärkning om akademisk avhandling/Benämning (dissertation/Dissertation/label = 502 #a)  
  Lägg till Anmärkning om akademisk avhandling. Skapa lokal entitet.  
Skriv in anmärkningen under Benämning.    
  ```Exempel: Diss. Umeå : Umeå universitet, 2018```  
