# Take-Home Interview: Graffiti Graph

Residents of Chicago can request graffiti removal by calling 3-1-1. Your job is to build a dashboard that displays the number of graffiti removal requests by ward. (The City of Chicago is divided into 50 subsections called "wards".)

## Exercise Instructions

Your tool should interact with the City of Chicago's data API to retrieve the information needed. It's up to you as to how the dashboard should display the data, but some sort of visual graph or chart may be nice! The main thing is that we can see how many 3-1-1 requests were made for each ward.

The data set to use for this coding challenge are Chicago's graffiti removal request data set: https://data.cityofchicago.org/resource/hec5-y4x5.json 

Graffiti removal requests data set API description:

[https://dev.socrata.com/foundry/data.cityofchicago.org/cdmx-wzbz](https://dev.socrata.com/foundry/data.cityofchicago.org/cdmx-wzbz)

This API happens to be paginated, and only shows 1,000 items at a time. For the purposes of this exercise, assume that the first 1,000 items are *all* of the removal requests; you don't need to bother with any of the remaining requests.

As a bonus, allow the user to input a month and year so that the dashboard only displays the graffiti removal requests for that period of time.






