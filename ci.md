# Theorie von CI
Continous Integration (Ci) beinhaltet den Automatisierungsprozess für das Entwicklerteam. Hierbei werden, sofern das System erfolgreich angewandt wird, regelmäßig neue Codeänderungen für das Projekt entwickelt, geprüft und zueletzt in ein gemeinsames Repostory zusammengeführt.
Dabei ist es möglich, dass mehrere Entwickler an diesem Projekt gleichzeitig arbeiten können, ohne dass sie sich gegenseitig zu stören. Somit ist es viel häufiger möglich die neu entwickelten Codes zusammenzuführen. Folglich können die Entwickler von einem schnelleren und häufigeren Feedback profitieren.

<h3>Vorteile</h3>

* Dadurch, dass keine "Riesenänderungen" vorgenommen werden, ist es möglich kleinere Fehler zu beheben, sodass eine Ansammlung von Problemen nicht möglich ist.
* Durch CI ist das Projekt, auch während der Bearbeitungsphase, ununterbrochen verfügbar.
* Die stetige Einsicht ermöglich ein einfaches Austauschen von Informationen oder Verbesserungen.
* Durch die stetigen Aktualisierungen ist ein durchgängiges Feedback möglich, welches die Anpassung und die Problemfindung vereinfacht.
* Durch eine genaue Protokollierung der Änderungen, ist es möglich die Timeline des Codes nachzuvollziehen und ggf. abzuändern, sodass Fehler reversibel sind.
* Durch die frühzeitige Fehlererkennung können Probleme direkt angesprochen und behoben werden.

![Continous Integration](https://i.imgur.com/OejDwPS.png "Continous Integration Circle")

Damitein Versionsverwaltungssystem solche Vorteile leben kann mussen Anwender diverse Regeln halten und ...Prozessablauf... Workflow steuern --> zentr. Begrifflichkeiten um Code zu verändern --> rläutern

<table>
  <thead>
    <tr>
      <th>Begriff</th>
      <th>Erläuterung</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>fetch</td>
      <td>Mit diesem Befehl werden Commits, Dateien und Verweise aus einem Remote-Repository heruntergeladen.</td>
    </tr>
    <tr>
      <td>Pull</td>
      <td>Dieser Befehl wird genutzt um alle Inhalte aus einen Remote-Repository herunterzuladen und zusätzlich das aktuelle lokale Repository zu aktualisieren. So übereinstimmen die Inhalte beider Repositories</td>
    </tr>
    <tr>
      <td>Commit</td>
      <td>Der Befehl commit nimmt alle Änderungen mit in den Stage-Bereich. Somit ist commit ein Checkpoint in der alle Änderungen verfolgt werden.</td>
    </tr>
    <tr>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Stage</td>
      <td></td>
    </tr>
    <tr>
      <td>Branch</td>
      <td></td>
    </tr>
  </tbody>
</table>



Hier zu [CI-Anwendungsbeispiel](https://github.com/TiloKar/SoftProDoc/blob/main/praxis_CI.md)
