# LaTeX-Tutorial

So, jetzt endlich zum LaTeX tutorial:

Hier bekommt man eine schöne Übersicht über LaTeX: https://www.overleaf.com/learn/latex/Learn_LaTeX_in_30_minutes

Der letzte Abschnitt ist besonders wichtig, meines erachtens sind LaTeX packages die größte Stärke von LaTeX.
Allgemein ist Overleaf ein gutes Wiki um LaTeX basics zu lernen.

Technisch funktioniert LaTeX so:

Man schreibt ein klartext Dokument, also im Prinzip so etwas wie eine .txt Datei nur mit der Endung .tex.
Das kann man mit jedem texteditor machen, man hat freie Wahl.

Dann lässt man einen sogenannten compiler darüberlaufen. Dieser liest die Klartext Datei ein und macht ein PDF daraus.

Diese PDF kannst Du dir dann ansehen, und entscheiden was Du daran ändern willst. Dann pflegst Du diese Änderung in Deine .tex Datei ein, lässt erneut den compiler darüberlaufen und schaust Dir das neue PDF an.

Wichtig ist hier, dass das Programm das Du zum Ansehen der PDF verwendest, es selbst merkt wenn sich die PDF ändert. Das tun z.B. Webbrowser(Firefox, Chrome, Edge) meist nicht.

Das heisst Du musst Dir im Prinzip 3 Programme aussuchen, die Du im Prinzip unabhängig voneineander wählen kannst:

1) Einen text editor zum schreiben der .tex Datei
2) Einen LaTeX compiler, der die .tex Datei in ein PDF umwandelt
3) Ein Programm zum ansehen der PDF, das es merkt wenn sich die PDF ändert. Ein sogenannter PDF viewer

In der Praxis bedeutet das Folgendes:

a) Du kannst den online Overleaf Editor nutzen: https://www.overleaf.com/
Vorteile:

1) Overleaf ist alles gleichzeitig: text Editor, Compiler, PDF viewer 
Nachteile:
1) Braucht Internet
2) Braucht einen Account
3) Ist langsam
4) Funktioniert nicht bei großen Dokumenten(meine Protokolle schafft es nicht)
5) Wenn man doch große Dokumente mit Overleaf erstellen will muss man dafür zahlen.

b1) Du verwendest bei dir lokal einen Text Editor, ich habe in dem Fall zwei Empfehlungen:
b1a) Vscode: https://code.visualstudio.com/#alt-downloads
Vorteile:
1. Ein guter Texteditor, wie gewohnt und leicht zu bedienen.
Nachteile:
1. Verhältnismässig langsam bei der verwendung (mit etwas Übung aber immernoch schneller als Word)

b1b) NeoVim: https://neovim.io/
Vorteile:
1. Unheimlich schnell: startet schnell, braucht wenig rescourcen, kann riesige Dateien schnell öffnen
2. Wenn man die Bedienung gelernt hat schreibt man mit NeoVim um den Faktor 2-4 mal schneller als mit z.B. VSCode
3. Praktisch unendlich viele einstellungsmöglichkeiten
Nachteile:
1. Sehr schwer zu lernen
2. Sehr schwer einzustellen, bzw. zu lernen wie man NeoVim einstellt.

b2) In diesem Fall brauchst Du auch einen lokalen LaTeX compiler, hier gibt es zwar mehrere Möglichkeiten, aber eine ist in jeder hinsicht besser als die Anderen und läuft auf jedem Betriebssystem:

TeX Live: https://tug.org/texlive/

b3) Ein Programm zum ansehen der produzierten PDF Datei, ein sogenannter PDF viewer.

Hier ist es betriebssystem abhängig was am besten funktioniert, meine Empfehlung ist wie folgt:
Windows:
1. Sumatra PDF: https://www.sumatrapdfreader.org/free-pdf-reader
Linux/BSD/Mac:
1. Zathura: https://pwmt.org/projects/zathura/

Nun zurück zu LaTeX. Am besten Du arbeitest alles bisher geschickte ab bevor Du dich an diesen Teil machst.
Einige allgemeine Tipps:
1. Du kannst bezüglich LaTeX alles direkt googeln, selbst spezifische Dinge wie "How to plot .csv data in latex"
2. Bei den Ergebnissen sind besonders die Erklärungen auf Overleaf(https://www.overleaf.com/learn), die Ergebnisse von TeX stackexchange (https://tex.stackexchange.com/), von stackoverflow(https://stackoverflow.com/) und LaTeX Community(https://latex.org/forum/index.php) gut.
3. TeX Live enthält direkt alle sogenannten Packages, das sind Erweiterungen die andere Nutzer geschrieben haben. Diese Packages machen es deutlich einfacher Dokumente zu erstellen.
4. Auf CTAN(https://ctan.org/?lang=en) findest Du alle seriösen Packages die Du jemals brauchen wirst. Aber, wie gesagt, mit TexLive sind alle bereits installiert.
5. Auf CTAN findest Du aber Erklärungen was Du mit einem Package machen kannst.
