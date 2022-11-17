## Installed Capacity Dashboard

I thought it would be a good idea to develop a dashboard about my previous career sector. 

The dashboard displays the installed capacity levels for energy sources between February 2019 and October 2022. The data is scraped from monthly pdf reports of TEIAS with Python. 

The capacity amounts through months and the percent of capacity difference between two dates for each source are visualized. The energy sources, start and end dates could be filtered on the dashboard.

I'm not completely satisfied with the final design.  The line chart is clustered when displaying the sources, whose capacities are close to each other. I'll keep looking for more effective ways to present the data.

[Dashboard link](https://public.tableau.com/app/profile/osman.cem.yilmaz/viz/InstalledCapacityReport/Dashboard1?publish=yes)

What can we learn from this dashboard despite its shortcomings?

- Natural gas has the largest share (25,304.3 MW installed capacity, 24.50% of total capacity as of October 2022) however, the installed capacity of natural gas decreased by 1.2% from February 2019 to October 2022.
- Hydroelectric energy has a larger share (30.57% of total capacity) than natural gas in Turkiye, but the dataset splits hydroelectric santrals into dam and run-of-river santrals.
	- Dams have the second-largest share (23,275.2 MW installed capacity, 22.54% of total capacity as of October 2022). Dams' installed capacity increased by 13.3% from February 2019 to October 2022.
	- Run-of-river santrals' installed capacity increased by 5.8% from February 2019 to October 2022. Run-of-river santrals' capacity is 8,293 MW as of October 2022 ( 8.03% of total capacity).
- Other than hydroelectric energy, renewable energy sources' capacities increased significantly. 
	- The third biggest source is wind power. Wind power capacity increased by 60.8% from February 2019 to October 2022 (11,306.8 MW capacity, 10.95% of total capacity as of October 2022).
	- Solar energy capacity is still less than that of lignite and imported coal, but the capacity increase percentage is 74.1. If the trend continues as it is, solar power will be the fourth-largest source.
	- Although geothermal installed capacity constituted 1.63% of total capacity with 1,686.3 MW, it increased by 29.5 percent from February 2019 to October 2022.
	- Biomass installed capacity showed the largest increase (177.3%) from February 2019 to October 2022. The installed capacity of biomass is 1,827.2 MW, and it constituted 1.77% of total capacity.
- Coal power is another important source for Turkiye. It constituted 21.11% of total capacity.
	- Among other coal power plants, import coal capacity is the largest. It constituted 10.04% of total capacity with 10,373.8 MW. The increase in percent is 16.1%, and 44 percent of that increase happened in the last 4 months.
	- The lignite capacity increase is 3.6%. It constituted 9.87% of total capacity with 10,191.5 MW.
	- Hard coal capacity constituted 0.81% of total capacity at 840.8 MW.
	- Asphaltite coal capacity constituted 0.38% of total capacity at 405 MW.
- Other energy sources
	- With 251.9 MW installed capacity, fuel oil accounts for 0.24% of total capacity. Installed capacity decreased by 48.3 percent from February 2019 to October 2022.
	- Naptha total capacity is 4.7 MW. There is no capacity change from February 2019 to October 2022.
	- LNG total capacity is 2 MW. There is no capacity change from February 2019 to October 2022.
	- Diesel total capacity is 2 MW. There is no capacity change from February 2019 to October 2022.
