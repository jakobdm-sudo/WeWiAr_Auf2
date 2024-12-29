# LaTeX-Unterlagen

"In diesem Repository befinden sich die LaTeX-Unterlagen zum Modul."

## Inhalt

Der Inhalt entspricht dem Text der Aufgabe 2 des Moduls.

Es kann sinnvoll sein, sich die PDF zur Aufgabe 2 noch einmal anzusehen.

## PDF erstellen

Das geht ganz schnell und einfach:

1. Zuerst installieren wir LaTeX ([tug.org/texlive](https://tug.org/texlive/))
2. Dann nutzen wir PDFLaTeX zum Erstellen des PDFs:
   ```bash
   pdflatex ./task.tex

# **ACHTUNG!!**

LaTeX erstelle einige nervige Dateien (.aux, .log) diese muss man loeschen bevor
man einen Commit mit seinen Aenderungen macht!