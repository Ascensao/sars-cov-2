# SARS-CoV-2.exe

<p align="center">
  <img width="380" height="380" src="https://github.com/Ascensao/sars-cov-2/blob/master/sars-cov-2.png">
</p>

SARS-CoV-2 is a .NET statistical analysis Console Application with the same name of the pandemic virus. This console application can predict with great accuracy the spread of the Covid-19 in the next followed days. This information is calculated through the historical analysis of the recently infected people of each country.

## Requirments
* Windows 7 or 10 (32/64 bits)

## How it works ?
1. Update the .txt file of the country you want to run the statistics with the correct value of COVID-19 cases for each day.
2. Execute the sars-cov-2.exe .

<img src="https://github.com/Ascensao/sars-cov-2/blob/master/printscreen.png">

## FAQ
**1. Where is located the .txt files ?**
* Folder "Countries" in .exe root directory.
<img src="https://github.com/Ascensao/sars-cov-2/blob/master/printscreen2.png">
<img src="https://github.com/Ascensao/sars-cov-2/blob/master/printscreen3.png">

**2. What mean the following sentences ?**
* "The Pandemic situation is coming to an end!": This means the average percentage of new cases in the last 10 days is 
significantly coming down . The COVID-19 in the selected location it is in the "Deceleration Phase". (Pandemic Management or Demobilization)
* "The Pandemic situation is unstable !": Means the average percentage of new cases is oscillating between Highs and Lows. In other words, the COVID-19 in the selected location it is in the "Initiation Phase" or "Acceleration Phase". (Containment or Community Mitigation)
* "The pandemic situation is getting bigger !!!" This means the average percentage of the new case is significantly increasing. The COVID-19 in the selected location it is in the "Acceleration Phase". (Containment or Community Mitigation)

<img width="680" src="https://github.com/Ascensao/sars-cov-2/blob/master/pandemic-stages.png">
<img width="680" src="https://github.com/Ascensao/sars-cov-2/blob/master/covid-19-stages.jpg">

**3. Statistical Analyses ?**
* This program only makes calculations based on cumulative values.

**4. Where I can find the values to write in the .txt files ?**
* https://www.arcgis.com/apps/opsdashboard/index.html#/bda7594740fd40299423467b48e9ecf6
* https://www.worldometers.info/coronavirus/
* https://experience.arcgis.com/experience/685d0ace521648f8a5beeeee1b9125cd

Feel free to pull this project and adapt to your needs. Please respect the copyrights.
