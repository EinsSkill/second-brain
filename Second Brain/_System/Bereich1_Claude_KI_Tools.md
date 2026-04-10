# 1️⃣ Bereich 1 – Claude & KI-Tools einrichten

> **Ziel:** Claude Pro + Google-Tools so einrichten, dass sie täglich reibungslos funktionieren.
> **System:** Windows
> **Status:** 🔲 In Bearbeitung

---

## 🔧 Schritt 1 – Claude Desktop App installieren

Die Desktop-App ist besser als der Browser: schneller erreichbar, läuft im Hintergrund, kein Tab-Wechsel nötig.

**So geht's:**
1. Gehe zu **claude.ai/download**
2. Windows-Version herunterladen & installieren
3. Mit deinem Claude Pro Account anmelden
4. App an die Taskleiste pinnen (Rechtsklick → „An Taskleiste anheften")

**Warum wichtig:** Wenn Claude einen Klick entfernt ist, nutzt du es automatisch öfter.

---

## 🧠 Schritt 2 – Memory aktivieren & befüllen

Memory sorgt dafür, dass Claude dich in jedem Gespräch kennt – ohne dass du dich jedes Mal neu vorstellst.

**Aktivieren:**
1. Einstellungen öffnen (unten links, dein Profilbild)
2. → **Capabilities**
3. Beide Optionen aktivieren:
   - ✅ **Search and reference past chats**
   - ✅ **Generate memory from chat history**

**Befüllen – schreib Claude das einmal:**
```
Merk dir folgendes über mich dauerhaft:
- Ich mache eine Ausbildung zum Kaufmann für Büromanagement bei NX Logistics in Bedburg
- 1. Ausbildungsjahr
- Arbeitszeiten: Montag, Donnerstag, Freitag 8–16 Uhr
- Berufsschule (Weingard): Dienstag & Mittwoch 8–13:10 Uhr
- Meine Hauptziele: Leben auf die Kette bekommen, beste Version meiner selbst werden, eigenes Business aufbauen
- Kommunikation: locker & freundschaftlich, einfache Sprache, kurz & präzise
- Ich bin auf Windows
```

**Memory prüfen:**
- Einstellungen → Capabilities → „View memory" – dort siehst du was Claude gespeichert hat
- Du kannst es jederzeit bearbeiten oder löschen

---

## 📁 Schritt 3 – Projects anlegen & einrichten

Projects sind getrennte Arbeitsbereiche. Jedes hat eigene Memory, eigene Dokumente, eigene Chats.

**Diese 5 Projects anlegen:**

### Project 1: 📚 Ausbildung & Schule
**Beschreibung (ins Project kopieren):**
```
Ich bin Azubi KfB im 1. Ausbildungsjahr bei NX Logistics.
Berufsschule: Di & Mi 8–13:10 Uhr (Weingard Berufsschule).

Dieses Project ist für: Lernfragen, Prüfungsvorbereitung,
Zusammenfassungen vom Schulstoff, Aufgaben aus der Ausbildung.

Erkläre mir Dinge immer einfach mit Praxisbeispielen.
Wenn ich Stoff hochlade, hilf mir daraus Zusammenfassungen
und Prüfungsfragen zu erstellen.
```

### Project 2: 💼 Business-Aufbau
**Beschreibung:**
```
Ich will parallel zur Ausbildung ein eigenes Business aufbauen.
Noch keine konkrete Idee – wir entwickeln das zusammen.

Dieses Project ist für: Ideenfindung, Marktrecherche,
Business-Analyse, Content-Planung, erste Schritte.

Sei ehrlich und kritisch – ich will realistische Einschätzungen,
keine leeren Motivationsfloskeln.
```

### Project 3: 🧠 Selbstentwicklung
**Beschreibung:**
```
Ich will die beste Version meiner selbst werden –
körperlich, mental, organisatorisch.

Dieses Project ist für: Wochenplanung, Reflexion,
Zielsetzung, Entscheidungshilfe, persönliche Themen.

Du kennst meinen Wochenrhythmus (Arbeit Mo/Do/Fr,
Schule Di/Mi). Nutze das bei Planungen.
```

### Project 4: ✍️ Kreatives & Texte
**Beschreibung:**
```
Für alles was ich schreibe: Social Media Posts,
Texte, Ideen ausformulieren, kreative Projekte.

Ton: authentisch, direkt, nicht zu förmlich.
Zielgruppe meistens: Gleichaltrige, junges Publikum.
```

### Project 5: 📅 Wochenpläne & Organisation
**Beschreibung:**
```
Für Wochenplanung, To-do-Listen und Organisation.

Mein Rhythmus:
- Mo, Do, Fr: Arbeit 8–16 Uhr
- Di, Mi: Schule 8–13:10 Uhr
- Abende & Wochenende: frei für Business & Privates

Erstell Pläne immer realistisch – kein Overloading.
```

---

## 💬 Schritt 4 – Prompt-Cheatsheet anlegen

Speichere diese Vorlagen in Obsidian unter `Ressourcen/Prompt-Vorlagen.md`.
So musst du häufige Anfragen nicht jedes Mal neu tippen.

### Allgemein
```
Erkläre mir [Thema] – einfache Sprache, mit Beispiel, max. 5 Sätze.
```

### Schule / Lernen
```
Ich habe nächste Woche eine Prüfung über [Thema].
Erstell mir 15 Prüfungsfragen mit Antworten für KfB 1. Jahr.
```
```
Hier ist meine Mitschrift: [Text einfügen]
Erstell daraus eine strukturierte Lernzusammenfassung.
```
```
Ich habe [X] Tage Zeit und muss lernen: [Themen-Liste]
Täglich [X] Minuten verfügbar. Erstell mir einen Lernplan.
```

### Planung
```
Hier ist was ich diese Woche erreichen will: [Liste]
Ich arbeite Mo/Do/Fr, Schule Di/Mi.
Erstell mir einen realistischen Wochenplan mit Zeitblöcken.
```

### E-Mails (Ausbildung)
```
Schreib mir eine professionelle aber nicht zu steife E-Mail an
[Empfänger / Ausbilder / Lehrer].
Ich will mitteilen: [Kernaussage].
Ich bin Azubi im 1. Jahr.
```

### Entscheidungen
```
Ich bin unentschlossen zwischen [Option A] und [Option B].
Kontext: [kurze Beschreibung].
Erstell mir eine ehrliche Pro/Contra-Analyse und sag mir deine Empfehlung.
```

### Business
```
Ich habe folgende Business-Idee: [Beschreibung]
Analysiere sie kritisch: Stärken, Risiken, Zielgruppe,
wie ich sie mit wenig Aufwand testen kann.
```

### Reflexion (abends)
```
Hier ist meine heutige Reflexion: [Text aus Daily Note]
Was sind die wichtigsten Learnings? Was sollte ich morgen anders machen?
```

---

## 🌐 Schritt 5 – Google-Tools einrichten

### NotebookLM Plus (Lern-Tool)
1. Gehe zu **notebooklm.google.com**
2. Mit deinem Google-Konto anmelden (das mit Google One Premium)
3. Notizbuch „Berufsschule" anlegen
4. Erste Quellen hochladen (PDFs, Mitschriften, YouTube-Links)
5. „Audio Overview" generieren lassen → beim Heimweg anhören

**Erster Test:** Lade deinen nächsten Schulstoff hoch und lass dir einen Podcast daraus generieren.

### Gemini in Gmail
1. Gmail im Browser öffnen (mail.google.com)
2. Neue E-Mail schreiben → Button „Hilfe beim Schreiben" (Stift-Symbol mit Stern)
3. Kurz beschreiben was die E-Mail sagen soll → Entwurf generieren lassen
4. Anpassen & abschicken

### Gemini App
1. **gemini.google.com** oder Gemini-App installieren
2. Nutze es als Ergänzung zu Claude für:
   - Schnelle Web-Suche mit KI
   - Wenn du gerade in Google-Apps arbeitest
   - Bilder generieren (Whisk)

---

## 🔍 Schritt 6 – Perplexity als Recherche-Tool

Perplexity = KI-Suche die dir direkte Antworten mit Quellen gibt statt einer Link-Liste.

1. Gehe zu **perplexity.ai**
2. Konto erstellen (kostenlos reicht)
3. Als Standard-Suche testen wenn du was recherchierst

**Wann Perplexity statt Google:**
- Aktuelle Infos brauchst (z.B. „Was sind aktuell beliebte Business-Modelle für Einzelpersonen?")
- Du eine Zusammenfassung statt Links willst
- Du mehrere Quellen auf einmal durchsuchen willst

---

## ✅ Checkliste – Bereich 1 komplett

### Sofort (Tag 1-2)
- [ ] Claude Desktop App installieren (claude.ai/download)
- [ ] App an Taskleiste pinnen
- [ ] Memory aktivieren (Einstellungen → Capabilities)
- [ ] Memory mit Kontext befüllen (Text aus Schritt 2 kopieren)

### Diese Woche (Tag 3-7)
- [ ] 5 Projects anlegen mit den Beschreibungen aus Schritt 3
- [ ] Prompt-Cheatsheet in Obsidian anlegen
- [ ] NotebookLM: erstes Notizbuch anlegen + testen
- [ ] Gemini in Gmail: einmal eine E-Mail schreiben lassen
- [ ] Perplexity: einmal für eine Recherche nutzen

### Nächste Woche
- [ ] Jeden Tag mindestens 1x Claude bewusst für eine Aufgabe nutzen
- [ ] Nach 7 Tagen: Memory prüfen was Claude sich gemerkt hat
- [ ] Prompt-Vorlagen ergänzen mit eigenen häufigen Anfragen

---

## 📊 Erfolgs-Check nach 2 Wochen

Stelle dir diese Fragen:
1. Nutze ich Claude täglich oder fast täglich?
2. Fühlt es sich natürlich an, Claude für Probleme zu fragen?
3. Spare ich Zeit bei Schulaufgaben, E-Mails oder Planung?
4. Weiß Claude meinen Kontext ohne dass ich ihn neu erkläre?

Wenn du 3 von 4 mit Ja beantwortest → Bereich 1 erfolgreich ✅

---

*Nächster Schritt nach Bereich 1: [[Bereich 2 – Obsidian Second Brain aufbauen]]*
