---
section: Hjälptexter agenter
title: Person - Skapa ny 
order: 70
date: 2021-10-06
tags:
- agenter
- auktoriteter
---

# Person - Skapa ny
Hjälptexten beskriver de egenskaper och klasser som finns representerade i mallen för att skapa en ny agent av typen person. Ett urval av egenskaper relevanta för person som är möjliga att lägga till men som inte finns i mallen beskrivs i slutet av hjälptexten.

## Innehåll
[Inledning](#inledning) 

| [Adminmetadata](#adminmetadata) | [Agent](#agent) | 
| ------ | ----------- |
| [Skapad av](#skapad-av) | [Agenttyp](#agent) |
| [Katalogiseringsregler](#katalogiseringsregler) | [Efternamn](#agenttyp) |
| [Katalogisatörens anmärkning](#katalogiseringsregler) | [Förnamn](#efternamn) |
| [Konsulterad källa](#katalogiseringsregler) | [Födelse- och/eller dödstid](#efternamn) |
| [Katalogiseringsspråk](#katalogiseringsspråk) | [Variant](#variant) |
| | [Se även](#variant) |
| | [Har yrke eller sysselsättning](#verksamhetsområde) |
| | [Verksamhetsområde](#verksamhetsområde) |
| | [Beskrivning](#beskrivning) |
| | [Identifikator](#identifikator) |
| | [Nationalitet](#nationalitet) |
| | [Födelsedatum](#födelsedatum) |
| | [Dödsdatum](#dödsdatum) |
| [**Ytterligare egenskaper vid behov**](#beskrivningsnivå) | [**Ytterligare egenskaper vid behov**](#beskrivningsnivå) |
| [Translitterering](#translitterering) | [Namn](#namn) | 
| | [Fullständigare namnform](#namn) | 
| | [Titel eller övrig beteckning](#namn) |
| | [Andra attribut för person- och organisationsnamn](#namn) |
| | [Ordningstal](#ordningstal) | 
| | [Språk](#språk) | 
| | [Organisatorisk tillhörighet](#organisatorisk-tillhörighet) | |

## Inledning
För information om katalogiseringsregler som gäller vid auktorisering, se [Auktoritetsarbete och agenter i Metadatabyrån](https://metadatabyran.kb.se/auktoritetsarbete-och-agenter).

Se även [Lathundar för agenter](https://metadatabyran.kb.se/auktoritetsarbete-och-agenter/lathundar-for-agenter).

OBS! Var noggrann vid sökning/testlänkning för att säkerställa att auktoriserad namnform inte redan finns. Glöm inte att redigera Adminmetadata och spara innan vidare navigation i verktyget.

Exemplet nedan baseras på den auktoriserade namnformen Lagerlöf, Selma, 1858-1940 (i de fall det är möjligt och relevant). Tillägg är fiktiva, enbart för att exemplifiera.

## Adminmetadata
Information av administrativ karaktär som är väsentlig för auktoriseringen i sig men inte är direkt förknippad med den auktoriserade namnformen.
  
### Skapad av
* Skapad av (descriptionCreator = 040 #a)
  <br/>Förval: Inloggad sigel. Ändras ej.
  <br/>```Exempel: S```

### Katalogiseringsregler
* Katalogiseringsregler (descriptionConventions = 040 #e)
  <br/>Förval: rda. Ändra vid behov. 
  <br/>```Exempel:```
  * ```Kod: rda```

### Katalogisatörens anmärkning
* Katalogisatörens anmärkning (cataloguersNote = 667 #a)
  <br/>Anmärkningar tänkta för kollegor inom Libriskollektivet. Det är önskvärt att alla nya auktoriserade namnformer kompletteras med datum och sigel/signatur. I övrigt kan det t.ex. vara uppgifter som rör ändring av den auktoriserade namnformen. Motivera gärna ändringen och komplettera alltid med datum och sigel/signatur. 
  <br/>```Exempel:``` 
  * ```2018-08-27 S/evaann```
  * ```Författaren vill inte ha sitt födelseår kopplat till den auktoriserade namnformen. Enligt e-post 2017-05-12, S/annbjo```

### Konsulterad källa
* Konsulterad källa (sourceConsulted) innehåller Benämning (label = 670 #a) samt Uppgift från källa (citationNote = 670 #b)
  <br/>Ange källa som Benämning och vid behov vilken uppgift som hämtats från källan som Uppgift från källa. Den resurs som föranleder auktoriseringen är obligatorisk källa. 
  <br/>```Exempel på obligatorisk källa där Primär medverkan föranleder auktoriseringen:``` 
  * ```Benämning: Jerusalem / Selma Lagerlöf, 1901``` 
    <br/>```Uppgift från källa: Lagerlöf, Selma```
  
  * ```Benämning: Harry Potter och hemligheternas kammare / J. K. Rowling, 2000``` 
    <br/>```Uppgift från källa: Rowling, J. K.```
    
  <br/>```Exempel på obligatorisk källa där Medverkan föranleder auktoriseringen:``` 
  * ```Benämning: Den gamle och havet / Ernest Hemingway ; översättning av Mårten Edlund, 2005``` 
    <br/>```Uppgift från källa: Edlund, Mårten```

  <br/>```Exempel på kompletterande källa:``` 
  * ```Benämning: NE 2018-04-12.``` 
    <br/>```Uppgift från källa: Levnadstid 1848-1920```
  
  * ```Benämning: NE 2016-10-01```
    <br/>```Uppgift från källa: Fullständigare namnform: Joanne Kathleen```
  
  * ```Benämning: Wikipedia (svenska) 2018-04-12``` 
    <br/>```Uppgift från källa: Dödstid 1867```
  
  * ```Benämning: Birthday``` 
    <br/>```Uppgift från källa: Född: 1988```
  
  * ```Benämning: LC i VIAF 2017-11-21``` 
    <br/>```Uppgift från källa: Proclus, approximately 410-485```
  
  <br/>OBS! Förkortningen t.p., isbd-interpunktion och parenteser som inte behövs för förståelse/läsbarhet behöver inte anges.      
  <br/>För att lägga till: Klicka på plustecknet inom Konsulterad källa. Välj typen Källa vid belagd uppgift i rullmenyn.

### Katalogiseringsspråk
* Katalogiseringsspråk (descriptionLanguage = 040 #b)
  <br/>Förval: language/swe. Ändras ej.


## Agent
Beskrivning av agenten som ska auktoriseras. 

### Agenttyp
Ändras normalt sett ej. Upptäckta felaktigheter och/eller problem rapporteras till Auktoritetsgruppen.

### Efternamn
* Efternamn (FamilyName = 100 1/- #a)
  <br/>Enkelt eller sammansatt släktnamn/efternamn. Föredragen namnform som tillsammans med förnamn utgör den auktoriserade namnformen.
  <br/>```Exempel:```
  * ```Enkelt efternamn: Lagerlöf```
  * ```Sammansatt släktnamn (dubbla efternamn): Lindmark Månsson```
  <br/>Om flera efternamn ska ingå i den auktoriserade namnformen skrivs de direkt efter varandra.

### Förnamn
* Förnamn (GivenName = 100 #a)
  <br/>Förnamn som tillsammans med efternamn utgör den auktoriserade namnformen. 
  <br/>```Exempel:```
  * ```Enkelt förnamn: Selma```
  * ```Flera förnamn: Helena Johanna```
  <br/>Om flera förnamn ska ingå i den auktoriserade namnformen skrivs de direkt efter varandra.

### Födelse- och/eller dödstid
* Födelse- och/eller dödstid (lifeSpan = 100 #d)
  <br/>Årtal används i första hand som särskiljande tillägg för personer. 
  <br/>```Exempel:```
  * ```1858-1940```
  * ```1968-```

<br/>För osäkra och ungefärliga uppgifter, se information och exempel på sidan [Födelsetid och/eller dödstid i Metadatabyrån](https://metadatabyran.kb.se/auktoritetsarbete-och-agenter/personer/fodelsetid-och-eller-dodstid)

### Variant
* Variant (hasVariant = 400 #a #d)
  <br/>Här anges variantnamn och alternativa namnformer samt födelse- och/eller dödstid. Hit hör stavningsvarianter, förkortningar, ändringar till följd av namnbyten, hänvisning från det andra ledet av sammansatt efternamn etc. Variantnamn kan t.ex. finnas i referenskällor eller i den bibliografiska informationen. Egenskapen upprepas om flera variantnamn behöver läggas till. 
  <br/>```Exempel:```
  * ```Enkelt efternamn: Lagerlöf```
  <br/>```Förnamn: Selma Ottiliana Lovisa``` 
  <br/>```Födelse- och/eller dödstid: 1858-1940```
  * ```Stvaningsvariant på efternamn: Lagerlœf``` 
  <br/>```Förnamn: Selma```
  <br/>```Födelse- och/eller dödstid: 1858-1940```
  * ```Sammansatt släktnamn (efternamn): Månsson```
  <br/>```Förnamn: Helena Lindmark``` 
  <br/>```Födelse- och/eller dödstid: 1954-```
  * ```Släktnamn med separata prefix (efternamn): Geer```
  <br/>```Förnamn: Louis de``` 
  <br/>```Födelse- och/eller dödstid: 1677-1735```
  <br/>OBS! För sammansatta släktnamn och namn innehållande separata prefix läggs informationen för närvarande till enligt exemplen ovan.
  <br/>För att lägga till ytterligare Variant: Duplicera entiteten och redigera uppgifterna.

### Se även
* Se även (seeAlso = 500 #a #d)
  <br/>Här länkas se även-hänvisning till en annan auktoriserad namnform, t.ex. till en pseudonym eller då en upphovsperson är verksam under mer än en identitet. T.ex. Smith, Rosamund, 1938- som se-hänvisning från den auktoriserade namnformen för Oates, Joyce Carol, 1938-.
  <br/>```Exempel:``` 
  * ```Efternamn: Smith``` 
  <br/>``` Förnamn: Rosamond``` 
  <br/>```Födelse- och/eller dödstid: 1938-``` 
  <br/>För att lägga till: Klicka på plustecknet inom egenskapen Se även, välj typen Person. Sök efter auktoriserad namnform och lägg till. (Finns ingen länkbar entitet behöver en skapas, dvs. Skapa ny Agent med länkning till den första. Avsluta och spara den ursprungliga först.)

### Har yrke eller sysselsättning
* Har yrke eller sysselsättning (hasOccupation = 374)
   <br/>Ange yrke eller sysselsättning om det behövs för att skilja en person från en annan, t.ex. när en persons födelsetid eller dödstid inte är tillgängligt. Hämta i första hand termen från en kontrollerad vokabulär som Svenska ämnesord och länka. Ange endast huvudordet för yrket och inte eventuella adjektivkonstruktioner (välj t.ex. Författare, inte Franska författare, välj Regissörer, inte Kvinnliga regissörer). Om den eftersökta termen saknas i Svenska ämnesord, föreslå en ny term.
   <br/>```Exempel:```
   * ```Romanförfattare```
   * ```Översättare```
   <br/>För att lägga till: Klicka på plustecknet inom egenskapen Har yrke eller sysselsättning, välj Allmänt ämnesord som typ, sök efter och välj önskad term. (Skapa lokal entitet används endast då det inte finns auktoriserad entitet att länka till.)
   
### Verksamhetsområde
* Verksamhetsområde (fieldOfActivity = 372)
  <br/>Personens verksamhetsområde beskriver vad personen är intresserad av eller ägnar sig åt och det behöver inte ha med yrkesutövning att göra. Hämta i första hand termen från en kontrollerad vokabulär som Svenska ämnesord och länka. 
   <br/>```Exempel: Fågelskådning```
   <br/>För att lägga till: Klicka på plustecknet inom egenskapen Verksamhetsområde, välj Allmänt ämnesord som typ, sök efter och välj önskad term. (Skapa lokal entitet används endast då det inte finns auktoriserad entitet att länka till.)
   
### Beskrivning
* Beskrivning (description = 678)
  <br/>Används för att ange kortfattad biografisk information om personens liv eller historia.
  <br/>```Exempel:```
  * ```Skönlitterär författare, nobelpristagare 1909, första kvinnliga ledamot av Svenska akademien 1914.```

### Identifikator
* Identifikator (identifiedBy = 024 #a)
  <br/>ISNI som identifikator är valfri uppgift men önskvärt om tillgänglig (uppgiften hämtas från [ISNI](http://www.isni.org/search)).
  <br/>```Exempel:```
  * ```ISNI:```
  * ```Värde: 0000000121339888```
  <br/>För att lägga till: Klicka på plustecknet i verktygsmenyn. Sidorutan öppnas. Sök efter och lägg till Identifikator. Välj typ (t.ex. ISNI) i rullgardinsmenyn.

### Nationalitet
* Nationalitet/verksamhetsland (nationality = 043)
  <br/>I mallen ligger nationalitetskoden för Sverige (e-sw---) förifylld. Vid behov kan denna raderas. 
  <br/>För att lägga till: Klicka på plustecknet inom egenskapen Nationalitet/verksamhetsland. Välj Nationalitet som typ, sök efter och välj önskad nationalitet. (Skapa lokal entitet används endast då det inte finns auktoriserad entitet att länka till.)
  
### Födelsedatum
* Födelsedatum (birthDate = 046 #f)
  <br/>Ange fullständigt födelsedatum om uppgiften är känd. I annat fall, ange känd uppgift.
  <br/> ```Exempel:```
  * ```1858-11-20```
  * ```1902```

<br/>För osäkra och ungefärliga uppgifter, se information och exempel på sidan [Födelsetid och/eller dödstid i Metadatabyrån](https://metadatabyran.kb.se/auktoritetsarbete-och-agenter/personer/fodelsetid-och-eller-dodstid)

### Dödsdatum
* Dödsdatum (deathDate = 046 #g)
  <br/>Ange fullständigt dödsdatum om uppgiften är känd. I annat fall, ange känd uppgift.
  <br/>```Exempel:```
  * ```1940-03-16```
  * ```1977```

<br/>För osäkra och ungefärliga uppgifter, se information och exempel på sidan [Födelsetid och/eller dödstid i Metadatabyrån](https://metadatabyran.kb.se/auktoritetsarbete-och-agenter/personer/fodelsetid-och-eller-dodstid)

## Ytterligare egenskaper att lägga till vid behov
Vid behov är det möjligt att lägga till egenskaper som inte ingår i mallen. Nya egenskaper läggs till med hjälp av plustecknet i verktygsmenyn.

### Namn
* Namn (name = 100 0/- #a)
  <br/>Används för namn i rak följd istället för Förnamn och Efternamn. **Kan användas i kombination med Förnamn och Efternamn endast för att ange variantnamn.**
  <br/>```Exempel:```
  * ```Namn: Bang``` 
  <br/>Som variantnamn till den auktoriserade namnformen Alving, Barbro, 1909-1987
  <br/>För att lägga till: Klicka på plustecknet inom egenskapen Se även, välj typen Person i sökrutan till vänster. Sök efter och lägg till auktoriserad namnform. (Finns ingen länkbar entitet behöver en skapas, dvs. Skapa ny Agent med länkning till den första. Avsluta och spara den ursprungliga först.)

### Fullständigare namnform
Används för att ange fullständig namnform i de fall då förkortning används i den auktoriserade namnformen. Anges i båda egenskaperna listade nedan.
* Fullständigare namnform (fullerFormOfName = 100 #q)
  <br/>```Exempel:```
  <br/>```Fullständigare namnform: Adam David``` (I egenskapen Förnamn är A. D. angivet.)
  
* Fullständigare namnform - Personnamn (marc:fullerFormOfPersonalName = 378 #q)
  <br/>```Exempel:```
  <br/>```Fullständigare namnform - Personnamn: Adam David``` (I egenskapen Förnamn är A. D. angivet.)

### Titel eller övrig beteckning 
* Titel eller övrig beteckning (marc:titlesAndOtherWordsAssociatedWithAName = 100 #c)
  <br/>Används vid behov som särskiljande tillägg till den auktoriserade namnformen. [Formuleras enligt instruktioner i Metadatabyrån](https://metadatabyran.kb.se/auktoritetsarbete-och-agenter/personer/sarskiljande-tillagg-for-personer#Titel%20eller%20%C3%B6vrig%20beteckning%20f%C3%B6rknippad%20med%20personen).
  <br/>```Exempel:```
  <br/>```påve```
  <br/>```(fiktiv gestalt)```

### Andra attribut för person- och organisationsnamn 
* Andra attribut för person- och organisationsnamn (marc:hasOtherAtrributes = 368)
  <br/>[Formuleras enligt instruktioner i Metadatabyrån)](https://metadatabyran.kb.se/auktoritetsarbete-och-agenter/personer/sarskiljande-tillagg-for-personer). Hämta i första hand termen från en kontrollerad vokabulär som Svenska ämnesord och länka. (Skapa lokal entitet används endast då det inte finns auktoriserad entitet att länka till).
  <br/>```Exempel:```
  <br/>```Fiktiva gestalter sao```
  <br/>```Professorer sao```
  <br/>```Kung av Sverige```
  <br/>Lägg till egenskapen genom att klicka på plustecknet i verktygsmenyn. 

### Ordningstal
* Ordningstal (marc:numeration = 100 #b)
  <br/>Används som särskiljande tillägg till den auktoriserade namnformen för kungligheter samt för påvar, biskopar och andra personer med religiösa yrken.
  <br/>```Exempel:```
  * ```XXII```
  * ```2```

### Språk
* Språk (associatedLanguage = 377 #a)
  <br/>Ange språk som personen använder vid behov.
  <br/>```Exempel: Engelska```
  <br/>Klicka på plustecknet vid egenskapen Språk. Välj Språk som typ vid sökning. Välj önskat språk och klicka på plustecknet. (Skapa lokal entitet används endast då det inte finns auktoriserad entitet att länka till).

### Organisatorisk tillhörighet
 * Organisatorisk tillhörighet (hasAffiliation = 373 #a)
  <br/>Här är det möjligt att ange en samhörande organisation.
  <br/>```Exempel: Uppsala universitet``` 
  <br/>För att lägga till: Klicka på plustecknet vid egenskapen Organisatorisk tillhörighet, och skapa lokal entitet t ex organisation. Lägg sedan till benämning och skriv in uppgiften. *OBS! Organisatorisk tillhörighet ska inte länkas.*

### Translitterering
* Translitterering (marc:romanization = 008/07)
  <br/>Läggs till vid behov (i adminmetadata).


#### OBS! I de fall namnformen ligger som en lokal entitet, dvs. olänkad, i en instans sker inte länkning automatiskt utan man behöver aktivt utföra länkningen i berörda instanser.
