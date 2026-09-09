# 🚀 TwitchHub Pro (v4.0.0)

**TwitchHub Pro** ist eine leistungsstarke, modulare All-in-One-Desktop-Anwendung für Twitch-Streamer. Sie vereint Chatbot-Funktionalitäten, interaktive Chat-Minigames, ein integriertes Wirtschaftssystem, automatisierte OBS-Overlays sowie Dual-PC-Steuerung über OBS WebSocket v5 in einer modernen CustomTkinter-Oberfläche.

##Entwickelt von **FreeSchok Studio**.

---
## ✨ Hauptfunktionen

### 🎰 Interaktive Chat-Minigames
* **5x3 Mega Slot Studio (`!megaslot`)**:
  * 20 feste Gewinnlinien, konfigurierbare Einsätze und dynamic Multi-Spin (z. B. `!megaslot 10 5`).
  * 3 auswählbare Visual Themes: **Ägyptischer Tempel**, **Neon Cyber** und **Klassisches Vegas**.
  * Eigenes animiertes OBS-Overlay für maximale Immersion im Stream.
* **Klassische Slot Machine (`!slot`)**:
  * Retro 3-Walzen-Slot mit anpassbaren Symbolen, Gewinngewichtungen, Multiplikatoren und Jackpot-Pool.
* **Tresor Knacken (`!safe`)**:
  * Zuschauer versuchen, einen Zahlencode zu erraten, um den Tresor-Jackpot zu knacken.
* **Lurk-Befehl (`!lurk`)**:
  * Meldet Zuschauer im Chat ab und begrüßt sie automatisch bei ihrer Rückkehr.

### 💰 Wirtschaftssystem & Punkte (Coins / Schokos)
* **SQLite-Datenbank**: Sichere und performante Speicherung von Nutzer-Guthaben, Check-in-Streaks, XP und Statistiken.
* **Belohnungssystem**:
  * **Daily Check-in (`!checkin`)**: Täglicher Bonus mit Streak-Multiplikator.
  * **Event-Rewards**: Automatische Punktevergabe bei Raids, Follows, Bits, Subscriptions und Sub-Gifts.
  * **Passives Einkommen**: Automatische Coin-Belohnung für aktive Zuschauer in einstellbaren Zeitintervallen.
* **🏆 Leaderboard-Overlay**:
  * Modernes OBS-Overlay zur Live-Anzeige der Top-Zuschauer (Ränge, Check-in-Streaks, Coins).

### 🎥 OBS Studio Integration & Dual-PC Support
* **OBS WebSocket v5**: Direkte, latenzfreie Verbindung zu OBS Studio (unterstützt auch Dual-PC-Stream-Setups).
* **Automatisierte Szenen & Quellen**: Automatische Steuerung von Szenenwechseln, Filter-Effekten und Overlay-Einblendungen bei Events.

### 🛡️ Raid-Greeter Studio & Anti-Leak-Schutz
* **Raid-Begrüßung**: Automatische Chat-Begrüßung inkl. Raid-Alert OBS-Overlay und optionalen Coin-Geschenken für den Raider.
* **🔒 Anti-Leak Protection**: Automatische Bereinigung (`sanitize_safe_chat_template`), um versehentliche Leaks von Tresor-Codes oder sensiblen Daten im Chat zu verhindern.

### ⚙️ Automation & Anpassung
* **Timed Commands**: Zeitgesteuerte Intervall-Nachrichten für Social-Media-Links, Regelerinnerungen etc.
* **Custom Commands**: Erstellung eigener Chat-Befehle direkt über die GUI.
* **RGB Color Sliders**: Stufenlose Farbanpassung der UI-Elemente und Overlays.
* **🌐 Multi-Sprachunterstützung (i18n)**: Vollständige Unterstützung für **Deutsch (DE)** und **Englisch (EN)**.
* **💬 Discord Webhook Integration**: Automatische Benachrichtigungen für Giveaways und integriertes Feedback-/Bug-Reporting.
* **🔄 Auto-Updater**: Automatische Benachrichtigung bei neuen Versionen.
