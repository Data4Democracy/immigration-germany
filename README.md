# immigration-germany
Exploring German immigration data

##Motivation
Over the past few years, immigration has become a major topic in public discourse in Germany and is poised to become an important part of the upcoming election campaigns. In the project, we would like to sort fact from stereotypes.
What data is there about immigrants in Germany? What does it say about the people who settle there?


##Project Ideas:
* Occasionally, law enforcement states in the media that crime statistics are no different for refugees and immigrants from German-born citizens. The BKA has open data on crime statistics that might be helpful. Are there additional data sources we can explore?



##Notes:
* Terminology; I think we need to understand this. How, exactly, are the terms “immigrant” and “refugee” defined, what other categories are important? How are they reflected in the data we (will) have?
* Using comparisons might be helpful. For example, the probability that someone will randomly get mugged on the street is quite small, but people aren’t good at understanding probabilities. It might be helpful to pair some of these with things that are dangerous, but people do every day (like cross a street, drive a car, climb a ladder, …)


## Possible Data Sources:

Naturally most sources will be German. We have a few German members that can help abstract this and perform the preprocessing to turn labels etc into english terms so that others can work with it. Text data is not easily translatable so we will have to see how we handle this.

### Crime Data

- BAMF: [http://www.bamf.de/DE/Infothek/Statistiken/statistiken-node.html](http://www.bamf.de/DE/Infothek/Statistiken/statistiken-node.html)
- BKA:[https://www.bka.de/DE/AktuelleInformationen/StatistikenLagebilder/PolizeilicheKriminalstatistik/PKS2015/pks2015_node.html](https://www.bka.de/DE/AktuelleInformationen/StatistikenLagebilder/PolizeilicheKriminalstatistik/PKS2015/pks2015_node.html)
    - Files are Latin1 ..
        - `iconv -f latin1 -t UTF-8 tb05_FaelleInternet_csv.csv > tb05_onlineCases.csv`
- The data portal of the German federal government: https://www.govdata.de/web/guest/daten This should have loads of useful data sets!
- Relatedly, the German ministry for statistics has lots of data sets (also available via the govdata website), and their website is available in English! https://www.destatis.de/EN/Homepage.html
