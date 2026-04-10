---
tags: [business, automatisierung, make, telegram, aktiv]
erstellt: 2026-04-10
aktualisiert: 2026-04-10
status: aktiv
---

# 🗞️ Lukes Daily – Automatische Morgenzeitung

## Was es ist

Automatische tägliche Morgenzeitung die jeden Morgen um **7:00 Uhr** als HTML-Datei via Telegram verschickt wird. Die Datei (`morgenzeitung.html`) wird im Browser geöffnet und zeigt eine persönliche Zeitung.

---

## Tech-Stack

| Komponente | Tool |
|---|---|
| Automatisierung | Make.com (Scenario: *Lukes Daily Morgenzeitung*) |
| Ausgabe | Telegram Bot `@Myflyingnewsbot` |
| Chat-ID | `8434546341` |
| KI-Formatierung | Claude Haiku via Anthropic API |
| Modell | `claude-haiku-4-5-20251001` |
| Max Tokens | 4000 |
| Dateiname | `morgenzeitung.html` |
| Kosten | ~0,60–1,20 €/Monat |

---

## Inhalte der Zeitung

**Wetter Neuss**
- HTTP-Module holen: aktuelles Wetter (HTTP 2), Sonnenauf/-untergang (HTTP 18), 3-Tage-Vorschau (HTTP 19)
- Quelle: `wttr.in/Neuss`

**Deutschland News**
- Tagesschau RSS Feed → 5 Artikel als Akkordeons
- Text Aggregator: Tools [4]

**Welt News**
- BBC RSS Feed → Tools [22]
- Claude übersetzt auf Deutsch

**Sport + Bundesliga**
- ESPN RSS → Tools [29]
- Bundesliga-Ergebnisse via Football-Data API → HTTP [30]

**Märkte**
- Bitcoin → HTTP [23]
- DAX → HTTP [24]

**Fun Fact**
- Kostenlose API → HTTP [5]

---

## Design-Vorgaben (Claude-Prompt)

- Fonts: Playfair Display + Inter (Google Fonts)
- Hintergrund: `#F8F7F4`
- Max-Breite: 900px zentriert
- Fade-in Animation
- Akkordeons für News (`<details><summary>`)
- Märkte-Karten grün/rot je nach Kurs
- Datum per JavaScript
- Header: `LUKES DAILY` groß + *Guten Morgen, Lukes.*
- Fester Prompt-Template → verhindert inkonsistentes Design

---

## Bekannte Probleme & Lösungen

| Problem | Lösung |
|---|---|
| Google Drive OAuth hat nicht funktioniert | Direkte Telegram-Datei statt Drive |
| Token-Limit (2000) war zu niedrig | Auf 4000 erhöht |
| Variablen-Platzhalter `[VARIABLE: ...]` im Output | Manuell durch Make-Variablen ersetzt |
| Design war inkonsistent (Claude generiert jedes Mal anders) | Fester Prompt-Template |

---

## Status

✅ Läuft — Trigger auf täglich 7:00 Uhr gestellt.  
→ Aktuellen Status prüfen unter: **Make.com → Scenarios → "Lukes Daily Morgenzeitung"**
