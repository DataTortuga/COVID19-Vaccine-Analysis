# COVID19-Vaccine-Analysis
Group 1 analyzed publicly available data from the Centers for Disease Control and Prevention to understand the mortality associated with Covid-19 vaccinations.
Upon merging, cleaning, and analyzing multiple datasets, Group 1 asked of the Data the following questions:
1. What is the mortality rate by US State?
2. Is there a relationship between vaccine manufacturer and mortality?
3. Does biological gender have an impact on mortality rate?
4. Does patient age impact vaccine related death?

The five US States with the highest total vaccine related deaths were:
California: 304 deaths
Florida: 192 deaths
Illinois: 179 deaths
NY: 179 deaths
Texas: 168 deaths
Unsurprisingly these are highly populated states with large urban cities. 

When normalized for the number of vaccinated patients in the population, the five US States with the highest total vaccine mortality rate were:
Alaska: 0.00009, meaning that 9 out of 100,000 people die after being fully vaccinated.
Wyoming: 0.00008
Kentucky: 0.00008
New Hampshire: 0.00006
North Dakota: 0.00006

We plotted the mortality rate for biological genders male/female for Janssen (J&J), Moderna, and Pfizer vaccines. All 3 manufacturers had statistically minimal adverse reactions resulting in death, with Pfizer being least associated with mortality, then Moderna, then Janssen. Recall that both Pfizer and Moderna vaccines use and MRNA mechanism to induce an immune system response in patients while J&J uses an adenovirus vector. Further examination of this data is warranted as access to all 3 vaccines was not universal for the time series examined, and elderly cohorts were prioritized for vaccination first for the initial months of the time series.

Vaccine mortality was highest for patients over 65 years of age. For patients 12-18, 6 total deaths were observed, 5 Pfizer and 1 Moderna. Because of the mechanisms of the vaccine rollout, there is minimal data for 12-18 mortality, and none for Janssen as that vaccine hasn't been tested in children in the datasets we examined. 

Men died in greater numbers and at a higher rate than women for all 3 vaccines. That said, death rates for the total population were on the order of 1 per million.

Our analysis confirms that vaccine related mortality is in fact, statistically rare.

All datasets, jupyter notebooks, images, and ppt files are located in the appropriately labeled folder structure of the repo.
