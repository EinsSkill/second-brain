# 🎮 Spielstand Transfer: PC → Lemuroid (Android)

*Für GBA-Spiele (z.B. [[Gaming/Pokemon_Unbound_Top4|Pokémon Unbound]])*

**Verwandte Seiten:** [[Gaming/Pokemon_Unbound_Top4]] · [[Selbstentwicklung/Interessen-und-Tech]]

---

## Das Problem

PC-Emulatoren und Lemuroid nutzen unterschiedliche Formate:

| Emulator | Format | Größe |
|---|---|---|
| PC (VBA-M etc.) | `.sav` | 131.088 Bytes |
| Lemuroid (Android) | `.srm` | 131.072 Bytes |

Die 16 Bytes Unterschied sind ein Footer den der PC-Emulator anhängt — Lemuroid kann damit nichts anfangen.

---

## Anleitung

### 1. Spielstand konvertieren (PC)
Die 16 Byte am Ende abschneiden und als `.srm` speichern:
```bash
dd if="Pokemon Unbound.sav" of="Pokemon Unbound.srm" bs=1 count=131072
```

Oder mit Claude: Datei hochladen, Claude macht das automatisch.

### 2. Datei richtig benennen
Der Dateiname muss **exakt** dem ROM-Namen entsprechen:
- ROM: `Pokemon Unbound (v2.1.1.1).zip`
- Save: `Pokemon Unbound (v2.1.1.1).srm`

### 3. Auf's Handy kopieren
1. **Lemuroid komplett schließen** (aus App-Switcher rausschieben!)
2. Handy per USB mit PC verbinden
3. Im Windows Explorer navigieren zu:
   ```
   Pixel 8a → Interner Speicher → Android → data → com.swordfish.lemuroid → files → saves → gba
   ```
4. Alte `.srm`-Datei ersetzen
5. Lemuroid starten → Spielstand geladen ✅

---

## ⚠️ Wichtig

- Lemuroid **muss** geschlossen sein vor dem Kopieren — sonst überschreibt er beim Beenden die Datei
- Auf Android 11+ ist `/Android/data/` nur per USB-Verbindung zugänglich (nicht über Handy-Dateimanager)

---

*Erstellt: 2026-04-14*
