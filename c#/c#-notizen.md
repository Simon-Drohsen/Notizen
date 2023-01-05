<h1>C# Notizen</h1>

* C# wird verwendet, um interaktive Websites, mobile Apps, Videospiele, erweiterte und virtuelle Realität (AR und VR), Back-End-Dienste und Desktop-Anwendungen zu erstellen.

* .NET bezieht sich im Allgemeinen auf die Familie von Programmen und Befehlen, mit denen mann Anwendungen mit C# erstellen können.

* Der Befehl Console.WriteLine() gibt Text auf der Konsole aus.

* Der Befehl Console.ReadLine() erfasst Benutzereingaben in der Konsole.

* Kommentare sind Codezeilen, die von Ihrem Computer ignoriert werden. Sie sollen stattdessen von Entwicklern gelesen werden. Mann kann sie mit // oder /*und*/ machen.

<h2>Ein paar Befehle sind:</h2>

* int - ganze Zahlen, wie: 1, -56, 948

* Double - Dezimalzahlen, wie: 239.43909, -660.01

* char - einzelne Zeichen, wie: „a“, „&“, „£“

* Zeichenfolge - Zeichenkette, wie: „Hund“, „Hallo Welt“

* bool - boolesche Werte, wie: wahr oder falsch

* Math.Abs() – findet den absoluten Wert einer Zahl. Beispiel: Math.Abs(-5) gibt 5 zurück.

* Math.Sqrt() – findet die Quadratwurzel einer Zahl. Beispiel: Math.Sqrt(16) gibt 4 zurück.

* Math.Round() – rundet das angegebene Double oder die Dezimalzahl auf die nächste ganze Zahl ab. Beispiel: Math.Floor(8.65) gibt 8 zurück.

* Math.Min() – gibt die kleinere von zwei Zahlen zurück. Beispiel: Math.Min(39, 12) gibt 12 zurück.

<h2>Hier erfährt man:</h2>

* Verwende arithmetische Operatoren, um Ausdrücke zu schreiben.

* Kombiniere Operatoren, um präzisere Programme zu schreiben.

* Verwende den Modulo-Operator (%), um Reste zu finden.

* Verwende integrierte Methoden, um komplexere Berechnungen durchzuführen.

* Verwende die Dokumentation, um neue Dinge nachzuschlagen.

* Speichere Zeichen- und Zeichenfolgenwerte in einer Variablen.

* Verwende das Additionssymbol (+), um Zeichenfolgen zu verketten.

* Interpoliere Saiten für eine einfachere Saitenkonstruktion.

* Finde Informationen über einen String mit .Length und .IndexOf().

* Erfasse Zeichen und Teile von Strings mit Klammern und .Substring().

* Verwende integrierte Methoden wie .ToUpper() und .ToLower(), um Zeichenfolgen zu bearbeiten.

<h2>Zu den Vergleichsoperatoren gehören:</h2>

* Gleich ==: gibt wahr zurück, wenn der Wert links gleich dem Wert rechts ist.

* Ungleichheitsoperator !=: gibt wahr zurück, wenn die beiden Werte nicht gleich sind.

* Kleiner als <: gibt wahr zurück, wenn der linke Wert kleiner als der rechte Wert ist.

* Größer als >: gibt wahr zurück, wenn der linke Wert größer als der rechte Wert ist.

* Kleiner oder gleich <=: gibt wahr zurück, wenn der linke Wert kleiner oder gleich dem rechten Wert ist.

* Größer als oder gleich >=: gibt wahr zurück, wenn der linke Wert größer oder gleich dem rechten Wert ist.

<h2>Hier erfährt man:</h2>

* die Schlüsselwörter if, else if und else verwenden, um bedingte Anweisungen zu schreiben.

* Switch-Anweisungen für Situationen schreiben, in denen es viele Bedingungen gibt.

* Verwenden von ternären Operatoren für kürzere bedingte Anweisungen.

* Rufe eine Methode mit ihrem Namen und Klammern auf: VisitPlanets();.

* den Rückgabewert einer Methode in einer Variablen speichern: double result = Math.Round(3.14159, 2);.

* Definiere eine grundlegende Methode mit der folgenden Syntax: static void VisitPlanets() {}.

* Jedes Mal, wenn eine Anwendung gestartet wird, wird die Methode Main() aufgerufen.

* An eine Methode übergebene Werte werden als Argumente bezeichnet. Wenn sie in der Methode definiert sind, sind sie Parameter.

* Methodenparameter können nur innerhalb des Methodenkörpers verwendet werden.

* Methodenparameter können optional sein, wenn man einen Standardwert mit equals = Syntax erhalten: static void VisitPlanets(int numberOfPlanets = 0).

* Übergebe beim Aufrufen einer Methode Argumente nach Position oder nach Namen. Wenn mann Namen verwenden, verwende die Doppelpunkt-Syntax (:): VisitPlanets(numberOfPlanets: 9);.

* Beim Überladen von Methoden können mehrere Methoden denselben Namen haben, solange mann unterschiedliche Methodensignaturen haben.

* Eine Methodensignatur besteht aus dem Namen einer Methode und den Parametertypen in dieser Reihenfolge.

<h2>Du hast gelernt:</h2>

* Methoden geben Werte mit dem Schlüsselwort return zurück.

* Jede Methode hat einen Rückgabetyp, der in ihrer Methodensignatur angegeben ist. Dieser Typ muss mit dem Typ des tatsächlich zurückgegebenen Werts übereinstimmen.

* Wenn eine Methode keinen Typ zurückgibt, ist ihr Rückgabetyp void.

* out-Parameter können verwendet werden, um mehrere Werte von einer Methode zurückzugeben.

<h3> Ausdruckskörper-Definitionen können für einzeilige Methodenkörper verwendet werden:</h3>

bool isEven(int num) => num % 2 == 0;.

<h3>Lambda-Ausdrücke können verwendet werden, um eine anonyme Methode zu erstellen:</h3>

* bool hasEvenNumbers = Array.Exists(numbers, (int num) => num % 2 == 0 );.

<h2>Man hat zwei „Unterabkürzungen“ innerhalb von Lambda-Ausdrücken gelernt:<h2>

<h3>Man kann den Parametertyp entfernen, wenn er abgeleitet werden kann:</h3>

* bool hasEvenNumbers = Array.Exists(numbers, (num) => num % 2 == 0 );.

<h3>Man kann die Klammern entfernen, wenn es einen Parameter gibt:</h3>
  
* bool hasEvenNumbers = Array.Exists(numbers, num => num % 2 == 0 );.

* Datenstrukturen und wie wir sie nutzen können, um unsere Daten besser zu organisieren.

* Wie man Werte in Arrays erstellt, auf sie zugreift und sie bearbeitet.

* Verwendung der integrierten Methoden der Array-Klasse, einschließlich Sort(), IndexOf() und Find().

* Eine Schleife ist eine Struktur in der Programmierung, bei der die Anweisungen einmal geschrieben werden, ein Computer sie jedoch mehrmals ausführen kann.

* Jede Ausführung dieser Anweisungen wird als Iteration bezeichnet.

* While-Schleifen werden wiederholt, bis sich eine Bedingung ändert.

* do...while-Schleifen werden einmal ausgeführt und dann wiederholt, bis sich eine Bedingung ändert.

* For-Schleifen wiederholen sich eine bestimmte Anzahl von Malen.

* Foreach-Schleifen werden für jedes Element in einer Sammlung wiederholt.

* Sprunganweisungen wie break, Continue und Return werden verwendet, um Schleifen zusätzlichen Kontrollfluss hinzuzufügen.
  
  <h2>man hat gelernt, wie man:</h2>

* Definiere eine Klasse.

* Instanziiere ein Objekt mit new.

* Definiere Felder, die Daten für jede Klasse.

* Definiere Eigenschaften, die Sprecher für jedes Feld.

* Definiere automatische Eigenschaften, die Abkürzung für das Erstellen von Eigenschaften.

* Definiere Methoden, die Aktionen, die eine Klasse ausführen kann.

* Definiere Konstruktoren, die speziellen Methoden, die aufgerufen werden, wenn eine Klasse instanziiert wird.

* Konstruktoren überladen und Code damit wiederverwenden.

* Kontrolliere den Zugriff auf Klassenmitglieder mit public und private.

* Im Allgemeinen bedeutet statisch "mit der Klasse verbunden, nicht mit einer Instanz".

* Der Zugriff auf ein statisches Mitglied erfolgt immer über den Klassennamen und nicht über den Instanznamen, wie bei Forest.Area.

* Eine statische Methode kann nicht auf nicht-statische Mitglieder zugreifen.

* Ein statischer Konstruktor wird einmal pro Typ ausgeführt, nicht pro Instanz. Er wird aufgerufen, bevor der Typ instanziiert wird oder auf ein statisches Mitglied zugegriffen wird.
  
* Eine statische Klasse kann nicht instanziiert werden. Der Zugriff auf ihre Mitglieder erfolgt über den Klassennamen, z. B. Math.PI.

  <h2>In dieser Lektion hat man gelernt:</h2>

* Dass Schnittstellen nützlich sind, um bestimmte Funktionen über mehrere Klassen hinweg zu garantieren.

* Eine Schnittstelle mit dem Schlüsselwort interface erstellt.

* Eigenschaften und Methoden (aber keine Konstruktoren oder Felder) in der Schnittstelle definiert.

* Klassen erstellt, die die Schnittstelle implementieren.

* Hinzufügen von Elementen zu den Klassen, die nicht in der Schnittstelle angegeben waren.

* Die Vererbung ist eine Möglichkeit, Duplikation über mehrere Klassen hinweg zu vermeiden.

* Bei der Vererbung erbt eine Klasse die Mitglieder einer anderen Klasse.
  
* Die Klasse, die erbt, wird Unterklasse oder abgeleitete Klasse genannt. Die andere Klasse wird als Oberklasse oder Basisklasse bezeichnet.

* Auf die Mitglieder einer Oberklasse kann man mit base zugreifen. Dies ist sehr nützlich, wenn der Konstruktor der Oberklasse aufgerufen wird.

* Mit protected kann der Zugriff auf eine Oberklasse und ihre Unterklassen eingeschränkt werden.

* Mit virtual und override kann ein Mitglied einer Oberklasse überschrieben werden.

* Mit abstract kann ein Mitglied einer Oberklasse ohne Definition seiner Implementierung erstellt werden. Dies ist nützlich, wenn die Implementierung in jeder Unterklasse anders sein wird.
  
* Klassen und Schnittstellen sind Referenztypen.
  
* Eine Variable dieses Typs enthält einen Verweis auf die Daten, nicht die Daten selbst. Dies unterscheidet sich von Werttypen wie int und bool.

* Der Gleichheitsoperator (==) verwendet einen referenziellen Vergleich für Referenztypen und einen Wertvergleich für Werttypen.

* Für ein einzelnes Objekt können mehrere Referenzen erstellt werden.

* Ein Verweis und das zugehörige Objekt müssen nicht vom gleichen Typ sein. Zum Beispiel kann man auf ein Objekt einer Unterklasse durch eine geerbte Oberklasse oder eine implementierte Schnittstellenreferenz verweisen.

* Die für eine Objektreferenz verfügbare Funktionalität wird durch den Typ der Referenz bestimmt, nicht durch den Typ des Objekts.

* Polymorphismus ist die Möglichkeit, in der Programmierung dieselbe Schnittstelle für unterschiedliche Datentypen zu verwenden.

* Die Referenzierung eines Objekts durch einen geerbten Typ oder eine implementierte Schnittstelle wird als Upcasting bezeichnet. Es kann implizit erfolgen.

* Die Referenzierung eines Objekts durch eine abgeleitete Klasse wird als Downcasting bezeichnet und muss explizit gemacht werden, indem der Typname in Klammern hinzugefügt wird. Es kann einen InvalidCastException-Fehler verursachen, wenn der Code ausgeführt wird

* Um zu signalisieren, dass eine Referenz "leer" ist oder sich auf kein Objekt bezieht, setzen wir sie auf null

* Wenn ein Verweis nicht auf einen Wert gesetzt wird, ist er nicht zugewiesen und kann keine Operationen durchführen.

* Jeder Typ erbt schließlich von Object.

* Object-Mitglieder umfassen Equals(), ToString() und GetType().

* Die Methode ToString() ermöglicht es Console.WriteLine(), für alle Typen zu funktionieren.

* Der Typ String oder Zeichenkette ist ein Referenztyp.

* Strings sind unveränderlich, d. h. sie können nach ihrer Erstellung nicht mehr geändert werden.

* Unveränderlich zu sein bedeutet auch, dass eine String-Referenz immer auf das ursprüngliche Objekt verweist, so dass die "Änderung" einer Referenz auf einen String keine Auswirkungen auf andere Referenzen auf diesen hat.

* Mit dem Gleichheitsoperator (==) werden Strings auf Wert- und nicht auf Referenzgleichheit geprüft.

* Eine String-Variable kann nicht zugewiesen, null oder leer sein. Leere Strings können durch String.Empty oder "" dargestellt werden - sie sind gleichwertig.

* Eine Liste, oder List<T>, ist eine allgemeine, sequentielle Datenstruktur. Der spezifische Typ, den sie enthält, wird bei der Instanziierung angegeben.

* Listen sind praktisch unbegrenzt. Sie "wachsen" und "schrumpfen", wenn die Anzahl der Elemente steigt und fällt.

* Auf Listenwerte kann mit Hilfe von eckigen Klammern über einen Index zugegriffen werden: [ ].

* Um eine leere Liste zu erstellen, verwenden Sie einen einfachen Konstruktor. Um eine Liste mit Werten zu erstellen, verwenden Sie die Objektinitialisierung.

* Add() wird verwendet, um ein Element zu einer Liste hinzuzufügen.

* Remove() wird verwendet, um ein Element aus der Liste zu entfernen. Sie gibt true zurück, wenn sie erfolgreich ist, andernfalls false.

* Count ist die Anzahl der Elemente im Array.

* Contains() gibt true zurück, wenn das Argument in der Liste vorhanden ist, andernfalls false.

* Eine Sequenz innerhalb einer Liste wird als Bereich bezeichnet. Es gibt spezifische Methoden für die Arbeit mit Bereichen, einschließlich GetRange(), AddRange(), InsertRange() und RemoveRange().

* Listen sind eine Art von generischen Sammlungen, die mit generischen Typparametern definiert werden. Die Typparameter werden bei der Instanziierung jeder generischen Klasse angegeben.

* LINQ ist ein Satz von Sprach- und Framework-Funktionen zum Schreiben strukturierter, typsicherer Abfragen über lokale Objektsammlungen und entfernte Datenquellen.

* Verwenden Sie LINQ, indem Sie den System.Linq-Namensraum in Ihrer Datei referenzieren.

* Wenn eine LINQ-Abfrage eine Folge von Elementen zurückgibt, ist ihr Typ IEnumerable<T>. Das heißt, sie funktioniert mit foreach-Schleifen und ihre Länge ist mit Count() zugänglich.

* Speichern Sie das Ergebnis einer Abfrage in einer Variablen des Typs var. var ist ein impliziter Typ, d. h. er erhält alle Vorteile der Typüberprüfung, ohne dass wir den tatsächlichen Typ angeben müssen.

* LINQ-Abfragen können in Methodensyntax oder Abfragesyntax geschrieben werden.

* Wir bevorzugen die Methodensyntax für einzelne Operationen und die Abfragesyntax für fast alles andere.

* Der Where-Operator wird verwendet, um bestimmte Elemente aus einer Sequenz auszuwählen.

* Der Select-Operator bestimmt, was für jedes Element in der Sequenz zurückgegeben wird.

* Der from-Operator deklariert eine Bereichsvariable, die zum Durchlaufen der Sequenz verwendet wird.

* LINQ kann neben anderen Datentypen auch auf Arrays und Listen angewendet werden.

* Man kann Klassen erstellen, damit der Code übersichtlicher wird.
  
* Mit TryParse wird automatisch geschaut ob man das eingegeben hatt was man sollte. Wenn nicht wird nachgefragt.
  
* DateTime ist sehr nützlich wenn man ein Datum ausgeben möchte.
