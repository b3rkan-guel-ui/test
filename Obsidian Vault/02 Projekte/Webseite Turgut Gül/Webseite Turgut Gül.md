---
tags: [projekt, webseite, referenzprojekt]
status: aktiv
erstellt: 2026-09-06
kunde: Turgut Gül
---

# Webseite Turgut Gül

## Ziel

Eine moderne, übersichtliche Webseite für meinen Vater Turgut Gül, Bildhauer in Alf an der Mosel. Mit schönen Animationen und starker Bildwirkung. Seine alte Seite ist nicht mehr erreichbar.

Gleichzeitig unser **erstes Referenzprojekt**: Was hier entsteht, können wir bei der Akquise vorzeigen.

## Ausgangslage

Die alte Domain **atelier-guel.de** existiert noch, liefert aber nur noch `HTTP 403 Forbidden`. Die Seite war technisch von 2011/2012: PHP mit Session-IDs in der URL, jQuery-Slider, Google Analytics alter Bauart, nicht mobiloptimiert.

**Gute Nachricht:** Die komplette alte Seite liegt im Internet Archive, inklusive **197 Fotos** seiner Arbeiten.
Archiv-Stand: `web.archive.org/web/20180830*/atelier-guel.de`

## Vita (aus der alten Seite rekonstruiert)

| Zeitraum | Station |
|---|---|
| 1972 | Geboren am 20.10.1972 in Kirka/Eskişehir, Türkei |
| 1992–1996 | Grund- und Volksschule in Kirka, Eskişehir |
| 1996–1999 | Sommerakademie in Nevşehir/Avanos, Schwerpunkt Skulpturen |
| 1999–2001 | Herstellung von Plastiken in der eigenen Firma „Bukalemum" |
| 2001 | Umzug nach Alf an der Mosel |
| seit 2002 | Freiberuflicher Bildhauer in Alf/Mosel, Mitglied im BBK Rheinland-Pfalz |

> **Zu prüfen:** Die Zuordnung der Jahreszahlen stammt aus einer JavaScript-Timeline und könnte verrutscht sein. Vor dem Livegang mit Papa durchgehen.

## Ausstellungen und Projekte

| Jahr | Was |
|---|---|
| 1994 | Schülerausstellung, Satur Akbank Künstlergalerie, Eskişehir |
| 1995 | Schülerausstellung, Kaufhaus Zafer, Ankara |
| 1996 | Ausstellung zum 10-jährigen Bestehen der Künstlerakademie „Palais Künstlergalerie Eskişehir" |
| 2002 | Teilnahme am Siemens Kunstpreis, Aufnahme in den Siemens Kunstkatalog |
| 2003 | Ausstellung in Bullay/Mosel im Rahmen des Bullayer Kultursommers |
| 2004 | Teilnahme an der Kunstmeile in Cochem |
| 2005 | Ausstellung in Pünderich/Mosel, Motto „Propheten aus dem eigenen Land" |
| 2007 | Porträts aus Sandstein für Mesenich/Mosel: „Mesenicher Steinreichsköpp" |
| 2009 | Ausstellung Alte Schule in Kaisersesch, Ausstellung Gillenbeuren, 40 Jahre Kunst im Landkreis Cochem-Zell |
| 2019 | **Kunstkreisel Alf**: vier lebensgroße Figuren aus GFK. Schmied, Winzerin beim Keltern, Angler und Mann beim Eisenabstich. Eröffnet am 03.10.2019 |
| — | Mosaikbank Bullay, Projekt „Garten der Begegnung", gemeinsam mit Schülern der IGS Zell |

## Leistungen (Original-Formulierungen der alten Seite)

- **Porträts** — Nach Fotovorlage individuell gefertigte Sandstein-Reliefs oder Stein-Plastiken
- **Hausschilder** — Individuell gestaltet nach Kundenwunsch
- **Skulpturen und Plastiken** — „Das Thema bestimmt das Material, das Material bestimmt das Thema. Ob Holz, Stein oder Metall: Jedes Objekt gewinnt seine eigene, starke Ausdrucksform."
- **Grabgestaltung** — „Grabsteine, die das Andenken an einen lieben Menschen bewahren und einen Begegnungsort zur Trauerbewältigung gestalten."
- Außerdem: Reliefs, Gravuren, Natursteinarbeiten

## Werktitel aus den alten Galerien

Gott sei Dank · Winzer und Kind · Sich befreien · Am Bahnhof · Figur aus Metall · Mein Pferd und ich · Figur-Kopf Pastor · Figur-Kopf Winzer · Relief Familie · Relief Winzer · Figur Heiliger Urban · Relief Gauner · Relief Böser Mann · Heiliger · Dreifaltigkeit

## Kontaktdaten (Stand alte Seite)

- **Turgut Gül**, Mühlenstraße 8, 56859 Alf/Mosel
- E-Mail: info@atelier-guel.de
- Telefon: noch zu klären
- Mitglied: BBK Rheinland-Pfalz

## Bildmaterial

Im Archiv gesichert, nach Kategorien:

| Kategorie | Anzahl | Quelle |
|---|---|---|
| Skulpturen | 83 | Internet Archive |
| Projekte | 53 | Internet Archive |
| Grabmale | 27 | Internet Archive |
| Hausschilder | 9 | Internet Archive |
| **Vom Block zum Porträt** | **56** | **Eigene Fotos, 2005** |

**Gesamt: 228 aufbereitete Bilder.**

Die Serie „Vom Block zum Porträt" stammt aus `C:\Users\b3rka\Pictures\Baba Hugos Stein`
und dokumentiert die Entstehung einer Sandstein-Porträtbüste von Januar bis Februar 2005:
Modellsitzen, Grobarbeit, Feinarbeit, fertige Büste, Signatur im Stein.

> **Nicht verwendet:** `C:\Users\b3rka\Pictures\Alte Handy Fotos Baba` (72 Fotos, 2018).
> Überwiegend private Familienbilder, nichts fürs Web. Ausnahme: ein graviertes
> Grabmal aus Schiefer, das später in die Grabmal-Galerie passen könnte.

## Projektordner

`C:\Users\b3rka\Projekte\atelier-guel`

Bewusst außerhalb des Vaults. Der Vault ist für Notizen, der Code liegt getrennt davon.

## Tech-Stack (festgelegt)

- **Astro 5** — statischer Seitengenerator, Build in unter 2 Sekunden
- **Tailwind CSS 4** — Gestaltung
- **sharp** — Bildaufbereitung nach WebP
- Schriften lokal eingebunden, kein Google-Fonts-Aufruf, DSGVO-freundlich
- **Web3Forms** für das Kontaktformular, kostenlos und ohne eigenen Server

Dieser Stack ist bewusst so gewählt, dass er sich für Kundenprojekte wiederverwenden lässt.

## Stand

Die Seite ist gebaut und läuft lokal unter `http://localhost:4321`.

**Umgesetzt:**
- Startseite mit Titelbereich, Leistungen, Werkgalerie, Kunstkreisel, Vita, Kontakt
- 172 Bilder aufbereitet, Galerie mit Lightbox (Pfeiltasten, Escape, Klick daneben)
- Kontaktformular mit Anliegen-Auswahl, Spamschutz und Datenschutz-Häkchen
- Impressum und Datenschutzerklärung
- Scroll-Animationen, mobiles Menü, Sprungmarke für Screenreader
- Strukturierte Daten (LocalBusiness) für Google

## Gestaltung

Dunkler Steinton als Basis, Bronze als Akzent, Cormorant als Schrift für Überschriften.
Der Werke-Bereich ist bewusst hell gehalten, weil die Atelierfotos vor weißem Hintergrund
aufgenommen wurden und so sauber wirken.

## Nächste Schritte

- [x] Archivbilder herunterladen und sichten
- [x] Tech-Stack festlegen
- [x] Telefonnummer klären: 06542 969987
- [x] Erste Version bauen
- [x] Eigene Fotos ergänzt: 56er-Serie „Vom Block zum Porträt"
- [x] Porträtfoto von Papa im Vita-Bereich eingebaut
- [ ] **Persönlichkeitsrechte klären:** Auf vielen Fotos der Serie sind Auftraggeber und
      Gäste zu sehen. Für die Seite wurden bewusst nur Bilder gewählt, die Papa selbst
      oder die Arbeit zeigen. Vor dem Livegang trotzdem gegenprüfen.
- [x] Galerie nach **Werken** gruppiert statt Einzelbildern (30 Arbeiten statt 172 Kacheln)
- [x] Leistungs-Kacheln springen jetzt in ihre eigene Kategorie
- [ ] **Kunstkreisel fotografieren.** Im Archiv ist kein einziges Foto davon, weil die alte
      Seite 2018 archiviert wurde und der Kreisel erst im Oktober 2019 eröffnet wurde.
      Das Bild an der Stelle zeigte in Wahrheit den Heiligen Urban. Aktuell steht der
      Kreisel nur im Text. Vier Fotos der Figuren wären ein großer Gewinn.
- [ ] Werktitel gegenchecken: viele sind von mir vergeben, Papa kennt die richtigen
- [ ] Papa die Seite zeigen und Rückmeldung einholen
- [ ] Vita mit Papa gegenchecken (Jahreszahlen aus der alten Timeline sind unsicher)
- [ ] Web3Forms-Key anlegen, damit das Formular wirklich Mails verschickt
- [ ] Eigene, aktuelle Fotos ergänzen (vor allem vom Kunstkreisel und aus dem Atelier)
- [ ] Foto von Papa selbst für den Vita-Bereich
- [ ] Werktitel den Bildern zuordnen (aktuell nur Kategorien)
- [ ] Klären: alte Domain reaktivieren oder neue registrieren?
- [ ] Hosting auswählen und Livegang

## Notizen

Siehe auch [[Webseiten-Produktion mit Claude]] und [[Erste Kunden gewinnen]].

Sitemap/Seitenstruktur als Excalidraw-Diagramm: [[Sitemap.excalidraw]]
