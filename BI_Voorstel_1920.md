---
title: Intro BI Analyse Document
acad_year: 1920
lector: David D'Haese
authors: Voornaam1 Naam1 & Voornaam2 Naam2
olod: Toegepaste Informatica
---

#### Professionele Bachelor Toegepaste Informatica

#### Intro BI Analyse Document

## Analyse van de Verkoop van Chips en Guacamole (Vervang dit dus door jouw titel!)

Voornaam1 Naam1 & Voornaam2 Naam2

### Versiebeheer

*Het versiebeheer laat alle versies van het document zien met de daarbij horende wijzigingen. Het laat ook zien aan wie je het hebt verspreid. Waarom is dit nodig? Het is voor de lezer belangrijk te weten hoe dit document tot stand is gekomen en wie het mogelijk heeft nagelezen. Denk eraan dat tijdelijke versies een nummer 0.x meekrijgen en dat de eerste finale versie het volgnummer 1.00 moet krijgen.*

| Nr.  | Datum      | Verspreiding | Wijziging                                         |
|------|------------|--------------|---------------------------------------------------|
| 0.01 | 2020-03-20 | Dirk Duivel  | (eerste draft) Probleemstelling en Doelstellingen |
| 0.02 | 2020-06-06 | Dirk Duivel  | Op te leveren documenten                          |

### Probleemstelling

*Omschrijf hier de huidige situatie en wat het probleem is met deze situatie: Waarom moet er iets veranderen? Max. 300 woorden.*

Op dit moment zijn er cijfers beschikbaar van de verkoop van chips en guacamole (https://data.world/mannydelrio1/sales#). Om te beginnen zijn de data niet naar behoren gestructureerd en verspreid over meerdere bestanden en is het erg moeilijk om een overzicht te krijgen. Verder is het de bedoeling om een voorspelling te maken van de verkoop van chips en guacamole met een horizont van 2 maanden.

### Doelstelling

*Wat is het doel, op langere termijn. Waarom denken we de nieuwe situatie beter zal zijn? Max. 200 woorden.*

- In eerste instantie zal er een staging area en DWH wordt opgezet met het doel alle data te centraliseren en te structureren.
- Er zal een OLAP cube worden opgezet voor het bekijken van de verkoopcijfers langs de dimensies tijd en/of staat
- Er zal getracht worden om na te gaan wat de voorspellende waarde is van de volgende data op de verkoop van chips en guacamole:

  - Interne verkoopscijfers van andere producten (van dezelfde bron)
  - Weersvoorspellingen
  - Google trends voorspellingen
  - Uitkomen van nieuwe blockbuster films

#### Op te Leveren Materialen

*Hier som je op welke bestanden er uiteindelijk opgeleverd gaan worden exclusief dit analyse document.*

- SSAS/SSIS project met staging area, ETL rules en DWH
- OLAP met Tijd en/of staat in Excel
- Rapport met voorspellingen en analyse van voorspellende waarde- 
