---
section: Materialtyper
title: Musiktryck
order: 49
date: 2020-02-25
tags:
- under arbete
- musiktryck
--- 

# Musiktryck
Denna hjälptext ger kortfattade instruktioner för de vanligaste egenskaperna för musiktryck. För utförliga instruktioner, se de generella hjälptexterna för Adminmetadata, Instans och Verk, se nedan.

## Innehåll

[Inledning](#inledning)

| [Adminmetadata](#adminmetadata) | [Instans](#instans) | [Verk](#verk) | 
| ----------- |  ----------- | ----------- | 
|  [Generell hjälptext för Adminmetadata](https://libris.kb.se/katalogisering/help/workflow-adminmetadata) | [Generell hjälptext för Instans](https://libris.kb.se/katalogisering/help/workflow-instance) | [Generell hjälptext för Verk](https://libris.kb.se/katalogisering/help/workflow-work) |
| | [Identifikator](#identifikator)  | [Byta verkstyp](#byta-verkstyp) |
| | [Utgivningssätt](#utgivningssatt) | [Verkets titel](#verkets-titel) |
| | [Medietyp](#medietyp) | [Medverkan och funktion](#medverkan-och-funktion) |
| | [Bärartyp](#barartyp) | [Språk](#sprak) |
| | [Titel](#titel) | [Genre/form](#genre-form) |
| | [Upphovsuppgift](#upphovsuppgift) | [Klassifikation](#klassifikation) |
| | [Upplageuppgift](#upplageuppgift) | [Ämne](#amne) |
| | [Utgivning](#utgivning) |  [Notationssystem och språk](#notationssystem-och-sprak) |
| | [Tillverkning](#tillverkning) | [Målgrupp](#malgrupp) |
| | [Copyrightår](#copyrightar) | [Innehållstyp](#innehallstyp) | 
| | [Identifikator](#identifikator) | [Har del](#har-del) |  
| | [Omfång](#omfang) | |
| | [Övriga fysiska detaljer](#ovriga-fysiska-detaljer) | | 
| | [Mått](#matt) | |
| | [Speltid](#speltid) | |
| | [Medföljande material](#medfoljande-material) | |  
| | [Seriemedlemskap](#seriemedlemskap) | |
| | [Anmärkning](#anmarkning) | |
| | [Format för noterad musik](#format-for-noterad-musik) | |
| | [Innehållsförteckning](#innehallsforteckning) | |
| | [Målgruppsanmärkning](#malgruppsanmarkning) | |
| | [Annat bärarformat](#annat-bararformat) | | 

## Inledning

Beskrivningen av ett musiktryck innehåller följande tre delar:  
* [Adminmetadata](https://libris.kb.se/katalogisering/help/workflow-adminmetadata) - administrativa data om instansbeskrivningen, såsom kontrollnummer och beskrivningsnivå
* [Instans](https://libris.kb.se/katalogisering/help/workflow-instance) - instans kan också kallas utgåva eller manifestation. Exempel på egenskaper under Instans är utgivningsplats, utgivare och utgivningsår, bärartyp, omfång.
* [Verk](https://libris.kb.se/katalogisering/help/workflow-work) – återger egenskaper för det abstrakta verket såsom medverkan och funktion (t.ex. författare), ämne, klassifikation, språk och innehållstyp. Verksbeskrivningen ligger under rubriken Instans av verk.

Många av egenskaperna finns redan i mallen Noterad musik, andra kan behöva läggas till. För instruktioner om att lägga till eller ta bort egenskaper, länka till entitet, skapa lokal entitet och om hur formuläret fungerar i övrigt, se Redigering i vänstermenyn. För en förhandspost, använd gärna Berika från mall och välj Noterad musik.  

För information om katalogregler, skrivregler och övriga katalogiseringsanvisningar, [se Anvisningar för katalogisering - RDA](http://www.kb.se/rdakatalogisering/ "Anvisningar för katalogisering - RDA") och [RDA Toolkit](https://access.rdatoolkit.org/).

I de flesta fall ska informationen delas upp i olika egenskaper (jfr fält) och underliggande egenskaper (jfr delfält). I några undantagsfall är det nödvändigt att använda ISBD-interpunktion inom en egenskap, för att separera uppgifter. Dessa fall visas genom exempel nedan. I övriga fall, lägg INTE in ISBD-interpunktion för att avsluta en egenskap (fält). Använd vid behov klamrar inom egenskap (fält), enligt Anvisningar för katalogisering - RDA.

[Se även instruktionsfilmer på KB:s Youtubekanal](https://www.youtube.com/playlist?list=PLZVkEICvA5-GRT2oJQmLgq_2Pksx6zYPy)  

## Instans  
För att lägga till egenskaper under Instans, klicka på plustecknet i redigeringsvyn (den stora runda plusikonen under Verktygsikonen) - Lägg till egenskaper under: Instans. Sök fram egenskapen och välj den genom att klicka på plustecknet vid egenskapens namn.  


### Identifikator 
* Identifikator (identifiedBy)  
  Välj typ från lista.  
  ```Exempel: ISBN```
* Identifikator/ISBN/Värde (identifiedBy/Isbn/value = 020 #a)  
  Skriv in uppgiften.  
  ```Exempel: 9789188107213```
* Identifikator/Särskiljande tillägg (= Bestämning) (identifiedBy/qualifier = 020 #q)  
  Skriv in uppgiften.  
  ```Exempel: inbunden```  

För ogiltiga ISBN, använd Indirekt identifierad av, direkt under Instans. Använd inte Ogiltigt värde under Identifikator/ISBN (identifiedBy/marc:hiddenValue).  
  
* Identifikator/ISMN/Värde (identifiedBy/ISMN/value = 024 2 _ #a)  
  Skriv in uppgiften.  
  ```Exempel: 9790006466641```  
* Identifikator/Plåtnummer/Värde (identifiedBy/MusicPlate/value = 028 2 1 #a)  
  Skriv in uppgiften.  
  ```Exempel: N.M.S. 1090```
* Identifikator/Editionsnummer  
* Värde (identifiedBy/MusicPublisherNumber/value = 028 3 1 #a)  
  Skriv in uppgiften.  
  ```Exempel: HN 6027```  
* Agent/organisation/namn (identifiedBy/MusicPublisherNumber/agent/Organization/name = 028 3 1 #b)  
  Skriv in förlagets namn, om det anges i omedelbar anslutning till editionsnumret.  
  ```Exempel: Henle```

### Indirekt identifierad av  
Ange ogiltiga ISBN här och inte under Identifikator/ISBN/Ogiltigt värde.  
Lägg till genom att klicka på Lägg till egenskaper under: Instans, sök upp "Indirekt identifierad av" och klicka på termen.

* Indirekt identifierad av/ISBN (indirectlyIdentifiedBy/ISBN = 020 #z)  
  Välj typ från lista.  
  ```Exempel: ISBN```  
* Indirekt identifierad av/ISBN/Värde (indirectlyIdentifiedBy/Isbn/value = 020 #a)    
  Skriv in uppgiften.  
  ```Exempel: 97891881072```  
* Indirekt identifierad av/Särskiljande tillägg (= Bestämning) (indirectlyIdentifiedBy/qualifier = 020 #q)   
  Skriv in uppgiften.  
  ```Exempel: inbunden``` 

### Utgivningssatt
* Utgivningssätt (issuanceType)  
  Välj från lista.  
  ```Exempel: Monografisk resurs```
  
### Medietyp
* Medietyp (mediaType/Mediatype = 337 #b)  
  Länka till entitet.  
  ```Exempel: n (= omedierad)```  
  
### Barartyp
* Bärartyp (carrierType/CarrierType = 338 #b)  
  Välj Bärartyp i listan över typer. Länka till entitet.  
  ```Exempel: nc (= volym)```  
  
### Titel  

#### Huvudtitel    
* Har titel/Titel/Huvudtitel (hasTitle/Title/mainTitle = 245 #a)   
  För att lägga till Har titel, klicka på plustecknet Lägg till egenskaper under: Instans.
  Återge huvudtiteln från titelsidan eller annan föredragen källa så som den förekommer i källan. [Se Anvisningar för katalogisering - RDA](http://www.kb.se/rdakatalogisering/Anvisningar/Arbetsfloden/Tryckta-monografier/#huvudtitel "Anvisningar för katalogisering - RDA").  
  Skriv in uppgiften.
  <br/>```Exempel:```
  * ```Lichtbogen```
  * ```Quartett Nr. 2 op. 92 für 2 Violinen, Viola und Violoncello```  
  För en titel som börjar med bestämd eller obestämd artikel, ska artikeln fileras bort. Ange fileringsvärde genom att lägga till fileringsvärde (plustecknet vid Titel - Lägg till egenskaper under: Titel) och ange en siffra.  
  ```Exempel: Huvudtitel: The best of Heavy metal, fileringsvärde: 4```  
  [Se exempel i formathandboken för Libris/Voyager - Fileringsindikator](http://www.kb.se/katalogisering/Formathandboken/Fileringsindikator/)

#### Övrig titelinformation (undertitel)
* Har titel/Titel/Övrig titelinformation (= Undertitel) (hasTitle/Title/subtitle = 245 #b)  
  Skriv in uppgiften. 
  <br/>```Exempel:```
  * ```for nine musicians and live electronics```
  * ```auf kabardinische Themen```  
  
  Om det finns flera undertitlar, skriv in dessa efter varandra i samma fält, åtskilda av mellanslag, kolon, mellanslag.  
    ```Exempel: fler progglåtar : guldkorn från 70-talet```
  
För att ange föredragen titel (=uniform titel), se Verk/Har titel/Titel/Huvudtitel.  

För Varianttitel och andra titelvarianter, [se hjälptexten för Instans](https://libris.kb.se/katalogisering/help/workflow-instance#titel): Varianttitel
  
### Upphovsuppgift
* Upphovsuppgift (responsibilityStatement = 245 #c)  
  För att lägga till upphovsuppgift, klicka på plustecknet Lägg till egenskaper under: Instans.  
  Vid postimport: i vissa importerade poster saknas upphovsuppgift. Lägg till det om relevant.   
  Skriv in uppgiften.
  <br/>```Exempel:```
  * ```Kaija Saariaho```
  * ```Sergej Prokofjew```
  * ```Ludwig van Beethoven ; herausgegeben von Rainer Cadenbach```
  
### Upplageuppgift  
* Upplageuppgift (editionStatement = 250 #a)  
  Skriv in upplagebeteckning här. Om de förekommer i källan ange även uppgifter om musikalietyp (partitur, klaverutdrag) och sättning (låg/hög röst) här.
  <br/>```Exempel:```
  * ```New edition```
  * ```Urtext```
  * ```Voix élevée```
  * ```Vocal score```    
  
* Påföljande upplageuppgift (editionStatementRemainder = 250 #b)  
  Skriv in uppgifter som följer omedelbart efter upplagebeteckningen här.  
  ```Exempel: prepared by Imogen Holst & Colin Matthews```  

### Utgivning  
* Utgivning (publication)  
   Välj typ från lista. För monografisk resurs, använd Primär utgivning.     
   I konverterade och maskininlästa poster finns det ibland två avsnitt: ett Primär utgivning med År och Land, och ett Utgivning med Plats, Agent och Datum. När man redigerar maskininlästa poster med två utgivningsavsnitt får man, om man bedömer det nödvändigt, flytta uppgifterna om Plats, Agent och Datum till avsnittet Primär utgivning och ta bort avsnittet Utgivning.   
   En maskinell ändring av dessa poster kommer att ske på sikt.  
   Vid postimport: I importerade poster förekommer ibland både År och Copyrightår inom Utgivning (= 008/06: t, 008/07-10: År och 008/11-14: Copyrightår). Låt uppgiften ligga kvar oförändrad. Om posten är katalogiserad enligt RDA kan även Copyright/Copyright/Datum (copyright/Copyright/date = 264 -/4 #c) finnas med.  
 
#### Utgivningsplats  
* Plats/Plats/Benämning (= Utgivningsort) (place/label = 264 -/1 #a)  
    Sök inte efter Plats som entitet. I rutan Skapa lokal entitet, längst ner i sidorutan till höger, skriv Plats och välj det.   
    Skriv in uppgiften under Benämning. Klamra vid behov.  
    ```Exempel: [Wiesbaden]```  
    
#### Utgivningsland  
* Land (country = 008/15-17)  
  Länka till entitet.  
  ```Exempel: Sverige (sw)``` 
  
#### Utgivarnamn  
* Agent/Agent/Benämning (= Utgivarnamn) (agent/label = 264 -/1 #b)  
    Sök inte efter Agent som entitet. Skapa Agent som lokal entitet.       
    Skriv in uppgiften under Benämning.  
    ```Exempel: Breitkopf & Härtel```   
    Om flera utgivare ska anges, lägg till Har del (hasPart) under Primär utgivning. Skapa Utgivning som lokal entitet (plustecknet vid Har del - Lägg till entitet). I rutan Skapa lokal entitet, längst ner i sidorutan till höger, skriv Utgivning och välj *** Utgivning. Upprepa Utgivning som lokal entitet genom att duplicera entiteten Utgivning.  
    Ange Plats/Plats/Benämning och Agent/Agent/Benämning och vid behov Datum inom respektive utgivningsavsnitt (angående Datum, se anvisningar nedan). Samtliga utgivare med Plats och Agent ska ligga inom Har del/Utgivning.  
    Land, År och eventuellt Datum ska ligga inom Primär utgivning.  
    [Se exempelpost i Libris katalogisering](https://libris.kb.se/katalogisering/w4rp4hlwtr5lctjr#it).
  
#### År och datum 
* År (= Utgivningstid) (date = 008/07-10, 264 -/1 #c)  
    År får endast innehålla siffror (0-9) och bokstaven u. År ska endast förekomma inom Primär utgivning.  
    Utgivningsår anges här, utan klamrar eller andra tecken - endast fyra positioner. Det kommer då att exporteras till både marcpostens 08/07-10 och 264 -/1 #c (till 264 förutsatt att inte Datum är angivet). 
<br/>```Exempel: 2017```  

  Observera att År måste finnas med i beskrivningen, även om datum finns med.</br>
  
  För att ange årtal med klamrar eller andra tecken utöver fyra positioner, använd Datum.

* Datum (= Utgivningstid) (date = 264 -/1 #c)  
  Datum får innehålla text och interpunktionstecken.  
  Utgivningsdatum med fler än fyra positioner, till exempel ett klamrat årtal, anges här. Det kommer att exporteras till marcpostens 264 -/1 #c.
  <br/>```Exempel:```
   * ```[2017]```
   * ```[mellan 1863 och 1866?]```  
  
  För att ange ett år utan klamrar eller andra tecken, använd År.  
  
* Flera år (flerbandsverk)  
  Använd Startår och Slutår (inte År). För att lägga till Startår och Slutår, klicka på plustecknet vid Primär utgivning (Lägg till egenskaper under: Primär utgivning) och välj Startår respektive Slutår. Egenskaperna ska ligga i avsnittet Primär utgivning. Om årtalen anges utan klammer eller andra tecken utöver fyra positioner, räcker det att ange årtalen här. De exporteras då både som 008 och 264 #c. Bindestreck sätts automatiskt. För att få rätt kod i 008/06 (Typ av utgivningsdatum/Utgivningsstatus) vid MARC-export: lägg till Typ av utgivningsdatum (marc:publicationStatus) (klicka på plustecknet vid Primär utgivning) och välj ”Flera årtal (monografisk resurs)".
    <br/>```Exempel:```
    * ```Startår: 1753```
    * ```Slutår: 1756```
    * ```Datum: [1732?]-1756```
    * ```Typ av utgivningsdatum: Flera årtal (monografisk resurs)``` 

 [Läs mer om År och Datum i inlägg på Supportforum för nya Libris](https://kundo.se/org/librisxl/d/falt-for-utgivningsar/)  

### Tillverkning 
* Tillverkning (manufacture)  

#### Tillverkningsplats (Tillverkningsort) 
* Plats/Plats/Benämning (place/label = 264 -/3 #a)  
     Skriv in uppgiften.  
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
  
### Copyrightar   
* Copyright/Copyright/Datum (copyright/Copyright/date = 264 -/4 #c)  
  För musiktryck anges alltid copyrightår om det skiljer sig från utgivningstid (om de sammanfaller anges endast utgivningsår). Ange endast senaste copyrightåret.  
  För att få fram copyrighttecknet, kopiera från exemplet nedan eller skriv Alt + 184. Se också [Specialtecken](https://libris.kb.se/katalogisering/help/search-04-special-chars). Du kan t ex söka på teckenuppsättning i “Sök i windows” och öppna programmet, markera och kopiera tecknet och sedan klistra in det.  
    Skriv in uppgiften.  
    ```Exempel: ©2017```   

### Omfang   
* Omfång/Omfång/Benämning (extent/Extent/label = 300 #a)  
  Skriv in uppgiften under Benämning.
  <br/>```Exempel:```
   * ```112 sidor```
   * ```1 partitur (ix, 43 sidor)```
   * ```1 klaverutdrag (18 sidor) + 2 stämmor```
    
### Ovriga fysiska detaljer
* Övriga fysiska detaljer (other physical details = 300 #b)  
  Skriv in uppgiften.  
  ```Exempel: faksimil```  

### Matt 
* Mått/Mått/Benämning (hasDimensions/Dimensions/label = 300 #c)  
  Skriv in uppgiften under Benämning.  
  ```Exempel: 24 cm``` 

### Speltid
* Speltid/speltid/Värde (hasDuration/Duration/Value = 306 #a)</br>
  Vid behov anges speltid här i kodad form.
  Skriv in uppgiften under Värde enligt formen TTMMSS.</br>
  Om sekunder inte är kända ange 00.</br>
  ```Exempel: 011200```
  
### Medfoljande material
* Medföljs av/Instans/Benämning (Bilagor) (accompaniedBy/Instance/label = 300 #e)</br>
  Här anges medföljande material, som t ex bilagor. Lägg till Medföljs av. Skapa Instans som lokal entitet (skriv Instans i rutan Skapa   lokal entitet och välj ** Instans.) Lägg till Benämning.</br>
  Skriv in uppgiften.    
  ```Exempel: 1 CD```  

### Seriemedlemskap
* Seriemedlemskap/Seriemedlemskap/Ingår i serie (seriesMembership/SeriesMembership/inSeries)   
  Avvakta med att skapa verk som länkade entiteter. Beskriv serien som lokal entitet, enligt följande instruktion.  
  *Nytt 2018-10-04:*   
  * Man måste inte längre fylla i två Seriemedlemskap för att vid export till MARC få ut både 490 och 830.  
  * Vid export till marc21 skapas både 490 och 830 (800/810) från Seriemedlemskap som saknar Serieuppgift (t ex gamla 440-fält). OBS! Hanteringen klarar de flesta fall bra, men det finns serier med deltitlar/delserier som kommer att exporteras fel (fel ordning mellan Delbeteckning och Deltitel, fel interpunktion). Om man stöter på sådana, och anser felet besvärande, får man gå in i posten och lägga till en korrekt Serieuppgift i rätt Seriemedlemskap. Då kommer 490 att skapas från det. (Finns det flera Seriemedlemskap behöver man komplettera alla, annars skapas bara 490 för den serien som har en ifylld Serieuppgift).  

[Läs mer om Seriemedlemskap i inlägg på Supportforum för nya Libris](https://kundo.se/org/librisxl/d/uppgifter-om-seriemedlemskap-saknas-i-marc-export/)  
     
#### Seriens titel (auktoriserad sökingång för serie)  
* Seriemedlemskap/Ingår i serie/Instans av Verk/Verk/Har titel/Titel/Huvudtitel (seriesMembership/inSeries/InstanceofWork/Work/hasTitle/Title/mainTitle = 830 #a)  
  Ange den auktoriserade sökingången för serien här (gäller serier som har seriehuvudpost) i de fall den avviker från serieuppgiften. Om endast Serieuppgift men inte Ingår i serie/Instans av Verk/Verk finns, t ex i en förhandspost från Bokinfo, fungerar det för närvarande bäst att skapa ett helt nytt seriemedlemskap och flytta över Serieuppgift dit. Ange sedan den auktoriserade sökingången för serien under Seriemedlemskap/Ingår i serie/Instans av Verk/Verk/Har titel/Titel/Huvudtitel. Ta bort det första seriemedlemskapet så att endast ett seriemedlemskap återstår.  
  Skriv in uppgiften.   
  ```Exempel: Neue Ausgabe sämtlicher Werke. Serie 2, Kammermusik```  
  
#### ISSN  
* Seriemedlemskap/Ingår i serie/Instans/Identifikator/ISSN/Värde (seriesMembership/inSeries/Instance/identifiedBy/ISSN/Value) (490 #x, 830 #x)  
  Ange seriens ISSN. För äldre serier som saknar ISSN, men har ett LibrisIII-nummer ("99-nummer"), ange detta nummer här.  
  Skriv in uppgiften.  
  ```Exempel: 1103-498X```     
  
#### Serieuppgift  
* Seriemedlemskap/Serieuppgift (seriesMembership/seriesStatement = 490 #a)  
  Skriv in uppgiften.  
   ```Exempel: Neue Ausgabe sämtlicher Werke. Serie 2, Kammermusik```
   
#### Numrering inom serie  
* Seriemedlemskap/Numrering inom serie (seriesMembership/seriesEnumeration = 490 #v, 830 #v)  
  Skriv in uppgiften.  
  ```Exempel: 8```  
  
#### Indikator för seriebiuppslag   
* Seriemedlemskap/Indikator för seriebiuppslag (marc:seriesTracingPolicy = 490 i1: 0/1)  
  Ange indikator 0 om endast serieuppgift samt eventuellt ISSN och eventuell numrering inom serie ska anges (om det inte finns en seriehuvudpost).   
  Skriv in uppgiften.  
  ```Exempel: 0```   
  Ange indikator 1 om dessutom Instans/Instans av Verk/Verk (830) anges (om det finns en seriehuvudpost).   
  ```Exempel: 1```   

  *Seriemedlemskap, vid postimport:* 
  Om fält 490 #a och 830 #a matchar, läggs de vid import i samma Seriemedlemskap. Om de inte matchar, skapas två Seriemedlemskap: ett med Seriemedlemskap/Serieuppgift och ett med Seriemedlemskap/Ingår i serie/Instans av Verk/Verk/Har titel/Titel/Huvudtitel.  
  När man redigerar importerade poster med två Seriemedlemskap får man, om man bedömer det nödvändigt, slå ihop dem till ett genom att lägga till Serieuppgift och Indikator för seriebiuppslag i det Seriemedlemskap som innehåller Seriemedlemskap/Ingår i serie/Instans av Verk/Verk/Har titel/Titel/Huvudtitel.  
  Om man försöker göra tvärtom och lägga till Instans av Verk i ett Seriemedlemskap så orsakar en bugg att detta kopplas till Instans av Verk/Noterad musik (överst i beskrivningen) och det går sedan inte att ändra. I dessa fall måste Seriemedlemskapet tas bort i sin helhet och ett nytt läggas till och fyllas i.  
  OBS! Om ISSN finns i både 490 och 830 och om volymbeteckningen är angiven på olika sätt i 490 och 830, dubbleras dessa inom Seriemedlemskapet. Radera en av de dubblerade ISSN- och/eller voIymbeteckningarna.  
  
### Anmarkning
* Anmärkning/Anmärkning/Benämning (hasNote/Note/label = 500 #a)   
  Gör allmänna anmärkningar här.
  <br/>```Exempel:```
   * ```Med realiserad, ej besiffrad, b.c.-stämma```
   * ```Noter med övnings-cd typ ”Music minus one”```
   * ```Speltid: 21 min.```

### Format for noterad musik
* Format för noterad musik/Format för noterad musik/Benämning (musicFormat/MusicFormat/label = 348 #a)   
  Ange musikalietyp [enligt KBSP för RDA 7.20.1.3 Ange musikalietyp](http://access.rdatoolkit.org/kbspchp7_kbsp7-251.html)  
  Partitur anges enligt svensk praxis, dvs. utelämnas för noter för soloinstrument och röst med piano samt för flerstämmig vokalmusik noterad på två notsystem. Om det behövs fler än en term, exempelvis partitur och stämma, skapa flera entiteter.   
  Skriv in uppgiften.
  <br/>```Exempel:```
    * ```partitur```
    * ```stämma```
    * ```klaverutdrag```  
* Format för noterad musik/Källa/Källa/Kod (musicFormat/MusicFormat/source/Source/code = 348 #2)  
  Ange att termen är hämtad från RDA.  
  Skriv in uppgiften.  
  ```Exempel: rda```  

### Innehallsforteckning  
* Har innehållsförteckning/Innehållsförteckning/Benämning (tableofContents = 505 8/_)  
  Musik- och teaterbiblioteket rekommenderar enkel innehållsförteckning för musiktryck.  
  För en enkel innehållsförteckning (505 #a), lägg till Har innehållsförteckning (från Lägg till egenskaper under: Instans). Lägg därefter till Innehållsförteckning (plustecknet under Har innehållsförteckning i vänstermenyn). Skriv in uppgiften under Benämning.
  <br/>```Exempel:```
   * ```Concerto nach italienischem Gusto, BWV 971 ; Ouverture nach französischer Art, BWV 831 ; Appendix: Ouverture in c, BWV 831a```
   * ```Chain of fools / Donald Covay -- A deeper love / David Cole, Robert Clivilles -- Do right woman, do right man / Chips Moman, Dan Penn -- I knew you were waiting (for me) / Dennis Morgan, Simon Climie```

* Har innehållsförteckning/Innehållsförteckning/Har del/Utökad innehållsanmärkning/Benämning, Upphovsuppgift, Kommentar (tableofContents = 505 8/0 #t, #r, #g)    
  För att skapa en utökad innehållsanmärkning med titlar och upphovsuppgifter, [se hjälptexten för Instans](https://libris.kb.se/katalogisering/help/workflow-instance#innehallsforteckning).

### Malgruppsanmarkning
* Målgrupp/Målgrupp/Benämning (intendedAudience/IntendedAudience/label = 521 #a)   
  För att lägga till målgruppsanmärkning, klicka på plustecknet Lägg till egenskaper under: Instans och välj Målgrupp.  
Skapa Målgrupp som lokal entitet (plustecknet vid Målgrupp - Lägg till målgrupp. I rutan Skapa lokal entitet, längst ner i sidorutan till höger, skriv Målgrupp och välj det). Skriv in uppgiften under Benämning.  
  ```Exempel: För årskurs 1```  
Observera att kodning av målgrupp, motsvarande 008/22, ska registreras under Instans av Verk/Genre.  

### Annat bararformat
* Annat bärarformat (otherPhysicalFormat = 776)  
  För att länka till en utgåva i annat format, till exempel en elektronisk utgåva, lägg till Annat bärarformat (Lägg till egenskaper, välj Annat bärarformat). Sök upp och länka till instansen. Klicka på plustecknet vid Annat bärarformat (Lägg till instans). I sidorutan under Lägg till entitet/Instans, skriv in id eller annat sökbegrepp. Välj instansen genom att klicka på plustecknet vid instansen eller på instansens titel. Om instansen som länken går till har identifikator (ISBN), skapas i marcexporten 776 #t (Titel) och #z (Identifikator). I webbsök ger detta en länk i högermenyn under rubriken Sök vidare/Andra versioner.   
  
  Om andra delfält i 776 önskas, skapa istället Instans som lokal entitet och lägg till önskade egenskaper.  
  Om särskild anmärkningstext önskas, som ersätter frasen "Andra versioner", skapa Instans som lokal entitet och lägg till Typanmärkning (= (776 #i) samt Har titel/Titel och Identifikator/ISBN/Värde. Beskriven av/Post/Kontrollnummer, motsvarande delfält w, är för närvarande låst för redigering. Det går därmed inte att lägga till egenskapen eller redigera det i befintliga beskrivningar.  

## Verk   

### Instans av Verk
* Instans av Verk/Noterad musik (instanceOf/Work/NotatedMusic)  
  Skapa verket som lokal entitet (bryt inte ut verket till en länkbar entitet). Denna hjälptext beskriver exempel på verk som lokal entitet. Det betyder att du anger de uppgifter som listas här nedan, under Instans av Verk, utan att klicka på länksymbolen (Länka entitet) vid Instans av Verk/Noterad musik.  
  [Läs mer om Verk och Instans på Libris informationssidor på kb.se](https://www.kb.se/samverkan-och-utveckling/nytt-fran-kb/nyheter-samverkan-och-utveckling/2018-05-30-verk-och-instans-i-startversionen-av-nya-libris.html).  

  För att lägga till egenskaper under Instans av Verk/Noterad musik, klicka på plustecknet vid Instans av Verk/Noterad musik - Lägg till egenskaper under: Noterad musik. Sök fram egenskapen och välj den genom att klicka på plustecknet vid egenskapens namn. 
  
### Byta verkstyp
Ibland finns behov av att ändra verkstyp, t ex från Text till Noterad musik. Det kan gälla förhandsposter från Bokinfo eller andra poster där den katalogiserande instansen har valt en annan verkstyp.  

**Observera:** Ta fram posten i ett nytt fönster i webbläsaren, innan du raderar verkstypen, om du vill kunna kopiera uppgifter från den gamla posten till den nya, eller jämföra posten före och efter. Spara inte posten förrän du är helt klar med byte av verkstyp och postberikning.  

* Steg 1: Kopiera postens ID som finns längst uppe till höger i postens sammanfattning (förutsatt att du senare vill berika posten med metadata från den gamla posten – annars hoppar du över detta steg).  

* Steg 2: För att ändra verkstyp måste du radera den befintliga verkstypen och lägga till en ny. Börja med att ta bort verkstypen, till exempel Text, genom att klicka på papperskorgen till höger om Text (eller annan verkstyp som du vill ändra). Lägg till en ny verkstyp genom att klicka på plustecknet till vänster om Instans av verk. Välj Skapa lokal entitet och välj verkstyp Noterad musik.  

* Steg 3: Välj sedan om du vill berika posten med metadata som fanns i den gamla posten (klicka på Verktyg och välj Berika från post - Från ID och klistra in det ID som du kopierade i Steg 1)  
ELLER  
om du vill berika från mall för att få fram de vanligaste egenskaperna (Klicka på Verktyg och välj Berika från mall och välj typ Noterad musik).  

**Observera:** Om du väljer att berika posten med metadata från den gamla verkstypen behöver du sedan också ändra Innehållstyp.

[Se även hjälptexten Att använda verktyget](https://libris.kb.se/katalogisering/help/use-the-editor).
 
### Verkets titel
Ange den föredragna titeln för verket här, vid behov. [Följ Anvisningar för katalogisering - RDA](http://www.kb.se/rdakatalogisering/Anvisningar/Allmanna-anvisningar/Sokingangar-for-verk-och-uttryck "Anvisningar för katalogisering - RDA"). Pregnanta titlar för musik anges ofilerade enligt svensk musikbibliotekstradition.  

#### Verkets titel - verk med primär medverkande
Föredragen titel för ett verk med primär medverkande ska anges i Har titel/Titel/Huvudtitel .</BR>

* Har titel/Titel/Huvudtitel (hasTitle/Title/mainTitle = 240 1/0 #a)  
  Ange den föredragna titeln för verket här, vid behov. Pregnanta titlar för musik anges ofilerade. Skriv in uppgiften. 
  <br/>```Exempel:```
   * ```La traviata```
   * ```Symfoni```
   * ```Pianomusik```
 
  Använd även Huvudtitel för *hela* den föredragna titeln då ordningen mellan uppgifterna i Har titel, Tonart, Version och språk för översättning blir felaktig i MARC-förhandsgranskningen, eller om den föredragna titeln är svår eller omöjlig att uttrycka med enbart dessa fält.
 <br/>```Exempel:```
    * ```Sonater och partitor, violin, BWV 1001-1006. Partita, nr 1, h-moll```
    * ```Kvartett, stråkar, nr 13, D. 804, op. 29:1, a-moll, "Rosamunde". Entr'acte```
  
* Delbeteckning (hasTitle/Title/mainTitle/partNumber = 240 1/0 #n)  
  Ange numreringar för verket här, vid behov. Skriv in uppgiften.
  <br/>```Exempel:```
   * ```nr 96, Hob. I:96```
   * ```nr 3, op. 90```
  
* Deltitel (hasTitle/Title/mainTitle/partName = 240 1/0 #p)       
  Lägg till eventuell deltitel genom att klicka på plustecknet vid Titel (lägg till fält under: Titel), välj Deltitel.
  Skriv in uppgiften.
  <br/>```Exempel:```
   * ```Di Provenza il mar```
   * ```Allegro```

* Specificering i form av grupptitel (hasTitle/Title/mainTitle/marc:formSubheading = 240 1/0 #k)   
  Grupptitlar, exempelvis ”Pianomusik. Urval”, används då Instansen innehåller flera verk av samma tonsättare. Grupptiteln kompletteras med individuella sökingångar för dessa verk (i Relation/Verk).  
  Lägg till eventuell grupptitel genom att klicka på plustecknet vid Titel (lägg till fält under: Titel), välj Specificering i form av grupptitel. Skriv in uppgiften.
  <br/>```Exempel: Urval```  

* Besättning för framförande (musicMedium = 240 #m)  
  Ange besättning. Skriv in uppgiften.
  <br/>```Exempel:```
   * ```orkester```
   * ```klarinett, piano```
   * ```blandad kör```
      
* Tonart (240 1/0 #r)       
  Ange tonart. Skriv in uppgiften.  
  ```Exempel: fiss-moll```  

* Version (240 1/0 #o)        
  Ange eventuellt arrangemang. Skriv in uppgiften.  
  ```Exempel: arr. röst, piano```  

#### Verkets titel - verk utan primär medverkande
Föredragen titel för ett verk utan primär medverkande ska anges i Uttryck av verk/Verk/Har titel/Huvudtitel .</BR>
*	Uttryck av/Verk/Har titel/Titel/Huvudtitel (expressionOf/Work/hasTitle/Title/mainTitle (= 130 #a)  
Under Instans av Verk, lägg till Uttryck av. Skapa verk som lokal entitet (plustecknet vid Uttryck av - Lägg till verk, välj Skapa lokal entitet, längst ner i sidorutan till höger), välj Verk. Lägg till Har titel. Välj Titel. Skriv in uppgiften under Huvudtitel.   
   ```Exempel: Cancionero de Upsala```  
*	Uttryck av/Verk/Har titel/Titel/Deltitel (expressionOf/Work/hasTitle/Title/partName = 130 #p)  
Lägg till eventuell deltitel (plustecknet vid Titel - lägg till egenskaper under: Titel, välj Deltitel).  
   ```Exempel: Piae cantiones. Ecce novum gaudium```  
*	Uttryck av/Verk/Har titel/Titel/Delbeteckning (expressionOf/Work/hasTitle/Title/partName = 130 #n)  
Lägg till eventuell delbeteckning (plustecknet vid Titel - lägg till egenskaper under: Titel, välj Delbeteckning).
*	Uttryck av/Verk/Språk/Språk/Benämning (expressionOf/Work/language/Language/label = 130 #l)  
Lägg till eventuell benämning på språk som ska ingå i den föredragna titeln. Klicka på plustecknet vid Verk (Lägg till egenskaper under: Verk) och välj Språk. Klicka på plustecknet vid Språk (Lägg till språk) och välj Skapa lokal entitet. Lägg till Benämning (plustecknet vid Språk - Lägg till egenskaper under: Språk, välj Benämning. Ange språket i klartext. Denna klartext - verkets (översättningens) språk - visas som ett tillägg till verkets titel i marcpostens 130 #l.</BR>

### Medverkan och funktion  
* Medverkan och funktion  
  Under Medverkan och funktion, ange relationer till de agenter som medverkar i verket samt funktionskod för respektive agent. Relationer till utgivare (710) anges för närvarande också här.</BR>
  För ytterligare instruktioner om hur man anger relationer till agenter, [se hjälptexten Relationer till Agent](https://libris.kb.se/katalogisering/help/workflow-agent-org-instance).</BR>
  [Se även Auktoritetsgruppens rekommendationer i inlägg på Supportforum för nya Libris](https://kundo.se/org/librisxl/d/kbs-auktoritetsgrupp-informerar-jraz/).  
  
#### Primär medverkan
* Medverkan och funktion/Primär medverkan/Agent/Person (contribution/PrimaryContribution/agent/Person = 100 1/- #a)  
  Länka till entitet. Börja alltid med att söka efter om agenten redan finns. Vid behov, skapa ny entitet för agent (se Skapa ny agent i hjälpsektionen). I undantagsfall, skapa lokal entitet.
  <br/>```Exempel:```
  * ```Maier-Röntgen, Amanda, 1853-1894```
  * ```Binchois, Gilles, ca 1400-1460```
* Medverkan och funktion/Primär medverkan/Funktion (contribution/PrimaryContribution/role = 100 #4)  
  Länka till entitet. Klicka på plustecknet vid Funktion (Lägg till funktion) och sök fram funktionskod. Skriv in kod eller utskriven form i sökrutan eller tryck på mellanslagstangenten för att se alla koder. Välj kod genom att klicka på plustecknet vid koden eller på koden.    
För en sorterad lista på koder, [se Formathandboken för Libris/Voyager - Funktions- och relationskoder](http://www.kb.se/katalogisering/Formathandboken/Funktionskoder/)  
  ```Exempel: relator/composer (= Kompositör, tonsättare, cmp)```  

#### Medverkan
* Medverkan och funktion/Medverkan/Agent/Person (contribution/agent/Person = 700 1/- #a)  
  Länka till entitet. Börja alltid med att söka efter om agenten redan finns. Vid behov, skapa ny entitet för agent (se Skapa ny agent i hjälpsektionen). I undantagsfall, skapa lokal entitet.   
  ```Exempel: Boye, Karin, 1900-1941```  
* Medverkan och funktion/Medverkan/Funktion (contribution/role = 700 #4)  
  Länka till entitet. Klicka på plustecknet vid Funktion (Lägg till funktion) och sök fram funktionskod. Skriv in kod eller utskriven form i sökrutan eller tryck på mellanslagstangenten för att se alla koder. Välj kod genom att klicka på plustecknet vid koden eller på koden.  
  För en sorterad lista på koder, [se Formathandboken för Libris/Voyager - Funktions- och relationskoder](http://www.kb.se/katalogisering/Formathandboken/Funktionskoder/)
  <br/>```Exempel:```
  * ```Sångtext/lyr```
  * ```Redaktör/edt```
  
### Sprak  
* Språk (language = 008/35-37)  
  För instrumentalmusik, ange Icke-språkligt medium (=language/zxx). För texter till musik, ange textens språk. För en text på svenska, ange svenska. För att ange originalspråk för ett översatt verk, se Originalversion/Verk/Språk.  
  Länka till entitet.
  <br/>```Exempel:```
  * ```language/zxx```
  * ```svenska (swe)```

<br/>För att ange att texten är på flera språk, ange ytterligare en språkkod genom att klicka på plustecknet vid Språk (Lägg till språk) och söka fram ytterligare en entitet för ett språk och länka till den.  

#### Översättning  
För en översättning, [se generell beskrivning av Verk](https://libris.kb.se/katalogisering/help/workflow-work#sprak): Språk/Översättning.

### Genre form
Länka till entitet.  
För att söka efter entiteter inom Genre/form, klicka på plustecknet vid Genre/form (lägg till entitet). I Lägg till entitet (längst upp i sidorutan till höger), välj typ i listan över typer. Skriv in sökbegrepp. Trunkera genom att trycka på mellanslagstangenten eller med * i sökrutan. Välj entitet genom att klicka på plustecknet vid entiteten (Lägg till). Vid behov, välj ytterligare entiteter i listan. Om sidorutan är stängd, klicka på plustecknet vid Genre/form (lägg till entitet) för att söka fram och välja fler entiteter.  

#### Saogf-termer  
* Genre/form – saogf-termer (genreForm = 655 -/7 #a, #2 saogf)  
  Här anges såväl besättning som genre/form.  
  Välj Genre/form i listan över typer. Avgränsa till saogf-termer genom att skriva "saogf" efter söktermen. Länka till entitet.  
  Träfflistan vid sökning på entiteter är för närvarande inte sorterad. Var därför uppmärksam på att det finns liknande genre/form-termer med olika listkoder, till exempel sao, barngf, gmgpc/swe. Välj kod från rätt lista. [Mer information om listkoder på Svenska ämnesords webbplats](http://www.kb.se/katalogisering/Svenska-amnesord/genrer-form/).
  <br/>```Exempel:```
   * ```Piano```
   * ```Blandad kör```
   * ```Menuetter```
      
[Se instruktionsfilm Lägga till genre/form på KB:s Youtubekanal](https://www.youtube.com/watch?v=aAMzfkh_ycA&list=PLZVkEICvA5-GRT2oJQmLgq_2Pksx6zYPy&index=7)  

### Klassifikation 
För anvisningar om hur man anger Klassifikation, se hjälptexten [Verk](https://libris.kb.se/katalogisering/help/workflow-work#klassifikation): Klassifikation.

### Amne  
För samlingar där den geografiska eller kronologiska aspekten är framhävd får genre/form/besättning kompletteras med geografiska eller kronologiska ämnesord (i separata fält). Titel "French piano music" kan alltså indexeras med Piano och Frankrike.  
Lägg till Ämne genom att klicka på plustecknet vid Noterad musik, sök upp Ämne och klicka på plustecknet vid termen. Klicka sedan på plustecknet vid Ämne och välj typ i listan Alla typer: Geografiskt ämnesord eller Kronologiskt ämnesord. Sök upp ämnesordet, t ex Frankrike, och länka till entitet genom att klicka på plustecknet vid termen.  
   
För ytterligare instruktioner, [se Ämnesord i Libris](https://libris.kb.se/katalogisering/help/workflow-general-sh)
  
### Notationssystem och sprak
* Anmärkning: Språk/Anmärkning om språk/Notationssystem /Notation/Benämning (hasNote/marc:LanguageNote/hasNotation/Notation/label = 546 #b)  
  Ange notationssystem [enligt KBSP för RDA 7.13.3.3 Ange typ av musiknotation](http://access.rdatoolkit.org/kbspchp7_kbsp7-120.html) 
  <br/>```Exempel:```
    * ```Traditionell västerländsk notskrift```
    * ```Grafisk notation```  
* Anmärkning/Anmärkning om språk/Anmärkning: Språk/Benämning (hasNote/marc:LanguageNote/marc:LanguageNote/label = 546 #a)
  <br/>```Exempel:```
    * ```Sångtext på hebreiska```
    * ```Kritiska kommentarer på svenska och engelska```  
 
### Malgrupp     
* Målgrupp (intendedAudience = 008/22)  
  Länka till entitet.  
  Trunkera genom att trycka på mellanslagstangenten eller med * i sökrutan. Välj rätt entitet genom att klicka på plustecknet vid entiteten eller på entiteten.  
    ```Exempel: j (= barn- och ungdom, 0-16 år)```  
  
### Innehallstyp
* Innehållstyp/Innehållstyp (contentType/ContentType = 336 #b)  
  Länka till entitet.  
  ```Exempel: term/rda/NotatedMusic```
  
  För att lägga till ytterligare innehållstyp, länka till ytterligare en entitet. I äldre poster har ytterligare innehållstyp lagts i Har del/Verk. Dessa behöver inte ändras.
  
### Har del
* Har del (hasPart = 700 2/_ )  
  Här anges ingående verk om instansen manifesterar fler än ett verk, med föredragna titlar och medverkande.  
  För att ange verk som ingår i det beskrivna verket, klicka på pilen vid Verk och lägg in uppgifterna enligt instruktionerna nedan. För att ange ytterligare verk, klicka på ikonen med tre prickar längst till höger om Verk och välj Duplicera entitet.
  
#### Verk/Har titel/Titel
* Huvudtitel (hasTitle/Title/mainTitle = 700 2/_ #a)  
   Ange den föredragna titeln för verket här, vid behov. Pregnanta titlar för musik anges ofilerade. Skriv in uppgiften.
   <br/>```Exempel:```
    * ```La traviata```
    * ```Symfoni```
         
* Delbeteckning (hasTitle/Title/mainTitle = 700 2/_ #n)  
    Ange numreringar för verket här, vid behov. Skriv in uppgiften.
    <br/>```Exempel:```
     * ```nr 96, Hob. I:96```
     * ```nr 3, op. 90```
         
* Uttryck av/Verk/Har titel/Titel/Deltitel (expressionOf/Work/hasTitle/Title/partName = 700 2/_ #p)  
    Ange eventuell deltitel. Skriv in uppgiften.
    <br/>```Exempel:```
     * ```Di Provenza il mar```
     * ```Allegro```  

* Använd Huvudtitel för hela den föredragna titeln då ordningen mellan uppgifterna i Har titel, Tonart, Version, Besättning och språk för översättning blir felaktig i MARC-förhandsgranskningen, eller om den föredragna titeln är svår eller omöjlig att uttrycka med enbart dessa fält.
    <br/>```Exempel:```
     * ```Sonater och partitor, violin, BWV 1001-1006. Partita, nr 1, h-moll```
     * ```Kvartett, stråkar, nr 13, D. 804, op. 29:1, a-moll, "Rosamunde". Entr'acte```  

* Verk/Primär medverkan/Agent/Person (contribution/PrimaryContribution/agent/Person = 700 2/_ #a)
  Länka till entitet. Börja alltid med att söka efter om agenten redan finns. Vid behov, skapa ny entitet för agent (se Skapa ny agent i hjälpsektionen). I undantagsfall, skapa lokal entitet.  
   ```Exempel: Maier-Röntgen, Amanda, 1853-1894```  
    
* Verk/Tonart (700 2/_ #r) 
  Ange tonart. Skriv in uppgiften.  
   ```Exempel: fiss-moll```  
   
* Verk/Version (700 2/_ #o)  
  Ange eventuellt arrangemang. Skriv in uppgiften.  
  ```Exempel: arr. röst, piano```  

* Verk/Besättning för framförande (700 2/_ #m)  
  Ange besättning. Skriv in uppgiften.
  <br/>```Exempel:```
   * ```orkester```
   * ```klarinett, piano```
   * ```blandad kör```
      
* Verk/Språk/Språk/Benämning (Language/label = 700 2/_ #l)  
  Språk för översättning. Lägg till en förekomst av Språk under Har del/Verk genom att klicka på plustecknet vid Verk. Sök fram Språk i sidorutan, klicka på termen och sedan på Skapa lokal entitet. Lägg till Benämning (klicka på Lägg till egenskaper under: Språk).  
  Skriv in språket i klartext. Denna klartext - verkets (översättningens) språk - visas som ett tillägg till verkets titel i marcpostens 700 2/_ #l.  
    ```Exempel: Svenska```    
    
#### Relationer till andra verk
* Relationer till andra verk med Primär medverkan (700 1/- #a, #d, #t) 
  [Se hjälptexten Relationer till delar och verk](https://libris.kb.se/katalogisering/help/workflow/-agent-relation)

* Relationer till andra verk utan Medverkan och funktion/Primär medverkan (730 0/_ , icke-analytisk sökingång)  
  Under Instans av Verk, lägg till Relation. Välj typ Relation. Lägg till Entitet och välj Entitet. Skapa verk som lokal entitet. Lägg till Har titel och välj Titel. Om det relaterade verket är en översättning, lägg till Språk, skapa lokal entitet och lägg till Benämning. Skriv in språket.
