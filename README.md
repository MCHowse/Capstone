Miles Apart: Transportation Access and Economic Opportunity Across Tennessee

Nashville Software School | Data Analytics Cohort DA-17 | 2026
Author: Michele Howse
GitHub: MCHowse | LinkedIn: mchowse1

Quick Summary:
I looked at whether or not having a car affects someone's ability to get ahead financially in Tennessee.
I used real government data covering all 95 TN counties.
Big takeaway: counties with fewer cars per household also tend to have more poverty. It's not a coincidence, the two go hand in hand.

What This Project Is About:
I used two data sources: the Census Bureau's American Community Survey (ACS) and the National Transit Database (NTD).
I measured "transportation access" two ways, both from the ACS: how many households have a car, and how many people use public transit to get to work.
The NTD tells me how many transit agencies operate in Tennessee, but I didn't break that data down by county.
Urban vs. rural: I hand-picked the state's 20 biggest metro counties (Davidson, Shelby, Knox, Hamilton, and others) and called those "urban." Everything else is "rural." This is my own simplified stand-in, not the official Census Bureau method.
Why I care: I drive for Lyft in Nashville. A lot of my riders don't have another way to get around, and that's what prompted me to ask these questions.

The 4 Questions I Answered:
1.  How does car ownership vary across counties, and does it connect to income?
2.  Which counties have the least access to public transportation?
3.  How do commute methods differ between city and rural counties?
4.  How are transportation access and poverty connected?

Data Sources:
American Community Survey (ACS)	Vehicle access, commute methods, income, and poverty, by county	(tables B08201, B08301, B19013, S1701, filtered to Tennessee); www.data.census.gov
National Transit Database (NTD)	Transit agency and ridership info for Tennessee (the Service table);	www.transit.dot.gov

Tools Used:
Python / Pandas: cleaning, merging, and prepping the data
SQL: querying and aggregating
Tableau: the dashboard and all final charts
Jupyter Notebook: documents the whole process, start to finish


How to Run This:
Clone it:     
git clone https://github.com/MCHowse/miles-apart-tn-transportation.git
