# Corona-Daten für die Öffentlichkeit

Stand: 06.04.2020 17:30 Uhr

# Was ist das hier?
... wird gf. weiter ergänzt

# Für wen?

Journalisten. Wissenschaft, Forschung, Interessierte Jederfrau & Mann. Darstellung - aber auch Analyse - auch rückwirkend.

# Nutzung/Lizenz

Die Daten sind die „Fallzahlen in Deutschland“ des Robert Koch-Institut (RKI) und stehen unter der [Open Data Datenlizenz Deutschland – Namensnennung – Version 2.0](https://www.govdata.de/dl-de/by-2-0) zur Verfügung.

Quellenvermerke siehe jeweilige Daten

Beachten Sie auch den [Haftungsausschluss unten](#Haftungsausschluss).

# Warum macht der NDR das?

Öff. Debatte unser Auftrag. Datenlage schlecht.

Nicht nur das [<span class="icon icon_extlink"></span>Robert Koch-Institut](https://www.rki.de/DE/Content/InfAZ/N/Neuartiges_Coronavirus/Fallzahlen.html "Link: Link zum Robert-Koch-Institut") veröffentlicht täglich die Anzahl der Corona-Neuinfektionen und -Verstorbenen für Bundesländer und Kreise. Auch die Ministerien der Länder vermelden die Zahlen ihrer Gesundheitsämter. Da es dort noch keinen einheitlichen Meldeweg gibt, stammen die Ministeriumsdaten je nach Bundesamt aus der Staatskanzlei oder den Gesundheitsministerien.

Die Quellen sind also nicht nur vielfältig, bisher werden die Daten an vielen Stellen täglich überschrieben, sodass immer nur die aktuellen Tageswerte zu sehen sind. Um die Ausbreitung des Virus verfolgen zu können, ist allerdings gerade eine historische Entwicklung der Fallzahlen interessant.

### Daten für die Öffentlichkeit

Die Datenjournalisten des Norddeutschen Rundfunks sammeln diese Daten und halten sie vor und liefern damit die Grundlage für die Corona-Berichterstattung für Fernsehen, Radio und [ndr.de](https://www.ndr.de/ "Zum Artikel: Webseite des NDR"). Zusätzlich berechnen sie aufgrund der Fallzahlen verschiedene Indikatoren, etwa die Zahl der Neuinfektionen pro 100.000 Einwohner für jedes deutsche Bundesland.

Damit auch andere diese Informationen nutzen können, stellt der NDR diese Daten hier zum Download bereit. Über die folgenden Links können sie mehrmals täglich aktualisierte .csv-Dateien mit mit Daten zur Corona-Pandemie im Zeitverlauf herunterladen und diese für Ihre eigenen Analysen und Projekte nutzen.

### Die Basis: RKI-Mirror & Bulk {#npgeo}

["RKI COVID 19"-Datensatz](https://npgeo-corona-npgeo-de.hub.arcgis.com/datasets/dd4580c810204019a7b8eb3e0b329dd6_0/data) (löscht sich selbst!)
Alles komprimiert als [gz](). Wie entpacken? Windows, Mac, Python

Bulk: https://storage.googleapis.com/public.ndrdata.de/rki_covid_19_bulk/covid_19_bulk.tsv.gz

Tägliche Spiegel: https://storage.googleapis.com/public.ndrdata.de/rki_covid_19_bulk/daily/covid_19_daily_`2020-06-16`.tsv.gz

Angabe im [ISO-Datumsformat JJJJ-MM-TT](https://de.wikipedia.org/wiki/ISO_8601#Datum). JJJJ = 4-stelliges Jahr, MM = 2stelliger Monat, TT = 2-stelliger Tag im Monat. ALso für den 16. Juli `2020-06-16`, für den 23. August `2020-07-23`.

(Auf Vollständigkeit geprüft und ggf. bereinigt, alle Datumsangaben einheitlich im ISO-Datumsformat.)

Spaltenbeschreibung in [Metadaten](https://www.arcgis.com/home/item.html?id=dd4580c810204019a7b8eb3e0b329dd6)

Quellenvermerk: Robert Koch-Institut (RKI), dl-de/by-2-0

### Das Bisherige

In den Dateien finden sich die Anzahl der Neuinfektionen, wie sie das jeweilige Ministerium und das Robert Koch-Institut angeben. Ebenso die bestätigten Todesfälle aus beiden Institutionen und die vom NDR anhand der jeweiligen Einwohnerzahl eines Bundeslands berechneter Inzidenz-Wert, also die Anzahl der Infektionen oder Todesopfer pro 100.000 Einwohner. Außerdem liefern einige Bundesländer weitere Informationen, wie zum Beispiel die Zahl der Genesenen. Eine genaue Übersicht über alle Spaltennamen finden Sie in der nachstehenden [<span class="icon icon_download"></span>Tabelle](/nachrichten/info/coronadownload112.xlsx "Download starten: Datenfelder der CSV-Dateien (XLSX)").

Die Datenjournalisten des NDR sind bemüht, die Informationen stets aktuell zu halten, können aber kein Gewähr für die Vollständigkeit oder Richtigkeit übernehmen. Da sich die Webseiten der Datenquellen (zum Beispiel der Landesministerien) regelmäßig ohne Vorwarnung ändern, kann es zu Fehlern und falschen Berechnungen kommen. Bei einer Verwendung müssen die Quellen der Daten (RKI oder Landesministerien) angegeben werden.

Quellenvermerk: Robert Koch-Institut (RKI), dl-de/by-2-0

<!-- <div class="contentbox voll">

<div class="boxhead">Download</div>

<div class="textpadding"> -->

*   [CSV-Download: Aktuelle Corona-Zahlen der Landkreise](https://storage.googleapis.com/ndrdata-corona-csv/csv/landkreise_aktuell.csv "Link: CSV-Download: Aktuelle Corona-Zahlen der Landkreise")
*   [CSV-Download: Aktuelle Corona-Zahlen Schleswig-Holstein](https://storage.googleapis.com/ndrdata-corona-csv/csv/aktueller_stand_schleswig_holstein.csv "Link: CSV-Download: Aktuelle Corona-Zahlen Schleswig-Holstein")
*   [CSV-Download: Aktuelle Corona-Zahlen Hamburg](https://storage.googleapis.com/ndrdata-corona-csv/csv/aktueller_stand_hamburg.csv "Link: CSV-Download: Aktuelle Corona-Zahlen Hamburg")
*   [CSV-Download: Aktuelle Corona-Zahlen Niedersachsen](https://storage.googleapis.com/ndrdata-corona-csv/csv/aktueller_stand_niedersachsen.csv "Link: CSV-Download: Aktuelle Corona-Zahlen Niedersachsen")
*   [CSV-Download: Aktuelle Corona-Zahlen Bremen](https://storage.googleapis.com/ndrdata-corona-csv/csv/aktueller_stand_bremen.csv "Link: CSV-Download: Aktuelle Corona-Zahlen Bremen")
*   [CSV-Download: Aktuelle Corona-Zahlen Mecklenburg-Vorpommern](https://storage.googleapis.com/ndrdata-corona-csv/csv/aktueller_stand_mecklenburg_vorpommern.csv "Link: CSV-Download: Aktuelle Corona-Zahlen Mecklenburg-Vorpommern")
*   [Datenfelder der CSV-Dateien (XLSX)](/data/coronadownload112.xlsx "Download starten: Datenfelder der CSV-Dateien (XLSX)")

<!-- </div>

</div> -->

### Sammeln Sie mit uns Daten!

Sie haben interessante Daten zu Corona? Z.B. ältere Versionen des ["RKI Covid-19"](#npgeo)-Datensatzes? Her damit!

Fragen und Anregungen nehmen wir gerne unter [<span class="icon icon_extlink"></span>data@ndr.de](mailto:data@ndr.de "Link: Link zur E-Mail-Adresse data@ndr.de") entgegen.

## Haftungsausschluss{#Haftungsausschluss}

*Haftungsausschluss: Die Inhalte dieser Seite dienen ausschließlich der allgemeinen Information der Öffentlichkeit. Der NDR übernimmt keine Verantwortung für die Richtigkeit und Vollständigkeit der Daten und Informationen, ob auf dieser Seite angegeben oder verlinkt, für Abweichungen von Originaldaten, Übertragungsfehler oder Veränderung der Informationen durch Dritte.*
