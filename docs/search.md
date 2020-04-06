---
section: Katalogiseringsverktyget
title: Sök
order: 10
date: 2020-04-06
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

```Exempel fritextsökning: 9789144113074```

För att söka på ISBN med eller utan bindestreck, välj att söka med avgränsning ISBN.
<br/>`Exempel:`
  * `ISBN: 9789144113074`
  * `ISBN: 978-91-44-11307-4`  

För att söka på ogiltiga ISBN eller ISBN som hör till annan version (Indirekt identifierad av), sök ISBN som fritext, utan bindestreck.  

### Specialtecken

**Sökning på specialtecken:**  
* Från och med version 1.15 av Libris katalogisering normaliseras diakriter vid import till Libris. Tecken bestående av två tecken (s.k. dekomponerade) rättas till sammansatta tecken (s.k. prekomponerade). Sökningen fungerar med både prekomponerade och dekomponerade tecken.
Det fungerar att söka med eller utan diakriter i egenskaperna Har titel\Titel samt Medverkan. Egenskapen Upphovsuppgift kräver fortfarande exakt match vad gäller diakriter, apostrofer och accenttecken.

<br/>`Exempel på polska:`
<br/>`Sökningen på titel med diakriter Przejdź przez wodę, krocz przez ogień respektive utan diakriter Przejdz przez wode, krocz przez ogien ger samma träffresultat.`

<br/>`Exempel på telugu:`
<br/>`Sökningen på titel med diakriter Runam Svati varapatrikalo dharavahikang respektive utan diakriter Ruṇaṃ Svāti vārapatrikalō dhārāvāhikaṅgā ger samma träffresultat.`

Det fungerar också att söka med eller utan apostrofer och accenttecken i egenskaperna Har titel\Titel samt Medverkan.
<br/>`Exempel på arabiska:`
<br/>`al-Mujtamaʻ al-miṣrī fī al-ʻaṣr al-ʻuthmānī kan sökas som al-Mujtama al-misri fi al-asr al-uthmani alternativt al Mujtama al misri fi al asr al uthmani`

Observera att apostrofen ʹ som används i translitterering av kyrilliska för närvarande inte fungerar på samma sätt som ovan.
<br/>`Exempel på ryska:`
<br/>`Sökningen på malenʹkij respektive malenkij kommer att ge olika träffresultat.`

Poster lagras på normaliseringsformen NFC och sökning inom de flesta egenskaper görs med normaliseringsformen NFKC. NFC och NFKC är en del av unicodestandarden.
<br/>`Exempel på normaliserade sökningar:`
  * y²-k=x³ ger även träff vid sökning på y2-k=x3
  * H₂O ger även träff vid sökning på h2o
