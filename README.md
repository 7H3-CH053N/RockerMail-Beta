# RockerMail Beta

Hier sammeln wir Fehlermeldungen, Wünsche und Fragen der Beta-Tester von RockerMail. Der Quellcode liegt nicht in diesem Repository, und die Testversion gibt es hier nicht zum Herunterladen.

RockerMail ist eine native Mac-App für Mail, Kalender, Kontakte und Aufgaben in einem Fenster. Sie verbindet Microsoft 365, Gmail, iCloud und andere IMAP-Konten direkt mit dem Anbieter, ohne eigenen Server dazwischen. Die KI schlägt Entwürfe und Aufräumaktionen vor. Gesendet, verschoben oder gelöscht wird erst nach deinem Klick.

Mehr zur App: [rockermail.app](https://rockermail.app)

## Voraussetzungen

- macOS 26 oder neuer
- ein Mac mit Apple-Chip (M1 oder neuer). Die App läuft auch auf Intel, dort ist sie aber nicht getestet.
- für die lokale KI mit Ollama: rund 4 GB freier Speicher für das Modell
- für das Apple-Modell: ein Mac mit eingeschalteter Apple Intelligence
- für Claude: ein eigener Claude-Zugang mit installierter Claude-CLI

## Beta-Tester werden

Trag dich auf [rockermail.app](https://rockermail.app/#beta) ein. Wir laden in kleinen Gruppen ein, in der Reihenfolge der Anmeldungen. Mit der Einladung bekommst du die Testversion als DMG und einen Beta-Schlüssel.

## Installieren

1. DMG öffnen und RockerMail in den Ordner „Programme“ ziehen.
2. RockerMail starten. Die Testversion ist mit Developer ID signiert, aber noch nicht von Apple notarisiert. macOS blockiert deshalb den ersten Start.
3. Systemeinstellungen → Datenschutz & Sicherheit öffnen, nach unten scrollen und bei RockerMail auf „Trotzdem öffnen“ klicken.
4. Im Freischalt-Fenster die Mailadresse eingeben, an die die Einladung ging, und den Beta-Schlüssel einfügen. Der Schlüssel funktioniert nur mit genau dieser Adresse.

Ein Beta-Schlüssel gilt 30 Tage. In den letzten 7 Tagen weist die App darauf hin. Danach sperrt sie, deine Daten bleiben erhalten.

## Fehler melden

[Neue Fehlermeldung anlegen](https://github.com/7H3-CH053N/RockerMail-Beta/issues/new?template=fehler.yml)

Schau vorher kurz in die [offenen Meldungen](https://github.com/7H3-CH053N/RockerMail-Beta/issues), ob es den Fehler schon gibt. Wenn ja, ergänze dort, was bei dir anders ist.

Das hilft uns am meisten:

- die Version von RockerMail (RockerMail → Über RockerMail) und von macOS ( → Über diesen Mac)
- welche Konten betroffen sind, zum Beispiel Microsoft 365 oder Gmail
- die Schritte, mit denen der Fehler wieder auftritt
- was du erwartet hast und was stattdessen passiert ist

**Dieses Repository ist öffentlich.** Alles, was du hier schreibst oder hochlädst, kann jeder lesen. Bitte keine echten Mails, Mailadressen, Namen, Termine, Passwörter oder Schlüssel. Schwärze Screenshots vorher oder nimm eine Testmail. Falls doch etwas Privates hineinrutscht, schreib uns, dann löschen wir es.

Kein GitHub-Konto? Schick die Meldung per Mail an [aj@medienwerk.cc](mailto:aj@medienwerk.cc?subject=RockerMail%20Beta), wir übertragen sie.

## Wünsche und Fragen

- [Wunsch einreichen](https://github.com/7H3-CH053N/RockerMail-Beta/issues/new?template=wunsch.yml)
- [Frage stellen](https://github.com/7H3-CH053N/RockerMail-Beta/issues/new?template=frage.yml)

## Sicherheitslücken

Bitte nicht als öffentliches Issue melden. Wie es vertraulich geht, steht in [SECURITY.md](SECURITY.md).

## Bekannte Einschränkungen dieser Beta

- Die App ist noch nicht von Apple notarisiert.
- Mails lassen sich noch nicht per Ziehen und Ablegen in Ordner verschieben. Verschieben geht über das Kontextmenü, die Symbolleiste und die Menüleiste.
- Auf Intel-Macs nicht getestet. Dort gibt es kein Apple-Modell, und Ollama läuft ohne Grafikbeschleunigung.
- Fehler lassen sich noch nicht direkt aus der App melden. Das kommt mit der nächsten Beta.

## Herausgeber

medienwerk KG, [Impressum](https://rockermail.app/impressum.html), [Datenschutz](https://rockermail.app/datenschutz.html)
