---
section: Redigering
title: Att använda verktyget
order: 11
date: 2019-05-10
tags:
- redigering
- editor
- att använda verktyget
---

# Att använda verktyget

### Innehåll
 ( * )Länk till annan relevant hjälptext

| [**Visningsvy**](#visningsvy) | [**Verktygsmeny i redigeringsvy**](#redigeringsvy) | [**Funktioner i redigeringsvy**](funktioner-i-redigeringsvy)
| -------- | ----------- | ----------- |
| [Lägg bestånd](#visningsvy) | [Verktyg](#verktyg) | [Ta bort egenskap](#ta-bort-egenskap) |
| [Visa som](#visa-som) | [Lägg till egenskap](#lägg-till-egenskap) | [Lägg till förekomst av egenskap](#lägg-till-förekomst-av-egenskap) | 
| [Verktyg](#verktyg) | [Ångra](#ångra) | [Hjälp i formuläret](#hjälp-i-formuläret) | 
| [- Expandera/minimera alla](#verktyg) | [Spara](#spara) | [Lägg till/ta bort underliggande egenskap](#lägg-till-och-ta-bort-underliggande-egenskap) | 
| [- Berika från mall* ](https://libris.kb.se/katalogisering/help/editor-templates) | [Spara och sluta redigera](#spara-och-sluta-redigera) | [Entitetsfunktioner](#entitetsfunktioner) | 
| [- Berika från post](#verktyg)
| [- Ladda ner sammanslagen MARC21](#ladda-ner-sammanslagen-MARC21) |
| [- Ladda ner JSON-LD](#ladda-ner-JSON-LD) |
| [- Förhandsgranska MARC21](#forhandsgranska-MARC21) |
| [- Ta bort](#ta-bort) |
| [- Redigera](#redigera) |


## Visningsvy

### Lägg bestånd (endast från typen instans)
Från instanser kan man lägga bestånd. Detta görs i postens visningsvy, där man når beståndsposten via beståndsknappen högst upp i posten. På beståndsknappen syns vilket sigel beståndet läggs på. Från instansposten kan man även se hur många andra bibliotek som har bestånd på instansen.

### Visa som
Under rubriken “Visa som” kan man, utöver den grafiska vyn även granska informationen i olika RDF format:
  * Formell resurs (resursens id samt länkar till olika visningsvyer)  
  * [Json-LD](https://www.w3.org/TR/json-ld/) (RDF anpassad för webbapplikationer) 
  * [Turtle](https://www.w3.org/TR/turtle/) (Den mest kompakta läsbara formen av RDF)
  * [RDF/XML](https://www.w3.org/TR/rdf-syntax-grammar/) (RDF i XML format)

### Verktyg

![Verktygsalternativ](verktygsalternativ.png)  

#### Expandera/minimera alla
För att skapa en bättre översikt över posten samt för att lättare se vad posten innehåller, finns möjlighet att expandera och minimera alla postens egenskaper och underliggande egenskaper med ett klick eller kortkommando.  
Expandera: Alt + Plus
Minimera: Alt + Minus

#### Berika från mall
Se separat instruktion för arbete med [mallar](https://libris.kb.se/katalogisering/help/editor-templates)

#### Berika från post
 * Berika från fil
  </br>Det går att berika från en sparad fil som då fungerar som en slags mall. Då behöver man först skapa en fil att berika från och det gör man lättast i gränssnittet, antingen genom att redigera en befintlig post eller skapa en ny tillfälligt. 
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
    </br>![Kopiera id](KopieraID.PNG)
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

Observera att förhandsgranskningen kan skilja sig åt mellan osparad kontra sparat läge. Följande egenskaper visas exempelvis inte i osparat läge:
 * bärartyp med flera värden
 * kodade genre/form-värden som exporteras till fasta fält
 * länkade ämnesord
 * indikatorer till klassifikations- och ämnesordsfält

#### Ta bort 
Rubriken skiljer sig åt beroende på var i verktyget man befinner sig: Ta bort Instans / Ta bort Bestånd / Ta bort Agent. En post går endast att radera om den inte har obrytbra relationer. 

### Redigera
Klicka på Redigera för att göra ändringar i posten. 



## Verktygsmeny i redigeringsvy

![Redigering](redigering.png)  

### Verktyg
(se beskrivning av Verktyg ovan)

### Lägg till egenskap
Knappen Lägg till egenskap lägger till en eller flera nya egenskaper. Välj egenskap i listan genom att klicka på plustecknet eller trycka Enter vid plustecknet vid egenskapen. Välj eventuellt fler egenskaper. Stäng sidorutan genom att trycka Escape.  

### Ångra
Du kan ångra text du skrivit in men även ångra om du till exempel lagt till en felaktig egenskap i formuläret.

### Spara
Spara-knappen sparar posten direkt till Libris databas, utan att ta dig ur redigeringsläget. När du sparar uppdateras uppgifter för tidpunkt och användare som sparat posten.

### Spara och sluta redigera
Spara och sluta redigera tar dig ur redigeringsläget och sparar dina ändringar. 

## Funktioner i redigeringsvy

![Redigeringsfunktioner](redigeringsfunktioner.png)  

### Ta bort egenskap
För att ta bort en egenskap klickar du på soptunnan i anslutning till egenskapsrubriken. Markören visar vilka data som då raderas.   

### Lägg till förekomst av egenskap
Till vänster finns postens egenskapsrubriker. För att lägga till en ny förekomst av egenskapen klickar du på plustecknet till vänster om egenskapens rubrik. Ytterligare en förekomst av egenskapen läggs då till i posten.  

### Hjälp i formuläret
Vid vissa egenskaper i posten finns det inbyggd hjälp. För muspekaren över frågetecknet. För längre hjälptexter, se [Hjälp ](https://libris.kb.se/katalogisering/help) (överst i formuläret).  

### Lägg till och ta bort underliggande egenskap
Klicka på plustecknet som finns till höger om den egenskap där du vill lägga till den underliggande egenskapen. För att ta bort en underliggande egenskap, klicka på soptunnan till höger om egenskapen du vill radera. 

### Entitetsfunktioner
Till höger om varje lokal entitet finns några funktioner där du kan länka den, lägga till underliggande egenskap till entiteten, ta bort den eller hantera den genom att duplicera eller kopiera. Se [Entiteter](https://libris.kb.se/katalogisering/help/entity-search).    
