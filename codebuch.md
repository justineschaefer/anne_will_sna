# Codebuch für Anne Will Testprojekt

Wir untersuchen ein Netzwerk der Gäste von Anne Will von den Sendungen 500 bis 503. Dabei wird auch die Parteizugehörigkeit der Gäste untersucht.

### Nodelist
id = Initialien von Vor- und Nachname, kleingeschrieben oder Sendungsnummer oder Abkürzung der Partei, kleingeschrieben  
name = voller Name
relationship = 1 Gast, 2 Parteimitglied

### Edgelist
from = Gast  
to = besuchte Sendung oder Parteimitgliedschaft
type = 1 Person, 2 Organisation
party = Abkürzung Partei
