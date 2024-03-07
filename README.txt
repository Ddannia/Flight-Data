README.txt
==========

Project Name
------------
Flight and Airline data - Compare delays of two US airlines

Description
-----------
This file contains the code and data for an analysis of delays for US domestic flights. The goal of this project is to analyze flight delays for specific routes relevant to Jim's business travels, focusing on Alaska and JetBlue airlines to determine which is more reliable in terms of punctuality.

Files 
-----
- rBootcamp_Airline_Delays.Rmd: R Markdown file containing the code and analysis.
- rBootcamp_Airline_Delays.html: HTML version of the R Markdown file.
- flights.csv: Raw data file containing flight information.
- airports.csv: Raw data file containing airport information.
- README.txt: This file.

Installation and Configuration
------------
1. Open R markdown file: Open the rBootcamp_Airline_Delays.Rmd file in RStudio.
2. Install packages: Run the following code in the R Markdown file to install the packages: install.packages(c("knitr", "shiny", "ggplot2", "dplyr", "maptiles", "sf", "tidyterra", "magrittr", "stringr", "hrbrthemes", "stats", "ggridges"))
3. Run the Analysis: Use the "Knit" function in RStudio to generate a HTML or PDF output. 
4. View the Results: Open the generated HTML or PDF file to view the results of the analysis.

Dependencies
------------
The analysis was conducted using R and several packages, including: 
- knitr (version 1.8.0)
- shiny (version 1.8.0)
- ggplot2 (version 3.4.4)
- dplyr (version 1.0.7)
- maptiles (version 0.7.0)
- sf (version 1.0-15)
- tidyterra (version 0.1.0)
- magrittr (version 2.0.1)
- stringr (version 1.5.1)
- hrbrthemes (version 0.8.0)
- stats (version 4.1.0)
- ggridges (version 0.5.6)
The code to install the above packages is written in R Markdown and can be run in RStudio.

Features
--------
1. Data Analysis: Use descriptive statistics to summarize and describe the main characteristics of the data set.
2. Visualization: Inspect the data with various plot functions using packages like ggplot2, maptiles and ggridges.
3. Statistical Analysis: Apply t-test on the delay difference of two airlines. 
4. Interactive Component: Include shinyApp to display delay difference of two airlines in a given month and on one specific route.

Data
----
The flights.csv file contains information about flights in 2015, including the airline, fligth date, origin and destination airports, and departure and arrival times, distance, the binary variable whether a flight was cancelled and other variables, that are not relevant to the analysis and thus, are removed from the data set. The data spans the year 2015 and include 5.8 Mio US domestic flight entries. There in total 31 variables. 
The airports.csv file complements the first file with gps coordinates of the airports and contains 322 entries with 7 variables.

Analysis
--------
The analysis includes exploratory data analysis, visualization, and statistical tests to compare the delays between Alaska and JetBlue airlines. The goal is to provide insights into which airline may be more reliable for Jim's business travels.

Results
-------
The analysis shows that Alaska airline has fewer delays compared to JetBlue and the delays are statistically significant in all months excluding January and October. This suggests that Jim may benefit from joining Alaska's loyalty program for his business travels.

Conclusion
----------
In conclusion, this project provides valuable insights into flight delays for Alaska and JetBlue airlines, helping Jim make more informed decisions about his travel plans. 

Credits
-------
The credits of this work, goes to Yaqun Wu and Blerta Imeri.

Contact Information
-------------------
Yaqun Wu: yaqun.wu@stud.hslu.ch
Blerta Imeri: blerta.imeri@stud.hslu.ch


