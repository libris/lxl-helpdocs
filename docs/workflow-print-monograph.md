---
section: Arbetsflöden katalogisering
title: Tryckt monografi
order: 16
date: 2018-10-25
tags:
- under arbete
- tryckt monografi
- bok
--- 

## Tryckt monografi - bok

Denna hjälptext beskriver ett antal vanligt förekommande fält, med utgångspunkt från exempel. För instruktioner om att länka till entitet, skapa lokal entitet och om hur formuläret fungerar i övrigt, se Redigering i vänstermenyn. För information om katalogregler, skrivregler och övriga katalogiseringsanvisningar, se [Anvisningar för katalogisering - RDA](http://www.kb.se/rdakatalogisering/Anvisningar/Arbetsfloden/Tryckta-monografier/ "Anvisningar för katalogisering - RDA").

Se även [instruktionsfilmer](https://www.youtube.com/playlist?list=PLZVkEICvA5-GRT2oJQmLgq_2Pksx6zYPy)  

I de flesta fall ska informationen delas upp i olika fält och delfält. I några undantagsfall är det nödvändigt att använda ISBD-interpunktion inom fält, för att separera uppgifter. Dessa fall visas genom exempel nedan. I övriga fall, lägg inte in ISBD-interpunktion för att avsluta ett fält. Använd vid behov klamrar inom fält, enligt Anvisningar för katalogisering - RDA.

I vissa fall fungerar det ännu inte fullt ut att lägga till alla uppgifter som beskrivs i denna hjälptext. Arbete pågår med förbättra gränssnittet. För att anmäla fel, använd detta formulär för [felrapportering](https://docs.google.com/forms/d/e/1FAIpQLSfOChJOGDoHUQguSF83F5XyTZiQL-yU47nvcqb6qwNT9GX7Aw/viewform). För att lämna synpunkter, använd detta formulär för  [ändringsförslag](https://docs.google.com/forms/d/e/1FAIpQLScgz_0enebhBn6uB8xvowkDBB4ax_dbvaobLSFfqFMoty6eQg/viewform).  


### Innehåll  

| [Adminmetadata](#adminmetadata) | [Instans](#instans) | [Verk](#verk) | 
| ------ | ----------- |  ----------- |
| [Skapad av](#skapad-av) | [Utgivningssätt](#utgivningssatt) | [Verkets titel](#verkets-titel) |
| [Uppgraderad av](#uppgraderad-av) | [Titel](#titel) | [Språk](#sprak) |
| [Katalogiserande instans](#katalogiserande-instans) | [Upphovsuppgift](#upphovsuppgift) | [Medverkan och funktion](#medverkan-och-funktion) |
| [Poststatus](#poststatus) | [Identifikator](#identifikator) | [Klassifikation](#klassifikation) |
| [Systemnummer](#systemnummer) | [Upplageuppgift](#upplageuppgift) | [Ämne](#amne) |
| [Katalogiseringsspråk](#katalogiseringssprak) | [Utgivning](#utgivning) | [Genre](#genre) |
| [Katalogiseringsregler](#katalogiseringsregler) | [Tillverkning](#tillverkning) | [Innehållstyp](#innehallstyp) |
| [Beskrivningsnivå](#beskrivningsniva) | [Copyrightår](#copyrightar) | [Anmärkning om akademisk avhandling](#anmarkning-om-akademisk-avhandling) |
| [Bibliografikod](#bibliografikod) | [Omfång](#omfang) | |
| [Systemteknisk anmärkning](#systemteknisk-anmarkning) | [Illustrationer](#illustrationer) | |
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
  
#### Uppgraderad av  
* Uppgraderad eller importerad av/Bibliotek/Sigel (descriptionUpgrader/Library/sigel = 040 ‡d)  
  Om beskrivningsnivån uppgraderas, lägg till denna uppgift. Vid postimport, lägg till uppgiften. Lägg inte till uppgiften när posten endast ändras utan att beskrivningsnivån uppgraderas.  
  
  Lägg till Uppgraderad eller importerad av (plustecknet Lägg till fält under: Post). Klicka på plustecknet vid Uppgraderad eller importerad av (Lägg till agent). Välj Skapa lokal entitet (längst ner i sidorutan). Välj Bibliotek.  
  Lägg till Sigel (plustecknet Lägg till fält under: Bibliotek). Skriv in uppgiften.     
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
  
  Lägg till Bibliografi (plustecknet Lägg till fält under: Post). Klicka på Lägg till bibliotek (plustecknet vid Bibliografi), välj därefter Skapa lokal entitet (längst ner i sidorutan). Lägg till Sigel (plustecknet Lägg till fält under Bibliotek).  
  Skriv in uppgiften.
 <br/>```Exempel:```
  * ```NB```
  * ```SAMB```  
  För att lägga in flera sigler, använd gärna Duplicera entitet och skriv in nästa sigel i den duplicerade entiteten.   
  
#### Systemnummer 
* Identifikator/Lokal identifikator/Värde (identifiedBy/SystemNumber/value = 035 ‡a)  
  Om ett systemnummer finns i förhandspost, till exempel Bokinfos systemnummer, låt det vara kvar oförändrat.  
  ```Exempel: (BOKR)9789188107213```  
  För att lägga till ett lokalt systemnummer, till exempel ett DIVA-urn som systemnummer, lägg till Identifikator (plustecknet Lägg till fält under: Post, i Adminmetadata). Välj typ Systemnummer, under Lokal identifikator. Lägg till Värde (plustecknet vid Lokal identifikator). Fyll i aktuellt systemnummer.  
  ```Exempel: (DIVA)urn:nbn:se:su:diva-83163```  
För ISBN, se [Identifikator](#identifikator) under Instans.
  
#### Katalogiseringssprak
* Katalogiseringsspråk (descriptionLanguage = 040 ‡b)  
  Länka till entitet.  
  ```Exempel: svenska (swe)```
  
#### Katalogiseringsregler  
* Katalogiseringsregler (descriptionConventions = 040 ‡e)  
  Lägg till Katalogiseringsregler (plustecknet Lägg till fält under: Post). Lägg till entitet (plustecknet vid Katalogiseringsregler - lägg till entitet). Välj "Regler för deskriptiv katalogisering (bib)" i listan. För en post katalogiserad enligt RDA, sök fram och länka till entitet: "i" (= marc/Isbd). När man skapar ny post från mall visas entiteten som "marc/Isbd". I en sparad post visas samma entitet som "ISBD-interpunktion finns * i". Båda är rätt.      
  Skapa också lokal entitet under Katalogiseringsregler. Klicka på plustecknet vid Katalogiseringsregler (Lägg till entitet). Välj Skapa lokal entitet (längst ner i sidorutan). Välj Regler för deskriptiv katalogisering (bib). Lägg till Kod (plustecknet vid Regler för deskriptiv katalogisering (bib). Skriv in "rda".    
  ```Exempel: marc/Isbd (länkad entitet) + lokal entitet, Kod: rda```
  
#### Beskrivningsniva  
* Beskrivningsnivå (000/17)  
I samband med att du uppgraderar en Bokinfopost eller annan post med beskrivningsnivå: CIP-post eller Preliminär nivå, ändra beskrivningsnivå till annan nivå, annars kan ändringar skrivas över.  
  Välj från lista.    
  ```Exempel: Biblioteksnivå```
  
#### Poststatus     
* Poststatus (000/05)  
  Uppdateras automatiskt. Ändra inte.
  <br/>```Exempel:```
  * ```Ny post```
  * ```Rättad eller reviderad post```
 
#### Systemteknisk anmarkning
* Systemteknisk anmärkning/Benämning (599)  
I samband med att du uppgraderar en Bokinfopost eller annan post med beskrivningsnivå: CIP-post eller Preliminär nivå, ändra beskrivningsnivå till annan nivå, annars kan ändringar skrivas över. Ta därefter bort systemteknisk anmärkning med innehåll: "Maskinellt genererad post. Ändra kod för fullständighetsnivå (leader/17), annars kommer manuellt gjorda ändringar att försvinna."  
 
Följande anmärkningar är under arbete och fungerar ännu inte fullt ut:  
 * Katalogisatörens anmärkning  
 * Anmärkning om katalogiseringskälla  
 

### Instans
#### Utgivningssatt
* Utgivningssätt (issuanceType)  
  Välj från lista.  
  ```Exempel: Monografisk resurs```
  
#### Titel  

##### Huvudtitel    
* Har titel/Titel/Huvudtitel (hasTitle/Title/mainTitle = 245 ‡a)  
  Återge huvudtiteln från titelsidan eller annan föredragen källa så som den förekommer i källan. se [Anvisningar för katalogisering - RDA](http://www.kb.se/rdakatalogisering/Anvisningar/Arbetsfloden/Tryckta-monografier/#huvudtitel "Anvisningar för katalogisering - RDA").  
  Skriv in uppgiften.    
 ```Exempel: En arbetsdag i skriftsamhället```  
    För en titel som börjar med bestämd eller obestämd artikel, ska artikeln fileras bort. Ange fileringsvärde genom att lägga till fileringsvärde (plustecknet vid Titel - Lägg till fält under: Titel) och ange en siffra.  
 ```Exempel: Huvudtitel: En arbetsdag i skriftsamhället, fileringsvärde: 3```  
 Se exempel i formathandboken för Libris/Voyager: 
[Fileringsindikator]( http://www.kb.se/katalogisering/Formathandboken/Fileringsindikator/)

##### Övrig titelinformation (undertitel)
* Har titel/Titel/Övrig titelinformation (= Undertitel) (hasTitle/Title/subtitle = 245 ‡b)  
  Skriv in uppgiften. Om det finns flera undertitlar, skriv in dessa efter varandra i samma fält, åtskilda av mellanslag, kolon, mellanslag.    
```Exempel: ett etnografiskt perspektiv på skriftanvändning i vanliga yrken : småskrift utarbetad av Språkrådet```
  
  För att ange originaltitel, se Verk/Har titel/Titel/Huvudtitel.  

##### Varianttitel   
  Används till exempel för felaktigheter. Kan specificeras med Typanmärkning.  
  Lägg till Har titel och välj typ Varianttitel. Lägg därefter till Huvudtitel och eventuell Övrig titelinformation (plustecknet vid Varianttitel - lägg till fält under: Varianttitel). Lägg vid behov till Typanmärkning.  
* Har titel/Varianttitel/Typanmärkning (hasTitle/VariantTitle/typeNote = 246 1/_ ‡i)  
 Anmärkningstext som i ett sökgränssnitt ska föregå varianttiteln. Används också för att ange typ av varianttitel som inte finns i listan, t ex Titelrubrik. Lägg vid behov till Typanmärkning (plustecknet vid Varianttitel - lägg till fält under: Varianttitel, välj Typanmärkning).  
  Skriv in uppgiften.  
  ```Exempel: Titeln felstavad, korrekt titel:```   
* Har titel/Varianttitel/Huvudtitel (hasTitle/VariantTitle/mainTitle = 246 ‡a)  
Lägg till Huvudtitel (plustecknet vid Varianttitel - lägg till fält under: Varianttitel, välj Huvudtitel).   
  Skriv in uppgiften.  
  ```Exempel: Hierarchy in organizations```   
* Har titel/Varianttitel/Övrig titelinformation (= Undertitel) (hasTitle/VariantTitle/subtitle = 246 ‡b)  
Lägg till Övrig titelinformation (plustecknet vid Varianttitel - lägg till fält under: Varianttitel, välj Övrig titelinformation). Om det finns flera undertitlar, skriv in dessa efter varandra i samma fält, åtskilda av mellanslag, kolon, mellanslag.  
  Skriv in uppgiften.  
  
##### Omslagstitel, Ryggtitel, Rubriktitel  
* Omslagstitel, Ryggtitel, Rubriktitel etc - lägg till Har titel och välj typ, till exempel Omslagstitel. Lägg därefter till Huvudtitel, eventuell Övrig titelinformation och Typanmärkning, enligt mönstret för Omslagstitel, se nedan.      

##### Omslagstitel   
* Har titel/Omslagstitel/Huvudtitel (hasTitle/CoverTitle/mainTitle = 246 1/4 ‡a)  
Lägg till Huvudtitel (plustecknet vid Omslagstitel - lägg till fält under: Omslagstitel, välj Huvudtitel).   
 Skriv in uppgiften.    
 ```Exempel: Bergens väktare```  
* Har titel/Omslagstitel/Övrig titelinformation (= Undertitel) (hasTitle/CoverTitle/subtitle = 246 1/4 ‡b)  
Återge övrig titelinformation som återfinns i annan källa än huvudtiteln som en varianttitel, till exempel som omslagstitel.    
Lägg till Övrig titelinformation (plustecknet vid Omslagstitel - lägg till fält under: Omslagstitel, välj Övrig titelinformation).      
  Skriv in uppgiften. Om det finns flera undertitlar, skriv in dessa efter varandra i samma fält, åtskilda av mellanslag, kolon, mellanslag.    
```Exempel: Djingis Khan – historiens störste erövrare```

  För att ange att omslagstiteln endast står på skyddsomslag, lägg till Typanmärkning (= 246 ‡i). Lägg därefter till Huvudtitel och eventuell Övrig titelinformation.  
  Skriv in uppgifterna.
  <br/>```Exempel:```
  * ```Typanmärkning (246 ‡i): Skyddsomslag:```
  * ```Omslagstitel/Huvudtitel (246 ‡a): På väg mot döden```
  * ```Övrig titelinformation (246 ‡b): en Cooper och Fry-deckare```  
    
##### Delbeteckning
* Har titel/Titel/Har del/Titeldel/Delbeteckning (hasTitle/Title/hasPart/TitlePart/partNumber = 245 ‡n)  
Lägg till Har del (hasPart) under Har titel/Titel (plustecknet vid Titel - lägg till fält under: Titel). Välj Har del. Lägg till Titeldel (TitlePart) som lokal entitet (plustecknet vid Har del - Lägg till resurs). Välj Skapa lokal entitet (längst ner i sidorutan). Skriv "titeldel" i rutan Skapa lokal entitet. Välj * Titeldel. Titeldel läggs till under Har del. Klicka på Titeldel och det fälls ut. 
Om Har del/Titeldel/Deltitel redan finns, lägg till Delbeteckning under Titeldel (plustecknet vid Titeldel - Lägg till fält under: Titeldel, välj Delbeteckning (partNumber)).   
Skriv in uppgiften under Delbeteckning.  
```Exempel: 1```   

##### Deltitel  
* Har titel/Titel/Har del/Titeldel/Deltitel (hasTitle/Title/hasPart/TitlePart/partName = 245 ‡p)  
Lägg till Har del (hasPart) under Har titel/Titel (plustecknet vid Titel - Lägg till fält under: Titel). Välj Har del. Lägg till Titeldel (TitlePart) som lokal entitet (plustecknet vid Har del - Lägg till resurs). Välj Skapa lokal entitet (längst ner i sidorutan). Skriv "titeldel" i rutan Skapa lokal entitet. Välj * Titeldel. Titeldel läggs till under Har del. Klicka på Titeldel och det fälls ut. 
Om Har del/Titeldel/Delbeteckning redan finns, lägg till Deltitel under Titeldel (plustecknet vid Titeldel - Lägg till fält under: Titeldel, välj Deltitel (partName)).   
Skriv in uppgiften under Deltitel.  
```Exempel: Träd och växter som resurs```  
För att ange Delbeteckning och Deltitel i en annan ordning, till exempel en deltitel som har efterföljande delbeteckningar, upprepa Titeldel och ange Delbeteckning och Deltitel som det passar i det aktuella fallet.  

#### Titel - alternativ stavning
* Relation/Relation/Entitet/Verk/Har titel/Titel/Huvudtitel (relationship/Relationship/entity/Work/hasTitle/Title/mainTitle = 740)  
Ange alternativa titlar här för att öka sökbarheten för titlar som innehåller exempelvis specialtecken, siffror eller oväntade stavningar av ord.  
  
##### Parallelltitel  
Ange parallelltitel här. Upprepa inte parallelltitel efter Har titel/Titel/Huvudtitel (245 ‡a) med interpunktion.   
* Har titel/Parallelltitel/Huvudtitel (hasTitle/ParallelTitle/mainTitle = 246 1/1 ‡a)   
Välj först Har titel, välj sedan typ Parallelltitel. Välj Huvudtitel.    
Skriv in uppgiften.   
  ```Exempel: The Great Northern War explained```  
* Har titel/Parallelltitel/Övrig titelinformation (hasTitle/ParallelTitle/subTitle = 246 1/1 ‡b)   
Vid behov, klicka även på plustecknet vid Parallelltitel och lägg till Övrig titelinformation (subtitle).  
  ```Exempel: Charles XII and the ideological address```  
  
#### Upphovsuppgift
* Upphovsuppgift (responsibilityStatement = 245 ‡c)  
  Skriv in uppgiften.  
  ```Exempel: Tom Marcus ; översättning: Svante Skoglund```

#### Identifikator 
* Identifikator/Typ (identifiedBy)  
  Välj från lista.  
  ```Exempel: ISBN```
* Identifikator/ISBN/Värde (identifiedBy/Isbn/value = 020 ‡a)  
  Skriv in uppgiften.  
  ```Exempel: 9789188107213```
* Identifikator/Särskiljande tillägg (= Bestämning) (identifiedBy/qualifier = 020 ‡q)  
  Skriv in uppgiften.  
  ```Exempel: inbunden```
* Identifikator/Ogiltigt värde (identifiedBy/marc:hiddenValue = 020 ‡z)  
  Skriv in uppgiften.  
  ```Exempel: 97891881072```
  
#### Upplageuppgift
* Upplageuppgift (editionStatement = 250 ‡a)  
  Skriv in upplagebeteckning här.  
  ```Exempel: Första upplagan```  
  
#### Utgivning  
* Utgivning (publication)  
  Välj typ från lista. För monografier, använd Primär utgivning.  
  I konverterade och maskininlästa poster finns det ibland två avsnitt: ett Primär utgivning med År och Land, och ett Utgivning med Plats, Agent och Datum. När man redigerar maskininlästa poster med två utgivningsavsnitt får man, om man bedömer det nödvändigt, flytta uppgifterna om Plats, Agent och Datum till avsnittet Primär utgivning och ta bort avsnittet Utgivning.   
NB inväntar en maskinell ändring av dessa poster och ändrar inte manuellt.    
 
 ##### Utgivningsplats
 * Plats/Plats/Benämning (= Utgivningsort) (place/label = 264 -/1 ‡a)  
  För att lägga till Plats, klicka på Lägg till fält under Primär utgvning och välj Plats. Sök inte efter Plats som entitet utan välj istället Skapa lokal entitet, typ Plats. Lägg till Benämning.   
  Skriv in uppgiften. Klamra vid behov. Plats ska inte länkas som entitet.  
  ```Exempel: [Göteborg]```  
 ##### Utgivarnamn
  * Agent/Agent//Benämning (= Utgivarnamn) (agent/label = 264 -/1 ‡b)  
  För att lägga till Agent, klicka på Lägg till fält under Primär utgivning och välj Agent. Sök inte efter Agent som entitet utan välj istället Skapa lokal entitet, typ Agent. Lägg till Benämning.     
  Skriv in uppgiften. Klamra vid behov. Utgivarnamn ska inte länkas som entitet.  
  ```Exempel: NoNa```   
  Om flera utgivare ska anges, lägg till "Har del" (hasPart) under Primär utgivning. Lägg därefter till Utgivning som lokal entitet (klicka på plustecknet vid Har del och klicka sedan på Skapa lokal entitet, längst ner i sidorutan). Välj Utgivning i listan). Använd År och vid behov Datum enligt anvisningar nedan. Upprepa Utgivning som lokal entitet under Har del för nästa utgivare.
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
  Använd Startår och Slutår. Fälten ska ligga i avsnittet Primär utgivning. Om årtalen anges utan klammer eller andra tecken utöver fyra positioner, räcker det att ange årtalen här. De exporteras då både som 008 och 264 ‡c. Bindestreck sätts automatiskt. För att få rätt kod i 008/06 (Typ av utgivningsdatum/Utgivningsstatus) vid MARC-export: lägg till Typ av utgivningsdatum (marc:publicationStatus) (klicka på plustecknet vid Primär utgivning) och välj ”Flera årtal (monografisk resurs)".
 <br/>```Exempel:```
 * ```Startår: 1999```
 * ```Slutår: 2017```
 * ```Typ av utgivningsdatum: Flera årtal (monografisk resurs)``` 

 Läs mer om [År och Datum](https://kundo.se/org/librisxl/d/falt-for-utgivningsar/)  
##### Utgivningsland  
 * Land (country = 008/15-17)  
  Länka till entitet.  
  ```Exempel: Sverige (sw)```  
  * Plats/Plats/Benämning (= Utgivningsort) (place/label = 264 -/1 ‡a)  
  För att lägga till Plats, klicka på Lägg till fält under Primär utgvning och välj Plats. Sök inte efter Plats som entitet utan välj istället Skapa lokal entitet, typ Plats. Lägg till Benämning.   
  Skriv in uppgiften. Klamra vid behov. Plats ska inte länkas som entitet.  
  ```Exempel: [Göteborg]```  
  
#### Tillverkning 
* Tillverkning (manufacture)  
* Plats/Plats/Benämning (place/label = 264 -/3 ‡a)  
  ```Exempel: Falun```  
* Agent/Agent/Benämning (agent/label = 264 -/3 ‡b)  
  Skriv in uppgiften.   
  ```Exempel: Scandbook```        
* Datum (= Tillverkningstid) (date = 264 -/3 ‡c)  
  Skriv in uppgiften. Klamra vid behov.
  <br/>```Exempel:```
  * ```2017```
  * ```[2017]```
  
#### Copyrightar   
* Copyright/Copyright/Datum (copyright/Copyright/date = 264 -/4 ‡c)  
  Skriv in uppgiften. För att få fram copyrighttecknet, kopiera från exemplet nedan eller skriv Alt + 184.  
  Se också [Specialtecken](https://libris-dev.kb.se/katalogisering/help/search-04-special-chars). Du kan t ex söka på teckenuppsättning i “Sök i windows” och öppna programmet, markera och kopiera tecknet och sedan klistra in det.  
  ```Exempel: ©2017``` 
   
#### Omfang   
* Omfång/Omfång/Benämning (extent/Extent/label = 300 ‡a)  
  Skriv in uppgiften.  
  ```Exempel: 319 sidor```  
  
#### Illustrationer    
* Övriga fysiska detaljer (other physical details = 300 ‡b)  
  Skriv in uppgiften.  
  ```Exempel: illustrationer```

#### Matt 
* Mått/Mått/Benämning (hasDimensions/Dimensions/label = 300 ‡c)  
  Skriv in uppgiften.  
  ```Exempel: 24 cm``` 
  
#### Bilagor
* Tillsammans med/Instans/Benämning (Bilagor) (accompaniedBy/Instance/label = 300 ‡e)  
  Under Instans, lägg till Tillsammans med. Skapa därefter Instans som lokal entitet (plustecknet vid Tillsammans med, välj Skapa lokal entitet, längst ner i sidorutan). Väj Instans i listan. Lägg till Benämning.  
Skriv in uppgiften.  
  ```Exempel: 10 mönsterark```  

#### Medietyp
* Medietyp (mediaType/Mediatype = 337 ‡b)  
  Länka till entitet.  
  ```Exempel: n (= omedierad)```
  
#### Barartyp
* Bärartyp (carrierType/CarrierType = 338 ‡b)  
  Länka till entitet.  
  ```Exempel: nc (= volym)```  

#### Seriemedlemskap
* Seriemedlemskap/Seriemedlemskap/Ingår i serie (seriesMembership/SeriesMembership/inSeries)  
  Avvakta med att skapa verk som länkade entiteter. Beskriv serien som lokal entitet, enligt följande instruktion.  
  *Nytt 2018-10-04:*   
  * Man måste inte längre fylla i två Seriemedlemskap för att vid export till MARC få ut både 490 och 830.  
  * Vid export till marc21 skapas både 490 och 830 (800/810) från Seriemedlemskap som saknar Serieuppgift (t ex gamla 440-fält). OBS. Hanteringen klarar de flesta fall bra, men det finns serier med deltitlar/delserier som kommer att exporteras fel (fel ordning mellan Delbeteckning och Deltitel, fel interpunktion). Om man stöter på sådana, och anser felet besvärande, får man gå in i posten och lägga till en korrekt Serieuppgift i rätt Seriemedlemskap. Då kommer 490 att skapas från det. (Finns det flera Seriemedlemskap behöver man komplettera alla, annars skapas bara 490 för den serien som har en ifylld Serieuppgift).  
  * Import: matchning av 490 + 830 (800/810) vid import via tratten och vid manuell import från Andra källor. Om fälten matchar läggs båda fältens data i samma Seriemedlemskap. Annars skapas ett Seriemedlemskap per fält. OBS. Behöver kontrolleras vid katalogisering:  
ISSN (dubbleras om det finns på båda fälten),  
volymbeteckning (dubbleras om det inte står exakt likadant)  
Läs mer om [Seriemedlemskap](https://kundo.se/org/librisxl/d/uppgifter-om-seriemedlemskap-saknas-i-marc-export/)  
     
##### Seriens titel (auktoriserad sökingång för serie)  
* Seriemedlemskap/Ingår i serie/Instans av Verk/Verk/Har titel/Titel/Huvudtitel (seriesMembership/inSeries/InstanceofWork/Work/hasTitle/Title/mainTitle = 830 ‡a)  
  Ange den auktoriserade sökingången för serien här (gäller serier som har seriehuvudpost) i de fall den avviker från serieuppgiften. Om endast Serieuppgift men inte Ingår i serie/Instans av Verk/Verk finns, t ex i en förhandspost från Bokinfo, fungerar det för närvarande bäst att skapa ett helt nytt seriemedlemskap och flytta över Serieuppgift dit. Ange sedan den auktoriserade sökingången för serien under Seriemedlemskap/Ingår i serie/Instans av Verk/Verk/Har titel/Titel/Huvudtitel. Ta bort det första seriemedlemskapet så att endast ett seriemedlemskap återstår.  
  Skriv in uppgiften.   
  ```Exempel: Årstasällskapets för Fredrika Bremer-studier skriftserie```  
##### ISSN  
* Seriemedlemskap/Ingår i serie/Instans/Identifikator/ISSN/Värde (seriesMembership/inSeries/Instance/identifiedBy/ISSN/Value) (490 ‡x, 830 ‡x)  
  Skriv in uppgiften.  
  ```Exempel: 1103-498X```     
##### Serieuppgift  
* Seriemedlemskap/Serieuppgift (seriesMembership/seriesStatement = 490 ‡a)  
  Skriv in uppgiften.  
   ```Exempel: Årstasällskapets skriftserie```   
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
 
##### Författarserie
* Seriemedlemskap/Ingår i serie/Instans/Instans av Verk/Verk/Har titel/Titel/Huvudtitel  
(seriesMembership/inSeries/Instance/InstanceOf/Work/hasTitle/Title/mainTitle = 800 ‡t)  
  ```Exempel: Millenium```   
* Seriemedlemskap/Ingår i serie/Instans/Instans av Verk/Verk/Medverkan och funktion/Primär medverkan/Agent/Person     (seriesMembership/inSeries/Instance/InstanceOf/Work/contribution/PrimaryContribution/Agent/Person = 800 ‡a)  
Lägg till Medverkan och funktion under Verk (inom Seriemedlemskap) genom att klicka på plustecknet vid Verk (Lägg till fält under: Verk). Välj Medverkan och funktion. Välj Primär medverkan. Lägg till Agent (plustecknet vid Primär medverkan - Lägg till fält under: Primär medverkan). Länka till entitet. Börja alltid med att söka efter om agenten redan finns. Vid behov, skapa ny entitet för agent (se Skapa ny agent i hjälpsektionen). I undantagsfall, skapa lokal entitet.    
 ```Exempel: Larsson, Stieg, 1954-2004```  
* Seriemedlemskap/Numrering inom serie (seriesMembership/seriesEnumeration = 800 ‡v)  
  Skriv in uppgiften.  
  ```Exempel: 1```  
  
#### Anmarkning
* Anmärkning/Anmärkning/Benämning (hasNote/Note/label = 500 ‡a)   
  Skriv in allmänna anmärkningar här.    
  Skriv in uppgiften.  
   
#### Innehallsanmarkning  
* Har innehållsförteckning/Innehållsförteckning/Benämning (tableofContents = 505 8/_)  
  För en enkel innehållsanmärkning (505 ‡a), lägg till Har innehållsförteckning (från Lägg till fält under: Instans). Lägg därefter till Innehållsförteckning (plustecknet under Har innehållsförteckning i vänstermenyn). Lägg till Benämning (klicka på plustecknet vid Lägg till fält under: Innehållsförteckning). Skriv in uppgiften.   
  ```Exempel: Culture at home -- Culture and the global -- Global youth -- Global music -- Territories of global globalization.```  
  
* Har innehållsförteckning/Innehållsförteckning/Har del/Utökad innehållsanmärkning/Benämning/Upphovsuppgift (tableofContents = 505 8/0 ‡t, ‡r)  
För en utökad innehållsanmärkning med titlar och upphovsuppgifter, lägg till Har innehållsförteckning (från Lägg till fält under: Instans). Klicka på plustecknet under Har innehållsförteckning i vänstermenyn (Lägg till innehållsförteckning). Lägg till Har del (plustecknet vid Innehållsförteckning - Lägg till fält under: Innehållsförteckning). Skriv Har del i sökrutan och välj det. Klicka på plustecknet vid Har del (Lägg till resurs) och välj Skapa lokal entitet (längst ner i sidorutan). Skriv Utökad innehållsanmärkning i rutan för Skapa lokal entitet och välj * Utökad innehållsanmärkning. Utökad innehållsanmärkning läggs till under Har del. Klicka på Utökad innehållsanmärkning och det fälls ut. Lägg in titel under Benämning. Lägg in upphovsuppgift under Upphovsuppgift.  
Upprepa, för ytterligare titel (Benämning) + upphovsuppgift, genom att lägga till ytterligare en Utökad innehållsanmärkning som lokal entitet (klicka på Duplicera entitet).

#### Malgruppsanmarkning
* Målgrupp/Målgrupp/Benämning (intendedAudience/IntendedAudience/label = 521 ‡a)   
  Skriv in uppgiften.    
  ```Exempel: För årskurs 1```  
Observera att kodning av målgrupp, motsvarande 008/22, ska registreras under Instans av Verk/Genre.  
  
#### Titel - alternativ stavning
* Relation/Relation/Entitet/Verk/Har titel/Titel/Huvudtitel   
(relationship/Relationship/entity/Work/hasTitle/Title/mainTitle = 740)  
Ange alternativa titlar här för att öka sökbarheten för titlar som innehåller exempelvis specialtecken, siffror eller oväntade stavningar av ord.  

#### Annat bararformat
* Annat bärarformat (otherPhysicalFormat = 776)  
  För att länka till en utgåva i annat format, till exempel en elektronisk utgåva, lägg till Annat bärarformat (Lägg till fält, välj Annat bärarformat). Sök upp och länka till instansen. Klicka på plustecknet vid Annat bärarformat (Lägg till instans). I sidorutan under Lägg till entitet/Instans, skriv in id eller annat sökbegrepp. Välj instansen genom att klicka på plustecknet vid instansen eller på instansens titel. Om instansen som länken går till har identifikator (ISBN), skapas i marcexporten 776 #t (Titel) och #z (Identifikator). I webbsök ger detta en länk i högermenyn under rubriken Sök vidare/Andra versioner.   
  
  Om andra delfält i 776 önskas, skapa istället Instans som lokal entitet och lägg till önskade delfält. 
Om särskild anmärkningstext önskas, som ersätter frasen "Andra versioner", skapa Instans som lokal entitet och lägg till Typanmärkning (= (776 ‡i) samt Har titel/Titel och Identifikator/ISBN/Värde. Beskriven av/Post/Kontrollnummer, motsvarande delfält w, är för närvarande låst för redigering. Det går därmed inte att lägga till fältet eller redigera det i befintliga beskrivningar. 


### Verk   

#### Instans av Verk/Text  
* Instans av Verk/Text (instanceOf/Work/Text)  
  Skapa verket som lokal entitet (bryt inte ut verket till en länkbar entitet). Vi rekommenderar att tills vidare skapa verket som lokal entitet. Vi återkommer med anvisningar för att skapa verk som länkbara entiteter. Denna hjälptext beskriver exempel på verk som lokal entitet. Det betyder att du anger de uppgifter som listas här nedan, under Instans av Verk, utan att klicka på länksymbolen (Länka entitet) vid Instans av Verk/Text.  
Läs mer om [Verk och Instans](https://librisbloggen.kb.se/2018/05/30/verk-och-instans-i-startversionen/).  

#### Verkets titel
 
Ange den föredragna titeln för verket här, vid behov. Följ [Anvisningar för katalogisering - RDA](http://www.kb.se/rdakatalogisering/Anvisningar/Allmanna-anvisningar/Sokingangar-for-verk-och-uttryck "Anvisningar för katalogisering - RDA").  
För översättningar och för verk som har givits ut under olika titlar på samma språk eller när samma titel har använts för olika verk, ska den föredragna titeln för verket anges.    

##### Verkets titel
* Har titel/Titel/Huvudtitel (hasTitle/Title/mainTitle = 240 1/0 ‡a)  
  "Originaltitel" för ett verk med primär medverkande anger du här.  
  Skriv in uppgiften.  
  ```Exempel: Soldier spy```  
  För en titel som börjar med bestämd eller obestämd artikel, ska artikeln fileras bort. Ange fileringsvärde genom att lägga till delfältet fileringsvärde och ange en siffra.  
  ```Exempel: Huvudtitel: En arbetsdag i skriftsamhället, fileringsvärde: 3```  
 
##### Verkets titel - huvuduppslag
*	Uttryck av/Verk/Har titel/Titel/Huvudtitel (expressionOf/Work/hasTitle/Title/mainTitle (= 130 ‡a)  
 "Originaltitel" för ett verk utan primär medverkande anger du här.  
Under Instans av Verk/Text, lägg till Uttryck av (plustecknet vid Instans av Verk/Text - Lägg till fält under: Text, välj Uttryck av).  
Skapa verk som lokal entitet (plustecknet vid Uttryck av - Lägg till verk, välj Skapa lokal entitet, längst ner i sidorutan), Skriv "verk" i rutan Skapa lokal entitet. Klicka på * Verk. Det läggs till under Uttryck av. Klicka på plustecknet vid Verk (Lägg till fält under: Verk) och välj Har titel. Välj Titel. Ta bort Övrig titelinformation.    
Skriv in uppgiften.  
```Exempel: Bibeln```
*	Uttryck av/Verk/Har titel/Titel/Deltitel  
(expressionOf/Work/hasTitle/Title/partName = 130 ‡p)  
Lägg till eventuell deltitel (plustecknet vid Titel - lägg till fält under: Titel, välj Deltitel).  
Skriv in uppgiften.  
```Exempel: Nya testamentet```
*	Uttryck av/Verk/Språk/Språk/Benämning  
(expressionOf/Work/language/Language/label = 130 ‡l)  
Lägg till eventuell benämning på språk som ska ingå i den föredragna titeln. Klicka på plustecknet vid Verk (Lägg till fält under: Verk) och välj Språk. Klicka på plustecknet vid Språk (Lägg till språk) och välj Skapa lokal entitet. Lägg till Benämning (plustecknet vid Språk - Lägg till fält under: Språk, välj Benämning.  
Skriv in uppgiften.  
```Exempel: Svenska```

##### Verkets titel - analytisk sökingång  
För att ange verk som ingår i det beskrivna verket, motsvarande fält 730 0/2 (analytisk sökingång) i marc:  
Under Instans av Verk/Text, klicka på plustecknet vid Verk (lägg till fält under: Verk) och välj Har del. Följ sedan stegen ovan, från ”Skapa verk som lokal entitet”.  

##### Verkets titel - relaterade verk  
För att ange verk som är relaterade, men inte ingår i det beskrivna verket, motsvarande fält 730 0/_ (icke-analytisk sökingång) i marc:   
Under Instans av Verk/Text, lägg till Relation genom att klicka på plustecknet vid Instans av Verk/Text (Lägg till fält under: Text) och välja Relation. Välj typ Relation. Lägg till Entitet genom att klicka på plustecknet vid Relation (Lägg till fält under: Relation), välj Entitet. Skapa verk som lokal entitet (plustecknet vid Entitet - Lägg till verk). Följ sedan stegen ovan, från ”Välj Skapa lokal entitet”.  

#### Sprak 
* Språk (language = 008/35-37)  
  Ange det språk som den text du beskriver är skriven på. För en text på svenska, ange svenska. För att ange originalspråk för ett översatt verk, se Originalversion/Verk/Språk.  
  Länka till entitet.  
  ```Exempel: svenska (swe)```  
  För att ange att texten är på flera språk, t ex parallelltext, ange ytterligare en språkkod genom att klicka på plustecknet vid Språk (Lägg till språk) och söka fram ytterligare en entitet för ett språk och länka till den.  
  
##### Översättning  
För en översättning, ange även:  
* Språk/Språk/Benämning (Language/label = 240 ‡l)  
  Lägg till ytterligare en förekomst av Språk, under Språk (klicka på plustecknet vid Språk), skapa lokal entitet (klicka på Skapa lokal entitet längst ner i sidorutan) och lägg till Benämning (klicka på Lägg till fält under: Språk).  
  Skriv in språket i klartext. Denna klartext - verkets (översättningens) språk - visas som ett tillägg till verkets titel i marcpostens 240 ‡l.  
  ```Exempel: Svenska```  

* Anmärkning: Språk (marc:LanguageNote = 041 i1: 1)  
  Ange om resursen är/innehåller en översättning.  
  För att lägga till uppgiften, klicka på plustecknet vid Instans av verk/Text och välj Anmärkning: Språk. Välj fras från lista.  
  ```Exempel: objektet är/innehåller översättning```  
  
* Originalversion/Verk/Språk (originalversion/Work/language = 041 ‡h)  
  Ange det språk som en översatt text är översatt från. För en text som är översatt från engelska till svenska, ange engelska här.   
  Klicka på Lägg till fält under: Text, välj Originalversion, klicka på plustecknet vid Originalversion, välj Skapa lokal entitet (längst ner i sidorutan). Skriv Verk i rutan för Skapa lokal entitet och välj * Verk. Klicka på plustecknet vid Verk (Lägg till fält under: Verk) och välj Språk. Klicka på plustecknet vid Språk. Sök fram språkentiteten och länka.  
  ```Exempel: engelska (eng)```  
  För översättningar i flera led, länka först till det mellanliggande språket och därefter till originalspråket.  
  
###### Texten delvis översatt  
(041 0/- #a + 041 1/- #a #h)  
* Har del/Verk/Språk (hasPart/Work/language) +  
  Anmärkning: Språk: Objektet är/innehåller översättning (marc:languageNote) +  
  Originalversion/Verk/Språk (originalVersion/Work/language)  
  För att ange att texten delvis är översatt, till exempel när en publikation innehåller parallelltext på två språk och den ena texten är en översättning: ange först Språk under Instans av Verk/Text (se Språk ovan). Lägg sedan till Har del under Instans av Verk/Text. Välj Skapa lokal entitet (längst ner i sidorutan). Skriv Verk i rutan för Skapa lokal entitet och välj * Verk. Klicka på plustecknet vid Verk (Lägg till fält under: Verk) och välj Språk. Sök fram och länka till entiteten för språket som texten är översatt till, till exempel engelska. Lägg till Anmärkning: Språk och ange att resursen är/innehåller en översättning. Lägg till Originalversion/Verk/Språk (se ovan under Översättning). Länka till entiteten för språket som resursen delvis är en översättning från.  
  
##### Parallelltext    
* Anmärkning/Anmärkning om språk/Anmärkning: Språk/Benämning (hasNote/marc:LanguageNote/marc:LanguageNote/label = 546 ‡a)  
  ```Exempel: Parallelltext på svenska och engelska```  
  Anmärkningen är under arbete och fungerar tyvärr ännu inte.  
  
 #### Medverkan och funktion  
* Medverkan och funktion  
  Läs mer:  
  [Auktoritetsgruppens rekommendationer](https://kundo.se/org/librisxl/d/kbs-auktoritetsgrupp-informerar-jraz/)   
  [Lägga till Agent - Organisation](https://libris.kb.se/katalogisering/help/workflow-agent-org-instance)  
  
* Medverkan och funktion/Primär medverkan/Agent/Person (contribution/PrimaryContribution/agent/Person = 100 1/- ‡a)  
  Länka till entitet. Börja alltid med att söka efter om agenten redan finns. Vid behov, skapa ny entitet för agent (se Skapa ny agent i hjälpsektionen). I undantagsfall, skapa lokal entitet.   
 ```Exempel: Lindgren, Astrid, 1907-2002```
* Medverkan och funktion/Primär medverkan/Funktion (contribution/PrimaryContribution/role = 100 ‡4)  
  Länka till entitet. Klicka på plustecknet vid Funktion (Lägg till funktion) och sök fram funktionskod. Skriv in kod eller utskriven form i sökrutan eller tryck på mellanslagstangenten för att se alla koder. Välj kod genom att klicka på plustecknet vid koden eller på koden.    
För en sorterad lista på koder, se Formathandboken för Libris/Voyager: [Funktions- och relationskoder](http://www.kb.se/katalogisering/Formathandboken/Funktionskoder/)  
  ```Exempel: relator/author (= Författare)```
  
* Medverkan och funktion/Medverkan/Agent/Person (contribution/agent/Person = 700 1/- ‡a)  
  Länka till entitet. Börja alltid med att söka efter om agenten redan finns. Vid behov, skapa ny entitet för agent (se Skapa ny agent i hjälpsektionen). I undantagsfall, skapa lokal entitet.   
  ```Exempel: Skoglund, Svante, 1960-```  
* Medverkan och funktion/Medverkan/Funktion (contribution/role = 700 ‡4)  
  Länka till entitet. Klicka på plustecknet vid Funktion (Lägg till funktion) och sök fram funktionskod. Skriv in kod eller utskriven form i sökrutan eller tryck på mellanslagstangenten för att se alla koder. Välj kod genom att klicka på plustecknet vid koden eller på koden.    
För en sorterad lista på koder, se Formathandboken för Libris/Voyager: [Funktions- och relationskoder](http://www.kb.se/katalogisering/Formathandboken/Funktionskoder/)    
  ```Exempel: relator/trl (= översättare)```  
  
#### Klassifikation 
* DDK-klassifikation  
  För att lägga till DDK-klassifikation:  
  * Om posten har Klassifikation/Klassifikation (till exempel SAB-klassifikation) men saknar Klassifikation/DDK-klassifikation, lägg till ytterligare en förekomst av Klassifikation (plustecknet vid Klassifikation - lägg till fält under: KLassifikation). Välj Skapa lokal entitet (längst ner i sidorutan) och välj DDK-klassifikation. Skriv in uppgiften under Kod.  
  * Om posten helt saknar Klassifikation, lägg till Klassifikation genom att klicka på den runda fält-knappen i verktygsmenyn (Lägg till fält under: Instans). Välj Klassifikation. Klicka på plustecknet under Klassifikation (Lägg till Klassifikation). Välj Skapa lokal entitet (längst ner i sidorutan) och välj DDK-klassifikation.  
   Skriv in uppgiften under Kod.  

* Klassifikation/DDK-klassifikation/Kod (classification/ClassificationDdc/code = 082 0/4 ‡a)  
  Skriv in uppgiften.  
  ```Exempel: 327.12092```
* Klassifikation/DDK-klassifikation/Klassifikationsupplaga  
  (classification/ClassificationDdc/edition = 082 ‡2)  
  ```full```  
*  Parallell upplagebeteckning/Upplagespecifik upphovsuppgift  
 (classification/ClassificationDdc/editionEnumeration = 082 ‡2)  
   ```Exempel: 23/swe```  
  
##### Sekundär DDK-klassifikation  
Lägg till DDK-klassifikation (sekundär) genom att klicka på plusikonen vid Instans av Verk/Text (Lägg till fält under: Text) och välja DDK-klassifikation (sekundär).  
Klicka sedan på plustecknet vid DDK-klassifikation (sekundär) (Lägg till ddk-klassifikation) och välj Skapa lokal entitet (längst ner i sidorutan). Skriv in uppgiften under Kod.  
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
  * Om posten har Klassifikation/DDK-klassifikation men saknar Klassifikation/Klassifikation (till exempel SAB-klassifikation), lägg till ytterligare en förekomst av Klassifikation (plustecknet vid Klassifikation - lägg till fält under: KLassifikation). Välj Skapa lokal entitet (längst ner i sidorutan) och välj Klassifikation. Skriv in uppgiften under Kod.  
  * Om posten helt saknar Klassifikation, lägg till Klassifikation genom att klicka på den runda fält-knappen i verktygsmenyn (Lägg till fält under: Instans). Välj Klassifikation. Klicka på plustecknet under Klassifikation (Lägg till fält under: Klassifikation). Välj Skapa lokal entitet (längst ner i sidorutan) och välj Klassifikation.  
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
  [Okontrollerat ämnesord](https://libris.kb.se/katalogisering/help/workflow-uncontrolled)

##### Allmänt ämnesord  
* Ämne - sao-term  (subject = 650 -/7 ‡a, ‡2 sao)  
  Länka till entitet.  
  ```Exempel: Säkerhetspolitik```

##### Allmänt ämnesord med underindelning   
* Ämne/Sammansatt term/Termkomponenter/Allmänt ämnesord  
 (subject/ComplexSubject/termComponentList = 650 -/7 ‡a)      
  Skapa Sammansatt term som lokal entitet. Lägg till Termkomponenter. Sök fram och länka till entiteten för det allmänna ämnesordet.     
  ```Exempel: Varumärken```    
* Ämne/Sammansatt term/Termkomponenter/Underindelning för allmänt ämnesord  
 (subject/ComplexSubject/termComponentList = 650 ‡x)   
  Sök fram och länka till entiteten för underindelningen.    
  ```Exempel: juridik och lagstiftning```   
* Ämne/Sammansatt term/Termlista (subject/ComplexSubject/inScheme = ‡2 sao)   
  Lägg till Termlista. Sök fram och länka till entiteten "sao".    
  ```Exempel: sao```   
  
##### Geografiska ämnesord  
* Geografiskt ämnesord (subject = 651 -/4 ‡a)  
  Sök fram och länka till entitet.  
  I undantagsfall, skapa lokal entitet (längst ner i sidorutan) och skriv in uppgiften.  
  ```Exempel: Sverige```
  
##### Geografiskt ämnesord med geografisk underindelning  
* Ämne/Sammansatt term/Föredragen benämning (subject/ComplexSubject/prefLabel = 651 -/7 ‡a, ‡z)   
  Skapa Sammansatt term som lokal entitet (längst ner i sidorutan). Lägg till Föredragen benämning.  
  Skriv in uppgiften, med interpunktion.  
  ```Exempel: Tyskland -- Bonn```  
* Ämne/Sammansatt term/Föredragen benämning/Termlista (subject/ComplexSubject/prefLabel/inScheme = ‡2 sao)    
   Lägg till Termlista. Sök fram och länka till entiteten "sao".      
  ```Exempel: sao```  
* Ämne/Sammansatt term/Termkomponenter/Geografiskt ämnesord/Föredragen benämning  
  (subject/ComplexSubject/termComponentList/Geographic/prefLabel)  
  Lägg till Termkomponenter. Skapa Geografiskt ämnesord som lokal entitet (längst ner i sidorutan). Lägg till Föredragen benämning.  
  Skriv in uppgiften.  
  ```Exempel: Tyskland```  
  Skapa Geografiskt ämnesord som lokal entitet igen. Lägg till Föredragen benämning.
  Skriv in uppgiften.  
   ```Exempel: Bonn``` 
   
##### Kronologiskt ämnesord
* Ämne/Kronologiskt ämnesord (subject = 648 7/- ‡a, ‡2 sao)  
Länka till entitet. Om du inte får träff vid sökning på entiteter, pröva att söka på första ledet i ett sammansatt ord, t ex "1800" istället för "1800-talet".   
 ```Exempel: 1800-talet```  
  
##### Ämnesord Person  
* Ämne/Agent/Person (subject = 600 1/4- ‡a)      
Länka till entitet. Börja alltid med att söka efter om agenten redan finns. Vid behov, skapa ny entitet för agent (se Skapa ny agent i hjälpsektionen). I undantagsfall, skapa lokal entitet (längst ner i sidorutan).  
```Exempel: Lindgren, Astrid, 1907-2002```  
Läs [Auktoritetsgruppens rekommendationer](https://kundo.se/org/librisxl/d/kbs-auktoritetsgrupp-informerar-jraz/)  
 
##### Ämnesord Organisation  
* Ämne/Agent/Organisation (subject/agent/Organization = 610 2/- ‡a)  
Länka till entitet. Börja alltid med att söka efter om agenten redan finns. Vid behov, skapa ny entitet för agent (se Skapa ny agent i hjälpsektionen). I undantagsfall, skapa lokal entitet (längst ner i sidorutan).    
```Exempel: Svenska Röda korset```  
Läs mer:  
  [Auktoritetsgruppens rekommendationer](https://kundo.se/org/librisxl/d/kbs-auktoritetsgrupp-informerar-jraz/)   
  [Lägga till Agent - Organisation](https://libris.kb.se/katalogisering/help/workflow-agent-org-instance)  
    
#### Genre 
##### Saogf-termer  
* Genre/form – saogf-termer (genreForm = 655 -/7 ‡a, ‡2 saogf)  
  Länka till entitet.  
  För att söka efter entiteter inom saogf-termer, välj Genre/form i listan över typer, under Genre/form. Trunkera genom att trycka på mellanslagstangenten eller med * i sökrutan. Välj rätt entitet genom att klicka på plustecknet vid entiteten eller på entiteten.    
 ```Exempel: Självbiografier```  
  Se [instruktionsfilm](https://www.youtube.com/watch?v=wrqs310Nt0M&list=PLZVkEICvA5-GRT2oJQmLgq_2Pksx6zYPy&index=7)  

##### Litterär genre  
* Genre/form – litterär genre (genreForm = 008/33)  
  Länka till entitet.  
  För att söka efter entiteter inom Litterär genre, välj Litterär genre i listan över typer, under Genre/form. Trunkera genom att trycka på mellanslagstangenten eller med * i sökrutan. Välj rätt entitet genom att klicka på plustecknet vid entiteten eller på entiteten.   
  ```Exempel: 0 ( = ej skönlitterärt verk)```
  
##### Biografiskt material  
* Genre/form – biografiskt material (genreForm = 008/34)  
  Länka till entitet.  
  För att söka efter entiteter inom Biografiskt material, välj Biografiskt material i listan över typer, under Genre/form. Trunkera genom att trycka på mellanslagstangenten eller med * i sökrutan. Välj rätt entitet genom att klicka på plustecknet vid entiteten eller på entiteten.     
  ```Exempel: a (= självbiografi)```  
    
 ##### Festskrift     
* Genre/form – festskrift (genreForm = 008/30)  
  Länka till entitet.  
  För att söka efter entiteter inom Festskrift, välj Festskrift i listan över typer, under Genre/form. Trunkera genom att trycka på mellanslagstangenten eller med * i sökrutan. Välj rätt entitet genom att klicka på plustecknet vid entiteten eller på entiteten.    
  ```Exempel: Ja, resursen är en festskrift```    
    
 ##### Konferenspublikation       
* Genre/form – konferenspublikation (genreForm = 008/29)  
  Länka till entitet.  
  För att söka efter entiteter inom Konferenspublikation, välj Konferenspublikation i listan över typer, under Genre/form. Trunkera genom att trycka på mellanslagstangenten eller med * i sökrutan. Välj rätt entitet genom att klicka på plustecknet vid entiteten eller på entiteten.      
  ```Exempel: Ja, resursen härrör från konferens```   
     
##### Akademisk avhandling      
* Genre/form – akademisk avhandling (genreForm = 008/24-27)  
  Länka till entitet. För att söka efter entiteten Akademisk avhandling, välj Innehåll 1, Innehåll 3, Innehåll 2, i listan över typer, under Genre/form.  Skriv "avhandling" i sökrutan. Välj rätt entitet genom att klicka på plustecknet vid entiteten eller på entiteten.    
  ```Exempel: Akademisk avhandling```     
 
##### Målgrupp     
 * Målgrupp (intendedAudience = 008/22)  
  Länka till entitet.  
  Trunkera genom att trycka på mellanslagstangenten eller med * i sökrutan. Välj rätt entitet genom att klicka på plustecknet vid entiteten eller på entiteten.    
  ```Exempel: j (= barn- och ungdom, 0-16 år)```  
  
#### Innehallstyp
* Innehållstyp/Innehållstyp (contentType/ContentType = 336 ‡b)  
  Ange de innehållstyp/er som är tillämplig/a på den huvudsakliga delen av resursen. Ange inte för medföljande material av uppenbart underordnad karaktär. Om resursen består av flera likvärdiga delar (kombinerat material), ange innehållstyp/er för alla delarna.  
  Länka till entitet.  
  ```Exempel: text (txt)```  
  För att lägga till ytterligare innehållstyp, till exempel "sti" = stillbild för en bilderbok med både text och bild, lägg till Har del under Instans av Verk, från plustecknet vid Text (Lägg till fält under: Text). Skapa därefter Verk som lokal entitet genom att klicka på plustecknet vid Har del (Lägg till resurs). Välj Skapa lokal entitet och välj därefter ++ Verk i listan. Lägg därefter till Innehållstyp från plustecknet vid Verk (Lägg till fält under: Verk). Sök fram och länka till entitet.
  
#### Anmarkning om akademisk avhandling    
* Anmärkning/Anmärkning om akademisk avhandling/Benämning (dissertation/Dissertation/label = 502 ‡a)  
  Lägg till anmärkning om akademisk avhandling (plustecknet vid Instans av Verk: Text - Lägg till fält under: Text, välj Anmärkning om akademisk avhandling. Klicka på plustecknet vid Anmärkning om akademisk avhandling och välj Skapa lokal entitet (längst ner i sidorutan). Klicka på plustecknet vid den lokala entiteten Anmärkning om akademisk avhandling och lägg till Benämning. Skriv in anmärkningen.  
  ```Exempel: Diss. Umeå : Umeå universitet, 2018```  
