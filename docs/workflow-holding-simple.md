---
section: Hjälptexter bestånd
title: Enkel beståndsregistrering
order: 135
date: 2020-03-02
tags:
- bestånd
- beståndsregistrering
--- 

# Enkel beståndsregistrering

Det är endast bibliotekskod/sigel som är obligatorisk och den sätts automatiskt när ett bestånd läggs till. Kortkommando för att lägga bestånd är alt+b.

Du kan lägga på bestånd direkt ifrån träfflistan. Från träfflistan kan du se om ditt bibliotek har bestånd och hur många andra bibliotek som har bestånd.

De mest vanliga egenskaperna finns färdiga att fylla i. Det motsvarar vad som kunde göras i Libris webbregistrering. Övriga egenskaper läggs till via plustecken. För vidare instruktioner och mer information, [se hjälptexten Beståndsregistrering](https://libris.kb.se/katalogisering/help/workflow-holding).

Du behöver inte ta bort tomma egenskaper när du sparar. Systemet tar bort dem automatiskt.

## Har komponent (852)
Klicka på pilen intill Bestånd för att expandera. Där kan följande läggas till:

* Hyllplacering (Avdelning, samling) (852 #c)
Används då ytterligare information om placering utöver Hyllkod behöver läggas till.
<br/>```Exempel: Institution 14```

* Hyllkod (852 #h)
Här läggs uppställning efter klassifikation eller annan hyllkod.
<br/>```Exempel: 158.1```

* Hyllsignum: Uppställningsord (852 #l)
<br/>```Exempel: Andersson```

* Hyllsignum: Löpnummer (852 #j)
<br/>```Exempel: 2594```

* Katalogisatörens anmärkning (852 #x)
<br/>```Exempel: HAA```


För att lägga till ytterligare ett Bestånd (motsvarande flera 852): Lägg till bestånd genom att klicka på plustecknet vid Har komponent, ett ytterligare bestånd läggs då till.

## Tillhörande media (856)
* Tillhörande media /Lägg till Mediaobjekt/Skapa lokal entitet/URI (856 4/0)
Länk till den elektroniska resurs som är den bibliografisk resurs som beskrivs

### Oformaterad beståndsuppgift - huvudpublikation (866)

**Exempel på oformaterad beståndsuppgift:**
![Oformaterad beståndsuppgift](oformateradbestand.png)

* Beståndsuppgift (866 #a)
* Katalogisatörens anmärkning (866 #x)
* Offentlig anmärkning (866 #z)
* Underordnad institution/enhet (866 #9) (Ej med i mallen, lägg till egenskapen vid Oformaterad beståndsuppgift)
