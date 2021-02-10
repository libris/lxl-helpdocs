---
section: Katalogiseringsverktyget
title: Entiteter
date: 2021-02-10
order: 19
tags:
- redigering
- entiteter
---

# Entiteter

| Innehåll  | | |
| ------ | ------ | ------ |
| [Söka fram entiteter](#soka-fram-entiteter) | | [Duplicera entitet](#duplicera-entitet) | 
| [Länka entitet](#lanka-entitet) | | [Kopiera till urklipp](#kopiera-till-urklipp) | 
| [Lägg till entitet eller skapa lokal entitet](#lagg-till-entitet-eller-skapa-lokal-entitet) | | [Inkommande länkar](#inkommande-lankar) |
| [Exempel på lokala entiteter](#exempel-pa-lokala-entiteter) | | |

## Soka fram entiteter
När du ska lägga till en entitet är första steget att göra en sökning för att se om entiteten redan finns eller inte. Klicka på plustecknet vid entitetsrubriken. En sidoruta öppnas till höger - "Lägg till entitet". Högst upp i sidorutan finns en sökruta. 

Sökningen görs antingen via:

**Fritextsök:**  Gör en bred sökning genom att skriva in text i sökfältet i sidorutan och få fram ett sökresultat.

**Sök i typer:** Välj “typ” i listan i kombination med en fritextsökning. Då blir sökresultatet specifikt för den valda typen.  

![Sök entitet](sokentitet.png)

För att se alla entiteter av en viss typ, tryck Enter när markören står i sökfältet eller skriv * i sökfältet.  

## Lanka entitet
Om det finns en befintlig lokal entitet, kan man ersätta den med en länkad entitet. Börja alltid med att söka efter om entiteten redan finns. Ersätt den lokala entiteten med korrekt länkbar entitet. (För agenter: finns ingen länkbar entitet, skapa en länkbar entitet eller låt den lokala entiteten ligga kvar.) 

![Lokal entitet steg 3](lokalentitet3.png)


## Lagg till entitet eller skapa lokal entitet
När du gjort en entitetssökning kan du: 

**Lägga till entitet:**
Om du fått fram ett önskat sökresultat kan du lägga till den relevanta entiteten genom att klicka på plustecknet till vänster om entiteten - “Lägg till". Entiteten lägger sig då i posten som en länk. Du kan även välja att granska entiteten innan du väljer att lägga till den. Klicka då på entitetens rubrik. Entiteten öppnas i ny flik.  

![Lägg till entitet](laggtillentitet.png)  


**Skapa lokal entitet:**
Om du inte hittar en relevant länkad entitet att lägga till, kan du i vissa fall i stället skapa en lokal entitet. Klicka på Skapa lokal entitet, längst ner till höger i sidorutan.

![Lokal entitet steg 1](lokalentitet1.png)


Välj typ av entitet i listan eller sök direkt på entitetsrubriken och välj sedan entiteten.
![Lokal entitet steg 2](lokalentitet2.png)

## Exempel pa lokala entiteter
Nedan listas exempel på hur du skapar olika typer av lokala entiteter i de fall det inte finns en länkbar entitet och heller inte behöver upprättas en sådan. Det senare gäller agenter, se [Metadatabyrån - Riktlinjer för löpande auktoritetsarbete i Libris](https://metadatabyran.kb.se/auktoritetsarbete-och-agenter/riktlinjer-for-lopande-auktoritetsarbete-i-libris) när det behövs eller inte.


### Person

* **Person som Primär medverkan** (contribution/PrimaryContribution/agent/Person = 100 1/_) **eller Medverkan** (contribution/Contribution/agent/Person = 700 1/_)
<br/>Vid Medverkan och funktion välj typ av medverkan i rullmenyn. Klicka på plustecknet vid Agent och välj Person i rullmenyn för Skapa lokal entitet. Skriv in korrekt namnform.
 <br/>```Exempel: Efternamn: Wigg samt Förnamn: Susan```
 <br/>För personnamn i rak följd. Klicka på plustecknet vid Person och välj egenskapen Namn. Skriv in uppgiften.
 <br/>```Exempel: Namn: Sigfús Daðason```

* **Person som Ämne** (Subject/agent/Person = 600 1/4)
<br/>Klicka på plustecknet vid Ämne och välj Person i rullmenyn för Skapa lokal entitet. Skriv in korrekt namnform.
 <br/>```Exempel: Efternamn: Goodman samt Förnamn: Amy```
 <br/>För personnamn i rak följd. Klicka på plustecknet vid Person och välj egenskapen Namn. Skriv in korrekt namnform.
 <br/>```Exempel: Namn: Mini samt Födelsetid och/eller dödstid: 1975-```

### Fiktiv gestalt

* **Fiktiv gestalt som Ämne** (Subject/agent/Person = 600 1/4)
<br/>Klicka på plustecknet vid Ämne och välj Person i rullmenyn för Skapa lokal entitet. Ange personnamnet enligt samma princip som för en verklig person. Tillägget "(fiktiv gestalt)" läggs till via egenskapen Titel eller övrig beteckning.
  <br/>```Exempel:```
  * ```Namn: Bambi samt Titel eller övrig beteckning (fiktiv gestalt)```
  * ```Efternamn: Granger samt Förnamn: Hermione samt Titel eller övrig beteckning (fiktiv gestalt)```

### Organisation

* **Organisation med namnform i ett led som Primär medverkan** (contribution/PrimaryContribution/agent/Organization = 110 2/_) **eller Medverkan** (contribution/Contribution/agent/Organization = 710 2/_)
<br/>Vid Medverkan och funktion välj typ av medverkan i rullmenyn. Klicka på plustecknet vid Agent och välj Organisation i rullmenyn för Skapa lokal entitet. Skriv in korrekt namnform.
  <br/>```Exempel: Namn: Vikingeskibsmuseet (Roskilde)```

* **Organisation med namnform i flera led som Primär medverkan** (contribution/PrimaryContribution/agent/Organization = 110 2/_) **eller Medverkan** (contribution/Contribution/agent/Organization = 710 2/_)
<br/>Vid Medverkan och funktion välj typ av medverkan i rullmenyn. Klicka på plustecknet vid Agent och välj Organisation i rullmenyn för Skapa lokal entitet. Ta bort Namn som följer med i en snippet. Klicka på plustecknet vid Organisation och lägg till egenskaperna Är del av samt Namn på underordnad enhet. Klicka på plustecknet vid egenskapen Är del av och välj återigen Organisation i rullmenyn för Skapa lokal entitet. Skriv in korrekt namnform.
 <br/>```Exempel: Organisation/Är del av/Organisation/Namn: British Library samt Organisation/Namn på underordnad enhet: Department of Oriental Manuscripts and Printed Books```
<br/>Om namnformen består av fler än två led används plustecknet inom Namn på underordnad enhet för att skapa ny rad. Här anges ytterligare led av namnformen.

* **Organisation som Ämne** (Subject/agent/Organization = 610 2/4)
<br/>Klicka på plustecknet vid Ämne och välj Organisation i rullmenyn för Skapa lokal entitet. Skriv in korrekt namnform.
  <br/>```Exempel: Namn: Kastelholms slott```

* **Organisation med namnform i flera led som Ämne** (Subject/agent/Organization = 610 2/4)
<br/>Klicka på plustecknet vid Ämne och välj Organisation i rullmenyn för Skapa lokal entitet. Ta bort Namn som följer med i en snippet. Klicka på plustecknet vid Organisation och lägg till egenskaperna Är del av samt Namn på underordnad enhet. Klicka på plustecknet vid egenskapen Är del av och välj återigen Organisation i rullmenyn för Skapa lokal entitet. Skriv in korrekt namnform.
<br/>```Exempel: Organisation/Är del av/Organisation/Namn: Library of Congress samt Organisation/Namn på underordnad enhet: Federal Research Division```
<br/>Om namnformen består av fler än två led används plustecknet inom Namn på underordnad enhet för att skapa ny rad. Här anges ytterligare led av namnformen.

### Jurisdiktion

* **Jurisdiktion med namnform i ett led som Primär medverkan** (contribution/PrimaryContribution/Agent/Jurisdiction = 110 1/_) **eller Medverkan** (contribution/Contribution = 710 1/_)
<br/>Vid Medverkan och funktion välj typ av medverkan i rullmenyn. Klicka på plustecknet vid Agent och välj Jurisdiktion i rullmenyn för Skapa lokal entitet. Skriv in korrekt namnform.
  <br/>```Exempel: Namn: Region Hovedstaden (Danmark)```

* **Jurisdiktion med namnform i flera led som Primär medverkan** (contribution/PrimaryContribution/agent/Jurisdiction = 110 1/_) **eller Medverkan** (contribution/Contribution/agent/Jurisdiction = 710 1/_)
<br/>Vid Medverkan och funktion välj typ av medverkan i rullmenyn. Klicka på plustecknet vid Agent och välj Jurisdiktion i rullmenyn för Skapa lokal entitet. Klicka på plustecknet vid Jurisdiktion och lägg till egenskaperna Är del av samt Namn på underordnad enhet. Klicka på plustecknet vid egenskapen Är del av och välj återigen Jurisdiktion i rullmenyn för Skapa lokal entitet. Skriv in korrekt namnform.
<br/>```Exempel: Jurisdiktion/Är del av/Jurisdiktion/Namn: Jönköpings kommun (Sverige) samt Jurisdiktion/Namn på underordnad enhet: Kulturnämnden```
<br/>Om namnformen består av fler än två led används plustecknet inom Namn på underordnad enhet för att skapa ny rad. Här anges ytterligare led av namnformen.

* **Jurisdiktion som Ämne** (Subject/agent/Jurisdiction = 610 1/4)
<br/>Klicka på plustecknet vid Ämne och välj Jurisdiktion i rullmenyn för Skapa lokal entitet. Skriv in korrekt namnform.
   <br/>```Exempel: Namn: Aalborgs kommun (Danmark)```

* **Jurisdiktion med namnform i flera led som Ämne** (Subject/agent/Jurisdiction = 610 1/4)
<br/>Klicka på plustecknet vid Ämne och välj Jurisdiktion i rullmenyn för Skapa lokal entitet. Klicka på plustecknet vid Jurisdiktion och lägg till egenskaperna Är del av samt Namn på underordnad enhet. Klicka på plustecknet vid egenskapen Är del av och välj återigen Jurisdiktion i rullmenyn för Skapa lokal entitet. Skriv in korrekt namnform.
<br/>```Exempel: Jurisdiktion/Är del av/Jurisdiktion/Namn: Storbritannien samt Jurisdiktion/Namn på underordnad enhet: MI5```
<br/>Om namnformen består av fler än två led används plustecknet inom Namn på underordnad enhet för att skapa ny rad. Här anges ytterligare led av namnformen.

### Släkt

* **Släkt som Primär medverkan** (contribution/PrimaryContribution/agent/Family = 100 3/) eller Medverkan (contribution/Contribution/agent/Family =700 3/_)
<br/>Vid Medverkan och funktion välj typ av medverkan i rullmenyn. Klicka på plustecknet vid Agent och välj Släkt i rullmenyn för Skapa lokal entitet. Klicka på plustecknet inom Släkt, sök efter och lägg till Titel eller övrig beteckning. Skriv in korrekt namnform, ange släkt och årtal vid behov.
  <br/>```Exempel: Namn: Ibsen samt Titel eller övrig beteckning: släkt```
  
* **Släkt som Ämne** (Subject/agent/Family = 600 3/_)
<br/>Klicka på plustecknet vid Ämne och välj Släkt i rullmenyn för Skapa lokal entitet. Klicka på plustecknet inom Släkt, sök efter och lägg till Titel eller övrig beteckning. Skriv in korrekt namnform, ange släkt och årtal vid behov.
  <br/>```Exempel: Namn: Hilton samt Titel eller övrig beteckning: släkt samt Födelsetid och/eller dödstid: 1900-talet-```

### Möte

* **Möte som Primär medverkan** (contribution/PrimaryContribution/agent/Meeting = 111 2/_) **eller Medverkan** (contribution/Contribution/agent/Meeting = 711 2/_)

<br/>Vid Medverkan och funktion välj typ av medverkan i rullmenyn. Klicka på plustecknet vid Agent och välj Möte i rullmenyn för Skapa lokal entitet. Skriv in korrekt namnform. Tillsvidare används ingen interpunktion för möten.
  <br/>```Exempel: Namn: International Congress of Byzantine Studies samt Ordningstal: 21 samt Datum: 2006```

* **Möte som Ämne** (Subject/agent/Meeting = 611 2/_)
<br/>Klicka på plustecknet vid Ämne och välj Möte i rullmenyn för Skapa lokal entitet. Skriv in korrekt namnform. Tillsvidare används ingen interpunktion för möten.
 <br/>```Exempel: Namn: Nationella cykelhjälmskonferensen samt Ordningstal: 2 samt Datum: 1999``


## Duplicera entitet
Det går i vissa fall att duplicera en entitet. Klicka på de tre prickarna till höger om entiteten - "Hantera". Välj Duplicera entitet. Entiteten dupliceras och den nya entiteten lägger sig under den kopierade, inom samma post.

## Kopiera till urklipp
Det går i vissa fall att kopiera en entitet till urklipp. Klicka på de tre prickarna till höger om entiteten - "Hantera". Välj Kopiera till urklipp. När du väljer kopiera till urklipp, sparas den lokala entiteten i verktygets minne samtidigt som verktyget känner av var entiteten kan klistras in.  
Kopiera till urklipp:  
![Kopiera till urklipp](kopieraurklipp.png)
<br><br>

 En klistra-in-ikon visar var det går att klistra in urklippet.  
Klistra in urklipp:  

![Klistra in urklipp](klistraurklipp.png)
<br>
Du kan kopiera en entitet från en post och klistra in i en annan post. Det fungerar ofta bra att använda olika flikar för posterna.

## Inkommande lankar
Gränssnittet använder en funktion för inkommande länkar som innebär att länkning mellan entiteter endast görs på ett ställe. Funktionen används för ämnesord där termer som ingår i en hierarki, dvs. bredare/smalare endast länkas på ett ställe. I den smalare termen länkas det till den bredare och funktionen för inkommande länkar visar då upp den motsatta relationen, dvs. "smalare" i beskrivningen av den bredare termen.
