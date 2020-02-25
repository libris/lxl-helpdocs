---
section: Materialtyper
title: Äldre tryck
order: 58
date: 2020-02-25
tags:
- under arbete
- äldre tryck
--- 

# Äldre tryck
Denna hjälptext beskriver ett antal vanligt förekommande egenskaper vid katalogisering av äldre tryck. 

## Innehåll  

[Inledning](#inledning)

| [Adminmetadata](#adminmetadata) | [Instans](#instans) | [Verk](#verk) | [Bestånd](#bestand) |  
| ------ | ----------- |  ----------- | ------------ |
| [Generell hjälptext: Adminmetadata](https://libris.kb.se/katalogisering/help/workflow-adminmetadata) | [Generell hjälptext: Instans](https://libris.kb.se/katalogisering/help/workflow-instance) | [Generell hjälptext: Verk](https://libris.kb.se/katalogisering/help/workflow-work) | [Generell hjälptext: Bestånd](https://libris.kb.se/katalogisering/help/workflow-holding) | 
| [Katalogiseringsspråk](#katalogiseringssprak) | [Titel och upphov](#titel-och-upphov) | [Medverkan och funktion](#medverkan-och-funktion) | [Ägarhistorik](#agarhistorik) | 
| [Katalogiseringsregler](#katalogiseringsregler) | [Identifikator](#identifikator) | [Klassifikation](#klassifikation) | [Exemplarinformation](#exemplarinformation) |
|[Anmärkning om katalogiseringskälla](#anmarkning-om-katalogiseringskalla)| [Fingerprint](#fingerprint) | [Ämne](#amne) | [Bokband](#bokband) | 
| | [Upplageuppgift](#upplageuppgift) | [Innehållstyp](#innehallstyp) | |
| | [Utgivning](#utgivning) | | |
| | [Huvudsakligt tillgängliggörande](#huvudsakligt-tillgangliggorande) | | |
| | [Tillverkning](#tillverkning) | | | 
| | [Omfång](#omfang) | | |
| | [Övriga fysiska detaljer](#ovriga-fysiska-detaljer) | | |
| | [Mått](#matt) | | |
| | [Medietyp](#medietyp) | | |
| | [Bärartyp](#barartyp) | | |
| | [Numrering i seriell resurs](#numrering-i-seriell-resurs)
| | [Seriemedlemskap](#seriemedlemskap) | | |
| | [Anmärkning](#anmarkning) | | |
| | [Citering i referatorgan](#citering-i-referatorgan) | | |
| | [Namn på orter och territorier](#namn-pa-orter-och-territorier) | | |

## Inledning
Med äldre tryck avses skrifter som har framställts i handpress. Det omfattar nästan allt material som är tryckt före 1830. Nya Libris är anpassat efter katalogisering enligt RDA men äldre tryck katalogiseras enligt ISBD. Några anvisningar rör därför skillnader mellan RDA och ISBD.

* För generella instruktioner om hur man lägger in nedanstående egenskaper, [se den generella hjälptexten Adminmetadata](https://libris.kb.se/katalogisering/help/workflow-adminmetadata), [den generella hjälptexten Instans](https://libris.kb.se/katalogisering/help/workflow-instance) respektive [den generella hjälptexten Verk](https://libris.kb.se/katalogisering/help/workflow-work).
* För katalogiseringsanvisningar, [se Anvisningar för äldre tryck](http://www.kb.se/katalogisering/Katalogisering/aldre-tryck/ "Anvisningar för äldre tryck").
* [Funktionen Berika från mall som beskrivs i hjälptexten Redigera och uppgradera](https://libris.kb.se/katalogisering/help/edit-upgrade) är ofta användbar när man vill lägga till egenskaper i en befintlig post. Mallarna Äldre tryck, Bok eller Tryckt seriell resurs kan exempelvis vara användbara.

I vissa fall fungerar det ännu inte fullt ut att lägga till alla uppgifter som beskrivs i denna hjälptext. Arbete pågår med att förbättra gränssnittet. För att anmäla fel, [använd detta formulär för Felrapportering nya Libris och XL](https://docs.google.com/forms/d/e/1FAIpQLSfOChJOGDoHUQguSF83F5XyTZiQL-yU47nvcqb6qwNT9GX7Aw/viewform). För att lämna synpunkter, [använd detta formulär för  Ändringsförslag nya Libris och XL](https://docs.google.com/forms/d/e/1FAIpQLScgz_0enebhBn6uB8xvowkDBB4ax_dbvaobLSFfqFMoty6eQg/viewform).

## Adminmetadata

### Katalogiseringssprak  
* Katalogiseringsspråk (040 #b)  
  Används numera även för äldre tryck. Egenskapen började anges vid övergången till RDA men är inte en RDA-specifik uppgift. Ta alltså inte bort uppgiften när du katalogiserar med hjälp av äldretrycksmallen eller poster som andra Libris-bibliotek har skapat. Vid postimport låter man uppgiften ligga kvar men man behöver inte lägga till om det saknas.
  
  ![Katalogiseringsspråk](adminkatsprak.png)
  
  
### Katalogiseringsregler  
* Katalogiseringsregler (040 #e)  
  Äldre tryck katalogiseras enligt ISBD. Ta bort Katalogiseringsregler: rda genom att klicka på papperskorgen till höger om egenskapen.
  
  ![Katalogiseringsregler rda](adminkatreglerrda.png)
  
  Sök fram och länka till "ISBD-interpunktion finns - i" om det saknas. Klicka på plustecknet till vänster om "Katalogiseringsregler" för att få fram sökrutan. När man sparar ändras frasen till "marc/Isbd".
  
  ![Katalogiseringsregler isbd](adminkatreglerisbd.png)
  
### Anmarkning om katalogiseringskalla  
* Anmärkning om katalogiseringskälla (588 #a)  
  Här kan man för äldre tryck bland annat ange att beskrivningen är osäker på grund av att titelblad saknas. Egenskapen finns med i mallen för äldre tryck men den kan för närvarande inte läggas till i befintliga poster. Använd i stället [funktionen Berika från mall som beskrivs i hjälptexten Redigera och uppgradera](https://libris.kb.se/katalogisering/help/edit-upgrade). Välj äldretrycksmallen.
  
  ![Katalogiseringskälla](adminkatkalla.png)
 

## Instans
  
### Titel och upphov  

#### Hela referenstiteln i Huvudtitel    
* Har titel/Titel/Huvudtitel (245 #a)  
Till referenstiteln räknas all text före impressum, inklusive upphovsuppgifter och oftast även upplageuppgifter. Hela referenstiteln bör anges i Huvudtitel om syntaxen bryts eller om man skulle behöva ändra ordningsföjden på titel-, upphovs- och upplageuppgifterna.

Monografi:
![Referenstitel i Huvudtitel - monografi](insttitelmon.png) 


Flerbandsverk:
![Referenstitel i Huvudtitel - flerbandsverk](insttitelfv.png)

#### Referenstiteln i Huvudtitel, Övrig titelinformation och Upphovsuppgift
Referenstiteln kan anges i Huvudtitel, Övrig titelinformation och Upphovsuppgift om syntaxen inte bryts eller om ordningsföljden inte behöver ändras.

Monografi:
![Referenstitel i Har titel och Upphov](insttitelupphov.png)


### Identifikator
Arbetsnoteringar i SB17- och COL-poster har placerats här (024).
 
![Identifikator](instidentifikator.png)


### Fingerprint
Fingerprint rekommenderas inte men möjligheten finns att ange det här.
* Identifikator/Fingerprint/Värde (026)
  * Klicka på det stora plustecknet i högermarginalen.
  * Sök efter och välj Identifikator i sidorutan.
  * Välj Fingerprint i rullgardinsmenyn Välj typ.
  * Klicka på plustecknet till höger om Fingerprint.
  * Sök efter och välj Värde i sidorutan. Skriv in uppgiften i Värde.
  * Sök efter och välj Källa.
  * Välj Källa i Skapa lokal entitet.
  * Klicka på plustecknet till höger om Källa.
  * Sök efter och välj Kod. Skriv in koden i Källa.
  
 ![Fingerprint](instfingerprint.png)  
  
  
### Upplageuppgift
* Upplageuppgift (250 #a)  
  Upplageuppgifter i äldre tryck anges sällan här utan i sitt sammanhang, som del av titel- eller utgivningscitatet. Kan exempelvis användas när upplageuppgift saknas i trycket.
  
  ![Upplageuppgift](instuppl.png)
 
  
### Utgivning  
* Utgivning  
  I RDA är det obligatoriskt att ange utgivningsort, utgivarnamn och utgivningsår. Tryck- eller copyrightår räknas exempelvis inte som utgivningsår. Dessa uppgifter måste därför klamras enligt RDA.
Nutida uppdelning av olika funktioner (utgivare, tryckare, distributör och försäljare) stämmer inte för handpresstiden. Tills vidare räknas därför tryckuppgifter som utgivningsuppgifter och klamras inte.
Impressum anges enbart i Plats om det finns någon tryck- eller utgivningsuppgift i trycket.
Impressum anges i Plats, Agent och Datum/År om det inte finns några tryck- eller utgivningsuppgifter i trycket.
 
#### Utgivningsplats
* Plats/Plats/Benämning (264 -/1 #a)  
  Här anges vanligtvis tryckort, tryckare etc. och tryckår.
  
  Fullständiga tryckuppgifter i trycket:
  ![Fullständiga tryckuppgifter](insttryckfull.png)
  
  Ofullständiga tryckuppgifter i trycket:
  ![Ofullständiga tryckuppgifter](insttryckofull.png)
  
  Tryckuppgifter saknas:
  ![Tryckuppgifter saknas](insttrycksaknas.png) 
 
  
#### Utgivarnamn
* Agent/Agent/Benämning (264 -/1 #b)  
  Här anges vanligtvis sannolika uppgifter om tryckare etc.
  
  Tryckeriuppgift saknas i trycket:
  ![Tryckeriuppgift saknas](insttryckagent1.png)
  
  Okänd tryckare, utgivare:
  ![Okänd tryckare](insttryckagent2.png)
  
#### Ar och datum 
* År (008/07-10, 264 -/1 #c)  
  Här anges vanligtvis tryckår. Egenskapen År ska alltid anges och får endast förekomma inom Primär utgivning. Året anges med fyra tecken, siffror (0-9) och/eller bokstaven u. Om fullständigt tryckår står i trycket räcker det med att ange År. Uppgiften motsvarar tryckåret i 008 och 264 #c.
  
  ![Tryckår](insttryckar.png)    
  
* Start- och slutår (flerbandsverk)  
  Om årtalen anges utan klammer eller andra tecken utöver fyra positioner, räcker det att ange årtalen här.
  
  ![Start- och slutår](insttryckstartar.png)
  
  
  <br/>Om tryckår saknas eller är ofullständigt använder man även Datum.
  
* Datum (264 -/1 #c)    
  Här anges tryckår som måste anges med fler än fyra tecken.
  
  Tryckår saknas i trycket:
  ![Tryckår saknas](insttryckdatum1.png)
  
  Sannolikt tryckår:
  ![Sannolikt tryckår](insttryckdatum2.png)
  
  Flerbandsverk:
  ![Tryckår för flerbandsverk](insttryckdatum3.png) 
  
  
### Huvudsakligt tillgangliggorande
Egenskapen används för äldre tryck tillsammans med Utgivning när tryckåret är osäkert men ett intervall kan anges. I Utgivning anges de uppgifter som står i trycket, som vanligt. Landkoden tas bort eftersom den ska anges i Huvudsakligt tillgängliggörande.

* Huvudsakligt tillgängliggörande/Primär utgivning (264)
  * Klicka på det stora plustecknet och välj Huvudsakligt tillgängliggörande.
  * Välj Primär utgivning i rullgardinsmenyn.
  * Flera av de egenskaper som då dyker upp är inte adekvata när man ska ange intervall. Plats, Agent och Datum anges i Utgivning, inte här. De försvinner när man sparar eftersom det inte finns något innehåll i dem. 
  * Landkod måste läggas till (country/sw är inte förval).
  * Klicka på plustecknet till höger om Primär utgivning
  * Sök efter och välj Kompletterande datum samt Typ av utgivningsdatum.
  * Skriv in troligt startår i År.
  * Skriv in troligt slutår i Kompletterande datum.
  * Välj Osäkert årtal i Typ av utgivningsdatum.
  
  ![Huvudsakligt tillgängliggörande](insthuvudsakligt.png)
   
### Tillverkning 
* Tillverkning (264 -/3)  
Egenskapen används vanligtvis inte vid katalogisering av äldre tryck. I SB17-poster har tryckuppgifter i normaliserad form lagts i 260 #e och #f. Dessa uppgifter har i nya Libris placerats här. Numera anger vi:

  * tryckorter i Har biuppslag - Namn på orter och territorier (752 #a och #d)
  * tryckare i Medverkan och funktion/Agent/Organisation (710 #a).
  
För orter som har bytt namn och ibland även landtillhörighet kan man tills vidare ange det dåtida ortnamnet i standardiserad form här. I nya Libris finns nämligen ingen motsvarighet till fält 751.

![Tillverkning](insttillverkning.png)
   
### Omfang   
* Omfång/Omfång/Benämning (300 #a)  
  Enligt RDA ska man inte förkorta sidor, planschblad etc. Vi förkortar så länge vi katalogiserar enligt ISBD.
  
  Monografi:
  ![Omfång för monografi](instomfang1.png)
  
  Flerbandsverk:
  ![Omfång för flerbandsverk](instomfang2.png)
    
  
### Ovriga fysiska detaljer   
* Övriga fysiska detaljer (300 #b)

![Övriga fysiska detaljer](instovrigafysiska1.png) 
  

### Matt 
* Mått/Mått/Benämning (300 #c)

![Mått](instmatt.png) 
  
### Medietyp
* Medietyp (337 #b)  
  Används numera även för äldre tryck. Egenskapen började anges vid övergången till RDA men är inte en RDA-specifik uppgift. Ta alltså inte bort uppgiften när du katalogiserar med hjälp av äldretrycksmallen eller poster som andra Libris-bibliotek har skapat. Vid postimport låter man uppgiften ligga kvar men man behöver inte lägga till om det saknas.
  
 Omedierad:
 ![Medietyp](instmedietyp.png)
 
  
### Barartyp
* Bärartyp (338 #b)  
  Används numera även för äldre tryck. Egenskapen började anges vid övergången till RDA men är inte en RDA-specifik uppgift. Ta alltså inte bort uppgiften när du katalogiserar med hjälp av äldretrycksmallen eller poster som andra Libris-bibliotek har skapat. Vid postimport låter man uppgiften ligga kvar men man behöver inte lägga till om det saknas.
  
 Volym:
 ![Bärartyp volym](instbarartyp1.png)
 
 Ark:
 ![Bärartyp ark](instbarartyp2.png)
  
  
### Numrering i seriell resurs   
* Har numrering av seriell resurs/Numrering av seriell resurs/Benämning (362 0/- #a)<br/> 
  Används i poster för seriella resurser. Uppgiften normaliseras vanligtvis inte när man katalogiserar äldre tryck.
  
  ![Numrering](instnumrering.png)
  
### Seriemedlemskap
* Seriemedlemskap/Seriemedlemskap/Ingår i serie  
  Inte så ofta man behöver ange att en skrift ingår i en serie. Ofta räcker det då att ange Serieuppgift, Numrering inom serie och Indikator för seriebiuppslag.
  
  ![Seriemedlemskap](instserie.png)

 
### Anmarkning
* Anmärkning (hasNote)/Anmärkning (Note)/Benämning (500 #a)   
  Skriv in allmänna anmärkningar i Benämning.
  
  ![Anmärkning](instanmarkning.png)

### Citering i referatorgan    
  Egenskapen finns med i mallen för äldre tryck. Den går att lägga till i befintliga poster men det är mycket krångligt. Använd i stället [funktionen Berika från mall som beskrivs i hjälptexten Redigera och uppgradera](https://libris.kb.se/katalogisering/help/edit-upgrade). Välj äldretrycksmallen. Välj Duplicera entitet om om fler entiteter ska läggas in. Alternativ lösning är att kopiera en post som har följande egenskaper med:
* Indexerad i/Instans/Har titel/Titel (510 #a)
* Indexerad i/Instans/Anmärkning/Benämning (510 #c)

![Citering](instcitering.png)

### Namn pa orter och territorier
  Här anges tryckorter i standardiserad form. Det går numera att ange flera tryckorter via plustecknet till vänster om Har biuppslag - Namn på orter och territorier.
  Egenskapen finns med i mallen för äldre tryck. Den går att lägga till i befintliga poster men det är lite krångligt. Använd förslagsvis [funktionen Berika från mall som beskrivs i hjälptexten Redigera och uppgradera](https://libris.kb.se/katalogisering/help/edit-upgrade). Välj äldretrycksmallen.

Lägga in manuellt:  
* Klicka på det stora plustecknet i högermarginalen.
* Sök efter och välj Har biuppslag - Namn på orter och territorier i sidorutan.
* Klicka på plustecknet intill rubriken.
* Sök efter och välj Land / Överordnat territorium i sidorutan.
* Sök efter och välj Stad, kommun i sidorutan.
* Skriv in land och stad i respektive ruta.

![Namn på orter](instorter.png)
  
#### Orter som har bytt namn och landtillhörighet    
I Voyager lade man vid behov till dåtida ortnamn i fält 751 eftersom man där inte behövde ange landtillhörighet, till skillnad från i fält 752. Det finns ingen motsvarighet till 751 i nya Libris. Jag föreslår därför att vi tills vidare anger orter som heter något annat nu i Tillverkning.    
  
## Verk   

### Medverkan och funktion  
* Medverkan och funktion/Medverkan/Agent/Organisation (710 #a)  
  Tryckare, utgivare etc. borde anges i Instans eftersom de har en relation till instansen, inte verket. Det fungerar dock inte för närvarande. Vi anger dem därför i Instans av Verk i stället. [Se exempel i hjälptexten Relationer till Agent](https://libris.kb.se/katalogisering/help/workflow-agent-org-instance)
  
  Tryckare:
  ![Tryckare](verktryckare.png) 

### Klassifikation  
* SAB-klassifikation  
  SOT,- SB17- och COL-poster innehåller förkortade SAB-koder. Ange gärna dessa förkortade SAB-koder vid primär- eller sekundärkatalogisering. Ta då bort Version: 8.
  
  ![SAB](verksab.png)
  
### Amne  
* Kontrollerat, ej auktoriserat ämnesord (650 #2)   
  SOT-projektet skapade ämnesord av rubrikerna i Nils Herman Quidings "Svenskt allmänt författningsregister för tiden från år 1522 till och med år 1862". Library of Congress godkände 2008 Quiding som ett godkänt ämnesordssystem. SOT-poster innehåller därför listkoden "quiding". Man kan använda dessa ämnesord och listkoden "quiding" vid katalogisering av en saknad förordning som ingår i Quiding författningsregister. Se anvisningar i hjälptexten [Ämnesord som lokal entitet](https://libris.kb.se/katalogisering/help/workflow-local-entity-sh).
  
  ![Quiding](verkquiding.png)
  
### Innehallstyp
* Innehållstyp/Innehållstyp (336 #b)   
  Används numera även för äldre tryck. Egenskapen började anges vid övergången till RDA men är inte en RDA-specifik uppgift. Ta alltså inte bort uppgiften när du katalogiserar med hjälp av äldretrycksmallen eller poster som andra Libris-bibliotek har skapat. Vid postimport låter man uppgiften ligga kvar men man behöver inte lägga till om det saknas.
  
  Text:
  
  ![Innehållstyp](verkinnehallstyp.png) 
  
## Bestand

### Agarhistorik
* Ägarhistorik (561 #a)   
  Man kan för närvarande inte upprepa egenskapen Ägarhistorik. Alla proveniensuppgifter läggs därför in på ett ställe.
  * Klicka på plustecknet i högermarginalen.
  * Sök efter och välj Ägarhistorik i sidorutan.
  * Skriv in uppgiften.
  
  En proveniensuppgift:
  ![En proveniensuppgift](bestprov1.png)
  
  Två proveniensuppgifter:
  ![Två proveniensuppgifter](bestprov2.png) 
  
### Exemplarinformation
* Igenkänningstecken (562 #a) och Identifiering av exemplar (562 #b)  
  * Klicka på plustecknet i högermarginalen.
  * Sök efter och välj Har lokal anmärkning: identifiering av exemplar, kopia eller version i sidorutan.
  * Klicka på plustecknet intill Har lokal anmärkning: Identifiering …
  * Klicka på plustecknet till höger om Lokal anmärkning: Identifiering …
  * Sök efter och välj Igenkänningstecken i sidorutan.
  * Sök efter och välj Identifiering av exemplar i sidorutan.
  * Skriv in uppgifterna.<br/><br/>  
  Klicka på plustecknet till vänster om Har lokal anmärkning: Identifiering ... för fler anmärkningar.
  
 ![Exemplarinformation](bestexemplar.png)
  
### Bokband
* Har lokal anmärkning: Bokband/Lokal anmärkning: Bokband/Benämning (563 #a)   
  I de flesta fall räcker det att ange en bokbandsuppgift. Vid behov kan man upprepa Benämning. I MARC21 hamnar då anmärkningarna i varsitt delfält. Det går för närvarande inte att upprepa Har lokal anmärkning: Bokband.       
  * Klicka på plustecknet i högermarginalen.
  * Sök efter och välj Har lokal anmärkning: Bokband i sidorutan.
  * Klicka på plustecknet intill Har lokal anmärkning: Bokband.
  * Klicka på > intill Lokal anmärkning: Bokband.
  * Skriv in uppgiften i Benämning.  
  Klicka på plustecknet intill Benämning för fler anmärkningar.
  
  ![Bokband](bestbokband.png)
