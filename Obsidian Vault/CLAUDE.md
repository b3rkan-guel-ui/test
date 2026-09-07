# Vault Context

Dieses Vault ist das Zweite Gehirn von Berkan Gül.

## Über mich

Berkan Gül, aktuell Auszubildender zum Fachinformatiker für Systemintegration, im Aufbau der Selbstständigkeit. Gründet gemeinsam mit einem Kollegen ein Startup, das KI-generierte Webseiten an lokale Unternehmen verkauft: Der Kollege macht den Vertrieb, Berkan die Technik und die Erstellung der Webseiten mit Claude.

Die Ausbildung passt nicht mehr, Interesse und Motivation fehlen, eine Mahnung liegt vor. Die Entscheidung darüber ist als eigenes Projekt angelegt.

**Antrieb:** Ortsunabhängig und selbstbestimmt arbeiten, sich nie wieder fragen müssen ob das Geld reicht, und den Vater in Rente schicken können.

Ausführliches Profil in `00 Kontext/Über mich.md`.

## Sprache

**Deutsch.** Notizen, Ordner, Antworten.

## Arbeitsstil beachten

Berkan arbeitet schnell und in fokussierten Schüben, ist dabei aber eher chaotisch. Mitten in einer Aufgabe kommen oft neue Ideen dazu. Konzentration schwankt je nach Aufgabe und Tagesform.

**Daraus folgt für dich:**
- Struktur schlank halten. Keine Ordnerbürokratie vorschlagen, die gepflegt werden muss.
- Neue Ideen, die während einer Aufgabe auftauchen, sofort in `01 Inbox/` sichern, damit der Fokus auf der laufenden Aufgabe bleiben kann.
- Das Aufräumen übernimmst du, nicht Berkan.
- Antworten konkret und umsetzbar halten. Keine langen Vorreden.

## Vault-Struktur

- `00 Kontext/`: Persönliches Kontext-Profil (Über mich.md, ICP.md, Angebot.md, Schreibstil.md, Branding.md). Zentrale Referenz für alle inhaltlichen Aufgaben. **Lies diese Dateien, wenn du Content erstellst, Kundenmails schreibst, Angebote formulierst oder Webseitentexte entwirfst.**
- `01 Inbox/`: Schnelle Gedanken, Brain Dumps, unverarbeitete Notizen. Alles was noch keinen festen Platz hat landet hier.
- `02 Projekte/`: Aktive Projekte mit konkretem Ziel und Ende. Projekte starten als einzelne .md Datei. Nur bei komplexen Projekten mit mehreren Dateien einen Unterordner anlegen.
- `03 Bereiche/`: Laufende Verantwortungsbereiche ohne Enddatum. Jeder Bereich ist ein eigener Ordner, weil Bereiche über die Zeit wachsen.
- `04 Ressourcen/`: Referenzmaterial, Wissen, gesammelte Informationen. Jedes Thema ist ein eigener Ordner.
- `05 Daily Report/`: **Schreibst du.** Was in einer Session passiert ist, welche Entscheidungen getroffen wurden, was offen ist. Gibt Kontinuität zwischen Sessions. Format: `YYYY-MM-DD.md`
- `06 Daily Notes/`: **Schreibt Berkan.** Eigene tägliche Notizen. Siehe Regeln unten.
- `07 Archiv/`: Abgeschlossene Projekte und inaktive Bereiche. Aus dem aktiven Blickfeld, aber durchsuchbar.
- `08 Anhänge/`: Bilder, PDFs, Medien. Obsidian legt hier automatisch alle eingefügten Dateien ab.

## Daily Notes: So funktionieren sie

Wenn Berkan sagt **"mach mir eine Notiz"**, "notier das" oder ähnliches, kommt der Eintrag nach `06 Daily Notes/`.

**Ordnerstruktur:** Direkt unter `06 Daily Notes/` liegen genau sieben Ordner, einer pro Wochentag. Keine Wochenordner, keine weitere Ebene.

```
06 Daily Notes/
├── 01 Montag/
│   └── YYYY-MM-DD Montag.md
├── 02 Dienstag/
│   └── YYYY-MM-DD Dienstag.md
├── 03 Mittwoch/
├── 04 Donnerstag/
├── 05 Freitag/
├── 06 Samstag/
└── 07 Sonntag/
```

Beispiel: `06 Daily Notes/02 Dienstag/2026-09-08 Dienstag.md`

**Wichtig:**
- Die Ordner tragen eine zweistellige Nummer als Präfix (01 bis 07), damit sie in Obsidian in der richtigen Wochenreihenfolge stehen statt alphabetisch.
- Die Notizdatei darin trägt das Datum, aber **keine** Nummer. In jedem Wochentagsordner sammeln sich mit der Zeit mehrere Wochen, das Datum hält sie auseinander und sortiert sie chronologisch.

**Regeln:**
- Immer erst `date` per Bash prüfen. Datum und Wochentag niemals raten.
- Notiz kommt in den Ordner des heutigen Wochentags, in die Datei `YYYY-MM-DD Wochentag.md`.
- Mehrere Notizen am selben Tag werden an dieselbe Datei angehängt, jeweils mit Uhrzeit als Präfix.
- Existiert die Tagesdatei noch nicht, lege sie an. Die sieben Wochentagsordner existieren dauerhaft und werden nie gelöscht.
- **Keine leeren Notizen auf Vorrat anlegen.** Eine Tagesdatei entsteht erst, wenn wirklich etwas notiert wird.
- Wochentage auf Deutsch: Montag, Dienstag, Mittwoch, Donnerstag, Freitag, Samstag, Sonntag.

## Kontext-Profil nutzen

Bevor du irgendetwas Inhaltliches schreibst (Mail, Angebot, Webseitentext, Social Post), lies:
- `00 Kontext/Schreibstil.md` für die Tonalität
- `00 Kontext/ICP.md` wenn es an Kunden geht
- `00 Kontext/Angebot.md` wenn es um Leistungen oder Preise geht

**Kurzfassung Schreibstil:** Siezen, professionell und sachlich, bei etablierten Kunden lockerer. Nicht übertreiben, keine Marketing-Floskeln. Klar sagen was gemacht wird, was es kostet, wann es fertig ist.

## Regeln für dieses Vault

- Nutze `[[Wikilinks]]` für Verknüpfungen zwischen Notizen
- Neue Notizen ohne klaren Platz kommen in `01 Inbox/`
- Halte Notizen atomar: eine Idee pro Notiz wo möglich. Ausnahme: Daily Notes und Daily Reports fassen einen ganzen Tag zusammen.
- Nutze YAML Frontmatter: `tags`, `status` (aktiv/abgeschlossen/pausiert), `erstellt` bzw. `date`
- Dateinamen in normaler Schreibweise mit Leerzeichen und Großbuchstaben: `Beschreibender Name.md`
- Neue Projekte bekommen eine einzelne .md Datei direkt unter `02 Projekte/`. Einen Unterordner nur anlegen, wenn das Projekt mehrere Dateien braucht.
- Bereiche und Ressourcen sind immer Ordner, weil sie über die Zeit wachsen
- Abgeschlossene Projekte nach `07 Archiv/` verschieben. Nur auf Anweisung, nicht eigenständig.
- Wenn du Dateien erstellst oder verschiebst, erkläre kurz warum
- Bevor du Dateien löschst oder überschreibst, frag nach
- Prüfe das aktuelle Datum immer per `date` in Bash, nie raten

## "Merk dir das"

Wenn Berkan sagt **"merk dir das"** oder "speicher das", speichere es dort wo es thematisch hingehört:

| Was | Wohin |
|---|---|
| Schreibregel, Formulierungswunsch | `00 Kontext/Schreibstil.md` |
| Info über die Zielgruppe | `00 Kontext/ICP.md` |
| Preis, Paketdetail, Leistung | `00 Kontext/Angebot.md` |
| Branding, Name, Farben, Logo | `00 Kontext/Branding.md` |
| Persönliches, Werte, Ziele | `00 Kontext/Über mich.md` |
| Projektinfo | die jeweilige Datei in `02 Projekte/` |
| Technische Erkenntnis, Prompt, Tool | passender Ordner in `04 Ressourcen/` |
| Vault-Regel, Arbeitsweise mit Claude | diese CLAUDE.md |

Im Zweifel kurz fragen wo es hin soll.

## Session-Routinen

### Bei Session-Start
Prüfe `01 Inbox/` auf neue Notizen. Zeige was drin liegt und biete an, die Einträge in die passenden Ordner einzusortieren.

### Kontext bei Bedarf
Wenn Berkan fragt "Was ist gerade aktuell?", "Wo war ich stehen geblieben?" oder ähnliches: Lies die letzten 2 bis 3 Daily Reports in `05 Daily Report/`, die aktuellen Daily Notes der laufenden Woche und die aktiven Projektdateien in `02 Projekte/`, und gib ein kurzes Briefing.

### Bei Session-Ende
Wenn die Session endet oder ein natürliches Ende erreicht ist, biete an:
1. Einen Eintrag in `05 Daily Report/` mit einer Zusammenfassung zu erstellen
2. Neue Erkenntnisse als Notizen zu speichern
3. Die Inbox aufzuräumen falls nötig

## Installierte Skills

**Regel:** Jedes Mal wenn ein neuer Skill, ein Tool oder eine Abhängigkeit installiert wird, direkt hier eintragen: Name, Quelle/Link, kurzer Zweck, Setup-Status. Nicht erst auf Nachfrage.

In `.claude/skills/` liegen die Obsidian Skills von kepano:
`obsidian-markdown`, `obsidian-bases`, `json-canvas`, `obsidian-cli`, `defuddle`

Zusätzlich installiert:
- `excalidraw-diagram` ([coleam00/excalidraw-diagram-skill](https://github.com/coleam00/excalidraw-diagram-skill)): Erstellt Excalidraw-Diagramme aus natürlicher Sprache, inkl. visueller Validierung per Playwright-Rendering. Setup (uv sync + Chromium) ist erledigt. **Bugfix:** `references/render_template.html` importierte ursprünglich `@excalidraw/excalidraw?bundle` von esm.sh — der `?bundle`-Modus löste einen internen Import fehlerhaft auf (404 auf `sanitize-url/.../dist/constants.mjs`) und ließ das Rendering hängen. Fix: `?bundle` aus dem Import entfernt.
- `notebooklm` ([teng-lin/notebooklm-py](https://github.com/teng-lin/notebooklm-py)): Inoffizielles Python-SDK/CLI für Google Gemini Notebook (NotebookLM) — Notebooks/Quellen verwalten, Chat mit Zitaten, Generierung von Podcasts/Videos/Slides/Quiz/Mindmaps. CLI installiert via `uv tool install "notebooklm-py[browser]"`, Skill per `notebooklm skill install --scope project --target claude` direkt vom Tool selbst eingerichtet. **Setup-Status: fertig.** Login am 2026-09-06 durchgeführt und per `notebooklm auth check --test --json` bestätigt (Konto b3rkan-guel@web.de, 1 Notebook vorhanden). Einsatzbereit.
- `remotion-best-practices` ([remotion-dev/skills](https://github.com/remotion-dev/skills)): Router-Skill für Remotion (React-basiertes Framework zum programmatischen Erstellen von Videos). Installiert via `npx skills add https://github.com/remotion-dev/skills --skill remotion-best-practices`, liegt unter `.agents/skills/remotion-best-practices` und ist nach `.claude/skills/` symlinked. **Setup-Status: fertig**, sofort einsatzbereit.

### Obsidian-Plugins (Community Plugins, nicht Claude-Skills)
- **Excalidraw** (`obsidian-excalidraw-plugin`, Version 2.27.3, von [zsviczian/obsidian-excalidraw-plugin](https://github.com/zsviczian/obsidian-excalidraw-plugin)): Zeigt `.excalidraw.md`-Dateien als editierbare Zeichnung in Obsidian an. Dateien liegen im Standardformat vor (Frontmatter `excalidraw-plugin: parsed`, JSON im ` ```json `-Block unter `## Drawing`). Installiert am 2026-09-06 durch Herunterladen von main.js/manifest.json/styles.css nach `.obsidian/plugins/obsidian-excalidraw-plugin/` und Eintrag in `community-plugins.json`. **Status: Neustart von Obsidian nötig**, damit es aktiv wird — die Obsidian-CLI ("Command line interface") ist in den Einstellungen nicht aktiviert, daher kein Live-Reload möglich.

## Entwicklungsumgebung

- **Claude Code:** installiert unter `C:\Users\b3rka\.local\bin\claude`
- **Node.js:** v24.20.0, npm 11.19.0, npx verfügbar unter `C:\Program Files\nodejs\`
- **Obsidian CLI:** verfügbar
- Alle fünf Obsidian Skills sind einsatzbereit, auch `defuddle`.
