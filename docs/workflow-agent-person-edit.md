---
section: Hjälptexter agenter
title: Person - Redigera befintlig 
order: 71
date: 2021-10-06
tags:
- redigera agent
- redigera auktoritet
--- 

# Person - Redigera befintlig
Hjälptexten beskriver de egenskaper och klasser som finns (i vissa fall kan ännu fler förekomma) i en befintlig auktoriserad agent av typen person och vilka egenskaper som bör läggas till. Under rubriken Innehåll finns de egenskaper klickbara som kan behöva redigeras eller läggas till i agenten.

## Innehåll
[Inledning](#inledning) 

| [**Adminmetadata**](#befintliga-egenskaper-i-adminmetadata) | [**Agent**](#befintliga-egenskaper-i-beskrivningen) | 
| ------ | ----------- |
| [Katalogiseringsregler](#katalogiseringsregler) | [Agenttyp](#agent) |
| [Katalogiseringsspråk](#katalogiseringsregler) | [Efternamn](#agenttyp) |
| [Auktoritetskontrollnivå](#typ-av-auktoritetspost) | [Förnamn](#efternamn) |
| [Konsulterad källa](#poststatus) | [Födelse- och/eller dödstid](#efternamn) |
| | [Nationalitet](#nationalitet) |
| [**Egenskaper att lägga till i Adminmetadata**](#egenskaper-att-lägga-till-i-adminmetadata) | [**Egenskaper att lägga till i Agent**](#nationalitet) |
| [Katalogisatörens anmärkning](#egenskaper-att-lägga-till-i-adminmetadata) | [Födelsedatum](#nationalitet) |
| | [Dödsdatum](#nationalitet) |
| | [Variant](#variant) |
| | [Identifikator](#identifikator) |
| | [Har yrke eller sysselsättning](#identifikator) |
| | [Beskrivning](#beskrivning) |
| | [**Ytterligare egenskaper att lägga till vid behov**](#beskrivning) |
| | [Namn](#namn) | 
| | [Fullständigare namnform](#namn) | 
| | [Verksamhetsområde](#verksamhetsområde) |
| | [Titel eller övrig beteckning](#verksamhetsområde) |
| | [Andra attribut för person- och organisationsnamn](#verksamhetsområde) |
| | [Ordningstal](#ordningstal) | 
| | [Språk](#ordningstal) | 
| | [Organisatorisk tillhörighet](#ordningstal) |


## Inledning
Vissa egenskaper kan vara obligatoriska att lägga till. Nya egenskaper läggs till med hjälp av den runda plustecknet i verktygsmenyn. Exemplen som finns i hjälptexten är fiktiva.

Det är möjligt att berika en befintlig agent från en mall. Klicka på det runda plustecknet i verktygsmenyn och välj: Berika från mall.

För information om katalogiseringsregler som gäller vid auktorisering, se [Auktoritetsarbete och agenter i Metadatabyrån](https://metadatabyran.kb.se/auktoritetsarbete-och-agenter).

OBS! Var noggrann vid sökning/testlänkning för att säkerställa att auktoriserad namnform inte redan finns. Glöm inte att redigera Adminmetadata och spara innan vidare navigation i verktyget.

## Adminmetadata
Information av administrativ karaktär som är väsentlig för auktoriseringen i sig och inte är direkt förknippad med den auktoriserade namnformen.

### Kontrollnummer
* Kontrollnummer (controlNumber = 001)
  <br/>LibrisID. Ändras ej.

### Skapad av
* Skapad av (descriptionCreator = 040 #a)
  <br/>Förval: Sigel för skapare av agenten. Ändras ej.
  <br/>```Exempel: Organisation: S```

### Katalogiseringsregler
* Katalogiseringsregler (descriptionConventions = 040 #e)
  <br/>Förval: RDA. Ändra vid behov. 
  <br/>```Exempel: RDA```
  
### Katalogiseringsspråk  
* Katalogiseringsspråk (descriptionLanguage = 040 #b)
 <br/>```Exempel: Svenska```
 <br/>Ändras ej. Om egenskapen Katalogiseringsspråk saknas läggs denna till. Länka till entitet.

### Senast ändrad av
* Senast ändrad av (descriptionLastModifier)
  <br/>Förval: Sigel som gjort senaste ändring. Ändras automatiskt vid sparande.  

### Katalogiserande instans
* Katalogiserande instans (marc:catalogingSource = 008/39)
  <br/>Ändras ej.
 
### Typ av auktoritetspost 
* Typ av auktoritetspost (marc:kindOfRecord = 008/9)
  <br/>Ändras ej.

### Auktoritetskontrollnivå
* Auktoritetskontrollnivå (marc:level = 008/33)
 <br/>```Exempel: Kontrollerad/godkänd```
 <br/>Om "Preliminär (ej kontrollerad)" ändra till Kontrollerad/godkänd.

### Poststatus
* Poststatus (recordStatus = 000)
  <br/>Ändras ej. Vid uppdatering ändras status automatiskt.

### Samma sak som
* Samma sak som 
  <br/>Ändras ej.
 
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
  
## Egenskaper att lägga till i Adminmetadata

### Katalogisatörens anmärkning
* Katalogisatörens anmärkning (cataloguersNote = 667 #a)
  <br/>Anmärkningar tänkta för kollegor inom Libriskollektivet. Det kan t.ex. vara uppgifter som rör ändring av den auktoriserade namnformen. Motivera gärna ändringen och komplettera alltid med datum och sigel/signatur. 
  <br/>```Exempel:``` 
  * ```Författaren vill inte ha sitt födelseår kopplat till den auktoriserade namnformen. Enligt e-post 2017-05-12, S/annbjo```
  * ```Ändrat auktoriserad namnform från Xxx till Yyy 2010-01-03 S/marjan```

  
## Agent
Beskrivning av den auktoriserade agenten. 

### Agenttyp
Ändras normalt sett ej. Upptäckta felaktigheter och/eller problem rapporteras till Auktoritetsgruppen.

### Efternamn
* Efternamn (FamilyName = 100 i1=1 #a)
  <br/>```Exempel: Jansson```

### Förnamn
* Förnamn (GivenName = = 100 #a)
  <br/>```Exempel: Erik```

### Födelse- och/eller dödstid
* Födelse- och/eller dödstid (lifeSpan = 100 #d)
  <br/>Årtal används i första hand som särskiljande tillägg för personer. Redigera om det behövs.
  <br/>```Exempel: 1848-1920```

<br/>För osäkra och ungefärliga uppgifter, se information och exempel på sidan [Födelsetid och/eller dödstid i Metadatabyrån](https://metadatabyran.kb.se/auktoritetsarbete-och-agenter/personer/fodelsetid-och-eller-dodstid)

### Nationalitet
* Nationalitet/verksamhetsland (Nationality = 043 #a)
  <br/>Nationalitet/verksamhetsland förknippat med personen. Vid behov kan denna ändras eller raderas.
  <br/>För att lägga till: Klicka på plustecknet under egenskapen Nationalitet/verksamhetsland. Välj Nationalitet som typ och sök efter och välj önskad nationalitet. (Skapa lokal entitet används endast då det inte finns auktoriserad entitet att länka till.)

### Samma sak som
* Samma sak som (SameAs)
  <br/>```Exempel: resource/auth/247521```
  
## Egenskaper att lägga till i beskrivningen

### Födelsedatum
* Födelsedatum (birthDate = 046 #f)
  <br/>Ange fullständigt födelsedatum om uppgiften är känd. I annat fall, ange känd uppgift.
  <br/>```Exempel: 1848-02-19```

<br/>För osäkra och ungefärliga uppgifter, se information och exempel på sidan [Födelsetid och/eller dödstid i Metadatabyrån](https://metadatabyran.kb.se/auktoritetsarbete-och-agenter/personer/fodelsetid-och-eller-dodstid)
  
### Dödsdatum  
* Dödsdatum (deathDate = 046 #g)
  <br/>Ange fullständigt dödsdatum om uppgiften är känd. I annat fall, ange känd uppgift.
  <br/>```Exempel: 1920-12-09```

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
  
### Identifikator
* Identifikator (identifiedBy = 024 #a)
  <br/>ISNI som identifikator är valfri uppgift men önskvärt om tillgänglig (uppgiften hämtas från [ISNI](http://www.isni.org/search)).
  <br/>```Exempel:```
  * ```ISNI:```
  * ```Värde: 0000000121339888```
  <br/>För att lägga till: Klicka på plustecknet i verktygsmenyn. Sidorutan öppnas. Sök efter och lägg till Identifikator. Välj typ (t.ex. ISNI) i rullgardinsmenyn.

### Har yrke eller sysselsättning
* Har yrke eller sysselsättning (hasOccupation = 374)
   <br/>Ange yrke eller sysselsättning om det behövs för att skilja en person från en annan, t.ex. när en persons födelsetid eller dödstid inte är tillgängligt. Hämta i första hand termen från en kontrollerad vokabulär som Svenska ämnesord och länka. Ange endast huvudordet för yrket och inte eventuella adjektivkonstruktioner (välj t.ex. Författare, inte Franska författare, välj Regissörer, inte Kvinnliga regissörer). Om den eftersökta termen saknas i Svenska ämnesord, [föreslå en ny term](https://metadatabyran.kb.se/amnesord-och-genre-form/svenska-amnesord/foresla-ny-term).
   <br/>```Exempel:```
   * ```Romanförfattare ```
   * ```Översättare```
   <br/>För att lägga till: Klicka på plustecknet under egenskapen Har yrke eller sysselsättning, välj Allmänt ämnesord som typ och sök efter och välj önskad term. (Skapa lokal entitet används endast då det inte finns auktoriserad entitet att länka till.)

### Beskrivning
* Beskrivning (description = 678)
  <br/>Används för att ange kortfattad biografisk information är om personens liv eller historia.
  <br/>```Exempel: Nobelpristagare 1909, första kvinnliga ledamot av Svenska akademien 1914.```
  <br/>För att lägga till: Klicka på plustecknet i verktygsmenyn. Sök efter och lägg till Beskrivning. Ange uppgifterna i rutan.


## Ytterligare egenskaper att lägga till vid behov
Vid behov är det möjligt att lägga till egenskaper som inte ingår i mallen. Nya egenskaper läggs till med hjälp av plustecknet i verktygsmenyn.

### Namn
* Namn (name = 100 0/- #a)
  <br/>Används för namn i rak följd istället för Förnamn och Efternamn. **Kan användas i kombination med Förnamn och Efternamn endast för att ange variantnamn.**
  <br/>```Exempel: Namn: Bang``` 
  <br/>Som variantnamn till den auktoriserade namnformen Alving, Barbro, 1909-1987
  <br/>För att lägga till: Klicka på plustecknet under egenskapen Se även, välj typen Person i sökrutan till vänster. Sök efter auktoriserad namnform och lägg till. (Finns ingen länkbar entitet behöver en skapas, dvs. Skapa ny Agent med länkning till den första. Avsluta och spara den ursprungliga först.)

### Fullständigare namnform
Används för att ange fullständig namnform i de fall då förkortning används i den auktoriserade namnformen. Anges i båda egenskaperna listade nedan.
* Fullständigare namnform (fullerFormOfName = 100 #q)
  <br/>```Exempel:```
  <br/>```Fullständigare namnform: Adam David``` (I egenskapen Förnamn är A. D. angivet.)
  
* Fullständigare namnform - Personnamn (marc:fullerFormOfPersonalName = 378 #q)
  <br/>```Exempel:```
  <br/>```Fullständigare namnform - Personnamn: Adam David``` (I egenskapen Förnamn är A. D. angivet.)
  
### Verksamhetsområde 
* Verksamhetsområde (fieldOfActivity = 372)
  <br/>Personens verksamhetsområde beskriver vad personen är intresserad av eller ägnar sig åt och det behöver inte ha med yrkesutövning att göra. Hämta i första hand termen från en kontrollerad vokabulär som Svenska ämnesord och länka.
   <br/>```Exempel: Fågelskådning```
   <br/>För att lägga till: Klicka på plustecknet under egenskapen Har yrke eller sysselsättning, välj Allmänt ämnesord som typ och sök efter och välj önskad term. (Skapa lokal entitet används endast då det inte finns auktoriserad entitet att länka till.)
  
### Titel eller övrig beteckning 
* Titel eller övrig beteckning (marc:titlesAndOtherWordsAssociatedWithAName = 100 #c)
  <br/>Används vid behov som särskiljande tillägg till den auktoriserade namnformen. [Formuleras enligt instruktioner i Metadatabyrån](https://metadatabyran.kb.se/auktoritetsarbete-och-agenter/personer/sarskiljande-tillagg-for-personer#Titel%20eller%20%C3%B6vrig%20beteckning%20f%C3%B6rknippad%20med%20personen).
  <br/>```Exempel:```
  <br/>```påve```
  <br/>```(fiktiv gestalt)```

### Andra attribut för person- och organisationsnamn 
* Andra attribut för person- och organisationsnamn (marc:hasOtherAtrributes = 368)
  <br/>[Formuleras enligt instruktioner i Metadatabyrån](https://metadatabyran.kb.se/auktoritetsarbete-och-agenter/personer/sarskiljande-tillagg-for-personer). Hämta i första hand termen från en kontrollerad vokabulär som Svenska ämnesord och länka. (Skapa lokal entitet används endast då det inte finns auktoriserad entitet att länka till).
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
  <br/>Det språk som personen använder, anges vid behov.
  <br/>```Exempel: Engelska```
  <br/>Klicka på plustecknet vid egenskapen Språk. Välj Språk som typ vid sökning. Välj önskat språk och lägg till. (Skapa lokal entitet används endast då det inte finns auktoriserad entitet att länka till).

### Organisatorisk tillhörighet
 * Organisatorisk tillhörighet (hasAffiliation = 373 #a)
  <br/>Här är det möjligt att ange en samhörande organisation.
  <br/>```Exempel: Uppsala universitet``` 
  <br/>För att lägga till: Klicka på plustecknet vid egenskapen Organisatorisk tillhörighet, och skapa lokal entitet t.ex. organisation. Lägg sedan till benämning och skriv in uppgiften. OBS! Organisatorisk tillhörighet ska inte länkas.


#### Glöm inte att redigera Adminmetadata och spara entiteten innan vidare navigation i verktyget!
