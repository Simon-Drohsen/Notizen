<h1>Command Line</h1>

<h2>Ein Datensystem organisiert Alle Dateien auf dem Computer in einer Baumstruktur:</h2>

* Der erste Ordner ist der Parent Ordner von allen Ordnern.

* Jeder Parent Ordner kan viele Child Ordner oder Dateien haben.

* Mit Command Line kann man direkt mit dem Computer kommunizieren (auf Mac Terminal).

<h2>Man kann mit Command Line durch alle Ordner schauen</h2>

* Die funktion von pwd ist dir zu sagen in welchem Ordner du bist.

* Die funktion von ls ist aufzulisten was alles in deinem Ordner ist.

* Die funktion von cd rtansportiert dich in dden Ordner den du angibst.

* Die funktion von mkdir macht einen neuen Ordner.

* Die funktion von touch macht auch einen neuen Ordner.

<h2>Man kann Helper Commands brauchen um sich das navigieren einfacher zu machen:</h2>

* clear "reinigt" das Terminal.

* tab beendet automatisch das Wort.

* ↑ und ↓ erlauben dir zwischen deinen geschriebenen Commands zu switchen.

<h2>Options modifizieren normale Commands:</h2>

* Die funktion von ls -a ist aufzulisten was alles in deinem Ordner ist, inklusive versteckte Ordner und Dateien.

* Die funktion von ls -l ist aufzulisten was alles in deinem Ordner ist, aber in einem langen Format.

* Die funktion von ls -t ist aufzulisten was alles in deinem Ordner ist und es mit dem letzten Bearbeitungsdatum zu sortieren.

* Mehrere Optionen können kombiniert werden wie zum Beispiel ls -alt. 

<h2>From the command line, you can also copy, move, and remove files and directories:</h2>

* cp kopiert Dateien.

* mv verschiebt und unbenennt Dateien.

* rm löscht Dateien.

* rm -r löscht Ordner.

* Redirection leitet den standart input, output und Error um.

<h2>Die Gewöhnlichen Redirection Behfele sind:</h2>

* \> leitet einen Standart output von einem Command in eine Datei, und überschreibt den alten Content mit dem neuen.

* \>\> leitet einen Standart output von einem Command in eine Datei, und fügt neuen Content zum alten Hinzu.

* < leitet einen Standart input in einen Command

* | leitet einen Standart output von einem Command in einen anderen Command.

<h2>Ein paar Commands die mächtig sind mit Redirection CommandsA number of other commands are powerful when combined with redirection commands:</h2>

* sort: Sortiert Text Linien alphabetisch.

* uniq: filtert Duplikate aus dem Text.

* grep: Sucht nach einem Textmuster und zeigt es an.

* sed : Sucht nach einem Textmuster, modifizeirt esund zeigt es an.

* Die Umgebung bezieht sich auf die Präferenzen und Einstellungen des aktuellen Benutzers.

* Der Nano Editor ist der Command Line Editor für die Umgebung.

* ~/.bash_profile ist der Ort wo dieUmgebungs Einstellungen gespeichert sind. Man kann sie im Nano Editor bearbeiten.

* Umgebungs Variabeln sind Variabeln die dazu gebraucht werden können um Informationen quer über alle Commands und Programme zu speichern.

* export VARIABLE="Value" setzt ein export Variable fest.

* USER Ist der Name des zurzeitigen Benutzers.

* PS1 Ist die Eingabeaufforderung.

* HOME ist der Home Ordner. Er ist meistens nicht bearbeitet.

* PATH gibt eine durch einen Doppelpunkt getrennte Liste von Dateipfaden zurück. Es wird in fortgeschrittenen Fällen angepasst.

* ENV gibt eine Liste von Umgebungsvariablen zurück. Sie können den output umleiten, indem Sie mit grep die Variable auswählen, die Sie sehen möchten.
