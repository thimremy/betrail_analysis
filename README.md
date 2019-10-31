# Betrail Analysis

## Introduction

Our goal is to find short "undervalued" trails in Belgium. We have defined the latter as:
- races between 10 and 20km (max 25km)
- races with less runners than the average
- races where good performers don't tend to participate

## Method

To achieve that goal, we are going to web scrape data from [Betrai](https://www.betrail.run/home). Betrail initially identified each trail in Belgium and has now expanded in Luxembourg, France and the Netherlands.

Betrail holds the following information:
- ranking of all runners based on their performance
- listing of all trails 

By combining the above information, we must be able to spot "undervalued" trails.
