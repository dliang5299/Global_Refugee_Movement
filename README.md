### University of California, Berkeley
### Master of Information and Data Science Program (MIDS)
### w205 - Fundamentals of Data Engineering

* Year: 2024
* Semester: Fall
* Section: 8
* Instructor: Kevin Crook
* Team Members:
    * Deric Liang
    * Allen Li 
    * Godsee Joy
 
This project presents an analysis into global refugee movement patterns from 2014 to 2022 using NoSQL. For context, NoSQL databases differ from traditional relational databases by storing data in non-tabular formats, which makes them particularly powerful for handling diverse and complex datasets like the one we analyzed.

The Global Refugee Dataset provides a detailed view of refugee movements and forcibly displaced populations worldwide, covering over 200 countries from 2010 to 2022. To make our analysis more focused and manageable, we concentrated on data from three key years: 2014, 2018, and 2022, each representing about 5,000 observations. We selected these years because they fall in the middle of the terms of former U.S. presidents, a time when international policies may have been in full effect. We hypothesized that these policies could have influenced global refugee movements and the countries where refugees sought asylum.

We explore the following research questions:

* Which countries received the largest number of refugees, and which
countries sent the most refugees?
* Which countries were places of temporary refuge in between starting
and final destinations?
* How did the first two years of a U.S. president’s term impact the
number of asylum cases approved in the U.S. and from which
countries?

We explore these questions using graph algorithms (PageRank, Degree Centrality, RA-Brandes) in Neo4j, and presenting business solutions for which MongoDB and Redis are a good fit for analyses.

From our analyses, we reach the following conclusions:

* Top countries receiving refugees: US, Canada, Germany, Great Britain, Australia 
* Top countries sending refugees (in general): Syria, Iraq, Somalia, DR of the Congo, Sudan
* Top countries sending refugees (to US): China, Central America, South America
* Top temporary refuge countries: US, Russia, Mali, Ethiopia, Syria (variation across years, high betweenness)
* Results consistent throughout years, with seemingly little change between US presidential administrations
* MongoDB use case: Organizing POVs by sending country, receiving country, year, etc. in hierarchical format
* Redis use case: Real-time refugee movement data



