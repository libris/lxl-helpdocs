---
section: Katalogiseringsverktyget
title: Skapa ny
order: 15
date: 2020-11-11
tags:
- create new
- skapa ny
---

# Skapa ny

| Innehåll  | | |
| ------ | ------ | ------ |
| [Anvisningar och praxis](#anvisningar-och-praxis) | | [Skapa ny från fil](#skapa-ny-från-fil) | 
| [Söka](#söka) | | [Importera från Andra källor](#importera-från-andra-källor) | 
| [Skapa ny från mall](#skapa-ny-från-mall) | | [Kopiera](#kopiera) |


## Anvisningar och praxis
Följ gällande anvisningar när du skapar en ny post. 

* [Metadatabyrån](https://metadatabyran.kb.se/)  
* [Kärnelement för verk och uttryck](https://metadatabyran.kb.se/generella-anvisningar---rda/verk-och-uttryck/karnelement-for-verk-och-uttryck?searchTerm=K%C3%A4rnelement+f%C3%B6r+verk+och+uttryck)
* [Kärnelement för manifestation](https://metadatabyran.kb.se/generella-anvisningar---rda/manifestation-instans/karnelement-for-manifestation)
* [Kärnelement för relationer](https://metadatabyran.kb.se/generella-anvisningar---rda/relationer/karnelement-for-relationer?searchTerm=K%C3%A4rnelement+f%C3%B6r+relationer)

## Söka
Sök först noga innan du skapar en ny post i Libris. I de flesta fall finns det redan en post att utgå ifrån. För mer information om Libris metadataflöden, [se Libris informationssidor](https://www.kb.se/samverkan-och-utveckling/libris/att-anvanda-librisdata.html).
Undvik att skapa dubbletter. Läs mer under Sök i vänstermenyn.

## Skapa ny från mall
Om du har gjort en uttömmande sökning och inte hittat någon post för den resurs du ska beskriva, kan du skapa en ny post från mall.

För att skapa en ny post, klicka på Skapa ny. En meny med mallar visas. Mallen innehåller de vanligaste egenskaperna för respektive typ. Fler egenskaper kan läggas till via knappen Lägg till egenskaper (eller kortkommando Alt + F).
Välj typ av post:
 *	Instans  
Här finns mallar för Bok, Datorspel, Ljudbok, Musik-CD med flera materialtyper. Läs mer under Materialtyper i vänstermenyn.
 *	Verk  
(Används ej)
 *	Koncept  
(Används endast av redaktionen för Svenska ämnesord och redaktionen för barnämnesord)
 * Agent  
Här finns mallar för Jurisdiktion, Organisation, Person. Läs mer under Hjälptexter Agenter i vänstermenyn.
 *	Från fil

### Skapa ny från fil
Om du har gjort en uttömmande sökning och inte hittat någon post för den resurs du ska beskriva, kan du skapa en ny post från fil.
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

### Importera från Andra källor
Klicka på Sök. Sök först noga i Libris innan du importerar, se Söka ovan. Om du har gjort en uttömmande sökning i Libris och inte hittat någon post för den resurs du ska beskriva, kan du växla flik till Andra källor. Välj databas i listan genom att klicka på plustecknet vid databasens namn. OCLC är förvald. [Läs mer om sökning i Andra källor](https://libris.kb.se/katalogisering/help/search-import).
För att importera en post, klicka på posten i träfflistan. [Följ anvisningar om Postimport i Libris i Metadatabyrån](https://metadatabyran.kb.se/arbetsfloden/postimport-i-libris?searchTerm=Postimport+i+Libris). Spara sedan posten till Libris databas genom att klicka på Spara.

## Kopiera
Sök först noga i Libris innan du skapar en ny post genom att kopiera, se Söka ovan. Kopiera-funktionen finns i visningsläge. Gå till Verktygsmenyn i visningsläge och klicka på Verktyg. Välj Kopiera. Uppdatera posten enligt instruktioner, [se ovan under Anvisningar och praxis](#anvisningar-och-praxis). Spara sedan posten till Libris databas genom att klicka på Spara. Jämför gärna med funktionerna Berika från mall och Berika från post.
