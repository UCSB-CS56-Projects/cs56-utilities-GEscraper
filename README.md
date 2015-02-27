cs56-utilities-GEscraper
========================

project history
===============
```
 YES | mastergberry | Scrape UCSB course pages for appripriate classes that fulfill certain GE requirements
```

Scrape University of California, Santa Barbara's General Catalog to show General Education Area Course list. 

Website for scraping: http://my.sa.ucsb.edu/catalog/current/UndergraduateEducation/AreaE.aspx 


Changes by Dylan Lynch and Brent Kirkland
- Added special subject requirements feature
- TODO: Sorting Options
- TODO: Reuse
- TODO: Better user documentation
- Added comments/new javadoc comments
- Shows names in course lists retrieved from webpages
- 


Recent Changes of LAST GROUP
-Improved Javadoc
-Added JUnit Tests
-Refactored files for Git
-Fixed missing class case
-Added User interaction to input an Area (eg "B", "C")


Example run to show Area B:

ant run

"Enter a Subject Area (B-H)" will appear

Type B

Hit Enter

Class will be displayed as "CHIN 3", "CHIN 3NH", ... "SPAN 6SS"

Picture Example: http://imgur.com/Tw30G1m
