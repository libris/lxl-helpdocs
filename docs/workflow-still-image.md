---
section: Materialtyper
title: Stillbild
order: 52
date: 2019-04-03
tags:
- under arbete
- stillbild
- bildkatalogisering
--- 

## Stillbild

Denna hjälptext beskriver ett antal vanligt förekommande egenskaper vid katalogisering av stillbilder. I de fall egenskaperna finns beskrivna i generell hjälptext upprepas inte informationen här utan istället finns en länk till relevant hjälptext. Egenskaper som är specifika för stillbilder redovisas däremot enbart här. 

För instruktioner om att länka till entitet, skapa lokal entitet och om hur formuläret fungerar i övrigt, se Redigering i vänstermenyn. För information om katalogregler, skrivregler och övriga katalogiseringsanvisningar, se [Anvisningar för katalogisering - RDA](http://www.kb.se/rdakatalogisering/Anvisningar/Arbetsfloden/Bilder/) samt [RDA Toolkit](https://access.rdatoolkit.org/).

### Innehåll
| [Adminmetadata](#adminmetadata) | [Instans](#instans) | [Verk](#verk) | 
| ------ | ----------- |  ----------- |
| [Generell hjälptext för Adminmetadata](https://libris.kb.se/katalogisering/help/workflow-adminmetadata) | [Generell hjälptext för Instans](https://libris.kb.se/katalogisering/help/workflow-instance) | [Generell hjälptext för Verk](https://libris.kb.se/katalogisering/help/workflow-work) |
| | [Övriga fysiska detaljer](#instans) | [Språk](#verk) |
| | [Produktionsmetod](#produktionsmetod) | [Genre/form (verk)](#verk) |
| |  [Applicerat material](#applicerat-material)  | [Ämne](https://libris.kb.se/katalogisering/help/workflow-general-sh)  |
| | [Bärande material](#applicerat-material) | |                                                                
| | [Färginnehåll](#farginnehall) | |
| | [Genre/form (instans)](#farginnehall) | |
| | [Polaritet](#polaritet) | |



### Adminmetadata
Använd generell hjälptext för [Adminmetadata](https://libris.kb.se/katalogisering/help/workflow-adminmetadata).


### Instans
Använd generell hjälptext för [Instans](https://libris.kb.se/katalogisering/help/workflow-instance). Egenskaper som är specifika för Instans vid katalogisering av kartor redovisas nedan. 

#### Övriga fysiska detaljer
* Övriga fysiska detaljer (marc:otherPhysicalDetails = 300 #b)
Skriv in uppgiften om färginnehåll i klartext (färg, svartvit eller kolorerad). Här anges även layout, t.ex. ”båda sidorna” om bilder finns på bägge sidor av arket/arken.

#### Produktionsmetod
*	Produktionsmetod/Benämning (productionMethod/label = 340 #d)
  </br>Ange produktionsmetod som lokal entitet. 
  </br>Lista över termer att använda vid beskrivning av produktionsmetod gällande kartor och stillbilder finns i [RDA-anvisningarna](http://www.kb.se/rdakatalogisering/Anvisningar/Arbetsfloden/Bilder/#Produktionsmetod).

#### Applicerat material
*	Applicerat material/Benämning (appliedMaterial/label = 340 #c)
  </br>Ange applicerat material som lokal entitet. Om flera entiteter behövs redovisas samtliga i en och samma fältetikett.
  </br>```Exempel: akvarell och penna```  
  </br>Lista över termer att använda vid beskrivning av applicerat material gällande kartor och stillbilder finns i [RDA-anvisningarna](http://www.kb.se/rdakatalogisering/Anvisningar/Arbetsfloden/Bilder/#Applicerat%20material).

#### Bärande material 
*	Bärande material (baseMaterial (marc) = 007/00: k/01)
  </br>Länka till enitet. Välj bland entiteterna som benämns ”Bildens bärande material”. 
  </br>Trunkera för att få upp en lista över samtliga entiteter. 
  </br>I stillbildsmallen finns entiteten Papp och kartong inlagd. Ändra vid behov.

*	Bärande material/Benämning ((baseMaterial/label = 340 #a)
  </br>Ange bärande material som lokal entitet.
  </br>I de fall flera entiteter behövs för korrekt beskrivning redovisas samtliga i en och samma ruta.
  </br>```Exempel: papper och textil ```  
  </br>I stillbildsmallen finns entiteten Papper inlagd. Ändra vid behov. 
  </br>Lista över termer att använda vid beskrivning av bärande material gällande kartor och stillbilder finns i [RDA-anvisningarna](http://www.kb.se/rdakatalogisering/Anvisningar/Arbetsfloden/Bilder/#B%C3%A4rande%20material).

#### Farginnehall
* Färginnehåll (colorContent (marc) = 007/00: k/03)
  </br>Länka till enitet. Välj bland följande entiteter: 
    * En färg
    * Svartvit
    * Flera färger
    * Handkolorerad (Bilden, som framställts genom tryck- eller fotografisk process, har handkolorerats.)
    * Blandad färgstatus (En färg, svartvitt, flera färger och/eller handkolorering har kombinerats i ett verk eller en samling.)

  </br>I stillbildsmallen finns entiteten svartvit (marc/BlackAndWhite)  inlagd. Ändra vid behov. 
  </br>Observera att uppgift om färginnehåll (färg, svartvit eller kolorerad) även anges i klartext i egenskapen Övriga fysiska detaljer.

#### Genre/form (instans)
*	Genre/form (genreForm (marc) = 007/00: k/01)
  </br>Länka till entitet. Välj bland entiteterna med rubriken ”Särskild bärarbeteckning för bilder”. Trunkera för att få upp en lista över samtliga entiteter. 
  </br>I stillbildsmallen finns entiteten bilder (marc/Picture) inlagd. Ändra vid behov till mer specifik entitet.
 	
#### Polaritet
*	Polaritet/Benämning (polarity/label= 340 #o)
  </br>Använd Polaritet vid katalogisering av fotografier. Ange polaritet som lokal entitet. Välj bland följande två entiteter:
    * positiv
    * negativ
  </br>I stillbildsmallen är entiteten positiv inlagd. Radera uppgiften om det är annat än fotografier som katalogiseras.

### Verk
Använd generell hjälptext för [Verk](https://libris.kb.se/katalogisering/help/workflow-work). Egenskaper som är specifika för Verk vid katalogisering av stillbild redovisas nedan.

#### Språk
*	Språk (language (marc) = 008/35-37)
  </br>Länka till entitet. För stillbilder utan text, välj Icke-språkligt medium (=language/zxx). Denna entitet är förvald i stillbildsmallen, ändra vid behov.

  </br>Se även: [Allmän hjälptext om verk](https://libris.kb.se/katalogisering/help/workflow-work) under rubriken Språk.

#### Genre/form (verk)
*	Genre/form(genreForm (marc) = 008/33)
  </br>Länka till enitet. Välj bland entiteterna med rubriken ”Typ av visuell resurs.” Trunkera för att få upp en lista över samtliga entiteter. 
  </br>I stillbildsmallen finns entiteten bilder (marc/Picture) inlagd. Ändra vid behov till mer specifik entitet.

*	Genre/form – TGM-termer (genreForm = 655 -/7 #a, #2 TGM)
  </br>Länka till entitet. Välj Genre/form i listan över typer. Sök på önskad term. 
  </br>I stillbildsmallen finns redan TGM-termen Bilder inlagd. Lägg till fler vid behov.
  </br>I nuläget går det inte att filtrera på enbart TGM-termer. Vid många sökträffar kan det därför vara bra att söka på termens id-nummer, som i nuläget enklast söks fram i [Auktoritetsdatabasen](https://regina.kb.se/F/7VGI9HCC7P3Y15JJFPNIGGGLLKTN7V64EAXH7BUV3PGV9HMKNV-10490?func=file&file_name=scan&local_base=kbs10) (välj Genre i index, sök efter aktuell term).  
