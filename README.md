# 🐛 Spike-Worm-Aquarium

Ein Live-Web-Betrachter für ein **digitales Aquarium aus Spike-Neuronen-Würmern**.
Jeder Wurm ist ein kleines Netz echter spikender LIF-Neuronen (Brian2) mit einem
peristaltischen Ring-Motor, einer „Nase" zum Futter-Riechen und Genen, die sich
über Auslese vererben. Nichts ist gescriptet — jeder Wurm entscheidet selbst.

## Die Seiten
- **index.html** — das Aquarium: 8 kleine Würmer in einer gemeinsamen Welt + 8 große in je eigener Welt (Mini-Cams, klickbar zum Zoomen).
- **ein_wurm.html** — ein Wurm exakt (1:1, nichts interpoliert), mit Live/Player-Umschalter.
- **landkarte.html / landkarte_gross.html** — Spuren-Landkarten: wo jeder Wurm überall war (Kopf mit Zahl = wer).
- **verlauf.html** — die gesammelten Werte über Zeit; zeigt, ob das Sozial-Gen wandert (= gelernt) oder fest liegt.

## Ehrlich
Die Seiten holen ihre Daten **live von einem Server**, auf dem der Sim rechnet.
Öffnet man sie ohne diesen Server, zeigen sie ehrlich „🚧 Baustelle" statt eines
gestellten Bildes. Kein Film, keine Schleife — echte Positionen oder nichts.

Teil des BirnPack-Forschungsprojekts. Die Fassade ist offen, das Labor bleibt zu.
