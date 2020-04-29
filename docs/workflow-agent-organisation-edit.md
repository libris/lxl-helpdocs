---
section: Hjälptexter agenter
title: Organisation - Redigera befintlig 
order: 76
date: 2020-04-29
tags:
- under arbete
- agenter
- auktoriteter
- organisationer
--- 

# Organisation - Redigera befintlig
Hjälptexten beskriver de egenskaper och klasser som finns i en befintlig auktoriserad agent av typen organisation och vilka egenskaper som bör läggas till. Under rubriken Innehåll finns de egenskaper klickbara som kan behöva redigeras eller läggas till i agenten. 

## Innehåll
[Inledning](#inledning)

| [Adminmetadata](#adminmetadata) | [Agent](#agent) | 
| ------ | ----------- |
| [Katalogiseringsregler](#katalogiseringsregler) | [Agenttyp](#agent) |
| [Katalogiseringsspråk](#katalogiseringsregler) | [Namn](#agenttyp) |
| | [Tid för grundande](#namn) |
| | [Variant](#variant) |
| [**Egenskaper att lägga till i Adminmetadata**](#egenskaper-att-lagga-till-i-adminmetadata) | [**Egenskaper att lägga till i Agent**](#egenskaper-att-lagga-till-i-agent) | |
| [Konsulterad källa](#egenskaper-att-lagga-till-i-adminmetadata) | [Beskrivning](#beskrivning) |
| [Katalogisatörens anmärkning](#egenskaper-att-lagga-till-i-adminmetadata) | [Nationalitet](#nationalitet) | |
| |[Verksamhetsområde](#nationalitet) |
| | [Identifikator](#identifikator) | |
| | [**Ytterligare egenskaper att lägga till vid behov**](#identifikator) |
| | [Tid för upphörande](#identifikator) |
| | [Verksamhtens starttid](#verksamhetens-starttid) |
| | [Verksamhetens sluttid](#verksamhetens-sluttid) | |
| | [Se även](#verksamhetens-sluttid) | |
| | [Språk](#verksamhetens-sluttid) | |
| | [Andra attribut för person- och organisationsnamn](#verksamhetens-sluttid) | |
| | [Organisatorisk tillhörighet](#verksamhetens-sluttid) | |
 
## Inledning
Vissa egenskaper kan vara obligatoriska att lägga till. Nya egenskaper läggs till med hjälp av den runda plustecknet i verktygsmenyn. Exemplen som finns i hjälptexten är fiktiva. 

Det är möjligt att berika en befintlig agentpost från mall. Klicka på det runda plustecknet i verktygsmenyn och välj: Berika från mall.

För information om katalogiseringsregler som gäller vid auktorisering, [se Anvisningar för katalogisering (RDA) - Auktoritetsarbete](http://www.kb.se/rdakatalogisering/Auktoritetsarbete// "Anvisningar för katalogisering (RDA) - Auktoritetsarbete").

  
## Adminmetadata
Information av administrativ karaktär som är väsentlig för auktoriseringen i sig men inte är direkt förknippad med den auktoriserade namnformen.

### Kontrollnummer
* Kontrollnummer (controllNumber = 001)
  <br/>LibrisID. Ändras ej.

### Skapad av
* Skapad av (descriptionCreator = 040 #a)
 <br/>Förval: Sigel för skapare av agenten. Ändras ej.
 <br/>```Exempel: library/S```

### Katalogiseringsregler
* Katalogiseringsregler (descriptionConventions = 040 #e)
 <br/>Förval: rda. Ändra vid behov.
 <br/>```Exempel: Kod: rda```

### Katalogiseringsspråk  
* Katalogiseringsspråk (descriptionLanguage = 040 #b)
 <br/>```Exempel: Svenska```
 <br/>Ändras ej. Om egenskapen Katalogiseringsspråk saknas läggs denna till. Länka till entitet.

### Senast ändrad av
* Senast ändrad av (descriptionLastModifier)
 <br/>Förval: Sigel som gjort senaste ändring. Ändras automatiskt vid sparande.
 
### Konverteringsdatum
 * Konverteringsdatum (generationDate = 000)
 <br/>Ändras ej.

### Beskrivningsprocess 
 * Beskrivningsprocess (generationProcess = 000)
 <br/>Ändras ej.

### Poststatus
* Poststatus (recordStatus = 000)
  <br/>Ändras ej. Vid uppdatering ändras status automatiskt.

### Samma sak som  
* Samma sak som (sameAs)
  <br/>```Exempel: auth/394287```.
  

## Egenskaper att lagga till i Adminmetadata


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

### Katalogisatorens anmärkning
 * Katalogisatörens anmärkning (cataloguersNote = 667 #a)
  <br/>Anmärkningar tänkta för kollegor inom Libriskollektivet. Det kan t.ex. vara uppgifter som rör ändring av den auktoriserade namnformen. Motivera gärna ändringen och komplettera alltid med datum/sigel/signatur.
  <br/>```Exempel: Ändrat auktoriserad namnform från Xxx till Yyy 2010-01-03/S/UL/marjan```


## Agent

### Agenttyp
Ändras normalt sett ej. Upptäckta felaktigheter och/eller problem rapporteras till Auktoritetsgruppen.

### Namn
* Namn (name) (110 #a)
  <br/>Föredragen namnform som utgör den auktoriserade namnformen.
  <br/>```Exempel: Sveriges släktforskarförbund```

### Tid för grundande  
* Tid för grundande/Startdatum (establishDate = 046 #q)
  <br/>```Exempel: 1886```

### Variant
* Variant (hasVariant = 410 #a #b #b)
  <br/>Här anges variantnamn och alternativa namnformer som stavningsvarianter, förkortningar etc.
  <br/> OBS! Varianter ska inte länkas.
  <br/>```Namnform i ett led```
  <br/>```Exempel: Släktforskarförbundet```
    
  ```Namnform i flera led:```
  <br/>```Exempel: Organisation/Är del av/Organisation/Namn: Uppsala universitet samt Organisation/Namn på underordnad enhet: Institutionen för informationsteknologi```
<br/>Om namnformen består av fler än två led används plutecknet vid Namn på underordnad enhet för att skapa ny rad. Här anges ytterligare led av namnformen.
  <br/>```Exempel: Avdelningen för systemteknik```
<br/> För att lägga till ytterligare Variant: Duplicera entiteten och redigera uppgifterna. Alternativt klicka på plustecknet vid egenskapen Variant och välj den typ av Agent som behöver läggas till i rullmenyn.

### Samma sak som
* Samma sak som (sameAs)
  <br/>```Exempel: resource/auth/394287```
    
    
## Egenskaper att lagga till i Agent


### Beskrivning
* Beskrivning (description = 678)
  <br/>Används för att ange kortfattad historisk eller sammanfattande information om organisationen. Obligatorisk uppgift.
  <br/>```Exempel: Riksförbund för svenska släktforskare. Grundat 1886```

### Nationalitet
* Nationalitet/verksamhetsland (nationality = 043 #a)
  <br/>Nationalitet/verksamhetsland för organisationen. Vid behov kan denna ändras eller flera nationaliteter läggas till.
  <br/>```Exempel: e-sw---```
  <br/>För att lägga till: Klicka på plustecknet vid egenskapen Nationalitet/verksamhetsland. Välj Nationalitet som typ,sök efter och välj önskad nationalitet. (Skapa lokal entitet används endast då det inte finns auktoriserad entitet att länka till).

### Verksamhetsområde
* Verksamhetsområde (fieldOfActivity = 372 #a #2)
  <br/>Ange verksamhetsområde för en organisation vid behov.
  <br/>```Exempel: Släktforskning```
  <br/>Länka i första hand termen från en kontrollerad vokabulär som Svenska ämnesord. 
För att lägga till: Klicka på plustecknet vid egenskapen Verksamhetsområde, välj Allmänt ämnesord som typ, sök efter och välj önskad term. (Skapa lokal entitet används endast då det inte finns auktoriserad entitet att länka till).

### Identifikator
* Identifikator (identifiedBy = 024 #a #2)
  <br/>ISNI som identifikator är valfri uppgift men önskvärt om tillgänglig (uppgiften hämtas förslagsvis från [ISNI](http://www.isni.org/search)). 
  <br/>```Exempel: Värde: 0000000104839039 samt Typanmärkning: ISNI ```


## Ytterligare egenskaper att lägga till vid behov

### Tid för upphörande
* Tid för upphörande/Slutdatum (terminateDate = 046 #r)
  <br/>```Exempel: 2003```

### Verksamhetens starttid
* Verksamhetens starttid/Startdatum för aktivitetsperiod (activityStartDate, 046 #s)
  <br/>```Exempel: 1886```

### Verksamhetens sluttid    
* Verksamhetens sluttid/Slutdatum för aktivitetsperiod (activityEndDate, 046 #t)
  <br/>```Exempel: 1999``` 

### Se även
* Se även (seeAlso = 510)
  <br/>Här länkas mot annan agent som hör ihop med organisationen. Det kan t.ex. vara föregångare eller efterföljare. 
  <br/>```Exempel: Föreningen Emigrantinstitutets vänner```
 <br/>För att lägga till: Klicka på plustecknet vid egenskapen Se även, välj typen Organisation i sökrutan till vänster. Sök efter auktoriserad namnform och lägg till. (Finns ingen länkbar entitet behöver en skapas, dvs. Skapa ny Agent med länkning till den första. Avsluta och spara den ursprungliga först.)
 
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
