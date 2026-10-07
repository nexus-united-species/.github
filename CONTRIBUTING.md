# Mitmachen bei N.E.X.U.S. / Contributing to N.E.X.U.S.

[🇩🇪 Deutsch](#-deutsch) | [🇬🇧 English](#-english)

---

## 🇩🇪 Deutsch

Schön, dass du beitragen möchtest! Dieser Leitfaden gilt für alle Repositories der Organisation `nexus-united-species`, sofern ein Repository keine eigene `CONTRIBUTING.md` mitbringt. Beiträge sind auf Deutsch und Englisch gleichermaßen willkommen.

### Wie du helfen kannst

- **Fehler melden:** Eröffne ein Issue im passenden Repository. Beschreibe, was du getan hast, was du erwartet hast und was stattdessen passiert ist. Gerät, Betriebssystem und App-Version helfen sehr.
- **Ideen vorschlagen:** Größere Ideen besprechen wir zuerst in den [Diskussionen](https://github.com/nexus-united-species/terminal/discussions) oder in der [Community](https://community.nexus-terminal.org/), bevor Code entsteht.
- **Code oder Dokumentation beitragen:** über Pull Requests (siehe unten).
- **Übersetzen, testen, erklären:** genauso wertvoll wie Code.

### Ablauf für Pull Requests

1. Forke das Repository und lege einen Branch mit sprechendem Namen an, z. B. `fix/kanal-loeschen` oder `feat/sprachsuche`.
2. Halte Änderungen klein und auf ein Thema fokussiert – eine Sache pro Pull Request.
3. Füge Tests hinzu oder passe sie an, wenn sich Verhalten ändert.
4. Prüfe lokal, dass Analyse und Tests durchlaufen (die genauen Befehle stehen in der README des jeweiligen Repositories).
5. Schreibe Commit-Nachrichten im Format `typ: kurze beschreibung`, z. B. `fix: Kanalreaktion nutzt echte Event-ID`. Typen: `feat`, `fix`, `docs`, `test`, `refactor`, `chore`.
6. Beschreibe im Pull Request, *warum* die Änderung nötig ist und wie du sie getestet hast.

Ein Maintainer prüft jeden Pull Request. Rückfragen sind normal und kein Zeichen von Ablehnung.

### Grundregeln

- **Keine Geheimnisse committen** – keine Schlüssel, Passwörter, Seed-Phrasen oder `.env`-Dateien.
- **Datenschutz zuerst:** keine echten personenbezogenen Daten in Tests, Logs oder Screenshots.
- **Sicherheitslücken nie öffentlich melden** – siehe [SECURITY.md](SECURITY.md).
- Es gilt unser [Verhaltenskodex](CODE_OF_CONDUCT.md).

### Lizenz deiner Beiträge

Mit einem Beitrag erklärst du dich einverstanden, dass er unter der Lizenz des jeweiligen Repositories veröffentlicht wird – in der Regel **AGPLv3** für Code und **CC BY-SA 4.0** für Texte.

---

## 🇬🇧 English

Great that you want to contribute! This guide applies to all repositories of the `nexus-united-species` organization unless a repository ships its own `CONTRIBUTING.md`. Contributions in English and German are equally welcome.

### How you can help

- **Report bugs:** Open an issue in the relevant repository. Describe what you did, what you expected and what happened instead. Device, operating system and app version help a lot.
- **Suggest ideas:** We discuss larger ideas first in [Discussions](https://github.com/nexus-united-species/terminal/discussions) or in the [community](https://community.nexus-terminal.org/) before any code is written.
- **Contribute code or documentation:** via pull requests (see below).
- **Translate, test, explain:** just as valuable as code.

### Pull request workflow

1. Fork the repository and create a branch with a descriptive name, e.g. `fix/channel-delete` or `feat/voice-search`.
2. Keep changes small and focused on one topic – one thing per pull request.
3. Add or update tests when behavior changes.
4. Make sure analysis and tests pass locally (the exact commands are in each repository's README).
5. Write commit messages in the format `type: short description`, e.g. `fix: channel reaction uses real event ID`. Types: `feat`, `fix`, `docs`, `test`, `refactor`, `chore`.
6. Explain in the pull request *why* the change is needed and how you tested it.

A maintainer reviews every pull request. Follow-up questions are normal and not a sign of rejection.

### Ground rules

- **Never commit secrets** – no keys, passwords, seed phrases or `.env` files.
- **Privacy first:** no real personal data in tests, logs or screenshots.
- **Never report security issues publicly** – see [SECURITY.md](SECURITY.md).
- Our [Code of Conduct](CODE_OF_CONDUCT.md) applies.

### License of your contributions

By contributing, you agree that your contribution is published under the license of the respective repository – usually **AGPLv3** for code and **CC BY-SA 4.0** for texts.
