---
section: Generell beskrivning
title: Relationer till delar och verk
order: 24
date: 2019-04-29
tags:
- editor
- under arbete
---

## Relationer till delar och verk 
(7XX)

700, 710 och 711 är komplicerade fält i MARC21 som kan uttrycka olika saker om en agent, medverkande, relationer, och att en instans innehåller flera verk. Den här hjälpen visar hur man skapar olika typer av relationer. 

Länka i första hand till befintliga auktioriteter för personer, organisationer och möten. Om det inte finns en auktoritet så kan du skapa en auktoritet. Se hjälptexterna för Agenter. Se även Hjälptexten Relationer till Agent i verksbeskrivningen.

*I de första versionerna av nya Libris bör man inte länka till eller skapa nya verk, det är under utveckling.*



[Relation till verk uttryckt genom text](#relation-till-verk-uttryckt-genom-text)

[Obestämd relation till verk](#obestamd-relation-till-verk)

[Ingående verk](#ingaende-verk)

[Verk som ämne](#verk-som-amne)

   

### Relation till verk uttryckt genom text 
Relation till ett verk av en författare (700 1/_ #i #a #d #t)
<br/>
Det finns fasta termer i RDA för att uttrycka en relation till ett verk och som motsvarar delfält i i Exportformatet, men det är ännu inte möjligt att länka till dessa i nya Libris. De kontrollerade relationsbeteckningarna tillämpas tills vidare restriktivt, eftersom det för närvarande saknas officiella svenska översättningar av RDA-termerna.

För att uttrycka relationen till ett verk som har ett samband med (men inte ingår i) den katalogiserade instansen:

![Relation till ett verk av en författare](Relationverkauth.png) 

* Öppna sidorutan Lägg till egenskaper under: Text
* Välj egenskapen Relation (Relationship)
* Välj typ Relation från rullgardinsmenyn
* Öppna sidorutan Lägg till egenskaper under: Relation och välj Entitet
  * Lägg till Entitet/Skapa lokal entitet/Verk
  * Lägg till egenskaper under Verk/Har titel/Titel/Huvudtitel och skriv in titeln
  * Lägg till egenskaper under Verk/Medverkan och funktion/Primär medverkan/Agent
  * Lägg till entitet och länka till auktoriserad namnform. Om en sådan inte finns Skapa lokal entitet, välj Person och fyll i uppgifterna
* Öppna sidorutan Lägg till egenskaper under: Relation och välj Relation
  * Lägg till Relation/Skapa lokal entitet
  * Lägg till egenskaper under: Relation och välj Benämning
  * Skriv in uppgiften. ```Exempel: Parafraserar```

 <br/>

### Obestamd relation till verk 
Om relationen är viktig att beskriva och inte kan beskrivas på annat sätt, gör en allmän anmärkning (500 #a)


![Obestämd relation till ett verk](Obestrelationverk.png) 

* Öppna sidorutan Lägg till egenskaper under: Text
* Välj egenskapen Relation (relationship)
* Välj typ Relation från rullgardinsmenyn
* Öppna sidorutan Lägg till egenskaper under: Relation och välj Entitet
* Lägg till Entitet/Skapa lokal entitet/Verk
  * Lägg till egenskaper under Verk/Har titel/Titel/Huvudtitel och skriv in titeln
  * Lägg till egenskaper under Verk/Medverkan och funktion/Primär medverkan/Agent
  * Lägg till entitet och länka till auktoriserad namnform. Om en sådan inte finns Skapa lokal entitet, välj Person och fyll i uppgifterna
* Lägg till en anmärkning (Lägg till egenskaper under: Instans/Anmärkning (hasNote)/Anmärkning/Benämning) och skriv in uppgiften
<br/>```Exempel:Bygger på förf:s diss. med titeln: En sund själ i en sund kropp : hälsopolitik i Stockholms folkskolor 1880-1930```

### Ingaende verk
För att skapa analytiska biuppslag på verk som ingår i den katalogiserade instansen (700 1/2 #a #d #t)

![Ingaende verk](Ingaendeverk.png) 
* Öppna sidorutan Lägg till egenskaper under Text:
* Välj egenskapen Har del (hasPart)
* Lägg till entitet/Skapa Lokal entitet/Verk
  * Lägg till egenskaper under Verk/Har titel/Titel/Huvudtitel och skriv in titlen
  * Lägg till egenskaper under Verk/Medverkan och funktion/Primär medverkan/Agent
  * Lägg till entitet och länka till autkoriserad namnform. Om en sådan inte finns, Skapa lokal entitet, välj Person och fyll i uppgifterna
 
## Verk som amne
I de fall det finns en auktoriserad beskrivning av ett verk går den att länka till. De auktoriserade beskrivningar för verk som finns i Libris är i många fall ganska tunna men bör trots det användas för länkning till för att undvika att skapa lokala entiteter i onödan.

Börja alltid med att söka efter länkbar entitet. Lokal entitet skapas endast då det inte finns auktoriserad beskrivning att länka till. Rekommendationen att inte bryta ut verk som länkbar entitet gäller fortfarande, se [information i Librisbloggen](http://librisbloggen.kb.se/2018/05/30/verk-och-instans-i-startversionen/).



### Länka till verk
* Öppna sidorutan Lägg till entitet inom egenskapen Ämne.
* Filtrera på typen Verk.
* Sök efter och lägg till aktuellt verk. Det auktoriserade verket länkas då till verksbeskrivningen i Instans av Verk.

Exempel:
</br>![Länkat verk som ämne](LankatVerkAmne.png)

Tillvägagångssättet är detsamma för verk med primärt upphov (600 1/0 #a #d #t) och anonyma verk (630 -/4 #a). 
</br>*Observera att för verk med primärt upphov genereras för tillfället andraindikator 0 i exportformatet.*

</br>Flera verk kan sökas efter/läggas till när sidorutan Lägg till entitet är öppen.

### Verk som lokal entitet
* Öppna sidorutan Lägg till entitet inom egenskapen Ämne.
* Välj typen Verk i rullgardinsmenyn för Skapa lokal entitet.
* Öppna sidorutan Lägg till egenskaper inom den tillagda typen Verk. Sök efter och lägg till egenskaperna Har titel och Medverkan och funktion.
* Välj Titel i rullgardinsmenyn och skriv in den föredragna titeln i rutan för Huvudtitel (Övrig titelinformation raderas).
* Välj Primär medverkan i rullgardinsmenyn och sök efter och länka till auktoriserad namnform. (Om auktoriserad namnform saknas: Välj typen Person under Skapa lokal entitet och fyll i uppgifterna).
* Öppna sidorutan Lägg till funktion och länka till aktuell funktion.

Exempel:
</br>![Verk som lokal entitet som ämne](VerkLokalEntitetAmne.png)
