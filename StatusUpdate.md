# Status Report
 
2/5/2022

## Project title: Logan Triangle: Health, History, and Home in Philadelphia

## Group Members: Angela, Cassie, Corinne, Deja, Lindsey, Olivia

[Link to proposal](https://github.com/oarenaucla/phillygis/blob/main/Group%20Assignments/Project%20Proposal.md) 

## Roles: 
### Public Health Researcher - Corinne
- Research existing public health outcomes across Philadelphia and produce tables and maps indicating what type of disparities exist.
- Visualize how Logan Triangle fits spatially into Philadelphia’s public health outcomes. 

### Environmental Health Researcher - Deja 
- Research existing environmental health conditions across Philadelphia and produce tables and maps to indicate the tree canopy coverage, air quality, and other relevant indicators. 
- Visualize how Logan Triangle fits spatially into Philadelphia’s environmental health conditions.

### Public Green Space Researcher - Cassie
- Research existing public open space across Philadelphia and produce tables and maps to indicate urban agriculture/fresh produce access, park access, vacant lot transformation (LandCare Program), and other relevant indicators. 
- Visualize how Logan Triangle fits spatially into Philadelphia’s green space access.

### Affordable Housing Researcher - Olivia
- Research existing affordable housing access across Philadelphia and produce tables and maps to indicate what housing displacement has looked like over and what access to affordable housing looks like now - Olivia
- Visualize how Logan Triangle fits spatially into Philadelphia’s affordable housing access. - Olivia

### Public Risk Researcher - Lindsey
- Research public risk factors across Philadelphia and produce tables and maps to visualize heat vulnerability, ADA accessibility, complaints against police, and other relevant indicators. 
- Visualize how Logan Triangle fits spatially into Philadelphia’s public risk data.

### Economic development Researcher - Angela
- Research economic development across Philadelphia and produce tables and maps to visualize income inequality, neighborhood amenities, unemployment rates, and other relevant indicators. 
- Visualize how Logan Triangle fits spatially into Philadelphia’s economic development data.

## Status update: 
We’re feeling generally positive with the number of topics and data we’re each exploring. However, it’s also challenging and overwhelming with the volume of data we’re analyzing for a City that not all team members are familiar with. 

## Data update: 
- On the housing research front, we have been working to visualize some of the larger housing trends before pinpointing specific affordable housing challenges. The main data sources are from the social explorer and OpendataPhilly (the Philadelphia Open Data Portal). At the census-tract level for both the Logan Neighborhood and the larger Philadelphia Area, we have the percentage of renter-occupied vs. owner-occupied housing units, the total number of housing units, and the average home value. These initial findings have revealed that there are a good portion of owner-occupied units, but these homes have much lower values than other areas of Philadelphia. These observations track with background reading that revealed a history of environmental hazards and even a buyout of uninhabitable properties. 
- We’ve also explored poverty rates for both the City/County of Philadelphia and the Logan neighborhood. To do so, we used the most recent Census-provided data on household income levels to group households into categories based on their relation to the Federal Poverty Level (FPL), used to determine eligibility for Federal financial assistance, and the most recent median household income numbers provided for Philadelphia by the Census. Mapping the data for both the City-wide dataset showed that the areas with higher rates of poverty were generally clustered towards the center of the City. The neighborhood of Logan is also close to the City center and has high rates of poverty compared to the majority of the City, which also makes sense considering literature on the mass displacement of residents and coupled disinvestment in amenities and commerce due to the area’s environmental toxicity.
- Unemployment data was also explored using the ACS 5-year estimates from 2017-2021 from the social explorer data portal. The census data included information regarding rates of employment and unemployment as well as the total number of those employed or unemployed in Philadelphia. We were also able to extract the same data for the smaller Logan area and found that while Logan’s total employed population makes up only 1 percent of the total labor force in Philadelphia, the percent of unemployed individuals in Logan is double the amount for the larger Philadelphia area. The percent of unemployed people in Logan is 18.5 percent while across Philadelphia it is only 9.1 percent. This increased rate of unemployment experienced by the Logan area is an issue to keep in mind moving forward as we continue with our data exploration. 
- Public open space properties owned by the City and public transit access were also analyzed using the Philadelphia Open Data Portal. The file used was provided by the Philadelphia Parks and Recreation Department. The data included names of parks, size, and geography. Data was then queried to zip codes in 19141 and 19141 which made up the Logan Neighborhood. Initial findings showed that open space was limited in these two zip codes compared to the greater Philadelphia area. Even though the Broad Street Line (BSL) runs through these zip codes, access to these parks and Logan Triangle are challenging as the nearest station, Logan Station, is about half a mile away.  
- For public risk research, Philadelphia’s Complaints Against Police (CAP) dataset available on Open Philly Data was explored. The CAP file included information such as the incident date and time, the district occurrence, the complaint classification, and a summary of the complaint. In addition to the complaints data, the police district boundaries were imported into Python. Then, the data was queried to zoom into Logan Neighborhood. Logan resides within the 35th Police District of Philadelphia. Preliminary data analysis shows that the 35th Police District has had the 2nd highest number (261) of Complaints Against Police from 2016 to date.
- To better understand public health conditions in Logan Triangle as compared to citywide trends, we are examining Social Determinants of Health (SDOH) data from OpendataPhilly. A definition in the metadata document describes SDOH as the “created conditions in which people are born, live, learn, work, play, worship and age which influence health.” The eight metrics included in the SDOH data are poverty, unemployment, older adult population, educational attainment, race and ethnicity, lack of primary care use, health insurance status, and population of people living with a disability. Data regarding the older adult population, lack of primary care use, health insurance status, and population of people living with a disability will be included in the public health research because the other data sets in our project more specifically address the topics of poverty, unemployment, and race. If time allows, other data relating to public health will be visualized, including but not limited to urban agriculture sites and air quality. 

## Concerns: 

### Major Concerns 
- Size of Geography - Because we are looking at a specific neighborhood that has a relatively small geography, it is hard to identify trends within the neighborhood itself. For example, the housing data shows the range of housing costs, but there are no huge disparities or wide ranges in the data. Because of this, we have been comparing the neighborhood with the broader Philadelphia area. The easiest way to do this has been to zoom in and out on a folium map to observe the differences between the two geographies. One thing that would be helpful is learning how to potentially do an outline or highlight of a specific geography, so that the Logan Neighborhood would be more easily identifiable on the larger map. 
- Quality of Available Data- As we discovered in our initial assignment, there are varying degrees of data quality in the Philadelphia open data portal. Because each agency seems to upload its own datasets, there are some that have helpful geographic data missing or that use different identifiers. For example, in the dataset of affordable housing projects, the “address” field lacked city, state, and zip code. When Olivia went to geocode the addresses, even though there were matches, they were all over the world. So, there was not an error code, but only when the data were plotted was the error caught (map below). While these data checks are important in any analysis project, we will need to be more diligent. 

### Minor Concerns
- Familiarity with Philadelphia- Because the scope of our project is in Philadelphia, it has been much harder to ground truth initial observations about the data. As a team, (minus Corinne), we have less familiarity with the geography of the city. We do not naturally know landmarks or regions that could account for specific trends. Our current solution is to pair our data work with more secondary research on existing documents on the Logan Neighborhood. 
- Cohesion - As a group, we’re researching a wide variety of topics and will need to capture the most important takeaways from the data each of us analyzes to arrive at an accurate and cohesive profile of the Logan neighborhood.
- Research Question - As mentioned above we are assessing an array of topics due in part to our research question being broad in scope. For the purpose of the final GIS project, should we narrow our scope and only focus on a few data indicators? 
