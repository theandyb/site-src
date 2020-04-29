---
title: State and County COVID-19 Information
author: Andy Beck
date: '2020-04-27'
slug: state-and-county-covid-19-information
categories:
  - r
tags:
  - COVID-19
  - web scraping
description: ''
noLicense: no
---

As I mentioned previously, I've been helping a project organized by BroadStreet Health to do quality assurance on county-level case and death counts entered by our large team of volunteers every day. This is a running list of counties and states where it is often the case that I have to update a number, whether because the state or county reports something different later than the state's initial report for that date. This list is incomplete and I intend to update it as I go.

*Initial posting: 27-April-2020 10:13PM Eastern*

*Updated: 28-April-2020 10:50PM Eastern*

# Special Cases

## Indiana

State regularly updates numbers for past dates, and [I can access numbers from the dashboard easily](https://gist.github.com/theandyb/8ab1b267b8355f931aa95b30bb3aa9c6). 

## Ohio

State regularly updates numbers for past dates and provides case data in an easy to digest [csv file](https://coronavirus.ohio.gov/static/COVIDSummaryData.csv). [See this for example](https://gist.github.com/theandyb/a675fe6e06c4c8cbbd14127a648a14df).

## Pennsylvania

### Bucks County

County posts [daily updates](http://www.buckscounty.org/news/2020News) with counts that are always higher than what the state reports.

### Chester County
County posts updated numbers in [their dashboard](https://chesco.maps.arcgis.com/apps/opsdashboard/index.html#/975082d579454c3ca7877db0a44e61ca) that can be [pulled from JSON](https://gist.github.com/theandyb/d837e12a37358fd9ecebf16cb2509532)

### Delaware County

[County Dashboard](https://chesco.maps.arcgis.com/apps/opsdashboard/index.html#/bce5af8a6f454ee78e00b5adc67f4c4a)

[Code to pull from JSON](https://gist.github.com/theandyb/664ae3f5d9c6a6cd557bd79681f655b2)

### Erie

[County news releases](https://eriecountypa.gov/about/county-news/news-releases/). Note that these appear to lag behind state for certain dates.

### Lancaster

The county coroner consistently reports higher numbers of deaths than both the state and the county on their dashboard. Generally can be found quoted in [lancasteronline.com](https://lancasteronline.com/)

### Philadelphia County

County posts [daily updates](https://www.phila.gov/the-latest/archives/#/?templates=press_release) with counts that are always higher than what the state reports.

## Wisconsin

Wisconsin has a historical data table, but it doesn't look like numbers are updated after the day they're reported (based on a few annecdotal examples, e.g. Milwaukee County reporting a higher number for a given day).

> "All data are laboratory-confirmed cases of COVID-19 that we freeze once a day to verify and ensure that we are reporting accurate information."

Still might be worth having [code to pull and wrangle the data](https://gist.github.com/theandyb/6a36937db7899e2428e0dcf34a533af2)
### Dane County

County regularly updates daily cumulative case counts along with new deaths on each date. [This can be pulled from a JSON feed](https://gist.github.com/theandyb/07862befe5d538cc90682ab36edaa6a4).

### Milwaukee County

County regularly updates case and death counts for past dates. [I can pull this from the dashboard's JSON](https://gist.github.com/theandyb/77c967ea504f4c3fccff76e82e5f6f7c).

### Waukesha County

County regularly updates just case counts for past dates. [I can pull this from the dashboard's JSON](https://gist.github.com/theandyb/108ec0ac86ad69999338bad449b2822d).