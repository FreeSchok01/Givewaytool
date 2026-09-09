🚀 Release Notes
Version 4.2.0
📢 Discord Auto-Announce
[NEU] Automatische Discord-Ankündigung bei Giveaway-Start und -Ende über euren eigenen Webhook (separat vom Entwickler-Feedback-Webhook)
[NEU] Eigene Ein/Aus-Schalter für Start- und Ende-Ankündigung, jeweils mit editierbarem Titel & Beschreibungstext
[NEU] Platzhalter {prize}, {sponsor}, {command}, {streamer} in den Ankündigungstexten nutzbar
[VERBESSERT] Discord-Versand läuft asynchron im Hintergrund-Thread, damit die App nicht blockiert
🎣 Angeln & ⛏️ Minen (neues Sammel-Minigame)
[NEU] Chat-Befehle !fish (Angeln) und !mine (Minen), je mit eigenem konfigurierbarem Cooldown pro User
[NEU] 6-stufige Loot-Tabelle pro Spiel (von "Alter Stiefel"/"Kieselstein" bis zur legendären "Schatztruhe"/"Mythril-Ader"), Coins-Auszahlung direkt ins bestehende Coins-System
[NEU] Eigenes OBS-Overlay (gather_overlay.html) mit Cast-/Schwing-Animation und Rarity-basiertem Glow-Effekt (grau → blau → lila → orange → gold) inkl. Sparkle-Partikeln bei seltenen Funden
[NEU] Loot-Tabellen direkt in der App editierbar (Name, Emoji, Gewichtung, Min/Max-Coins, Seltenheit) – kein Code-Zugriff nötig
[NEU] Test-Buttons für sofortigen Beispiel-Fang/-Fund ohne echten Chat-Befehl
[NEU] Beide Befehle automatisch in der Commands-Übersicht dokumentiert
🔄 Automatischer Updater
[NEU] Update-Fenster lädt jetzt direkt die neue .exe aus den GitHub-Release-Assets herunter, statt nur auf die Release-Seite zu verlinken
[NEU] "Automatisch installieren"-Button mit Live-Fortschrittsanzeige (Download-%)
[NEU] Automatischer Austausch der laufenden .exe nach dem Beenden per Helfer-Skript, inkl. automatischem Neustart der App
[INFO] Funktioniert nur in gebauten .exe-Releases unter Windows – beim Testen als .py-Skript bleibt der Button deaktiviert
[INFO] Setzt voraus, dass dem GitHub-Release eine .exe-Datei als Asset angehängt ist
👋 Willkommensnachricht
[NEU] Begrüßungsfenster beim allerersten Start einer neuen Version
[NEU] Erscheint automatisch genau einmal pro Version (Erkennung über gespeicherte last_seen_version)
