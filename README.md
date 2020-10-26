# my-angular-start

Angular

Was brauchen wir? Sofern noch nicht auf Ihrem Entwicklungsrechner vorhanden, installieren Sie Node.js und npm und einen Editor bzw. eine integrierte Entwicklungsumgebung, zum Beispiel Visual Studio Code. Die aktuell installierten Versionen erfragen Sie über die Kommandozeile mit folgenden Befehlen:

node -v
npm –v

Danach installieren wir bereits das Web-Framework Angular. Auch dazu bedarf es nur des Kommandos npm install -g @angular/cli.

Wir können an dieser Stelle bereits die erste Angular-App erzeugen. Erstellen Sie dazu ein passendes Projektverzeichnis, begeben Sie sich dann auf Ebene der Kommandozeile und erstellen Sie das Gerüst der App wie folgt mit dem Befehl "ng new MyApp". Beantworten Sie die Frage, ob Sie ein Routing erstellen wollen zustimmend und wählen Sie CSS als Stylingsprache. Einige Augenblicke später sollten alle Dateien und Abhängigkeiten zum Projekt erzeugt sein. Starten Sie Ihren Editor – in unserem Fall Visual Studio Code – und öffnen Sie das Projekt. Vielleicht sind Sie etwas überrascht, wie viele Dateien und Ordner angelegt wurden. Wie Sie jedoch sehen werden, wird sich die Arbeit hauptsächlich auf den App-Ordner konzentrieren.

Wir sind natürlich mehr als gespannt und möchten das Ergebnis sofort begutachten. Aus der Kommandozeile starten Sie die App mittels "ng serve --open" und öffnen auch gleichzeitig den Standardbrowser des Systems. Dazu wird die App kompiliert und der lokale Server gestartet. Über http://localhost:4200/ greifen Sie auf die App aus Ihrem Browser zu. 