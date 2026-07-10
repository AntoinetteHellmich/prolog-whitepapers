# Whitepaper 3 – Kryptarithmen mit Prolog modellieren

## Motivation

Kryptarithmen gehören zu den klassischen Anwendungsgebieten der logischen Programmierung. Im Gegensatz zu imperativen Programmiersprachen steht dabei nicht die schrittweise Berechnung einer Lösung im Vordergrund, sondern die Beschreibung der Randbedingungen, welche eine gültige Lösung erfüllen muss.

Dieses Whitepaper zeigt anhand verschiedener Kryptarithmen, wie sich arithmetische Randbedingungen in Prolog modellieren lassen und welche Auswirkungen unterschiedliche Modellierungsstrategien auf den Suchprozess haben.

---

## Ziel

Ziel dieses Whitepapers ist es, verschiedene Ansätze zur Modellierung von Kryptarithmen in Prolog vorzustellen und hinsichtlich ihres Suchverhaltens zu vergleichen.

Dabei werden insbesondere folgende Fragestellungen untersucht:

- Wie lassen sich Buchstaben eindeutig auf Ziffern abbilden?
- Welche Modellierungsstrategien eignen sich für Kryptarithmen?
- Wie beeinflusst die Reihenfolge von Bedingungen das Backtracking?
- Welche Auswirkungen besitzen unterschiedliche Suchstrategien auf die Performance?

---

## Inhalt

Das Whitepaper behandelt unter anderem folgende Themen:

- Kryptarithmen als Constraint-Probleme
- Modellierung eindeutiger Variablenbelegungen
- Generate-and-Test
- schrittweise Variablenbindung
- schriftliche Addition als Modellierungsstrategie
- Suchraumreduktion
- Performanceanalyse verschiedener Lösungsansätze

---

## Zielgruppe

Dieses Whitepaper richtet sich an Leser, die bereits grundlegende Kenntnisse in Prolog besitzen und diese anhand komplexerer Modellierungsaufgaben vertiefen möchten.

---

## Lernziele

Nach der Lektüre sollen Leser

- Kryptarithmen in Prolog modellieren können,
- unterschiedliche Modellierungsstrategien vergleichen,
- Suchräume analysieren,
- Backtracking gezielt reduzieren,
- Performancemessungen interpretieren.

---

## Repository

Dieses Whitepaper ist Teil der Projektreihe **Prolog Whitepapers**.

Weitere Whitepaper behandeln

- Einführung in Prolog
- Backtracking verstehen
- Das Einstein-Rätsel
- Optimierung deklarativer Programme

---

## Lizenz

MIT License
