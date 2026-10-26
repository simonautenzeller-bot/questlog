# questlog

## Wochen-Backup

Die App sichert einmal pro Woche (beim Öffnen) ein Backup außerhalb des Browsers, denn gelöschte Browser-Daten nehmen sonst auch die App-Daten mit. Am Computer (Chrome/Edge) schreibt sie automatisch in einen gewählten Ordner, z. B. im OneDrive-Ordner; am Handy lädt sie nach einmaliger Einrichtung direkt in dein privates OneDrive oder erinnert dich, die Datei per „Teilen“ abzulegen. Fehlen beim Start alle Daten, bietet die App direkt das Einspielen eines Backups an. Einstellungen und Einrichtung der Microsoft-Anmeldung: **Einstellungen → Wochen-Backup**. Weiterleitungs-URI für die Microsoft-App-Registrierung: `https://simonautenzeller-bot.github.io/questlog/`. Ausführliche Anleitung: README von alltagplus. Die Logik steckt in `backup.js` (eine Kopie in jeder App).
