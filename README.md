# Corona-Daten des NDR für die Öffentlichkeit

Hier stellt das Datenteam des Norddeutschen Rundfunks (NDR Data) der Öffentlichkeit aktuelle und historische Daten zur Corona-Pandemie zur Verfügung. Jeder kann sie herunterladen und kostenfrei nutzen (siehe [Nutzungsbedingungen](#Lizenz)).

Der NDR möchte so als Teil seines öffentlich-rechtlichen Auftrages sicherstellen, dass diese Daten jetzt und dauerhaft als saubere und maschinenlesbare Datensätze in gleichbleibendem Format allgemein verfügbar sind, um die Coronakrise nachzuvollziehen, zu analysieren und zu erforschen. Das Angebot richtet sich nicht nur an die Medien und die Wissenschaft, sondern an jeden Interessierten.

Zudem stellt der NDR interaktive Karten zur eigenen Nutzung und Veränderung zur Verfügung, die den aktuellen Verlauf der Covid-19 Neuinfektionen in den Stadt- und Landkreisen zeigen.

## Welche Daten gibt es hier?

Es handelt sich vor allem um die Fallzahlen der an Covid-19 Erkrankten als "Kerndaten" der Pandemie in unterschiedlicher regionaler Auflösung und aus unterschiedlichen Quellen. Zusätzlich enthalten die Datensätzen verschiedene Indikatoren, etwa die Zahl der Neuinfektionen pro 100.000 Einwohner für jedes deutsche Bundesland. Die Daten waren und sind auch Grundlage für die NDR-Berichterstattung in Fernsehen, Radio und auf [ndr.de](https://www.ndr.de/ "Webseite des NDR").

Die Datensätze sind stets tagesaktuell.

Da sich die Corona-Daten der Originalquellen (Robert Koch-Institut oder Landesministerien) oft täglich überschreiben, sind dort immer nur aktuellen Tageswerte zu sehen - und Zeitvergleiche der Datensätze nicht möglich. Das NDR Data-Team greift viele dieser Tageswerte automatisiert ab und stellt sie hier bereinigt als konsistente Zeitreihen zur Verfügung.

## Lizenz

Alle Daten können frei und kostenlos unter der [Open Data Datenlizenz Deutschland – Namensnennung – Version 2.0](https://www.govdata.de/dl-de/by-2-0) genutzt werden. Die Quellenvermerke sind bei den jeweilige Datensäten genannt (s.u.). Beachten Sie bitte auch den [Haftungsausschluss unten](#Haftungsausschluss).

## Alle Meldedaten des Robert-Koch-Instituts

Das Robert-Koch-Institut (RKI) in Berlin stellt mit seinem ["RKI COVID 19"-Datensatz](https://github.com/robert-koch-institut/SARS-CoV-2_Infektionen_in_Deutschland) auf GitHub die wichtigste und vollständigste amtliche Datensammlung mit Covid-19 Fallzahlen nach Meldetag, Alter, Geschlecht, Landkreis und anderen Merkmalen zur Verfügung. Der Datensatz überschreibt sich täglich, so dass alte Datensätze nicht mehr vorliegen.

NDR Data bietet hier für jeden Tag seit dem 31. März 2020 eine komplette Kopie dieser täglichen Datensätze zum Download an, die auf Vollständigkeit geprüft, bereinigt, und in ein einheitliches Format gebracht wurden. Eine Beschreibung der Spalten und ihrer Bedeutung findet sich im ReadMe des [RKI-GitHub-Repositories](https://github.com/robert-koch-institut/SARS-CoV-2_Infektionen_in_Deutschland#merkmalsauspr%C3%A4gungen).

Sämtliche Datumsspalten sind im [ISO-Datumsformat JJJJ-MM-TT](https://de.wikipedia.org/wiki/ISO_8601#Datum) angegeben. Dabei bedeuten: JJJJ = 4-stelliges Jahr, MM = 2-stelliger Monat, TT = 2-stelliger Tag im Monat. Der 16. Juli 2020 wäre also im ISO-Format `2020-07-16`, der 23. August 2020 wäre beispielsweise `2020-08-23`.

**Der Datensatz zum jüngsten Datenstand (also heute, solange das RKI die Daten täglich aktualisiert)** findet sich unter der URL https://storage.googleapis.com/public.ndrdata.de/rki_covid_19_bulk/daily/covid_19_daily_latest.tsv.gz (komprimiert)

**Der Datensatz zu einem bestimmten Datum** findet sich unter der URL https://storage.googleapis.com/public.ndrdata.de/rki_covid_19_bulk/daily/covid_19_daily_2020-06-16.tsv.gz, wobei anstelle der Zeichenfolge `2020-06-16` das gewünschte Datum im ISO-Format (siehe oben) angegeben werden muss.

Alle Tabellen liegen als [CSV-Dateien](https://de.wikipedia.org/wiki/CSV_(Dateiformat)) vor. Das Trennnzeichen der Spalten ist der Tabulator (`\t`). Die Dateien sind zumeist komprimiert und tragen darum die Endung `gz`. Unter Windows lassen sie sich beispielsweise mit dem kostenfreien Programm [7-Zip](https://www.7-zip.org/) dekomprimieren, auf Apple-Rechnern einfach per Doppelklick im Finder.

**Quellenvermerk: Robert Koch-Institut (RKI), dl-de/by-2-0**

## Sammeln Sie mit uns Daten!

Sie haben interessante Daten zur Coronakrise? Melden Sie sich beim NDRdata-Team!

Fragen und Anregungen nehmen wir gerne unter [data@ndr.de](mailto:data@ndr.de "Link: Link zur E-Mail-Adresse data@ndr.de") entgegen.

## Haftungsausschluss

*Haftungsausschluss: Die Inhalte dieser Seite dienen ausschließlich der allgemeinen Information der Öffentlichkeit. Der NDR übernimmt keine Verantwortung für die Richtigkeit und Vollständigkeit der Daten und Informationen, ob auf dieser Seite angegeben oder verlinkt, für Abweichungen von Originaldaten, Übertragungsfehler oder Veränderung der Informationen durch Dritte.*
