# My Room – Englisch Klasse 5

Lern-Web-App zum Thema *My room* (Lighthouse Basic 1, Unit 2): Vokabeln, Präpositionen, Lesen, Traumzimmer in 3D einrichten und vorstellen – mit englischer Sprachausgabe.

| Datei | Inhalt |
|---|---|
| `index.html` | Die App mit allen 5 Stationen und Ergebnissen (Startseite) |
| `raum-3d.html` | Freies 3D-Zimmer zum Ausprobieren aller Präpositionen (Werkzeug für die Lehrkraft) |
| `My-Room_Anleitung.pptx` | Anleitung für die Schülerinnen und Schüler |

## Als Webseite veröffentlichen (GitHub Pages)

1. Auf github.com: **New repository** → Name z. B. `my-room` → **Public** → *Create repository*.
2. **Add file → Upload files** → alle Dateien aus diesem Ordner hineinziehen → *Commit changes*.
3. **Settings → Pages** → *Source: Deploy from a branch* → Branch **main**, Ordner **/ (root)** → *Save*.
4. Nach 1–2 Minuten ist die App erreichbar unter
   `https://DEIN-GITHUB-NAME.github.io/my-room/`
   Das 3D-Werkzeug: `https://DEIN-GITHUB-NAME.github.io/my-room/raum-3d.html`

## Aktualisieren

Neue `index.html` über **Add file → Upload files** hochladen (gleicher Dateiname) → *Commit changes*. Nach 1–2 Minuten ist die Seite aktuell, der Link bleibt gleich.

## Gut zu wissen

- Die App braucht keinen Server und speichert keine Daten im Internet. Name, Sterne und Traumzimmer bleiben nur im Browser des jeweiligen iPads.
- Alles ist in die Dateien eingebaut (3D-Grafik, Sprachaufnahmen). Es werden keine externen Dienste geladen.
- Die Sprachaufnahmen wurden mit dem freien Sprachmodell Kokoro (Apache-2.0) erzeugt, Stimme „Fable“. Three.js steht unter MIT-Lizenz.
