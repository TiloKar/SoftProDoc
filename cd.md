# Continious Deployment für ein Wordpress Plugin
![Continious Deployment in unserem Projekt](https://raw.githubusercontent.com/TiloKar/SoftProDoc/main/img/ci_cd%20chain_full.png "Continious Deployment in unserem Projekt")
* Wordpress.org stellt ein kostenloses repository zur Verfügung, um eigne Plugins zu deployen
* Dabei handelt es sich um ein [SVN Repository](https://developer.wordpress.org/plugins/wordpress-org/how-to-use-subversion/)
* dabei müssen bestimmte [Richtlinien](https://wordpress.org/plugins/developers/) eingehalten werden
* die Richtlinien sagen vor, nur stabile Plugins sollen gepusht werden, da sie von wordpress.org ein review bekommen
* Es ist daher in der Deploy-Kette ratsam, einfache PHP Unittest zu automatisieren (Action auf allen dev_user branches)
* Laufen die Tests durch, erfolgt noch ein automatischer Upload bei pull request auf dem zentralen dev branch in eine dem produktiven Umfeld sehr ähnliche Testumgebung auf unserem Spielserver 
* erst nach interner Freigabe erfolgt ein automatisches Update des Wordpress SVN Repository und damit die Freigabe an die Nutzer

# CD im Allgemeinen
Durch Continous Deployment durchlaufen Software-Releases automatisierte Testphasen. Werden diese erfolgreich durchlaufen, gelangt die Version in den Produktiveinsatz. Eine kontinuierliche Bereitstellung erhöht die Nutzerfreundlichkeit im Prozess und vermindert den Zeitaufwand der Testphase.

# Github Actions
CD kann durch Workflows mit Github Actions automatisiert werden. Ein Workflow ist ein automtisierter Prozess, der in der GitHub-Repository eingerichtet wird. Der Workflow besteht aus Aktionen, die nach einen angegebenn Ereigniss ausgeführt werden. GitHub Actions dient der Erstellung eine dynamische CI/CD-Pipline.
Die im aktuellen Projekt bisher identifizierten Möglicheiten für Actions sind folgende: 
* automatische PHP unit tests in allen branches
* [automatischer FTP Upload im dev branch](https://github.com/TiloKar/SoftProPlugin/blob/dev/.github/workflows/ftpPush.yml)
* [automatischer SVN Upload im main branch](https://github.com/TiloKar/SoftProPlugin/blob/dev/.github/workflows/WPPush.yml)
