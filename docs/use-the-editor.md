---
section: Katalogiseringsverktyget
title: Att använda verktyget
order: 12
date: 2020-04-01
tags:
- redigering
- editor
- att använda verktyget
---

# Att använda verktyget

## Innehåll
 ( * )Länk till annan relevant hjälptext

[Inledning](#inledning)

| [**Verktygsmeny i visningsläge**](#verktygsmeny-i-visningslage) | [**Verktygsmeny i redigeringsläge**](#verktygsmeny-i-redigeringslage) | [**Övriga funktioner**](#ovriga-funktioner) |
| -------- | ----------- | ----------- |
| [Visa som](#visa-som) | [Verktyg](#verktygsmeny-i-redigeringslage) | [Ta bort egenskap](#ovriga-funktioner) |
| [Verktyg](#verktyg) | [- Berika från mall*](https://libris.kb.se/katalogisering/help/edit-upgrade) | [Lägg till förekomst av egenskap](#ovriga-funktioner) | 
| [- Expandera alla](#verktyg) | [- Berika från post*](https://libris.kb.se/katalogisering/help/edit-upgrade) | [Hjälp i formuläret](#ovriga-funktioner) | 
| [- Minimera alla](#verktyg) | [Detaljerad berikning](https://libris.kb.se/katalogisering/help/edit-upgrade)| [Lägg till/ta bort underliggande egenskap](#ovriga-funktioner) |
| [- Kopiera](#verktyg) | [Lägg till egenskaper](#verktygsmeny-i-redigeringslage) | [Entitetsfunktioner](#6-entitetsfunktioner) |
| [- Ladda ner sammanslagen MARC21](#ladda-ner-sammanslagen-marc21) | [Ångra](#verktygsmeny-i-redigeringslage) | [Byta verkstyp och instanstyp](#byta-verkstyp-och-instanstyp) |
| [- Ladda ner JSON-LD](#ladda-ner-sammanslagen-marc21) | [Avbryt](#avbryt)  |  [- Byta verkstyp](#byta-verkstyp) |
| [- Förhandsgranska MARC21](#ladda-ner-sammanslagen-marc21) | [Spara](#spara) | [- Byta instanstyp](#byta-instanstyp) |
| [- Ta bort Instans](#ta-bort-instans) | [Spara och sluta redigera](#spara-och-sluta-redigera)  |  |
| [Redigera](#redigera) |  |  | 


## Inledning
Hjälptexten beskriver funktionalitet och verktyg med utgångspunkt från en Instans (inklusive Instans av Verk). Viss funktionalitet och vissa verktyg är genomgående i hela Libris katalogisering. 

I varje instans finns en sammanfattande ruta högst upp.

![Visualisering av sammanfattningsrutan i en instansbeskrivning](sammanfattningsrutan.png)

Sammanfattningsrutan innehåller:
 1. Titel och sammanfattande bibliografisk information. Välj Visa fler för att visa mer information i sammanfattningsrutan
 2. Beskrivningsnivå 
 3. Instanstyp 
 4. Utgivningssätt 
 5. Medietyp
 6. Bärartyp
 7. Postens ID
 8. Flagga för Katalogvård
 9. Information om bestånd: Lägg bestånd/Visa bestånd
 10. Antal bestånd (visa alla beståndsposter)

## Verktygsmeny i visningslage
En del av funktionerna tillgängliga i verktygsmenyn i visningsläge går att använda även om man inte är inloggad. För att kunna använda alla funktioner som beskrivs nedan krävs det att man loggar in.

### Visa som
Under rubriken “Visa som” kan man välja att granska informationen i olika RDF-format:
  * Formell resurs (resursens id samt länkar till olika visningsvyer)  
  * [Information om Json-LD](https://www.w3.org/TR/json-ld/) (RDF-anpassad för webbapplikationer) 
  * [Information om Turtle](https://www.w3.org/TR/turtle/) (Den mest kompakta läsbara formen av RDF)
  * [Information om RDF/XML](https://www.w3.org/TR/rdf-syntax-grammar/) (RDF i XML-format)

### Verktyg

![Alternativ i verktygsmeny i visningsläge](verktygsalternativ.png)  

#### Expandera alla
För att skapa en bättre översikt över posten samt för att lättare se vad posten innehåller, finns möjlighet att expandera alla postens egenskaper och underliggande egenskaper med ett klick eller kortkommando.
<br/>Expandera: Alt + Plus

#### Minimera alla
För att minimera postens alla egenskaper till en mer kompakt vy med ett klick eller kortkommando.
<br/>Kortkommando: Alt + Minus

#### Kopiera
För att kopiera en helt post kan kopierafunktionen användas. Jämför gärna med funktionerna Berika från mall och Berika från post för att använda den funktionalitet som är lämplgast för ändamålet.
<br/>Kortkommando: Ctrl + (pil upp) + C

#### Ladda ner sammanslagen MARC21
Med funktionen Ladda ner sammanslagen MARC21 laddas en fil ner som kan importeras till lokala bibliotekssystem.

#### Ladda ner JSON-LD
Välj Ladda ner JSON-LD för att ladda ner en JSON-LD-fil.

#### Forhandsgranska MARC21
Som ett ytterligare stöd finns också möjlighet att granska sitt arbete genom att förhandsgranska det i MARC21-format. MARC21-vyn konverterar posten vid öppning och är inte redigerbar.

#### Ta bort Instans
För att radera en post välj Ta bort Instans. Åtgärden går inte att utföra om det finns bestånd länkade till instansen och det går inte att ångra, så kontrollera noga innan radering görs. Glöm inte att kontrollera Adminmetadata för att notera eventuella anmärkningar eller om posten ingår i en bibliografi - då ska den inte raderas.

### Redigera
Välj Redigera för att aktivera redigeringsläget och för att kunna göra ändringar i posten.
<br/>Kortkommando: Ctrl + E


## Verktygsmeny i redigeringslage

![Alternativ i verktygsmeny i redigeringsläge](verktygsmenyredigeringslage.png) 

Nedan beskrivs de funktioner som är tillgängliga i verktygsmenyn när man har aktiverat redigeringsläget.

### Verktyg
Förutom de funktioner som är tillgängliga i visningsläget, se Verktyg ovan, tillkommer här ytterligare två. Berika från mall och Berika från post. [Dessa funktioner beskrivs utförligt i hjälptexten Redigera och uppgradera](https://libris-dev.kb.se/katalogisering/help/edit-upgrade).

### Lägg till egenskaper

![Visualisering av hur egenskaper läggs till](laggtillegenskap.png)

 1. Lägg till egenskaper under: Instans. Används för att lägga till en eller flera nya egenskaper under instans. Välj egenskap i listan genom att klicka på plustecknet eller trycka Enter vid plustecknet vid egenskapen.
<br/> Kortkommando: Alt + F 
 2. För att lägga till egenskaper inom Instans av Verk används det lilla plustecknet uppe till höger inom rutan för Instans av Verk.

### Ångra
Du kan ångra text du skrivit in men även ångra om du till exempel lagt till en felaktig egenskap i formuläret.
<br/> Kortkommando: Alt + Z

### Avbryt
Avbryter pågående redigering och tar bort eventuella ändringar.
<br/> Kortkommando: Alt + Q

### Spara
Spara-knappen sparar posten direkt till Libris databas, utan att ta dig ur redigeringsläget. När du sparar uppdateras uppgifter för tidpunkt och användare som sparat posten.
<br/> Kortkommando: Ctrl + S

### Spara och sluta redigera
Spara och sluta redigera tar dig ur redigeringsläget och sparar dina ändringar. 
<br/> Kortkommando: Ctrl + D


## Ovriga funktioner

Redigeringsfunktioner inom en egenskap:

![Redigeringsfunktioner inom en egenskap](redigeringsfunktioner.png)

### 1 Ta bort egenskap
För att ta bort en egenskap klickar du på soptunnan i anslutning till egenskapsrubriken. Färgmarkeringen visar vilka data som då raderas.   

### 2 Lägg till förekomst av egenskap
Till vänster finns postens egenskapsrubriker. För att lägga till en ny förekomst av egenskapen klickar du på plustecknet till vänster om egenskapens rubrik. Ytterligare en förekomst av egenskapen läggs då till i posten. Observera att alla egenskaper inte är upprepningsbara.

### 3 Hjälp i formuläret
Vid vissa egenskaper i posten finns det inbyggd hjälp. För muspekaren över frågetecknet. För längre hjälptexter, [se Hjälp](https://libris.kb.se/katalogisering/help) (överst i formuläret).

### 4, 5 Lägg till/ta bort underliggande egenskap
Klicka på plustecknet som finns till höger om den egenskap där du vill lägga till den underliggande egenskapen. För att ta bort en underliggande egenskap, klicka på soptunnan till höger om egenskapen du vill radera.

### 6 Entitetsfunktioner
Till höger om varje lokal entitet finns några funktioner där du kan länka den, lägga till underliggande egenskap till entiteten, ta bort den eller hantera den genom att duplicera eller kopiera. [Se hjälptexten Entiteter](https://libris.kb.se/katalogisering/help/entity-search).

### Byta verkstyp och instanstyp
Från och med version 1.12 går det att byta verks- och instanstyp i katalogiseringsgränssnittet. Det finns inga restriktioner kring vilka instanstyper som går att kombinera med vilka verkstyper utan alla kombinationer är tekniskt möjliga. Observera att arbetet med verk i Libris kommer att leda till en uppstädning för mer renodlade verks- och instanstyper. Använd tabellen nedan för guidning gällande de nuvarande rekommenderade kombinationerna.

Om posten har länkningar till andra poster (t.ex. bestånd) är typfältet låst, men det går att låsa upp om man klickar på hänglåset längst till höger.

#### **Lista över de rekommenderade kombinationerna av verks- och instanstyp**

| **Verkstyp**  |  **Instanstyp** |   
| :----------- | :----------- |
| Text (000/06=a i MARC21) | Instans (mall: Bok/Tryckt seriell/Äldre tryck)<br>Elektronisk (007c i MARC21) (mall: E-bok)<br>Tryck<br>Handskrift<br>Taktil resurs |   
| Karta (000/06=e i MARC21) | Karta (007a i MARC21) (mall: Karta)<br>Kartglob (007d i MARC21)<br>Elektronisk (007c i MARC21)<br>Handskrift |   
| Ljud (t.ex. ljudbok) (000/06=i i MARC21) | Ljudinspelning (007s i MARC21) (mall: Ljudbok)<br>Elektronisk (007c i MARC21) |   
| Musik (t.ex. musik-CD) (000/06=j i MARC21) | Ljudinspelning (007s i MARC21) (mall: Musik-CD)<br>Elektronisk (007c i MARC21) |   
| Multimedia (000/06=m i MARC21) | Instans<br>Elektronisk (007c i MARC21) (mall: Datorspel) |   
| Noterad musik (000/06=c i MARC21) | Instans (mall: Noterad musik)<br>Elektronisk (007c i MARC21)<br>Tryck<br>Handskrift<br>Taktil resurs |
| Rörlig bild (000/06=g i MARC21) | Videoinspelning (007v i MARC21) (mall: Film)<br>Elektronisk (007c i MARC21) |
| Stillbild (000/06=k i MARC21) | Instans (mall: Stillbild)<br>Elektronisk (007c i MARC21)<br>Instans av stillbild (007k i MARC21) |
| Paket (000/06=o i MARC21) | Instans |

##### **Följande instanstyper bör ej användas:**
 * Instans av paket
 * Instans av text
 * Instans av musiknoter
 * Instans av projicerad bild

### Byta verkstyp  
*	Gå till Instans av verk/Verkstyp. Klicka på hänglåset längst till höger och ta del av informationen i dialogrutan
* Välj typ i rullgardinslistan

<br/>*OBS!* Listan innehåller alla verkstyper.
<br/>*OBS!* Byte av verkstyp kan innebära att länkade entiteter i verksbeskrivningen behöver ändras, t.ex. MARC21-koder specifika för de olika verkstyperna eller RDA-entiteter.
  <br/>```Exempel:```
  <br/>```Koden för Genre/form/Litterär genre: Roman – f hör till verkstypen Text och ska inte användas med verkstypen Ljudmaterial.
För en ljudbok som ändras till verkstypen Text behöver också Innehållstyp ändras till Text – txt.```

Om det är mycket som behöver ändras kan det vara smidigare att radera de berörda egenskaperna och sedan berika från lämplig mall.

### Byta instanstyp 
*	Gå till Instanstyp. Klicka på hänglåset längst till höger och ta del av informationen i dialogrutan
*	Välj typ i rullgardinslistan

<br/>*OBS!* Listan innehåller alla instanstyper.
<br/>*OBS!* Byte av instanstyp kan innebära att länkade entiteter i instansbeskrivningen behöver ändras, t.ex. MARC21-koder specifika för de olika instanstyperna eller RDA-entiteter.
   <br/>```Exempel:```
   <br/>```Bärartypen Ljudskiva - d under Instans hör till instanstypen Ljudinspelning och ska inte användas med andra instanstyper.```
   
Om det är mycket som behöver ändras kan det vara smidigare att radera de berörda egenskaperna och sedan berika från lämplig mall.
