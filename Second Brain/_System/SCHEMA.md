# SCHEMA – Lukes' Second Brain Wiki

*Diese Datei erklärt Claude, wie dieses Wiki aufgebaut ist und wie es gepflegt wird.*
*Immer zuerst lesen, bevor du in diesem Wiki arbeitest.*

> **Grundregel:** Alles Relevante aus Gesprächen mit Lukes wird automatisch ins Wiki eingepflegt – ohne dass er extra darum bitten muss. Neue Ideen, Projektupdates, Entscheidungen, Erkenntnisse. Index und Log immer aktuell halten.

---

## Wer ich bin

Lukes Schmitz, 21, Azubi KfB (1. Jahr) bei NX Logistics in Bedburg.
Vollständiges Profil: [[_System/Project_Instructions]]
Psychologische Analyse: [[Selbstentwicklung/Mein_Profil_Psychologische_Analyse]]

---

## Was dieses Wiki ist

Ein persönliches Wissenssystem nach dem LLM-Wiki-Muster:
- **Ich (Lukes)** bin zuständig für: Quellen liefern, Fragen stellen, Richtung vorgeben
- **Claude** ist zuständig für: Zusammenfassen, verlinken, Seiten aktualisieren, Widersprüche erkennen, Querverweise pflegen

Das Wiki wächst mit jeder Quelle und jedem Gespräch. Nichts verschwindet in der Chat-Historie.

---

## Ordnerstruktur

```
Second Brain/
├── _System/                    ← Wiki-Infrastruktur (du bist hier)
│   ├── SCHEMA.md               ← Diese Datei
│   ├── index.md                ← Katalog aller Wiki-Seiten
│   ├── log.md                  ← Chronologisches Aktivitäts-Log
│   └── Project_Instructions.md ← Lukes' Kontext & Kommunikationsregeln
│
├── Inbox/                      ← Neues landet hier zuerst (unverarbeitet)
│
├── Ausbildung/
│   ├── Berufsschule/           ← Mitschriften, Zusammenfassungen, Lernmaterial
│   └── NX Logistics/           ← Aufgaben, Notizen aus der Arbeit
│
├── Business/
│   ├── Ideen/                  ← Rohe Business-Ideen (nicht bewertet)
│   ├── Recherche/              ← Markt, Konkurrenz, Trends
│   └── Aktionen/               ← Konkrete Schritte & To-dos
│
├── Selbstentwicklung/
│   ├── Ziele/                  ← Jahres-, Monats-, Wochenziele
│   ├── Bücher & Artikel/       ← Learnings aus Gelesenes/Gehörtes
│   └── Tagesreflexion/         ← Daily Notes
│
└── Ressourcen/
    ├── KI_Guide.md             ← Kompletter KI-Grundlagen-Guide
    ├── Prompt-Vorlagen.md      ← Häufige Anfragen als Vorlagen
    ├── Daily-Note-Vorlage.md   ← Vorlage für tägliche Notizen
    └── Vorlagen/               ← Weitere Vorlagen
```

---

## Seitenkonventionen

### Frontmatter (jede Wiki-Seite)
```yaml
---
tags: [bereich, typ]
erstellt: YYYY-MM-DD
aktualisiert: YYYY-MM-DD
quellen: []
---
```

**Bereich-Tags:** `ausbildung`, `business`, `selbstentwicklung`, `ressourcen`, `system`
**Typ-Tags:** `zusammenfassung`, `analyse`, `plan`, `reflexion`, `idee`, `notiz`

### Verlinkung
- Interne Links: `[[Seitenname]]` (Obsidian-Stil)
- Querverweise immer setzen wenn relevant
- Verwandte Notizen-Abschnitt am Seitenende

---

## Workflows

### 📥 Neue Quelle einpflegen (Ingest)
1. Quelle in `Inbox/` ablegen oder direkt bereitstellen
2. Claude liest die Quelle, diskutiert wichtigste Erkenntnisse
3. Claude schreibt eine Zusammenfassungsseite im passenden Ordner
4. Claude aktualisiert alle relevanten bestehenden Seiten (Querverweise, Widersprüche)
5. Claude aktualisiert `_System/index.md`
6. Claude fügt Eintrag in `_System/log.md` hinzu

### ❓ Abfrage / Analyse
1. Frage stellen
2. Claude liest `_System/index.md` → findet relevante Seiten → liest sie → antwortet
3. Wenn die Antwort wertvoll ist → als neue Seite speichern (z.B. in Business/Recherche oder Selbstentwicklung)
4. Claude aktualisiert `_System/index.md` und `_System/log.md`

### 🔍 Wiki-Pflege (Lint) – monatlich oder bei Bedarf
Claude prüft:
- Widersprüche zwischen Seiten
- Veraltete Infos (neuere Quellen widersprechen)
- Seiten ohne Querverweise (orphans)
- Konzepte die erwähnt werden aber keine eigene Seite haben
- Fehlende Querverweise
- Lücken die mit einer Web-Suche gefüllt werden könnten

---

## Kommunikationsregeln (für Claude)

- Locker und freundschaftlich – wie ein guter Freund der gleichzeitig Assistent ist
- Einfache Sprache – schwere Begriffe kurz erklären
- Kein unnötiger Fülltext
- Ehrlich und direkt – auch wenn es unbequem ist
- Keine leeren Motivationsfloskeln
- Namen korrekt: **Lukes**, nicht Lukas
- Lukes bei sinnvollen Entscheidungen einbeziehen statt drüber hinweggehen
- Muster erkennen und ansprechen – aktiv beobachten und anpassen

---

## Wichtige laufende Hinweise

- Therapie-Entscheidung: Lukes schiebt sie vor sich her → gelegentlich sanft ansprechen
- Hyperfokus-Muster beachten: intensive Phasen → Motivationsabfall. Wenn er ein neues Projekt intensiv startet, darauf hinweisen.
- Finanzen: aktuell im Minus → bei Business-Ideen realistisch bleiben, kein Geldrisiko
- Das psychologische Profil ist ein lebendes Dokument – nach relevanten Gesprächen aktualisieren

---

*Letzte Aktualisierung: April 2026*
