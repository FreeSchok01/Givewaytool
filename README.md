Giveaway Pro ist ein hochgradig anpassbares, professionelles Giveaway-Tool für Twitch-Streamer. Es kombiniert einen leistungsstarken Chat-Bot zur automatischen Teilnehmererfassung mit beeindruckenden, animierten OBS-Overlays.
✨ Features (Neu in v1.1.3)
🤖 Automatischer Chat-Bot: Zuschauer tippen einfach !giveaway (anpassbar) in den Chat, um teilzunehmen.
🎥 OBS Browser-Quellen: Animierte Slot-Machine (Rollen), aktive Giveaway-Banner und Live-Gewinnerlisten direkt im Stream.
⏱️ Timeout & Strike-System: Meldet sich der Gewinner nicht innerhalb der eingestellten Zeit im Chat, wird automatisch neu gezogen!
🎵 Dynamische Custom Sounds: Lade eigene MP3s hoch für das Rollen, Bestätigen und Gewinnen. Sounds loopen automatisch und brechen sofort ab, wenn der Gewinner sich meldet.
🔄 Mehrfach-Ziehungen (Multi-Draw): Ziehe bis zu 10 Gewinner gleichzeitig (mit Warteschlangen-System).
💤 Integriertes Lurk-Tool: Belohne deine Lurker mit einem eigenen !lurk Command und Willkommens-Nachrichten.
📊 Live Stream Stats: Behalte Teilnehmer, Peak-Zuschauer, Chat-Nachrichten und Top-Chatter im Blick.
🚀 Integrierter Auto-Updater: Lade neue Versionen (.exe) direkt mit einem Klick aus der App herunter!
📥 Installation

Die fertige .exe nutzen (Empfohlen für Streamer)
Gehe rechts auf dieser Seite auf Releases.
Lade die Datei GiveawayTool_v1.1.0.exe herunter.
Führe die .exe aus. (Windows Defender könnte eine Warnung anzeigen, klicke auf "Weitere Informationen" -> "Trotzdem ausführen").
Fertig! Das Tool erstellt alle benötigten Dateien automatisch in demselben Ordner.

📖 Anleitung: So startest du dein erstes Giveaway
Schritt 1: Login mit Twitch
Beim ersten Start öffnet sich das Login-Fenster. Klicke auf "Mit Twitch verbinden". Es öffnet sich dein Browser. Bestätige die Berechtigungen für den Bot. Das Fenster schließt sich danach automatisch und du bist im Dashboard.
![Login Screen]([HIER BILD EINFÜGEN: Screenshot vom Twitch Login Fenster der App])
Schritt 2: OBS Overlays einrichten
Damit deine Zuschauer das Giveaway sehen, musst du die Overlays in OBS Studio (oder Streamlabs) hinzufügen.
Gehe in der App links im Menü auf 🎥 OBS Tools.
Kopiere die URL für die "Gewinner-Slot Animation" (http://localhost:8765/winner_slot.html).
Füge in OBS eine neue Browser-Quelle hinzu.
Setze das Häkchen bei Lokale Datei NICHT. Füge die URL ein.
Empfohlene Größe: Breite 1280, Höhe 720.
(Du kannst dasselbe für das aktive Giveaway-Banner und die Multi-Gewinnerliste tun!)
Schritt 3: Einstellungen & Sounds anpassen
Bevor es losgeht, passe das Tool an deinen Stream an:
Gehe auf ⚙️ Setup: Stelle ein, wie lange die Slot-Maschine rollen soll und wie viele Sekunden der Gewinner Zeit hat, um "Hier!" in den Chat zu schreiben.
Gehe auf 🔊 Sounds: Aktiviere Sounds oder lade deine eigenen MP3-Dateien für den maximalen Hype hoch!
Schritt 4: Giveaway Starten
Gehe zum 🏠 Dashboard.
Trage bei "Gewinn" ein, was es zu gewinnen gibt (z.B. 1x Tier 1 Sub).
Passe bei Bedarf den Command an (z.B. !mitmachen).
Klicke auf ▶️ Fortsetzen. Das Giveaway ist nun "Aktiv"! Der Bot postet eine Nachricht im Chat und Zuschauer können sich eintragen.
Schritt 5: Den Gewinner ziehen
Wenn genug Teilnehmer da sind, klicke auf ⏸️ Pausieren, um die Teilnahme zu schließen.
Klicke auf 🎲 Gewinner ziehen (OBS).
Die Animation in OBS startet, die Spannung steigt und der Sound wird abgespielt!
Sobald der Name feststeht, wartet das Tool. Sobald der Gewinner etwas in den Twitch-Chat schreibt, drücke auf ✅ Gewinner da! (Bestätigen). Der Win-Sound ertönt!
Hat der Gewinner sich nicht in der eingestellten Zeit gemeldet? Das Tool gibt ihm einen "Strike", wirft ihn aus der Liste und zieht vollautomatisch jemand Neues!
🛠️ Fehlerbehebung (Troubleshooting)
Die Browser-Quelle in OBS bleibt unsichtbar / lädt nicht?
Das Tool muss geöffnet sein, damit die HTML-Seiten in OBS funktionieren (es startet einen kleinen lokalen Server). Aktualisiere notfalls die Browser-Quelle in OBS.
Sounds werden nicht abgespielt?
Stelle sicher, dass in den Sound-Einstellungen (🔊 Sounds) die Haken gesetzt sind und die Lautstärke nicht auf 0 steht. Falls du eigene MP3s nutzt, überprüfe, ob der Dateipfad noch stimmt.
Der Bot schreibt nicht im Chat?
Gehe in den Tab 🤖 Chat Bot und überprüfe, ob dort "Status: Verbunden (Grün)" steht. Falls nicht, klicke einmal auf "Bot Starten".
❤️ Feedback & Support
Dir gefällt das Tool, du hast einen Bug gefunden oder hast eine Idee für ein neues Feature?
Nutze einfach den 💬 Feedback & Bugs Tab direkt in der App! Deine Nachricht landet dann direkt beim Entwicklerteam.
Erstellt von FreeSchok Studio.
Wenn dir meine Arbeit gefällt, freue ich mich über einen Kaffee! ☕
💖 Hier Spenden
