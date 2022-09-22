<h1>Css Notizen</h1>

* The basic anatomy of CSS syntax written for both inline styles and stylesheets.

* Die gewöhnlichsten CSS Begriffe sind: ruleset, selector, und declaration.

* CSS "inline styles" können in einem HTML Dokument geschrieben werden wenn man das "style" Attribut verwendet. can be written inside the opening HTML tag using the style attribute.

* "inline styles" können dafür verwendet werden um ein HTML Dokument zu stylen, aber es ist nicht die beste übung.

* Ein "internal stylesheet" wird durch ein <style> Element geschrieben, das in einem <head> Element ist. und das in einem HTML Dokument.

* "internal stylesheets" können auch dazu verwendet werden um ein HTML Dokument zu stylen sind aber auch nicht die beste Übung.

* Ein "external stylesheet" seperiert einen CSS code von einem HTMLDokument, in dem es eine .css erweiterung benutzt.

* "external stylesheets" sind der beste Ansatz um ein HTML Dokument zu stylen.

* "external stylesheets" sind mit dem <link> Element verbunden zum HTML Dokument.

* CSS kann HTML Elemente auswählen, wie zum Beispiel "type", "class", "ID","attribute".

* Alle Elemente können mit dem "universal selector" ausgewählt werden.

* Ein Element kan mit dem "pseudo-class selector" verschiedene Zustände haben.

* Es können mehrere "CSS classes" in ein HTML Dokument sein.

* "Classes" kann man an verschiedenen Orten gebrauchen un "ID's" können nur einmal gebraucht werden.

* "ID's" sind spezifischer als "classes" und "classes" sin spezifischer als "type". Das heisst "ID's" können "styles"  von "classes" überschreiben und "classes" können "styles" von "type" überschreiben.

* Mehrere "selectors" können miteinander verkettet werden, um ein Element auszuwählen. Dies erhöht die Spezifität, kann aber notwendig sein.

* Verschachtelte Elemente können ausgewählt werden, indem "selectors" durch ein Leerzeichen getrennt werden.

* Mehrere unabhängige "selectors" können dieselben "styles" haben, indem die "selector"-namen durch Kommas getrennt werden.

* Das Attribut "font-family" definiert die Schriftart eines Elements.

* "font-size" steuert die Größe des angezeigten Textes.

* "font-weight" definiert, wie dünne oder dicke Text angezeigt wird.

* Das Attribut "text-align" platziert Text links, rechts oder in der Mitte seines übergeordneten Containers.

* Text kann zwei verschiedene Farbattribute haben: Farbe und Hintergrundfarbe. "color" definiert die Farbe des Textes, während "background-color" die Farbe hinter dem Text definiert.

* CSS kann ein Element mit dem Attribut "opacity()" transparent machen.

* CSS kann mit dem Attribut "background-image" auch den Hintergrund eines Elements auf ein Bild setzen.

* Das "!important-Flag" überschreibt jeden Stil, sollte jedoch fast nie verwendet werden, da es extrem schwierig ist, es zu überschreiben.

* Das Box-Modell besteht aus einer Reihe von Attributen, die verwendet werden, um Platz um und zwischen HTML-Elementen zu schaffen.

* Die Höhe und Breite eines Inhaltsbereichs kann in Pixeln oder Prozent angegeben werden.

* Rände umgeben den "content" und das "padding" eines Elements. Die Farbe, der Stil und die Dicke eines Randes können mit CSS Attribut festgelegt werden.
 
* "padding" ist der Abstand zwischen dem "content" und dem Rand. Es kann in Pixel oder Prozent angegeben werden.

* "margin" ist der Abstand ausserhalb des Randes eines Elements.

* Horizontale Ränder werden addiert, sodass der Gesamtabstand zwischen den Rändern benachbarter Elemente gleich der Summe des rechten Rands eines Elements und des linken Rands des benachbarten Elements ist.

* Vertikale Ränder fallen zusammen, sodass der Abstand zwischen vertikal benachbarten Elementen gleich dem größeren Rand ist.

* "margin: 0 auto" zentriert ein Element horizontal innerhalb seines übergeordneten Inhal"contents", wenn es eine Breite hat.

* Das "Overflow" Attribut kann so eingestellt werden, display, hide, oder scroll, und es diktiert das HTML wie es den "content" behandeln soll der über den "parentcontent" überlaufen.

* Das "visibility" Attribut kann Elemente ein- oder ausblenden.

* Mit dem "position" Attribut kann man die Position eines Elements angeben.

* Wenn "position" auf "relativ" gestellt ist, ist die Standartsposition relativ auf der Website.

* Wenn "position" auf "absolute" gestellt ist, dann ist ein Element relativ zum "parent" Element.

* Wenn "position" auf "fixed" gestellt ist, wird der "content" immer im Sichtfeld bleiben, egal ob man scrollt oder nicht.

* Wenn "position" auf "sticky" gestellt ist, dann bleibt es immer beim "parentcontainer".

* Der Z-Index eines Elements gibt an, wie weit hinten oder wie weit vorne ein Element auf der Seite erscheint, wenn es andere Elemente überlappt.

* Mit der Anzeigeeigenschaft können Sie steuern, wie ein Element vertikal und horizontal in einem Dokument fließt.

* Inline-Elemente nehmen so wenig Platz wie möglich ein und können weder in der Breite noch in der Höhe manuell angepasst werden.

* Blockelemente nehmen die Breite ihres Containers ein und können manuell in der Höhe angepasst werden.

* Inline-Block-Elemente können festgelegte Breite und Höhe haben, sie können aber auch nebeneinander erscheinen und nicht ihre gesamte Containerbreite einnehmen.

* Die Float-Eigenschaft kann Elemente auf einer Webseite so weit links oder so weit rechts wie möglich verschieben.

* Mit der clear-Eigenschaft können Sie die linke oder rechte Seite eines Elements (oder beide) löschen.

* Benannte Farben – es gibt mehr als 140 benannte Farben, die Sie hier überprüfen können.

* Hexadezimal- oder Hex-Farben

* Hexadezimal ist ein Zahlensystem mit sechzehn Ziffern, 0 bis 9, gefolgt von „A“ bis „F“.

* Hex-Werte beginnen immer mit # und geben Werte für Rot, Blau und Grün mit Hexadezimalzahlen wie #23F41A an.

* Sechsstellige Hexadezimalwerte mit doppelten Werten für jeden RGB-Wert können auf drei Ziffern gekürzt werden.


* <h2>RGB</h2>


#ffffff #000000

* RGB-Farben verwenden die rgb()-Syntax mit einem Wert für Rot, einem Wert für Blau und einem Wert für Grün.

* RGB-Werte reichen von 0 bis 255 und sehen so aus: rgb(7, 210, 50).

* RGBA heißt Rot Grün Blau Alpha


* <h2>HSL</h2>


* HSL steht für Farbton (die Farbe selbst), Sättigung (die Intensität der Farbe) und Helligkeit (wie hell oder dunkel eine Farbe ist).

* Farbton reicht von 0 bis 360 und Sättigung und Helligkeit werden beide als Prozentsätze wie folgt dargestellt: hsl(200, 20 %, 50 %).

* Sie können der Farbe in RGB und HSL Deckkraft hinzufügen, indem Sie einen vierten Wert hinzufügen, a, der als Prozentsatz dargestellt wird.

* Typografie ist die Kunst, Text auf einer Seite anzuordnen.

* Text kann mit der Eigenschaft font-weight fett oder dünn erscheinen.

* Text kann mit der Eigenschaft font-style kursiv dargestellt werden.

* Der vertikale Abstand zwischen Textzeilen kann mit der Eigenschaft line-height geändert werden.

* Serifenschriften haben zusätzliche Details am Ende jedes Buchstabens. Sans-Serif-Schriftarten nicht.

* Fallback-Schriftarten werden verwendet, wenn eine bestimmte Schriftart nicht auf dem Computer eines Benutzers installiert ist.

* Die Wortabstandseigenschaft ändert, wie weit einzelne Wörter voneinander entfernt sind.

* Die Eigenschaft Buchstabenabstand ändert, wie weit einzelne Buchstaben voneinander entfernt sind.

* Die Eigenschaft text-align ändert die horizontale Ausrichtung von Text.

* Google Fonts bietet kostenlose Schriftarten, die in einer HTML-Datei mit dem <link>-Tag oder der @font-face-Eigenschaft verwendet werden können.

* Lokale Schriftarten können einem Dokument mit der Eigenschaft @font-face und dem Pfad zur Quelle der Schriftart hinzugefügt werden.

* grid-template-columns definiert die Anzahl und Größe der Spalten des Grids

* grid-template-rows definiert die Anzahl und Größe der Zeilen des Grids

* grid-template ist eine Abkürzung für die Definition von grid-template-columns und grid-template-rows in einer Zeile

* row-gap setzt Leerzeichen zwischen die Zeilen des Rasters

* column-gap setzt Leerzeichen zwischen die Spalten des Gitters

* Lücke ist eine Abkürzung für die Definition von Reihenlücken und Spaltenlücken in einer Zeile

* grid-row-start und grid-row-end sorgen dafür, dass Elemente bestimmte Zeilen des Grids überspannen

* grid-column-start und grid-column-end sorgen dafür, dass Elemente bestimmte Spalten des Grids überspannen

* grid-area ist eine Abkürzung für grid-row-start, grid-column-start, grid-row-end und grid-column-end, alles in einer Zeile

* Grid-Template-Areas gibt Grid-Namen Grid Areas an

* Grid-Layouts sind zweidimensional: Sie haben eine Zeilen- oder Inline-Achse und eine Spalten- oder Blockachse.

* justify-items gibt an, wie einzelne Elemente über die Zeilenachse verteilt werden sollen

* justify-content gibt an, wie Gruppen von Elementen über die Zeilenachse verteilt werden sollen

* justify-self gibt an, wie sich ein einzelnes Element in Bezug auf die Zeilenachse positionieren soll

* align-items gibt an, wie einzelne Elemente über die Spaltenachse verteilt werden sollen

* align-content gibt an, wie Gruppen von Elementen über die Spaltenachse verteilt werden sollen
 
* align-self gibt an, wie sich ein einzelnes Element in Bezug auf die Spaltenachse positionieren soll

* grid-auto-rows gibt die Höhe der Zeilen an, die implizit zum Grid hinzugefügt werden

* grid-auto-columns gibt die Breite der Spalten an, die dem Grid implizit hinzugefügt werden

* grid-auto-flow gibt an, in welcher Richtung implizite Elemente erstellt werden sollen.

 <h2>CSS-Übergänge bestehen aus 4 Komponenten:</h2>

    * Eine Eigenschaft, die übergehen wird.

    * Die Dauer, die beschreibt, wie lange der Übergang dauert.

    * Die Verzögerung zum Anhalten, bevor der Übergang stattfindet.

    * Die Timing-Funktion, die die Beschleunigung des Übergangs beschreibt.

* Die Größe von Inhalten auf einer Website kann relativ zu anderen Elementen auf der Seite mithilfe von relativen Maßen angepasst werden.

* Die Einheit der em-Größen-Schriftart relativ zur Schriftgröße eines übergeordneten Elements.

* Die Einheit der Rem-Größen-Schriftart relativ zur Schriftgröße eines Wurzelelements. Dieses Wurzelelement ist das <html>-Element.

* Prozentsätze werden häufig verwendet, um Eigenschaften von Boxmodellen wie Breite, Höhe, Polsterung oder Rand eines Elements zu skalieren.

* Wenn Prozentsätze zur Größenanpassung von Breite und Höhe verwendet werden, werden die untergeordneten Elemente relativ zu den Abmessungen ihrer übergeordneten Elemente skaliert (denken Sie daran, dass die Abmessungen der übergeordneten Elemente zuerst festgelegt werden müssen).

* Prozentsätze können verwendet werden, um Auffüllung und Rand einzustellen. Die horizontale und vertikale Auffüllung und der Rand werden relativ zur Breite eines übergeordneten Elements festgelegt.

* Die minimale und maximale Breite der Elemente kann mit min-width und max-width eingestellt werden.

* Die minimale und maximale Höhe der Elemente kann mit min-height und max-height eingestellt werden.

* Wenn die Höhe eines Bildes oder Videos eingestellt ist, kann seine Breite auf automatisch eingestellt werden, sodass die Medien proportional skaliert werden. Das Umkehren dieser beiden Eigenschaften und Werte führt ebenfalls zum gleichen Ergebnis.

* Ein Hintergrundbild eines HTML-Elements wird proportional skaliert, wenn seine Eigenschaft background-size auf cover eingestellt ist.


<h2>CSS-Variablen</h2>


* Variablen verringern die Notwendigkeit, Eigenschaftswerte zu wiederholen, und erleichtern das Lesen von CSS-Code.

* Sie können Variablen in CSS verwenden, um Werte zu speichern.

* Die Variablendeklaration muss mit einem doppelten Bindestrich (--) beginnen.

* Variablen müssen als Werte für CSS-Eigenschaften verwendet werden.

* Variablen müssen als Argument innerhalb der Funktion var() verwendet werden.

* Variablen unterliegen sowohl dem Geltungsbereich als auch der Vererbung.

* Variablen mit globalem Geltungsbereich werden innerhalb der Pseudoklasse :root definiert.

* Das Überschreiben einer Variablen erfolgt durch Neudefinition des Werts dieser Variablen innerhalb des gewünschten Selektor-Regelsatzes.

* Fallback-Werte können verwendet werden, um einen Backup-Wert bereitzustellen, wenn die ursprüngliche Variable ungültig ist.

* Mehrere Fallback-Werte können bereitgestellt werden, indem weitere Werte innerhalb von kaskadierenden var()-Funktionen hinzugefügt werden.

* Responsiv gestaltete Webseiten können erstellt werden, indem Variablen mit Medienabfragen kombiniert werden.

<h2>CSS-Funktionen</h2>

* Variablen verringern die Notwendigkeit, Eigenschaftswerte zu wiederholen, und machen CSS-Code leichter lesbar.

* Funktionen sind eine Art CSS-Wert, der anstelle eines hartcodierten Werts in eine CSS-Eigenschaft eingefügt wird

* Die Funktion url() wird verwendet, um Ressourcen in das Stylesheet zu laden.

* Sie können die Funktion calc() verwenden, um einfache mathematische Operationen an Elementen durchzuführen.

* Die Funktion min() kann verwendet werden, um den kleinsten Wert aus einer Reihe von Werten auszuwählen und diesen Wert für eine Eigenschaft festzulegen.

* Die Funktion max() kann verwendet werden, um den größten Wert aus einer Reihe von Werten auszuwählen und diesen Wert für eine Eigenschaft festzulegen.

* Sie können die Funktion clamp() verwenden, um sicherzustellen, dass der Eigenschaftswert nach oben und unten skaliert wird, während Sie zwischen einer Ober- und einer Untergrenze bleiben.

* Vollständig deckende Farbwerte können mit den Funktionen rgb() und hsl() gesetzt werden.

* Farbwerte, die einen unterschiedlichen Alpha-Level benötigen, können mit den Funktionen rgba() und hsla() gesetzt werden.

* Sie können Filterfunktionen verwenden, um das Erscheinungsbild von Eingabebildern und -elementen zu ändern.

* Die Funktionen drop-shadow(), blur() und bright() führen jeweils unterschiedliche Arten der Elementfilterung durch.

* Sie können Transformationsfunktionen verwenden, um Bildpositionierung, Skalierung, Drehung und mehr zu manipulieren.

* Die Funktionen scale(), rotate() und translate() ermöglichen jeweils spezifische Transformationsarten.

* Der Text soll mindestens 18px gross sein und die "line-height" soll 1.5 gross sein.

* der Farben Kontrast soll mindestens 4.5:1 für standart Texte sein.

* Interaktive Elemente sollten ein Zeichen haben das sie Interaktiv sind wie unterstrichen oder so.

* Abgekürzte Sachen sind immer in einem <abbr> Element.

* "visibility: hidden" oder "display: none" verstecken Texte von allen Usern.

* Die visuelle Anzeige sollte die Struktur der präsentierten Elemente innerhalb des HTML widerspiegeln, um Navigationskohärenz für unterstützte und nicht unterstützte Benutzer bereitzustellen.

* Designe Websiten immer für verschiedene grössen.

* Mit Tools wie caniuse.com können wir überprüfen, ob eine CSS-Funktion in bestimmten Browsern verfügbar ist.

* Browser haben Standardstile, die wir mit Ressourcen wie browserdefaultstyles.com überprüfen können.

* Manchmal müssen wir browserspezifische Präfixe verwenden, insbesondere für neue CSS-Funktionen.

* Polyfills bieten eine Möglichkeit, neuere Webfunktionen in älteren Browsern zu unterstützen.

* Stile hinzugefügt, um Links erkennbar und von gewöhnlichem Text unterscheidbar zu machen.

* Linkstile hinzugefügt, die vom Mausinteraktionsstatus abhängen und Benutzern ein visuelles Feedback für das Bewegen des Cursors und Mausklicks geben.

* Zusätzlicher Kontexttext mit dem HTML-Titelattribut hinzugefügt.

* Gestaltete Schaltflächen, die leicht erkennbar sind (sowohl in skeuomorphen als auch in flachen Designstilen), indem sie Kästchenformen, Rahmen, Hover und aktive Zustände verwenden.

* Verwenden Sie Breadcrumbs, um anzuzeigen, wo sich ein Benutzer befindet und wie groß die Website ist

* Breadcrumbs werden mithilfe von ungeordneten Listen in HTML mit benutzerdefiniertem CSS-Stil implementiert

<h2>Es gibt drei Arten von "Breadcrumbs":</h2>

    * Standort - basierend auf der hierarchischen Struktur der Website

    * Attribut - basierend auf Attributen der aktuellen Seite oder des aktuellen Elements

    * Pfad - einzigartig für die Reise eines Benutzers auf der Website

* Pfadbasierte Breadcrumbs können verwirrend sein, verwenden Sie sie nur bei Bedarf

* Stellen Sie sicher, dass Breadcrumbs einen Mehrwert bringen, bevor Sie sie zu einer Website hinzufügen
