# Theorie von CI
* Gleichzeitiges bearbeiten von Projekten
* Automatisierung für Entwickler
* kontinuierliche Änderungen
* Rückmeldung für Entwickler

![Continous Integration](https://i.imgur.com/OejDwPS.png "Continous Integration Circle")

# Vorteile vom CI
from dbtable import *

persons = DbTable('persons',['id', 'name', 'vorname',
                  'wohnort', 'geschlecht', 'jahrgang'])
persons.insert(1, 'Huber', 'Lia', 'Bern', 'w', 2002)
persons.insert(2, 'Meier', 'Luca', 'Basel', 'm', 2003)
persons.insert(3, 'Frech', 'Tim', 'Bern', 'm', 2000)
persons.insert(4, 'Bauer', 'Jan', 'Luzern', 'm', 2003)
persons.insert(5, 'Zwahlen', 'Noah', 'Thun', 'm', 2002)
persons.insert(6, 'Meier', 'Nina', 'Biel', 'w', 2001)
persons.printTable()
DbTable.save('schule.db')   

# Software
* GitHub
* Atom
