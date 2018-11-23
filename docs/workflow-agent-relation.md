---
section: Hjälptexter katalogisering
title: Relationer till delar och verk
order: 34
date: 2018-11-22
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

[Obestämd relation till verk](#obestämd-relation-till-verk)

[Fler ingående verk](#Fler-ingaende-verk)

    

#### Relation till verk uttryckt genom text 
Det finns fasta termer i RDA för att uttrycka en relation till ett verk och som motsvarar delfält i i Exportformatet. Det är ännu inte möjligt att länka till dessa i nya Libris. Svensk översättning för relationerna behöver gås igenom.

Relation till ett verk av en författare (700 1/_ ‡i a  ‡d ǂt)
* Välj Relation (Relationship) vid plustecknet vid Verksdelen
* Välj typ Relation (Relationship) i sidopanelen
* Välj Relation (Relation) vid plustecknet vid Relation (Relationship)

Lägg till Entitet / Skapa lokalt / Verk / Benämning
*  Benämning
  <br/>```Exempel: Parafraserar```
  
 *  Har titel/ Titel / Huvudtitel
  <br/>```Exempel: Pride and prejudice```
 
Välj Primär medverkan när en agent har en relation till verk som beskrivs som relaterat.
* Medverkan och funktion / Primär medverkan / Agent/ Person (700 1/_ ‡a  ǂd )
  Länka i första hand till en agent.
    <br/>```Exempel: Austin,  Jane, 1775-1817```
 

#### Obestämd relation till verk 
Om relationen är viktig att beskriva och inte kan beskrivas på annat sätt, gör en allmän anmärkning (500 ‡a)

* Anmärkning (hasNote) 
<br/>```Exempel:Bygger på förf:s diss. med titeln: En sund själ i en sund kropp : hälsopolitik i Stockholms folkskolor 1880-1930```

* Välj Relation vid plustecknet  vid Verk
* Välj typ Relation i menyn
* Välj Entitet vid plustecknet vid Relation

Lägg till Entitet / Skapa lokalt / Verk 
*  Har titel/ Titel / Huvudtitel
  <br/>```Exempel: En sund själ i en sund kropp```
 
Välj Primär medverkan när en agent har en relation till verk som beskrivs som relaterat.
* Medverkan och funktion / Primär medverkan / Agent/ Person (700 1/_ ‡a ǂd )
   
 Länka i första hand till auktoritet.
   <br/>```Exempel: Hammarberg, Lena, 1943-```
 

#### Fler ingaende verk
Om du vill ange fler ingående verk:
(700 1/2 ‡a ǂd ǂt )
  * Har del / skapa lokal entitet / Verk
    * Har titel / Titel / Huvudtitel 
  Skriv in titeln 
  <br/>```Exempel:  Mind over matter```

  Lägg därefter till Agenten:
* Medverkan och medverkan / Primär medverkan / Agent/ Person
 
    
####  Fler delfält
  Fler delfält att lägga till vid plustecknet för Titeln som rör titeln:
  * Specificering i form av grupptitel (700 ‡k)
  * Delbeteckning (700 ‡n)
  * Deltitel (700 ‡p)
  
 
