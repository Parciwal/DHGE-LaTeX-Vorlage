# DHGE Latex Vorlage

## Allgemeines

- [DHGE Vorgaben](https://www.dhge.de/DHGE/dam/jcr:6e5d8217-0965-42fe-8982-c7515c12f0b9/Hinweise_und_Empfehlungen_schr_Arb_Technik_Gera_2023.pdf)
- [VSCode Integration](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop)
- [Rechtschreibung (VSCode)](https://marketplace.visualstudio.com/items?itemName=ltex-plus.vscode-ltex-plus)
- [Gruvbox Colortheme](https://marketplace.visualstudio.com/items?itemName=jdinhlife.gruvbox)

## Latex Installation

* [MacOS](https://www.tug.org/mactex/)
* [Linux](https://wiki.debian.org/Latex)
* [Windows](https://miktex.org/)

## Latex Dokumentation

* [Latex](https://www.latex-project.org/help/documentation/)


## Ausführung

Beim kompilieren der `.tex` Datei muss ggf. mehrfach kompiliert werden.
Daher sollte ein build tool verwendet werden ([latexmk](https://ctan.org/pkg/latexmk/))

```
latexmk -pdf DATEINAME.tex
```
> [!NOTE]
> In VSCode mit [VSCode Latex Integration](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop) passiert das automatisch

## Erste Schritte und Tipps fürs Arbeiten

1. Vorlage kompilieren, die erzeigte PDF ist zugleich auch die Bedienungsanleitung für die Vorlage
2. Alle Platzhalter in Deckblatt, Sperrvermerk und ehrenwörtlicher Erklärung sollten frühzeitig entfernt werden (sonst wird es schnell peinlich), für den Titel gibt es eine Sektion, der wird dann an allen nötigen Stellen automatisch eingesetzt oder ersetzt.
3. Aktuell werden nur `Normen`, `Bücher` und `Onlinequellen` korrekt im Dokument und im Quellenverzeichnis formatiert.

Viel Spaß beim schreiben 🚀

## Weitere nützliche Links

[Alte Latex Vorlage (deprecated)](https://github.com/RvNovae/dhge-latex/issues)
[Prof. Bariè Anforderungen](https://github.com/DanielBarie/HinweiseAnfertigungArbeiten)
[Prof. Kusche Anforderungen](https://www.computerix.info/)

## Quellenformatierung mit biblatex

Diese Vorlage ist auf biblatex ausgelegt. Mit Citavi kann man die Liste passend ausgeben. Um Online Reccourcen richtig angeben zu können, müssen sie im in der .bib datei als "@online" gekennzeichnet sein. Bei Citavi kann man dias im Exportfilter einstellen. Dort ist bei "Internetdokument" "online" einzustellen. Falls es nicht in der Liste ist, ist es mölich das händich einzugeben.

## Copyright

?
