# Git Commands


**git —version**: Es zeigt die Installierte Version an.

**git init**: Es initialisiert das git in den ausgewählten Ordner.

**git config user.name "*Benutzername*“**: Es setzt den Benutzernamen des Repos fest.

**git config user.email "*E-Mail*"**: Es setzt die E-mail des Repos fest.

**git status**: Es zeigt den Status des Repos an.

**git status —short**: Es macht das gleiche wie oben einfach kompakt	(?? = untracked files, A = Files added to stage, M = Modified files, D = Deleted files).

**git add "file"**: Es bereitet ein file darauf vor commited zu werden.

**git add —all (-A = Abkürzung)**: Es bereitet alle files darauf vor commited zu werden.

**git commit -m**: Es speichert alles was du geadded hast (-m steht für eine kleine Nachricht die man dazu schreibt).

**git commit —amend -m**: Es ändert den namen des letzten commits.

**git log**: Es zeigt den log an.

**git log —oneline**: Es zeigt den log an aber alles ist eine Linie gross.

**git commit help**: Es zeigt Hilfe für spezifische commands an.

**git help —all**: Es zeigt Hilfe für alle commands an.

**git branch "Name"**: Es erstellt einen neuen "Branch".

**git branch**: Es zeigt alle Branches auf dem Terminal an und markiert den Branch auf dem man sich befindet mit *.

**Git Branch -a**: Es zeigt alle Branches auf dem Terminal und auf GitHub an und markiert den Branch auf dem man sich befindet mit *.

**git checkout "Name"**: Es wechselt zu dem Branch der in "Name" steht.

**ls**: Es zeigt alle Dokumente an.

**git checkout -b emergency-fix**: Es erstellt einen Branch z. B wenn mann auf Branch1 etwas fertig machen muss aber Branch2 noch nicht fertig ist.

**git merge "branch"**: Man kombiniert den Branch auf dem man sich befindet mit dem dem Branch den man auswählt.

**git branch -d "branch"**: Der Ausgewählte Branch wird gelöscht.

**git remote add origin "Link"**: Es ladet das im GitHub erstellte repo ins Terminal.

**git remote -v**:	Es zeigt die 

**git push —set-upstrean origin master**: Es ladet Dateien vom Terminal ins GitHub.

**git fetch origin**: Es zeigt alle Veränderungen an.

**git diff "Branch"**: Es zeigt die unterschiede zwischen den Branches.

**git pull origin**: Es zieht alle Veränderungen vom einem Branch zum anderen.

**git clone "Link"**: Es ladet das repo auf das Terminal das man kopiert hat.

**git remote rename "*alter name*" "*neuer name*"**: Es benennt ein remote um.

**git .gitignore**: Es erstellt ein Dokument indem man verschiedene Commands reinschreiben kann (siehe link https://www.w3schools.com/git/git_ignore.asp?remote=github).

**ssh-keygen -t rsa -b 4096 -C "E-mail"**: Es generiert einen SSH-Schlüsse und sendet in an deine Email.

**ssh-add /Users/"Benutzername"/.ssh/id_rsa**: Jetzt kann man den SSH-Schlüssel verwenden.

**ssh -T git@github.com**: Du kannst deine Verbindung testen ob der SSH-Schlüssel funktioniert hat.

**git revert HEAD —no-edit**: Es bereitet den letzten commit vor rückgängig gemacht zu werden.

**git reset "commit Nummer"**: Es resetet das repo auf den gewünschten Commit zurück.

