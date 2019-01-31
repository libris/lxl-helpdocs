---
section: Redigering
title: Att använda verktyget
order: 11
date: 2019-01-31
tags:
- redigering
- editor
- interaktionselement
---

# Visningsvy

## Lägg bestånd (endast från typen instans)
Från instanser kan man lägga bestånd. Detta görs i postens visningsvy, där man når beståndsposten via beståndsknappen högst upp i posten. På beståndsknappen syns vilket sigel beståndet läggs på. Från instansposten kan man även se hur många andra bibliotek som har bestånd på instansen.


## Visa som
Under rubriken “Visa som” kan man, utöver den grafiska vyn även granska informationen i olika RDF format:
  * Formell resurs (resursens id samt länkar till olika visningsvyer)  
  * [Json-LD](https://www.w3.org/TR/json-ld/) (RDF anpassad för webbapplikationer) 
  * [Turtle](https://www.w3.org/TR/turtle/) (Den mest kompakta läsbara formen av RDF)
  * [RDF/XML](https://www.w3.org/TR/rdf-syntax-grammar/) (RDF i XML format)



## Verktyg

![Verktygsalternativ](verktygsalternativ.png)  

### Expandera/minimera alla
För att skapa en bättre översikt över posten samt för att lättare se vad posten innehåller, finns möjlighet att expandera och minimera alla postens egenskaper och underliggande egenskaper med ett klick eller kortkommando.  
Expandera: Alt + Plus
Minimera: Alt + Minus

### Kopiera
Knappen för att kopiera duplicerar hela beskrivningen in i en ny post. Det står då [Kopia] i postens rubrik. 
OBS! Dock har ingen post skapats förrän posten sparats. När posten sparats får den ett nytt ID. Om man avbryter utan att spara försvinner posten.

### Ladda ner sammanslagen MARC21
Med funktionen Ladda ner sammanslagen MARC21 laddas en fil ner som kan importeras till lokala bibliotekssystem. 

### Ladda ner JSON-LD
Välj Ladda ner JSON-LD för att ladda ner en JSON-LD-fil.  

### Förhandsgranska MARC21
Som ett ytterligare stöd finns också möjlighet att granska sitt arbete genom att förhandsgranska det i MARC21-format. MARC21-vyn konverterar posten vid öppning och är inte redigerbar.

### Ta bort post 
En post går endast att radera om den inte har obrytbra relationer.

## Redigera post
Klicka på Redigera för att göra ändringar i posten. 



# Redigeringsvy - verktygsmeny (till höger)

![Redigering](redigering.png)  

## Verktyg
(se beskrivning av Verktyg ovan)

## Lägg till egenskap
Knappen Lägg till egenskap lägger till en eller flera nya egenskaper. Välj egenskap i listan genom att klicka på plustecknet eller trycka Enter vid plustecknet vid egenskapen. Välj eventuellt fler egenskaper. Stäng sidorutan genom att trycka Escape.  

## Ångra
Du kan ångra text du skrivit in men även ångra om du till exempel lagt till en felaktig egenskap i formuläret.

## Spara
Spara-knappen sparar posten direkt till Libris databas, utan att ta dig ur redigeringsläget. När du sparar uppdateras uppgifter för tidpunkt och användare som sparat posten.

## Spara och sluta redigera
Spara och sluta redigera tar dig ur redigeringsläget och sparar dina ändringar. 

# Redigeringsvy - funktioner i posten

![Redigeringsfunktioner](redigeringsfunktioner.png)  

## Ta bort egenskap
För att ta bort en egenskap klickar du på soptunnan i anslutning till egenskapsrubriken. Markören visar vilka data som då raderas.   

## Lägg till förekomst av egenskap
Till vänster finns postens egenskapsrubriker. För att lägga till en ny förekomst av egenskapen klickar du på plustecknet till vänster om egenskapens rubrik. Ytterligare en förekomst av egenskapen läggs då till i posten.  

## Hjälp i formuläret
Vid vissa egenskaper i posten finns det inbyggd hjälp. För muspekaren över frågetecknet. För längre hjälptexter, se [Hjälp ](https://libris.kb.se/katalogisering/help) (överst i formuläret).  

## Lägga till och ta bort underliggande egenskap
Klicka på plustecknet som finns till höger om den egenskap där du vill lägga till den underliggande egenskapen. För att ta bort en underliggande egenskap, klicka på soptunnan till höger om egenskapen du vill radera. 

## Entitetsfunktioner
Till höger om varje lokal entitet finns några funktioner där du kan länka den, lägga till underliggande egenskap till entiteten, ta bort den eller hantera den genom att duplicera eller kopiera. Se [Entiteter](https://libris.kb.se/katalogisering/help/entity-search).  
