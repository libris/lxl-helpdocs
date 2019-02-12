---
section: Hjälptexter agenter
title: Person - Skapa ny 
order: 40
date: 2019-02-12
tags:
- agenter
- auktoriteter
- under arbete
---

## Skapa ny: Agent - Person
Hjälptexten beskriver de egenskaper och klasser som finns representerade i mallen. Ett urval av egenskaper relevanta för person som är möjliga att lägga till men som inte finns i mallen beskrivs i slutet av hjälptexten. 

För information om katalogiseringsregler som gäller vid auktorisering, se 
[Anvisningar för katalogisering (RDA) - Auktoritetsarbete.](http://www.kb.se/rdakatalogisering/Auktoritetsarbete// "Anvisningar för katalogisering (RDA) - Auktoritetsarbete")

OBS! Var noggrann vid sökning/testlänkning för att säkerställa att auktoriserad namnform inte redan finns. Glöm inte att redigera Adminmetadata och spara innan vidare navigation i verktyget. Verktyget är fortfarande under utveckling och viss åtskillnad från hjälptexten, t.ex. avseende ordning på egenskaper kan förekomma. 

Exemplet nedan baseras på den auktoriserade namnformen Lagerlöf, Selma, 1858-1940 (i de fall det är möjligt och relevant). Tillägg är fiktiva, enbart för att exemplifiera.


### Innehåll

| [Adminmetadata](#adminmetadata) | [Agent](#agent) | 
| ------ | ----------- |
| [Skapad av](#skapad-av) | [Efternamn](#efternamn) |
| [Katalogiseringsregler](#katalogiseringsregler) | [Förnamn](#efternamn) |
| [Translitterering](#translitterering) | [Födelse- och/eller dödstid](#efternamn) |
| [Typ av auktoritetspost](#typ-av-auktoritetspost) | [Födelsedatum](#efternamn) |
| [Marc:headingMain](#typ-av-auktoritetspost) | [Dödsdatum](#efternamn) |
| [Katalogisatörens anmärkning](#typ-av-auktoritetspost) | [Variant](#variant) |
| [Konsulterad källa](#typ-av-auktoritetspost) | [Se även](#variant) |
| [Poststatus](#poststatus) |[Verksamhetsområde](#verksamhetsomrade) |
| [Uppdatering av posten](#uppdatering-av-posten) | [Har yrke eller sysselsättning](#verksamhetsomrade) |
| [Differentiering av person](#differentiering-av-person) | [Identifikator](#identifikator) |
| [Auktoritetskontrollnivå](#differentiering-av-person) | [Nationalitet](#nationalitet) |
| [Katalogiseringsspråk](#differentiering-av-person) | [**Ytterligare egenskaper att lägga till vid behov**](#beskrivningsniva) |
| [Beskrivningsnivå](#beskrivningsniva) | [Namn](#namn) | 
| | [Fullständigare namnform](#namn) | 
| | [Biografiska uppgifter](#biografiska-uppgifter) |
| | [Titel eller övrig beteckning](#biografiska-uppgifter) |
| | [Andra attribut för person- och organisationsnamn](#biografiska-uppgifter) |
| | [Ordningstal](#ordningstal) | 
| | [Språk](#ordningstal) | 
| | [Organisatorisk tillhörighet](#ordningstal) | |


### Adminmetadata
Information av administrativ karaktär som är väsentlig för auktoriseringen i sig men inte är direkt förknippad med den auktoriserade namnformen.

#### Kontrollnummer
* Kontrollnummer (controlNumber = 001)
  <br/>Libris-ID. Genereras automatiskt vid sparande. Ändras ej.

#### Skapad av
* Skapad av (descriptionCreator = 040 ‡a)
  <br/>Förval: Inloggad sigel. Ändras ej.
  <br/>```Exempel: S```

#### Katalogiseringsregler
* Katalogiseringsregler (descriptionConventions = 040 ‡e)
  <br/>Förval: rda. Ändra vid behov. 
  <br/>```Exempel:```
  * ```Kod: rda```

#### Translitterering
* Translitterering (marc:romanization = 008/07)
  <br/>Ändras ej.

#### Typ av auktoritetspost
* Typ av auktoritetspost (marc:kindOfRecord = 008/09)
  <br/>Ändras ej.

#### Marc:headingMain
* Marc:headingMain (008/14)
  <br/>Ändras ej.

#### Katalogisatörens anmärkning
* Katalogisatörens anmärkning (cataloguersNote = 667 ‡a)
  <br/>Anmärkningar tänkta för kollegor inom Libriskollektivet. Det är önskvärt att alla nya auktoriserade namnformer kompletteras med datum/sigel/signatur. I övrigt kan det t.ex. vara uppgifter som rör ändring av den auktoriserade namnformen. Motivera gärna ändringen och komplettera alltid med datum/sigel/signatur. 
  <br/>```Exempel:``` 
  * ```2018-08-27 S/MSS/evaann```
  * ```Författaren vill inte ha sitt födelseår kopplat till den auktoriserade namnformen. Enligt e-post 2017-05-12, S/NB/annbjo```

#### Konsulterad källa
* Konsulterad källa (sourceConsulted) innehåller Benämning (label = 670 ‡a) samt Uppgift från källa (citationNote = 670 ‡b)
  <br/>Ange källa och vid behov vilken uppgift som hämtats från källan. Den resurs som föranleder auktoriseringen är obligatorisk källa. 
  <br/>```Exempel på obligatorisk källa:``` 
  * ```Benämning: Jerusalem / Selma Lagerlöf, 1901 Uppgift från källa: Lagerlöf, Selma```
  * ```Benämning: Harry Potter och hemligheternas kammare / J. K. Rowling, 2000 Uppgift från källa: Rowling, J. K.```

  <br/>```Exempel på kompletterande källa:``` 
  * ```Benämning: NE 2018-04-12. Uppgift från källa: Levnadstid 1848-1920```
  * ```Benämning: NE 2016-10-01 Uppgift från källa: Fullständigare namnform: Joanne Kathleen```
  * ```Benämning: Wikipedia (svenska) 2018-04-12 Uppgift från källa: Dödstid 1867```
  * ```Benämning: Birthday. Uppgift från källa: Född: 1988```
  * ```Benämning: LC i VIAF 2017-11-21 Uppgift från källa: Proclus, approximately 410-485```
  <br/>OBS! Förkortningen t.p., isbd-interpunktion och parenteser som inte behövs för förståelse/läsbarhet behöver inte anges.      
  <br/>För att lägga till: Klicka på plustecknet inom Konsulterad källa. Välj typ av konsulterad källa i rullmenyn. 
Vid val av "Källa vid belagd uppgift" finns möjlighet att ange såväl Benämning (källa) som Uppgift hämtad från källa.

#### Poststatus
* Poststatus (recordStatus = 000/Leader/)
  <br/>Val i meny. Välj Ny post vid skapande av ny auktoriserad agent. Vid uppdatering ändras status automatiskt.

#### Uppdatering av posten
* Uppdatering av posten (marc:recordUpdate = 008/31)
  <br/>Ändras ej.

#### Differentiering av person
* Differentiering av person (marc:personalName = 008/32)
  <br/>Ändras ej.

#### Auktoritetskontrollnivå
* Auktoritetskontrollnivå (marc:level = 008/33)
  <br/>Ändras ej.

#### Katalogiseringsspråk
* Katalogiseringsspråk (descriptionLanguage = 040 ‡b)
  <br/>Förval: language/swe. Ändras ej.

#### Beskrivningsniva
* Beskrivningsnivå
  <br/>Förval: Fullständig. Ändras ej.


### Agent
Beskrivning av agenten som ska auktoriseras. 

#### Efternamn
* Efternamn (FamilyName = 100 1/- ‡a)
  <br/>Enkelt eller sammansatt släktnamn/efternamn. Föredragen namnform som tillsammans med förnamn utgör den auktoriserade namnformen.
  <br/>```Exempel:```
  * ```Enkelt efternamn: Lagerlöf```
  * ```Sammansatt släktnamn (dubbla efternamn): Lindmark Månsson```
  <br/>Om flera efternamn ska ingå i den auktoriserade namnformen skrivs de direkt efter varandra.

#### Förnamn
* Förnamn (GivenName = 100 ‡a)
  <br/>Förnamn som tillsammans med efternamn utgör den auktoriserade namnformen. 
  <br/>```Exempel:```
  * ```Enkelt förnamn: Selma```
  * ```Flera förnamn: Helena Johanna```
  <br/>Om flera förnamn ska ingå i den auktoriserade namnformen skrivs de direkt efter varandra.

#### Födelse- och/eller dödstid
* Födelse- och/eller dödstid (lifeSpan = 100 ‡d)
  <br/>Årtal används i första hand som särskiljande tillägg för personer. 
  <br/>```Exempel:```
  * ```1858-1940```
  * ```1968-```

#### Födelsedatum
* Födelsedatum (birthDate = 046 ‡f)
  <br/>Ange fullständigt födelsedatum om uppgiften är känd. I annat fall, ange känd uppgift.
  <br/> ```Exempel:```
  * ```18581120```
  * ```1902```

#### Dödsdatum
* Dödsdatum (deathDate = 046 ‡g)
  <br/>Ange fullständigt dödsdatum om uppgiften är känd. I annat fall, ange känd uppgift.
  <br/>```Exempel:```
  * ```19400316```
  * ```1977```

#### Variant
* Variant (hasVariant = 400 ‡a ‡d)
  <br/>Här anges variantnamn och alternativa namnformer samt födelse- och/eller dödstid. Hit hör stavningsvaranter, förkortningar, ändringar till följd av namnbyten, hänvisning från det andra ledet av sammansatt efternamn etc. Variantnamn kan t.ex. finnas i referenskällor eller i den bibliografiska informationen. Egenskapen upprepas om flera variantnamn behöver läggas till. 
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

#### Se även
* Se även (seeAlso = 500 ‡a ‡d)
  <br/>Här länkas se även-hänvisning till en annan auktoriserad namnform, t.ex. till en pseudonym eller då en upphovsperson är verksam under mer än en identitet. T.ex. Smith, Rosamund, 1938- som se-hänvisning från den auktoriserade namnformen för Oates, Joyce Carol, 1938-.
  <br/>```Exempel:``` 
  * ```Efternamn: Smith``` 
  <br/>``` Förnamn: Rosamond``` 
  <br/>```Födelse- och/eller dödstid: 1938-``` 
  <br/>För att lägga till: Klicka på plustecknet inom egenskapen Se även, välj typen Person. Sök efter auktoriserad namnform och lägg till. (Finns ingen länkbar entitet behöver en skapas, dvs. Skapa ny Agent med länkning till den första. Avsluta och spara den ursprungliga först.)

#### Verksamhetsomrade
* Verksamhetsområde (fieldOfActivity = 372)
  <br/>Personens verksamhetsområde beskriver vad personen är intresserad av eller ägnar sig åt och det behöver inte ha med yrkesutövning att göra. Hämta i första hand termen från en kontrollerad vokabulär som Svenska ämnesord och länka. 
   <br/>```Exempel: Fågelskådning```
   <br/>För att lägga till: Klicka på plustecknet inom egenskapen Verksamhetsområde, välj Allmänt ämnesord som typ, sök efter och välj önskad term. (Skapa lokal entitet används endast då det inte finns auktoriserad entitet att länka till.)

#### Har yrke eller sysselsättning
* Har yrke eller sysselsättning (hasOccupation = 374)
   <br/>Ange yrke eller sysselsättning om det behövs för att skilja en person från en annan, t.ex. när en persons födelsetid eller dödstid inte är tillgängligt. Hämta i första hand termen från en kontrollerad vokabulär som Svenska ämnesord och länka.
   <br/>```Exempel:```
   * ```Romanförfattare```
   * ```Översättare```
   <br/>För att lägga till: Klicka på plustecknet inom egenskapen Har yrke eller sysselsättning, välj Allmänt ämnesord som typ, sök efter och välj önskad term. (Skapa lokal entitet används endast då det inte finns auktoriserad entitet att länka till.)

#### Identifikator
* Identifikator (identifiedBy = 024 ‡a)
  <br/>ISNI som identifikator är valfri uppgift men önskvärt om tillgänglig (uppgiften hämtas förslagsvis från VIAF). 
  <br/>```Exempel:```
  * ```Värde: 0000000121339888```
  * ```Typanmärkning: isni```
  <br/>För att lägga till: Klicka på plustecknet i verktygsmenyn. Välj typen Identifikator i rullgardinsmenyn. Klicka på plustecknet inom Identifikator, sök efter och lägg till Typanmärkning.

#### Nationalitet
* Nationalitet/verksamhetsland (nationality = 043)
  <br/>I mallen ligger nationalitetskoden för Sverige (e-sw---) förifylld. Vid behov kan denna raderas. 
  <br/>För att lägga till: Klicka på plustecknet inom egenskapen Nationalitet/verksamhetsland. Välj Nationalitet som typ, sök efter och välj önskad nationalitet. (Skapa lokal entitet används endast då det inte finns auktoriserad entitet att länka till.)


### Ytterligare egenskaper att lägga till vid behov
Vid behov är det möjligt att lägga till egenskaper som inte ingår i mallen. Nya egenskaper läggs till med hjälp av plustecknet i verktygsmenyn.

#### Namn
* Namn (name = 100 0/- ‡a)
  <br/>Används för namn i rak följd istället för Förnamn och Efternamn. **Kan användas i kombination med Förnamn och Efternamn endast för att ange variantnamn.**
  <br/>```Exempel:```
  * ```Namn: Bang``` 
  <br/>Som variantnamn till den auktoriserade namnformen Alving, Barbro, 1909-1987
  <br/>För att lägga till: Klicka på plustecknet inom egenskapen Se även, välj typen Person i sökrutan till vänster. Sök efter och lägg till auktoriserad namnform. (Finns ingen länkbar entitet behöver en skapas, dvs. Skapa ny Agent med länkning till den första. Avsluta och spara den ursprungliga först.)

#### Fullständigare namnform
* Fullständigare namnform (fullerFormOfName = 100 ‡q och 378)
  <br/>Används för att ange fullständig namnform i de fall då fortkortning används i den auktoriserade namnformen.
  <br/>```Exempel:```
  * ```Efternamn: Smith```
  <br/>```Förnamn: A. D.```
  <br/>```Fullständigare namnform: Adam David```

#### Biografiska uppgifter
* Biografiska uppgifter (hasBiographicalInformation = 678)
  <br/>Används för att ange biografisk information är information om personens liv eller historia.
  <br/>```Exempel:```
  * ```Skönlitterär författare, nobelpristagare 1909, första kvinnliga ledamot av Svenska akademien 1914.```
  <br/>Lägg till egenskapen genom att klicka på plustecknet i verktygsmenyn. Klicka på plustecknet inom den tillagda egenskapen och välj Benämning där uppgifterna anges.

#### Titel eller övrig beteckning
* Titel eller övrig beteckning (marc:titlesAndOtherWordsAssociatedWithAName = 100 ‡c ‡d)
  <br/>Används vid behov som särskiljande tillägg till den auktoriserade namnformen. 
  <br/>```Exempel: påve```

#### Andra attribut för person- och organisationsnamn
* Andra attribut för person- och organisationsnamn (hasOtherAttributes = 368 ‡a ‡2)
  <br/>Används vid behov som särskiljande tillägg för att ange akademiska titlar, kyrkliga ämbeten, militära tjänstegrader (till exempel kapten), hederstitlar etc. Hämta i första hand termen från en kontrollerad vokabulär som Svenska ämnesord.
  <br/>```Exempel: Professorer sao```
  <br/>För att lägga till: Klicka på plustecknet inom egenskapen Andra attribut för person- och organisationsnamn, klicka på Skapa lokal entitet. Klicka på plustecknet inom den tillagda lokala entiteten. Välj egenskaperna Titel/officiell rang för kunglig, adlig eller religiös person samt Kod för kontrollerad vokabulär i de fall termen hämtas från en kontrollerad vokabulär. Skriv in aktuell term och listkod. Länkas ej.

#### Ordningstal
* Ordningstal (marc:numeration = 100 ‡b)
  <br/>Används som särskiljande tillägg till den auktoriserade namnformen för kungligheter samt för påvar, biskopar och andra personer med religiösa yrken.
  <br/>```Exempel:```
  * ```XXII```
  * ```2```

#### Språk
* Språk (associatedLanguage = 377 ‡a)
  <br/>Ange språk som personen använder vid behov.
  <br/>```Exempel: Engelska```
  <br/>Klicka på plustecknet vid egenskapen Språk. Välj Språk som typ vid sökning. Välj önskat språk och klicka på plustecknet. (Skapa lokal entitet används endast då det inte finns auktoriserad entitet att länka till).

#### Organisatorisk tillhörighet
 * Organisatorisk tillhörighet (hasAffiliation = 373 ‡a)
  <br/>Här är det möjligt att ange en samhörande organisation.
  <br/>```Exempel: Uppsala universitet``` 
  <br/>För att lägga till: Klicka på plustecknet vid egenskapen Organisatorisk tillhörighet, och skapa lokal entitet t ex organisation. Lägg sedan till benämning och skriv in uppgiften. *OBS! Organisatorisk tillhörighet ska inte länkas.*


#### Glöm inte att redigera Adminmetadata och spara entiteten innan vidare navigation i verktyget!

