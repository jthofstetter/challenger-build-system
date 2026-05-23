# Percentile Scoring

Dieses Dokument definiert, wie Leistungen aus dem Ring-System in Ranks übersetzt werden.

Das System nutzt folgende Ranks:

```text
Bronze
Silver
Gold
Platinum
Emerald
Diamond
Master
Grandmaster
Challenger
```

Deutsch:

```text
Bronze
Silber
Gold
Platin
Smaragd
Diamant
Meister
Großmeister
Challenger
```

---

## Grundidee

Ein Rank beschreibt nicht den absoluten Wert einer Person.

Ein Rank beschreibt:

```text
Wie selten ist eine Leistung innerhalb einer definierten Population?
```

Die Population wird durch das Ring-System definiert.

Beispiel:

```text
Europa → Österreich → HTL IT → Matura → Mathematik → Note 2
```

Erst nachdem alle Ringe definiert sind, kann ein Percentile berechnet werden.

---

## Rank Ladder

| Rank | Deutsch | Percentile-Bereich | Bedeutung |
|---|---|---:|---|
| Bronze | Bronze | Top 75 % | Grundniveau erreicht |
| Silver | Silber | Top 50 % | durchschnittlich bis solide |
| Gold | Gold | Top 25 % | überdurchschnittlich |
| Platinum | Platin | Top 15 % | stark |
| Emerald | Smaragd | Top 10 % | sehr stark |
| Diamond | Diamant | Top 5 % | elite-nah |
| Master | Meister | Top 1 % | Elite |
| Grandmaster | Großmeister | Top 0.1 % | absolute Ausnahme |
| Challenger | Challenger | Top 0.01 % | historische / extrem seltene Dominanz |

---

## Interpretation

### Bronze

Die Person befindet sich in der Population und erfüllt grundlegende Anforderungen.

### Silver / Silber

Die Person liegt ungefähr im soliden oder durchschnittlichen Bereich.

### Gold

Die Person ist klar überdurchschnittlich.

### Platinum / Platin

Die Person zeigt starke Leistung innerhalb der definierten Population.

### Emerald / Smaragd

Die Person gehört zu einer sehr starken Minderheit.

### Diamond / Diamant

Die Person gehört zur erweiterten Elite innerhalb der Population.

### Master / Meister

Die Person ist innerhalb der Population klar Elite.

### Grandmaster / Großmeister

Die Person ist extrem selten und gehört zur absoluten Spitze.

### Challenger

Die Person oder Leistung ist historisch oder extrem selten dominant.

---

## Wichtig

Ranks gelten immer nur relativ zum Ring-Kontext.

Beispiel:

```text
Gold in HTL IT ≠ Gold in allgemeiner Schule
Master EUW ≠ Master OCE
Diamond Natural Bodybuilding ≠ Diamond Casual Gym
```

Deshalb muss jeder Rank immer mit seinem vollständigen Ring-Pfad gespeichert werden.

---

## Score-Formel, erste Version

```text
Rank Score = Percentile Score × Region Difficulty × Ring Difficulty × Confidence
```

### Percentile Score

Wie selten ist die Leistung innerhalb der definierten Population?

### Region Difficulty

Wie stark ist die äußere Region?

### Ring Difficulty

Wie schwierig sind die inneren Ringe?

### Confidence

Wie sicher sind die Daten?

---

## Beispiel

```text
Europa → Österreich → HTL IT → Matura → Mathematik → Note 2
```

Mögliche Bewertung:

- Region: Europa / Österreich
- System: HTL IT
- Spezialisierung: Matura Mathematik
- Performance: Note 2
- Percentile: muss durch Daten geschätzt oder berechnet werden
- Rank: abhängig vom tatsächlichen Percentile

---

## Offene Aufgaben

- echte Datenquellen pro Population sammeln
- Notenverteilungen recherchieren
- Difficulty Modifier definieren
- Confidence-System standardisieren
- Score-Normalisierung verbessern
