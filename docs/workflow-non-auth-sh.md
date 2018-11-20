---
section: Hjälptexter ämnesord
title: Sammansatt, ej auktoriserat ämnesord
order: 105
date: 2018-11-01
tags:
- ämnesord
- sammansatta ämnesord
- under arbete
---

## Lägg till sammansatt men ej auktoriserat ämnesord 

Hjälptexten beskriver hur sammansatta ämnesord (som inte finns auktoriserade som en sträng) läggs till verksinformationen i Instans av Verk och där de ingående beståndsdelarna (huvudord respektive underindelning) är auktoriserade termer från ämnesordssystemet Svenska ämnesord (sao). 

För att lägga till geografiska sammansatta ämnesord är tillvägagångssättet delvis annorlunda. Se avsnittet [Geografiskt huvudord med geografisk underindelning](#geografiskt-huvudord-med-geografisk-underindelning) nedan.

**OBS! Från och med version 1.3.1 är tillvägagångssättet för att lägga till sammansatta ämnesord delvis förändrat/förenklat med hjälp av snippets, dvs. fördefinierade inmatningsfält som följer med vid tillägg av egenskapen.**

#### Utgå från Instans av Verk
Utgår katalogiseringen från en mall finns egenskapen Ämne redan i mallen inom avsnittet för Instans av Verk. Vid behov av att lägga till egenskapen Ämne: Klicka på plustecknet inom Instans av Verk/Text, sök efter och lägg till Ämne (subject).

### Allmänt ämnesord med allmän underindelning

* Klicka på plustecknet intill Ämne, sidorutan Lägg till entitet öppnas. Välj typen Sammansatt term i rullgardinsmenyn Skapa lokal entitet. 

* Klicka på plustecknet intill Termlista, sidorutan för Lägg till entitet öppnas. Sök efter och lägg till listkod sao. Koden länkas till verksinformationen.

* Klicka på plustecknet intill Termkomponenter, sidorutan Lägg till entitet öppnas. Välj typen Allmänt ämnesord i sökrutans rullgardinsmeny och sök efter aktuell term och klicka på Lägg till. Termen länkas till verksinformationen.

* Klicka på plustecknet intill Termkomponenter, sidorutan Lägg till entitet öppnas. Välj typen Underindelning för allmänt ämnesord i sökrutans rullgardinsmeny och sök efter och lägg till aktuell term. Termen länkas till verksinformationen.

Upprepa momenten ovan för att lägga till fler sammansatta termer.

OBS! Instruktionen ovan fungerar även för sammansatta men ej auktoriserade termer ur andra kontrollerade ämnesordssystem. Punkt tre och fyra ersätts då av Allmänt ämnesord respektive Underindelning för allmänt ämnesord i rullgardinsmenyn för Skapa lokal entitet. Länka till aktuell listkod.


### Geografiskt huvudord med geografisk underindelning
Instruktionen nedan gäller geografiska ämnesord i flera led som inte finns auktoriserade som en sträng men är konstruerade enligt Riktlinjer för Svenska ämnesord. Exempel: Tyskland--Bonn--sao

* Klicka på plustecknet intill egenskapen Ämne, sidorutan Lägg till entitet öppnas. Välj Sammansatt term under Skapa lokal entitet.

* Klicka på plustecknet inom Termlista, sidorutan Lägg till entitet öppnas. Sök efter och lägg till listkod sao. Koden länkas till verksinformationen.

* Klicka på plustecknet inom Termkomponenter, sidorutan Lägg till entitet öppnas. Välj Geografiskt ämnesord under Skapa lokal entitet. Skriv "Tyskland" i Föredragen benämning. *Ska i nuläget ej länkas.*
    
* Klicka på plustecknet inom Termkomponenter, sidorutan Lägg till entitet öppnas. Välj Underindelning för geografisk term under Skapa lokal entitet. Skriv "Bonn" i Föredragen benämning. *Ska i nuläget ej länkas.*

Upprepa momenten ovan för att lägga till fler sammansatta termer eller kopiera och redigera sektionen Underindelning för geografisk term för ytterligare underordnat led (t.ex. Tyskland--Bonn--Beuel).
