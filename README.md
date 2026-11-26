# Website-Entwurf: Städtisches Klinikum Hamburg

Diese Website besteht aus statischen Dateien und benötigt weder Datenbank noch Backend. Das bereitgestellte Logo liegt unter `assets/logo.png`. Die Website ist als Entwurf gekennzeichnet und enthält bewusst keine erfundenen Klinik- oder Kontaktdaten. Startseite, Über uns, Kollegium, Abteilungen, Karriere und Kontakt sind eigenständige Seiten.

## Inhalte bearbeiten

Öffne die jeweilige HTML-Datei in einem Texteditor und ersetze die deutlich gekennzeichneten Platzhalter durch deine bestätigten Angaben. Kollegiumsfotos lassen sich lokal im Ordner `assets` ablegen und in `kollegium.html` einbinden. Für Änderungen am Erscheinungsbild bearbeite `style.css`. Prüfe vor einer Veröffentlichung insbesondere, ob Angaben korrekt und zur Veröffentlichung freigegeben sind. Ergänze gegebenenfalls ein Impressum, eine Datenschutzerklärung und weitere rechtlich erforderliche Angaben; welche Pflichten gelten, hängt vom konkreten Angebot und Betreiber ab.

## Kostenlos auf GitHub Pages veröffentlichen

1. Melde dich bei GitHub an oder erstelle ein Konto. Erstelle über **New repository** ein neues öffentliches Repository (z. B. `klinikum-website`).
2. Öffne das Repository und wähle **Add file → Upload files**. Lade den **Inhalt** dieses Ordners hoch: alle HTML-Dateien, `style.css`, `README.md` und den Ordner `assets` mit `logo.png`. Achte darauf, dass `index.html` und die weiteren HTML-Dateien direkt im Hauptverzeichnis liegen, nicht in einem zusätzlichen Unterordner. Bestätige mit **Commit changes**. Falls der Browser den Ordner-Upload nicht unterstützt, erstelle `assets` separat oder lade die Dateien mit Git hoch.
3. Öffne **Settings → Pages**. Wähle unter **Build and deployment** bei **Source** die Option **Deploy from a branch**. Wähle den Branch `main` und den Ordner `/ (root)` und klicke auf **Save**.
4. Warte, bis die Veröffentlichung abgeschlossen ist. Unter **Settings → Pages** erscheint der öffentliche Link, üblicherweise `https://DEIN-NUTZERNAME.github.io/klinikum-website/`. Den genauen Link von GitHub kopieren und im Browser testen. Der Link ist erst nach der erfolgreichen Veröffentlichung erreichbar.
5. Füge den Link in einen Discord-Chat ein und sende ihn ab. Alle mit Zugriff auf den öffentlichen Link können die Seite öffnen.

Wenn bereits eine ältere Version veröffentlicht ist, lade die neuen Dateien in dasselbe Repository hoch und ersetze die bestehenden Dateien. Achte darauf, auch die neuen HTML-Unterseiten hochzuladen. Nach dem Commit veröffentlicht GitHub die Änderungen erneut; das kann einige Minuten dauern.

## Lokal ansehen

`index.html` im Browser öffnen. Für den Betrieb der Website ist kein eigener Server nötig.
