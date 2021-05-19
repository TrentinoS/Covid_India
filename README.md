<p align="center">
  <img   src='https://images.unsplash.com/photo-1584036561566-baf8f5f1b144?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8MTZ8fGNvcm9uYXZpcnVzfGVufDB8fDB8fA%3D%3D&auto=format&fit=crop&w=500&q=60'>
</p>

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

###### There is a seperate notebook for [India](Notebooks/India.ipynb), [States](Notebooks/State.ipynb) & [Districts](Notebooks/District.ipynb).

###### Each notebook contain the following:-
* Data Cleaning
* Data Visualization
* Stats for each state/districts

---
