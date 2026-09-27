# N-Code

**N-Code** ist eine Windows-Desktop-IDE für **FiveM** / **Lua** (Editor, Projekt-Tools, Referenzen u. a.).

> **Download:** Installer nur über **[Releases](https://github.com/Nils2006-dev/N-Code/releases)** – nicht von fremden Links oder Discord-DMs.

---

## Installation

1. Öffne **[Releases → Latest](https://github.com/Nils2006-dev/N-Code/releases/latest)**.
2. Lade **`N-Code-Setup-x.y.z.exe`** herunter.
3. Setup starten und den Anweisungen folgen.
4. Danach **N-Code-Loader** vom Desktop/Startmenü verwenden (prüft Updates und startet die App).

---

## Windows warnt: „Unbekannter Herausgeber“ / SmartScreen

Beim ersten Start kann **Windows Defender SmartScreen** melden, dass die App blockiert wurde oder der **Herausgeber unbekannt** ist.

**Das bedeutet nicht, dass N-Code ein Virus ist.**

| Was Windows meint | Was es *nicht* bedeutet |
|-------------------|-------------------------|
| Die `.exe` ist **nicht digital signiert** | Kein automatischer „Virus“-Befund |
| Microsoft kennt diesen Herausgeber noch nicht | Die Datei muss nicht „schädlich“ sein |

### Warum ist N-Code nicht signiert?

Für Windows-Programme braucht man ein **Code-Signing-Zertifikat** (Authenticode). Das kostet typischerweise **mehrere hundert Euro pro Jahr** und lohnt sich für mich als **kleines, privates Projekt** derzeit **nicht**. Deshalb erscheint **„Unbekannter Herausgeber“** – das ist bei vielen Indie-Tools normal.

Wenn das Projekt wächst, kann ich später optional ein Zertifikat nutzen; bis dahin gibt es **nur offizielle Builds auf GitHub**.

### So installierst du trotzdem sicher

1. Datei **nur** von **[diesem GitHub-Repo → Releases](https://github.com/Nils2006-dev/N-Code/releases)** laden.
2. Im blauen SmartScreen-Fenster auf **„Weitere Informationen“** klicken (falls sichtbar).
3. **„Trotzdem ausführen“** wählen.

Prüfe optional die **Dateigröße** und den **Release-Text** auf GitHub – Version und Setup-Name sollten zusammenpassen (`N-Code-Setup-x.y.z.exe`).

---

## Updates

- **N-Code-Loader** starten → holt bei Bedarf ein neues Setup von GitHub, **oder**
- In der App: Hinweis **„Update verfügbar“** → **Aktualisieren**.

Updates kommen immer über **dieselbe Releases-Seite** (kein separates Update-Portal).

---

## Support / Fragen

Issues auf GitHub oder über die Kanäle, in denen du N-Code kennengelernt hast.

---

## Hinweis für Entwickler

Quellcode dieses Repos kann minimal gehalten sein (z. B. nur README + Releases). Die **Installationsdateien** liegen ausschließlich unter **Releases**.

---

*Unabhängiges Hobby-/Community-Projekt – kein Microsoft-, Rockstar- oder Cfx-offizielles Produkt.*
