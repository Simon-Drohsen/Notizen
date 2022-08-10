Notizen zur Website


1. Worum geht es auf meiner Website?                                              Star Wars
3. Welche Informationen zeige ich zu meinem Thema?                    Charakterbeschreibungen, Zusammenfassungen der Story, Planeten, verschiedene Schiffe
4. Wie soll meine Website aussehen?                                                  Dunkel, Simple, formale Schriftart, subtil






1. Website skizzieren *
2. Inhalte und aussehen bestimmen
    1. Text schreiben
    2. Hauptfarbe wählen
    3. Bilder auswählen
        1. Haben Sie ein Bild gefunden, das Sie nutzen möchten, machen Sie folgendes bei Google Images:
        2. Klicken Sie auf das Bild.Wählen Sie "Bild ansehen“.
        3. Klicken Sie mit der rechten Maustaste auf das Bild und wählen Sie "Grafik speichern unter…" oder kopieren Sie die Internetaddresse des Bildes und speichern diese ab.
3. Gehen Sie auf Google Fonts und scrollen Sie durch die Liste bis Sie eine Schriftart entdecken, welche Sie mögen. Sie können auch die Filter auf der rechten Seiten nutzen, um die Auswahl zu filtern.
4. Klicken Sie den "+" Button bei der gewünschten Schriftart.
5. Es erscheint eine Popup-Box. Klicken Sie auf den "* Family Selected" Button im unteren Bereich der Seite. ("*" abhängig davon wieviele Fonts man ausgewählt hat).
6. In der Popup-Box stehen jetzt zwei Codes. Diese können Sie kopieren und in einem beliebigen Texteditor für später speichern.


Einen Ordner für alle Webprojekte machen, im Webprojekte Ordner einen Ordner nur für diese Website erstellen, Index.html im VS Code erstellen, Bider Ordner, Styles Ordner (CSS-Dateien), Scripts Ordner (), 

Index.html

<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>w-vision</title>
    <link href="assets/style.css" rel="stylesheet" type="text/css">
  </head>
  <body>
    <h1>w-vision ist cool</h1>

    <img class="vader" src="assets/logos/w-vision.svg"   alt="w-vision Logo: Es steht w-vison in Blau und unter dem text steht klein Webentwicklung. ">
    <p>In w-vision, sind wir eine Gemeinschaft aus</p>

    <ul>
      <li>Experten</li>
      <li>Denkern</li>
      <li>Machern</li>
    </ul>
    <p>Lest die Website <a href="https://w-vision.ch/de">w-vision</a> durch um mehr über meinen Lehrbetrieb zu erfahren.</p>
    <button>Name ändern</button>
    <script src="assets/main.js"></script>
  </body>
</html>


style.css

html {
    font-size: 10px;
    font-family: 'Lado', sans-serif;
  }
  
.vader {
  width: 300px;
}


h1 {
  font-size: 60px;
  text-align: center;
}

p, li {
  font-size: 16px;
  line-height: 2;
  letter-spacing: 1px;
}


html {
  background-color: rgb(93, 93, 93);
}

body {
  width: 600px;
  margin: 0 auto;
  background-color: #00b7ff;
  padding: 0 20px 20px 20px;
  border: 5px solid rgb(93, 93, 93);
}

h1 {
  margin: 0;
  padding: 20px 0;
  color: rgb(93, 93, 93);
  text-shadow: 3px 3px 1px black;
}
img {
  display: block;
  margin: 0 auto;
}


main.js

var myHeading = document.querySelector('h1');
myHeading.textContent = 'Hallo Michis!';


var myImage = document.querySelector('img');

myImage.onclick = function() {
    var mySrc = myImage.getAttribute('src');
    if(mySrc === 'assets/logos/w-vision.svg') {
        myImage.setAttribute('src','assets/star_wars_logo.png');
    } else {
      myImage.setAttribute('src','assets/logos/w-vision.svg');
    }
}
var myButton = document.querySelector('button');
var myHeading = document.querySelector('h1');

function setUserName() {
    var myName = prompt('Bitte geben Sie Ihren Namen ein.');
    localStorage.setItem('name', myName);
    myHeading.textContent = 'w-vision ist cool, ' + myName;
  }
  if(!localStorage.getItem('name')) {
    setUserName();
  } else {
    var storedName = localStorage.getItem('name');
    myHeading.textContent = 'w-vision ist cool, ' + storedName;
  }

Dann sieht die Website so aus:

![This is an Image](/Dokumente/images/website-bildschirmfoto)

Am Anfang kann man seinen Namen in ein Pop-up Feld reinschreiben damit nachher der eigene Name im Titel steht.  Ausserdem kann man auf das w-vision Logo klicken damit es zu einem Star Wars Logo wird.




Wie funktioniert das Internet

Der Client schickt ein request (Anfrage) an den Server. Der Server reagiert mit einer response (Antwort).


Wie funktioniert der Weg vom Client bis zum Server


* Ihre Internetverbindung: Erlaubt Ihnen Daten über das Internet zu senden und zu empfangen. Dies ist wie die eigentliche Straße auf der Sie entlang gehen, um von Ihrem Haus zum Laden zu gelangen.
* TCP/IP: Transmission Control Protocol und  Internet Protocol  sind Kommunikationsprotokolle, welche bestimmen wie Daten über das Internet übertragen werden. Dies ist vergleichbar mit dem Transportvehikel, mit dem Sie zu dem Laden kommen, welches ein Auto oder ein Fahrrad oder ein anderes Fahrzeug sein könnte.
* DNS: Domain Name Servers sind wie ein Adressbuch für Internetseiten. Wenn Sie nach einer Internetadresse suchen, dann schaut der Browser auf dem DNS nach, um die wirkliche Adresse dieser Webseite zu finden. Der Browser muss herausfinden, auf welchem Server die Webseite liegt, damit er eine HTTP Anfrage an die richtige Stelle senden kann. Dies ist vergleichbar mit dem heraussuchen der Adresse des Geschäftes, in dem Sie einkaufen gehen wollen, damit Sie dieses auch finden.
* HTTP: Hypertext Transfer Protocol ist ein Applikations protocol welches eine Sprache definiert mit welcher Client und Server miteinander kommunizieren können. Dies ist wie die Sprache, mit der Sie im Laden Ihre Bestellung machen.
* Zusätzliche Dateien: Eine Webseite wir aus verschiedenen Dateien zusammengesetzt, ähnlich wie sie aus verschiedenen Teilen aus dem Laden etwas sinnvolles bauen können. Diese Dateien kommen in zwei Haupttypen vor:
    * Code Dateien: Webseiten sind hauptsächlich aus HTML, CSS, und JavaScript, aber es gibt noch weitere Möglichkeiten.
    * Inhalte: Dies ist alles andere, was auf einer Website zu finden ist, wie Bilder, Musik, Videos, Word-Dokumente oder PDFs.



Was passiert jetzt also genau?

Wenn Sie eine Internetadresse in Ihren Browser eintippen (wie wenn Sie zu dem Laden gehen):
1. Der Browser kontaktiert den DNS Server und findet die echte Adresse von dem Server auf dem die Webseite liegt (Sie finden die Adresse des Ladens).
2. Der Browser sendet eine HTTP-Anfrage an den Server und fragt nach einer Kopie der Webseite für den Client (Sie gehen zu dem Laden und bestellen Ihre Waren). Diese Nachricht und alle anderen Daten, welche zwischen Client und Server gesendet werden, nutzen Ihre Internetverbindung und nutzen TCP/IP für die Übertragung.
3. Wenn der Server die Anfrage entgegennimmt, sendet dieser an den Client eine "200 OK" Nachricht, welche soviel bedeutet wie "Natürlich können Sie sich die Webseite anschauen! Hier ist sie." Danach sendet der Server die Dateien der Webseite, in kleinen Datenpaketen, an den Browser.  (Im Laden bekommen Sie Ihre Waren und bringen diese nach Hause)
4. Im Browser werden die kleinen Datenpakete zusammengesetzt und zeigt Ihnen die komplette Webseite. (die Waren kommen bei Ihnen daheim an)
