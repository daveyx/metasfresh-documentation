---
title: Wie konfiguriere ich ein Produkt für die Produktion ?
layout: default
tags:
  - Stammdaten
  - Produktion
lang: de
---
## Vorbereitung
1. [Es existiert ein Produkt namens "Ergebnis" das hergestellt werden soll](Wie_lege_ich_ein_neues_Produkt_an)
1. [Stückliste erstellen](Wie_erstelle_ich_eine_Rezeptur_Stückliste)
1. [Produktionsressource erstellen](Wie_erstelle_ich_eine_Produktionsressource)
1. [Arbeitsablauf erstellen](Wie_erstelle_ich_einen_Arbeitsablauf)
1. [Gebindelager einrichten](Wie_richte_ich_ein_Gebindelager_ein)
1. [Warenverteilung für Gebindelager konfigurieren](Wie_richte_ich_eine_automatische_warenverteilung_fuer_Leergebinde_ein)
1. [Lager für die Produktion vorbereiten](Wie_lege_ich_ein_neues_Lager_an): Sicherstellen, dass die Lagerzuordnung für "Physischer Warenbestand" und "Manufacturing Order" besteht

## Schritte
1. [Fenster "Produkt Plandaten" öffnen](Wie_finde_und_öffne_ich_ein_Fenster)
1. Nach Produkt "Ergebnis" suchen
1. In Register "Daten Planung" wechseln
1. [Neuen Datensatz anlegen](Wie_lege_ich_einen_neuen_datensatz_an)
1. __Lager__ auswählen in dem produziert werden soll
1. __Produktionsressource__ auswählen mit der produziert werden soll
1. __Wird produziert__ auf _Ja_ setzen
1. __Stücklisten Konfiguration__ für das Produkt auswählen (siehe [Stückliste anlegen](Wie_erstelle_ich_eine_Rezeptur_Stückliste))
1. __Arbeitsablauf__ auswählen nach dem produziert werden soll
1. __Order Policy__ _Lot for Lot_ auswählen
1. optional: Wenn der Produktionsauftrag automatisch fertiggestellt werden soll __isDocComplete__ anhaken
1. [Speichern](Wie_lege_ich_einen_neuen_datensatz_an)
