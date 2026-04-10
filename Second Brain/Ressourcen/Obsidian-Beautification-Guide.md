---
tags: [ressourcen, obsidian, setup]
erstellt: 2026-04-10
aktualisiert: 2026-04-10
---

# 🎨 Obsidian Schöner Machen – Kompletter Guide

*Recherchiert April 2026. Fokus: Graph View, Mindmaps, Themes.*

---

## 🏆 Schritt 1 – Das beste Theme: Minimal

**Minimal Theme** ist das mit Abstand populärste Obsidian-Theme (⭐4.9k, offiziell Obsidian Best Theme Award).

**Installieren:**
1. Einstellungen → Erscheinungsbild → Community Themes durchsuchen
2. Nach "Minimal" suchen → installieren
3. Dazu **Minimal Theme Settings** Plugin installieren (gibt dir Farbregler, Font-Auswahl, etc.)
4. Dazu **Style Settings** Plugin installieren (für feine Anpassungen)

**Farbpaletten die gut aussehen:**
- `Dracula` – dunkel, lila/pink Akzente (sehr beliebt)
- `Gruvbox` – warm, retro, dunkelgrün/gelb → passt zu deinen AzubiPass-Farben
- `Nord` – kalt, blau-grau, clean
- `Everforest` – dunkelgrün, natürlich → passt perfekt zu deiner Wabi-Sabi-Ästhetik ✨

**Empfehlung für dich:** Minimal + Everforest oder Gruvbox (grün/gold, wie dein AzubiPass-Branding)

---

## 🕸️ Schritt 2 – Graph View aufwerten

### Eingebaut: Farb-Gruppen setzen
In der Graph View oben rechts → Einstellungen → **Gruppen**:
- Eigene Farben pro Ordner/Tag vergeben
- Zum Beispiel: Business = Gold, Selbstentwicklung = Grün, Ausbildung = Blau, System = Grau
- So sieht der Graph sofort strukturiert aus

### Plugins für den Graph:

**`Graph Analysis`** *(Community Plugin)*
→ Findet versteckte Verbindungen zwischen Notizen mit Graph-Algorithmen
→ Zeigt dir welche Seiten thematisch verwandt sind auch ohne direkte Links

**`Graph Banner`** *(Community Plugin)*
→ Zeigt einen Mini-Graph oben in jeder Notiz – siehst sofort was verbunden ist

**`Juggl`** *(Community Plugin)*
→ Kompletter Ersatz für den Standard-Graph – voll stilisierbar, interaktiv, mit Filtern
→ Kannst einzelne Node-Farben, -Größen und Labels selbst bestimmen

**`New 3D Graph`** *(Community Plugin)*
→ Rendert den Graph in 3D – spektakulär anzusehen, praktischer Nutzen begrenzt aber sieht gut aus

**`Tags Routes`** *(Community Plugin)*
→ 3D-Graph speziell für Tags und Verknüpfungen, mit visuellen Effekten

---

## 🧠 Schritt 3 – Mindmaps

**`ExcaliBrain`** ← **Beste Wahl** *(Community Plugin)*
→ Interaktive Mindmap des gesamten Vaults, inspiriert von "TheBrain"
→ Zeigt Eltern-, Kind- und Geschwister-Beziehungen zwischen Notizen
→ Klickbar, navigierbar, sehr visuell
→ Funktioniert mit deinen bestehenden `[[Links]]` sofort

**`Mind Map` / `Mindmap Nextgen`** *(Community Plugins)*
→ Rendert eine einzelne Notiz als Mindmap (basiert auf Markmap)
→ Gut für Lernzettel und Strukturübersichten

**`Better Mind Map`** *(Community Plugin)*
→ Interaktive Mindmaps direkt aus einer Notiz heraus

**`Canvas Mindmap`** *(Community Plugin)*
→ Macht das Obsidian Canvas wie eine Mindmap bedienbar

---

## ✨ Schritt 4 – Weitere optische Upgrades

**`Beautitab`**
→ Neuer Tab wird zu einer schönen Startseite mit Hintergrund, Uhrzeit, Zitat, Suche

**`Colored Tags Wrangler`**
→ Vergib Farben an Tags → sieht im Graph und in Notizen deutlich besser aus

**`Style Settings`** *(Pflicht-Plugin)*
→ Feinste CSS-Kontrolle über fast alles ohne Code schreiben zu müssen

**`CSS Editor`**
→ Direkt CSS-Snippets im Editor schreiben – für Fortgeschrittene

---

## 🎨 Graph View CSS-Snippet (sofort verwendbar)

Erstelle eine Datei `.obsidian/snippets/graph-colors.css` mit folgendem Inhalt und aktiviere sie unter Einstellungen → Erscheinungsbild → CSS-Snippets:

```css
/* Graph View – Custom Colors */
.graph-view.color-fill {
  color: #1B4332; /* Dark Forest Green – deine Brand-Farbe */
}

.graph-view.color-fill-tag {
  color: #C9A227; /* Gold – deine zweite Brand-Farbe */
}

.graph-view.color-fill-attachment {
  color: #6B7280;
}

.graph-view.color-fill-unresolved {
  color: #374151;
}

.graph-view.color-arrow {
  color: #C9A227;
}

.graph-view.color-line {
  color: #2D6A4F;
}
```

→ Damit sind Node-Farben genau deine AzubiPass-Brand-Farben (Grün + Gold)

---

## 📋 Empfohlene Installations-Reihenfolge

1. **Minimal Theme** + Minimal Theme Settings + Style Settings → Basis
2. **ExcaliBrain** → Mindmap/Graph
3. **Graph Analysis** → versteckte Verbindungen
4. **Colored Tags Wrangler** → Farb-Tags
5. **Beautitab** → Startseite
6. **Graph Banner** → Mini-Graph in Notizen

---

## 🔗 Verbindungen

- [[_System/SCHEMA]] – Second Brain Grundstruktur
- [[Ressourcen/GitHub-Skills/README]] – Skill-Übersicht
- [[Business/AzubiPass]] – Brand-Farben (#1B4332 + #C9A227) für Graph-CSS

---

*Quellen: GitHub, Obsidian Community Plugins Registry, April 2026*
