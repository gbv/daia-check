Das Skript `daia-check` überprüft den zentrale DAIA-Server der VZG, indem es
für alle in der Datei `daia-examples.csv` aufgeführten ISIL und PPN eine
Abfrage durchführt. Dabei wird getestet, ob mindestens ein Exemplar
zurückliefert wird und ob dieses Exemplar explizit als verfügbar oder nicht
verfügbar gekennzeichnet ist.

Zusätzlich kann überprüft werden, ob alle OPACs aus dem
GBV-Datenbankverzeichnis mit mindestens einer Beispiel-PPN getestet werden.

[![Status bei Travis-CI](https://travis-ci.org/gbv/daia-check.svg?branch=master)](https://travis-ci.org/gbv/daia-check)
