# Data Analysis: Aircraft Accidents

## Table of Contents
1. [Introduction](#introduction)
2. [Datasets](#datasets)
3. [Dictionary](#dictionary)
4. [EDA and ETL](#eda-and-etl)
5. [Dashboards](#dashboards)
6. [Professional Contact](#contact)
  

## Introduction and Context <a name="introduction"></a>

The air transport industry is closely related to safety procedures. The priceless human lives and the high economic investment on airplanes requires the top procedures to prevent accidents. Considering flights number increaser over time because of the demographics and economy growth, to preserve safety first is a must. Over the years, engineers has focused their efforts in decreasing the aircraft fatalities. The object of this analysis is to find out if this effort reflects in the studied data.

The nature of aircraft accidents vary depending on the type of flight (experimental, militar, civilian), unplanned events (weather, war, pilot's error, technical issue), and many other possibilities. We want to find out if the fatalities has decreased over the time, considering some of this possibilities. To find out if this objective has been achieved, we compare :a: the overall aircraft crew fatality rate and :b: the militar vs civilian crew fatality rate.

:arrow_right: On this context, only two decades concern to this analysis, the current and the one before. This is a bounded study, so it will give results of a specific time and data frame. Not all of the possibilities are considered yet, so please do not consider this results as a final conclusion, but a part to get to it. 

:arrow_forward: This analysis uses the next parts of the original data source: date, operator, crew aboard, crew fatalities. The proces will use averages, totals, operator type (and subsequently flight type, as civilian or military) and number of flights. 
