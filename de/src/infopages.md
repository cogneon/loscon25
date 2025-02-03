# Infoseiten bearbeiten

Die Infoseiten der Veranstaltung werden in [diesem Github Repository](https://github.com/cogneon/loscon24) gepflegt. Die Quelle sind [Markdown](https://de.wikipedia.org/wiki/Markdown)-Dateien, die Webversion wird wie bei den Leitfäden von der [lernOS Produktionskette](https://github.com/cogneon/loscon24/blob/main/.github/workflows/lernos-produktionskette.yml) erzeugt. Als Theme verwenden wir [Read the Docs](https://www.mkdocs.org/user-guide/choosing-your-theme/). So können die Seiten geändert werden:

1. Repo mit Github Desktop klonen
1. Dateien ändern (z.B. mit Visual Studio Code)
1. Einzelne Änderungen einchecken (commit), sprechende Beschreibung ergänzen
1. Repo pushen
1. Nach ca. 1 Minute ist die neue Version der Infoseiten verfügbar

**Tipp:** mit lokal installiertem [mkdocs](https://www.mkdocs.org/) und [mkdocs-material](https://squidfunk.github.io/mkdocs-material/) kann man die Infoseiten über *mkdocs serve* auch lokal testen, bevor man das Repo pusht.