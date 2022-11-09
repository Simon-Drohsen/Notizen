<h1>Ethernet</h1>

<h2>A) Was versteht man unter Ethernet?</h2>

* Ethernet ist eine Technolgie die zum verbinden von Computern oder Netzwerken dient.

<h2>B) Wie hat alles angefangen?</h2>

Ethernet wurde als Bustopologie erfunden. Das heisst wenn ein Gerät die Verbindung unterbrach war das ganze Netzwerk tot.

<h2>C) Weiterentwicklung bis heute?</h2>

Heutzutage haben wir Switches und Hubs die das Ethernet viel einfacher machen.

<h2></h2>Was versteht man unter Ethernet?</h2>
* Ethernet ist eine Technik die Software (Protokolle) und Hardware (Kabel, Verteiler, Netzwerkkarten) für kabelgebundene Datennetze spezifiziert. Dass alles geschieht in einem Rahmen (Ethernet Frame).

* CS = Carriere Sense: Alle Teilnehmer überwachen das Medium.

* MA = Multiple Acces: Jeder darf das Netzwerk nutzen.

* CD = Collision Detection: Kollisionen werden erkannt.

<h1>Osi Modell</h1>

<h2>Was ist ein OSI Modell?</h2>

* OSI = Standart, der dafür sorgt, dass diese Aufgabe bewältigt wird.

* OSI = Open Systems Interconection

* Referenzmodell für Kommunikation zwischen Technischen Systemen

<h3>Kommunikation = viele unterschiedliche Aufgaben z.B Probleme</h3>

* Übertragung der Daten im lokalen Netz

* Wegfindung im Internet

* Ist alles angekommen?

* Sind die Daten korrekt angekommen?

* Für welche Anwendung ist ein Nachricht?

<h2>Wie ist das Osi Modell aufgebaut?</h2>

![Schichtenmodell](../images/schichtenmodell_m117.png)

![Erklärung des Schichtenmodells](../images/schichtenmodell_erklaerung.png)

<h2>Wie arbeitet ein Hub?</h2>

<h4>Die Nachricht von PC-A ist an PC-B adressiert. Der Hub wird jedoch das Packet an alle angeschlossene PCs senden.</h4>

* «Sharedmedium» Prinzip

* Das Medium ist Belegt

* Alle anderen müssen warten

* Der Datendurchsatz ist nicht sohoch

* Es kommt zu vielen Kollisionen

![Wie arbeitet ein Hub?](../images/arbeitsweise_hub.png)

<h2>Wie arbeitet ein Switch?</h2>

<h4>Die Nachricht von PC-A ist an PC-B adressiert. Der Hub wird jedoch das Packet an alle angeschlossene PCs senden.</h4>

* Dot-Matrix-Logik 

* Dedizierte Leitung von A zu D

* B und C könnten gleichzeitig Kommunizieren

* Es sind also mehrerer parallele Verbindungen möglich

* Jedes angeschlossene Gerät bildetseine eigene Kollisionsdomäne(Mikrosegmentierung)

* Bei einem Switch können quasi keine Kollisionen mehr stattfinden

![Wie arbeitet ein Switch?](../images/funktionsweise_switch.png)

<h2>Arbeitsweise eines Switchs</h2>

<h4>Der Switch ist nach dem erstmaligen Einschalten noch nicht in der Lage, dedizierte Verbindungen herzustellen! Denn er betreibt eine SAT, sogenannt «Source AddressTable»</h4>

![Wie arbeitet ein Switch?](../images/Arbeitsweise_switch.png)

<h2>SAT</h2>

![Wie arbeitet ein Switch?](../images/sat_tabelle.png)