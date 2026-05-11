# humanizer-de

Claude Code Skill, der KI-typische Schreibmuster in **deutschen Texten** erkennt und entfernt. Ziel: Texte, die nach einem Menschen klingen — nicht nach ChatGPT.

Basiert auf Wikipedias "Anzeichen für KI-generierte Inhalte" und deutschen Stilquellen. Erkennt 28 Muster: aufgeblasene Symbolik, Werbesprache, KI-Vokabular, Füllphrasen, Chatbot-Artefakte, Gedankenstrich-Inflation, Dreierregel und mehr.

## Was der Skill macht

- Scannt Text nach KI-Mustern (28 Kategorien)
- Schreibt problematische Stellen in natürlichem Deutsch um
- Bewahrt die Kernaussage — entfernt nur den KI-Sound
- Zeigt vorher/nachher, damit man die Änderungen nachvollziehen kann

## Installation

### Per User (alle Projekte)

```bash
git clone https://github.com/edgeglobal/claude-skill-humanizer-de.git ~/.claude/skills/humanizer-de
```

### Per Projekt

```bash
git clone https://github.com/edgeglobal/claude-skill-humanizer-de.git .claude/skills/humanizer-de
```

Danach Claude Code neu starten — der Skill wird automatisch geladen.

## Verwendung

Sage Claude einfach:

- "Humanisiere diesen Text"
- "Mach das natürlicher"
- "Entferne KI-Muster"
- "Lies das wie ein Mensch"

Oder übergib eine Datei:

- "Humanisiere `draft.md`"

## Sprache

Deutsch only. Für englische Texte gibt es separate Skills.

## Lizenz

MIT — siehe [LICENSE](LICENSE).
