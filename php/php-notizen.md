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

* Wir können geordnete Arrays mit der kurzen Array-Syntax konstruieren, z.B. [1,2,3].

* Wir können Arrays mit der eingebauten Funktion print_r() ausdrucken oder sie mit der Funktion implode() in Strings umwandeln.

* Wir verwenden eckige Klammern ([]), um auf Elemente in einem Array über ihren Index zuzugreifen.

* Wir können Elemente an das Ende eines Arrays anfügen, indem wir eckige Klammern ([]) an den Namen einer Array-Variablen anhängen und den Wert mit dem Zuweisungsoperator (=) zuweisen.

* Mit Hilfe der Array-Indizierung und des Zuweisungsoperators können Sie Elemente in einem Array ändern.

* Mit der Funktion array_pop() wird das letzte Element eines Arrays entfernt.

* Die Funktion array_push() fügt Elemente an das Ende eines Arrays hinzu.

* Die Funktion array_shift() entfernt das erste Element eines Arrays.

* Die Funktion array_unshift() fügt Elemente an den Anfang des Arrays hinzu.

* Wir können verkettete eckige Klammern ([]) verwenden, um auf Elemente innerhalb eines verschachtelten Arrays zuzugreifen und diese zu ändern.
