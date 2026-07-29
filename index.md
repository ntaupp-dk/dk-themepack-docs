---
layout: default
title: DRYKORN Themepack — Inhaltselemente
---

# DRYKORN Themepack — Inhaltselemente

Handbuch fuer Redakteure. Dieses Dokument beschreibt alle verfuegbaren Inhaltselemente im TYPO3-Backend.
Fuer jedes Element werden Zweck, Felder und Hinweise zur Nutzung erlaeutert.

---

## Inhaltsverzeichnis

1. [Hero Banner](#hero-banner)
2. [Card Group](#card-group)
3. [Category Group](#category-group)
4. [Look Group](#look-group)
5. [Lookbook](#lookbook)
6. [Wall Grid](#wall-grid)
7. [Icon Group](#icon-group)
8. [Gallery](#gallery)
9. [Accordion](#accordion)
10. [Tab](#tab)
11. [Timeline](#timeline)
12. [USPs](#usps)
13. [Progress Bar](#progress-bar)
14. [Kategorie-Navigation](#kategorie-navigation)
15. [Footer Navigation](#footer-navigation)
16. [Media](#media)
17. [Container / Layouts](#container--layouts)
18. [News: WE_MIND Blog](#news-we_mind-blog)
19. [News: Jobs / Karriere](#news-jobs--karriere)

---

## Banner

### Hero Banner

Grossflaechiges Bannerelement fuer den Seiteneinstieg. Zeigt ein Bild oder Video ueber die volle Seitenbreite mit optionalem Text-Overlay und Button. Mehrere Slides sind moeglich.

![Hero Banner](Screenshots/hero-banner.png)

#### Optionen des Elements

| Feld | Beschreibung |
|------|-------------|
| Ueberschrift | Wird oberhalb des Banners angezeigt (optional). |
| Text & Buttons zentriert | Zentriert den Text-Overlay ueber dem gesamten Banner. |
| Hoehe | Klein / Mittel / Gross. Bestimmt die sichtbare Hoehe des Banners. |
| Variante | 1-spaltig / 2-spaltig / 2-spaltig Text mittig / 3-spaltig. Bestimmt die Aufteilung der Slides. |
| Rahmen oben/unten | Fuegt oben und/oder unten einen sichtbaren Rahmen hinzu. |

<details markdown="1">
<summary>Felder pro Slide-Eintrag</summary>

| Feld | Beschreibung |
|------|-------------|
| Ueberschrift | Headline auf dem Slide. |
| Text | Beschreibungstext (Richtext-Editor). |
| Bild / Video | Hintergrundbild oder -video fuer den Slide. |
| Link / Link-Titel | Button-Link und dessen Beschriftung. |
| Linktyp | Detail / Navigation / Landingpage / Extern / Modal. |
| Textfarbe | Aendert die Textfarbe (Standard: Schwarz). |
| Hintergrundfarbe | Weiss / Hellgrau / Dunkel / Verlauf — als farbiger Overlay. |

</details>

> **Tipp:** Fuer helle Bilder die Textfarbe auf Schwarz setzen; bei dunklen Bildern eine helle Hintergrundfarbe waehlen, damit der Text lesbar bleibt. Bei Linktyp »Modal« wird ein Video-Overlay geoeffnet statt eines Seitenwechsels.

---

## Karten, Gruppen & Galerien

### Card Group

Zeigt Inhalte als Kartengitter an — ideal fuer Teaser, Stories oder Lookbooks. Auf Mobilgeraeten werden die Karten als Slider dargestellt.

![Card Group](Screenshots/card-group.png)

#### Optionen des Elements

| Feld | Beschreibung |
|------|-------------|
| Stil | Kein / Teaser / Story / Fixe Hoehe. Bestimmt die Darstellungsart. |
| Karten-Stil | Kein / Weisser Hintergrund / Heller Hintergrund / Dunkler Hintergrund / Rahmen. |
| Ausrichtung | Links / Zentriert / Rechts. |
| Animation | Aktiviert eine Einblendanimation (Fade-Up) mit zeitversetztem Erscheinen. |
| Spalten | 1 / 2 / 3 / 4 Spalten im Desktop-Layout. |

<details markdown="1">
<summary>Felder pro Karte</summary>

| Feld | Beschreibung |
|------|-------------|
| Typ | Story / Teaser / Lookbook — beeinflusst die Darstellung. |
| Bild | Visuelles Element der Karte. |
| Text | Kartentext (Richtext). |
| Link / Link-Titel | Verlinkung der Karte. |
| Linktyp | Bei »Modal« wird ein Video-Overlay geoeffnet. |

</details>

---

### Category Group

Shopware-Kategorie-Slider mit Herren/Damen-Umschalter. Zeigt Produktkategorien als Slider mit verschiedenen Darstellungsarten: Freisteller, Editorial-Bilder oder Texteinblendungen.

![Category Group](Screenshots/category-group.png)

#### Optionen des Elements

| Feld | Beschreibung |
|------|-------------|
| Ueberschrift | Titel ueber dem Slider. |
| Peek-Effekt | Zeigt beim Laden kurz an, dass weitere Inhalte vorhanden sind. |
| Rahmen | Rahmenlinien oben/unten. |

<details markdown="1">
<summary>Felder pro Kategorie-Eintrag</summary>

| Feld | Beschreibung |
|------|-------------|
| Typ | Freisteller / Editorial-Text aussen / Editorial-Text innen / NOS. |
| Hauptkategorie | Herren / Damen — bestimmt, bei welchem Tab die Karte erscheint. |
| Kategorie-Label | Beschriftung der Kategorie. |
| Bild-Anpassung | Cover (zuschneiden) oder Contain (vollstaendig anzeigen). |
| Unterkategorien | Inline-Eintraege mit Bild, Link, Titel und Subline. |

</details>

> **Tipp:** Ueber die Hauptkategorie (Herren/Damen) wird automatisch ein animierter Tab-Umschalter erzeugt. Bei Typ »Freisteller« wirkt ein freigestelltes Produktbild am besten.

---

### Look Group

Outfit-Slider, der komplette Looks mit verlinkten Produkten zeigt. Jeder Slide enthaelt ein grosses Look-Bild mit kleinen Produkt-Icons, die auf die jeweiligen Produktseiten verlinken.

![Look Group](Screenshots/look-group.png)

<details markdown="1">
<summary>Felder pro Look-Eintrag</summary>

| Feld | Beschreibung |
|------|-------------|
| Titel | Name des Looks. |
| Look-Bild | Das Hauptbild des Outfits. |
| Produkt-Bilder | Bis zu 3 kleine Produktbilder. Jedes kann auf eine Produktseite verlinkt werden. |

</details>

---

### Lookbook

Bildergalerie im Fashion-Lookbook-Stil. Unter jedem Bild koennen bis zu 3 Produkt-Links hinterlegt werden, die auf den Shopware-Shop verweisen.

![Lookbook](Screenshots/lookbook.png)

#### Felder

| Feld | Beschreibung |
|------|-------------|
| Ueberschrift | Titel des Lookbooks. |
| Textfarbe | Schwarz oder Standard. |
| Bilder | Die Lookbook-Bilder. Pro Bild koennen bis zu 3 Produkt-Links und Kategorien hinterlegt werden. |

> **Tipp:** Die Produkt-Links und Kategorien werden direkt an der jeweiligen Bildreferenz eingetragen — die Felder erscheinen, sobald ein Bild hinzugefuegt wurde.

---

### Wall Grid

Bildwand-Layout mit Rasterdarstellung. Alle 8 Bilder wird automatisch ein Textblock (Subueberschrift und Bodytext) eingeblendet. Jedes Bild kann individuell mit einem Shopware-Produktlink versehen werden.

![Wall Grid](Screenshots/wall-grid.png)

#### Felder

| Feld | Beschreibung |
|------|-------------|
| Ueberschrift / Subueberschrift | Titel und Zwischentitel fuer den eingeblendeten Textblock. |
| Text | Richtext-Inhalt fuer den Textblock. |
| Bilder | Pro Bild: Ausrichtung, Mobil-Ausblendung und individueller Link. |
| Rahmen | Rahmenlinien oben/unten. |

---

### Icon Group

Raster aus Icons mit begleitendem Text — fuer Features, Services oder Vorteile. Icons koennen aus den hinterlegten Icon-Sets oder als eigenes Bild hochgeladen werden.

![Icon Group](Screenshots/icon-group.png)

#### Optionen des Elements

| Feld | Beschreibung |
|------|-------------|
| Ausrichtung | Links / Zentriert / Rechts. |
| Spalten | Auto / 1–7 Spalten. |
| Icon-Position | Links-Oben / Links-Mitte / Rechts-Oben / Rechts-Mitte / Darueber / Darunter. |

<details markdown="1">
<summary>Felder pro Icon-Eintrag</summary>

| Feld | Beschreibung |
|------|-------------|
| Text | Beschreibung neben dem Icon (Richtext). |
| Link | Optionale Verlinkung. |
| Icon-Set / Icon | Auswahl aus den verfuegbaren Icon-Bibliotheken. |
| Icon-Datei | Alternativ: eigenes Bild als Icon hochladen. |

</details>

---

### Gallery

Bildergalerie mit einstellbarem Seitenverhaeltnis. Ideal fuer Kampagnenbilder oder Produktfotos in einheitlichem Format.

![Gallery](Screenshots/gallery.png)

#### Felder

| Feld | Beschreibung |
|------|-------------|
| Bilder | Die Galeriebilder. |
| Seitenverhaeltnis | 4:3 / 16:9 / 1:1 — alle Bilder werden einheitlich zugeschnitten. |
| Elemente pro Seite | Anzahl der sichtbaren Bilder pro Seite. |
| Rahmen | Rahmenlinien oben/unten. |

---

## Listen & interaktive Elemente

### Accordion

Aufklappbare Bereiche — z.B. fuer FAQ, Produktdetails oder Zusatzinformationen. Jeder Bereich kann Richtext oder eine Tabelle sowie Medien enthalten.

![Accordion](Screenshots/accordion.png)

#### Optionen des Elements

| Feld | Beschreibung |
|------|-------------|
| Ueberschrift | Titel ueber dem Accordion. |
| Standard-Element | Welches Panel beim Laden automatisch geoeffnet ist (FlexForm). |

<details markdown="1">
<summary>Felder pro Accordion-Eintrag</summary>

| Feld | Beschreibung |
|------|-------------|
| Ueberschrift | Titel des aufklappbaren Bereichs (Pflichtfeld). |
| Tabellen-Modus | Schaltet zwischen Richtext und Tabellendarstellung um. |
| Text | Inhalt des Bereichs (Richtext oder Tabelle). |
| Textbreite | 25% / 33% / 50% / 75% der Gesamtbreite. |
| Medien | Bilder oder Videos neben dem Text. |
| Medien-Ausrichtung | Links / Oben / Rechts / Unten. |
| Bildspalten | 1–6 Spalten fuer die Medienansicht. |

</details>

> **Tipp:** Im Tabellen-Modus koennen Groessentabellen oder Datenvergleiche komfortabel dargestellt werden. Die Textbreite und Medien-Ausrichtung ermoeglichen flexible Layouts innerhalb jedes Panels.

---

### Tab

Tab-Navigation mit mehreren Reitern. Jeder Reiter zeigt beim Klick seinen Inhalt an (Medien wie Bilder oder Videos).

![Tab](Screenshots/tab.png)

#### Optionen des Elements

| Feld | Beschreibung |
|------|-------------|
| Ueberschrift | Titel ueber den Tabs. |
| Standard-Tab | Welcher Tab beim Laden aktiv ist (FlexForm). |

<details markdown="1">
<summary>Felder pro Tab-Eintrag</summary>

| Feld | Beschreibung |
|------|-------------|
| Ueberschrift | Tab-Beschriftung in der Navigation. |
| Medien | Bilder oder Videos, die im Tab-Bereich angezeigt werden. |

</details>

---

### Timeline

Vertikale Zeitleiste mit Datumsmarkierungen — z.B. fuer Unternehmensgeschichte, Meilensteine oder Projektverlaeufe.

![Timeline](Screenshots/timeline.png)

#### Optionen des Elements

| Feld | Beschreibung |
|------|-------------|
| Ueberschrift | Titel ueber der Timeline. |
| Sortierung | Aufsteigend / Absteigend (nach Datum). |

<details markdown="1">
<summary>Felder pro Timeline-Eintrag</summary>

| Feld | Beschreibung |
|------|-------------|
| Datum | Das Datum des Eintrags — die Jahreszahl wird als Markierung angezeigt. |
| Ueberschrift | Titel des Zeitpunkts. |
| Text | Beschreibung (Richtext). |
| Icon | Icon aus einer Bibliothek oder als eigene Datei. |
| Bild | Optionales Bild zum Eintrag. |

</details>

---

### USPs

Horizontale Leiste mit Alleinstellungsmerkmalen (Unique Selling Points). Wird als scrollbares Karussell mit Icons und Text dargestellt — z.B. fuer Versandvorteile, Serviceversprechen oder Zertifizierungen.

![USPs](Screenshots/usps.png)

<details markdown="1">
<summary>Felder pro USP-Eintrag</summary>

| Feld | Beschreibung |
|------|-------------|
| Text | Kurzbeschreibung des USP (Richtext). |
| Icon | Icon aus einer Bibliothek oder als eigene Datei. |

</details>

---

### Progress Bar

Animierte Fortschrittsbalken — z.B. fuer Nachhaltigkeitsziele, Skill-Levels oder Projektfortschritte. Die Balken werden beim Scrollen animiert.

![Progress Bar](Screenshots/progress-bar.png)

<details markdown="1">
<summary>Felder pro Balken</summary>

| Feld | Beschreibung |
|------|-------------|
| Bezeichnung | Label des Balkens (Pflichtfeld). |
| Wert | Prozentwert von 0–100 (Pflichtfeld). |

</details>

---

## Spezialelemente

### Kategorie-Navigation

Horizontale Navigationsleiste mit Links zu Shopware-Kategorien. Zeigt einen Intro-Text und darunter eine Reihe von Kategorie-Links.

![Kategorie-Navigation](Screenshots/kategorie-navigation.png)

#### Felder

| Feld | Beschreibung |
|------|-------------|
| Kategorie-Intro | Einleitungstext ueber der Navigation. |

<details markdown="1">
<summary>Felder pro Navigationseintrag</summary>

| Feld | Beschreibung |
|------|-------------|
| Titel | Anzeigetext des Links. |
| Link | Shopware-Pfad (Slug der Kategorie). |
| Linktyp | Landingpage / Detail / Navigation / Extern. |

</details>

---

### Footer Navigation

Aufklappbare Spalte im Footer-Bereich. Zeigt eine Ueberschrift als Klappmenue-Trigger und den Inhalt als erweiterbaren Bereich (auf Mobilgeraeten).

![Footer Navigation](Screenshots/footer-navigation.png)

#### Felder

| Feld | Beschreibung |
|------|-------------|
| Ueberschrift | Titel der Footer-Spalte — dient gleichzeitig als Klapp-Trigger. |
| Text | Inhalt der Spalte (Richtext) — z.B. Links, Kontaktdaten, Texte. |

---

### Media

Universelles Medien-Element fuer Bilder, Videos (YouTube, Vimeo, MP4) und PDFs. Unterstuetzt Galerie-Layouts und kann auf Mobilgeraeten ausgeblendet werden.

![Media](Screenshots/media.png)

#### Felder

| Feld | Beschreibung |
|------|-------------|
| Bilder / Videos | Medien aus der Dateiliste. |
| Medienspalten | 1–6 Spalten fuer die Darstellung. |
| Abstand | Normaler oder grosser Abstand zwischen Medien. |
| Mobil verbergen | Blendet das Element auf kleinen Bildschirmen aus. |

---

## Container / Layouts

Container sind keine eigenstaendigen Inhaltselemente, sondern Huellen, die andere Elemente in Spalten-Layouts anordnen.

### Verfuegbare Container

| Container | Beschreibung |
|-----------|-------------|
| 2 Spalten (gleich) | Zwei gleichbreite Spalten nebeneinander. |
| 2 Spalten (links breit) | Linke Spalte breiter als rechte (ca. 60/40). |
| 2 Spalten (rechts breit) | Rechte Spalte breiter als linke (ca. 40/60). |
| 3 Spalten | Drei gleichbreite Spalten. |
| 4 Spalten | Vier gleichbreite Spalten. |
| Slider | Umschliesst Elemente in einem horizontalen Slider. |
| Tabs | Umschliesst Elemente in einer Tab-Navigation. |

> **Tipp:** Container koennen verschachtelt werden. Beispiel: Innerhalb einer 2-Spalten-Anordnung kann eine Spalte wiederum einen Slider enthalten.

### Gemeinsame Optionen (Frame)

Jedes Inhaltselement — ob eigenstaendig oder in einem Container — besitzt im Tab **Erscheinungsbild** folgende Optionen:

| Option | Beschreibung |
|--------|-------------|
| Layout | Frame-Groesse: Default / Small / Medium / Large / Full Width. |
| Frame-Klasse | Optischer Rahmen des Elements (z.B. Well, Jumbotron, Ruler, None). |
| Abstand oben/unten | Extra / Default / Small / None — steuert den vertikalen Abstand. |
| Hintergrundfarbe | Transparent / Primary / Secondary / Tertiary / Quaternary / Light / Dark. |

---

## News: WE_MIND Blog

Die Blog-Beitraege werden ueber die **News-Extension** (georgringer/news) verwaltet. Im Backend werden sie als News-Datensaetze im Ordner **WE_MIND** (SysFolder PID 189) gepflegt.

![News Blog Liste](Screenshots/news-blog-liste.png)

### Einrichtung auf einer Seite

1. Inhaltselement **News system > News-Listenansicht** einfuegen.
2. Im Plugin die Startseite/Storage auf den WE_MIND-Ordner setzen.
3. Fuer die Detailansicht: auf derselben Seite ein zweites News-Plugin als **Detailansicht** einfuegen, oder das gleiche Plugin im Modus *Liste und Detail* nutzen.

### Felder eines Blog-Beitrags

| Feld | Beschreibung |
|------|-------------|
| Typ | **Blog-Beitrag** (Typ 0, templateLayout 10). |
| Titel | Ueberschrift des Beitrags. |
| Teaser | Kurztext fuer die Listenansicht. |
| Datum | Veroeffentlichungsdatum — bestimmt die Sortierung. |
| Bild | Vorschaubild fuer Liste und Detailansicht (Hero). |
| Inhalt (Content Elements) | Der eigentliche Beitragsinhalt wird ueber eingebettete Inhaltselemente (Texte, Bilder, etc.) aufgebaut. |
| Kategorien | Fuer Filterung in der Listenansicht. |
| Tags | Fuer Filterung in der Listenansicht. |
| Verwandte Dateien | PDFs oder andere Dateien zum Download im Beitrag. |

![News Blog Detail](Screenshots/news-blog-detail.png)

> **Tipp:** Die Listenansicht zeigt automatisch einen Kategorie-Filter. Blog-Beitraege haben das templateLayout **WE_MIND (10)**, was das spezielle Blog-Design aktiviert.

---

## News: Jobs / Karriere

Stellenanzeigen werden ebenfalls ueber die **News-Extension** verwaltet, jedoch als eigener Typ **Karriere** (Typ 1, templateLayout 99). Sie liegen im SysFolder **Karriere** (PID 204).

![News Karriere Liste](Screenshots/news-karriere-liste.png)

### Einrichtung auf einer Seite

1. Inhaltselement **News system > News-Listenansicht** einfuegen.
2. Im Plugin die Startseite/Storage auf den Karriere-Ordner setzen.
3. Die Detailansicht wird auf derselben Seite angezeigt. Der Seitentitel wird automatisch aus dem News-Titel uebernommen.

### Felder einer Stellenanzeige

| Feld | Beschreibung |
|------|-------------|
| Typ | **Karriere** (Typ 1, templateLayout 99). |
| Titel | Stellenbezeichnung (wird als Headline der Detailseite angezeigt). |
| Dachzeile | Erscheint oberhalb des Titels (z.B. Bereich oder Standort). |
| Teaser | Kurztext fuer die Listenansicht. |
| Datum | Veroeffentlichungsdatum. |
| Bild | Headerbild fuer die Detailseite (vollflaechig). |
| Content Elements | Hauptinhalt der Stellenanzeige — typischerweise mit 2-Spalten-Layout (Beschreibung links, Sidebar rechts). |
| Meta-Daten | Level und Standort — werden in einer eigenen Meta-Leiste unterhalb des Headers angezeigt. |
| Kategorien | Fuer Filterung (z.B. Abteilung, Standort). |

![News Karriere Detail](Screenshots/news-karriere-detail.png)

### Aufbau der Detailseite

Die Karriere-Detailseite hat ein eigenes Layout:

1. **Header** — Vollflaechiges Headerbild mit Dachzeile und Stellentitel.
2. **Meta-Leiste** — Zeigt Level und Standort in voller Breite.
3. **Inhaltsbereich** — Typischerweise 2-Spalten-Layout mit Stellenbeschreibung (links) und Sidebar (rechts, z.B. Ansprechpartner, Quick-Facts).

> **Tipp:** Die Detailansicht bricht automatisch aus dem Frame der Listenansicht aus, sodass Header und Meta-Leiste vollflaechig dargestellt werden, waehrend der Inhaltsbereich im normalen Seitenlayout bleibt.

---

*DRYKORN Themepack — dk_themepack fuer TYPO3 v13*
