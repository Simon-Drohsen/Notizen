<h1>Interaktive Websites mit JavaScript bauen</h1>

* HTML erstellt das Grundgerüst einer Webseite, aber JavaScript sorgt für Interaktivität

* Das <\script>-Element hat einen öffnenden und einen schließenden Tag. Sie können JavaScript-Code zwischen den öffnenden und schließenden <\script>-Tags einbetten.

* Mit dem src-Attribut im öffnenden <\script>-Tag können Sie auf externe JavaScript-Dateien verweisen.

* Standardmäßig werden Skripte geladen und ausgeführt, sobald der HTML-Parser auf sie in der HTML-Datei stößt. Der HTML-Parser wartet, bis das gesamte Skript geladen ist, bevor er mit der Analyse der übrigen Seitenelemente fortfährt.

* Das Attribut defer stellt sicher, dass die gesamte HTML-Datei geparst wurde, bevor das Skript ausgeführt wird.

* Das async-Attribut ermöglicht es dem HTML-Parser, mit dem Parsen fortzufahren, während das Skript heruntergeladen wird, aber es wird sofort nach dem Herunterladen ausgeführt.