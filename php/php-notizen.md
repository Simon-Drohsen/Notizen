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
