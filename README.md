<h1 align='center' style='color:#e85d04'>Covid-19 Data Analysis & Visualization</h1>

---
**Data Source:-**
   1. [India](https://api.covid19india.org/csv/latest/case_time_series.csv)           
   2. [States](https://api.covid19india.org/csv/latest/states.csv)           
   3. [Districts](https://api.covid19india.org/csv/latest/districts.csv) 
---

<h3 style='color:#023e8a'>INDIA</h3>


_Columns_ = `Date` `Daily Confirmed` `Total Confirmed` `Daily Recovered` `Total Recovered` `Daily Deceased` `Total Deceased`


##### The file contains the real-time data of covid-19, daily cases as-well-as cumulative cases of whole country. 
---

<h3 style='color:#023e8a'>STATES</h3>


_Columns_ = `Date` `State` `Confirmed` `Recovered` `Deceased` `Other` `Tested`

##### The file contains the cumulative data for `confirmed cases`, `recovered cases` , `deceased cases` & `tested cases` for each state and it is  updated regularly. 
---

<h3 style='color:#023e8a'>DISTRICTS</h3>

_Columns_ = `Date` `State` `District` `Confirmed` `Recovered` `Deceased` `Other` `Tested`

##### The file contains the cumulative data for `confirmed cases`, `recovered cases` , `deceased cases` & `tested cases` for each district of each state and it is updated regularly. 
---

###### There is a seperate notebook for [India](India.ipynb), [States](State.ipynb) & [Districts]().

###### Each notebook consists the following:-
* Data Cleaning
* Data Visualization
* Stats for each state/districts

---
