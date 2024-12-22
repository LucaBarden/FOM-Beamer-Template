# FOM Presentation Latex Template

Geupdatete und Refactored Version von https://github.com/Flipez/latex-fom-presentation FOM Template

## Benutzung

Beim Manuellen kompilieren muss mehrmals kompiliert werden aufgrund von bibtex

```
pdflatex main.tex
bibtex main
pdflatex main.tex
pdflatex main.tex
```

## Zitierstyle

Die Zitiereinstellungen sind in der Datei [`skripte/bibtex-config.tex`](./skripte/bibtex-config.tex) hinterlegt.

Der Zitierstil ist an IEEE angepasst und entspricht dem offiziellen IEEE Styleguide.

## Metadaten

Die Metadaten lassen sich in [`skripte/meta.tex`](./skripte/meta.tex) anpassen. Dort sind Titel, Autor und Hochschule hinterlegt.


## Textinhalte

Die Kapitelstruktur befindet sich in [`kapitel.tex`](.kapitel.tex) und lässt sich nach belieben anpassen. 
Die Struktur ist aktuell so angepasst, dass inhaltliche Slides in [`slides/inhalt.tex`](./slides/inhalt.tex) zu finden sind.