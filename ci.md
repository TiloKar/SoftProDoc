# Theorie von CI
* Gleichzeitiges bearbeiten von Projekten
* Automatisierung für Entwickler
* kontinuierliche Änderungen
* Rückmeldung für Entwickler

![Continous Integration](https://i.imgur.com/OejDwPS.png "Continous Integration Circle")

# Vorteile und Nachteile vom CI
<table>
  <thead>
    <tr>
      <th>Vorteile</th>
      <th>Nachteile</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>durchgängiges Feedback durch die stetige Aktualisierungen</td>
      <td>Umgewöhnung / Umstellung der gewohnten Prozesse -> Widerstand</td>
    </tr>
    <tr>
      <td>Keine "Riesenänderungen", die am Ende zu viele Probleme beinhalten</td>
      <td>Zusätzliche Software und Umgebungen/td>
    </tr>
    <tr>
      <td>ununterbrochene Verfügbarkeit</td>
      <td>Schwierigkeiten bei Projekten mit vielen Entwickler, durch Wartezeit oder "Überschreibungen"</td>
    </tr>
    <tr>
      <td>einfaches Austauschen von Informationen oder Verbesserungen durch die stetige Einsicht</td>
      <td>benötigt zugeschnittene Tests -> CD</td>
    </tr>
    <tr>
      <td>Genaue Protokollierungen / Zeitmaschine</td>
      <td></td>
    </tr>
    <tr>
      <td>frühzeitiges Erkennen von Fehler, die umgehend bearbeitet werden können</td>
      <td></td>
    </tr>
  </tbody>
</table>

# Software
<h2>Allgemeine Defintion</h2>
  <h3> GitHub </h3>
    <img src="https://github.com/TiloKar/SoftProDoc/blob/main/img/logo_github_icon_text_150x84.png?raw=true" alt="logo_github" />
    <p> Was ist GitHub überhaupt?</p>
    <p> GitHub ist kurz gesagt, ein Softwaretool zur Versionsverwaltung welches seit 2018 zum Unternehmen Microsoft gehört. GitHub bietet den Vorteil,   dass bei Softwareprojekten mehrere Projektbeteiligte / Entwickler an unterschiedlichen Elemente der Software arbeiten können ohne das dies Ergebnisse manuell zusammengeführt werden müssen. Dieser Aspekt lässt sich mittels GitHub nämlich automatisieren. Neben anderen Dienstleistern zur Verwaltung von quelloffener Software, steht bei GitHub der Benutzer mit seinen Quelltextdatenbanken im Fokus. Diese werden in GitHub auch Repositories genannt.
  
  <h3> Atom </h3>
  <img src="https://github.com/TiloKar/SoftProDoc/blob/main/img/logo_atom_72x66px.png?raw=true" alt="logo_atom"/>
  <p> Und was ist Atom? </p>
  <p> Atom ist ein Open-Source Texteditor von GitHub. Der Texteditor aus gleichem Hause bietet wie zu erwarten eine enge Verzahnung hinsichtlich der angebotenen Funktionen mit GitHub an. Zusätzlich eignet sich der Texteditor neben der mannigfaltigen Auswahl an unterstützen Programmiersprache auch bestens für die Projektdokumentation an.</p>

<h2> Wie verbinde ich Atom mit meinem GitHub-Repository? </h2>
  <p> Für die Verbindung des Atom-Texteditors mit GitHub sind folgende Punkte Voraussetzung </p>
  <ul>
    <li>
       <h3>Registrierung bei GitHub</h3>
        <p> Logische Voraussetzung für das Verbinden seines GitHub-Repository mit dem Atom-Texteditor ist das Erstellen eines eigenen GitHub-Accounts</p>
        <p> Unter folgender URL https://github.com/ kann man sich innerhalb von wenigen Sekunden unter Angabe der eigenen e-Mail-Adresse, Passwort und den gewünschten Nutzernamen einen Account erstellen.</p>
        <img src="https://github.com/TiloKar/SoftProDoc/blob/main/img/github_sign_in.png?raw=true" alt="github_signin" />
    </li>
    <li>
      <h3>Herunterladen und Installation des Atom-Texteditors</h3>
        <p> Unter der URL https://atom.io/ kann die aktuell Version von Atom runtergeladen werden</p>
        <p> Im Anschluss kann die heruntergeladene .exe-Datei unter dem gewünschten Pfad installiert werden </p>
        <img src="https://github.com/TiloKar/SoftProDoc/blob/main/img/atom_download.png?raw=true" alt="download_page_atom" />
    </li>      
    <li>
      <h3>Das Repository mit Atom verbinden</h3>
        <p>Nachdem man sich ein Repository in GitHub erstellt hat, kann man dieses nun mit Atom verbinden.</p>
        <p>Hierzu müssen wir in unser Repository navigieren und sichstellen, dass wir in dem Tab "Code" uns befinden. </p>
        <img src="https://github.com/TiloKar/SoftProDoc/blob/main/img/repository_code.png?raw=true" alt="repository_tab_code" />
        <p>Benötigt wird der Pfad zum Repository, den wir über den grünen Button "Code" (nicht verwechseln mit dem Repository-Tab) und rufen die darunter liegenden Informationen über einen Mausklick auf. Jetzt sollte der Link zum Repository sichtbar sein, den wir nun in die Zwischenablage kopieren können</p>
        <img src="https://github.com/TiloKar/SoftProDoc/blob/main/img/repository_link.png?raw=true" alt="repository_link" />
        <p>Im Anschluss öffnen wir unseren zuvor installierten Atom-Texteditor und mittel "Strg + Shift + P" können wir nun den notwendigen clone-Befehl absetzen</p>
        <img src="https://github.com/TiloKar/SoftProDoc/blob/main/img/atom_clone_command.png?raw=true" alt="atom_clone_command"/>
    </li>
  </ul>
