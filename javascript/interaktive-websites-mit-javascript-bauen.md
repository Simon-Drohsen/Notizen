<h1>Interaktive Websites mit JavaScript bauen</h1>

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
