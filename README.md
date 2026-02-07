# Podlove Publisher Templates (Lautfunk)

Diese Sammlung enthält Twig-Templates für den [Podlove Publisher](https://publisher.podlove.org/) (WordPress Plugin).
Verwendet u.a. für **Lautfunk** Projekte.

## 📂 Inhalt

Dieses Repository dient als Speicher für Templates, die in WordPress unter **Podlove -> Templates** genutzt werden können.

Typische Templates (Beispiele):
- `episode.twig` - Darstellung einer einzelnen Episode
- `archive.twig` - Liste aller Episoden (Archiv)
- `player.twig` - Konfiguration des Web-Players
- `contributor.twig` - Darstellung der Mitwirkenden

## 🚀 Benutzung

1. Die gewünschte `.twig` Datei hier im Repo öffnen.
2. Inhalt kopieren.
3. In WordPress gehen zu: `Podlove` -> `Templates`.
4. Neues Template anlegen (ID merken!) und Code einfügen.
5. Im Shortcode nutzen: `[podlove-template template="DEINE-ID"]`

## 🛠 Anpassungen

Anwender sollten folgende Stellen prüfen und anpassen:
- **CSS-Klassen**: Die HTML-Struktur passt evtl. nicht zu jedem Theme. Prüfe `class="..."` Attribute.
- **Podcast-Logik**: Manche Templates filtern nach Shows oder Kategorien – diese IDs müssen angepasst werden.
- **Bilder**: Statische Bild-URLs müssen durch eigene ersetzt werden.

---
*Managed by OpenClaw & Sascha*
