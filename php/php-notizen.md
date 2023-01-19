<h1>PHP Notizen</h1>

* Trotz seines Alters ist PHP immer noch eine weit verbreitete Technologie in der Webentwicklung.

* PHP wurde für die Interaktion mit HTML entwickelt, um dynamische Websites zu erstellen.

* Die Einbettung von PHP in HTML erfolgt durch die Platzierung von PHP-Code zwischen den Tags <?php und ?>.

* Jede Anweisung in PHP muss mit einem Semikolon ; abgeschlossen werden.

* PHP-Dateien haben eine .php-Erweiterung und die Datei beginnt immer mit dem öffnenden PHP-Tag <?php. Der schließende Tag ist implizit und wird aus Konvention weggelassen.

* Leerzeichen werden bei der Ausführung von PHP-Code generell ignoriert.

* Bei Schlüsselwörtern wird in PHP nicht zwischen Groß- und Kleinschreibung unterschieden. Als Konvention sollte die Standard-Schreibweise verwendet werden.

* Einzeilige Kommentare werden in PHP mit # oder \// eingefügt. Mehrzeilige Kommentare werden zwischen \/* und \*/ eingefügt.

* Zeichenketten sind Textsammlungen, die der Computer als eine einzige Dateneinheit behandelt.

* Eine Zeichenfolge kann beliebig lang sein und beliebige Buchstaben, Zahlen, Symbole oder Leerzeichen enthalten, die von Anführungszeichen umgeben sind.

* Um bestimmte Zeichen in Zeichenketten einzufügen, müssen wir Escape-Sequenzen verwenden.

* Ein Operator ist ein Zeichen, das eine Aufgabe in unserem Code übernimmt.

* Wir können den Verkettungsoperator (.) verwenden, um zwei Zeichenketten zu einer einzigen zu verbinden.

* Variablen sind ein grundlegendes Programmierkonzept, mit dem wir Daten in unserem Code leicht wiederverwenden können.

* Wir deklarieren eine Variable mit dem Dollarzeichen ($), gefolgt vom Variablennamen, und verwenden dann den Zuweisungsoperator (=), um ihr einen Wert zu geben.

* PHP verfügt über ein Variablen-Parsing, mit dem wir Variablen direkt in unsere Strings einfügen können.

* Sobald eine Variable zugewiesen wurde, können wir ihren Wert ändern. Dies wird als Neuzuweisung bezeichnet.

* Mit dem Referenzzuweisungsoperator (=&) können wir einen Alias für eine Variable erstellen, anstatt nur eine Kopie.

* Die Operationen rechts vom Zuweisungsoperator werden ausgewertet, bevor die Zuweisung erfolgt.

* Der Verkettungsoperator (.=) ist eine Kurzschreibweise für die Neuzuweisung einer String-Variablen an ihren aktuellen Wert, an den ein anderer String-Wert angehängt wird.

* PHP hat zwei Datentypen: Ganzzahlen und Fließkommazahlen

* Wir können arithmetische Operatoren verwenden, um mathematische Operationen durchzuführen:

* Operationen haben eine Rangfolge, d. h. bestimmte Arten von Operationen in einer Kette werden vor anderen ausgewertet: Zuerst wird jede Operation ausgewertet, die in Klammern (()) eingeschlossen ist, dann Exponenten (**), dann Multiplikation (*) und Division (/) und schließlich Addition (+) und Subtraktion (-).

* Wir können Variablen Zahlenwerte zuweisen und dann numerische Operationen mit ihnen durchführen.

* Bei der Neuzuweisung von Zahlenvariablen können wir mathematische Zuweisungsoperatoren als Abkürzung verwenden.

* Wir können eine Reihe von Anweisungen in einer benannten Funktion zusammenfassen und jederzeit wiederverwenden.

* Wenn wir eine Funktion aufrufen, führt der Computer den Funktionskörper aus, der durch den Codeblock nach der Parameterliste angegeben wird.

* Funktionen können einen Wert zurückgeben, indem sie das Schlüsselwort return verwenden, andernfalls geben sie NULL zurück, was keinen Wert bedeutet.

* Der Rückgabewert einer Funktion kann in einer Variablen gespeichert oder auf jede andere Weise verwendet werden.

* Wir können Funktionen mit Parametern definieren, die Variablen sind, auf die wir uns im gesamten Funktionskörper beziehen können.

* Beim Aufrufen von Funktionen werden die Werte, die wir ihnen geben, als Argumente bezeichnet.

* Funktionen können mehrere Parameter haben.

* Die Reihenfolge, in der die Argumente übergeben werden, bestimmt, welchen Parametern sie entsprechen.

* Sie können ein Argument optional machen, indem Sie den entsprechenden Parameter mit einem Standardwert versehen.

* Wenn Sie einem Parameter das Referenzzeichen (&) voranstellen, wird das Argument per Referenz übergeben.

* Variablen innerhalb von Funktionen haben einen lokalen Geltungsbereich und können nicht von außerhalb der Funktion angesprochen werden.

* Verwenden Sie das Schlüsselwort global, um Variablen aus dem globalen Bereich innerhalb einer Funktion zu verwenden.

* Built-in Funktionen sind Funktionen von PHP.

* Die Funktoinen folgen nicht dem normalen naming scheme.

* Arrays sind geordnete Datensammlungen, die eine grundlegende Datenstruktur in der Informatik darstellen.

* In PHP bezeichnen wir diese Datenstruktur als geordnete Arrays.

* Die Position eines Elements in einem Array wird als sein Index bezeichnet.

* Die Elemente in einem geordneten Array sind in aufsteigender numerischer Reihenfolge angeordnet, beginnend mit Index Null.

* Wir können geordnete Arrays mit einer eingebauten PHP-Funktion konstruieren: array().

* Wir können geordnete Arrays mit der kurzen Array-Syntax konstruieren, z.B. \[1,2,3].

* Wir können Arrays mit der eingebauten Funktion print_r() ausdrucken oder sie mit der Funktion implode() in Strings umwandeln.

* Wir verwenden eckige Klammern ([]), um auf Elemente in einem Array über ihren Index zuzugreifen.

* Wir können Elemente an das Ende eines Arrays anfügen, indem wir eckige Klammern ([]) an den Namen einer Array-Variablen anhängen und den Wert mit dem Zuweisungsoperator (=) zuweisen.

* Mit Hilfe der Array-Indizierung und des Zuweisungsoperators können Sie Elemente in einem Array ändern.

* Mit der Funktion array_pop() wird das letzte Element eines Arrays entfernt.

* Die Funktion array_push() fügt Elemente an das Ende eines Arrays hinzu.

* Die Funktion array_shift() entfernt das erste Element eines Arrays.

* Die Funktion array_unshift() fügt Elemente an den Anfang des Arrays hinzu.

* Wir können verkettete eckige Klammern ([]) verwenden, um auf Elemente innerhalb eines verschachtelten Arrays zuzugreifen und diese zu ändern.

* Assoziative Arrays sind Datenstrukturen, in denen String- oder Integer-Schlüssel mit Werten verbunden sind.

* Wir verwenden den Operator =>, um einen Schlüssel mit seinem Wert zu verknüpfen. $my_array = ["panda"=>"sehr süß"]

* Um die Schlüssel eines Arrays und ihre Werte zu drucken, können wir die Funktion print_r() verwenden.

* Wir greifen auf den Wert zu, der mit einem bestimmten Schlüssel verbunden ist, indem wir eckige Klammern ([ ]) verwenden. Zum Beispiel: $my_array\["panda"] gibt "very cute" zurück.

* Mit der gleichen Indizierungssyntax und dem Zuweisungsoperator (=) können wir den Schlüsseln Werte zuweisen: $my_array\["dog"] = "good cuteness";

* Dieselbe Syntax kann verwendet werden, um bestehende Elemente zu ändern. $my_array\["Hund"] = "maximale Niedlichkeit";

* Mit der PHP-Funktion unset() können wir ein Schlüssel=>Wert-Paar vollständig entfernen.

* Schlüssel können ganze Zahlen sein. Geordnete Arrays sind eigentlich nur Arrays, in denen den Werten automatisch Integer-Schlüssel zugewiesen wurden.

* In PHP sind assoziative Arrays und geordnete Arrays unterschiedliche Verwendungen desselben Datentyps.

* Der Operator union (+) nimmt zwei Array-Operanden und gibt ein neues Array zurück, bei dem alle eindeutigen Schlüssel des zweiten Arrays an das erste Array angehängt werden.

* Wenn wir eine Funktion mit Array-Parametern schreiben, können wir das Array als Wert oder als Referenz übergeben, je nach unserer Absicht.

* Das Front-End einer Website besteht aus JavaScript, CSS, HTML, Bildern und anderen statischen Elementen, die an den Client gesendet werden.

* Wenn wir zu einer Website navigieren, ist der Browser der Client und sendet eine Anfrage an das Back-End, um alle für die Anzeige und Interaktion mit der Website erforderlichen Elemente zu erhalten.

* Das Back-End besteht aus einem Webserver und der gesamten Logik und den Daten, die zur Erstellung und Pflege einer Website oder Webanwendung erforderlich sind.

* PHP ist eine Backend-Sprache.

* PHP kann zur Erzeugung von HTML-Dateien verwendet werden.

* Wir betten PHP-Skripte in HTML ein, indem wir PHP-Code zwischen den öffnenden (<?php) und schließenden (?>) Tags einfügen.

* <?= ist die Kurzform für <?php echo.

* PHP bietet Superglobale, auf die überall im Skript zugegriffen werden kann.

* $_GET ist ein assoziatives Array, das Daten aus einer GET-Anfrage enthält.

* $_POST ist ein assoziatives Array, das Daten von einer POST-Anfrage enthält.

* $_REQUEST ist ein assoziatives Array, das Daten sowohl von GET- als auch von POST-Anfragen enthält. Es sollte nur verwendet werden, wenn es Ihnen egal ist, welche Methode verwendet wurde.

* Die Array-Schlüssel in den PHP-Anfrage-Superglobalen werden durch die Namensattribute im HTML-Formular festgelegt, die eindeutig sein müssen.

* Das action-Attribut wird verwendet, um anzugeben, welche Datei die Daten aus der Formularanfrage verarbeiten soll.

* Mit Hilfe von Konditionalen können Programme entscheiden, wie sie auf eine Vielzahl von Situationen reagieren sollen.

* if-Anweisungen ermöglichen es uns, einen Codeblock auszuführen, wenn eine Bedingung erfüllt ist.

* Der boolesche Datentyp hat entweder den Wert TRUE oder FALSE und ist die Grundlage der programmatischen Entscheidungsfindung.

* Mit else wird ein Codeblock eingefügt, der ausgeführt wird, wenn die Bedingung nicht erfüllt ist.

* Vergleichsoperatoren bewerten eine Beziehung zwischen zwei Operanden und geben einen booleschen Wert zurück.

* Der Kleiner-als-Operator (<)

* Der Operator kleiner als oder gleich (<=)

* Der Operator größer als (>)

* Der Operator "größer als" oder "gleich" (>=)

* Der Identisch-Operator (===)

* Der nicht identische Operator (!==)

* Mit der elseif-Konstruktion können wir Konditionale mit mehreren if-Anweisungen schreiben.

* Anstatt eine Reihe von if-Anweisungen zu verwenden, wenn wir einen Wert, einen Ausdruck oder eine Variable mit vielen verschiedenen möglichen Werten vergleichen und je nach Übereinstimmung unterschiedlichen Code ausführen wollen, können wir eine switch-Anweisung verwenden.

* Das Schlüsselwort break weist den Computer an, die switch-Anweisung zu verlassen. Ohne dieses Schlüsselwort wird der Rest der switch-Anweisung durchlaufen, wobei der gesamte Code ausgeführt wird, bis ein break oder das Ende der Anweisung erreicht wird.

* Ein ternärer Operator (?:) ist ein Kurzzeichen für einen Bedingungsoperator. Er benötigt drei Operanden (eine zu prüfende Bedingung, einen Ausdruck, der zurückgegeben wird, wenn die Bedingung TRUE ist, und einen Ausdruck, der zurückgegeben wird, wenn die Bedingung FALSE ist).

* Jeder Wert oder Ausdruck innerhalb einer Bedingung wird in TRUE oder FALSE umgewandelt. Wir betrachten Werte, die in TRUE umgewandelt werden, als wahrheitsgemäß und Werte, die in FALSE umgewandelt werden, als falsch.

* Mit der Funktion readline() können wir Benutzereingaben vom Terminal abrufen.

* Durch die Verschachtelung von Bedingungen ineinander können wir Verzweigungsentscheidungen treffen.

* Der logische Operator || nimmt zwei verschiedene boolesche Werte oder Ausdrücke als Operanden und gibt einen einzigen booleschen Wert zurück. Er gibt TRUE zurück, wenn entweder sein linker Operand oder sein rechter Operand TRUE ergibt.

* Der logische Operator && gibt nur TRUE zurück, wenn beide Operanden TRUE ergeben. Er gibt FALSE zurück, wenn einer oder beide seiner Operanden FALSE ergeben.

* Der logische Operator not (!) nimmt nur einen rechten Operanden an. Er kehrt den booleschen Wert seines Operanden um.

* Der logische Exklusiv-Oder-Operator (xor) gibt nur dann TRUE zurück, wenn entweder sein linker oder sein rechter Operand TRUE ergibt, aber nicht beide oder keiner von beiden.

* PHP bietet eine alternative Syntax für die Operatoren || und &&: Wir können or anstelle von || und and anstelle von && verwenden. Diese Operatoren funktionieren auf die gleiche Weise, haben aber eine andere Rangfolge.

* Mit include können wir Code aus einer Datei in eine andere einbinden, was es uns ermöglicht, modulare Programme zu schreiben.

* while-Schleifen werden nur so lange ausgeführt, wie ihre Bedingung TRUE ergibt.

* do...while-Schleifen werden immer mindestens einmal ausgeführt und setzen dann die Ausführung fort, solange ihre Bedingung TRUE ist.

* for-Schleifen enthalten 3 Ausdrücke und werden häufig verwendet, um einen Codeblock eine bestimmte Anzahl von Malen auszuführen.

* Der erste Ausdruck wird vor der ersten Iteration ausgeführt.

* Der zweite Ausdruck wird vor jeder Iteration ausgewertet. Wenn TRUE, wird der Codeblock ausgeführt. Andernfalls wird die Schleife abgebrochen.

* Der dritte Ausdruck wird nach jeder Iteration ausgewertet.

* foreach-Schleifen werden verwendet, um über die Elemente eines Arrays zu iterieren. Der Schlüssel und der Wert jedes Elements sind im Codeblock verfügbar.

* break wird verwendet, um die Ausführung einer Schleife vorzeitig zu beenden.

* continue wird verwendet, um die Ausführung einer Schleifeniteration vorzeitig zu beenden und mit der nächsten Iteration fortzufahren.

* Die PHP-Kurzschrift für Schleifen verwendet einen Doppelpunkt (:) anstelle einer Klammer ({), um den Codeblock zu öffnen.

* Die Kurzschrift verwendet Schlüsselwörter zum Schließen des Codeblocks anstelle einer Klammer (}):

* Verwenden Sie endfor, um eine for-Schleife zu schließen.

* Verwenden Sie endforeach, um eine foreach-Schleife zu schließen.

* Verwenden Sie endwhile, um eine while-Schleife zu schließen.

* Das abschließende Schlüsselwort muss von einem Semikolon (;) gefolgt werden.

* Vergewissern Sie sich, dass Sie mit <?php oder der Echo-Verknüpfung <?= wieder in den PHP-Modus wechseln, bevor Sie PHP-Variablen in der Schleife verwenden.

* Moderne Websites benötigen eine Vielzahl von Informationen von ihren Nutzern, und viele dieser Informationen werden über HTML-Formulare erfasst.

* Es ist wichtig, die über Formulare übermittelten Daten zu validieren, um die Sicherheit von Websites zu gewährleisten und sicherzustellen, dass sie korrekt funktionieren.

* Reguläre Ausdrücke sind Zeichenfolgen, die Muster definieren, nach denen im Text gesucht werden soll. Sie sind ein wichtiges Werkzeug für die Validierung von Eingaben.

* Modernes HTML verfügt über nützliche integrierte Methoden zur Formularvalidierung.

* Benutzerdefinierte und komplizierte Client-seitige Validierung kann mit JavaScript durchgeführt werden.

* Asynchrone Anfragen an den Server können Back-End-Validierungen durchführen, bevor ein Formular abgeschickt wird.

* Eine abschließende Back-End-Validierung aller Daten ist erforderlich, um die Sicherheit einer Anwendung zu gewährleisten und alle Daten zu säubern.

* Die Durchführung von Back-End-Formularvalidierungen an den übermittelten Daten ist ein wesentlicher Schritt zum Schutz unserer Website und ihrer Benutzer.

* Die Verwendung des POST-Methodenattributs in einem HTML-Formular gibt unserem PHP-Skript Zugriff auf die Daten, die in dem superglobalen assoziativen Array $_POST übermittelt werden.

* Wir ändern unser HTML- und PHP-Skript so, dass dem Benutzer eine aussagekräftige Rückmeldung angezeigt wird, wenn die Eingabe als ungültig eingestuft wird.

* Wenn wir planen, Benutzereingaben anzuzeigen, müssen wir sie zunächst bereinigen. Wir können Methoden wie trim() und htmlspecialchars() für die grundlegende Bereinigung verwenden.

* Wir können filter_var() mit einem Filter verwenden, um gängige Eingabetypen zu bereinigen.

* Wir können auch filter_var() mit einem Filter verwenden, um Validierungen für gängige Eingabetypen durchzuführen.

* Wir werden oft benutzerdefinierte Überprüfungen durchführen wollen.

* Die Funktion preg_match() vergleicht, ob eine gegebene Zeichenkette mit einem regulären Ausdruck übereinstimmt.

* Da Vergleiche mit regulären Ausdrücken viel Rechenleistung verbrauchen können, ist es sinnvoll, die Länge der Eingaben zu überprüfen, bevor die Prüfungen mit regulären Ausdrücken durchgeführt werden.

* Es ist üblich, Validierungen durch den Vergleich von Benutzereingaben mit Backend-Daten durchzuführen

* Bevor wir die Benutzereingaben in unserem Backend speichern, werden wir sie aus Gründen der Sicherheit und der einheitlichen Formatierung bereinigen

* Wenn das Formular eines Benutzers akzeptiert wurde, können wir ihn auf eine andere Seite umleiten.

* Klassen werden mit dem Schlüsselwort class definiert.

* Innerhalb einer Klasse definierte Funktionen werden zu Methoden und Variablen innerhalb der Klasse werden als Eigenschaften betrachtet.

* Es gibt drei Stufen der Sichtbarkeit von Klassenmitgliedern:

* public (Standard) - von außerhalb der Klasse zugänglich

* protected - nur innerhalb der Klasse oder ihrer Nachkommenschaft zugänglich

* private - nur innerhalb der definierenden Klasse zugänglich

* Mitglieder können als statisch definiert werden.

* Auf statische Mitglieder wird mit dem Scope Resolution Operator (::) zugegriffen.

* Klassen werden mit dem Schlüsselwort new zu Objekten instanziiert.

* Der Zugriff auf die Mitglieder eines Objekts erfolgt mit dem Objektoperator (->).

* Mit einer if-Anweisung können wir überprüfen, ob eine Datenbankabfrage Ergebnisdaten zurückgegeben hat.

* Die alternative Syntax von PHP bietet eine Alternative zum Einschließen von Blöcken in geschweifte Klammern, wodurch verschachtelte Blöcke leichter abgegrenzt werden können.

* Die alternative Syntax kann sowohl mit if-Anweisungen als auch mit for-, while- und foreach-Schleifen verwendet werden.

* Mit dem kurzen echo-Tag können wir prägnantere echo-Anweisungen schreiben.

* Um PHP-Warnungen zu vermeiden, ist es eine gute Idee, eine Eigenschaft zu überprüfen, bevor man auf sie zugreift.

* Die Überprüfung von Werten kann mit einem ternären Operator erfolgen, der drei Operanden benötigt, oder mit dem kürzeren null-coalescing-Operator, der zwei benötigt.

* Verwenden Sie fopen mit dem richtigen Modus, um auf eine Datei zum Lesen, Schreiben oder Anhängen zuzugreifen.

* Schließen Sie alle Dateien, die Sie nicht aktiv benutzen, mit fclose.

* Lesen Sie Dateien mit fread oder file_get_contents.

* Schreiben von Dateien mit fwrite oder file_put_contents.

* Abrufen von Informationen über Dateien mit Operationen wie filesize und file_exists.

* Fehler zu finden und zu diagnostizieren, indem man die Rückgabewerte von Funktionen überprüft, die Konsole auf Fehlermeldungen untersucht und Dateiinformationsfunktionen verwendet.

* Mit Web-APIs haben wir ein Werkzeug, mit dem wir auf die Funktionen und Daten einer anderen Anwendung zugreifen können.

* Es gibt zwei Haupttypen von APIs: Browser- und Drittanbieter-APIs.

* Browser-APIs erfordern eine bestimmte Syntax und Berechtigungen.

* Drittanbieter-APIs haben ihre eigenen Regeln und Anforderungen, die von den Organisationen festgelegt werden, die sie verwalten.

* Wenn wir eine Anfrage an eine API stellen, müssen wir möglicherweise mehr Details zu den gewünschten Informationen angeben.

* Wenn wir eine erfolgreiche Antwort erhalten, müssen wir noch entscheiden, wie wir die Antwortdaten nutzen wollen.

* Bevor Sie eine API verwenden, sollten Sie ihre Dokumentation lesen. Achten Sie besonders darauf, wie sie Anfragen, Antworten und Fehler behandelt.

* Abfragezeichenfolgen werden verwendet, um zusätzliche Informationen zusammen mit einer API-Anforderung bereitzustellen. Sie bestehen aus key-value-pairs, die an das Ende einer URL angehängt werden.

* Die Funktion file_get_contents() kann zur Durchführung einfacher API-Anfragen in PHP verwendet werden. Wenn die Funktion mit einer Anfrage-URL aufgerufen wird, gibt sie die Antwort als String zurück - oder false, wenn die Anfrage erfolglos war.

* Die Funktion json_decode() wird zum Parsen einer JSON-Antwort verwendet. Je nach dem zweiten Argument kann die Funktion entweder ein Objekt oder ein assoziatives Array zurückgeben.

* Um Fehler in der API-Antwort zu behandeln, sollten Sie die Antwortdaten validieren, bevor Sie auf bestimmte Eigenschaften zugreifen.

* Speichern Sie die Dienstleistungsbeschreibungen in den Tabellenzeilen mit dem Namen und den Preisen. Vielleicht sogar eine Schleife durch die Datenbankabfrageergebnisse, um die Blöcke auf der Dienstleistungsseite anzuzeigen!

* Beenden Sie die Kontaktseite - betten Sie eine Karte des Salons ein und fügen Sie ein Kontaktformular hinzu, mit dem der Besitzer per E-Mail kontaktiert werden kann.

* Erstellen Sie eine Anmeldeseite und eine Seite, auf der der Salonbesitzer die Preise aktualisieren kann.

* Können Sie sich vorstellen, wie Sie eine neue Tabelle verwenden könnten, um Kunden die Möglichkeit zu geben, online einen Service zu buchen?

<h2>Database</h2>

* Databases store data for PHP applications.

* PDO lets us write code that will work with many common database systems.

* We write queries by inserting SQL into the query() method.

* SQL queries with user-defined parameters (variables) are vulnerable to SQL injection.

* We use prepared statements to prevent SQL injection.

* Prepared statements use the prepare() and execute() methods and send SQL commands and data separately.

* For exception handling, we wrap code in a try/catch block.

* We use exception handling to catch and handle exceptions when our program throws them.

* We can use methods on the exception object to troubleshoot exceptions.
