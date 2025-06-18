```bash
# 🛠️ Git Tipps & Tricks
# Autor: Mehmet Ali Karayusuf
# Datei: tipps.md
# Ziel: Praktische Git-Befehle kompakt erklärt

 🔹 1. Repository starten & verbinden
git init                       # Neues Git-Repository lokal erstellen
git clone <url>               # Bestehendes Projekt klonen
git remote add origin <url>   # Lokales Projekt mit GitHub verbinden
git remote -v                 # Verbundene Remotes anzeigen

 🔹 2. Änderungen vorbereiten & festhalten
git status                    # Aktuelle Änderungen anzeigen
git add .                     # Alle Dateien zum Commit vormerken
git commit -m "Beschreibung"  # Änderungen committen mit Nachricht
git log --oneline             # Commit-History kompakt anzeigen

# Tipp: Schreibe klare Commit-Nachrichten wie z. B. Fix: Rechtschreibung README.md

 🔹 3. Push, Pull & Remote-Arbeit
git push origin main                        # Änderungen zu GitHub senden
git pull origin main                        # Änderungen von GitHub holen
git push --set-upstream origin branch-name  # Upstream-Verknüpfung erstellen

 🔹 4. Datei-Wiederherstellung & Zwischenablage
git restore datei.txt       # Datei auf letzte gespeicherte Version zurücksetzen
git stash                   # Änderungen zwischenspeichern (temporär)
git stash pop               # Gespeicherte Änderungen wiederherstellen

 🔹 5. Aufräumen & Übersicht behalten
git diff                    # Zeigt Unterschiede vor dem Commit
git add -p                  # Änderungen interaktiv auswählen
git clean -f                # Nicht getrackte Dateien löschen (⚠️ vorsichtig!)

 🔹 6. Navigieren im Terminal
ls              # Zeigt Dateien & Ordner im aktuellen Verzeichnis
ls -la          # Zeigt auch versteckte Dateien (.git etc.)
pwd             # Zeigt den aktuellen Pfad (Working Directory)
cd <ordner>     # In einen Unterordner wechseln
cd ..           # Eine Ebene zurück
cd ../..        # Zwei Ebenen zurück
cd ~            # Zum Home-Verzeichnis springen
cd ~/Desktop    # Direkt zum Desktop (Windows/macOS)
```