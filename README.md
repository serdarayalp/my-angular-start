# my-angular-start

Angular

Was brauchen wir? Sofern noch nicht auf Ihrem Entwicklungsrechner vorhanden, installieren Sie Node.js und npm und einen Editor bzw. eine integrierte Entwicklungsumgebung, zum Beispiel Visual Studio Code. Die aktuell installierten Versionen erfragen Sie über die Kommandozeile mit folgenden Befehlen:

node -v
npm –v

Danach installieren wir bereits das Web-Framework Angular. Auch dazu bedarf es nur des Kommandos npm install -g @angular/cli.

Wir können an dieser Stelle bereits die erste Angular-App erzeugen. Erstellen Sie dazu ein passendes Projektverzeichnis, begeben Sie sich dann auf Ebene der Kommandozeile und erstellen Sie das Gerüst der App wie folgt mit dem Befehl "ng new MyApp". Beantworten Sie die Frage, ob Sie ein Routing erstellen wollen zustimmend und wählen Sie CSS als Stylingsprache. Einige Augenblicke später sollten alle Dateien und Abhängigkeiten zum Projekt erzeugt sein. Starten Sie Ihren Editor – in unserem Fall Visual Studio Code – und öffnen Sie das Projekt. Vielleicht sind Sie etwas überrascht, wie viele Dateien und Ordner angelegt wurden. Wie Sie jedoch sehen werden, wird sich die Arbeit hauptsächlich auf den App-Ordner konzentrieren.

Wir sind natürlich mehr als gespannt und möchten das Ergebnis sofort begutachten. Aus der Kommandozeile starten Sie die App mittels "ng serve --open" und öffnen auch gleichzeitig den Standardbrowser des Systems. Dazu wird die App kompiliert und der lokale Server gestartet. Über http://localhost:4200/ greifen Sie auf die App aus Ihrem Browser zu. 

*******************************************************************************************

Angular: Unterschiede zu VueJS und React

Alle drei Bibliotheken bzw. Frameworks haben ihre Daseinsberechtigung, Stärken und Schwächen. Je nach Use-Case sollte hier entschieden werden, welche der Alternativen die beste Basis für das aktuelle Projekt liefert.

Angular zielt hierbei ganz klar auf die professionelle Entwicklung von Enterprise Software. Durch klare Vorgaben in Struktur und den Einsatz von Generatoren können langfristig wartbare und skalierbare Softwarelösungen erstellt werden. Konzepte wie Dependency Injection und ein Fokus auf TDD sind seit der ersten Stunde von Angular im Core verankert. Durch die klare Struktur von Projekten ist hierbei explizit die Skalierbarkeit von neuen Entwickler:innen hervorzuheben. Durch dieses Massive Grundgerüst wirkt Angular auf den ersten Blick oft etwas schwergewichtig - überzeugt jedoch in Production durch systematische Optimierungen und Erweiterbarkeit.

ReactJS zielt hierbei eher auf einen sehr minimalen Layer auf Komponenten-Ebene und ermöglicht/erfordert das Konzipieren einer eigenen Architektur von Grund auf. Dies bietet sehr flexible Möglichkeiten für individuelle Problemstellungen sehr explizite Lösungen zu bauen. Es gibt eine Auswahl an verschiedensten Modulen für die verschiedene Anforderungen. Der Aufwand der Integration und Pflege ist hier höher als in Angular, allerdings ist das Projekt dadurch oftmals auch simpler und sehr leichtgewichtig.

VueJS bedient die Anforderungen zwischen diesen beiden Frameworks. Indem das Framework auf einen Generator und klare Strukturen setzt begünstigt es ebenfalls die Skalierung von Projekt-Teams. Allerdings versucht VueJS gleichzeitig sehr leichtgewichtig zu bleiben und möglichst wenig “Framework-Magic” einzubringen. Es ist also die simple aber strukturiere Mittellösung.


*************************************************************

There are several possible types of scaffolds angular-cli can generate:

Module	    ng g module my-new-module
Component	ng g component my-new-component
Directive	ng g directive my-new-directive
Pipe	    ng g pipe my-new-pipe
Service	    ng g service my-new-service
Class	    ng g class my-new-class
Interface	ng g interface my-new-interface
Enum	    ng g enum my-new-enum

***********************************************************************
Building/Bundling

"ng build" or "ng build --prod"

*******************************************************************

Unit Testing: The unit tests are written using jasmine, and executed through Karma.

ng test
 



