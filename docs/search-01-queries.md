---
section: Sök
title: Utforma sökfrågor
order: 1
date: 2019-02-28
tags:
- search
---

# Sök

[Sökning på specialtecken](#specialtecken)

## Operatorer för frågespråk

   `+` betyder AND  
   `|` betyder OR  
   `-` innebär uteslutning  
   `"` används för frassökning  
   `*` innebär trunkering av en term  
   `~` används för oexakt sökning

---

### Standardsökning

En standardsökning ger träff på sammanslagen sökterm. En sökning på Astrid Lindgren kommer matcha poster som innehåller Astrid och Lindgren, oavsett ordning och oavsett var i posten orden finns. Sökningen kommer alltså även matcha `Lindgren Astrid`, `Astrid heter i efternamn Lindgren` och liknande.

### Exakt sökning

Om du vill söka på en exakt fras, använd `"`. En sökning på `"Emil i Lönneberga"` ger träff på fras i angiven ordning. Sökningen kommer alltså inte matcha till exempel `Emil som bor i Lönneberga`.
Denna sökning kan även användas för att söka på ämnesord eller andra begrepp med bindestreck, till exempel `"Människa-dator-interaktion"` eller `"Marie-Louise"`.  

### Eller

Om du vill söka på eller, använd `"|"`. Exempelvis ger `"Tove Jansson" | "Astrid Lindgren"` träff på `Tove Jansson` eller `Astrid Lindgren`.

### Utesluta termer

Om du vill utesluta en term, använd `-`. Exempelvis ger `Astrid -Lindgren` alla träffar som innehåller `Astrid` men inte `Lindgren`.

### Gruppering av termer 

Om du vill gruppera termer och operatorer, använd `(` och `)`. Exempelvis ger en sökning på `(Tove | Lars) Jansson`träff på Tove eller Lars Jansson. Utan parenteserna söker du efter `Tove` eller `Lars Jansson`, men med parenteserna söker du på `Tove Jansson` eller `Lars Jansson`

### Trunkering

Om du vill trunkera, använd `*`. Trunkering ger träff på alla ändelser efter prefixet. Exempelvis ger `sol*` träff på bland andra `solros` , `sola` och `solig`.  

### Oexakt sökning  

Om du vill söka på ett ord, men är osäker på stavningen, kan du lägga till en tilde, `"~"`, efter ordet. Denna sökning kan även användas för att söka på ord med specialtecken eller diakriter. Exempelvis kan du söka på `Noren~` och få träff på Norén.  

### Avgränsa sökningen

Det går att avgränsa sökningen till ISBN, ISSN eller titel. Välj alternativ i menyn vid sökrutan. Om man inte väljer någon avgränsning söker man som fritext. 

### ISBN

I nya Libris sparas ISBN utan bindestreck.  

För att söka på ISBN i fritextsökning (utan avgränsning), ta bort bindestrecken.  

    Exempel fritextsökning: `9789144113074`

För att söka på ISBN med eller utan bindestreck, välj att söka med  avgränsning ISBN.  

    Exempel ISBN: `9789144113074`
    Exempel ISBN: `978-91-44-11307-4`

För att söka på ogiltiga ISBN eller ISBN som hör till annan version (Indirekt identifierad av), sök ISBN som fritext, utan bindestreck.  

### Specialtecken

**Sökning på specialtecken:**  
I Libris lagras all text i [UTF-8]( https://sv.wikipedia.org/wiki/UTF-8), den teckenkod som tillåter hantering av världens alla språk. Det finns trots det vissa problem med hantering av diakriter och andra specialtecken. Medan arbetet med normalisering av tecken pågår,  följ denna instruktion för att ändå få träff vid sökning där diakriter och specialtecken ingår.  

Vissa tecken kan vara kodade på olika sätt, prekomponerade (sammansatta) eller dekomponerade. Prekomponerade tecken innebär att grundbokstav och sammanhörande diakrit uppträder som ett sammanhållet tecken. Dekomponerade innebär att grundbokstav och sammanhörande diakrit uppträder som separata tecken. Prekomponerade tecken går att söka men kan vara svåra att skriva in manuellt (se [Specialtecken](https://libris.kb.se/katalogisering/help/search-04-special-chars)). Dekomponerade tecken går däremot varken att söka fram med eller utan diakriter (i Andra källor fungerar det dock).  

Om sökningen med diakriter inte ger träff, fortsätt med denna sökning:  

1. Kopiera strängen från källan du använt dig av och klistra in den.
2. Om det finns dekomponerade tecken i strängen, ställ textmarkören efter ett sådant och tryck backsteg en gång. Detta ska resultera i att t.ex. "bokstav + diakrit" ändras till "bokstav". Om det blir två tecken vid inklistring (eller bara frågetecken), ta bort de "konstiga" bitarna.
3. Skriv in en tilde, "~", efter varje ord där ersättning har gjorts.
4. Sök.  

Inklistrad sträng med dekomponerade tecken:  
![Inklistrad sträng med dekomponerade tecken](tecken1.png)  
Inklistrad sträng efter backsteg och med tilde, "~":  
![Inklistrad sträng efter backsteg och med tilde, "~"](tecken2.png) 

eller

1. Skriv in sträng utan diakriter.  
2. Skriv in en tilde, "~", efter varje ord som borde innehålla diakriter eller specialtecken.  
3. Sök.
