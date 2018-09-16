# VM mit Shell starten
1. vagrant up
2. vagrant ssh

# Ein paar Shell-Befehle
| Code    | Erklärung              |
| ------- | ---------------------- |
| expr    | kleiner Taschenrechner |
| echo    | print-Befehl           |
| history | genutzte Befehle       |

# Ein paar geläufige Shell-Befehle
| Code                        | Erklärung                             |
| --------------------------- | ------------------------------------- |
| ls                          | Inhalt des Ordners anzeigen           |
| unzip things.zip            | Datei entpacken                       |
| cat     (concatenate files) | wird auch zum lesen von Files genutzt |
| wc      (wordcount)         | Zeilen, Wörter, Bytes zur Analyse     |
| diff                        | Dateien vergleichen                   |
| rm      (remove)            | Dateien löschen                       |
| sort                        | Liste von Strings sortieren           |
| bc                          | Taschenrechner                        |
| less                        | Dateien lesen                         |

# Manuals
man <Befehl>

# Tastaturbefehle
| Tastaturbefehl | Erklärung          |
| -------------- | ------------------ |
| Ctrl + C       | Abbruch            |
| Ctrl + D       | Befehl abschließen |

# Filesystem
Hinweis: Linux nutzt /, wie URL, im Gegensatz dazu nutzt Windows \

| Code                | Erklärung                                                    |
| ------------------- | ------------------------------------------------------------ |
| pwd                 | print working directory                                      |
| cd                  | change directory (ohne Angabe eines Verzeichnisses führt direkt zum *home*) |
| ~                   | home directory                                               |
| .                   | actual directory                                             |
| ..                  | higher directory                                             |
| mv      (move)      | Dateien verschieben                                          |
| cp      (copy)      | Dateien kopieren                                             |
| mkdir   (makedir)   | Ordner erzeugen                                              |
| rmdir   (removedir) | Ordner ohne Inhalt löschen                                   |
| rm -r <dir>         | Ordner mit Inhalt löschen                                    |
| rm -rf .git         | Git-Repository in Ordner löschen                             |

# Globbing
| Code           | Erklärung                                                    |
| -------------- | ------------------------------------------------------------ |
| *filename      | Platzhalter für viele Zeichen                                |
| ?filename      | Platzhalter für ein Zeichen                                  |
| ??filename     | Platzhalter für zwei Zeichen                                 |
| f[aeiou]lename | Auswahl an Zeichen                                           |
| *{jpg,JPG}     | Linux ist case-sensitiv, hier Auswahl aller JPEGs (groß oder klein) |


