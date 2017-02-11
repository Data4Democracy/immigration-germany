## Crime data

###BKA data

[Link](https://www.bka.de/DE/AktuelleInformationen/StatistikenLagebilder/PolizeilicheKriminalstatistik/pks_node.html)

The Website offers several statistics, easily downloadable as csv or xls files. Data can be consumed starting with 2012 and is available for each year. Before that time, only PDFs are available (maybe later).

The data includes all crime that is known to the police as well as attempts to perform crimes. It does not include minor or traffic offenses as well as those criminal acts that were directly taken to court without the police being involved.

> Hinweis:
Die Nutzung der Daten (vollständig oder auszugsweise) ist nur mit Quellenangabe (PKS Bundeskriminalamt, Angabe der Version) zulässig.
Es gilt die Datenlizenz Deutschland - Namensnennung - Version 2.0
> https://www.govdata.de/dl-de/by-2-0

This means we need to always ensure we reference the sources of the data. It's kind of like a CC OSS license.

- Files are Latin1 ..
    - `iconv -f latin1 -t UTF-8 tb05_FaelleInternet_csv.csv > tb05_onlineCases.csv`


Tables offered are:

- Case overview
- Suspect Tables
- Victim Tables
- "Belastungstabellen" (I think this is the solved cases but I need a second opinion here!)

furthermore there are time rows starting with 1987 that give a nice overview of the historical changes.

Overall the data is (at first glance) of great quality as it is all formatted as csv or xls files and they are all in one place. They are also placed in a structured format and can therefore be easily downloaded automatically

```
#BKA 2015-2013
https://www.bka.de/SharedDocs/Downloads/DE/Publikationen/PolizeilicheKriminalstatistik/2015/BKATabellen/Faelle/tb01_FaelleGrundtabelleFallentwicklung_csv.csv?__blob=publicationFile&v=3
https://www.bka.de/SharedDocs/Downloads/DE/Publikationen/PolizeilicheKriminalstatistik/2014/BKATabellen/Faelle/tb01_FaelleGrundtabelleFallentwicklung_csv.csv?__blob=publicationFile&v=3
https://www.bka.de/SharedDocs/Downloads/DE/Publikationen/PolizeilicheKriminalstatistik/2013/BKATabellen/Faelle/tb01_FaelleGrundtabelleFallentwicklung_csv.csv?__blob=publicationFile&v=3
#Police 2015-2014
https://www.bka.de/SharedDocs/Downloads/DE/Publikationen/PolizeilicheKriminalstatistik/2015/Standardtabellen/Faelle/tb01_FaelleGrundtabelle_csv.csv?__blob=publicationFile&v=3
https://www.bka.de/SharedDocs/Downloads/DE/Publikationen/PolizeilicheKriminalstatistik/2014/Standardtabellen/Faelle/tb01_FaelleGrundtabelle_csv.csv?__blob=publicationFile&v=3
https://www.bka.de/SharedDocs/Downloads/DE/Publikationen/PolizeilicheKriminalstatistik/2013/Standardtabellen/Faelle/tb01_FaelleGrundtabelle_csv.csv?__blob=publicationFile&v=3
```
