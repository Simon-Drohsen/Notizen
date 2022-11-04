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
