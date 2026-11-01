# Calc Studio – Downloads

Fertige Pakete stehen unter [Releases](https://github.com/Darkice519/Calc-Studio-Downloads/releases). Kein GitHub-Konto erforderlich. Dieses Repository enthält keinen Quellcode.

## Installation

- **Windows:** `Windows-Setup.exe` installieren oder `Windows-Portable.exe` starten. Die Pakete sind nicht signiert; Windows SmartScreen kann eine Warnung anzeigen. Herkunft und SHA256-Prüfsumme vor dem Start kontrollieren.
- **Linux:** AppImage herunterladen, ausführbar machen (`chmod +x Calc-Studio-*.AppImage`) und starten. Ohne FUSE: `./Calc-Studio-*.AppImage --appimage-extract-and-run`.
- **Browser:** [Calc Studio öffnen](https://calc-studio-261101.jetepoch2.chatgpt.site).

**Automatische Updates gibt es nicht.** Neue Versionen findest du unter Releases. Exportiere vorher eine JSON-Sicherung und beende die App. Setup über die bestehende Installation installieren; AppImage oder portable EXE ersetzen. Mappen liegen im Benutzerprofil, nicht in der Programmdatei. Die portable EXE allein nimmt keine Daten auf einen anderen PC mit.

Pläne liegen lokal auf dem Gerät. Optional verbindet ein verschlüsselter Sync-Link genau eine Mappe mit anderen Geräten. Wer diesen Link hat, kann sie lesen und ändern; den Link sicher aufbewahren. Ohne Link oder Sicherung sind lokale Daten nach Profil- oder Geräteverlust nicht wiederherstellbar. Für neue Sync-Links ist ein Einladungscode des Betreibers nötig.

## Lizenzhinweise

Calc Studio ist ein unabhängiges Projekt unter MIT, siehe [LICENSE](LICENSE). SheetJS Community Edition steht unter Apache-2.0; Electron und enthaltene Laufzeitkomponenten haben eigene Lizenzen. Vollständige Hinweise liegen in den Paketen, insbesondere `THIRD_PARTY_NOTICES.md`, `ui/vendor/SHEETJS-LICENSE.txt`, `LICENSE.electron.txt` und `LICENSES.chromium.html`. Microsoft und Excel werden nur beschreibend zur Dateikompatibilität genannt. Keine Verbindung zu Microsoft, keine vollständige Excel-Kompatibilität. Ohne Gewähr.

