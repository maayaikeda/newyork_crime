# New York State Arrest and Prison Sentence Analysis
I analyzed the New York State 2018 arrest data to see if racial disparities exist. Analysis included adjusting for county population data and racial demographics of counties in which persons were arrested or sentenced to prison. I found that black people are arrested and sentenced to prison disproportionately high compared to every other demographic group. This is true especially for counties with high white population (>50%). Conversely, in counties where black people make up more than 10% of the total population, black people are arrested less and yield fewer prison sentences per arrest. This suggest that disproportionately high arrest and prison sentences of black people is due to racial biases against black people in counties with high white/ low black population.


## Analysis

One of the first stark observations I made from the data is the disproportionate amount of arrests among the Black population as compared to every other demographic category. This figure shows the mean arrest by population by race of all counties in New York State.

Figure 1:
![figure1](/images/Figure1.png)



When we look at race arrest/race population against the size of the county, we see that black people are arrested at a higher rate than other races in counties with lower population, when compared to larger counties.

Figure 2:
![figure2](/images/Figure2.png)


This figure examines the same data as the previous figure, but observes a logarithmic function of total population. This makes it easier to see the differences & similarities between counties of lower and mid-range population. It is worthwhile to note that highly/densely populated areas generally are more dangerous (have higher crime rates) than lightly populated areas. In NY State, the overall crime rate in the mid-sized counties is half or less than half of the high-populated counties.


Figure 3:
![figure3](/images/Figure3.png)



When we looked at the demographics, as expected, higher populated counties have a higher percentage of minorities. Using the same logarithmic population range, four stacked columns illustrate the mean racial demographic for counties in New York State. 

Figure 4:
![figure4](/images/Figure4.png)

Comparing Figure 3 to Figure 4, we find that the highest rates of arrests of Black people occur mainly in counties where Black people make up less than 7.6% of the total population and continues to drop as Black people make up larger & larger percentages of the total population.

### Does this mean that the higher percentage of minorities, the fewer black people get arrested?
This is interesting, as it is "generally believed" that neighborhoods with more black population/fewer white people are more dangerous. 


In fact, it is the opposite. The data shows that in counties where Black people make up less than 10% of the total population, their arrest rate is significantly higher than in counties which Black people make up more than 10% of the total population. 

Figure 5:
![figure5](/images/Figure5.png)



Once again, black people are the only demographic that seems to be affected. There doesn’t seem to be much difference in the percentage of arrests within other racial groups based upon the percentage of Black people in each county — but **what about the percentage of White people?**



When race arrest/race population is plotted against the percentage of white population in each county, it is clear that black people are arrested at a lower rate in counties where white people make up less than 50% of the total population (in which White people are the minority), and a higher rate in counties where white people are greater than 50% of the population (in which white people are the majority).


Figure 6:
![figure7](/images/Figure7.png)



To quantify the racial disparities of arrest, I calculated a "Representation Factor" which is the percentage of arrests divided by the percentage of the population for each race. For instance, if 35% of arrested people were white and the white population of the country was 40% of the total population, the representation Factor will be 35/40 (or 0.85). If the percentage of the arrest and the percentage of the population were equal, the representation factor will equal to 1.  In a perfectly fair system, this number should be close to 1 for every group.



In this figure we can see that is not the case. The representation factor is a lot higher for black people than for other races in almost all counties.

Figure 7:
![figure8](/images/Figure8.png)


In this figure, the dotted line marks an Arrest Representation Factor = 1 , and the x-axis shows the percentage of white people in each county. The higher the percentage of white people in the county, the higher the representation factor is for black people. Hispanic people seem somewhat over-represented, but not by much. Asian people seem somewhat under-represented, white people seem to move closer to 1 as the percentage of white people in each county approaches 100%, but as that benchmark is reached the Representation Factor for black arrestees gets higher and higher.


Figure 8:
![figure9](/images/Figure9.png)

This is a summary plot for the figure above, showing the mean representation factor for each race in counties with white majority (white >0.5) vs. white minority (white <0.5).

Figure 9:
![figure10](/images/Figure10.png)

 
When the counties are grouped by the percentage of black population (using 10% as a cutoff), it is clear that the representation factor for black people is lower/closer to one when there are more than 10% of black people in the county. 


Figure 10:
![figure11](/images/Figure11.png)

These two figure shows that the fewer white people/the more black people in the community, the fewer black people get arrested per black population.

### More black people are sentenced to prison than any other race and it's worse when they are arrested in white marjority counties.

To see if these racial disparities continue up through the justice system, I looked to see if there's a difference in the percentages of prison sentences among the arrestees of different races. 


This plot shows that black and hispanic arrestees are much more likely to receive prison sentences than other races/ethnicities.

Figure 11:
![figure12](/images/Figure12.png)




When plotted against the percentage of white demographic, it is clear that black and hispanic arrestees are sentenced prison at a higher rate than other races in counties with a higher percentage of white residents.


Figure 12:
![figure13](/images/Figure13.png)



In the context of the other data in this series, it’s unsurprising that these results sharply increase as the size of the white majority increases, resulting in higher incarceration rates in both the black and hispanic populations. What is surprising is that persons in the Other-Unknown category and Asians are also somewhat affected by this phenomenon, even though they’re somewhat under-represented in arrests.


Figure 13:
![figure14](/images/Figure14.png)



This graph has a diagonal dotted line signifying the Representation Factor equalling 1 - here we can see that black people are imprisoned at a higher rate (and white people are incarcerated at a lower rate) than their percentage of arrests.

Figure 14:
![figure15](/images/Figure15.png)



An interesting twist is that when we look at felony arrests (a subdivision of total arrests) and prison sentences, the disparity actually narrows just a little bit — suggesting that black people are often incarcerated more frequently for less serious crimes.


Figure 15:
![figure16](/images/Figure16.png)



How does this play out in counties with varying black populations? In counties where black people make up less than 10% of the population, the incarceration rates approach 2x the “fair” Representation Factor of 1.

In counties where black people make up more than 10% of the population, that rate drops to around 1.4.

Figure 16:
![figure17](/images/Figure17.png)



The effect contrasts much more strongly when we look at counties with white majorities vs counties with white minorities. In the counties where white people make up less than 50% of the population, the imprisonment Representation Factor for the black population drops almost to 1 - suggesting that in those locations the justice system is handling their cases more fairly. 






## What conclusions can we draw from this dataset?



It seems as though, all other things being equal, arrests and prison sentences of each racial group should fall near the “fair” Representation Factor of 1 (1:1 ratio of population to arrests and arrests to prison sentences). This is not the case in this dataset.



If inner-city poverty and “ghetto culture” were to be blamed for criminal behavior, as is often implied by racist dog-whistles, you’d expect that the rates of arrests vs population would be much higher in the larger counties, but the opposite is true. In counties where there are more black people, smaller and smaller percentages of the black population are arrested, not the same rate, not slightly fewer; substantially fewer.

…and in those same places, black arrestees seem to get a better chance at avoiding prison — read as: a fair trial by a jury of their peers.



The ugly conclusion is that in New York State it seems that **the higher the White population, the more likely a Black community member will be arrested, and the more likely that person will be sentenced to prison for a non-serious or misdemeanor offense.**



Notes: 

** Some might say that larger cities are more efficient at solving crimes, however, I found no significant difference in clearance rates between large cities and small towns, according to the 2017 FBI uniform crime report.  <br>
** In the context of violent crimes, in almost all cases, the offender and the victim are the same race (also from FBI uniform crime report). 

[Linke to full analysis](https://github.com/maayaikeda/newyork_crime/blob/master/New_york_race_and_arrest.ipynb)




