# git workflow

Format Listen/Aufzählungen: * oder 1,2,3...

```js
const x = 12;
```

## neues Repository anlegen

`mkdir <name of repo>`
`cd <name of repo>`

1. auf Github neues Repository anlegen 
2. im Ordner `git init`
3. `git add <filename>` für einzelne Datei oder `git add .` für alle Dateien im Ordner
4. `git commit` 
    * Eingabe Beschreibung was man verändert hat
    * Editorfenster speichern und schließen
5. `git remote add origin git@github.com:Benni-beep/<Name Repository auf Github>.git`
6. `git push -u origin master`

## Repository von Github auf Rechner
1. in Github auf "clone or download", Pfad kopieren
2. `git clone <kopierter Pfad>`

## Datei auf Rechner in Repository synchen
1. `git add <filename>` für einzelne Datei oder `git add .` für alle Dateien im Ordner
2. `git commit` 
    * Eingabe Beschreibung was man verändert hat
    * Editorfenster speichern und schließen
3. `git push`
