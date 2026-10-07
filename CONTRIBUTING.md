# Mitmachen bei N.E.X.U.S.

*English summary below.*

Schön, dass du beitragen möchtest! Dieser Leitfaden gilt für alle Repositories der Organisation `nexus-united-species`, sofern ein Repository keine eigene `CONTRIBUTING.md` mitbringt.

## Wie du helfen kannst

- **Fehler melden:** Eröffne ein Issue im passenden Repository. Beschreibe, was du getan hast, was du erwartet hast und was stattdessen passiert ist. Gerät, Betriebssystem und App-Version helfen sehr.
- **Ideen vorschlagen:** Größere Ideen besprechen wir zuerst in den [Diskussionen](https://github.com/nexus-united-species/terminal/discussions) oder in der [Community](https://community.nexus-terminal.org/), bevor Code entsteht.
- **Code oder Dokumentation beitragen:** über Pull Requests (siehe unten).
- **Übersetzen, testen, erklären:** genauso wertvoll wie Code.

## Ablauf für Pull Requests

1. Forke das Repository und lege einen Branch mit sprechendem Namen an, z. B. `fix/kanal-loeschen` oder `feat/sprachsuche`.
2. Halte Änderungen klein und auf ein Thema fokussiert. Eine Sache pro Pull Request.
3. Füge Tests hinzu oder passe sie an, wenn sich Verhalten ändert.
4. Prüfe lokal, dass Analyse und Tests durchlaufen (die genauen Befehle stehen in der README des jeweiligen Repositories).
5. Schreibe Commit-Nachrichten im Format `typ: kurze beschreibung`, z. B. `fix: Kanalreaktion nutzt echte Event-ID`. Typen: `feat`, `fix`, `docs`, `test`, `refactor`, `chore`.
6. Beschreibe im Pull Request, *warum* die Änderung nötig ist und wie du sie getestet hast.

Ein Maintainer prüft jeden Pull Request. Rückfragen sind normal und kein Zeichen von Ablehnung.

## Grundregeln

- **Keine Geheimnisse committen** – keine Schlüssel, Passwörter, Seed-Phrasen oder `.env`-Dateien.
- **Datenschutz zuerst:** Keine echten personenbezogenen Daten in Tests, Logs oder Screenshots.
- **Sicherheitslücken nie öffentlich melden** – siehe [SECURITY.md](SECURITY.md).
- Es gilt unser [Verhaltenskodex](CODE_OF_CONDUCT.md).

## Lizenz deiner Beiträge

Mit einem Beitrag erklärst du dich einverstanden, dass er unter der Lizenz des jeweiligen Repositories veröffentlicht wird – in der Regel **AGPLv3** für Code und **CC BY-SA 4.0** für Texte.

---

## English summary

Contributions are welcome – code, documentation, translations, testing and ideas. Discuss larger changes first in [Discussions](https://github.com/nexus-united-species/terminal/discussions). For pull requests: fork, create a focused branch, add or update tests, use commit messages like `fix: short description`, and explain *why* in the PR. Never commit secrets or real personal data, and report security issues privately as described in [SECURITY.md](SECURITY.md). Contributions are licensed under the repository's license (usually AGPLv3 for code, CC BY-SA 4.0 for texts).
