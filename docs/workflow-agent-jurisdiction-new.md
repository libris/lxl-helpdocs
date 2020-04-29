---
section: Hjälptexter agenter
title: Jurisdiktion - Skapa ny 
order: 77
date: 2020-04-29
tags:
- under arbete
- agenter
- auktoriteter
- jurisdiktioner
--- 


# Jurisdiktion - Skapa ny
Hjälptexten beskriver de egenskaper som finns representerade i mallen för att skapa en ny agent av typen jurisdiktion. Egenskaper relevanta för jurisdiktion som är möjliga att lägga till men som inte finns i mallen beskrivs i slutet av hjälptexten.

## Innehåll
[Inledning](#inledning)

| [Adminmetadata](#adminmetadata) | [Agent](#agent) | 
| ------ | ----------- |
| [Skapad av](#adminmetadata) | [Agenttyp](#agent) |
| [Katalogiseringsregler](#adminmetadata) | [Namn](#agenttyp) |
| [Katalogisatörens anmärkning](#katalogiseringsregler) | [Namnform i flera led](#namnform-i-flera-led) |
| [Konsulterad källa](#katalogiseringsregler) | [Variant](#variant) |
| [Katalogiseringsspråk](#katalogiseringsregler) | [Se även](#variant) |
| | [Beskrivning](#beskrivning) |
| | [Verksamhetens starttid](#verksamhetens-starttid) |
| | [Verksamhetens sluttid](#verksamhetens-sluttid) |
| | [Identifikator](#identifikator) |
| | [Nationalitet](#nationalitet) |
| | [**Ytterligare egenskaper att lägga till vid behov**](#administrativ-historik) |
| | [Tid för grundande](#tid-for-grundande) | |
| | [Tid för upphörande](#tid-for-grundande) | |
| | [Verksamhetsområde](#tid-for-grundande) | |
| | [Språk](#tid-for-grundande) | |
 

## Inledning
För information om katalogiseringsregler som gäller vid auktorisering, [se Anvisningar för katalogisering (RDA) - Auktoritetsarbete](http://www.kb.se/rdakatalogisering/Auktoritetsarbete// "Anvisningar för katalogisering (RDA) - Auktoritetsarbete").

OBS! Var noggrann vid sökning/testlänkning för att säkerställa att auktoriserad namnform inte redan finns. Glöm inte att redigera Adminmetadata och spara innan vidare navigation i verktyget.

Exempel i hjälptexten är fiktiva.

## Adminmetadata
Information av administrativ karaktär som är väsentlig för auktoriseringen i sig men inte är direkt förknippad med den auktoriserade namnformen.
   
### Skapad av
* Skapad av (descriptionCreator = 040 #a)
 <br/>Förval: inloggad sigel. Ändras ej.
 <br/>```Exempel: library/S```

### Katalogiseringsregler
* Katalogiseringsregler (descriptionConventions = 040 #e)
 <br/>Förval: rda. Ändra vid behov.
 <br/>```Exempel: Kod: rda```

### Katalogisatorens anmärkning
* Katalogisatörens anmärkning (cataloguersNote = 667 #a)
  <br/>Anmärkningar tänkta för kollegor inom Libriskollektivet. Det kan till exempel vara uppgifter som rör ändring av den auktoriserade namnformen. Motivera gärna ändringen och komplettera alltid med datum/sigel/signatur. Det är önskvärt att alla nya auktoriserade namnformer kompletteras med datum/sigel/signatur. 
  <br/>```Exempel:```
  * ```2018-08-28/S/NB/carbac```
  * ```Ändrat auktoriserad namnform från Xxx till Yyy 2010-01-03/S/UL/marjan```

### Konsulterad källa
* Konsulterad källa (sourceConsulted) innehåller Benämning (label = 670 #a) samt Uppgift från källa (citationNote = 670 #b)
  <br/>Ange källa som Benämning och vid behov uppgift som hämtats från källan som Uppgift från källa. 
  <br/>Den resurs som föranleder auktoriseringen är en obligatorisk källa.
  <br/>```Exempel på obligatorisk källa:```
  * ```Benämning: Översyn av utredningsförfarandet i brottmål, 1979``` 
    <br/>```Uppgift från källa: Sverige. Justitiedepartementet```
 
  <br/>```Exempel på kompletterande källa:```
  * ```Benämning: Wikipedia (Svenska) 2017-10-20```
    <br/>```Uppgift från källa: Namnformen: Åmåls kommun```
    
  * ```Benämning: Sveriges statskalender. Årg. 2003``` 
    <br/>```Uppgift från källa: Startår: 1840```
   
  <br/>OBS! Förkortningen t.p., isbd-interpunktion och parenteser som inte behövs för förståelse/läsbarhet behöver inte anges.      
  <br/>För att lägga till: Klicka på plustecknet inom Konsulterad källa. Välj typen Källa vid belagd uppgift i rullmenyn.

### Katalogiseringsspråk
* Katalogiseringsspråk (descriptionLanguage = 040 #b)
 <br/>Förval: language/swe. Ändras ej


## Agent

### Agenttyp
Ändras normalt sett ej. Upptäckta felaktigheter och/eller problem rapporteras till Auktoritetsgruppen.

### Namn   
* Namn 
  <br/>(name) (110 #a)
  <br/>Föredragen namnform som utgör den auktoriserade namnformen.
  <br/>```Exempel: Göteborgs stad (Sverige)```
  <br/>För namnform som består av flera led används istället egenskaperna Är del av tillsammans med Namn på underordnad enhet.
  
### Namnform i flera led
Namnform i flera led består av egenskaperna Är del av tillsammans med Namn på underordnad enhet.
* Är del av/Namn (isPartOf/name = 110 2/- #a)
  <br/>Överordnat namn i en auktoriserad namnform som består av flera led. Egenskapen används endast tillsammans med Namn på underordnad enhet.
  <br/>```Exempel: Sverige```
  <br/>OBS! Egenskapen Är del av ska inte länkas.

* Namn på underordnad enhet (marc/subordinateUnit = 110 2/- #b och 110 2/- #b #b)
  <br/>Underordnade och relaterade jurisdiktioner som ska anges som underavdelning. Namn på underordnad enhet ingår i den auktoriserade namnformen. Egenskapen används endast tillsammans med Är del av.
  <br/>```Exempel: Riksdagen```
<br/>Om namnformen består av fler än två led används plustecknet inom Namn på underordnad enhet för att skapa ny rad. Här anges ytterligare led av namnformen.
  <br/>```Exempel: Miljö- och jordbruksutskottet```

### Variant
* Variant (hasVariant = 410 #a #b och 410 #a #b #b)
  <br/>Här anges variantnamn och alternativa namnformer som stavningsvarianter, förkortningar etc. 
  <br/>OBS! Varianter ska inte göras till sökbara länkar. 
  <br/>```Namnform i ett led:```
  <br/>```Exempel: Borås kommun (Sverige)```
  
  ```Namnform i flera led:```
  <br/>```Exempel: Jurisdiktion/Är del av/Jurisdiktion/Namn: Sverige samt Jurisdiktion/Namn på underordnad enhet: Riksdagen ```
<br/>Om namnformen består av fler än två led används plutecknet vid Namn på underordnad enhet för att skapa ny rad. Här anges ytterligare led av namnformen.
  <br/>```Exempel: Jordbruksutskottet```
<br/> För att lägga till ytterligare Variant: Duplicera entiteten och redigera uppgifterna. Alternativt klicka på plustecknet vid egenskapen Variant och välj den typ av agent som behöver läggas till i rullmenyn.

### Se även
* Se även (seeAlso = 510)
  <br/>Här länkas mot annan agent som hör ihop med jurisdiktionen. Det kan t ex vara föregångare eller efterföljare.
  <br/>```Exempel: Göteborgs kommun (Sverige)```
  <br/>För att lägga till: Klicka på plustecknet vid egenskapen Se även, välj typen Jurisdiktion i sökrutan till vänster. Sök efter auktoriserad namnform och lägg till. (Finns ingen länkbar entitet behöver en skapas, dvs. Skapa ny Agent med länkning till den första. Avsluta och spara den ursprungliga först.)
  
### Beskrivning
* Beskrivning (description = 678)
  <br/>Används för att ange kortfattad historisk eller sammanfattande information om jurisdiktionen. Obligatorisk uppgift.
  <br/>```Exempel: Inrättat 1909. Namnbyte från Jordbruksutskottet till Miljö- och jordbruksutskottet från och med riksmötet 1989/99```

### Verksamhetens starttid  
* Verksamhetens starttid/Startdatum för aktivitetsperiod (activityStartDate = 046 #s)
  <br/>```Exempel: 1977```
  
### Verksamhetens sluttid    
* Verksamhetens sluttid/Slutdatum för aktivitetsperiod (activityEndDate = 046 #t)
  <br/>```Exempel: 1994```

### Identifikator
* Identifikator (identifiedBy = 024 #a #2)
  <br/>Identifikator t ex ISNI kan läggas till om tillgänglig. ISNI kan hämtas från t ex VIAF. 
  <br/>```Exempel: Värde: 0000000104839039 samt Typanmärkning: ISNI ```
 <br/>OBS! Om ingen Identifikator läggs till behöver egenskapen raderas. 

### Nationalitet
* Nationalitet/verksamhetsland (nationality = 043 #a)
  <br/>I mallen ligger nationalitetskoden för Sverige (e-sw---) förifylld. Vid behov kan denna ändras eller flera nationaliteter läggas till.
  <br/>```Exempel: e-no---```
  <br/>För att lägga till: Klicka på plustecknet vid egenskapen Nationalitet/verksamhetsland. Välj Nationalitet som typ, sök efter och välj önskad nationalitet. (Skapa lokal entitet används endast då det inte finns auktoriserad entitet att länka till).
  
## Ytterligare egenskaper att lägga till vid behov
Vid behov är det möjligt att lägga till egenskaper som inte ingår i mallen. Nya egenskaper läggs till med hjälp av plustecknet i verktygsmenyn.

### Tid for grundande
* Tid för grundande/Startdatum (establishDate = 046 #q)
  <br/>```Exempel: 1965```

### Tid för upphörande
* Tid för upphörande/Slutdatum (terminateDate = 046 #r)
  <br/>```Exempel: 2003```

### Verksamhetsområde
* Verksamhetsområde (fieldOfActivity = 372 #a #2)
  <br/>Ange verksamhetsområde för en jurisdiktionen vid behov.
  <br/>```Exempel: Miljörätt```
  <br/>Länka i första hand termen från en kontrollerad vokabulär som Svenska ämnesord. 
För att lägga till: Klicka på plustecknet vid egenskapen Verksamhetsområde, välj Allmänt ämnesord som typ, sök efter och välj önskad term. (Skapa lokal entitet används endast då det inte finns auktoriserad entitet att länka till).

### Språk
* Språk (associatedLanguage = 377 #a)
  <br/>Ange språk som jurisdiktionen använder vid behov.
  <br/>```Exempel: Engelska```
  <br/>Klicka på plustecknet vid egenskapen Språk. Välj Språk som typ, sök efter och välj önskat språk. (Skapa lokal entitet används endast då det inte finns auktoriserad entitet att länka till).
