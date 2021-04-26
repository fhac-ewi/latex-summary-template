# LaTeX Template für Zusammenfassungen
Dieses einfache LaTeX Template ermöglicht es schnell und einfach Zusammenfassungen von z.B. Modulen zu erstellen. Das Repository ist so eingestellt, dass automatisch aus dem Branch `main` eine PDF generiert wird.

Das aktuellste PDF findest du [hier](./releases/latest).

## How to use

### Vorbereitung
1. Erstelle dein eigenes Repository und nutze dieses als Template.
2. Trage in der Datei [master.tex](./master.tex) Semester und Modulnamen ein.
3. Schreibe die Zusammenfassung in die Datei [Zusammenfassung.tex](./Zusammenfassung.tex).

### Online editieren
Du kannst theoretisch alles Online bei GitHub bearbeiten. Öffne dazu die jeweilige Datei und drücke auf den Button `edit`. 

Nachteil: Online wird leider keine Vervollständigung von LaTeX angeboten.

### Lokal editieren
#### Vorbereitung - Editor
Ich empfehle LaTeX mit [Visual Studio Code](https://code.visualstudio.com/) zu editieren. Du kannst aber auch jeden anderen Editor nutzen.

Folgende Erweiterungen empfehle ich:
- [LaTeX Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop)
- [Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker)
- [German - Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker-german) 

#### Vorbereitung - Repository herunterladen
1. Installiere dir Git für dein Betriebssystem.
2. Öffne die Git Bash und clone das Repository: `git clone https://<your-url>`

#### Änderungen hochladen
0. (Falls mehrere Benutzer an dem Repository arbeiten, müssen ggf. die Änderungen der Anderen zuvor runtergeladen werden: `git pull --rebase`)
1. Öffne die Git Bash in dem Ordner der `master.tex` und merke deine Änderungen vor: `git add .`
2. Erstelle ein Commit: `git commit -m <message>`
3. Lade die Änderungen hoch: `git push`

## Beispiele
Im Folgenden enthält einige LaTeX Beispiele.

TODO

## Wieso GitHub?
GitHub bietet viele Vorteile, die besonders bei Gruppenarbeiten interessant sind:
- Versionsverlauf
- Gleichzeitiges Bearbeiten möglich
- Automatisches Erstellen der PDF

Anders als andere Online Tools ist dies völlig kostenlos... und funktioniert. :^)