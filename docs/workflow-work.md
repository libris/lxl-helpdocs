---
section: Hjälptexter katalogisering
title: Verk
order: 21
date: 2019-02-12
tags:
- under arbete
- verk
--- 

## Verk

Beskrivningen av ett verk innehåller information som ämne, klassifikation, språk och innehållstyp. Ett verk kan ha en eller flera instanser, till exempel olika upplagor och utgåvor. Läs mer om [Instans](https://libris.kb.se/katalogisering/help/instance).  

Ett verk är av en viss typ. Exempel på verkstyper är: text, ljud, stillbild, rörlig bild, multimedia, karta. Det går för närvarande inte att byta beskrivningens verkstyp.  

Skapa verket som lokal entitet (bryt inte ut verket till en länkbar entitet). Denna hjälptext beskriver exempel på verk som lokal entitet. Det betyder att du anger de uppgifter som listas här nedan under Instans av verk utan att klicka på länksymbolen (Länka entitet) vid Instans av verk.  
Läs mer om [Verk och Instans](https://librisbloggen.kb.se/2018/05/30/verk-och-instans-i-startversionen/).  

Denna hjälptext beskriver de vanligaste egenskaperna under Instans av verk. För instruktioner om att länka till entitet, skapa lokal entitet och om hur formuläret fungerar, se Redigering i vänstermenyn. För information om katalogregler, skrivregler och övriga katalogiseringsanvisningar, se [Anvisningar för katalogisering - RDA](http://www.kb.se/rdakatalogisering/Anvisningar/Arbetsfloden/Tryckta-monografier/ "Anvisningar för katalogisering - RDA").

Se även [instruktionsfilmer](https://www.youtube.com/playlist?list=PLZVkEICvA5-GRT2oJQmLgq_2Pksx6zYPy)  

I de flesta fall ska informationen delas upp i olika egenskaper (jfr fält) och underliggande egenskaper (jfr delfält). I några undantagsfall är det nödvändigt att använda ISBD-interpunktion inom en egenskap, för att separera uppgifter. Dessa fall visas genom exempel nedan. I övriga fall, lägg inte in ISBD-interpunktion för att avsluta en egenskap (fält). 
 

### Innehåll  

| [Verk](#verk) |  |  | 
| ----------- |  ----------- |  ----------- |
| [Verkets titel](#verkets-titel) |  | [Ämne](#amne) | 
| [Relationer till ingående verk och andra verk](#relationer-till-ingaende-verk-och-andra-verk) |  | [Målgrupp](#malgrupp) | 
| [Medverkan och funktion](#medverkan-och-funktion) |  | [Innehållstyp](#innehallstyp) | 
| [Språk](#sprak) |  | [Sammanfattning av innehåll](#sammanfattning-av-innehall) | 
| [Genre](#genre) |  | [Anmärkning om akademisk avhandling](#anmarkning-om-akademisk-avhandling) | 
| [Klassifikation](#klassifikation) |  |  | 

### Verk   
   
#### Instans av verk
* Instans av verk (instanceOf/Work)  
  
För att lägga till egenskaper under Instans av verk, klicka på plustecknet till höger om Instans av verk och verkstypen.  
![Instans av verk](instansavverk.png)  

Sök fram egenskapen och välj den genom att klicka på plustecknet vid egenskapens namn.  

![Instans av verk egenskap](instansavverkegenskap.png)  


#### Verkets titel
Ange den föredragna titeln för verket här, vid behov. Följ [Anvisningar för katalogisering - RDA](http://www.kb.se/rdakatalogisering/Anvisningar/Allmanna-anvisningar/Sokingangar-for-verk-och-uttryck "Anvisningar för katalogisering - RDA").  
Ange föredragen titel för översättningar, för verk som har givits ut under olika titlar på samma språk eller när samma titel har använts för olika verk.   

##### Verkets titel
###### Verk med Primär medverkan
* Har titel/Titel/Huvudtitel (hasTitle/Title/mainTitle = 240 1/0 ‡a)  
  "Originaltitel" för ett verk med Medverkan och funktion/Primär medverkan anges här.  
  Skriv in uppgiften.  
  ```Exempel: Soldier spy```  
  För en titel som börjar med bestämd eller obestämd artikel, ska artikeln fileras bort. Lägg till fileringsvärde och ange en siffra.  

###### Verk utan Primär medverkan
*	Uttryck av/Verk/Har titel/Titel/Huvudtitel (expressionOf/Work/hasTitle/Title/mainTitle (= 130 ‡a)  
 "Originaltitel" för ett verk utan Medverkan och funktion/Primär medverkan anges här.
Under Instans av Verk, lägg till Uttryck av. Skapa verk som lokal entitet (skriv "verk" i rutan Skapa lokal entitet och välj verk). Lägg till Har titel. Välj Titel.
Skriv in uppgiften under Huvudtitel.  
```Exempel: Bibeln``` 
*	Uttryck av/Verk/Har titel/Titel/Deltitel  
(expressionOf/Work/hasTitle/Title/partName = 130 ‡p)  
Lägg till eventuell deltitel.    
Skriv in uppgiften.  

#### Relationer till ingaende verk och andra verk

##### Relationer till ingående verk  
* Ingående verk med Primär medverkan (700 1/2 ‡a, ǂd, ǂt)  
  Se [Relationer till delar och verk](https://libris.kb.se/katalogisering/help/workflow-agent-relation).  
* Ingående verk utan Medverkan och funktion/Primär medverkan (730 0/2 ‡a, ǂl, analytisk sökingång)  
  Under Instans av Verk, lägg till Har del. Skapa verk som lokal entitet. Lägg till Har titel och välj Titel. Om det ingående verket är en översättning, lägg till Språk under Verk, skapa lokal entitet och lägg till Benämning. Skriv in språket.
 
##### Relationer till andra verk  
  * Relationer till andra verk med Primär medverkan (700 1/- ‡a, ǂd, ǂt)  
   Se [Relationer till delar och verk](https://libris.kb.se/katalogisering/help/workflow-agent-relation).
*  Relationer till andra verk utan Medverkan och funktion/Primär medverkan (730 0/_ , icke-analytisk sökingång)  
   Under Instans av Verk, lägg till Relation. Välj typ Relation. Lägg till Entitet och välj Entitet. Skapa verk som lokal entitet. Lägg till Har titel och välj Titel. Om det relaterade verket är en översättning, lägg till Språk, skapa lokal entitet och lägg till Benämning. Skriv in språket.
  
#### Medverkan och funktion  
* Medverkan och funktion  
  Under Medverkan och funktion, ange relationer till de agenter som medverkar i verket, till exempel författare, översättare, illustratörer samt funktionskod för respektive agent. Relationer till utgivare (710) anges för närvarande också här.   
  Följ dessa instruktioner:  
  [Relationer till Agent](https://libris.kb.se/katalogisering/help/workflow-agent-org-instance)  
    
* Medverkan och funktion/Primär medverkan/Agent/Person (contribution/PrimaryContribution/agent/Person = 100 1/- ‡a)  
  Länka till entitet. Se [Relationer till Agent](https://libris.kb.se/katalogisering/help/workflow-agent-org-instance).  
 
* Medverkan och funktion/Primär medverkan/Funktion (contribution/PrimaryContribution/role = 100 ‡4)  
  Länka till entitet. Se [Relationer till Agent](https://libris.kb.se/katalogisering/help/workflow-agent-org-instance).  
  
* Medverkan och funktion/Medverkan/Agent/Person (contribution/agent/Person = 700 1/- ‡a)  
  Länka till entitet. Se [Relationer till Agent](https://libris.kb.se/katalogisering/help/workflow-agent-org-instance).  
  
* Medverkan och funktion/Medverkan/Agent/Organisation (contribution/agent/Organisation = 710 2/- ‡a, ‡4 pbl)  
  Länka till entitet. Se [Relationer till Agent](https://libris.kb.se/katalogisering/help/workflow-agent-org-instance). 
  
* Medverkan och funktion/Medverkan/Agent/Jurisdiktion (contribution/agent/Jurisdiktion = 710 1/- ‡a, ‡4 pbl)  
  Länka till entitet. Se [Relationer till Agent](https://libris.kb.se/katalogisering/help/workflow-agent-org-instance). 

#### Sprak 
* Språk (language = 008/35-37)  
  Ange textens språk. För en text på svenska, länka till svenska. För att ange originalspråk för ett översatt verk, se Originalversion/Verk/Språk.  
  Länka till entitet.  
  ```Exempel: svenska (swe)```   
  För att ange att texten är på flera språk, länka till ytterligare en språkkod.     
  
##### Översättning  
För en översättning, ange även:  
* Språk/Språk/Benämning (Language/label = 130 ‡l, 240 ‡l)  
  Lägg till ytterligare en förekomst av Språk, under Språk, skapa lokal entitet och lägg till Benämning.  
  Skriv in språket i klartext. Denna klartext - verkets (översättningens) språk - visas som ett tillägg till verkets titel i marcpostens 130 ‡l, 240 ‡l, 730 ‡l.  
  ![Språk](sprak.png)

* Anmärkning: Språk (marc:LanguageNote = 041 i1: 1)  
  Ange om resursen är/innehåller en översättning.  
  För att lägga till uppgiften, klicka på plustecknet till höger om Instans av verk och verkstypen och välj Anmärkning: Språk. Välj fras från lista.  
  ```Exempel: objektet är/innehåller översättning```  
  
* Originalversion/Verk/Språk (originalversion/Work/language = 041 ‡h)  
  Ange det språk som en översatt text är översatt från. För en text som är översatt från engelska till svenska, ange engelska här.   
  Klicka på plustecknet vid Instans av verk, välj Originalversion, klicka på plustecknet vid Originalversion, välj Skapa lokal entitet. Skriv Verk i rutan för Skapa lokal entitet och välj * Verk. Lägg till Språk under verk. Sök fram språkentiteten och länka.  
  ![Originalversion sprak](originalversionsprak.png)  
För översättningar i flera led, länka först till det mellanliggande språket och därefter till originalspråket.  
  
###### Parallelltext  
(008/35-37 + 041 ‡a + ‡a)  
* Språk (language = 008/35-37) +
   Anmärkning: Språk: Objektet är/innehåller ej översättning (marc:languageNote = 041 0/- ‡a)
   Ange det första språket genom att länka till språket, under Språk. Länka till ytterligare ett språk för parallelltexten. Ange sedan om parallelltexten är en översättning. Klicka på plustecknet vid Verk och välj Anmärkning: Språk. Välj Objektet är/innehåller ej översättning.    
   
###### Parallelltext och texten delvis översatt 
(008/35-37 + 041 0/- ‡a + 041 1/- #a ‡h)  
* Språk (language = 008/35-37) +
   Anmärkning: Språk: Objektet är/innehåller ej översättning (marc:languageNote = 041 0/- ‡a)   
* Har del/Verk/Språk (hasPart/Work/language = 041 ‡a) +  
  Anmärkning: Språk: Objektet är/innehåller översättning (marc:languageNote 041 1/-) +  
  Originalversion/Verk/Språk (originalVersion/Work/language = 041 ‡h) 
  
  För att ange att texten delvis är översatt, till exempel när en publikation innehåller parallelltext där den ena texten är en översättning: aLägg först till Språk under Instans av verk. Sök fram och länka till det språk som inte är en översättning. Klicka sedan på plustecknet vid Verk och välj Anmärkning: Språk. Välj Objektet är/innehåller ej översättning.   
 Lägg till Har del under Instans av verk. Skapa verk som lokal entitet. Lägg till Språk under Verk. Sök fram och länka till språket som texten är översatt till. Lägg till Anmärkning: Språk och ange att resursen är/innehåller en översättning. Under Har del, lägg till Originalversion/Verk/Språk (se ovan under Översättning). Länka till språket som resursen delvis är en översättning från.  
 
##### Sammanfattningsspråk  
Se Sammanfattning av innehåll   
  
##### Språkanmärkning     
* Anmärkning/Anmärkning om språk/Anmärkning: Språk/Benämning
(hasNote/marc:LanguageNote/marc:LanguageNote/label = 546 ‡a)  
  ```Exempel: Parallelltext på svenska och engelska```  
  Anmärkningen är under arbete och fungerar tyvärr ännu inte.  
  
#### Genre 
Länka till entiteter.  
 För att söka efter entiteter inom Genre/form, klicka på plustecknet vid Genre/form (lägg till entitet). I Lägg till entitet, välj typ. Skriv in sökbegrepp. Trunkera genom att trycka på mellanslagstangenten eller med * i sökrutan. Välj entitet genom att klicka på plustecknet vid entiteten (Lägg till). Vid behov, välj ytterligare entiteter i listan. 
 
Under Genre/form, ange dels saogf-termer (genre/form-termer enligt Svenska ämnesord), dels termer som motsvarar marc-koder i 008.  
För att länka till saogf-termer, välj Genre/form i listan (det första alternativet under Alla).  
För att länka till termer som motsvarar marc-koder i 008, se övriga rubriker. De vanligaste finns under rubriken Föreslagna.  
![Genre exempel](genre_exempel.png)  

##### Saogf-termer  
* Genre/form – saogf-termer (genreForm = 655 -/7 ‡a, ‡2 saogf)  
 Välj Genre/form i listan över typer. Avgränsa till saogf-termer genom att skriva "saogf" efter söktermen. Länka till entitet.  
 Träfflistan vid sökning på entiteter är för närvarande inte sorterad. Var därför uppmärksam på att det finns liknande genre/form-termer med olika listkoder, till exempel sao, barngf, gmgpc/swe. Välj kod från rätt lista. Mer [information om listkoder](http://www.kb.se/katalogisering/Svenska-amnesord/genrer-form/).  
 ```Exempel: Självbiografier```  
  Se [instruktionsfilm](https://www.youtube.com/watch?v=wrqs310Nt0M&list=PLZVkEICvA5-GRT2oJQmLgq_2Pksx6zYPy&index=7)  
  
##### Biografiskt material  
* Genre/form – biografiskt material (genreForm = 008/34)  
  Välj Biografiskt material i listan över typer. Länka till entitet.  
  ```Exempel: a (= självbiografi)```  
  
##### Festskrift     
* Genre/form – festskrift (genreForm = 008/30)  
  Välj Festskrift i listan över typer. Länka till entitet.    
  ```Exempel: Ja, resursen är en festskrift```    
  
##### Litterär genre  
* Genre/form – litterär genre (genreForm = 008/33)  
  Välj Litterär genre i listan över typer. Länka till entitet.  
  ```Exempel: 0 ( = ej skönlitterärt verk)```
   
##### Konferenspublikation       
* Genre/form – konferenspublikation (genreForm = 008/29)  
  Välj Konferenspublikation i listan över typer. Länka till entitet.         
  ```Exempel: Ja, resursen härrör från konferens```   
     
##### Akademisk avhandling      
* Genre/form – akademisk avhandling (genreForm = 008/24-27)  
  Välj Innehåll, i listan över typer. Skriv "avhandling" i sökrutan. Länka till entitet.      
  ```Exempel: Akademisk avhandling```  
  Se även [Anmärkning om akademisk avhandling](#anmarkning-om-akademisk-avhandling).  

#### Klassifikation  
* DDK-klassifikation  
  För att lägga till DDK-klassifikation:  
  * Om posten har Klassifikation/Klassifikation (till exempel SAB-klassifikation) men saknar Klassifikation/DDK-klassifikation, lägg till ytterligare en förekomst av Klassifikation (plustecknet vid Klassifikation - lägg till klassifikation). Välj Skapa lokal entitet och välj DDK-klassifikation. Skriv in uppgiften under Kod.  
  * Om posten helt saknar Klassifikation, lägg till Klassifikation genom att klicka på plustecknet till höger om Instans av verk och verkstypen. Välj Klassifikation. Klicka på plustecknet vid Klassifikation (Lägg till klassifikation). Välj Skapa lokal entitet och välj DDK-klassifikation.  
   Skriv in uppgiften under Kod.  

* Klassifikation/DDK-klassifikation/Kod (classification/ClassificationDdc/code = 082 0/4 ‡a)  
  Skriv in uppgiften.  
  ```Exempel: 327.12092```
* Klassifikation/DDK-klassifikation/Klassifikationsupplaga (classification/ClassificationDdc/edition = 082 ‡2)  
  ```Exempel: full```  
*  Parallell upplagebeteckning/Upplagespecifik upphovsuppgift (classification/ClassificationDdc/editionEnumeration = 082 ‡2)  
  ```Exempel: 23/swe```  
  
##### Sekundär DDK-klassifikation  
Lägg till DDK-klassifikation (sekundär) genom att klicka på plustecknet till höger om Instans av verk och verkstypen och välja DDK-klassifikation (sekundär).  
Klicka sedan på plustecknet vid DDK-klassifikation (sekundär) (Lägg till ddk-klassifikation) och välj Skapa lokal entitet. Skriv in uppgiften under Kod.  
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
  * Om posten har Klassifikation/DDK-klassifikation men saknar Klassifikation/Klassifikation (till exempel SAB-klassifikation), lägg till ytterligare en förekomst av Klassifikation (plustecknet vid Klassifikation - lägg till klassifikation). Välj Skapa lokal entitet och välj Klassifikation. Skriv in uppgiften under Kod.  
  * Om posten helt saknar Klassifikation, lägg till Klassifikation genom att klicka på plustecknet till höger om Instans av verk och verkstypen. Välj Klassifikation. Klicka på plustecknet vid Klassifikation (Lägg till klassifikation). Välj Skapa lokal entitet och välj Klassifikation.  
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
  Länka  i första hand till entiteter för ämnesord. Följ instruktionerna på följande sidor:  
  [Länka till auktoriserat ämnesord](https://libris.kb.se/katalogisering/help/workflow-linked-entity-sh)   
  [Lägg till sammansatt men ej auktoriserat ämnesord](https://libris.kb.se/katalogisering/help/workflow-non-auth-sh)   
  [Lägg till kontrollerade men ej auktoriserade ämnesord](https://libris.kb.se/katalogisering/help/workflow-controlled-non-auth-sh)   
  [Lägg till okontrollerade ämnesord, t.ex. prel-termer i samband med ämnesordsförslag](https://libris.kb.se/katalogisering/help/workflow-uncontrolled-sh)

##### Allmänt ämnesord  
* Ämne - sao-term  (subject = 650 -/7 ‡a, ‡2 sao)  
  Länka till entitet från Svenska ämnesord, enligt instruktion:  
  [Länka till auktoriserat ämnesord](https://libris.kb.se/katalogisering/help/workflow-linked-entity-sh)    
   
* Ämne - annan kontrollerad lista (subject = 650 -/7 ‡a, ‡2)  
  För ämnesord från andra kontrollerade listor, följ denna instruktion:  
  [Lägg till kontrollerade men ej auktoriserade ämnesord](https://libris.kb.se/katalogisering/help/workflow-controlled-non-auth-sh)  
  
* Ämne - okontrollerade (subject = 653 -/- ‡a)  
  För ämnesord från andra kontrollerade listor, följ denna instruktion:  
  [Lägg till kontrollerade men ej auktoriserade ämnesord](https://libris.kb.se/katalogisering/help/workflow-controlled-non-auth-sh)   

##### Allmänt ämnesord med underindelning   
* Ämne - sao-term  (subject = 650 -/7 ‡a, ‡x, ‡2 sao)  
  Länka till entitet från Svenska ämnesord, enligt instruktion:  
  [Länka till auktoriserat ämnesord](https://libris.kb.se/katalogisering/help/workflow-linked-entity-sh)  
  
##### Geografiska ämnesord  
* Geografiskt ämnesord (subject = 651 -/4 ‡a)  
  Länka till entitet från Svenska ämnesord, enligt instruktion:  
  [Länka till auktoriserat ämnesord](https://libris.kb.se/katalogisering/help/workflow-linked-entity-sh)
  
##### Geografiskt ämnesord med geografisk underindelning  
* Geografiskt ämnesord (subject = 651 -/7 ‡a, ‡x, ‡2 sao)  
  För auktoriserade geografiska ämnesordssträngar, följ denna instruktion:    
 [Länka till auktoriserat ämnesord](https://libris.kb.se/katalogisering/help/workflow-linked-entity-sh)   
  För ej auktoriserade geografiska ämnesordssträngar, följ denna instruktion:  
 [Lägg till sammansatt men ej auktoriserat ämnesord](https://libris.kb.se/katalogisering/help/workflow-non-auth-sh) 
   
##### Kronologiskt ämnesord
* Ämne/Kronologiskt ämnesord (subject = 648 7/- ‡a, ‡2 sao)  
  Länka till entitet. Följ denna instruktion:  
  [Länka till auktoriserat ämnesord](https://libris.kb.se/katalogisering/help/workflow-linked-entity-sh)   
  
##### Ämnesord Person  
* Ämne/Agent/Person (subject = 600 1/4- ‡a)      
 Länka till entitet. Följ dessa instruktioner:  
 [Relationer till Agent](https://libris.kb.se/katalogisering/help/workflow-agent-org-instance)   
 I undantagsfall, skapa lokal entitet.  
  
##### Ämnesord Organisation  
* Ämne/Agent/Organisation (subject/agent/Organization = 610 2/- ‡a)  
  Länka till entitet. Följ dessa instruktioner:  
  [Relationer till Agent](https://libris.kb.se/katalogisering/help/workflow-agent-org-instance)   
  I undantagsfall, skapa lokal entitet.  
 
#### Malgrupp     
* Målgrupp (intendedAudience = 008/22)
 Länka till entitet.  
 <br/>```Exempel:```
  * ```Barn och ungdom (0-16 år) (008/22: j)```
  Normalvärde för barn- och ungdomslitteratur.
  
  * ```Barn (ca 10-12 år)/Läromedel (008/22: c)```  
  Normalvärde för läromedel avsedda för skolbruk (till och med gymnasiet).  

  För att lägga till Målgruppsanmärkning (Målgrupp/Målgrupp/Benämning), se [Instans](https://libris.kb.se/katalogisering/help/workflow-instance).  

#### Innehallstyp
* Innehållstyp/Innehållstyp (contentType/ContentType = 336 ‡b)   
  Länka till entitet.  
  <br/>```Exempel:```
  * ```kartografisk bild (cri)```
  * ```framförd musik (prm)```
  * ```stillbild (sti)```
  * ```text (txt)```
 <br>Läs mer om [innehållstyper](http://www.kb.se/katalogisering/Formathandboken/innehallstyper/innehall/).
  
  För att lägga till ytterligare innehållstyp, till exempel "sti" = stillbild för en bilderbok med både text och bild, lägg till Har del under Instans av verk. Skapa Verk som lokal entitet. Välj Skapa lokal entitet och välj därefter ++ Verk i listan. Lägg till Innehållstyp under Verk. Sök fram och länka till entitet.  
  
#### Sammanfattning av innehall    
 * Sammanfattning av innehåll/Sammanfattning/Benämning (summary/Summary/label = 520 ‡a)  
Lägg till Sammanfattning av innehåll. Välj Sammanfattning av innehåll. Lägg till Samanfattning.  
 Skriv in uppgiften under Benämning.  
  ```Exempel: Åtskilliga utdrag af framledne … Axel v. Fersens bref till f.d. konungen av Swerige, Gustaf Adolph, 1806```  
  
 * Typ av sammanfattning/typ av innehållsbeskrivning (marc:summaryType = 520 ind1)  
 Sök fram och lägg till Typ av sammanfattning. Välj typ från lista.  
 ```Exempel: Ej preciserad``` 
 
##### Sammanfattningsspråk  
* Sammanfattning av innehåll/Sammanfattning/Språk (summary/Summary/language = 041 ‡b)  
Lägg till sammanfattningsspråk. Lägg till Sammanfattning. Ta bort Benämning. Länka till entiteten för sammanfattningens språk.  
  ```Exempel: Engelska```
  
#### Anmarkning om akademisk avhandling    
* Anmärkning/Anmärkning om akademisk avhandling/Benämning (dissertation/Dissertation/label = 502 ‡a)  
  Lägg till Anmärkning om akademisk avhandling. Skapa lokal entitet.  
Skriv in anmärkningen under Benämning.    
  ```Exempel: Diss. Umeå : Umeå universitet, 2018```  