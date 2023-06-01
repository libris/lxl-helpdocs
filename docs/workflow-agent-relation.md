---
section: Generell beskrivning
title: Relationer till delar och verk
order: 29
date: 2023-06-01
tags:
- editor
---

# Relationer till delar och verk 

Katalogiseringsregler och information om hur relationer anges i förhållande till delar och verk beskrivs i Metadatabyrån. Se [Ingående verk/uttryck](https://metadatabyran.kb.se/beskrivning/generella-anvisningar---rda/relationer/ingaende-verk), [Relaterade resurser](https://metadatabyran.kb.se/beskrivning/generella-anvisningar---rda/relationer/relaterade-resurser) och [Relationer till ämnen](https://metadatabyran.kb.se/beskrivning/generella-anvisningar---rda/relationer/relationer-till-amnen).

För praktisk information om hantering av entiteter i Libris katalogisering, se hjälptext [Entiteter](https://libris.kb.se/katalogisering/help/entity-search).

## Verk som ämne 
Läs viktig information om arbetet med att bryta ut och länka till verk: [Länkning till verk i Libris](https://metadatabyran.kb.se/beskrivning/generella-anvisningar---rda/verk-och-uttryck/lankning-till-verk-i-libris)!

Tills vidare är rekommendationen att verk beskrivs som lokala entiteter. 

### Verk som ämne - lokal entitet 

För att lägga till en författares verk som ämne (motsvarande Marc21 600 1/4 #a #d #t):

* Utgå från egenskapen Ämne inom Instans av Verk
* Öppna sidorutan Lägg till entitet inom egenskapen Ämne
* Välj typen Verk i rullgardinsmenyn Skapa lokal entitet. En snippet läggs till med egenskaperna Verkstyp, Har titel, Medverkan och funktion och Språk (gäller översättning)
* Ange föredragen titel för verket
* Välj typ av medverkan och länka till aktuell agent eller ange agenten som en lokal entitet
* Länka till aktuellt språk (gäller översättning)

**Svenskt original:**
<br/>![Verk av en författare som ämne](Verksomamne.png)

**Översättning till svenska:**
<br/>![Översättning verk av en författare som ämne](Verksomamneoversattning.png)

För att lägga till ett verk utan primärt upphov som ämne (motsvarande Marc21 630 0/4 #a #n #p):

* Utgå från egenskapen Ämne inom Instans av Verk
* Öppna sidorutan Lägg till entitet inom egenskapen Ämne
* Välj typen Verk i rullgardinsmenyn Skapa lokal entitet. En snippet läggs till med egenskaperna Verkstyp, Har titel, Medverkan och funktion och Språk
* Ta bort egenskaperna Medverkan och funktion och Språk genom att klicka på soptunnan intill dessa
* Ange föredragen titel för verket inom Huvudtitel, följt av en punkt och Deltitel och Delbeteckning

**Verk innehållande deltitel och delbeteckning:**
<br/>![Verk innehållande deltitel och delbeteckning](VerksomamneBibeln.png)
