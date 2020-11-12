---
section: Hjälptexter ämnesord
title: Ämnesord som lokal entitet
order: 115
date: 2020-11-12
tags:
- ämnesord
- koncept
- ämnesord som lokal entitet
---


# Ämnesord som lokal entitet
Hjälptexten beskriver hur man anger ämnesord i verksbeskrivningen i Instans av Verk i de fall ämnesorden inte finns auktoriserade. För auktoriserade ämnesord [använd hjälptexten Länka ämnesord](https://libris.kb.se/katalogisering/help/workflow-linked-entity-sh).

Utgår katalogiseringen från en mall finns egenskapen Ämne redan tillagd under Instans av Verk. 
<br/>För att lägga till egenskapen Ämne: Klicka på plustecknet inom Instans av Verk, sök efter och lägg till Ämne (subject).

| [Ämnesord från system med listkod som länkad entitet](#amnesord-från-system-med-listkod-som-länkad-entitet) | [Ämnesord från system med listkod (utan listkod som länkad entitet)](#amnesord-från-system-med-listkod-utan-listkod-som-länkad-entitet) | [Ämnesord utan listkod](#amnesord-utan-listkod)
| ----------- |  ----------- |  ----------- |
| [Enkelt ämnesord som lokal entitet](#enkelt-amnesord-som-lokal-entitet-med-lankbar-listkod) | [Enkelt ämnesord som lokal entitet](#enkelt-amnesord-som-lokal-entitet-utan-lankbar-listkod) |  [Ämnesord utan listkod](#amnesord-utan-listkod) |
| [Sammansatt ämnesord som lokal entitet](#sammansatt-amnesord-som-lokal-entitet-med-lankbar-listkod) | [Sammansatt ämnesord som lokal entitet](#sammansatt-amnesord-som-lokal-entitet-utan-lankbar-listkod)  |
| [Sammansatt ämnesord som lokal entitet med listkod sao och länkbara komponenter](#sammansatt-amnesord-som-lokal-entitet-med-listkod-sao-och-lankbara-komponenter) | |


## Ämnesord från system med listkod som länkad entitet
Instruktionen används i de fall man vill ange ämnesord som en lokal entitet från kontrollerade ämnesordslistor vars listkod finns som en länkad enitet, t.ex. **agrovoc**, **kao** och **mesh**. Vissa ämnesordskonstruktioner från Svenska ämnesord (sao) läggs också in som lokala entiteter, t.ex. sammansatta geografiska ämnesord där den sammansatta konstruktionen inte finns auktoriserad eller konstruktioner av typen *Byggnader i litteraturen* där hela strängen läggs som ett enkelt ämnesord. [Mer information om den senare typen finns i riktlinjerna för Svenska ämnesord i Metadatabyrån](https://metadatabyran.kb.se/amnesord-och-genre-form/svenska-amnesord/sarskilda-amnesomraden/....i-bibeln-i-filmen-i-heraldiken-i-konsten).

**OBS! Från version 1.17 av Libris katalogisering finns många fler listkoder som länkbara entiteter.**

### Enkelt amnesord som lokal entitet med lankbar listkod

* Öppna sidorutan Lägg till entitet inom egenskapen Ämne. 
* Välj den typ av ämnesord du vill lägga till i rullgardinsmenyn Skapa lokal entitet, t.ex. Allmänt ämnesord.
* Skriv in aktuell term som Föredragen benämning.
* Öppna sidorutan Lägg till egenskap inom den tillagda ämnesorstypen, sök efter och lägg till Ingår i system.
* Lägg till entitet inom Ingår i system. Sök efter och välj aktuell listkod.

För att lägga till flera termer av samma typ kan den lokala entiteten kopieras.

**Exempel på enkelt ämnesord som lokal entitet med länkbar listkod - kao:**
</br>![Enkelt ämnesord som lokal entitet](LokaltEnkeltKao.png) 

**Exempel på enkelt ämnesord som lokal entitet med länkbar listkod - sao:**
</br>![Enkelt ämnesord som lokal entitet](LokaltilitteraturenSao.png) 


### Sammansatt amnesord som lokal entitet med lankbar listkod

* Öppna sidorutan Lägg till entitet inom egenskapen Ämne. 
* Välj typen Sammansatt term i rullgardinsmenyn Skapa lokal entitet.
* Öppna sidorutan Lägg till entitet inom egenskapen Ingår i system. Sök efter och välj aktuell listkod.
* Öppna sidorutan Lägg till entitet inom egenskapen Termkomponenter. 
* Välj typ av ämnesord i rullgardinsmenyn Skapa lokal entitet, t.ex. Allmänt ämnesord.
* Skriv in aktuell term som Föredragen benämning.
* Öppna sidorutan Lägg till entitet inom egenskapen Termkomponenter. 
* Välj typ av ämnesord i rullgardinsmenyn Skapa lokal entitet, t.ex. Underindelning för allmänt ämnesord.
* Skriv in aktuell term som Föredragen benämning.

För att lägga till flera termer av samma typ, eller flera underindelningar inom den sammansatta termen, kan kopierafunktionen användas.

**Exempel på sammansatt ämnesord som lokal entitet med länkbar listkod - kao:**
</br>![Exempel på sammansatt ämnesord som lokal entitet med länkbar listkod - kao](LokaltSammansattKao.png) 

**Exempel på sammansatt ämnesord som lokal entitet med länkbar listkod - sao:**
</br>![Exempel på sammansatt ämnesord som lokal entitet med länkbar listkod - sao](LokaltGeoSammansattSao.png)


### Sammansatt amnesord som lokal entitet med listkod sao och lankbara komponenter

Sammansatta ämnesord från Svenska ämnesord bestående av allmänt ämnesord med allmän underindelning finns inte alltid auktoriserade. De kan dock skapas som lokal entitet endast via kombination av länkbart ämnesord med länkbar underindelning.

[Se riktlinjer för indexering med Svenska ämnesord i Metadatabyrån](https://metadatabyran.kb.se/amnesord-och-genre-form/svenska-amnesord/typer-av-amnesord/allmanna-amnesord) för regler kring hur sammansatta termer får konstrueras.

* Öppna sidorutan Lägg till entitet inom egenskapen Ämne. 
* Välj typen Sammansatt term i rullgardinsmenyn Skapa lokal entitet.
* Öppna sidorutan Lägg till entitet inom egenskapen Ingår i system. Sök efter och välj listkod sao.
* Öppna sidorutan Lägg till entitet under inom egenskapen Termkomponenter. 
* Välj typen Allmänt ämnesord. Sök efter och lägg till aktuell term (kontrollera ämnesordssystem, sao). Termen länkas då till verksbeskrivningen i Instans av Verk. Behåll sidorutan öppen.
* Välj typen Underindelning för allmänt ämnesord. Sök efter och lägg till aktuell underindelning. Termen länkas då till verksbeskrivningen i Instans av Verk.

Upprepa momenten ovan för att lägga till fler sammansatta termer.

**Exempel på sammansatt ämnesord som lokal entitet med listkod sao och länkbara komponenter:**
</br>![Sammansatt ämnesord som lokal entitet med listkod sao och länkbara komponenter](LokaltSammansattSao.png) 

## Ämnesord från system med listkod där listkoden inte finns som länkad entitet
**OBS! Från version 1.17 av Libris katalogisering finns många fler listkoder som länkbara entiteter och behovet av att lägga till listkod som lokal entitet har minskat. Sök först!**

### Enkelt amnesord som lokal entitet utan lankbar listkod

* Öppna sidorutan Lägg till entitet inom egenskapen Ämne. 
* Välj aktuell typ av ämnesord i rullgardinsmenyn Skapa lokal entitet, t.ex. Allmänt ämnesord.
* Skriv in aktuell term som Föredragen benämning.
* Öppna sidorutan Lägg till egenskap inom den tillagda ämnesorstypen, sök efter och lägg till Ingår i system.
* Öppna sidorutan Lägg till entitet inom Ingår i system. Välj Ämnesordssystem i rullgardinsmenyn för Skapa lokal entitet.
* Öppna sidorutan Lägg till egenskaper under inom typen Ämnesordssystem. Sök efter och lägg till egenskapen Kod.
* Skriv in kod för aktuellt ämnesordssystem i rutan, t.ex. ”ram”.

**Exempel på enkelt amnesord som lokal entitet utan länkbar listkod:**
</br>![Lokalt enkelt ämnesord med listkod ram](LokaltEnkeltram.png)

### Sammansatt amnesord som lokal entitet utan lankbar listkod 

* Öppna sidorutan Lägg till entitet inom egenskapen Ämne. 
* Välj typen Sammansatt term i rullgardinsmenyn Skapa lokal entitet.
* Öppna sidorutan Lägg till entitet inom egenskapen Ingår i system. Välj typen Ämnesordssystem i rullgardinsmenyn för Skapa lokal entitet.
* Öppna sidorutan Lägg till egenskaper under inom typen Ämnesordssystem. Sök efter och lägg till egenskapen Kod.
* Skriv in aktuell listkod i rutan, t.ex. ”ram”.
* Öppna sidorutan Lägg till entitet inom egenskapen Termkomponenter. 
* Välj typ av ämnesord i rullgardinsmenyn Skapa lokal entitet, t.ex. Allmänt ämnesord.
* Skriv in aktuell term som Föredragen benämning.
* Öppna sidorutan Lägg till entitet under inom egenskapen Termkomponenter. 
* Välj typ av ämnesord i rullgardinsmenyn Skapa lokal entitet, t.ex. Underindelning för allmänt ämnesord.
* Skriv in aktuell term som Föredragen benämning.

För att lägga till flera termer av samma typ, eller flera underindelningar inom den sammansatta termen, kan kopierafunktionen användas.

**Exempel på sammansatt amnesord som lokal entitet utan länkbar listkod:**
</br>![Lokalt sammansatt ämnesord med listkod ram](LokaltSammansattram.png)

### Amnesord utan listkod

* Öppna sidorutan Lägg till entitet inom egenskapen Ämne. 
* Välj aktuell typ av ämnesord i rullgardinsmenyn Skapa lokal entitet.
* Öppna sidorutan Lägg till egenskaper under inom den tillagda ämnesordstypen. 
* Sök efter och lägg till Föredragen benämning. Skriv in aktuell term.
