---
section: Generell beskrivning
title: Verk
order: 26
date: 2025-03-06
tags:
- verk
--- 

# Verk


| Innehåll  |  |  | 
| ----------- |  ----------- |  ----------- |
| [Inledning](#inledning)  |  | [Genre/form](#genre-form) | 
| [Verkstyp](#verkstyp)  |  | [Klassifikation](#klassifikation) | 
| [Föredragen titel för verket](#föredragen-titel-för-verket) |  | [Ämne](https://libris.kb.se/katalogisering/help/workflow-general-sh) | 
| [Relationer till ingående verk och andra verk](#relationer-till-ingaende-verk-och-andra-verk) |  | [Målgrupp](#målgrupp) | 
| [Medverkan och funktion](#medverkan-och-funktion) |  | [Målgruppsanmärkning](#målgruppsanmärkning) | 
| [Språk](#språk) |  | [Innehållstyp](#innehållstyp) | 
| [Översättning av](#översättning-av) |  | [Anmärkning om akademisk avhandling](#anmärkning-om-akademisk-avhandling) | 

Det är möjligt att bryta ut verk i Libris. Men du ska bara göra det i vissa fall. Arbete pågår med verk i och det sker förändringar i verktyget och i praxis löpande. Det är viktigt att följa aktuella instruktioner!
Läs [Att arbeta med länkade verk i Libris](https://metadatabyran.kb.se/generella-anvisningar---rda/verk-och-uttryck/att-arbeta-med-lankade-verk-i-libris).  

Följ [nyhetsflödet i Metadatabyrån](https://metadatabyran.kb.se/ovrigt/nyhetslistning) för att hålla dig uppdaterad!

Se också [Lathundar för verk i Libris, i Metadatabyrån](https://metadatabyran.kb.se/generella-anvisningar---rda/verk-och-uttryck/lathundar-for-verk-i-libris).

## Inledning
Beskrivningen av ett verk innehåller information som ämne, klassifikation, språk och innehållstyp. Ett verk kan ha en eller flera instanser, till exempel olika upplagor och utgåvor. Vissa egenskaper, till exempel utgivning, bärartyp och omfång, beskrivs i stället under Instans. [Läs mer om Instans](https://libris.kb.se/katalogisering/help/workflow-instance).  

Denna hjälptext beskriver exempel på verk som lokal entitet. Det betyder att du anger de uppgifter som listas här nedan under "Instans av" utan att klicka på länksymbolen (Länka entitet) vid Instans av. Mallen för att skapa nytt verk bör inte användas.

**Denna hjälptext beskriver de vanligaste egenskaperna under Instans av / Verk.** 

  * För utförligare instruktioner om att lägga till och ta bort egenskaper, länka till entitet, skapa lokal entitet och om hur formuläret fungerar, se Redigering i vänstermenyn
  * För information om katalogregler, skrivregler och övriga katalogiseringsanvisningar, [se Verk och uttryck, i Metadatabyrån](https://metadatabyran.kb.se/generella-anvisningar---rda/verk-och-uttryck)
  * Se även instruktionsfilmer:
    
    [Librisutbildning](https://kbplay.mediaflowportal.com/folder/88157/)   
    [Instruktionsfilmer för Libris katalogisering](https://kbplay.mediaflowportal.com/folder/91512/)
    
I de flesta fall ska informationen delas upp i olika egenskaper (jfr fält) och underliggande egenskaper (jfr delfält). I några undantagsfall är det nödvändigt att använda ISBD-interpunktion inom en egenskap, för att separera uppgifter. Dessa fall visas genom exempel nedan. I övriga fall, lägg inte in ISBD-interpunktion för att avsluta en egenskap (fält). 

## Verkstyp
(= 000/06)   
Ett verk är av en viss typ. Exempel på verkstyper är: text, ljud, stillbild, rörlig bild, multimedia, karta. För instruktioner om att byta verkstyp, [se Att använda verktyget](https://libris.kb.se/katalogisering/help/use-the-editor).  

Från version 1.19 av katalogiseringsverktyget är verkstyperna försedda med illustrerande ikoner:
![Ikoner för de olika verksyperna](verkstypsikoner.png)

När man skapar Instans eller Verk som lokal entitet under en egenskap behöver man inte välja Instans- eller Verkstyp.

## Instans av / Verk
* Instans av (instanceOf)  

För att lägga till egenskaper i beskrivningen av verket, klicka på plustecknet till höger om "Instans av" och verkstypen.  
![Lägg till egenskaper under Instans av](instansav.png)  

Sök fram egenskapen och välj den genom att klicka på plustecknet vid egenskapens namn.  

![Sök fram och lägg till egenskap](instansavverkegenskap.png)  


### Föredragen titel för verket
Ange den föredragna titeln för verket här (direkt under Instans av), vid behov. [Följ anvisningar i Metadatabyrån - Föredragen titel för verket](https://metadatabyran.kb.se/generella-anvisningar---rda/verk-och-uttryck/egenskaper-som-beskriver-verk-och-uttryck/foredragen-titel-for-verket).  
  
* Har titel/Titel/Huvudtitel (hasTitle/Title/mainTitle). Om Primär medverkan finns i posten, exporteras uppgiften till 240 #a. Om Primär medverkan inte finns i posten, exporteras uppgiften till 130 #a.  
Skriv in uppgiften.  

I följande exempel har verket utkommit tidigare med annan titel. Ange föredragen titel för verket här.    
 ```Exempel: Choklad```  

I följande exempel har verket utkommit under olika titlar. Ange föredragen titel för verket här.    
```Exempel: Bibeln``` 

För en titel som börjar med bestämd eller obestämd artikel, ska artikeln fileras bort. Lägg till Fileringsvärde och ange en siffra.  
  
För översättningar, ange originaltiteln under [Översättning av](#översättning-av).  

### Relationer till ingående verk och andra verk

#### Relationer till ingående verk   
[Se Relationer till ingående verk/uttryck, i Metadatabyrån](https://metadatabyran.kb.se/generella-anvisningar---rda/verk-och-uttryck/relationer-till-ingaende-verk-uttryck).
* Ingående verk med Primär medverkan (700 1/2 #a, #d, #t)       
* Ingående verk utan Medverkan och funktion/Primär medverkan (730 0/2 #a, #l, analytisk sökingång)  
  Under "Instans av", lägg till Har del. Skapa verk som lokal entitet. Man behöver inte välja verkstyp här. Lägg till Har titel och välj Titel. Om det ingående verket är en översättning, lägg till Språk under Verk och länka till entitet.   

#### Relationer till andra verk  
* Relationer till andra verk med Primär medverkan (700 1/- #a, #d, #t)   
  Under "Instans av", lägg till Relation. Välj typ Relation. Lägg till egenskap och välj Entitet. Skapa verk som lokal entitet. Ange Primär medverkan och Har titel / Titel / Huvudtitel.  
* Relationer till andra verk utan Medverkan och funktion/Primär medverkan (730 0/_ , icke-analytisk sökingång)  
   Under "Instans av", lägg till Relation. Välj typ Relation. Lägg till egenskap och välj Entitet. Skapa verk som lokal entitet. Ange Har titel / Titel / Huvudtitel.       

### Medverkan och funktion  
Under Medverkan och funktion, ange relationer till de agenter som medverkar i verket, till exempel författare, översättare, redaktörer samt funktionskod för respektive agent. Från version 1.33 av Libris katalogisering finns vissa begränsningar för funktionerna. På id.kb.se listas funktioner: 
   * [Funktioner möjliga att använda endast på verk](https://id.kb.se/find?q=%2a&%40type=Role&and-domain.%40id=https%3A%2F%2Fid.kb.se%2Fvocab%2FWork&_sort=_sortKeyByLang.sv) 
   * [Funktioner möjliga att använda på verk och instans](https://id.kb.se/find?q=%2a&%40type=Role&and-domain.%40id=https%3A%2F%2Fid.kb.se%2Fvocab%2FCreation&_sort=_sortKeyByLang.sv)
   * [Funktioner möjliga att använda på verk, instans och bestånd](https://id.kb.se/find?q=%2a&%40type=Role&and-domain.%40id=https%3A%2F%2Fid.kb.se%2Fvocab%2FEndeavour&_sort=_sortKeyByLang.sv)

För anvisningar, se [Agenter knutna till verk och uttryck, i Metadatabyrån](https://metadatabyran.kb.se/generella-anvisningar---rda/verk-och-uttryck/agenter-knutna-till-verk-och-uttryck)

* Medverkan och funktion/Primär medverkan/Agent/Person  
(contribution/PrimaryContribution/agent/Person = 100 1/- #a)   
  Länka till entitet.

* Medverkan och funktion/Primär medverkan/Funktion  
(contribution/PrimaryContribution/role = 100 #4)  
  Länka till entitet.

* Medverkan och funktion/Medverkan/Agent/Person  
(contribution/agent/Person = 700 1/- #a)  
  Länka till entitet.

* Medverkan och funktion/Medverkan/Funktion  
(contribution/PrimaryContribution/role = 700 #4)  
  Länka till entitet.

### Språk 
* Språk (language = 008/35-37)  
  Ange textens språk. För en text på svenska, länka till svenska.   
  Länka till entitet.  
  ```Exempel: svenska (swe)```   
  För att ange att texten är på flera språk, länka till ytterligare en språkkod.  
  För att ange originalspråk för ett översatt verk, se Översättning av, nedan. 

#### Översättning av 
* Anmärkning: Språk (marc:LanguageNote = 041 i1: 1)  
```Exempel: objektet är/innehåller översättning```   
  *Uppgiften skapas automatiskt.*
   
* Översättning av/Verk/Verkstyp/Språk (translationOf/Work/type: Work/language = 041 #h)  
  Ange det språk som en översatt text är översatt från. För en text som är översatt från engelska till svenska, ange engelska här.
  
  Klicka på plustecknet vid "Instans av", välj Översättning av, klicka på plustecknet vid Översättning av, välj Skapa lokal entitet. Skriv Verk i rutan för Skapa lokal entitet och välj * Verk. Man behöver inte välja verkstyp här. Ange originalspråk genom att länka till språk här.  
  ![Uppgift om originalversionens språk](translationof.png)  

För översättningar i flera led, använd egenskapen Intermediärt språk till översättningar.  
![Intermediärt språk](intermediate_language.png)  

* Har titel/Titel/Huvudtitel ((hasTitle/Title/mainTitle). Om Primär medverkan finns i posten, exporteras uppgiften till 240 #a. Om Primär medverkan inte finns i posten, exporteras uppgiften till 130 #a.  
Skriv in uppgiften.  

Originaltitel ("Föredragen titel för verket") för en översättning ska du ange här.  
```Exempel: Soldier spy```  

För en titel som börjar med bestämd eller obestämd artikel, ska artikeln fileras bort. Lägg till fileringsvärde och ange en siffra.  

Mer information om översättningar finns på sidan [Språk](https://metadatabyran.kb.se/generella-anvisningar---rda/verk-och-uttryck/egenskaper-som-beskriver-verk-och-uttryck/sprak#h-Oversattning), i Metadatabyrån. Se också [Lathund för ett översatt verk, i Metadatabyrån](https://metadatabyran.kb.se/generella-anvisningar---rda/verk-och-uttryck/lathundar-for-verk-i-libris/lathund-for-ett-oversatt-verk).  

##### Parallelltext  
Se [Lathund för parallelltext, i Metadatabyrån](https://metadatabyran.kb.se/generella-anvisningar---rda/verk-och-uttryck/lathundar-for-verk-i-libris/lathund-for-parallelltext).    

#### Anmärkning om språk    
* Anmärkning/Anmärkning om språk/Benämning  
(hasNote/marc:LanguageNote/label = 546 #a)  
  ```Exempel: Parallelltext på svenska och engelska```  
Anmärkningen finns i vissa mallar och kan läggas till med hjälp av Berikning från mall. Det går inte att lägga till egenskapen från Lägg till egenskaper.

#### Sammanfattningsspråk
* Sammanfattning av innehåll/Sammanfattning/Språk (summary/Summary/language = 041 #b)  
Lägg till Sammanfattning av innehåll. Lägg till Sammanfattning. Ta bort Benämning. Lägg till Språk. Länka till entiteten för sammanfattningens språk.  
  ```Exempel: Engelska```  

### Genre form
Länka till entiteter.  
 För att söka efter entiteter inom Genre/form, klicka på plustecknet vid Genre/form (lägg till entitet). Skriv in sökbegrepp. Vid behov, välj typ. Trunkera genom att trycka på mellanslagstangenten eller med * i sökrutan. Välj entitet genom att klicka på plustecknet vid entiteten (Lägg till). Vid behov, välj ytterligare entiteter i listan.
 
 [Se instruktionsfilm Lägga till Genre/form](https://kbplay.mediaflowportal.com/watch/1123263/)  

Under Genre/form, ange dels termer som motsvarar marc-koder i 008, dels saogf-termer (genre/form-termer enligt Svenska ämnesord).  

![Lägga till genre/form](genre_exempel.png) 

#### Marc-koder i 008
För att länka till genretermer som motsvarar marc-koder i 008, välj rubrik under Föreslagna (eller vid behov välj en annan rubrik längre ner i listan). Trunkera med * för att se listan över typer under varje rubrik. Länka till entitet.  
Läs mer på sidan [Exempel på användning av genre/form, i Metadatabyrån](https://metadatabyran.kb.se/arbetsfloden/tryckta-monografier/verk---tryckta-monografier/exempel-pa-anvandning-av-genre-form)

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
  [Se även Anmärkning om akademisk avhandling nedan](#anmarkning-om-akademisk-avhandling).  

#### Saogf-termer  
* Genre/form – saogf-termer (genreForm = 655 -/7 #a, #2 saogf)  
Sök direkt efter genre/form-termer i sökrutan. Länka till entitet.   
 ```Exempel: Självbiografier```  
 Träfflistan vid sökning på entiteter är för närvarande inte sorterad. Var därför uppmärksam på att det finns liknande genre/form-termer med olika listkoder, till exempel saogf, barngf, gmgpc/swe. Välj kod från rätt lista. För att söka på koder från en specifik lista, lägg till listkoden efter sökordet och mellanslag, t.ex. "tecknade serier saogf". För att söka fram en barngf-term, lägg på motsvarande sätt till koden barngf efter sökordet, t.ex. "bilderböcker barngf".  
[Mer information om listkoder, i Metadatabyrån](https://metadatabyran.kb.se/amnesord-och-genre-form/amnesord-och-genre-form-i-libris).  

### Klassifikation  
**VERSION 1.19:**  
Vissa klassifikationssystem har sedan version 1.19 flyttats till [Instans](https://libris.kb.se/katalogisering/help/workflow-instance).  
Kvar under Verk är DDK, Sekundär DDK-klassifikation, UDK samt klassifikation som beskrivs genom Ingår i system/Konceptsystem. Detta gäller bland annat SAB.  

* DDK-klassifikation  
  För att lägga till DDK-klassifikation:  
  * Om posten har Klassifikation/Klassifikation (till exempel SAB-klassifikation) men saknar Klassifikation/DDK-klassifikation, lägg till ytterligare en förekomst av Klassifikation (plustecknet vid Klassifikation - lägg till klassifikation). Välj Skapa lokal entitet och välj DDK-klassifikation. Skriv in uppgiften under Kod.  
  * Om posten helt saknar Klassifikation, lägg till Klassifikation genom att klicka på plustecknet till höger om "Instans av" och verkstypen. Välj Klassifikation. Klicka på plustecknet vid Klassifikation (Lägg till klassifikation). Välj Skapa lokal entitet och välj DDK-klassifikation.  
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
Lägg till DDK-klassifikation (sekundär) genom att klicka på plustecknet till höger om "Instans av" och verkstypen och välja DDK-klassifikation (sekundär).  
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
  * Om posten helt saknar Klassifikation, lägg till Klassifikation genom att klicka på plustecknet till höger om "Instans av" och verkstypen. Välj Klassifikation. Klicka på plustecknet vid Klassifikation (Lägg till klassifikation). Välj Skapa lokal entitet och välj Klassifikation.  
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

### Ämne  
* [Se hjälptexten Ämnesord i Libris](https://libris.kb.se/katalogisering/help/workflow-general-sh)  

### Målgrupp     
* Målgrupp (intendedAudience = 008/22)  
 Länka till entitet.
 <br/>```Exempel:```
  * ```Barn och ungdom (0-16 år) (008/22: j)```  
  Normalvärde för barn- och ungdomslitteratur.

  * ```Barn (ca 10-12 år)/Läromedel (008/22: c)```  
  Normalvärde för läromedel avsedda för skolbruk (till och med gymnasiet).  

### Målgruppsanmärkning  
* Målgrupp/Målgrupp/Benämning (intendedAudience/IntendedAudience/label = 521 #a)   
  Under Målgrupp, skapa Målgrupp som lokal entitet (klicka i rutan Skapa lokal entitet och välj Målgrupp). Skriv in uppgiften under Benämning.  
  ```Exempel: För årskurs 1```  
  
### Innehållstyp
* Innehållstyp/Innehållstyp (contentType/ContentType = 336 #b)   
  Länka till entitet.
  <br/>```Exempel:```
  * ```kartografisk bild (cri)```
  * ```framförd musik (prm)```
  * ```stillbild (sti)```
  * ```text (txt)```  

[Läs mer om innehållstyp i Metadatabyrån](https://metadatabyran.kb.se/generella-anvisningar---rda/verk-och-uttryck/egenskaper-som-beskriver-verk-och-uttryck/innehallstyp).

För att lägga till ytterligare innehållstyp, till exempel "sti" = stillbild för en bilderbok med både text och bild, länka till ytterligare en entitet. Välj Innehållstyp i listan (i stället för "Föreslagna typer").    
I äldre poster har ytterligare innehållstyp lagts i Har del/Verk. Dessa behöver inte ändras.   

### Anmärkning om akademisk avhandling    
* Anmärkning/Anmärkning om akademisk avhandling/Benämning (dissertation/Dissertation/label = 502 #a)  
  Lägg till Anmärkning om akademisk avhandling. Skapa lokal entitet.  
Skriv in anmärkningen under Benämning.    
  ```Exempel: Diss. Umeå : Umeå universitet, 2018```
