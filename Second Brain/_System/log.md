# 📋 Aktivitäts-Log

*Append-only. Neuestes oben. Format: `## [DATUM] TYP | Beschreibung`*
*Typen: `setup`, `ingest`, `query`, `lint`, `update`*

---

## [2026-06-17] update | UI Design Workflow eingerichtet

**Was passiert ist:**
- 4 Design-Skills installiert: taste-skill, emilkowalski-ui, ui-ux-pro-max, impeccable
- Magic MCP (21st.dev) als globaler MCP-Server hinzugefügt
- Automatischer 4-Stufen-Workflow in globale CLAUDE.md eingetragen
- Neue Seite: [[Ressourcen/GitHub-Skills/UI-Design-Workflow]]
- [[Ressourcen/GitHub-Skills/README]] aktualisiert

---

## [2026-06-16] update | Vault-Aufräumen & neue Seiten

**Was passiert ist:**
- `Overwatch Coach Wissen.md` aus falschem Root (`/Second Brain/`) nach `Gaming/Overwatch_Coach_Wissen.md` verschoben + Wikilinks gesetzt
- `Unbenannt.md` (leere Datei) gelöscht
- `_Archive/` vollständig geleert: 2 tote Dateien endgültig entsorgt (Duplikat + Redirect-Stub)
- `Business/n8n.md` angelegt: 4-Phasen-Plan, Ressourcen, Wikilinks zu Lukes_Daily + AzubiPass
- `Selbstentwicklung/Calisthenics.md` angelegt: Ziele, 4er-Split Trainingsplan, Fortschritts-Log-Tabelle
- `Interessen-und-Tech.md` mit Rücklinks zu n8n + Calisthenics erweitert
- `TASKS.md`: n8n-Link korrigiert, Calisthenics verlinkt, Archive-Task als erledigt markiert
- `_System/index.md`: 3 neue Seiten eingetragen (n8n, Calisthenics, OW2), Seitenanzahl 40 → 43

**Änderungen gesamt:**
- 4 Dateien gelöscht, 2 neue Seiten erstellt, 1 verschoben, 4 bestehende aktualisiert

---

## [2026-06-14] lint | Wöchentliche Strukturpflege

**Geprüft:**
- 58 Dateien gescannt
- Keine Probleme gefunden

**Änderungen:**
- index.md: Datum auf 2026-06-14 aktualisiert, Letzte-Aktivität-Zeile aktualisiert
- TASKS.md: Kein Aufräumen nötig – Aktiv + Diese Woche leer, Offen-Tasks sind langfristige offene Punkte ohne klare Erledigung erkennbar
- Struktur: Keine Stray-Dateien im Root, alle 40 Wiki-Seiten korrekt im Index, Gaming/-Ordner weiterhin korrekt als bekannte Erweiterung

---

## [2026-06-07] lint | Wöchentliche Strukturpflege

**Geprüft:**
- 58 Dateien gescannt
- 1 Problem gefunden: neue Seite nicht im Index

**Änderungen:**
- index.md: `Business/Masterplan – AzubiPass & Worksheet-Projekt` eingetragen (fehlte seit Erstellung)
- index.md: Seitenanzahl von 39 auf 40 aktualisiert, Datum + Letzte-Aktivität-Zeile aktualisiert
- TASKS.md: Keine Änderungen nötig – Aktiv + Diese Woche leer, alle Offen-Tasks bereits korrekt eingeordnet

---

## [2026-05-31] lint | Wöchentliche Strukturpflege

**Geprüft:**
- 59 Dateien gescannt (39 Wiki-Seiten + READMEs/SKILLs/Archiv/System)
- Keine Probleme gefunden

**Änderungen:**
- index.md: Datum auf 2026-05-31 aktualisiert, Letzte-Aktivität-Zeile aktualisiert
- TASKS.md: Kein Aufräumen nötig – Aktiv und Diese Woche bereits leer, keine Offen-Tasks >2 Wochen in aktivem Status
- Struktur: Keine stray files im Root (CLAUDE.md + TASKS.md gehören dort hin), alle 39 Wiki-Seiten korrekt im Index verzeichnet

---

## [2026-05-24] lint | Wöchentliche Strukturpflege

**Geprüft:**
- 57 Dateien gescannt
- 1 Problem gefunden (veraltete Tasks)

**Änderungen:**
- TASKS.md: 1 Aktiv-Task (AzubiPass "Ersten Verkauf machen") + 4 "Diese Woche"-Tasks → alle >17 Tage alt, in "Offen" verschoben; Aktiv + Diese Woche jetzt leer
- TASKS.md: "Inbox-Dateien entsorgen" in neue Sektion "Second Brain" unter Offen verschoben (Entscheidung weiterhin offen)
- index.md: Datum auf 2026-05-24 aktualisiert, Letzte-Aktivität-Zeile aktualisiert
- Keine Struktur-Probleme: keine Stray-Dateien im Root, alle 39 Wiki-Seiten korrekt im Index

---

## [2026-05-14] lint | Wöchentliche Strukturpflege

**Geprüft:**
- 57 Dateien gescannt (39 Wiki-Seiten + READMEs/SKILL-Dateien/Archiv)
- Keine Probleme gefunden

**Änderungen:**
- index.md: Datum auf 2026-05-14 aktualisiert, Letzte-Aktivität-Zeile aktualisiert
- TASKS.md: Kein Aufräumen nötig – Aktiv-Task (AzubiPass Erster Verkauf) erst 7 Tage alt, keine Task >2 Wochen unverändert aktiv
- Hinweis: "Inbox-Dateien entsorgen"-Task – Inbox ist leer (nur README), 2 Dateien liegen bereits in `_Archive/`; Task zur manuellen Entscheidung durch Lukes offen gelassen

---

## [2026-05-07] update | Second Brain Optimierung – L0-Umbau

**Was passiert ist:**
- `CLAUDE.md` zu echtem L0 umgebaut: auf 25 Zeilen gekürzt, zwei Pflichtregeln ganz oben (Session-Start: index.md lesen + Two-Output-Regel), nur dynamische Infos drin
- `TASKS.md` komplett aktualisiert: Aktiv-Sektion und "Diese Woche"-Sektion befüllt, Calisthenics-Ziel ergänzt, erledigte Tasks nachgepflegt
- `_System/SCHEMA.md` bereinigt: doppelte "Wer ich bin"-Sektion entfernt, nur Pointer auf Project_Instructions
- Inbox aufgeräumt: 2 tote Dateien nach `_Archive/` verschoben (Duplikat + Redirect-Stub)
- `_Archive/`-Ordner neu angelegt

**Warum:**
- CLAUDE.md war zu groß für L0 und zu klein für L1 – saß zwischen zwei Stühlen
- Two-Output-Regel war in SCHEMA.md vergraben statt prominent
- TASKS.md hatte seit Wochen keine aktiven Tasks – Completion Gap direkt im System sichtbar
- SCHEMA.md und Project_Instructions hatten redundante Infos

---

## [2026-05-04] lint | Wöchentliche Strukturpflege

**Geprüft:**
- 57 Markdown-Dateien gescannt (43 Wiki-Inhalt + READMEs/SKILL-Dateien)
- 1 Problem gefunden

**Änderungen:**
- Stray-Datei aus Root verschoben: `KI Guide – Grundlagen.md` (Redirect-Stub, enthielt nur "→ Verschoben nach [[Ressourcen/KI_Guide]]") → `Inbox/KI_Guide_Grundlagen_REDIRECT_STUB.md`
- TASKS.md: Kein Aufräumen nötig – Aktiv-Sektion ist leer, keine Task >2 Wochen unverändert aktiv
- index.md: Datum auf 2026-05-04 aktualisiert, Seitenanzahl 39 bestätigt (korrekt)

---

## [2026-04-28] lint | Wöchentliche Strukturpflege

**Geprüft:**
- 57 Markdown-Dateien gescannt (43 Wiki-Inhalt + READMEs/SKILL-Dateien)
- 3 Probleme gefunden

**Änderungen:**
- Stray-Datei aus Root verschoben: leere `14_Du_musst_nicht_von_allen_gemocht_werden.md` (0 B, Duplikat zur befüllten Version in `Selbstentwicklung/Bücher & Artikel/`) → `Inbox/14_Du_musst_nicht_von_allen_gemocht_werden_LEER_DUPLIKAT.md` (zum manuellen Sichten/Entsorgen, nicht gelöscht laut Lint-Regeln)
- TASKS.md: 3 AzubiPass-Aufgaben unter „Aktiv" (seit 2026-04-10 unverändert, >2 Wochen) → in „Offen / Business – AzubiPass" verschoben
- TASKS.md: „Daily Note Vorlage in Obsidian anlegen" als ✅ erledigt markiert (Datei existiert mit Inhalt unter `Ressourcen/Daily-Note-Vorlage.md`)
- index.md: Seitenanzahl 38 → 39 korrigiert (tatsächlicher Stand der gelisteten Wiki-Seiten), Datum + letzte Aktivität aktualisiert

---

## [2026-04-24] ingest | 17 Buch-Notes (personalisiert) + Übersicht angelegt

**Was passiert ist:**
- Lukes_Lernbuch_2025.pdf + Lukes_Wissenskompendium.pdf eingelesen und verarbeitet
- 17 individuelle Buch-Notes erstellt in `Selbstentwicklung/Bücher & Artikel/`
- Jede Note tief mit Lukes' psychologischem Profil verknüpft: Completion Gap, Hyperfokus, emotionale Isolation, Fearful-Avoidant, "nicht genug sein", AzubiPass, Beziehung
- Übersichts-Note `00_Übersicht_Bücher_x_Psychologisches_Profil.md` angelegt: Muster-zu-Buch-Mapping + Wenn-dann-Navigation
- index.md: Selbstentwicklung-Bereich um 18 Seiten erweitert, Seitenanzahl 20 → 38
- Stärkste Bücher für Lukes: Atomic Habits, Das Kind in dir, 6 Säulen Selbstwert, Mom Test, 100M Offers

---

## [2026-04-15] ingest | Niederländisch-Lernbereich aufgebaut + KI-Leitfaden eingespeist

**Was passiert ist:**
- PDF-Guide "Niederländisch lernen mit KI" gelesen und zusammengefasst
- Neuer Ordner `Ausbildung/Berufsschule/Niederlaendisch/` angelegt
- `KI_Leitfaden_Niederlaendisch.md` erstellt: Tool-Vergleich, Aussprache-Guide, Wochenrhythmus, System-Prompt
- `Lernfortschritt.md` erstellt: Profil, Schwachstellen, offene HAs, Materialien
- index.md: Ausbildung-Bereich befüllt, Seitenanzahl 18 → 20
- Neue Tools für Lukes identifiziert: ElevenLabs (Shadowing), Talkpal AI (Sprechtraining)

---

## [2026-04-13] lint | Wöchentliche Strukturpflege

**Geprüft:**
- 35 Dateien gescannt
- 1 Problem gefunden (Seitenanzahl in index.md)

**Änderungen:**
- index.md: Seitenanzahl korrigiert von 18 → 17 (tatsächlicher Stand: 17 echte Wiki-Seiten)
- index.md: Datum auf 2026-04-13 aktualisiert

---

## [2026-04-10] update | Obsidian Git Sync + Graph-Vernetzung + Psych-Modus

**Was passiert ist:**
- Graph-Problem gelöst: alle Notes haben jetzt bidirektionale `[[Wikilinks]]` – kein Node mehr isoliert
  - TASKS.md, Mein_Profil, Prompt-Vorlagen, Daily-Note-Vorlage, alle 6 SKILL-Dateien, architecture.md, Projektgeruest_KI_System vernetzt
- Obsidian Git eingerichtet: Second Brain läuft jetzt auf GitHub (https://github.com/EinsSkill/second-brain)
  - Auto-Sync alle 10 Minuten (commit-and-sync + pull)
- GitJournal auf Android eingerichtet → Second Brain auch vom Handy lesbar
- Neue Dauerregel: bei jeder neuen/geänderten Note automatisch Wikilinks setzen
- Neuer Modus aktiviert: laufende Psychologische Analyse parallel zu allen Gesprächen (Option C)
  - Muster und Verhalten werden auch dann analysiert wenn wir an anderen Themen arbeiten
  - Erkenntnisse fließen automatisch in Mein_Profil_Psychologische_Analyse.md ein

**Psychologische Beobachtung heute:**
- Lukes hat heute konsequent durchgezogen: GitHub-Setup, Fehler getroffen, nicht aufgehört, gelöst. Klassisches Resilienz-Muster in Aktion – aber er hat es wahrscheinlich nicht als Erfolg wahrgenommen.

---

## [2026-04-10] lint | Wöchentliche Strukturpflege

**Geprüft:**
- 34 Dateien gescannt
- 2 Probleme gefunden

**Änderungen:**
- `Skills/frontend-design-SKILL.md` → `Ressourcen/GitHub-Skills/frontend-design/SKILL.md` verschoben (nicht-schema Ordner `Skills/` bereinigt; Ordner selbst konnte wegen Dateisystem-Beschränkung nicht gelöscht werden, ist aber leer)
- TASKS.md: „CLAUDE.md mit Kontext befüllen" → ✅ Erledigt verschoben (Datei existiert und ist befüllt)
- index.md Statistik & Aktivitätsdatum aktualisiert

---

## [2026-04-10] lint | Strukturbereinigung + Produktivitätssystem

**Was passiert ist:**
- Fehlende Ordner angelegt: `Inbox/`, `Ausbildung/Berufsschule/`, `Ausbildung/NX Logistics/`, `Business/Ideen/`, `Business/Recherche/`, `Business/Aktionen/`, `Selbstentwicklung/Tagesreflexion/`
- Root-Dateien in korrekte Ordner verschoben: `Projektgeruest_KI_System.md` + `Bereich1_Claude_KI_Tools.md` → `_System/`
- `Business/Lukes_Daily.md` → `Business/Aktionen/Lukes_Daily.md`
- `KI Guide – Grundlagen.md` (leer/Duplikat) → Redirect-Stub zu `Ressourcen/KI_Guide`
- `CLAUDE.md` als schlankes Working Memory angelegt (referenziert Project_Instructions statt zu duplizieren)
- `TASKS.md` als aktive To-do-Liste angelegt
- `dashboard.html` als visuelles Task-Dashboard bereitgestellt
- Index auf 18 Seiten aktualisiert

---

## [2026-04-10] ingest | GitHub Skills + Obsidian Beautification Research

**Was passiert ist:**
- 6 GitHub Skills heruntergeladen nach `Ressourcen/GitHub-Skills/`: frontend-design, doc-coauthoring, theme-factory, web-artifacts-builder, file-organizer, obsidian-second-brain
- Vollständige Obsidian-Beautification-Guide erstellt: Minimal Theme, ExcaliBrain, Graph CSS-Snippet mit AzubiPass-Farben, Top-Plugin-Empfehlungen
- `Ressourcen/GitHub-Skills/README.md` erstellt als Übersicht + Installationsweg
- Index auf 16 Seiten aktualisiert
- SCHEMA-Grundregel gesetzt: alles Relevante wird automatisch eingepflegt

**Highlights:**
- Graph CSS nutzt bereits Lukes' Brand-Farben (#1B4332 + #C9A227)
- ExcaliBrain als beste Mindmap-Lösung identifiziert
- obsidian-second-brain Skill (24 Commands, autonomes Vault-Management) heruntergeladen

---

## [2026-04-10] ingest | Wissensbasis-Import aus Claude Memory

**Was passiert ist:**
- Umfangreiche Wissensbasis aus Claude eingepflegt (Persönliches, Beruf, Projekte, Psychologie, Interessen, Tech)
- `_System/Project_Instructions.md` vollständig aktualisiert (v2): Spitzname Cheff, Gym-Tage, Wabi-Sabi, NX-Aufgaben, Claude-Präferenzen, n8n-Stack
- `Selbstentwicklung/Mein_Profil_Psychologische_Analyse.md` erweitert: Completion Gap, produktive Prokrastination, Fortschrittsblindheit, Lebenswunsch ergänzt
- Neue Seiten angelegt: `Business/AzubiPass.md`, `Business/KitchenRise.md`, `Business/Worksheet-Projekt.md`, `Selbstentwicklung/Interessen-und-Tech.md`
- `_System/index.md` auf 13 Seiten aktualisiert

**Wichtige neue Erkenntnisse:**
- AzubiPass ist ein aktives Side Business (nicht nur Idee) – Completion Gap hier direkt relevant
- n8n als primärer Weg zu Remote-Einkommen definiert
- SOLENCE-Konzert: 24.04.2026, Köln

---

## [2026-04-10] setup | Initiales Wiki-Setup

**Was passiert ist:**
- Obsidian Vault war bereits vorhanden (`.obsidian` Ordner)
- Ordnerstruktur angelegt: Inbox, Ausbildung, Business, Selbstentwicklung, Ressourcen, _System
- 5 Dokumente aus vorherigen Claude-Gesprächen importiert:
  - `Project_Instructions.md` → `_System/`
  - `Projektgeruest_KI_System.md` → Root
  - `Bereich1_Claude_KI_Tools.md` → Root
  - `Mein_Profil_Psychologische_Analyse.md` → `Selbstentwicklung/`
  - `KI_Guide.md` → `Ressourcen/`
- Wiki-Infrastruktur erstellt: `SCHEMA.md`, `index.md`, `log.md`
- `Ressourcen/Prompt-Vorlagen.md` erstellt
- `Ressourcen/Daily-Note-Vorlage.md` erstellt

**Stand nach Setup:**
- 8 Wiki-Seiten aktiv
- Bereiche Ausbildung, Business und Tagesreflexion noch leer – wachsen mit Nutzung
- System bereit für Ingest und tägliche Nutzung

---

*Neue Einträge oben einfügen.*
