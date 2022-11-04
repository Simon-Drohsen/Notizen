<h1>Front- und Backend Notizen</h1>

* Schnelleres Schreiben von Front-End-Code - das Laden von Vue in einer Zeile, Mustache-Templates, eingebaute Direktiven und wiederverwendbare Komponenten machen Vue leicht lesbar und einfach zu schreiben.

* Front-End-Code ist einfacher zu ändern und zu korrigieren - die Verwendung von lesbaren Mustache-Vorlagen, die Verwendung eingebauter, stark getesteter Direktiven und die Konsolidierung von sich wiederholendem Code in Komponenten machen den Vue-Code weniger fehleranfällig und einfacher zu beheben, wenn Fehler auftreten.

* Schnelle und reaktionsschnelle Frontend-Applikationen - Vue verwendet ein virtuelles DOM, so dass Website-Aktualisierungen nur dann erfolgen, wenn sie erforderlich sind, und dabei unglaublich schnell sind.

* data - wird zum Speichern bekannter dynamischer Werte verwendet.

* computed - dient zur Berechnung dynamischer Werte auf der Grundlage bekannter dynamischer Werte - kann zusätzlich einen Setter angeben, indem get- und set-Funktionen spezifiziert werden - der Setter aktualisiert andere dynamische Werte, wenn sich der berechnete Wert ändert.

* watch - wird für die Ausführung von Funktionen verwendet, wenn sich ein angegebener dynamischer Wert ändert.

* methods - zum Speichern von Instanzmethoden, die in der gesamten Anwendung verwendet werden sollen.

* Formularfelder können mit Hilfe der v-model-Direktive an Vue-Daten gebunden werden - wie v-model verwendet wird, hängt von der Art des Feldes ab, dem es hinzugefügt wird.

* Formular-Event-Handler können mit v-on:submit und v-on:reset hinzugefügt werden.

* Modifikatoren können verwendet werden, um Funktionalitäten zu Direktiven hinzuzufügen - am wichtigsten ist die Verhinderung des Neuladens der Seite beim Absenden des Formulars mit v-on:submit.prevent und die Bereinigung von Formularfeldwerten mit .number und .trim

* Formularvalidierung kann implementiert werden, indem der Wert des disabled-Attributs auf einem <button> mit v-bind auf den Wert einer berechneten Eigenschaft gesetzt wird.

* Wir haben gelernt, wie man mit v-bind:style mit einem style-Objekt oder einem Array von style-Objekten dynamisch Inline-Stile hinzufügt. Dann haben wir gelernt, wie man mit v-bind:class dynamisch Klassen mit einem Klassenobjekt oder einem Array von Klassenobjekten und Klassennamenstrings hinzufügt.

* Es mag den Anschein erwecken, als ob jede dieser Techniken für das dynamische Styling einer Front-End-Anwendung ausreichen würde - und das stimmt auch! Wenn Sie weiter über Vue lernen, werden Sie Vorteile und Anwendungsfälle für jede Technik sehen.

* Das Wichtigste, was Sie in diesem Stadium Ihrer Lernreise mitnehmen können, ist, dass Sie die Technik verwenden sollten, die Ihren Code am lesbarsten hält und Ihre App mit dem wenigsten sich wiederholenden Code zurücklässt.