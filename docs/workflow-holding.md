---
section: Hjälptexter bestånd
title: Beståndsregistrering
order: 136
date: 2020-03-02
tags:
- bestånd
- beståndsregistrering
--- 

# Beståndsregistrering

Det är endast bibliotekskod/sigel som är obligatorisk och den sätts automatiskt när du väljer att lägga bestånd. (852 #b)

Bestånd kan läggas direkt ifrån träfflistan. Från träfflistan ser du om ditt bibliotek har bestånd och hur många andra bibliotek som har bestånd. Kortkommando för att lägga bestånd är alt+b.

De mest använda fälten finns färdiga att fylla i. Det motsvarar vad som kunde göras i Libris webbregistrering. Övriga fält läggs till via plustecknet för bestånd. Det är viktigt använda rätt plustecken. 

Plustecken i sidorutan Lägg till egenskaper under bestånd används för vad som motsvarande fält i marc. 

Plustecken intill det som valts väljer man det som motsvarar delfält.

Du behöver inte ta bort tomma egenskaper när du sparar. Systemet tar bort dem automatiskt.

## Innehåll   

| [Adminmetadata](#adminmetadata)  | [Bestånd](#bestånd) | 
| -----------  |  ----------- |
| [Adminmetadata](#adminmetadata) | [Har komponent](#har-komponent) |
| | [Anmärkningar](#anmarkningar) |
| | [Lokala ämnesord och klassifikation](#lokala-amnesord-och-klassifikation) |
| | [Agenter](#agenter)  |
| | [Elektronisk adress](#elektronisk-adress) |
| | [Oformaterad beståndsuppgift](#oformaterad-bestandsuppgift) |
| | [Exemplarinformation](#exemplarinformation) |
| | [Lokalt definierade beståndsfält](#lokalt-definierade-bestandsfalt) |


## Adminmetadata
För enkla monografier behöver vanligen inte Adminmetadata läggas till eller ändras. *Hör av dig till Supportforumet om du saknar möjlighet att lägga till Adminmetadata som ditt bibliotek behöver.*
* Posttyp. Om inget val görs blir värdet (000 [6] u). För att ändra värde lägg till Posttyp och välj i lista (000 [6])
  * Fortlöpande (seriell eller integrerande) resurs) (000 [6] y)
  * Monografisk resurs (000 [6] x)
  * Monografisk resurs (1 bibliografisk post med flera delar) (000 [6] v)
  
* Beskrivningsnivå (000 [17])
  * Beskrivningsnivå anges inte för bestånd. Defalultvärde är u. Vid export till lokalt system hamnar informationen i 841 #e.

* Katalogisatörens anmärkning (599 #a)

## Har komponent
(852)
OBS! I konverterade data med bara ett 852 ligger delfälten inte under Har komponent. Vid skapande av nytt bestånd måste de delfält som  motsvarar delfält i 852 läggas under Har komponent för det ska bli korrekt. För att uppdatera en konverterad post som inte har Har komponent behöver du ta bort de konverterade fälten som ligger fel och lägga dem under Har komponent. 

I Bestånd finns följande fält färdiga:
* Hyllplacering (Avdelning,samling) (852 #c)
Om ytterligare information om placering utöver Hyllkod behöver läggas till.
<br/>```Exempel: Institution 140```
  
* Hyllkod (852 #h)
Här lägger du uppställning efter klassifikation eller annan hyllkod
<br/>```Exempel: 158.1```

* Hyllsignum: Uppställningsord (852 #l)
<br/>```Exempel: AND```

* Hyllsignum: Löpnummer (852 #j)
<br/>```Exempel: 2694```

* Katalogisatörens anmärkning (852 #x)
 
Många ytterligare egenskaper kan läggas till för Har komponent - Lägg till egenskaper under Bestånd vid Har Komponent. Där kan du söka upp följande:
* Tidigare hylluppställning (852 #d)

* Precisering av hyllplacering (852 #g)

* Exemplarstatus (852 #i) 
Klicka på plustecknet vid Exemplarstatus - Lägg till exemplarplarstatus. Ett antal vanliga beskrivningar finns att länka till. Sök fram dessa med en asterisk. 

**Exempel länkad exemplarstatus:**
<br/>![Exempel länkad exemplarstatus](lankadexemplarstatus.png)

Skapa andra beskrivningar som lokal entitet / Lägg åter till egenskaper under Exemplarstatus och klicka sedan på plusikonen och välj Benämning.


**Exempel på exemplarstatus som lokal entitet:**
<br/>![Exempel på exemplarstatus som lokal entitet](exemplarstatus.png)


* Prefix för lokalsignum (852 #k)
* Suffix för lokalsignum (852 #m)
* Unik exemplarbeteckning (streckkod) (852 #p)
* Exemplarets fysiska tillstånd (852 #q)
* Exemplarnummer (852 #t)
* URI (852 #u)
* Anmärkning (hasNote) (852 #z) /Lägg till anmärkning/Benämning
<br/>```Exempel: S. [7]-[8] saknas```

* Del av materialet som avses (852 #3) /Lägg till entitet/Skapa lokal entitet/Resurs/Lägg till egenskaper under Resurs/Benämning 

**Exempel på Del av materialet som avses:**
<br/>![Exempel på Del av materialet som avses](delavmaterial.png)

* Underordnad institution/enhet (852 #9)

Klicka på plustecknet vid Har komponent för att lägga till ytterligare ett bestånd (motsvarande flera 852)

## Anmarkningar
* Anmärkning/hasNote (500 #a). Lägg till anmärkning vid plustecknet vid Anmärkning. 

* Villkor för användning och åtkomst (506)

**Exempel på Villkor för användning och åtkomst:**
<br/>![Exempel på Villkor för användning och åtkomst](Villkoranvbenamn.png)

* Lägg till egenskaper under Bestånd/Villkor som användning och åtkomst/Lägg till entitet/Skapa Lokal entitet/ Villkor som användning och åtkomst/Lägg till egenskaper under: Villkor för användning och åtkomst


  * Benämning (506 #a)
  * Tillståndsgivare (506 #b)
  * Fysiska omständigheter (506 #c)
  * Godkända användare (506 #d)
  * Laglig grund för restriktion (506 #e)
  * Standardiserad terminologi för åtkomstbegränsning (506 #f)
  * URI (506 #u)
  *  Del av materialet som avses (506 #3) /Lägg till entitet/Skapa lokal entitet/Resurs/Lägg till egenskaper under Resurs/Benämning 

* Sammanfattning av innehåll (520)
* Lägg till egenskaper under Bestånd/Sammanfattning av innehåll/Lägg till sammanfattning
  * Benämning (520 #a)
* Lägg till egenskaper under Sammanfattning
  * Utförligare anmärkningstext (520 #b)
  * Instans som åsatt anmärkning/etikett (520 #c)
  * URI (520 #u)

* Förvärvsuppgifter (541)
* Lägg till egenskaper under Bestånd/ Förvärvsuppgifter /Lägg till förvärvsuppgifter /Skapa lokal entitet /Lägg till egenskaper under Förvärsuppgifter
  * Sekretessbelagd information / Klicka i boxen (541 indikator 1) 0 = ifylld, 1 = ej ifylld. 
  * Förvärvskälla (541 #a)
  * Adress (541 #b)
  * Förvärvssättt (541 #c)
  * Förvärvsdataum (541 #d)
  * Accessionsnummer (541 #e)
  * Ägare (541 #f)
  * Anskaffningspris (541 #h)
  * Del av materialet som avses (541 #3) /Lägg till entitet/Skapa lokal entitet/Resurs/Lägg till egenskaper under Resurs/Benämning 

* Ägarhistorik (561 #a)

* Har lokal anmärkning: Identifiering av exemplar, kopia eller version (562)
  * Igenkänningstecken (562 #a) 
  * Identifiering av exemplar (562 #b)
  * Identifiering av version (562 #c)
  * Presentationsformat (562 #d)
  * Antal exemplar (562 #e)
  * Del av materialet som avses (562 #3) /Lägg till entitet/Skapa lokal entitet/Resurs/Lägg till egenskaper under Resurs/Benämning 

* Har lokal anmärkning: Bokband (563)
  * Benämning (563 #a)

* Har lokal anmärkning: Åtgärd (583)
* Lägg till egenskaper under Lokal anmärkning Åtgärd/ Klicka därefter på plustecknet till höger om Lokal anmärkning: Åtgärd för att lägga till delfält och indikator
  * Sekretessbelagd information / Klicka i boxen (583 indikator 1) 0 = ifylld, 1 = ej ifylld. 
  * Benämning (583 #a)
  * Del av materialet som avses (563 #3) /Lägg till entitet/Skapa lokal entitet/Resurs/Lägg till egenskaper under Resurs/Benämning 

## Lokala amnesord och klassifikation
Lägg i första hand ämnesord och klassifikation till det beskrivna verket.
* För ämnesord, [se hjälptexten Ämnesord i Libris](https://libris.kb.se/katalogisering/help/workflow-general-sh)

* Lokala ämnesord/rubriker (övriga) (698)
  * Kod (698 #a)
  * Benämning (698 #b)

* För Klassifikation
[Se generell hjälptext om Verk](https://libris.kb.se/katalogisering/help/workflow-work) under rubriken Klassifikation.

## Agenter
Här anges agenter som hör till bestånd eller exemplarbeteckning.
Länka till auktoriteter i första hand, men det går att skapa en lokal entitet för en agent. [Se hjälptexten Relationer till Agent]( https://libris.kb.se/katalogisering/help/workflow-agent-org-instance).
  * För relationer till agenters verk, [se hjälptexten Relation till delar och verk](https://libris.kb.se/katalogisering/help/workflow-agent-relation).

## Elektronisk adress
* Tillhörande media /Lägg till Mediaobjekt/Skapa lokal entitet/URI (856 4/0)
Länk till den elektroniska resurs som är den bibliografisk resurs som beskrivs

* Annan relaterad resurs /Lägg till Elektronisk/Skapa lokal entitet (856 4/1)
Länk till elektronisk resurs av en icke elektronisk bibliografisk resurs som beskrivits

* Relaterad beskrivning eller innehåll /Lägg till entitet/Skapa lokal entitet/Dokument (856 4/2)
Länk till relaterad resurs till den bibliografiska resursen, men som inte är en annan resurs. Egenskapen Del av materialet som beskrivs (#3) kan användas för att beskriva relationen.

Egenskaper att lägga till:
  * URI (856 #u)
  * Katalogisatörens anmärkning (856 #x)
  * Länktext (856 #y)
  * Offentlig anmärkning (856 #z)
  * Del av materialet som avses (856 #3) /Lägg till entitet/Skapa lokal entitet/Resurs/Lägg till egenskaper under Resurs/Benämning 

### Oformaterad bestandsuppgift
* Beståndsuppgift (866 #a)
* Katalogisatörens anmärkning (866 #x)
* Offentlig anmärkning (866 #z)
* Underordnad institution/enhet (866 #9)

### Exemplarinformation 
(876-877)
* Har exemplarinformation - huvudpublikation etc. (876)
  * Internt exemplarnummer (876 #a)
  * Ogiltigt/makulerat intern exemplarnummer (876 #b)
  * Förvärvspris (876 #c)
  * Förvärvsdatum (876 #d)
  * Förvärvskälla (876 #e)
  * Begränsningar för användning (876 #h)
  * Tillfällig placering (876 #l)
  * Unik exemplarbeteckning (streckkod) (876 #p)
  * Ogiltig/makulerad intern exemplarbeteckning (876 #r)
  * Exemplarnummer (876 #t)
  * Katalogisatörens anmärkning (876 #x)
  * Offentlig anmärkning (876 #z)
  * Del av materialet som avses (876 #3) /Lägg till entitet/Skapa lokal entitet/Resurs/Lägg till egenskaper under Resurs/Benämning 
  * Underordnad institution/enhet (876 #9)

* Har exemplarinformation - bihang etc. (877)
  * Internt exemplarnummer (877 #a)
  * Ogiltigt/makulerat intern exemplarnummer (877 #b)
  * Förvärvspris (877 #c)
  * Förvärvsdatum (877 #d)
  * Förvärvskälla (877 #e)
  * Begränsningar för användning (use) (877 #h)
  * Tillfällig placering (877 #l)
  * Unik exemplarbeteckning (streckkod) (877 #p)
  * Ogiltig/makulerad intern exemplarbeteckning (877 #r)
  * Exemplarnummer (876 #t)
  * Katalogisatörens anmärkning (876 #x)
  * Offentlig anmärkning (877 #z)
  * Del av materialet som avses (877 #3) /Lägg till entitet/Skapa lokal entitet/Resurs/Lägg till egenskaper under Resurs/Benämning 
  * Underordnad institution/enhet (877 #9)

### Lokalt definierade bestandsfalt
* Lokalt definierat beståndsfält (beståndsfält 948)
  * Beståndsfält 948, a-z, A-Z samt 0-9 kan läggas till.
  * Beståndsfält 948, indikator 1
  * Beståndsfält 948, indikator 2
Sök upp de fält som önskas, t.ex.: Beståndsfält 948, delfält a

* Lokalt definierat beståndsfält (beståndsfält 949)
  * Beståndsfält 949, a-z, A-Z samt 0-9 kan läggas till.
  * Beståndsfält 949, indikator 1
  * Beståndsfält 949, indikator 2
