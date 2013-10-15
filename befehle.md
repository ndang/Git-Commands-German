# Befehle

**Wichtig: Nach dem Hinzufügen von Dateien und Ordnern und nach dem Entfernen von Dateien und Ordnern immer `git commit -m 'MESSAGE'` ausführen!!**

Konfigurationen ändern:

`git config --global user.name "USERNAME"` *Username setzten (muss mit GitHub übereinstimmen!)*

`git config --global user.email "E-MAIL@ADRESSE.TLD"` *E-Mail Adresse setzten (muss mit GitHub übereinstimmen!)*

Neue Repository erstellen:

`mkdir ~/NAME_DER_REPOSITORY` *Legt das Verzeichnis an*

`cd ~/NAME_DER_REPOSITORY` *Repository auswählen um damit zu arbeiten*

`touch README.md` *Erstellt die README Datei*

`git init` *Initialisiert das Verzeichnis und erstellt das Verzeichnis /.git*

`git add README.md` *Fügt die README Datei der Repository hinzu*

`git commit -m 'NACHRICHT_DES_COMMIT'` *Den Dateien des letzten add-Befehls einen commit hinzufügen*

Repository auswählen um damit zu arbeiten:

`cd ~/NAME_DER_REPOSITORY`

Dateien und Ordner hinzufügen:

`git add .` *Fügt alle Ordner + Dateien in dem Repo-Ordner der Repo hinzu*

`git commit -m 'NACHRICHT_DES_COMMIT'` *Den Dateien des letzten add-Befehls einen commit hinzufügen*

Verbindung zur Repository auf GitHub herstellen:

`git remote add origin https://github.com/USERNAME/NAME_DER_REPOSITORY.git` *Anstatt der https-Methode: git@github.com:USERNAME/NAME_DER_REPOSITORY.git*

Repository aktualisieren/hochladen:

`git push -u origin master` *master ist der Branch! - Im Anschluss erfolgt eine Authentifizierung*

Dateien, Ordner und/oder Repository löschen:

`git rm --cached PATH/TO/FILE.txt` *Löscht die Datei aus der Repository*

`git rm PATH/TO/FILE.txt` *Löscht die Datei aus dem Lokalen Datei System*

`git rm -r PATH/TO/DIRECTORY` *Löscht einen Ordner aus der Repository*

`rm -rf PATH/TO/DIRECTORY` *Löscht einen Ordner aus dem Lokalen Datei System*

`rm -rf .git` *Löscht die Repository (im Anschluss den Ordner der Repo löschen!)*
