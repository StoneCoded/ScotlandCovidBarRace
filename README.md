# Scotland Covid Bar Race

Creates a bar race (an animated updating bar chart over time) of covid-19 numbers in Scotland.


### Table of Contents

 1. Installation
 2. Motivation
 3. File Descriptions
 4. Results
 5. Licensing, Authors, and Acknowledgements

## 1. Installation.

BarCharRace installation is required. Documentation/Installation instructions can be found [here](https://pypi.org/project/bar-chart-race)

Other than the above and the standard Anaconda distribution of Python 3, there should be no issues running the code.

As I have left it, the default numbers are centered around Hospital Numbers as they are increasingly showing a better indicator on how a country is dealing with Covid amid a vast increase in testing. To change this, simply change the argument Dataframe in covid_fmt().

## 2. Motivation

As I sit pretending to understand the pandemic around me I try to use publically available data to combine my own opinions with
daily news briefings. Whilst the official data has done most of the data processing for me, I thought a Bar Chart Race would be an interesting way to view the numbers over time. 

## 3. File Descriptions

There is one jupyter notebook file that related to the questions above. 

BarRace.ipynb - that downloads the most recent Scottish Government covid information, formats it into a form that BarChartRace recognises and implements it. You may notice the warning removal at the bottom of the code. I have yet to work out why this warning is happening but it doesn't effect output so for ease of viewing I have removed warnings for the final cell.

Each is commented through to aid reading and understanding.

## 4. Results

From anyone living in the UK and Scotland in particular the fact that Glasgow experiences the highest nubmers is consistant with current events and nothing new. This project was in part an attempt to view the data in a different way and also an opportunity to use BarChartRace. 

## 5. Licensing, Authors, and Acknowledgements

All data was published by the Scottish Government. The data spreadsheet can be found on the Scottish Goverment Website:[Download](https://www.gov.scot/binaries/content/documents/govscot/publications/statistics/2020/04/coronavirus-covid-19-trends-in-daily-data/documents/covid-19-data-by-nhs-board/covid-19-data-by-nhs-board/govscot%3Adocument/COVID-19%2Bdaily%2Bdata%2B-%2Bby%2BNHS%2BBoard%2B-%2B6%2BSeptember%2B2020.xlsx)

Feeling free to use and abuse the code above to you hearts content.
 
