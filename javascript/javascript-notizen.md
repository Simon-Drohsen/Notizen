<h1>Javascript</h1>

* HTML erstellt das Grundgerüst einer Webseite, aber JavaScript sorgt für Interaktivität

* Das \<script>-Element hat einen öffnenden und einen schließenden Tag. Sie können JavaScript-Code zwischen den öffnenden und schließenden \<script>-Tags einbetten.

* Mit dem src-Attribut im öffnenden \<script>-Tag können Sie auf externe JavaScript-Dateien verweisen.

* Standardmäßig werden Skripte geladen und ausgeführt, sobald der HTML-Parser auf sie in der HTML-Datei stößt. Der HTML-Parser wartet, bis das gesamte Skript geladen ist, bevor er mit der Analyse der übrigen Seitenelemente fortfährt.

* Das Attribut defer stellt sicher, dass die gesamte HTML-Datei geparst wurde, bevor das Skript ausgeführt wird.

* Das async-Attribut ermöglicht es dem HTML-Parser, mit dem Parsen fortzufahren, während das Skript heruntergeladen wird, aber es wird sofort nach dem Herunterladen ausgeführt.

* Das Schlüsselwort document ermöglicht den Zugriff auf die Wurzel des DOM in JavaScript.

* Die DOM-Schnittstelle ermöglicht es, ein bestimmtes Element mit CSS-Selektoren auszuwählen, indem die Methode .querySelector() verwendet wird.

* Mit der Methode .getElementById(), die ein einzelnes Element zurückgibt, können Sie direkt über dessen ID auf ein Element zugreifen.

* Sie können auf ein Array von Elementen mit den Methoden .getElementsByClassName() und .getElementsByTagName() zugreifen und dann ein einzelnes Element aufrufen, indem Sie auf seine Position im Array verweisen.

* Die Eigenschaften .innerHTML und .style ermöglichen es Ihnen, ein Element zu modifizieren, indem Sie seinen Inhalt bzw. seinen Stil ändern.

* Mit den Methoden .createElement(), .appendChild() und .removeChild() können Sie Elemente erstellen, anhängen und entfernen.

* Mit der Eigenschaft .onclick kann einem DOM-Element auf der Grundlage eines Klick-Ereignisses Interaktivität hinzugefügt werden.

* Die Eigenschaft .children gibt eine Liste der Kinder eines Elements zurück, und die Eigenschaft .parentNode gibt den nächsten verbundenen Knoten des Elements in Richtung der Wurzel zurück.

* Handlebars ist eine externe Bibliothek, mit der Vorlagen erstellt werden können, die eine Mischung aus HTML, Text und Ausdrücken sind.

* Handlebars verwendet Ausdrücke, die in doppelte geschweifte Klammern eingeschlossen sind, wie: {{someVariable}}

* Ein Skript-Tag mit dem Typ "text/x-handlebars-template" wird verwendet, um eine Vorlage an den Browser zu übergeben.

* Handlebar.compile() gibt eine Template-Funktion aus einem Template-Skript zurück, das für Handlebars bestimmt ist.

* Ein Template, das mit .compile() erstellt wird, nimmt ein Objekt als Argument und verwendet es als Kontext, um einen String mit HTML zu erzeugen.

* Handlebars verfügt über eingebaute Block-Helfer, die in ein Handlebars-Skript eingefügt werden können.

* Block-Helfer haben einen Anfangsausdruck und einen Endausdruck. Der Anfangsausdruck enthält ein # vor einem Schlüsselwort. Der Endausdruck hat das gleiche Schlüsselwort, aber mit einem /-Zeichen, um das Ende zu kennzeichnen.

* Der {{if}}-Ausdruck gibt einen Codeblock bedingt wieder.

* Ein {{else}}-Ausdruck kann in einen if-Hilfsblock eingefügt und als Teil der bedingten Anweisung verwendet werden.

* {{each}} ist ein weiterer eingebauter Hilfsausdruck, der ein Array zur Iteration akzeptiert.

* In den Block-Helper-Funktionen gibt der {{this}}-Ausdruck den Kontext an und dient als Platzhalter für den aktuellen Wert.

* Das Objekt, zu dem eine Methode gehört, wird das aufrufende Objekt genannt.

* Das Schlüsselwort this bezieht sich auf das aufrufende Objekt und kann verwendet werden, um auf Eigenschaften des aufrufenden Objekts zuzugreifen.

* Methoden haben nicht automatisch Zugriff auf andere interne Eigenschaften des aufrufenden Objekts.

* Der Wert von this hängt davon ab, woher der Zugriff auf this erfolgt.

* Wir können Pfeilfunktionen nicht als Methoden verwenden, wenn wir auf andere interne Eigenschaften zugreifen wollen.

* JavaScript-Objekte haben keine eingebaute Privatsphäre, sondern es gibt Konventionen, die man befolgen muss, um andere Entwickler über die Absicht des Codes zu informieren.

* Die Verwendung eines Unterstrichs vor einem Eigenschaftsnamen bedeutet, dass der ursprüngliche Entwickler nicht beabsichtigt hat, diese Eigenschaft direkt zu ändern.

* Setter- und Getter-Methoden ermöglichen detailliertere Möglichkeiten des Zugriffs auf und der Zuweisung von Eigenschaften.

* Factory-Funktionen ermöglichen es, Objektinstanzen schnell und wiederholt zu erstellen.

* Es gibt verschiedene Möglichkeiten, die Objektdestrukturierung zu verwenden: eine Möglichkeit ist die Kurzschrift für Eigenschaftswerte, eine andere die destrukturierte Zuweisung.

* Wie bei jedem Konzept ist es gut zu lernen, wie man die Dokumentation mit Objekten verwendet!* 

* Komplette Array Dokumentation: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array#Iteration_methods

* Die Daten werden mit console.log() auf der Konsole, einem Panel angezeigt.

* Wir können einzeilige Kommentare mit // und mehrzeilige Kommentare zwischen /* und */ schreiben.

* Es gibt 7 grundlegende Datentypen in JavaScript: Strings, Zahlen, Boolesche Werte (true, false), null, undefiniert, Symbol und Objekt.

* Zahlen sind beliebige Zahlen ohne Anführungszeichen: 23.8879

* Strings sind Zeichen, die in einfache oder doppelte Anführungszeichen eingeschlossen sind: 'Beispielstring'

* Zu den eingebauten arithmetischen Operatoren gehören +, -, *, / und %.

* Objekte, einschließlich Instanzen von Datentypen, können Eigenschaften haben, also gespeicherte Informationen. Die Eigenschaften werden mit einem . nach dem Namen des Objekts gekennzeichnet, zum Beispiel: 'Hello'.length.

* Objekte, einschließlich Instanzen von Datentypen, können über Methoden verfügen, die Aktionen ausführen. Methoden werden aufgerufen, indem dem Objekt oder der Instanz ein Punkt, der Methodenname und Klammern angehängt werden. Zum Beispiel: 'hallo'.toUpperCase().

* Auf Eigenschaften und Methoden kann man mit dem Operator "Dot", zugreifen.

* Eingebaute Objekte, mit "Math", sind Sammlungen von Methoden und Eigenschaften, die JavaScript bereitstellt.

* Variablen enthalten wiederverwendbare Daten in einem Programm und verknüpfen sie mit einem Namen.

* Variablen werden im Speicher abgelegt.

* Das var-Schlüsselwort wird in Vor-ES6-Versionen von JS verwendet.

* let ist die bevorzugte Art, eine Variable zu deklarieren, wenn sie neu zugewiesen werden kann, und const ist die bevorzugte Art, eine Variable mit einem konstanten Wert zu deklarieren.

* Variablen, die nicht initialisiert wurden, speichern den primitiven Datentyp undefined.

* Mathematische Zuweisungsoperatoren erleichtern die Berechnung eines neuen Wertes und seine Zuweisung an dieselbe Variable.

* Der +-Operator wird zur Verkettung von Strings verwendet, einschließlich der in Variablen gespeicherten Zeichenkettenwerte.

* In ES6 verwenden Template-Literale "Backticks" (`) und "${}", um Werte in einen String zu interpolieren.

* Das Schlüsselwort typeof gibt den Datentyp (als String) eines Wertes zurück.

* Eine if-Anweisung prüft eine Bedingung und führt eine Aufgabe aus, wenn diese Bedingung als wahr bewertet wird.

* if...else-Anweisungen treffen binäre Entscheidungen und führen verschiedene Codeblöcke auf der Grundlage einer vorgegebenen Bedingung aus.

* Mit else if-Anweisungen können wir weitere Bedingungen hinzufügen.

* Vergleichsoperatoren, einschließlich <, >, <=, >=, === und !==, können zwei Werte vergleichen.

* Der Logisch und-Operator && oder "und" prüft, ob beide angegebenen Ausdrücke wahr sind.

* Der Logisch Operator ||, oder "oder", prüft, ob einer der beiden angegebenen Ausdrücke der Wahrheit entspricht.

* Der bang-Operator ! wechselt den Wahrheitsgehalt und Falschheitsgehalt eines Wertes.

* Der ternäre Operator ist eine Abkürzung, um prägnante if...else-Anweisungen zu vereinfachen.

* Eine switch-Anweisung kann verwendet werden, um den Prozess des Schreibens mehrerer else if-Anweisungen zu vereinfachen. Das break-Schlüsselwort verhindert, dass die verbleibenden Fälle in einer switch-Anweisung geprüft und ausgeführt werden.

* Eine Funktion ist ein wiederverwendbarer Codeblock, der eine Folge von Anweisungen zusammenfasst, um eine bestimmte Aufgabe zu erfüllen.

* Ein Parameter ist eine benannte Variable innerhalb eines Funktionsblocks, der der Wert des übergebenen Arguments zugewiesen wird, wenn die Funktion aufgerufen wird:

* ES6 führt neue Möglichkeiten für den Umgang mit beliebigen Parametern durch Standardparameter ein, die es uns ermöglichen, einem Parameter einen Standardwert zuzuweisen, falls kein Argument an die Funktion übergeben wird.

* Um einen Wert aus einer Funktion zurückzugeben, verwenden wir eine return-Anweisung.

* "Scope" bezieht sich darauf, wo im Programm auf Variablen zugegriffen werden kann, und wird dadurch bestimmt, wo und wie sie deklariert werden.

* "Blocks" sind Anweisungen, die innerhalb geschweifter Klammern {} stehen.

* Der "Global scope" bezieht sich auf den Kontext, in dem Variablen für jeden Teil des Programms zugänglich sind.

* "Global variables" sind Variablen, die im "Global Scope" existieren.

* Der "Block scope" bezieht sich auf den Kontext, in dem Variablen nur innerhalb des Blocks definiert sind.

* "Local variables" sind Variablen, die innerhalb des Blockbereichs existieren.

* "Global namespace" ist der Bereich in unserem Code, der Informationen mit globalem Geltungsbereich enthält.

* Von "scope pollution" spricht man, wenn zu viele Variablen in einem Namespace hat oder Variablennamen wiederverwendet werden.

* Denken Sie daran, bei der Deklaration Ihrer Variablen die besten Praktiken anzuwenden! Wenn Sie Ihre Variablen eng einteilen, können Sie sicherstellen, dass Ihr Code eine saubere, organisierte und modulare Logik aufweist.

* Arrays sind Listen, die Daten in JavaScript speichern.

* Arrays werden mit Klammern [] erstellt.

* Jedes Element in einem Array befindet sich an einer nummerierten Position oder einem Index, beginnend bei 0.

* Wir können auf ein Element in einem Array über seinen Index zugreifen, mit einer Syntax wie: myArray[0].

* Wir können auch ein Element in einem Array über seinen Index ändern, mit einer Syntax wie: myArray[0] = 'new string';

* Arrays haben eine ".length property", mit der Sie die Anzahl der Elemente in einem Array anzeigen können.

* Arrays haben ihre eigenen Methoden, einschließlich .push() und .pop(), die Elemente zu einem Array hinzufügen bzw. daraus entfernen.

* Arrays haben viele Methoden, die verschiedene Aufgaben erfüllen, wie z.B. .slice() und .shift().

* Einige eingebaute Methoden sind veränderlich, d.h. die Methode verändert das Array, während andere das nicht tun.

* Variablen, die Arrays enthalten, können mit "let" oder "const" deklariert werden. Selbst wenn sie mit const deklariert werden, sind Arrays noch veränderbar. Allerdings kann eine mit const deklarierte Variable nicht neu zugewiesen werden.

* Arrays, die innerhalb einer Funktion verändert werden, behalten diese Änderung auch außerhalb der Funktion bei.

* Arrays können innerhalb anderer Arrays verschachtelt werden.

* Um auf Elemente in verschachtelten Arrays zuzugreifen, verketten Sie die Indizes mit der Klammerschreibweise.

* "Loops" führen sich wiederholende Aktionen aus, so dass wir diesen Prozess nicht jedes Mal manuell programmieren müssen.

* Eine verschachtelte for-Schleife ist eine Schleife innerhalb einer anderen Schleife

* while-Schleifen ermöglichen verschiedene Arten von Abbruchbedingungen

* Abbruchbedingungen sind entscheidend für die Vermeidung von Endlosschleifen.

* do...while-Schleifen führen den Code mindestens einmal aus und überprüfen die Abbruchbedingung erst nach der ersten Ausführung.

* Das break-Schlüsselwort ermöglicht es Programmen, eine Schleife während der Ausführung ihres Blocks zu verlassen.

* "abstraction" ermöglicht es uns, komplizierten Code so zu schreiben, dass er leicht wiederverwendbar, fehlerfrei und für den menschlichen Leser verständlich ist.

* Wir können mit Funktionen auf dieselbe Weise arbeiten wie mit jeder anderen Art von Daten, einschließlich der Neuzuweisung von Funktionen an neue Variablen.

* JavaScript-Funktionen sind Objekte erster Klasse, d.h. sie haben Eigenschaften und Methoden wie jedes andere Objekt.

* Funktionen können an andere Funktionen als Parameter übergeben werden.

* Eine Funktion höherer Ordnung ist eine Funktion, die entweder Funktionen als Parameter annimmt, eine Funktion zurückgibt oder beides.

* .forEach() wird verwendet, um den gleichen Code für jedes Element in einem Array auszuführen, verändert aber das Array nicht und gibt undefiniert zurück.

* .map() führt denselben Code für jedes Element in einem Array aus und gibt ein neues Array mit den aktualisierten Elementen zurück.

* .filter() prüft jedes Element in einem Array, um zu sehen, ob es bestimmte Kriterien erfüllt und gibt ein neues Array mit den Elementen zurück, die die Kriterien erfüllen.

* .findIndex() gibt den Index des ersten Elements eines Arrays zurück, das eine Bedingung in der Callback-Funktion erfüllt. Sie gibt -1 zurück, wenn keines der Elemente im Array die Bedingung erfüllt.

* .reduce() iteriert durch ein Array, nimmt die Werte der Elemente und gibt einen einzelnen Wert zurück.

* Alle Iterator-Methoden benötigen eine Callback-Funktion, die eine vordefinierte Funktion, ein Funktionsausdruck oder eine Pfeilfunktion sein kann.

* In Objekten werden Sammlungen von Schlüssel-Wert-Paaren gespeichert.

* Jedes Schlüssel-Wert-Paar ist eine Eigenschaft - wenn eine Eigenschaft eine Funktion ist, wird sie als Methode bezeichnet.

* Ein Objektliteral besteht aus kommagetrennten Schlüssel-Wert-Paaren, die von geschweiften Klammern umgeben sind.

* Sie können auf eine Eigenschaft innerhalb eines Objekts zugreifen, sie hinzufügen oder bearbeiten, indem Sie die Punkt- oder Klammerschreibweise verwenden.

* Wir können Methoden zu unseren Objektliteralen hinzufügen, indem wir die Schlüssel-Wert-Syntax mit anonymen Funktionsausdrücken als Werte verwenden oder die neue ES6-Methodensyntax nutzen.

* Wir können durch komplexe, verschachtelte Objekte navigieren, indem wir Operatoren verketten.

* Objekte sind veränderbar - wir können ihre Eigenschaften ändern, auch wenn sie mit const deklariert sind.

* Objekte werden per Referenz übergeben - wenn wir Änderungen an einem Objekt vornehmen, das an eine Funktion übergeben wird, sind diese Änderungen dauerhaft.

* Wir können mit der For...in-Syntax durch Objekte iterieren.

* Das Objekt, zu dem eine Methode gehört, wird das "calling object" genannt.

* Das Schlüsselwort "this" bezieht sich auf das "calling object" und kann verwendet werden, um auf Eigenschaften des "calling objects" zuzugreifen.

* Methoden haben nicht automatisch Zugriff auf andere interne Eigenschaften des aufrufenden Objekts.

* Der Wert von "this" hängt davon ab, woher der Zugriff auf "this" erfolgt.

* Wir können Pfeilfunktionen nicht als Methoden verwenden, wenn wir auf andere interne Eigenschaften zugreifen wollen.

* JavaScript-Objekte haben keinen eingebauten Datenschutz, sondern es gibt Konventionen, die man einhalten muss, um andere Entwickler über die Absicht des Codes zu informieren.

* Die Verwendung eines Unterstrichs vor einem Eigenschaftsnamen bedeutet, dass der ursprüngliche Entwickler nicht beabsichtigt hat, diese Eigenschaft direkt zu ändern.

* Setter- und Getter-Methoden ermöglichen detailliertere Möglichkeiten des Zugriffs auf und der Zuweisung von Eigenschaften.

* Factory-Funktionen ermöglichen es, Objektinstanzen schnell und wiederholt zu erstellen.

* Es gibt verschiedene Möglichkeiten, die Objektdestrukturierung zu verwenden: eine Möglichkeit ist die Kurzschrift für Eigenschaftswerte, eine andere die destrukturierte Zuweisung.

* Wie bei jedem Konzept ist es gut zu lernen, wie man die Dokumentation mit Objekten verwendet!

* In Objekten werden Sammlungen von Schlüssel-Wert-Paaren gespeichert.

* Jedes Schlüssel-Wert-Paar ist eine Eigenschaft - wenn eine Eigenschaft eine Funktion ist, wird sie als Methode bezeichnet.

* Ein Objektliteral besteht aus kommagetrennten Schlüssel-Wert-Paaren, die von geschweiften Klammern umgeben sind.

* Sie können auf eine Eigenschaft innerhalb eines Objekts zugreifen, sie hinzufügen oder bearbeiten, indem Sie die Punkt- oder Klammerschreibweise verwenden.

* Wir können Methoden zu unseren Objektliteralen hinzufügen, indem wir die Schlüssel-Wert-Syntax mit anonymen Funktionsausdrücken als Werte verwenden oder die neue ES6-Methodensyntax nutzen.

* Wir können durch komplexe, verschachtelte Objekte navigieren, indem wir Operatoren verketten.

* Objekte sind veränderbar - wir können ihre Eigenschaften ändern, auch wenn sie mit const deklariert sind.

* Objekte werden per Referenz übergeben - wenn wir Änderungen an einem Objekt vornehmen, das an eine Funktion übergeben wird, sind diese Änderungen dauerhaft.

* Wir können mit der For...in-Syntax durch Objekte iterieren.
