---
section: Redigering
title: Att använda verktyget
order: 11
date: 2019-10-18
tags:
- redigering
- editor
- att använda verktyget
---

## Att använda verktyget

### Innehåll
 ( * )Länk till annan relevant hjälptext

| [**Visningsvy**](#visningsvy) | [**Verktygsmeny i redigeringsvy**](#redigeringsvy) | [**Funktioner i redigeringsvy**](funktioner-i-redigeringsvy) | [**Övrigt**](#ovrigt) |
| -------- | ----------- | ----------- | ----------- |
| [Lägg bestånd](#visningsvy) | [Verktyg](#visa-som) | [Ta bort egenskap](#funktioner-i-redigeringsvy) | [Skapa ny - Från fil](#ovrigt) |
| [Visa som](#visningsvy) | [Lägg till egenskap](#lagg-till-egenskap) | [Lägg till förekomst av egenskap](#funktioner-i-redigeringsvy) | [Byta verks- och instanstyp](#ovrigt) |
| [Verktyg](#verktyg) | [Ångra](#lagg-till-egenskap) | [Hjälp i formuläret](#funktioner-i-redigeringsvy) | 
| [- Expandera/minimera alla](#verktyg) | [Spara](#spara) | [Lägg till/ta bort underliggande egenskap](#funktioner-i-redigeringsvy) |
| [- Berika från mall* ](https://libris.kb.se/katalogisering/help/editor-templates) | [Spara och sluta redigera](#spara) | [Entitetsfunktioner](#entitetsfunktioner) |
| [- Berika från post](#verktyg) |
| [- Ladda ner sammanslagen MARC21](#ladda-ner-sammanslagen-marc21) |
| [- Ladda ner JSON-LD](#ladda-ner-sammanslagen-marc21) |
| [- Förhandsgranska MARC21](#ladda-ner-sammanslagen-marc21) |
| [- Ta bort](#ta-bort) |
| [- Redigera](#redigera) |



### Visningsvy

#### Lägg bestånd (endast från typen instans)
Från instanser kan man lägga bestånd. Detta görs i postens visningsvy, där man når beståndsposten via beståndsknappen högst upp i posten. På beståndsknappen syns vilket sigel beståndet läggs på. Från instansposten kan man även se hur många andra bibliotek som har bestånd på instansen.

#### Visa som
Under rubriken “Visa som” kan man, utöver den grafiska vyn även granska informationen i olika RDF format:
  * Formell resurs (resursens id samt länkar till olika visningsvyer)  
  * [Json-LD](https://www.w3.org/TR/json-ld/) (RDF anpassad för webbapplikationer) 
  * [Turtle](https://www.w3.org/TR/turtle/) (Den mest kompakta läsbara formen av RDF)
  * [RDF/XML](https://www.w3.org/TR/rdf-syntax-grammar/) (RDF i XML format)

#### Verktyg

![Verktygsalternativ](verktygsalternativ.png)  

#### Expandera/minimera alla
För att skapa en bättre översikt över posten samt för att lättare se vad posten innehåller, finns möjlighet att expandera och minimera alla postens egenskaper och underliggande egenskaper med ett klick eller kortkommando.  
Expandera: Alt + Plus
Minimera: Alt + Minus

#### Berika från mall
Se separat instruktion för arbete med [mallar](https://libris.kb.se/katalogisering/help/editor-templates)

#### Berika från post
 * Berika från fil
  </br>Det går att berika från en sparad fil som då fungerar som en slags mall. Då behöver man först skapa en fil att berika från och det gör man lättast i gränssnittet, antingen genom att redigera en befintlig post eller skapa en ny tillfälligt. *Observera att det kan vara nödvändigt att spara om sin fil som fungerar som mall efter varje ny release av katalogiseringsverktyget ifall att det har gjorts formatändringar eller andra uppdateringar som påverkar funktionaliteten.*
   * Sök fram eller skapa en post (A) med de egenskaper som ska finnas i mallen. Både tomma egenskaper och egenskaper med innehåll går att få med.
   * Gå till verktygsmenyn och välj "Ladda ner JSON-LD inklusive osparade ändringar". Namnge filen och spara. 
   * Avbryt redigeringen av posten (A) ifall en ny tillfällig skapats, d.v.s. radera den. 
   * Sök fram posten (B) som ska berikas från fil, d.v.s. från post (A). 
   * Öppna redigeringsläge och välj "Berika från post" --> "Från fil" i verktygsmenyn.
   * Leta upp och välj rätt fil (den sparade post A) i utforskaren. Post B berikas med metadata från A.
 
   Berika från fil kan användas även för bestånd enligt ovanstående instruktion. För att berika en beståndspost, tag bort Har komponent i den beståndspost som ska berikas. Välj sedan "Berika från post" --> "Från fil" i verktygsmenyn.  
 
 * Berika från ID
   </br>Funktionen är lämplig att använda för att berika en preliminär beskrivning (förhandspost, prelpost, CIP-post) (B) med metadata från en mer utförlig beskrivning (A), t.ex. metadata från en första utgåva kan berika en tunn förhandspost för en andra utgåva. Med funktionen är det också möjligt att få med egenskaper som inte går att lägga till manuellt i verktyget men som finns i befintlig data.

   * Sök fram en post (A) med de egenskaper du vill föra över till den post du vill berika (B). 
   * I post (A), klicka ID-numret som visas till höger i sammanfattningsrutan. Klicka på Kopiera ID till vänster om postens ID.
    </br>![Kopiera ID](KopieraID.PNG)
   * I post (B), välj Berika från post i verktygsmenyn. Välj Från ID. 
    </br>[Berika från ID](BerikafranID.png)
   * Klistra in ID från (A). De egenskaper som inte redan finns i (B) läggs till. Länkade egenskaper visas i klartext först när du har sparat. 
   * Redigera och spara.

#### Ladda ner sammanslagen MARC21
Med funktionen Ladda ner sammanslagen MARC21 laddas en fil ner som kan importeras till lokala bibliotekssystem. 

#### Ladda ner JSON-LD
Välj Ladda ner JSON-LD för att ladda ner en JSON-LD-fil.  

#### Forhandsgranska MARC21
Som ett ytterligare stöd finns också möjlighet att granska sitt arbete genom att förhandsgranska det i MARC21-format. MARC21-vyn konverterar posten vid öppning och är inte redigerbar.

#### Ta bort 
Rubriken skiljer sig åt beroende på var i verktyget man befinner sig: Ta bort Instans / Ta bort Bestånd / Ta bort Agent. En post går endast att radera om den inte har obrytbra relationer. 

#### Redigera
Klicka på Redigera för att göra ändringar i posten. 


### Verktygsmeny i redigeringsvy

![Redigering](redigering.png)  

#### Verktyg
(se beskrivning av Verktyg ovan)

#### Lagg till egenskap
Knappen Lägg till egenskap lägger till en eller flera nya egenskaper. Välj egenskap i listan genom att klicka på plustecknet eller trycka Enter vid plustecknet vid egenskapen. Välj eventuellt fler egenskaper. Stäng sidorutan genom att trycka Escape.  

#### Ångra
Du kan ångra text du skrivit in men även ångra om du till exempel lagt till en felaktig egenskap i formuläret.

#### Spara
Spara-knappen sparar posten direkt till Libris databas, utan att ta dig ur redigeringsläget. När du sparar uppdateras uppgifter för tidpunkt och användare som sparat posten.

#### Spara och sluta redigera
Spara och sluta redigera tar dig ur redigeringsläget och sparar dina ändringar. 

### Funktioner i redigeringsvy

![Redigeringsfunktioner](redigeringsfunktioner.png)  

#### Ta bort egenskap
För att ta bort en egenskap klickar du på soptunnan i anslutning till egenskapsrubriken. Markören visar vilka data som då raderas.   

#### Lägg till förekomst av egenskap
Till vänster finns postens egenskapsrubriker. För att lägga till en ny förekomst av egenskapen klickar du på plustecknet till vänster om egenskapens rubrik. Ytterligare en förekomst av egenskapen läggs då till i posten.  

#### Hjälp i formuläret
Vid vissa egenskaper i posten finns det inbyggd hjälp. För muspekaren över frågetecknet. För längre hjälptexter, se [Hjälp ](https://libris.kb.se/katalogisering/help) (överst i formuläret).  

#### Lägg till och ta bort underliggande egenskap
Klicka på plustecknet som finns till höger om den egenskap där du vill lägga till den underliggande egenskapen. För att ta bort en underliggande egenskap, klicka på soptunnan till höger om egenskapen du vill radera. 

#### Entitetsfunktioner
Till höger om varje lokal entitet finns några funktioner där du kan länka den, lägga till underliggande egenskap till entiteten, ta bort den eller hantera den genom att duplicera eller kopiera. Se [Entiteter](https://libris.kb.se/katalogisering/help/entity-search).    

### Ovrigt

#### Skapa ny - Från fil
Funktionen Skapa ny - från fil är användbar om man t.ex. ska skapa ett antal helt nya poster som har en del egenskaper gemensamt och en del egenskaper som är helt olika. Själva arbetsgången blir att man först skapar en egen mallpost som sedan kan användas som utgångspunkt för nya poster. *Observera att det kan vara nödvändigt att spara om sin fil som fungerar som mall efter varje ny release av katalogiseringsverktyget ifall att det har gjorts formatändringar eller andra uppdateringar som påverkar funktionaliteten.*

1. Förbered genom att skapa mallpost. Enklast är att utgå från en befintlig post.
 * Börja med att kopiera posten (Verktyg -> Kopiera). 
 * Fyll i den information som är gemensam för alla poster som sedan ska skapas. Lägg till egenskaper eller töm informationen i de egenskaper som ska vara med, men där informationen skiljer sig åt mellan posterna.
 * När mallposten är färdigredigerad: Välj Ladda ner JSON-LD (Inkl. osparade ändringar) i verktygsmenyn. Namnge filen 
och välj ok för att spara filen/mallen.
 * Avbryt sedan redigeringen av posten i katalogiseringsverktyget (utan att spara).

2. Skapa ny från fil
 * Välj Skapa ny - Från fil. 
 * Klicka på Välj fil och leta fram den förberedda filen/mallen i utforskaren. Klicka på öppna (alternativt dra in filen till ytan markerad "Släpp din fil här").
 * Den nya posten öppnas med ifyllda och tomma inmatningsfält (länkade entiteter visas som URI:er men dessa ändras till korrekt etikett vid sparande).

3. Redigera posten efter behov och spara.

Upprepa punkt 2 och 3 för att skapa fler poster utifrån samma fil/mall.


### Byta verks- och instanstyp
Från och med version 1.12 går det att byta verks- och instanstyp i katalogiseringsgränssnittet. Det finns inga restriktioner kring vilka instanstyper som går att kombinera med vilka verkstyper utan alla kombinationer är tekniskt möjliga. Observera att arbetet med verk i Libris kommer att leda till en uppstädning för mer renodlade verks- och instanstyper. Använd tabellen nedan för guidning gällande de nuvarande rekommenderade kombinationerna.

Om posten har länkningar till andra poster (t.ex. bestånd) är typfältet låst, men det går att låsa upp om man klickar på hänglåset längst till höger.

##### **Lista över de rekommenderade kombinationerna av verks- och instanstyp**

| **Verkstyp**  |  **Instanstyp** |   
| :----------- | :----------- |
| Text (000/06=a i MARC21) | Instans (mall: Bok/Tryckt seriell/Äldre tryck)<br>Elektronisk (007c i MARC21) (mall: E-bok)<br>Tryck<br>Handskrift<br>Taktil resurs |   
| Kartmaterial (000/06=e i MARC21) | Karta (007a i MARC21) (mall: Karta)<br>Kartglob (007d i MARC21)<br>Elektronisk (007c i MARC21)<br>Handskrift |   
| Ljudmaterial (t.ex. ljudbok) (000/06=i i MARC21) | Ljudinspelning (007s i MARC21) (mall: Ljudbok)<br>Elektronisk (007c i MARC21) |   
| Musik (t.ex. musik-CD) (000/06=j i MARC21) | Ljudinspelning (007s i MARC21) (mall: Musik-CD)<br>Elektronisk (007c i MARC21) |   
| Multimedia (000/06=m i MARC21) | Instans<br>Elektronisk (007c i MARC21) (mall: Datorspel) |   
| Noterad musik (000/06=c i MARC21) | Instans (mall: Noterad musik) |
| Rörlig bild (000/06=g i MARC21) | Videoinspelning (007v i MARC21) (mall: Film)<br>Elektronisk (007c i MARC21) |
| Stillbild (000/06=k i MARC21) | Instans (mall: Stillbild)<br>Elektronisk (007c i MARC21)<br>Instans av stillbild (007k i MARC21) |
| Paket (000/06=o i MARC21) | Instans |

##### **Följande instanstyper bör ej användas:**
 * Instans av paket
 * Instans av text
 * Instans av musiknoter
 * Instans av projicerad bild


#### Byta verkstyp  
*	Gå till Instans av verk/Verkstyp. Klicka på hänglåset längst till höger och ta del av informationen i dialogrutan
* Välj typ i rullgardinslistan

<br/>*OBS!* Listan innehåller alla verkstyper.
<br/>*OBS!* Byte av verkstyp kan innebära att länkade entiteter i verksbeskrivningen behöver ändras, t.ex. MARC-koder specifika för de olika verkstyperna eller RDA-entiteter.
  <br/>```Exempel:```
  <br/>```Koden för Genre/form/Litterär genre: Roman – f hör till verkstypen Text och ska inte användas med verkstypen Ljudmaterial.
För en ljudbok som ändras till verkstypen Text behöver också Innehållstyp ändras till Text – txt.```

Om det är mycket som behöver ändras kan det vara smidigare att radera de berörda egenskaperna och sedan berika från lämplig mall.

#### Byta instanstyp 
*	Gå till Instanstyp. Klicka på hänglåset längst till höger och ta del av informationen i dialogrutan
*	Välj typ i rullgardinslistan

<br/>*OBS!* Listan innehåller alla instanstyper.
<br/>*OBS!* Byte av instanstyp kan innebära att länkade entiteter i instansbeskrivningen behöver ändras, t.ex. MARC-koder specifika för de olika instanstyperna eller RDA-entiteter.
   <br/>```Exempel:```
   <br/>```Bärartypen Ljudskiva - d under Instans hör till instanstypen Ljudinspelning och ska inte användas med andra instanstyper.```

Om det är mycket som behöver ändras kan det vara smidigare att radera de berörda egenskaperna och sedan berika från lämplig mall.

