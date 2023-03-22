<h1>Git Workflows</h1>

<h2>Zentraler Workflow</h2>

* Ein zentrales Repository dient als zentrale Quelle der Wahrheit.

* Jeder Entwickler klonen das zentrale Repository auf seinen lokalen Computer und arbeitet auf einem gemeinsamen Hauptbranch.

* Die Änderungen werden auf den gemeinsamen Hauptbranch gepusht und gepullt.

<h2>Feature Branch Workflow</h2>

* Jedes Feature wird in einem separaten Branch entwickelt, der von einem stabilen Hauptbranch ausgeht.

* Entwickler erstellen einen Feature-Branch, bearbeiten ihn und machen dann einen Pull Request, um die Änderungen in den Hauptbranch zu übernehmen.

* Der Hauptbranch enthält immer nur stabile und veröffentlichte Versionen des Codes.

<h2>Git-flow-Workflow</h2>

* Es wird ein Hauptbranch erstellt, der die stabile, veröffentlichte Version des Codes enthält.

* Feature-Branches werden für neue Features erstellt.

* Release-Branches werden für Veröffentlichungen erstellt.

* Hotfix-Branches werden erstellt, um Probleme in der Veröffentlichung zu beheben.

* Änderungen werden in den entsprechenden Branches vorgenommen und dann in den Hauptbranch integriert.

<h2>Workflows verzweigen</h2>

* Es gibt viele verschiedene Möglichkeiten, Branches zu verwenden, um verschiedene Workflows zu implementieren, die spezifisch für das jeweilige Team oder Projekt sind.

* Zum Beispiel können Teams eine Kombination aus Feature-Branch- und Git-Flow-Workflow verwenden oder einen Workflow erstellen, der auf ihren spezifischen Arbeitsablauf zugeschnitten ist.

* Die Entscheidung darüber, welcher Workflow am besten geeignet ist, hängt von vielen Faktoren ab, einschließlich der Art des Projekts, der Größe des Teams und den Anforderungen an die Freigabe.
