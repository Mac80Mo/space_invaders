# Space Invaders - Python-Spielprojekt

## Beschreibung

Dieses Projekt wurde im Jahr 2024 im Rahmen eines Python-Kurses erstellt. Es handelt sich um eine einfache Implementierung des klassischen Spiels "Space Invaders". Der Spieler steuert ein Raumschiff und muss feindliche Aliens abschießen, um Punkte zu sammeln. Ziel ist es, so lange wie möglich zu überleben und eine hohe Punktzahl zu erreichen.

## Funktionen

- **Raumschiffsteuerung**: Bewegung nach links und rechts mit den Pfeiltasten und Schießen mit der Leertaste.
- **Feindliche Aliens**: Zufällige Positionierung und Bewegung der Gegner.
- **Punktesystem**: Spieler erhält Punkte für jeden abgeschossenen Gegner.
- **Game Over**: Das Spiel endet, wenn ein Alien die untere Grenze des Spielfensters erreicht.

## Voraussetzungen

Um das Spiel auszuführen, müssen folgende Voraussetzungen erfüllt sein:

- **Python**: Version 3.7 oder höher
- **Pygame**: Version 2.0 oder höher

### Installation von Pygame

Du kannst Pygame mit dem folgenden Befehl installieren:

```bash
pip install pygame
```

## Dateistruktur

Das Projekt verwendet folgende Dateien:

- **Hauptskript**: `main.py` (enthält den Spielcode)
- **Bilder**:
  - `spr_space_himmel.png` (Hintergrundbild)
  - `spr_spaceship.png` (Bild des Raumschiffs)
  - `spr_patrone.png` (Bild der Geschosse)
  - `spr_space_enemy.png` (Bild der Gegner)

Stelle sicher, dass alle Bilddateien im selben Verzeichnis wie das Hauptskript gespeichert sind.

## Spielanleitung

1. Starte das Spiel mit folgendem Befehl:

   ```bash
   python main.py
   ```

2. **Steuerung**:

   - Bewege das Raumschiff nach links: **Pfeiltaste links**
   - Bewege das Raumschiff nach rechts: **Pfeiltaste rechts**
   - Schieße eine Patrone: **Leertaste**

3. Ziel: Schieße alle Aliens ab, bevor sie die untere Grenze des Spielfensters erreichen.

4. Punkte werden oben links im Spielfenster angezeigt.

## Codeübersicht

Das Projekt besteht aus den folgenden Klassen:

- **`Game`**: Verwaltet das Spielfenster, den Spielzustand und die Hauptspielschleife.
- **`Spaceship`**: Repräsentiert das Raumschiff des Spielers.
- **`Bullet`**: Stellt die Geschosse dar, die vom Raumschiff abgefeuert werden.
- **`Enemy`**: Repräsentiert die Gegner im Spiel.

## Erweiterungsmöglichkeiten

Hier sind einige Ideen, um das Spiel weiterzuentwickeln:

- **Levelsystem**: Erhöhe die Schwierigkeit mit jedem Level, indem du die Geschwindigkeit der Gegner erhöhst oder deren Anzahl steigerst.
- **Soundeffekte**: Füge Schusseffekte und Hintergrundmusik hinzu.
- **Power-ups**: Implementiere Boni, die der Spieler sammeln kann (z. B. schnellere Geschosse, größere Explosionen).
- **Highscore-System**: Speichere und zeige die besten Punktzahlen an.

## Autor

Dieses Projekt wurde von **M. Moser** während eines Python-Kurses im Jahr 2024 erstellt.

## Lizenz

Dieses Projekt ist unter der MIT-Lizenz veröffentlicht. Weitere Informationen findest du in der Datei `LICENSE`.


