# Sales Master 30 – iPhone PWA

## Was enthalten ist
- 30 deutschsprachige B2B-Sales-Lektionen
- Lernziele, Konzepte, praktische Übungen und Transferaufgaben
- Wissenstest pro Lektion
- Notizen pro Tag (lokal gespeichert)
- Fortschrittsanzeige
- Drei B2B-Rollenspiel-Szenarien mit Coaching-Hinweisen
- Dark Mode, Home-Screen-Metadaten und Offline-Cache

## Wichtig: Für „Zum Home-Bildschirm“ wird eine HTTPS-Adresse benötigt
Eine PWA kann nicht allein aus einer ZIP-Datei dauerhaft wie eine installierbare Web-App auf dem iPhone installiert werden. Die Dateien müssen zuerst über eine HTTPS-Website bereitgestellt werden.

## iPhone-only Hosting über GitHub Pages
1. Safari öffnen und bei GitHub anmelden oder ein Konto erstellen.
2. Ein neues öffentliches Repository erstellen, z. B. `sales-master-30`.
3. Repository öffnen und über **Add file → Upload files** alle Dateien aus diesem Ordner hochladen (nicht den übergeordneten Ordner als einzelne ZIP).
4. Commit durchführen.
5. Im Repository **Settings → Pages** öffnen.
6. Bei „Build and deployment“ `Deploy from a branch` auswählen, Branch `main`, Ordner `/ (root)`, dann speichern.
7. Warten, bis GitHub Pages eine HTTPS-Adresse anzeigt.
8. Diese Adresse in Safari auf dem iPhone öffnen.
9. Teilen → **Zum Home-Bildschirm** → **Als Web-App öffnen** (falls angeboten) → Hinzufügen.

Die Bezeichnungen der GitHub-Menüs können sich ändern. GitHub Pages stellt statische Dateien bereit; die App benötigt dafür kein Backend.

## Nutzung
- Lernfortschritt und Notizen werden in `localStorage` des Browsers gespeichert.
- Safari-Daten löschen oder ein anderer Browser/ein anderes Gerät kann lokale Daten entfernen bzw. nicht übernehmen.
- Der Offline-Cache wird nach dem ersten erfolgreichen Online-Aufruf eingerichtet.
- Der Trainer enthält keine echte generative KI und keine automatische Textbewertung.

## Grenzen
- Noch keine Anmeldung, Cloud-Synchronisierung, Push-Erinnerungen, Audio-Rollenspiele oder KI-Anbindung.
- Keine App-Store-Veröffentlichung.
- Rechtliche Hinweise zu B2B-Direktwerbung in Deutschland sind bewusst allgemein gehalten; die konkrete Zulässigkeit ist im Einzelfall zu prüfen.
- Lerninhalte sind ein Grundlagenprogramm und ersetzen keine praktische Berufserfahrung.
