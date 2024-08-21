---
section: Terminologi
title: BIBFRAME svensk terminologi
order: 141
date: 2020-11-12
tags:
- bibframe
- rda
---

# BIBFRAME svensk terminologi

[Information om BIBFRAME - Introduktion till Libris på kb.se](https://www.kb.se/samverkan-och-utveckling/libris/katalogisering-i-libris/introduktion-till-libris.html)

BIBFRAME (Bibliographic Framework) är ett initiativ från Library of Congress som anpassar bibliografiska beskrivningsstandarder till en modell för länkade data. Syftet med övergången till länkade data är att göra den bibliografiska informationen mer användbar och synlig. Det gynnar inte bara biblioteken och dess användare, utan även samhället i stort.

Vid katalogisering av en resurs, till exempel en bok, beskrivs resursen med informationselement som författare, innehåll, utgåvor och exemplar.

I BIBFRAME 2.0 organiseras den här typen av information i tre huvudsakliga abstraktionsnivåer, så kallade kärnklasser: **Verk**, **Instans** och **Exemplar**.

* **Verk**. Den högsta abstraktionsnivån, ett Verk, återspeglar i BIBFRAME den katalogiserade resursens konceptuella väsen: författare, språk och vad det handlar om (ämnen).
   * _Not till Verk:_ Uttrycksnivån, som finns i FRBR och RDA, innefattas i BIBFRAME:s Verk. Det innebär att ett nytt uttryck av ett Verk, t. ex en översättning, i BIBFRAME betraktas som ett nytt Verk.

* **Instans**. Ett verk kan ges en eller flera fysiska gestalter, t.ex. en särskild utgåva. Dessa är Instanser av Verket. En Instans återspeglar information som dess utgivningsplats, utgivare och utgivningsår, samt bärartyp (t.ex. volym, videoskiva).
   * _Not till Instans:_ Instans kallas i RDA för Manifestation.

* **Exemplar**. Ett Exemplar är en kopia (fysisk eller elektronisk) av en Instans. Exemplaret återspeglar information som dess placering (fysiskt eller elektroniskt), hyllkod och lokal identifikator.  
   
   * _Not till Exemplar:_ Ett eller flera exemplar på ett bibliotek kallas för Bestånd.

BIBFRAME 2.0 definierar även ytterligare nyckelbegrepp, med relationer till kärnklasserna.

* **Agent**. Agenter är personer, organisationer, jurisdiktioner, osv. Dessa är i sin tur förknippade med ett Verk eller en Instans genom funktioner som författare, redaktör, konstnär, fotograf, kompositör, illustratör osv.

* **Ämnen**. Ett Verk kan “handla om” en eller flera saker. Saker som kan vara ämnen innefattar platser, händelser, verk, instanser, exemplar, agenter osv.

* **Händelser**: Exempel på händelser är evenemang, konsert. En inspelning av en händelse kan utgöra ett Verks innehåll.

Vokabulären i BIBFRAME 2.0 består av klasser och egenskaper (properties) hämtade från RDF.

* **Klasser** innehåller tre kärnklasser, beskrivna ovan, men även kompletterande klasser, av vilka många är subklasser (underklasser), till kärnklasserna.

* **Egenskaper** beskriver såväl resursens karaktäristika som relationer mellan resurser. Till exempel: ett Verk kan vara en “översättning av” ett annat Verk, och en Instans kan vara en “instans av” ett specifikt Verk i BIBFRAME. Andra egenskaper utgör attribut till Verk och Instanser. Till exempel: egenskapen “ämne” i BIBFRAME utgör ett viktigt attribut till Verket (vad Verket handlar om), och egenskapen “omfång” (t.ex. 77 sidor, 2 CD) utgör ett attribut till en Instans.

![BIBFRAME modell svensk terminologi](Bibframe_modell.png)

Texten är en bearbetad översättning av Library of Congress text [Overview of the BIBFRAME 2.0 Model](https://www.loc.gov/bibframe/docs/bibframe2-model.html)

[Se även instruktionsfilmen BIBFRAME Svensk terminologi på KB Play]([https://youtu.be/LmhsXICZ0MQ](https://kbplay.mediaflowportal.com/watch/1099538/))
