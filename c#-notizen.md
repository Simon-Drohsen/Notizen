<h1>C# Notizen</h1>

* C# wird verwendet, um interaktive Websites, mobile Apps, Videospiele, erweiterte und virtuelle Realität (AR und VR), Back-End-Dienste und Desktop-Anwendungen zu erstellen.

* .NET bezieht sich im Allgemeinen auf die Familie von Programmen und Befehlen, mit denen mann Anwendungen mit C# erstellen können.

* Der Befehl Console.WriteLine() gibt Text auf der Konsole aus.

* Der Befehl Console.ReadLine() erfasst Benutzereingaben in der Konsole.

* Kommentare sind Codezeilen, die von Ihrem Computer ignoriert werden. Sie sollen stattdessen von Entwicklern gelesen werden. Mann kann sie mit // oder /* und */ machen.

<h2>Ein paar Befehle sind:</h2>

* int - ganze Zahlen, wie: 1, -56, 948

* Double - Dezimalzahlen, wie: 239.43909, -660.01

* char - einzelne Zeichen, wie: „a“, „&“, „£“

* Zeichenfolge - Zeichenkette, wie: „Hund“, „Hallo Welt“

* bool - boolesche Werte, wie: wahr oder falsch

* Math.Abs() – findet den absoluten Wert einer Zahl. Beispiel: Math.Abs(-5) gibt 5 zurück.

* Math.Sqrt() – findet die Quadratwurzel einer Zahl. Beispiel: Math.Sqrt(16) gibt 4 zurück.

* Math.Floor() – rundet das angegebene Double oder die Dezimalzahl auf die nächste ganze Zahl ab. Beispiel: Math.Floor(8.65) gibt 8 zurück.

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

<h3>Ausdruckskörper-Definitionen können für einzeilige Methodenkörper verwendet werden:</h3>

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
