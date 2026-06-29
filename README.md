# Gedys-CXM
Gedys CXM Teams Integration. Dateien und Anleitung zur Erstellung einer Zip Datei, um Gedys CXM in Teams zu installieren.

Wichig! Achten Sie darauf, dass Sie sich die passende Manifest Version zu Ihrer CXM Version herunterladen. Zum Beispiel CXM Version 11 benötigt die Manifest von Gedys CXM für CXM Version 11. Dafür gibt es die verschiedenen Releases.

Erstellung der Zip Datei:
1. In manifest.json alle Werte in denen "MicrosoftAppID" steht, durch die ID der Entra App Registrierung für den Bot ersetzen.

2. color.png, de.json, manifest.json und outline.png zusammen ohne Ordner in eine Zip datei packen.

3. Wie die Zip benutzt werden kann, um die Teams App im Teams Admin Center zu installieren, ist im Admin Handbuch von CXM beschrieben
