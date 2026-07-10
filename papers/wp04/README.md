# Whitepaper 4 – Constraint-Modellierung mit dem Einstein-Rätsel

## Motivation

Das Einstein-Rätsel zählt zu den bekanntesten Logikrätseln und eignet sich hervorragend zur Demonstration deklarativer Programmierung. Im Mittelpunkt steht dabei nicht die Berechnung eines Lösungswegs, sondern die Beschreibung einer Menge von Bedingungen, aus denen Prolog durch logische Schlussfolgerungen eine konsistente Lösung bestimmt.

Dieses Whitepaper zeigt, wie sich unterschiedliche Arten von Randbedingungen modellieren lassen und welche Auswirkungen diese auf das Suchverhalten besitzen.

---

## Ziel

Ziel dieses Whitepapers ist es, die Modellierung komplexer Constraint-Probleme in Prolog anhand des Einstein-Rätsels zu erläutern.

Dabei werden insbesondere folgende Fragestellungen untersucht:

- Wie lassen sich komplexe Zusammenhänge deklarativ modellieren?
- Welche Datenstruktur eignet sich zur Darstellung der Häuser?
- Wie werden Eigenschafts- und Positionsregeln formuliert?
- Welche Auswirkungen besitzt die Reihenfolge der Regeln auf den Suchraum?
- Wie lässt sich Backtracking gezielt reduzieren?

---

## Inhalt

Das Whitepaper behandelt unter anderem folgende Themen:

- Constraint Satisfaction Problems (CSP)
- Datenmodellierung in Prolog
- Listen als Wissensbasis
- Eigenschaftsregeln
- Positionsregeln
- Einsatz von `member/2`
- Einsatz von `nth1/3`
- Einsatz von `nextto/3`
- Suchraumanalyse
- Optimierung des Backtracking-Verhaltens

---

## Zielgruppe

Dieses Whitepaper richtet sich an Leser mit grundlegenden Prolog-Kenntnissen, die komplexere Modellierungsaufgaben verstehen und eigene Constraint-Probleme entwickeln möchten.

---

## Lernziele

Nach der Lektüre sollen Leser

- Constraint-Probleme in Prolog modellieren können,
- geeignete Datenstrukturen auswählen,
- deklarative Regeln formulieren,
- Suchräume analysieren,
- Backtracking durch geeignete Modellierung reduzieren.

---

## Repository

Dieses Whitepaper ist Teil der Projektreihe **Prolog Whitepapers**.

Weitere Whitepaper behandeln

- Einführung in Prolog
- Backtracking verstehen
- Kryptarithmen modellieren
- Performanceanalysen deklarativer Programme

---

## Lizenz

MIT License
