# Analysis of U.S. Electric Fueling Stations

### What is this?

This is an analysis of electric fueling stations (AKA electric vehicle charging stations) in the United States.

I wanted to explore a few questions:
- How many EV charging stations are there in the U.S? Which states have the most?
- How many EV charging stations have opened in the last few years?
- Where have EV charging stations opened at the fastest rate?

I sourced data to answer these questions from the U.S. Department of Energy Alternative Fuels Data Center: https://afdc.energy.gov/stations#/find/nearest?country=US. 

Specifically, I downloaded a CSV of alternative fuel charging stations data, using the API here: https://developer.nrel.gov/docs/transportation/alt-fuel-stations-v1/all/#csv-output-format. The data I downloaded was accurate as of July 17, 2024.

### So what?

**Here's what I found:**
- According to the data source I used, there are about 75,000 electric charging stations in the U.S.
- Outside of California, much of the growth in electric charging stations in the U.S. started around 2010 to 2011.
- In the last five years, Massachusetts has seen the fastest rate of increase (723%) in charging stations.
- Meanwhile, Wyoming has seen the slowest rate of increase (122%) in charging stations.
- And yet, in the time period, all states have seen their number of electirc charging stations double.

<img width="1249" alt="Screenshot 2024-07-22 at 3 29 15 PM" src="https://github.com/user-attachments/assets/e7edfad7-7024-45ab-bdb7-a0cd7114c80c">

Check out the interactive Tableau map that I created [here](https://public.tableau.com/views/MappingtheIncreaseinU_S_ElectricChargingStations/MappingtheIncreaseinU_S_ElectricChargingStations?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link) to see the rate of growth of charging stations in each state.

**Areas for further investigation:**

There is a ton of data here. A few questions I might investigate in the future:
- Who owns most of these electric charging stations?
- How does the location of these electric charging stations correlate with other geographic factors, like climate or household income?
- And what does the distribution of workplace stations and private vs. public charging stations look like?
