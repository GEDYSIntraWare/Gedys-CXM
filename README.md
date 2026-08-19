# Gedys-CXM
Gedys CXM Teams Integration. Dateien und Anleitung zur Erstellung einer Zip Datei, um Gedys CXM in Teams zu installieren.

Wichig! Achten Sie darauf, dass Sie sich die passende Manifest Version zu Ihrer CXM Version herunterladen. Zum Beispiel CXM Version 11 benötigt die Manifest von Gedys CXM für CXM Version 11. Dafür gibt es die verschiedenen Releases.

Erstellung der Zip Datei:
1. In manifest.json alle "MicrosoftAppID" Einträge, durch die ID der Entra App Registrierung für den Bot ersetzen.

2. Damit die Linkvorschau für Datensätze in MS Teams funktioniert, in manifest.json alle "CXMURL" Einträge, durch die öffentlich erreichbare URL zur CXM Instanz ersetzen. (www.example.com/cxm)

3. color.png, de.json, manifest.json und outline.png zusammen ohne Ordner in eine Zip datei packen.

4. Wie die Zip benutzt werden kann, um die Teams App im Teams Admin Center zu installieren, ist im technischen Handbuch von Gedys CXM zu finden. 
https://www.manula.com/manuals/business-app/business-app-handbuch/12.0/de/topic/4-20-3-installation-der-app-im-teams-admin-center
