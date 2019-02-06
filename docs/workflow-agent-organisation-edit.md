---
section: Hjälptexter agenter
title: Organisation - Redigera befintlig 
order: 65
date: 2019-02-06
tags:
- under arbete
- agenter
- auktoriteter
- organisationer
--- 

## Redigera befintlig: Agent - Organisation

<br/>Hjälptexten beskriver de egenskaper och klasser som finns i en befintlig auktoriserad agent och vilka egenskaper som bör läggas till. Under rubriken Innehåll finns de egenskaper klickbara som kan behöva redigeras eller läggas till i agenten. Vissa egenskaper kan vara obligatoriska att lägga till. Nya egenskaper läggs till med hjälp av den runda plustecknet i verktygsmenyn. Exemplen som finns i hjälptexten är fiktiva. 

Det är möjligt att berika en befintlig agentpost från mall. Klicka på det runda plustecknet i verktygsmenyn och välj: Berika från mall.

För information om katalogiseringsregler som gäller vid auktorisering, se 
[Anvisningar för katalogisering (RDA) - Auktoritetsarbete.](http://www.kb.se/rdakatalogisering/Auktoritetsarbete// "Anvisningar för katalogisering (RDA) - Auktoritetsarbete")

OBS! Glöm inte att redigera Adminmetadata och spara innan vidare navigation i verktyget. Verktyget är fortfarande under utveckling och viss åtskillnad från hjälptexten, tex avseende ordning på egenskaper kan förekomma.


### Innehåll

| [Adminmetadata](#adminmetadata) | [Agent](#agent) | 
| ------ | ----------- |
| [Katalogiseringsregler](#katalogiseringsregler) | [Namn](#namn) |
| [Katalogiseringsspråk](#katalogiseringsregler) | [Tid för grundande](#namn) |
| [Auktoritetskontrollnivå](#typ-av-auktoritetspost) | [Variant](#variant) |
| [**Egenskaper att lägga till i Adminmetadata**](#egenskaper-att-lagga-till-i-adminmetadata) | [**Egenskaper att lägga till i Agent**](#egenskaper-att-lagga-till-i-agent) | |
| [Konsulterad källa](#egenskaper-att-lagga-till-i-adminmetadata) | [Administrativ historik](#administrativ-historik) |
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
 

  
### Adminmetadata

Information av administrativ karaktär som är väsentlig för auktoriseringen i sig men inte är direkt förknippad med den auktoriserade namnformen.

#### Kontrollnummer
* Kontrollnummer (controllNumber = 001)
  <br/>LibrisID. Ändras ej.

#### Skapad av
* Skapad av (descriptionCreator = 040 ‡a)
 <br/>Förval: Sigel för skapare av agenten. Ändras ej.
 <br/>```Exempel: library/S```

#### Katalogiseringsregler
* Katalogiseringsregler (descriptionConventions = 040 ‡e)
 <br/>Förval: rda. Ändra vid behov.
 <br/>```Exempel: Kod: rda```

#### Katalogiseringsspråk  
* Katalogiseringsspråk (descriptionLanguage = 040 ‡b)
 <br/>```Exempel: Svenska```Ändras ej.
 <br/>Om egenskapen Katalogiseringsspråk saknas läggs denna till. Länka till entitet.

#### Beskrivningsnivå
* Beskrivningsnivå (encodingLevel = 000)
 <br/>```Exempel: Fullständig```
 <br/>Ändras ej.

#### Senast ändrad av
* Senast ändrad av (descriptionLastModifier)
 <br/>Förval: Sigel som gjort senaste ändring. Ändras automatiskt vid sparande.
 
#### Konverteringsdatum
 * Konverteringsdatum (generationDate = 000)
 <br/>Ändras ej.

#### Beskrivningsprocess 
 * Beskrivningsprocess (generationProcess = 000)
 <br/>Ändras ej.

#### Marc:headingMain 
* Marc:headingMain (marc:headingMain = 008/14)
 <br/>Ändras ej.

#### Typ av auktoritetspost
* Typ av auktoritetspost (marc:kindOfRecord = 008/9)
 <br/>Ändras ej.

#### Auktoritetskontrollnivå
* Auktoritetskontrollnivå (marc:level = 008/33)
 <br/>```Exempel: Kontrollerad/godkänd```
 <br/>Om "Preliminär (ej kontrollerad)" ändra till Kontrollerad/godkänd.

#### Numrering i serie
* Numrering i serie (marc:numberedSeries = 008/13)
 <br/>Ändras ej.

#### Differentiering av person     
* Differentiering av person (marc:personalName = 008/32)
  <br/>Ändras ej.

#### Uppdatering av posten  
* Uppdatering av posten (marc:recordUpdate = 008/31)
  <br/>Ändras ej.

#### Formatering av icke auktoriserade sökelement  
* Formatering av icke auktoriserade sökelement (marc:reference = 008/29)
 <br/>Ändras ej. 

#### Translitterering
* Translitterering (marc:romanization = 008/07)
 <br/>Ändras ej

#### Geografisk precisering 
* Geografisk precisering (marc:subdivision = 008/6)
 <br/>Ändras ej.  

#### Typ av underindelning
* Typ av underindelning (marc:subjectSubdivision = 008/7)
 <br/>Ändras ej.  

#### Typ av serie
* Typ av serie (marc:typeOfSeries = 008/12)
 <br/>Ändras ej.  

#### Poststatus
* Poststatus (recordStatus = 000)
  <br/>Ändras ej. Vid uppdatering ändras status automatiskt.

#### Samma sak som  
* Samma sak som (sameAs)
  <br/>```Exempel: auth/394287```.
  

### Egenskaper att lagga till i Adminmetadata

#### Konsulterad källa
* Konsulterad källa (sourceConsulted) innehåller Benämning (label = 670 ‡a) samt Uppgift från källa (citationNote = 670 ‡b)
  <br/>Ange källa och vid behov vilken uppgift som hämtats från källan. 
  <br/>Den resurs som föranleder auktoriseringen är en obligatorisk källa.
  <br/>```Exempel:```
  * ```Benämning: Fader okänd / Sveriges släktforskarförbund, 2016```
  * ```Benämning: Material i Kungliga bibliotekets vardagstryckssamling. Uppgift från källa: Namnformen: Stockholm vatten och avfall```
  
  Ytterligare relevanta källor kan vara.
  <br/>```Exempel:```
  * ```Benämning: Wikipedia (Svenska) 2018-04-24. Uppgift från källa: Startår 1886```
  * ```Benämning: Företagets webbplats 2018-08-17. Uppgift från källa: Datum för namnbyte: 1986```
  
  OBS! Förkortningen t.p., isbd-interpunktion och parenteser som inte behövs för förståelse/läsbarhet behöver inte anges.
  <br/>För att lägga till ytterligare källa: Klicka på plustecknet inom Konsulterad källa. Välj typ av konsulterad källa i rullmenyn. Vid val av "Källa vid belagd uppgift" finns möjlighet att ange såväl Benämning (källa) som Uppgift hämtad från källa.
  

#### Katalogisatorens anmärkning
 * Katalogisatörens anmärkning (cataloguersNote = 667 ‡a)
  <br/>Anmärkningar tänkta för kollegor inom Libriskollektivet. Det kan till exempel vara uppgifter som rör ändring av den auktoriserade namnformen. Motivera gärna ändringen och komplettera alltid med datum/sigel/signatur.
  <br/>```Exempel: Ändrat auktoriserad namnform från Xxx till Yyy 2010-01-03/S/UL/marjan```


### Agent

#### Namn
* Namn (name) (110 ‡a)
  <br/>Föredragen namnform som utgör den auktoriserade namnformen.
  <br/>```Exempel: Sveriges släktforskarförbund```

#### Tid för grundande  
* Tid för grundande/Startdatum (establishDate = 046 ‡q)
  <br/>```Exempel: 1886```

#### Variant
* Variant (hasVariant = 410 ‡a ‡b)
  <br/>Här anges variantnamn och alternativa namnformer som stavningsvarianter, förkortningar etc. Varianter ska inte göras till sökbara länkar. 
<br/>OBS! Det fungerar inte att göra Variant med namnformer i fler än två led i nuläget.
  <br/>```Exempel:```
   * ```Släktforskarförbundet```
   * ```Federation of Swedish Genealogical Societies```
   <br/>För att lägga till namn: Klicka på plustecknet vid egenskapen Variant, och välj typ t ex Organisation.
   
   ```Exempel på namnform i två led:```
  * ```Organisation/Är del av/Organisation/Namn: Stockholm University samt Organisation/Namn på underordnad enhet: Centre for Medieval Studies ```
  * ```Jurisdiktion/Är del av/Jurisdiktion/Namn: Sverige samt Jurisdiktion/Namn på underordnad enhet: Smittskyddsinstitutet```
  <br/>För att ange namnform i två led: klicka på plustecknet vid egenskapen Variant, och välj typ t ex Organisation. Klicka på plustecknet vid Organisation och lägg till egenskaperna Är del av samt Namn på underordnad enhet. Klicka på plustecknet vid egenskapen Är del av och välj Organisation i rullmenyn för Skapa lokal entitet.

#### Samma sak som
* Samma sak som (sameAs)
  <br/>```Exempel: resource/auth/394287```
    
    
### Egenskaper att lagga till i Agent


  #### Administrativ historik
* Administativ historik (has Historical Data = 678 ‡a)
  <br/>Anmärkning om administrativ historik är obligatorisk uppgift för Organisationer.
  <br/>```Exempel: Riksförbund för svenska släktforskare. Grundat 1886```

#### Nationalitet
* Nationalitet/verksamhetsland (nationality = 043 ‡a)
  <br/>Nationalitet/verksamhetsland för organisationen. Vid behov kan denna ändras eller flera nationaliteter läggas till.
  <br/>```Exempel: e-sw---```
  <br/>För att lägga till: Klicka på plustecknet vid egenskapen Nationalitet/verksamhetsland. Välj Nationalitet som typ vid sökning. Välj önskad nationalitet och klicka på plustecknet. (Skapa lokal entitet används endast då det inte finns auktoriserad entitet att länka till).

 #### Verksamhetsområde
* Verksamhetsområde (fieldOfActivity = 372 ‡a ‡2)
  <br/>Ange verksamhetsområde för en organisation vid behov.
  <br/>```Exempel: Släktforskning```
  <br/>Länka i första hand termen från en kontrollerad vokabulär som Svenska ämnesord. 
För att lägga till: Klicka på plustecknet vid egenskapen Verksamhetsområde, välj Allmänt ämnesord som typ vid sökning. Välj önskad term och klicka på plustecknet. (Skapa lokal entitet används endast då det inte finns auktoriserad entitet att länka till).

#### Identifikator
* Identifikator (identifiedBy = 024 ‡a ‡2)
  <br/>Identifikator t ex ISNI kan läggas till om tillgänglig. ISNI kan hämtas från t ex VIAF.
  <br/>```Exempel: Värde: 0000000104839039 samt Typanmärkning: ISNI ```


### Ytterligare egenskaper att lägga till vid behov

#### Tid för upphörande
* Tid för upphörande/Slutdatum (terminateDate = 046 ‡r)
  <br/>```Exempel: 2003```

#### Verksamhetens starttid
* Verksamhetens starttid/Startdatum för aktivitetsperiod (activityStartDate, 046 ‡s)
  <br/>```Exempel: 1886```

#### Verksamhetens sluttid    
* Verksamhetens sluttid/Slutdatum för aktivitetsperiod (activityEndDate, 046 ‡t)
  <br/>```Exempel: 1999``` 

#### Se även
* Se även (seeAlso = 510)
  <br/>Här länkas mot annan agent som hör ihop med organisationen. Det kan t ex vara föregångare eller efterföljare. 
  <br/>```Exempel: Föreningen Emigrantinstitutets vänner```
 <br/>För att lägga till: Klicka på plustecknet vid egenskapen Se även, välj typen Organisation i sökrutan till vänster. Sök efter auktoriserad namnform och klicka på plustecknet. (Om organisationen inte finns behöver en ny post skapas som kan länkas). Spara och avsluta innan ny organisation skapas. Använd befintlig mall för Skapa ny: Agent - Organisation).

#### Språk
* Språk (associatedLanguage = 377 ‡a)
  <br/>Ange språk som organisation använder vid behov.
  <br/>```Exempel: Engelska```
  <br/>Klicka på plustecknet vid egenskapen Språk. Välj Språk som typ vid sökning. Välj önskat språk och klicka på plustecknet. (Skapa lokal entitet används endast då det inte finns auktoriserad entitet att länka till).

#### Andra attribut for person- och organisationsnamn
* Andra attribut för person- och organisationsnamn (marc:hasOtherAttributes = 368 ‡a ‡2)
  <br/> Används vid behov som särskiljande tillägg för att beskriva typ av organisation. Hämta i första hand termen från en kontrollerad vokabulär som Svenska ämnesord.
  <br/>```Exempel: Herrgårdar sao```
  <br/>För att lägga till: Klicka på plustecknet inom egenskapen Andra attribut för person- och organisationsnamn, klicka på Skapa lokal entitet. Klicka på plustecknet inom den tillagda lokala entiteten. Välj egenskaperna Typ av organisation etc. samt Kod för kontrollerad vokabulär i de fall termen hämtas från en kontrollerad vokabulär. Skriv in aktuell term och listkod. Länkas ej.

#### Organisatorisk tillhörighet
 * Organisatorisk tillhörighet (hasAffiliation = 373 ‡a)
  <br/>Här är det möjligt att ange en samhörande organisation.
  <br/>```Exempel: Uppsala universitet``` 
  <br/>För att lägga till: Klicka på plustecknet vid egenskapen Organisatorisk tillhörighet, och skapa lokal entitet t ex organisation. Lägg sedan till benämning och skriv in uppgiften. OBS! Organisatorisk tillhörighet ska inte göras till sökbar länk.
