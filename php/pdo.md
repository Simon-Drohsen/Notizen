<h1>PDO</h1>

* PDO ist eine PHP-Erweiterung, die eine einheitliche Schnittstelle für den Zugriff auf verschiedene Datenbanken bietet.

* PDO unterstützt verschiedene Datenbanktreiber wie MySQL, PostgreSQL, SQLite und mehr.

* Die Verwendung von PDO bietet Vorteile wie Portabilität und Sicherheit durch vorbereitete Statements.

* Um eine Verbindung zur Datenbank herzustellen, verwendet man die PDO-Klasse und gibt den entsprechenden Datenbanktreiber, den Host, den Datenbanknamen und die Anmeldeinformationen an.

* PDO ermöglicht das Ausführen von SQL-Abfragen mit der Methode query() oder vorbereiteten Statements mit der Methode prepare().

* Vor der Ausführung einer Abfrage können Parameter in vorbereitete Statements eingefügt werden, um sicherzustellen, dass die Werte korrekt und sicher in die Abfrage eingefügt werden.

* PDO unterstützt das Arbeiten mit Transaktionen, wodurch mehrere Datenbankoperationen als atomare Einheit behandelt werden können.

* Fehler beim Datenbankzugriff können mit PDO durch das Abfangen von PDOExceptions gehandhabt werden.

* PDO bietet Funktionen zum Abrufen von Ergebnissen von Datenbankabfragen, wie z.B. das Abrufen von Ergebniszeilen als assoziative Arrays oder das Abrufen einzelner Werte.

* Durch die Verwendung von PDO können Datenbankverbindungen wiederverwendet werden, was die Leistung verbessern kann.

* fetch(PDO::FETCH_ASSOC): Diese Methode ruft eine einzelne Zeile aus dem Abfrageergebnis ab und gibt sie als assoziatives Array zurück. Jedes Array-Element entspricht einem Spaltenwert, der mit dem Spaltennamen als Schlüssel verknüpft ist.

* fetch(PDO::FETCH_NUM): Diese Methode ruft eine einzelne Zeile aus dem Abfrageergebnis ab und gibt sie als numerisches Array zurück. Jedes Array-Element enthält den Wert einer Spalte basierend auf dem numerischen Index.

* fetch(PDO::FETCH_BOTH): Diese Methode ruft eine einzelne Zeile aus dem Abfrageergebnis ab und gibt sie als Array zurück, das sowohl numerische als auch assoziative Indizes verwendet. Dadurch kann auf Spaltenwerte sowohl über den Spaltennamen als auch über den numerischen Index zugegriffen werden.

* fetchAll(PDO::FETCH_ASSOC): Diese Methode ruft alle Zeilen aus dem Abfrageergebnis ab und gibt sie als mehrdimensionales assoziatives Array zurück. Jedes Array-Element entspricht einer Zeile, und die Spaltenwerte werden mit den Spaltennamen als Schlüssel verknüpft.

* fetchAll(PDO::FETCH_NUM): Diese Methode ruft alle Zeilen aus dem Abfrageergebnis ab und gibt sie als mehrdimensionales numerisches Array zurück. Jedes Array-Element enthält den Wert einer Spalte basierend auf dem numerischen Index.

* fetchAll(PDO::FETCH_BOTH): Diese Methode ruft alle Zeilen aus dem Abfrageergebnis ab und gibt sie als mehrdimensionales Array zurück, das sowohl numerische als auch assoziative Indizes verwendet.
