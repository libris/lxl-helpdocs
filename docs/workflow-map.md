---
section: Materialtyper
title: Karta
order: 45
date: 2020-01-21
tags:
- under arbete
- karta
--- 

# Karta
Denna hjälptext beskriver ett antal vanligt förekommande egenskaper vid katalogisering av kartor. I de fall egenskaperna finns beskrivna i generell hjälptext upprepas inte informationen här utan istället finns en länk till relevant hjälptext. Egenskaper som är specifika för kartor redovisas däremot enbart här.

## Innehåll

[Inledning](#inledning)

| [Adminmetadata](#adminmetadata) | [Instans](#instans) | [Verk](#verk) | 
| ------ | ----------- |  ----------- |
| [Generell hjälptext för Adminmetadata](https://libris.kb.se/katalogisering/help/workflow-adminmetadata) | [Generell hjälptext för Instans](https://libris.kb.se/katalogisering/help/workflow-instance) | [Generell hjälptext för Verk](https://libris.kb.se/katalogisering/help/workflow-work) |
| | [Övriga fysiska detaljer](#ovriga-fysiska-detaljer) | [Genre/form (verk)](#verk) |
| | [Relief](#relief) | [Kartografisk data](#kartografisk-data) |
| | [Produktionsmetod](#produktionsmetod) | [Kompletterande innehåll index](#kompletterande-innehall-index) |                                                  
| | [Bärande material](#barande-material) | | 
| | [Applicerat material](#applicerat-material) | | 
| | [Färginnehåll](#farginnehall) | | 
| | [Genre/form (instans)](#farginnehall) | | 		
	
			
## Inledning
I nuläget finns endast en kartmall för tryckta kartor, men det är relativt enkelt att justera mallen så att den kan användas för katalogisering av en handritad kartresurs. [En kort beskrivning av hur man gör detta finns i slutet av denna hjälptext](#att-andra-i-kartmallen-sa-att-den-kan-anvandas-for-handritad-kartresurs).

För instruktioner om att länka till entitet, skapa lokal entitet och om hur formuläret fungerar i övrigt, se hjälptexterna under rubriken Katalogiseringsverktyget i hjälpsektionens vänstermeny. För information om katalogregler, skrivregler och övriga katalogiseringsanvisningar, [se Anvisningar för katalogisering - RDA](http://www.kb.se/rdakatalogisering/) samt [RDA Toolkit](http://access.rdatoolkit.org/).

## Adminmetadata
[Använd generell hjälptext för Adminmetadata](https://libris.kb.se/katalogisering/help/workflow-adminmetadata). 

## Instans
[Använd generell hjälptext för Instans](https://libris.kb.se/katalogisering/help/workflow-instance). Egenskaper som är specifika för Instans vid katalogisering av kartor redovisas nedan.

### Ovriga fysiska detaljer
 * Övriga fysiska detaljer (marc:otherPhysicalDetails = 300 #b)
Skriv in uppgiften om färginnehåll i klartext (färg, svartvit eller kolorerad). Här anges även layout såsom *motstående sidor* och *rygg mot rygg*.

### Relief
 * Relief (marc:relief = 008/18-21)
Ange hur höjdskillnader är återgivna på resursen. Länka till entitet. Trunkera för att få upp en lista över samtliga entiteter. 

### Produktionsmetod
 * Produktionsmetod/Benämning (productionMethod/label = 340 #d)
Ange produktionsmetod som lokal entitet. Lista över termer att använda vid beskrivning av produktionsmetod gällande kartor och stillbilder finns i RDA-anvisningarna.

### Barande material
 * Bärande material (baseMaterial = 007/00: a/01)
Länka till enitet. Välj bland entiteterna som benämns ”Material (kartor)”. Trunkera för att få upp en lista över samtliga entiteter. I mallen finns entiteten Papper/papp (marc/Paper) inlagd. Ändra vid behov.

 * Bärande material/Benämning (baseMaterial/label = 340 #a)
 Ange vid behov bärande material även som lokal entitet. Denna egenskap används framför allt vid katalogisering av handritade kartor. Lista över termer att använda för kartor och stillbilder finns i RDA-anvisningarna. I de fall flera entiteter behövs för korrekt beskrivning redovisas samtliga i en och samma ruta. 
 </br>```Exempel: papper och textil```

### Applicerat material
 * Applicerat material/Benämning (appliedMaterial/label = 340 #c)
Skapa lokal entitet . Ange applicerat material vid katalogisering av handritade kartor. Om flera entiteter behövs redovisas samtliga i en och samma ruta. Lista över termer att använda vid beskrivning av applicerat material gällande kartor och stillbilder finns i RDA-anvisningarna.
 </br>```Exempel: akvarell och penna```

### Farginnehall
 * Färginnehåll (colorContent = 007/00: a/03)
 Länka till enitet. Välj bland följande entiteter:
   * En färg (används för svartvita kartor)
   * Flera färger
   * Handkolorerad (Kartan, som framställts genom tryck- eller fotografisk process, har handkolorerats. Denna entitet används om man kan anta att hela upplagan är handkolorerad. Välj entiteten ”en färg” om det är ett specifikt exemplar som är handkolorerat. I det senare fallet redovisas uppgiften om att exemplaret är handkolorerat i beståndet).

I kartmallen finns entiteten Flera färger (marc/Multicolored) inlagd. Ändra vid behov. Observera att uppgift om färginnehåll (färg, svartvit eller kolorerad) även anges i klartext i egenskapen Övriga fysiska detaljer.

### Genre/form (instans)
 * Genre/form (genreForm = 007/00: a/01)
 Länka till entitet. Välj bland entiteterna med rubriken ”Särskild bärarbeteckning kartmaterial”. Trunkera för att få upp en lista över samtliga entiteter. 
 </br>I kartmallen finns entiteten Karta (marc/MapATwoDimensionalMap) inlagd. Ändra vid behov.
 
 * Genre/form/Typ av kartografiskt material(genreForm(marc) = 008/25)
 Länka till entitet. Välj bland entiteterna med rubriken ”Typ av kartografiskt material” Trunkera för att få upp en lista över samtliga entiteter. I kartmallen finns  entiteten ”Monografisk karta, utgiven ensam”(marc/SingleMap) inlagd. Ändra vid behov. Vid katalogisering av t.ex. atlas, ändra till ”Atlas/Kartbok, e”.

## Verk
[Använd generell hjälptext för Verk](https://libris.kb.se/katalogisering/help/workflow-work). Egenskaper som är specifika för Verk vid katalogisering av kartor redovisas nedan.

### Genre/form (verk)
 * Genre/form – TGM-termer (genreForm = 655 -/7 #a #2 TGM)
 Länka till entitet. Välj Genre/form i listan över typer. Sök på önskad term. I kartmallen finns redan TGM-termen Kartor inlagd. Lägg till fler vid behov. I nuläget går det inte att filtrera på enbart TGM-termer. Vid många sökträffar kan det därför vara bra att söka på termens id-nummer, som i nuläget enklast söks fram i Auktoritetsdatabasen (välj Genre i index, sök efter aktuell term).

### Kartografisk data

I nuläget måste koordinater och skala anges i både kodform och klartext. Ange uppgifterna inom egenskapen Kartografisk data, i en Kartografisk information för kodad data och i en annan sådan för data i klartext. Det ska även vara ytterligare en Kartografisk information som specificerar vilken typ av måttenhet för koordinaterna som används. I kartmallen finns samtliga tre Kartografisk information inlagda. 

#### Koordinater i kodform

Ange koordinater så exakt som möjligt, men om viss osäkerhet finns avrundas koordinaterna till en nära jämn siffra speglande kartans precision. Koordinaterna registreras i fyra underliggande egenskaper: västligaste longitud, östligaste longitud, nordligaste latitud, sydligaste latitud. Varje koordinat inleds med kod för halvklot/hemisfär (w = väst, e = öst, n = nord, s= syd) när måttenheten grader, minuter och sekunder används. Ange enbart siffror i de fall måttenheten är i SWEREF 99. Antalet siffror ska alltid vara sju.

 * Kartans västligaste longitud i kodform
 Kartografisk data/Kartografisk information/koordinater-Västlig gränslongitud (CartographicAttributes/Cartographic/ marc:westernmostLongitudeCoordinates = 034 #d)
  </br>```Exempel: e0144120```

 * Kartans östligaste longitud i kodform
 Kartografisk data/Kartografisk information/koordinater-Östlig gränslongitud (CartographicAttributes/Cartographic/ marc:eaternmostLongitudeCoordinates = 034 #e)
  </br>```Exempel: e0144155``` 

 * Kartans nordligaste latitud i kodform
 Kartografisk data/Kartografisk information/koordinater-Nordlig gränslongitud (CartographicAttributes/Cartographic/ marc:northernmostLongitudeCoordinates = 034 #f)
  </br>```Exempel: n0562905```

 * Kartans sydligaste latitud i kodform
 Kartografisk data/Kartografisk information/koordinater-Sydlig gränslongitud (CartographicAttributes/Cartographic/ marc:southernmostLongitudeCoordinates = 034 #g)
  </br>```Exempel: n0562825```

#### Skala i kodform
I de flesta fall är skalan linjär. Den linjära skalan är antingen horisontell eller vertikal. I kartmallen finns Linjär horisontell skala medtagen. Lägg till eller ändra skaltyp genom att skapa lokal entitet. Ange skalan med enbart siffror.
	</br>```Exempel: 20000```
  
 * Linjär horisontell skala:
 Kartografisk data /Kartografisk information/Skala/Linjär skala/Linjär horisontell skala med konstant proportion (CartographicAttributes/Cartographic/marc/constantRatioLinearHorizontalScale  = 034 #a a #b)

 * Linjär vertikal skala:
 Kartografisk data /Kartografisk information/Skala/Linjär skala/Linjär vertikal skala med konstant proportion (CartographicAttributes/Cartographic/marc/constantRatioLinearHorizontalScale = 034 #a a #c)

#### Kartprojektion
 * Kartografisk data/Kartografisk information/Kartprojektion (CartographicAttributes/Cartographic/projection = 008 22-23)
 </br>Länka till entitet. Trunkera (sök på * ) för att få upp en lista över samtliga entiteter. 

#### Koordinater i klartext
Ange koordinater så exakt som möjligt, men om viss osäkerhet finns avrundas koordinaterna till en nära jämn siffra speglande kartans precision. Lägg in koordinater i klartext i en Kartografisk information som inte innehåller kodad kartografisk data. Använd samma Kartografisk information som du använder till skala i klartext. Ange koordinaterna inom en parentes. Varje koordinat inleds med kod för halvklot/hemisfär (V = väst, Ö = öst, N = nord, S= syd) när måttenheten grader, minuter och sekunder används. Uteslut gärna sekunduppgiften i de fall denna inte används. 

 * Kartografisk data/Kartografisk information/koordinater (CartographicAttributes/Cartographic/coordinates =255 #c)
   <br/> ```Exempel:```
   * ```(Ö 17°53'10''-Ö 17°59'40''/N 59°21'30''-N 59°18'50'')```
   * ```(E569000-636000/N7003000-6958000)```
 
#### Skala i klartext
 * Kartografisk data/Kartografisk information/Skala/Skala/Benämning (CartographicAttributes/Cartographic/scale/scale/label =255 #a)
Ange skala i klartext i en Kartografisk information som inte innehåller kodad kartografisk data. Använd samma Kartografisk information som du använder till koordinater i klartext. Medta eventuell uppgift om skalstock i de fall exakt skalangivelse saknas. Lägg i dessa fall till semikolon mellan den uträknade skalangivelsen och uppgift om skalstock. Skalstocken anges enligt följande formel: Skalstock: x måttenheter = y cm.
 <br/>```Exempel:```
  * ```Skala 1:200 000```
  * ```Skala cirka 1:141 000 ; Skalstock: 1 svensk mil = 7,6 cm```

#### Typ av måttenhet för koordinaterna
 * Kartografisk data/Kartografisk information/koordinater (CartographicAttributes/Cartographic/coordinates =255 #c)
Lägg in  uppgift om typ av koordinater i en separat Kartografisk information. I regel används måttenheten grader minuter och sekunder. I kartmallen finns därför texten ” Måttenhet för koordinaterna: grader, minuter och sekunder (0-360°)” inlagd. Om måttenheten är SWEREF 99 TM ska texten ändras till: Måttenhet för koordinaterna: meter (SWEREF 99 TM)

### Kompletterande innehall index
 * Kompletterande innehåll (supplementaryContent/MARC = 008/31)
 <br/>Ange om resursen innehåller index eller ej.  Gäller framför allt kartböcker och atlaser. Länka till entitet.

### Att andra i kartmallen sa att den kan anvandas for handritad kartresurs
 1. Hämta mallen för Karta (tryckt kartmaterial)
 2. Ändra Verkstyp i rullgardinsmenyn till Karthandskrift
 3. Lägg till följande egenskaper inom Instans:
    * Produktion (production = 264 -/0)
      Används för opublicerade resurser. Komplettera med egenskapen Huvudsakligt tillgängliggörande. Använd inte egenskapen utgivning. [Läs mer om egenskaperna Produktion och Huvudsakligt tillgängliggörande i den generella hjälptexten för Instans](https://libris.kb.se/katalogisering/help/workflow-instance).
    * Bärande material/Benämning (baseMaterial/label = 340 #a)
      [Läs mer under Bärande material](#barande-material).
    * Applicerat material/Benämning (appliedMaterial/label = 340 #c
      [Läs mer under Applicerat material](#applicerat-material).
 4. Lägg till följande egenskap inom Instans av Verk:
    * Genre/form/Typ av kartografiskt material (genreForm(marc) = 008/33-34 e)
      Länka till entitet. Välj ”Handritad, e” med rubriken ”Särskilda formella egenskaper”
    * Genre/form – TGM-termer (genreForm = 655 -/7 #a #2 TGM)
      Länka till entitet. Välj Genre/form i listan över typer. Sök och lägg till termen ”Handritade kartor”.
