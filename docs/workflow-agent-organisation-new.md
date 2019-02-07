---
section: Hjälptexter agenter
title: Organisation - Skapa ny 
order: 55
date: 2019-02-07
tags:
- under arbete
- agenter
- auktoriteter
- organisationer
--- 


## Skapa ny: Agent - Organisation

Hjälptexten beskriver de egenskaper som finns representerade i mallen. Egenskaper relevanta för organisation som är möjliga att lägga till men som inte finns i mallen beskrivs i slutet av hjälptexten. Exemplen är fiktiva.

För information om katalogiseringsregler som gäller vid auktorisering, se 
[Anvisningar för katalogisering (RDA) - Auktoritetsarbete.](http://www.kb.se/rdakatalogisering/Auktoritetsarbete// "Anvisningar för katalogisering (RDA) - Auktoritetsarbete")

OBS! Var noggrann vid sökning/testlänkning för att säkerställa att auktoriserad namnform inte redan finns. Glöm inte att redigera Adminmetadata och spara innan vidare navigation i verktyget. Verktyget är fortfarande under utveckling och viss åtskillnad från hjälptexten, t ex avseende ordning på egenskaper kan förekomma.



### Innehåll

| [Adminmetadata](#adminmetadata) | [Agent](#agent) | 
| ------ | ----------- |
| [Skapad av](#skapad-av) | [Namn](#namn) |
| [Katalogiseringsregler](#katalogiseringsregler) | [Namnform i två led](#namn) |
| [Katalogiseringsspråk](#katalogiseringsregler) | [Verksamhtens starttid](#verksamhetens-starttid) |
| [Translitterering](#translitterering) | [Verksamhetens sluttid](#verksamhetens-sluttid) |
| [Poststatus](#poststatus) | [Administrativ historik](#administrativ-historik) |
| [Katalogisatörens anmärkning](#poststatus) | [Variant](#variant) |
| [Konsulterad källa](#poststatus) | [Se även](#variant) |
| [Uppdatering av posten](#uppdatering-av-posten) | [Identifikator](#identifikator) |
| [Differentiering av person](#differentiering-av-person) | [Nationalitet](#nationalitet) | |
| [Auktoritetskontrollnivå](#differentiering-av-person) | [**Valbara egenskaper att lägga till i Agent**](#nationalitet) |
| [Beskrivningsnivå](#differentiering-av-person) | [Tid för grundande](#tid-for-grundande) | |
| | [Tid för upphörande](#tid-for-grundande) | |
| | [Verksamhetsområde](#tid-for-grundande) | |
| | [Språk](#tid-for-grundande) | |
| | [Andra attribut för person- och organisationsnamn](#tid-for-grundande) | |
| | [Organisatorisk tillhörighet](#tid-for-grundande) | |
 

  
### Adminmetadata

Information av administrativ karaktär som är väsentlig för auktoriseringen i sig men inte är direkt förknippad med den auktoriserade namnformen.

#### Skapad av
* Skapad av (descriptionCreator = 040 ‡a)
 <br/>Förval: inloggad sigel. Ändras ej.
 <br/>```Exempel: library/S```

#### Katalogiseringsregler
* Katalogiseringsregler (descriptionConventions = 040 ‡e)
 <br/>Förval: rda. Ändra vid behov.
 <br/>```Exempel: Kod: rda```

#### Katalogiseringsspråk
* Katalogiseringsspråk (descriptionLanguage = 040 ‡b)
 <br/>```Exempel: Svenska```Ändras ej.

#### Translitterering
* Translitterering (marc:romanization = 008/07)
 <br/>Ändras ej.

#### Poststatus
* Poststatus (recordStatus = = 000)
  <br/>Val i meny. Välj Ny post vid skapande av ny auktoriserad agent. Vid uppdatering ändras status automatiskt.

#### Katalogisatorens anmärkning
* Katalogisatörens anmärkning (cataloguersNote = 667 ‡a)
  <br/>Anmärkningar tänkta för kollegor inom Libriskollektivet. Det kan till exempel vara uppgifter som rör ändring av den auktoriserade namnformen. Motivera gärna ändringen och komplettera alltid med datum/sigel/signatur. Det är önskvärt att alla nya auktoriserade namnformer kompletteras med datum/sigel/signatur. 
  <br/>```Exempel:```
  * ```2018-08-28/S/NB/carbac```
  * ```Ändrat auktoriserad namnform från Xxx till Yyy 2010-01-03/S/UL/marjan```

#### Konsulterad källa
* Konsulterad källa (sourceConsulted) innehåller Benämning (label = 670 ‡a) samt Uppgift från källa (citationNote = 670 ‡b)
  <br/>Ange källa och vid behov vilken uppgift som hämtats från källan. 
  <br/>Den resurs som föranleder auktoriseringen är en obligatorisk källa.
  <br/>```Exempel på obligatorisk källa:```
  * ```Benämning: Fader okänd / Sveriges släktforskarförbund, 2016. Uppgift från källa: Sveriges släktforskarförbund```
  * ```Benämning: Material i Kungliga bibliotekets vardagstryckssamling. Uppgift från källa: Namnformen: Stockholm vatten och avfall```
  
  <br/>```Exempel på kompletterande källa:```
  * ```Benämning: Wikipedia (Svenska) 2018-04-24. Uppgift från källa: Startår 1886```
  * ```Benämning: Landstingsförbundets webbplats 2018-08-17. Uppgift från källa: Datum för namnbyte: 1984```
  
  OBS! Förkortningen t.p., isbd-interpunktion och parenteser som inte behövs för förståelse/läsbarhet behöver inte anges.
  <br/>För att lägga till ytterligare källa: Klicka på plustecknet inom Konsulterad källa. Välj typ av konsulterad källa i rullmenyn. Vid val av "Källa vid belagd uppgift" finns möjlighet att ange såväl Benämning (källa) som Uppgift hämtad från källa.
   
 
#### Uppdatering av posten
* Uppdatering av posten (marc:recordUpdate = 008/31)
  <br/>Ändras ej.

#### Differentiering av person
* Differentiering av person (marc:personalName = 008/32)
  <br/>Ändras ej.

#### Auktoritetskontrollnivå
* Auktoritetskontrollnivå (marc:level = 008/33)
  <br/>Ändras ej.
 
#### Beskrivningsnivå 
 * Beskrivningsnivå (encodingLevel)
  <br/>Ändras ej.
   

### Agent

#### Namn   
* Namn 
  <br/>(name) (110 ‡a)
  <br/>Föredragen namnform som utgör den auktoriserade namnformen.
  <br/>```Exempel: Arbetslivscentrum```
  <br/>För namnformer som består av överordnad och underordnad enhet används istället egenskaperna Är del av tillsammans med Namn på underordnad enhet.
  
#### Namnform i två led 
* Är del av/Namn
  <br/>(isPartOf/name = 110 2/- ‡a)
  <br/>Överordnat namn i en auktoriserad namnform som består av flera led. Egenskapen används endast tillsammans med Namn på underordnad enhet.
  <br/>```Exempel: Stockholms universitet```
  
* Namn på underordnad enhet (marc/subordinateUnit =110 2/- ‡b)
  <br/>Underordnade och relaterade organisationer som ska anges som underavdelning. Namn på underordnad enhet ingår i den auktoriserade namnformen. Egenskapen används endast tillsammans med Är del av.
  <br/>```Exempel: Centrum för medeltidsstudier```
<br/>OBS! Det fungerar inte att göra Organisation med namnform i fler än två led i nuläget.
  
#### Verksamhetens starttid  
* Verksamhetens starttid/Startdatum för aktivitetsperiod (activityStartDate = 046 ‡s)
  <br/>```Exempel: 1977```
  
#### Verksamhetens sluttid    
* Verksamhetens sluttid/Slutdatum för aktivitetsperiod (activityEndDate = 046 ‡t)
  <br/>```Exempel: 1994```
  
#### Administrativ historik
* Administativ historik (hasHistoricalData = 678 ‡a)
  <br/>Anmärkning om administrativ historik.
  <br/>```Exempel: Statligt forskningsinstitut inom arbetslivsområdet. 1994 ändrades namnet till Institutet för arbetslivsforskning```

#### Variant
* Variant (hasVariant = 410 ‡a ‡b)
  <br/>Här anges variantnamn och alternativa namnformer som stavningsvarianter, förkortningar etc. Varianter ska inte göras till sökbara länkar. 
<br/>OBS! Det fungerar inte att göra Variant med namn i fler än två led i nuläget.
  <br/>```Exempel:```
   * ```ALC```
   * ```Swedish Centre for Working Life```
   <br/>För att lägga till namn: Klicka på plustecknet vid egenskapen Variant, och välj typ t ex Organisation.
   
  ```Exempel på namnform i två led:```
  * ```Organisation/Är del av/Organisation/Namn: Stockholm University samt Organisation/Namn på underordnad enhet: Centre for Medieval Studies ```
  * ```Jurisdiktion/Är del av/Jurisdiktion/Namn: Sverige samt Jurisdiktion/Namn på underordnad enhet: Smittskyddsinstitutet```
  <br/>För att ange namnform i två led: klicka på plustecknet vid egenskapen Variant, och välj typ t ex Organisation. Klicka på plustecknet vid Organisation och lägg till egenskaperna Är del av samt Namn på underordnad enhet. Klicka på plustecknet vid egenskapen Är del av och välj Organisation i rullmenyn för Skapa lokal entitet.

#### Se även
* Se även (seeAlso = 510)
  <br/>Här länkas mot annan agent som hör ihop med organisationen. Det kan t ex vara föregångare eller efterföljare.
  <br/>```Exempel: Institutet för arbetslivsforskning```
  <br/>För att lägga till: Klicka på plustecknet vid egenskapen Se även, välj typen Organisation i sökrutan till vänster. Sök efter auktoriserad namnform och klicka på plustecknet. (Om organisationen inte finns behöver en ny post skapas som kan länkas). Spara och avsluta innan ny organisation skapas. Använd befintlig mall för Skapa ny: Agent - Organisation).

#### Identifikator
* Identifikator (identifiedBy = 024 ‡a ‡2)
  <br/>Identifikator t ex ISNI kan läggas till om tillgänglig. ISNI kan hämtas från t ex VIAF. 
  <br/>```Exempel: Värde: 0000000104839039 samt Typanmärkning: ISNI ```
 <br/>OBS! Om ingen Identifikator läggs till behöver egenskapen raderas med papperskorgen.
  

#### Nationalitet
* Nationalitet/verksamhetsland (nationality = 043 ‡a)
  <br/>I mallen ligger nationalitetskoden för Sverige (e-sw---) förifylld. Vid behov kan denna ändras eller flera nationaliteter läggas till.
  <br/>```Exempel: e-uk---```
  <br/>För att lägga till: Klicka på plustecknet vid egenskapen Nationalitet/verksamhetsland. Välj Nationalitet som typ vid sökning. Välj önskad nationalitet och klicka på plustecknet. (Skapa lokal entitet används endast då det inte finns auktoriserad entitet att länka till).

  
### Valbara egenskaper att lägga till i Agent
 <br/>Vid behov är det möjligt att lägga till egenskaper som inte ingår i mallen. Nya egenskaper läggs till med hjälp av det runda plustecknet i verktygsmenyn.

#### Tid for grundande
* Tid för grundande/Startdatum (establishDate = 046 ‡q)
  <br/>```Exempel: 1965```

#### Tid för upphörande
* Tid för upphörande/Slutdatum (terminateDate = 046 ‡r)
  <br/>```Exempel: 2003```

#### Verksamhetsområde
* Verksamhetsområde (fieldOfActivity = 372 ‡a ‡2)
  <br/>Ange verksamhetsområde för en organisation vid behov.
  <br/>```Exempel: Design```
  <br/>Länka i första hand termen från en kontrollerad vokabulär som Svenska ämnesord. 
För att lägga till: Klicka på plustecknet vid egenskapen Verksamhetsområde, välj Allmänt ämnesord som typ vid sökning. Välj önskad term och klicka på plustecknet. (Skapa lokal entitet används endast då det inte finns auktoriserad entitet att länka till).

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
