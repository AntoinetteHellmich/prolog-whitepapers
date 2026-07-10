# Whitepaper 2 – Backtracking verstehen und analysieren

## Motivation

Backtracking ist einer der zentralen Mechanismen der logischen Programmierung. Während imperativ entwickelte Programme den Lösungsweg explizit vorgeben, durchsucht Prolog den Lösungsraum selbstständig anhand der definierten Fakten und Regeln.

Für Einsteiger bleibt dieser Suchprozess jedoch häufig eine "Black Box". Das Whitepaper zeigt deshalb anhand praktischer Beispiele, wie Backtracking arbeitet und wie sich unterschiedliche Modellierungsentscheidungen auf das Suchverhalten auswirken.

---

## Ziel

Ziel dieses Whitepapers ist es, den internen Lösungsprozess von Prolog nachvollziehbar zu machen.

Dabei werden insbesondere folgende Fragestellungen untersucht:

- Wie entsteht Backtracking?
- Wann werden Wahlpunkte erzeugt?
- Wie verwirft Prolog ungültige Belegungen?
- Welche Auswirkungen hat die Reihenfolge von Zielen?
- Wie beeinflussen Modellierungsentscheidungen den Suchraum?

---

## Inhalt

Das Whitepaper behandelt unter anderem folgende Themen:

- Suchraum in Prolog
- Wahlpunkte (Choice Points)
- Backtracking
- Generate-and-Test
- Tiefensuche
- Analyse mit `trace/0`
- Performanceanalyse mit `time/1`
- Einfluss der Zielreihenfolge
- Praktische Beispiele

---

## Zielgruppe

Dieses Whitepaper richtet sich an Leser, die bereits erste Erfahrungen mit Prolog gesammelt haben und verstehen möchten, wie die Inferenzkomponente intern arbeitet.

Grundkenntnisse zu Fakten, Regeln und Variablen werden vorausgesetzt.

---

## Lernziele

Nach der Lektüre sollen Leser

- das Backtracking von Prolog nachvollziehen können,
- Trace-Ausgaben interpretieren,
- Suchräume analysieren,
- ineffiziente Modellierungen erkennen,
- Möglichkeiten zur Suchraumreduktion beurteilen.

---

## Repository

Dieses Whitepaper ist Teil der Projektreihe **Prolog Whitepapers**.

Weitere Whitepaper behandeln

- Einführung in Prolog
- Kryptarithmen in Prolog
- Das Einstein-Rätsel
- Optimierung deklarativer Programme

---

## Lizenz

MIT License
