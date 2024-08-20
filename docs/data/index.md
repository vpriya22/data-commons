[Data Commons](../)

# UN Goal Timelines - Data Pull

TO DO: Update our [UN Goals CoLab](https://colab.research.google.com/drive/1riRnKUGNGkJZOU6qJoznAxjySInQjnFQ?usp=sharing) to pull DCID's from our [Google Sheet with Goal tabs](https://docs.google.com/spreadsheets/d/1IGyvcMV5wkGaIWM5dyB-vQIXXZFJUMV3WRf_UmyLkRk/edit?usp=sharing).

TO DO: Save .csv files to GitHub using tokens. - Ivy
<!--
[Our Run Models Colab](https://colab.research.google.com/drive/1zu0WcCiIJ5X3iN1Hd1KSW4dGn0JuodB8?usp=sharing#scrollTo=Z12cWU4y09on) already includes a process for saving CSV files to GitHub. The relevant part happens around saving the integrated dataset to the repo.
-->

<!--
Abhishek L may also have .ipynb files that generate .csv files locally. The output .csv could be sent to a fork of [data-commons](https://github.com/ModelEarth/data-commons) in a folder added at data-common/docs/data.
-->

TO DO: Update our [Google Sheet UN Goal tabs](https://docs.google.com/spreadsheets/d/1IGyvcMV5wkGaIWM5dyB-vQIXXZFJUMV3WRf_UmyLkRk/edit?usp=sharing) with additional DCID values that we'll pull for our Python .csv file generation. - Pratyush 

<!--
TO DO: Also update our [Data Commons Timelines CoLab](https://colab.research.google.com/drive/1PF8wojIOHxDCdmadsAdkpHnb-An1ymEh?usp=sharing)
-->

TO DO: From the sheet columns, display a navigation hierarchy with 3 levels using javascript. Here's [.csv for the "Air" tab](https://docs.google.com/spreadsheets/d/1IGyvcMV5wkGaIWM5dyB-vQIXXZFJUMV3WRf_UmyLkRk/pub?gid=0&single=true&output=csv).  

Goal (Air) > Topic (Emissions) > Subtopic (Methane)


SPECS:

We'll create one function in the CoLab that generates all versions of the timelines.

We'll pass the function the column LocationType as: Country, State, County

We'll convert from 3 to 2-char country codes.

We'll send rules in the function's parameters to identify which locations to omit (like which countries lack emissions data).

We'll pull the valid year range from the Google Sheet row. 

The rules can reside in each DCID row in the Google Sheet.

Initial [timeline output Abhishek created](https://github.com/ModelEarth/community-data/blob/master/locations/datacommons/Country.csv).

We'll send our .csv output to UN Goal subfolders at [data-commons/docs/data](https://github.com/ModelEarth/data-commons/tree/main/docs/data)

