# Gedit Theme erstellen

Der Standard Texteditor [Gedit](https://wiki.gnome.org/Apps/Gedit) der Desktopumgebung Gnome benutzt die Bibliothek [GtkSourceView](https://wiki.gnome.org/Projects/GtkSourceView/). Diese unterstützt unter anderem Syntaxhervorhebung und eine Möglichkeit das Aussehen (Theme) anzupassen.
Da ich beruflich wie auch Privat Visual Studio Code (VS Code, oder auch nur Code genannt) benutze und mir das dunkle Theme sehr gut gefällt, wollte ich das Aussehen von Gedit dementsprechend anpassen.


![](gedit_icon.png)

## Theme generieren
Ich bin auf einen [Theme Generator](http://scribes.sourceforge.net/themegenerator.php) gestossen, bei der man sich ein Theme mit seinene Farbvorstellungen generieren lassen kann.

Nach dem herunterladen des Themes kann es in Gedit geladen werden.

![](theme_load.png)

## Theme anpassen
Wenn man wie ich, noch Feinheiten anpassen möchte, kann man das direkt in der `*.xml` Datei machen. Das geladene Theme liegt im Pfad `~/.local/share/gedit/styles`. Nach dem anpassen und speichern muss Gedit neu gestartet werden damit die Änderungen sichtbar werden. Das heisst, am besten einen anderen Editor benutzen um die `*.xml` Datei zu bearbeiten.

## Ergebnis
Da VS Code noch mehr als nur Syntaxhervorhebung macht, sieht es nicht identisch aus, aber für mich reicht es.

VS Code mit `C++` Code:
![](vscode.png)

Gedit mit `C++` Code:
![](gedit.png)

Falls man mein Theme installieren will, geht das am einfachsten so:

* Downlaod ``