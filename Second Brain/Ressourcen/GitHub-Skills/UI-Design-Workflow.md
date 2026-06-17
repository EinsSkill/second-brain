# 🎨 UI Design Workflow – Automatischer 4-Stufen-Prozess

*Eingerichtet: Juni 2026*

> Dieser Workflow ist in `C:\Users\Lukes\CLAUDE.md` hinterlegt und läuft bei jedem UI-Task automatisch ab – ohne dass du etwas tun musst.

---

## Was ist das?

4 Design-Tools die Claude bei jedem Frontend-Task automatisch der Reihe nach einsetzt:

| Stufe | Tool | Aufgabe |
|---|---|---|
| 1 | **taste-skill** | Situation lesen, Dials setzen, Anti-Slop-Filter |
| 2 | **ui-ux-pro-max** | Farben, Schriften, Stil wählen |
| 3 | **Magic MCP** | Fertige Komponenten generieren |
| 4 | **emilkowalski-ui** | Details polieren, Animationen, Micro-Interactions |

---

## Die 4 Stufen im Detail

### Stufe 1 – Design Read (taste-skill)

Bevor Code geschrieben wird, liest Claude die Situation:
- Was für eine Seite? (Landing, App, Dashboard, ...)
- Für wen? (Gamer, B2B, Consumer, ...)
- Welcher Vibe? (gamifiziert, minimalistisch, dunkel, ...)

Dann setzt Claude 3 Dials:
- `DESIGN_VARIANCE` – wie experimentell (1–10)
- `MOTION_INTENSITY` – wie animiert (1–10)
- `VISUAL_DENSITY` – wie luftig/vollgepackt (1–10)

**Anti-Slop-Regel:** Kein KI-lila Gradient, kein zentrierter Hero auf dunklem Mesh, kein Inter-Font auf alles.

---

### Stufe 2 – Design System (ui-ux-pro-max)

Wählt automatisch:
- Passende Farbpalette (aus 161 Optionen)
- Typografie (aus 57 Schriftpaarungen)
- UI-Stil (aus 67 Stilen: Minimalism, Cyberpunk, Retro/8-Bit, Brutalism, ...)

---

### Stufe 3 – Komponenten (Magic MCP)

Magic MCP von 21st.dev generiert fertige Komponenten:
- Hero Sections, Navigation, Cards, Modals, Pricing Tables
- Animierte Elemente
- Mobile-optimierte Layouts

---

### Stufe 4 – Polish (emilkowalski-ui)

Emil Kowalski's Design-Engineering-Philosophie:
- `ease-out` für eintretende Elemente (fühlt sich schneller an)
- Buttons brauchen `:active` State (`scale(0.97)`)
- Nichts erscheint aus dem Nichts: `scale(0.95) + opacity(0)` als Start
- Hover States auf allem Klickbaren
- Konsistentes 8px-Spacing-Grid

---

## Trigger-Wörter (automatische Aktivierung)

Claude aktiviert diesen Workflow automatisch wenn du sagst:
- UI, Design, Komponente, Button, Screen, Layout
- Animation, Frontend, Seite, App-Oberfläche
- Landing Page, Style, Farben, Schriften

---

## Wo die Skill-Dateien liegen

| Datei | Pfad |
|---|---|
| Master Workflow | `C:\Users\Lukes\.claude\skills\ui-workflow.md` |
| taste-skill | `C:\Users\Lukes\.claude\skills\taste-skill.md` |
| emilkowalski-ui | `C:\Users\Lukes\.claude\skills\emilkowalski-ui.md` |
| ui-ux-pro-max | `C:\Users\Lukes\.claude\skills\ui-ux-pro-max.md` |
| impeccable | `C:\Users\Lukes\Desktop\Second Brain\.claude\skills\impeccable\` |

---

## Nützliche Befehle

```
# impeccable aktualisieren
npx impeccable update

# Magic MCP neu hinzufügen (falls nötig)
claude mcp add magic --scope user --env API_KEY="..." -- npx -y @21st-dev/magic@latest
```

---

*Verwandte Seiten: [[Ressourcen/GitHub-Skills/README]] · [[_System/Bereich1_Claude_KI_Tools]]*
