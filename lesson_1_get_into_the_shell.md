# VM mit Shell starten
vagrant up
vagrant ssh

# Ein paar Shell-Befehle
expr		kleiner Taschenrechner
echo		print-Befehl
history	 	genutzte Befehle

# Ein paar geläufige Shell-Befehle
ls                              Inhalt des Ordners anzeigen
unzip things.zip                Datei entpacken
cat     (concatenate files)     wird auch zum lesen von Files genutzt
wc      (wordcount)             Zeilen, Wörter, Bytes zur Analyse
diff                            Dateien vergleichen
rm      (remove)                Dateien löschen
sort                            Liste von Strings sortieren
bc                              Taschenrechner
less                            Dateien lesen



# Manuals
man <Befehl>

# Tastaturbefehle
Ctrl + C    Abbruch
Ctrl + D    Befehl abschließen

# Filesystem
Linux nutzt /, wie URL
Windows nutzt \

pwd     print working directory
cd      change directory (ohne Angabe eines Verzeichnisses führt direkt zum *home*)
~       home directory
.       actual directory
..      higher directory
mv      (move)                  Dateien verschieben
cp      (copy)                  Dateien kopieren
mkdir   (makedir)               Ordner erzeugen
rmdir   (removedir)             Ordner ohne Inhalt löschen
rm -r <dir>                     Ordner mit Inhalt löschen

# Globbing
*filename       Platzhalter für viele Zeichen
?filename       Platzhalter für ein Zeichen
??filename      Platzhalter für zwei Zeichen
f[aeiou]lename  Auswahl an Zeichen
*{jpg,JPG}      Linux ist case-sensitiv, hier Auswahl aller JPEGs (groß oder klein)
