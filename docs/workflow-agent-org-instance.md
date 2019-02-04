---
section: Hjälptexter katalogisering
title: Relationer till Agent
order: 33
date: 2019-01-10
tags:
- editor
- under arbete
--- 

## Relationer till Agent

Hjälptexten innehåller instruktioner för hur man beskriver någon eller något som en typ Agent kopplad till egenskaperna Medverkan och funktion och/eller Ämne i resursens verksbeskrivning.

Verksbeskrivningen görs i instansbeskrivningsens översta del, Instans av Verk. Saknas egenskaperna Medverkan och funktion eller Ämne läggs dessa till genom att klicka på plustecknet vid verkstypen.

Beskrivning av Agent sker genom att antingen länka till någon eller något som redan finns i Libris som en länkbar entitet (en auktoritetsbeskrivning finns) eller genom att beskriva agenten som en lokal entitet (auktoritetsbeskrivning saknas). 

I de fall en länkbar entitet saknas kan en ny entitet skapas genom att göra en ny auktoritetsbeskrivning. För riktlinjer när nya auktoritetsbeskrivningar bör skapas, se [Riktlinjer för det löpande auktoritetsarbetet i Libris](http://www.kb.se/dokument/Riktlinjer%20för%20det%20löpande%20auktoritetsarbetet%20i%20Libris.pdf). Instruktioner för hur man praktiskt går till väga finns under Hjälptexter Agenter. OBS! I nuläget finns endast mallar för att skapa ny Person och för att skapa ny Organisation.

För information om katalogregler, skrivregler och övriga katalogiseringsanvisningar, se [Anvisningar för katalogisering - RDA](http://www.kb.se/rdakatalogisering/Anvisningar/ "Anvisningar för katalogisering - RDA").

För information om katalogiseringsregler som gäller vid auktoritetsarbete, se 
[Anvisningar för katalogisering (RDA) - Auktoritetsarbete.](http://www.kb.se/rdakatalogisering/Auktoritetsarbete// "Anvisningar för katalogisering (RDA) - Auktoritetsarbete")


### Innehåll

| [Agent som Primär medverkan eller Medverkan](#agent-som-primar-medverkan-eller-medverkan)  | [Agent som Ämne](#agent-som-amne)
| ------ | ------- |
| [**Länka till entitet**](#agent-som-primar-medverkan-eller-medverkan) | [**Länka till entitet**](#agent-som-amne) |
| [Agent](#agent-som-primar-medverkan-eller-medverkan) | [Agent](#agent-som-amne)
| [Funktion](#funktion)
| [**Skapa lokal entitet**](#skapa-lokal-entitet) | [**Skapa lokal entitet**](#skapa-lokal-entitet) 
| [Person](#person) | [Person](#person)
| [Organisation](#organisation) | [Fiktiv gestalt](#fiktiv-gestalt) |
| [Jurisdiktion](#jurisdiktion) | [Organisation](#organisation) |
| [Släkt](#jurisdiktion) | [Jurisdiktion](#jurisdiktion) |
| [Möte](#mote) | [Släkt](#jurisdiktion)
| | [Möte](#mote) |


### Agent som Primar medverkan eller Medverkan

#### Länka till entitet

##### Agent

* Primär medverkan/Medverkan/Agent (contribution/PrimaryContribution/agent = 100, 110, 111, 700, 710, 711)
<br/>Vid Medverkan och funktion välj typ av medverkan i rullmenyn. Klicka på plustecknet vid Agent. Sök efter namnformen som ska länkas. Begränsa sökningen genom att välja typ av Agent. Välj namnform och länka genom att klicka på plustecknet vid namnformen eller på namnformen.
<br/>```Exempel:```
  * ```Lindgren, Astrid, 1907-2002```
  * ```Potter, Harry, (fiktiv gestalt)```
  * ```Arbetslivscentrum```
  * ```Sverige. Landsbygdsdepartementet```
  * ```Kommunikationer i gränsland (konferens)```
  
##### Funktion 

* Primär medverkan/Medverkan/Funktion (contribution/PrimaryContribution/role = 100 ‡4, 110 ‡4, 700 ‡4, 710 ‡4)
<br/>Lägg till en funktionskod genom att klicka på plustecknet vid Funktion och sök fram en funktionskod. Skriv in kod eller utskriven form i sökrutan eller tryck på mellanslagstangenten för att se alla koder. Välj kod och länka genom att klicka på plustecknet vid koden eller på koden. Vid behov länkas Funktion även när lokal entitet skapas.
<br/>För en sorterad lista på koder, se Formathandboken för Libris/Voyager: [Funktions- och relationskoder](http://www.kb.se/katalogisering/Formathandboken/Funktionskoder/)
<br/>```Exempel:```
  * ```Författare, aut```
  * ```Illustratör, ill```
  * ```Utgivare, pbl```
  

### Agent som Amne

#### Länka till entitet

##### Agent

* Ämne/Agent (subject/agent = 600, 610, 611)
<br/>Klicka på plustecknet vid Ämne. Sök efter namnformen som ska länkas. Begränsa sökningen genom att välja typ av Agent. Välj namnform och länka genom att klicka på plustecknet vid namnformen eller på namnformen.
<br/>```Exempel:```
  * ```Lindgren, Astrid, 1907-2002```
  * ```Potter, Harry, (fiktiv gestalt)```
  * ```Arbetslivscentrum```
  * ```Sverige. Landsbygdsdepartementet```
  * ```Windsor (kungahus: 1917-)```
  * ```Olympiska spelen, 2012```
    

### Skapa lokal entitet

#### Person

* Person som Primär medverkan/Medverkan (contribution/PrimaryContribution/agent/Person = 100 1/ , 700 1/ )
<br/>Vid Medverkan och funktion välj typ av medverkan i rullmenyn. Klicka på plustecknet vid Agent och välj Person i rullmenyn för Skapa lokal entitet. Skriv in korrekt namnform.
 <br/>```Exempel: Efternamn: Wigg samt Förnamn: Susan```
 <br/>För personnamn i rak följd. Klicka på plustecknet vid Person och välj egenskapen Namn. Skriv in uppgiften.
 <br/>```Exempel: Namn: Sigfús Daðason```

* Person som Ämne (Subject/agent/Person = 600 1/4)
<br/>Klicka på plustecknet vid Ämne och välj Person i rullmenyn för Skapa lokal entitet. Skriv in korrekt namnform.
 <br/>```Exempel: Efternamn: Goodman samt Förnamn: Amy```
 <br/>För personnamn i rak följd. Klicka på plustecknet vid Person och välj egenskapen Namn. Skriv in korrekt namnform.
 <br/>```Exempel: Namn: Madonna samt Födelsetid och/eller dödstid: 1958-```

#### Fiktiv gestalt

* Fiktiv gestalt som Ämne (Subject/agent/Person = 600 1/4)
<br/>Klicka på plustecknet vid Ämne och välj Person i rullmenyn för Skapa lokal entitet. Ange personnamnet enligt samma princip som för en verklig person. Tillägget "(fiktiv gestalt)" läggs till via egenskapen Titel eller övrig beteckning.
  <br/>```Exempel:```
  * ```Namn: Bambi samt Titel eller övrig beteckning (fiktiv gestalt)```
  * ```Efternamn: Granger samt Förnamn: Hermione samt Titel eller övrig beteckning (fiktiv gestalt)```

#### Organisation

* Organisation med namnformen i ett led som Primär medverkan/Medverkan (contribution/PrimaryContribution/agent/Organization = 110 2/ , 710 2/ )
<br/>Vid Medverkan och funktion välj typ av medverkan i rullmenyn. Klicka på plustecknet vid Agent och välj Organisation i rullmenyn för Skapa lokal entitet. Skriv in korrekt namnform.
  <br/>```Exempel: Namn: Vikingeskibsmuseet (Roskilde)```

* Organisation med namnformen i flera led som Primär medverkan/Medverkan (contribution/PrimaryContribution/agent/Organization = 110 2/ , 710 2/ )
<br/>Vid Medverkan och funktion välj typ av medverkan i rullmenyn. Klicka på plustecknet vid Agent och välj Organisation i rullmenyn för Skapa lokal entitet. Klicka på plustecknet vid Organisation och lägg till egenskaperna Är del av samt Namn på underordnad enhet. Klicka på plustecknet vid egenskapen Är del av och välj återigen Organisation i rullmenyn för Skapa lokal entitet. Skriv in korrekt namnform.
<br/>```Exempel: Organisation/Är del av/Organisation/Namn: British Library samt Organisation/Namn på underordnad enhet: Department of Oriental Manuscripts and Printed Books```
<br/>OBS! Det fungerar inte att konstruera namnformer i fler än två led i nuläget.

* Organisation med namnformen i ett led som Ämne (Subject/agent/Organization = 610 2/4)
<br/>Klicka på plustecknet vid Ämne och välj Organisation i rullmenyn för Skapa lokal entitet. Skriv in korrekt namnform.
  <br/>```Exempel: Namn: Kastelholms slott```

* Organisation med namnformen i flera led som Ämne (Subject/agent/Organization = 610 0/4)
<br/>Klicka på plustecknet vid Ämne och välj Organisation i rullmenyn för Skapa lokal entitet. Klicka på plustecknet vid Organisation och lägg till egenskaperna Är del av samt Namn på underordnad enhet. Klicka på plustecknet vid egenskapen Är del av och välj återigen Organisation i rullmenyn för Skapa lokal entitet. Skriv in korrekt namnform.
<br/>```Exempel: Organisation/Är del av/Organisation/Namn: Library of Congress samt Organisation/Namn på underordnad enhet: Federal Research Division```
<br/>OBS! Det fungerar inte att konstruera namnformer i fler än två led i nuläget.

#### Jurisdiktion

* Jurisdiktion med namnform i ett led som Primär medverkan/Medverkan (contribution/PrimaryContribution/agent/Jurisdiction = 110 1/ , 710 1/ )
<br/>Vid Medverkan och funktion välj typ av medverkan i rullmenyn. Klicka på plustecknet vid Agent och välj Jurisdiktion i rullmenyn för Skapa lokal entitet. Skriv in korrekt namnform.
  <br/>```Exempel: Namn: Region Hovedstaden (Danmark)```

* Jurisdiktion med namnformen i flera led som Primär medverkan/Medverkan (contribution/PrimaryContribution/agent/Jurisdiction = 110 1/ , 710 1/ )
<br/>Vid Medverkan och funktion välj typ av medverkan i rullmenyn. Klicka på plustecknet vid Agent och välj Jurisdiktion i rullmenyn för Skapa lokal entitet. Klicka på plustecknet vid Jurisdiktion och lägg till egenskaperna Är del av samt Namn på underordnad enhet. Klicka på plustecknet vid egenskapen Är del av och välj återigen Jurisdiktion i rullmenyn för Skapa lokal entitet. Skriv in korrekt namnform.
<br/>```Exempel: Jurisdiktion/Är del av/Jurisdiktion/Namn: Danmark samt Jurisdiktion/Namn på underordnad enhet: Folketinget```
<br/>OBS! Det fungerar inte att konstruera namnformer i fler än två led i nuläget.

* Jurisdiktion med namnformen i ett led som Ämne (Subject/agent/Jurisdiction = 610 1/4)
<br/>Klicka på plustecknet vid Ämne och välj Jurisdiktion i rullmenyn för Skapa lokal entitet. Skriv in korrekt namnform.
   <br/>```Exempel: Namn: Aalborgs kommun (Danmark)```

* Jurisdiktion med namnformen i flera led som Ämne (Subject/agent/Jurisdiction = 610 1/4)
<br/>Klicka på plustecknet vid Ämne och välj Jurisdiktion i rullmenyn för Skapa lokal entitet. Klicka på plustecknet vid Jurisdiktion och lägg till egenskaperna Är del av samt Namn på underordnad enhet. Klicka på plustecknet vid egenskapen Är del av och välj återigen Jurisdiktion i rullmenyn för Skapa lokal entitet. Skriv in korrekt namnform.
<br/>```Exempel: Jurisdiktion/Är del av/Jurisdiktion/Namn: Storbritannien samt Jurisdiktion/Namn på underordnad enhet: MI5```
<br/>OBS! Det fungerar inte att konstruera namnformer i fler än två led i nuläget.

#### Släkt

* Släkt som Primär medverkan/Medverkan (contribution/PrimaryContribution/agent/Family = 100 3/ , 700 3/ )
<br/>Vid Medverkan och funktion välj typ av medverkan i rullmenyn. Klicka på plustecknet vid Agent och välj Släkt i rullmenyn för Skapa lokal entitet. Skriv in korrekt namnform.
  <br/>```Exempel: Namn: Ibsen (släkt)```
  
* Släkt som Ämne (Subject/agent/Family = 600 3/ )
<br/>Klicka på plustecknet vid Ämne och välj Släkt i rullmenyn för Skapa lokal entitet. Skriv in korrekt namnform.
  <br/>```Exempel: Namn: Hilton (släkt) samt Födelsetid och/eller dödstid: 1900-talet-```

#### Mote

* Möte som Primär medverkan/Medverkan (contribution/PrimaryContribution/agent/Meeting = 111 2/ , 711 2/ )
<br/>Vid Medverkan och funktion välj typ av medverkan i rullmenyn. Klicka på plustecknet vid Agent och välj Möte i rullmenyn för Skapa lokal entitet. Skriv in korrekt namnform.
  <br/>```Exempel: Namn: International Congress of Byzantine Studies samt Datum: 2006 samt Ordningstal: 21```

* Möte som Ämne (Subject/agent/Meeting = 611 2/ )
<br/>Klicka på plustecknet vid Ämne och välj Möte i rullmenyn för Skapa lokal entitet. Skriv in korrekt namnform.
 <br/>```Exempel: Namn: Nationella cykelhjälmskonferensen samt Datum: 1999 samt Ordningstal: 2```

