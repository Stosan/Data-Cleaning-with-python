# Data-Cleaning-with-python
# GAMES Consort

## DATA CLEANING & MANIPULATION

#### Student-Instructor: Sam Ayo

### Methodology: Lecture/Practical series

### Dataset Definition

This is an Electricity dataset. This data was collected from the Australian New South Wales Electricity Market. In this market, prices are not fixed and are affected by the market's demand and supply. 
They are set every five minutes. 
Electricity transfers to/from the neighboring state of Victoria.

The dataset contains 45,312 instances dated from 7 May 1996 to 5 December 1998.


* Date: date between 7 May 1996 to 5 December 1998. Here normalized between 0 and 1
* Day: day of the week (1-7)
* Period: time of the measurement (1-48) in half hour intervals over 24 hours. Here normalized between 0 and 1
* NSWprice: New South Wales electricity price, normalized between 0 and 1
* NSWdemand: New South Wales electricity demand, normalized between 0 and 1
* VICprice: Victoria electricity price, normalized between 0 and 1
* VICdemand: Victoria electricity demand, normalized between 0 and 1
* transfer: scheduled electricity transfer between both states, normalized between 0 and 1
* class: identifies the change of the price (UP or DOWN) in New South Wales relative to a moving average of the last 24 hours (and removes the impact of longer term price trends).

#### target: class

#### Dataset Category: Energy

##### Rows: 45,312 # Columns: 8

### Keywords

keywords=["central tendency", "imputation"]
