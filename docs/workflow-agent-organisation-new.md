---
section: Hjälptexter agenter
title: Organisation - Skapa ny 
order: 75
date: 2020-04-29
tags:
- under arbete
- agenter
- auktoriteter
- organisationer
--- 


# Organisation - Skapa ny
Hjälptexten beskriver de egenskaper som finns representerade i mallen för att skapa en ny agent av typen organisation. Egenskaper relevanta för organisation som är möjliga att lägga till men som inte finns i mallen beskrivs i slutet av hjälptexten.

## Innehåll
[Inledning](#inledning)

| [Adminmetadata](#adminmetadata) | [Agent](#agent) | 
| ------ | ----------- |
| [Skapad av](#adminmetadata) | [Agenttyp](#agent) |
| [Katalogiseringsregler](#adminmetadata) | [Namn](#agenttyp) |
| [Katalogisatörens anmärkning](#katalogiseringsregler) | [Namnform i flera led](#namnform-i-flera-led) |
| [Katalogiseringsspråk](#katalogiseringsregler) | [Variant](#variant) |
| [Konsulterad källa](#katalogiseringsregler) | [Se även](#variant)  |
| | [Beskrivning](#beskrivning) |
| | [Verksamhtens starttid](#verksamhetens-starttid)|
| | [Verksamhetens sluttid](#verksamhetens-sluttid) |
| | [Identifikator](#identifikator) |
| | [Nationalitet](#nationalitet) |
| | [**Ytterligare egenskaper att lägga till vid behov**](#administrativ-historik) |
| | [Tid för grundande](#tid-for-grundande) | |
| | [Tid för upphörande](#tid-for-grundande) | |
| | [Verksamhetsområde](#tid-for-grundande) | |
| | [Språk](#tid-for-grundande) | |
| | [Andra attribut för person- och organisationsnamn](#tid-for-grundande) | |
| | [Organisatorisk tillhörighet](#tid-for-grundande) | |
 

## Inledning
För information om katalogiseringsregler som gäller vid auktorisering, [se Anvisningar för katalogisering (RDA) - Auktoritetsarbete](http://www.kb.se/rdakatalogisering/Auktoritetsarbete// "Anvisningar för katalogisering (RDA) - Auktoritetsarbete").

OBS! Var noggrann vid sökning/testlänkning för att säkerställa att auktoriserad namnform inte redan finns. Glöm inte att redigera Adminmetadata och spara innan vidare navigation i verktyget.

Exemplen i hjälptexten är fiktiva.

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

### Katalogiseringsspråk
* Katalogiseringsspråk (descriptionLanguage = 040 #b)
 <br/>Förval: language/swe. Ändras ej

### Konsulterad källa
* Konsulterad källa (sourceConsulted) innehåller Benämning (label = 670 #a) samt Uppgift från källa (citationNote = 670 #b)
  <br/>Ange källa som Benämning och vid behov uppgift som hämtats från källan som Uppgift från källa. 
  <br/>Den resurs som föranleder auktoriseringen är en obligatorisk källa.
  <br/>```Exempel på obligatorisk källa:```
  * ```Benämning: Fader okänd / Sveriges släktforskarförbund, 2016``` 
    <br/>```Uppgift från källa: Sveriges släktforskarförbund```
    
  * ```Benämning: Material i Kungliga bibliotekets vardagstryckssamling```
    <br/>```Uppgift från källa: Namnformen: Stockholm vatten och avfall```
  
  <br/>```Exempel på kompletterande källa:```
  * ```Benämning: Wikipedia (Svenska) 2018-04-24```
    <br/>```Uppgift från källa: Startår 1886```
    
  * ```Benämning: Landstingsförbundets webbplats 2018-08-17``` 
    <br/>```Uppgift från källa: Datum för namnbyte: 1984```
   
  <br/>OBS! Förkortningen t.p., isbd-interpunktion och parenteser som inte behövs för förståelse/läsbarhet behöver inte anges.      
  <br/>För att lägga till: Klicka på plustecknet inom Konsulterad källa. Välj typen Källa vid belagd uppgift i rullmenyn.


## Agent

### Agenttyp
Ändras normalt sett ej. Upptäckta felaktigheter och/eller problem rapporteras till Auktoritetsgruppen.

### Namn   
* Namn 
  <br/>(name) (110 #a)
  <br/>Föredragen namnform som utgör den auktoriserade namnformen.
  <br/>```Exempel: Arbetslivscentrum```
  <br/>För namnform som består av flera led används istället egenskaperna Är del av tillsammans med Namn på underordnad enhet.
  
### Namnform i flera led
<br/>Namnform i flera led består av egenskaperna Är del av tillsammans med Namn på underordnad enhet
* Är del av/Namn (isPartOf/name = 110 2/- #a)
  <br/>Överordnat namn i en auktoriserad namnform som består av flera led. Egenskapen används endast tillsammans med Namn på underordnad enhet.
  <br/>```Exempel: Stockholms universitet```
  <br/>OBS! Egenskapen Är del av ska inte länkas.

* Namn på underordnad enhet (marc/subordinateUnit = 110 2/- #b och 110 2/- #b #b)
  <br/>Underordnade och relaterade organisationer som ska anges som underavdelning. Namn på underordnad enhet ingår i den auktoriserade namnformen. Egenskapen används endast tillsammans med Är del av.
  <br/>```Exempel: Centrum för medeltidsstudier```
<br/>Om namnformen består av fler än två led används plustecknet inom Namn på underordnad enhet för att skapa ny rad. Här anges ytterligare led av namnformen.
  <br/>```Exempel: Biblioteket```

### Variant
* Variant (hasVariant = 410 #a #b och 410 #a #b #b)
  <br/>Här anges variantnamn och alternativa namnformer som stavningsvarianter, förkortningar etc.
  <br/> OBS! Varianter ska inte göras till sökbara länkar.
  <br/>```Namnform i ett led:```
  <br/>```Exempel: Swedish Centre for Working Life```
   
  ```Namnform i flera led:```
  <br/>```Exempel: Organisation/Är del av/Organisation/Namn: Uppsala universitet samt Organisation/Namn på underordnad enhet: Institutionen för informationsteknologi```
<br/>Om namnformen består av fler än två led används plutecknet vid Namn på underordnad enhet för att skapa ny rad. Här anges ytterligare led av namnformen.
  <br/>```Exempel: Avdelningen för systemteknik```
<br/> För att lägga till ytterligare Variant: Duplicera entiteten och redigera uppgifterna. Alternativt klicka på plustecknet vid egenskapen Variant och välj den typ av Agent som behöver läggas till i rullmenyn.

### Se även
* Se även (seeAlso = 510)
  <br/>Här länkas mot annan agent som hör ihop med organisationen. Det kan t ex vara föregångare eller efterföljare.
  <br/>```Exempel: Institutet för arbetslivsforskning```
  <br/>För att lägga till: Klicka på plustecknet vid egenskapen Se även, välj typen Organisation i sökrutan till vänster. Sök efter auktoriserad namnform och lägg till. (Finns ingen länkbar entitet behöver en skapas, dvs. Skapa ny Agent med länkning till den första. Avsluta och spara den ursprungliga först.)
  
### Beskrivning
* Beskrivning (description = 678)
  <br/>Används för att ange kortfattad historisk eller sammanfattande information om organisationen. Obligatorisk uppgift.
  <br/>```Exempel: Statligt forskningsinstitut inom arbetslivsområdet. 1994 ändrades namnet till Institutet för arbetslivsforskning```
  
### Verksamhetens starttid  
* Verksamhetens starttid/Startdatum för aktivitetsperiod (activityStartDate = 046 #s)
  <br/>```Exempel: 1977```
  
### Verksamhetens sluttid    
* Verksamhetens sluttid/Slutdatum för aktivitetsperiod (activityEndDate = 046 #t)
  <br/>```Exempel: 1994```

### Identifikator
* Identifikator (identifiedBy = 024 #a #2)
  <br/>ISNI som identifikator är valfri uppgift men önskvärt om tillgänglig (uppgiften hämtas förslagsvis från [ISNI](http://www.isni.org/search)). 
  <br/>```Exempel: Värde: 0000000104839039 samt Typanmärkning: ISNI ```
 <br/>OBS! Om ingen Identifikator läggs till behöver egenskapen raderas. 
 
### Nationalitet
* Nationalitet/verksamhetsland (nationality = 043 #a)
  <br/>I mallen ligger nationalitetskoden för Sverige (e-sw---) förifylld. Vid behov kan denna ändras eller flera nationaliteter läggas till.
  <br/>```Exempel: e-uk---```
  <br/>För att lägga till: Klicka på plustecknet vid egenskapen Nationalitet/verksamhetsland. Välj Nationalitet som typ, sök efter och välj önskad nationalitet. (Skapa lokal entitet används endast då det inte finns auktoriserad entitet att länka till).

  
## Ytterligare egenskaper att lägga till vid behov
 <br/>Vid behov är det möjligt att lägga till egenskaper som inte ingår i mallen. Nya egenskaper läggs till med hjälp av plustecknet i verktygsmenyn.

### Tid for grundande
* Tid för grundande/Startdatum (establishDate = 046 #q)
  <br/>```Exempel: 1965```

### Tid för upphörande
* Tid för upphörande/Slutdatum (terminateDate = 046 #r)
  <br/>```Exempel: 2003```

### Verksamhetsområde
* Verksamhetsområde (fieldOfActivity = 372 #a #2)
  <br/>Ange verksamhetsområde för en organisation vid behov.
  <br/>```Exempel: Design```
  <br/>Länka i första hand termen från en kontrollerad vokabulär som Svenska ämnesord. 
För att lägga till: Klicka på plustecknet vid egenskapen Verksamhetsområde, välj Allmänt ämnesord som typ, sök efter och välj önskad term. (Skapa lokal entitet används endast då det inte finns auktoriserad entitet att länka till).

### Språk
* Språk (associatedLanguage = 377 #a)
  <br/>Ange språk som organisation använder vid behov.
  <br/>```Exempel: Engelska```
  <br/>Klicka på plustecknet vid egenskapen Språk. Välj Språk som typ, sök efter och välj önskat språk. (Skapa lokal entitet används endast då det inte finns auktoriserad entitet att länka till).

### Andra attribut for person- och organisationsnamn
* Andra attribut för person- och organisationsnamn (marc:hasOtherAttributes = 368 #a #2)
  <br/> Används vid behov som särskiljande tillägg för att beskriva typ av organisation. Hämta i första hand termen från en kontrollerad vokabulär som Svenska ämnesord. (Skapa lokal entitet används endast då det inte finns auktoriserad entitet att länka till).
  <br/>```Exempel: Herrgårdar sao```
  <br/>Lägg till egenskapen genom att klicka på plustecknet i verktygsmenyn.

### Organisatorisk tillhörighet
 * Organisatorisk tillhörighet (hasAffiliation = 373 #a)
  <br/>Här är det möjligt att ange en samhörande organisation.
  <br/>```Exempel: Uppsala universitet``` 
  <br/>För att lägga till: Klicka på plustecknet vid egenskapen Organisatorisk tillhörighet, och skapa lokal entitet. Lägg sedan till Benämning och skriv in uppgiften. OBS! Organisatorisk tillhörighet ska inte länkas.
