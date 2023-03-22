<h1>Git Workflows</h1>

<h2>Zentraler Workflow</h2>

* Ein zentrales Repository dient als zentrale Quelle.

* Jeder Entwickler klont das zentrale Repository auf seinen Computer und arbeitet auf einem gemeinsamen Main-Branch.

* Die Änderungen werden auf den gemeinsamen Main branch gepusht und gepullt.

<h2>Feature Branch Workflow</h2>

* Jedes Feature wird in einem separaten Main-Branch entwickelt, der von einem stabilen Main-Branch ausgeht.

* Alle erstellen einen Feature-Branch, bearbeiten ihn und machen dann einen Pull Request, um die Änderungen in den Main-Branch zu übernehmen.

* Der Main-Branch enthält immer nur stabile und veröffentlichte Versionen des Codes.

<h2>Git-Flow-Workflow</h2>

* Es wird ein Main-Branch erstellt, der die stabile, veröffentlichte Version des Codes enthält.

* Feature-Branches werden für neue Features erstellt.

* Release-Branches werden für Veröffentlichungen erstellt.

* Hotfix-Branches werden erstellt, um Probleme in der Veröffentlichung zu beheben.

* Änderungen werden in den entsprechenden Branches vorgenommen und dann in den Main-Branch integriert.

<h2>Workflows verzweigen</h2>

* Es gibt viele verschiedene Möglichkeiten, Branches zu verwenden, um verschiedene Workflows zu implementieren, die spezifisch für das jeweilige Team oder Projekt sind.

* Zum Beispiel können Teams eine Kombination aus Feature-Branch und Git-Flow-Workflow verwenden oder einen Workflow erstellen, der auf ihren spezifischen Arbeitsablauf zugeschnitten ist.

* Die Entscheidung darüber, welcher Workflow am besten geeignet ist, hängt von vielen Faktoren ab, einschließlich der Art des Projekts, der Größe des Teams und den Anforderungen an die Freigabe.
