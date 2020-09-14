# New York State Arrest and Prison Sentence Analysis
I analyzed the New York State 2018 arrest data to see if racial disparities exist. Analysis included adjusting for county population data and racial demographics of counties in which persons were arrested or sentenced to prison. I found that black people are arrested and sentenced to prison disproportionately high compared to every other demographic group. This is true especially for counties with high white population (>50%). Conversely, in counties where black people make up more than 10% of the total population black people are arrested less and yield fewer prison sentences per arrest. This suggest that disproportionately high arrest and prison sentences of black people is due to racial biases against black people in counties with high white/ low black population.



![figure1](/images/plo2arrestdemographic.png)





Mean arrests by population illustrates the proportion between arrests by race (race arrests) and the percentage of people of that race within the population (race population). This figure represents the mean (average) of all counties in New York State.

Here we can see a disproportionate amount of arrests among the Black population as compared to every other demographic category.



![figure2](/images/plot3arrestvpopulation.png)



This figure plots Race arrests/Race population by the total population of each county. In counties with low population, a larger percentage by far of Black people within that county are arrested. Other races seem to be mostly arrested at the same percentage rate regardless of total county population. 



![figure3](/images/racelogpop.png)



This figure examines the same data as the previous figure, but observes a logarithmic function of total population. This makes it easier to see the differences & similarities between counties of lower and mid-range population. 



It’s worthwhile to note that the overall crime rates in the mid-sized counties is half or less than half of the high-population counties. As a representation factor, the percentage of each race arrested seems fairly constant for every racial group except Black people, and seems to sharply decrease when the total population of each county is high. 


![figure4](/images/populationbarplot.png)




Using the same logarithmic population range, four stacked columns illustrate the mean racial demographic for counties in New York State. Comparing Figure 3 to Figure 4, we find that the highest rates of arrests of Black people occur mainly in counties where Black people make up less than 7.6% of the total population and continues to drop as Black people make up larger & larger percentages of the total population.


![figure5](/images/plot12bararrestvsblackdem.png)




This figure further illustrates percent of arrests per racial demographic. In counties where Black people make up less than 10% of the total population, their arrest rate is significantly higher than counties in which Black people make up more than 10% of the total population. 



Once again, there doesn’t seem to be much difference in the percentage of arrests within other racial groups based upon the percentage of Black people in each county — but what about the percentage of White people?


![figure6](/images/plot9%arrestvswhitedem.png)




This figure shows the mean county arrests for each racial group as a percentage of the total arrests in the counties, split into two groups: Counties where White people make up less than 50% of the total population (in which White people are the minority), and counties where White people are greater than 50% of the population (in which White people are the majority).


![figure7](/images/plot10bararrestvswhitedem.png)




This figure shows the number of arrests of people in each racial group scaled to the percentage of the population of each racial group. The two clusters show the variation between counties where there is a White minority vs a White majority. Once again, there is not much of a difference between the arrest rates for any group except Black people.



![figure8](/images/plot13unfairfactorallcounties.png)




It’s easier to see this disparity if we use a “Representation Factor”: Arrests for each racial group divided by each racial group’s population. In a perfectly fair system, this number should be close to 1 for every group.



In this figure we can see that is not the case.



![figure9](/images/plot14unfairfactor%white.png)



In this figure, the dotted line marks a 1:1 Arrest Representation Factor, and the x-axis shows the percentage of White people in each county.



Hispanic people seem somewhat over-represented, but not by much. Asian people seem somewhat under-represented, White people seem to move closer to 1 as the percentage of White people in each county approaches 100%, but as that benchmark is reached the Representation Factor for Black arrestees gets higher and higher.



Figure 10: Plot15unfairfactorbarwhitedem



This figure condenses the Representation Factors for each racial group based upon White majority (White >0.5) or White minority (White <0.5).



Figure 11: plt16unfairfactorbarblackdem



This figure illustrates the Arrest Representation Factor for each racial group based upon whether the population of the counties have fewer than 10% Black population or greater than 10% Black population.



Figure 12: plot18prison_arrestrace



These racial disparities continue up through the justice system, with Black and Hispanic arrestees much more likely to receive prison sentences.



Figure 13: plot19prison_arrest%white



In the context of the other data in this series, it’s unsurprising that these results sharply increase as the White majority increases, resulting in higher incarceration rates in both the Black and Hispanic populations. What is surprising is that persons in the Other-Unknown category and Asians are also somewhat affected by this phenomenon, even though they’re somewhat under-represented in arrests.



Figure 14: plot17prisonvsarrest



This graph has a diagonal dotted line signifying the Representation Factor equalling 1 - here we can see that Black people are imprisoned at a higher rate (and White people are incarcerated at a lower rate) than their percentage of arrests.



Figure 15: felonyvsprison



An interesting twist is that when we look at felony arrests (a subdivision of total arrests) and prison sentences, the disparity actually narrows just a little bit — suggesting that Black people are often incarcerated more frequently for less serious crimes.



Figure 16: plot21prison_arrestblackdem



How does this play out in counties with varying Black populations? In counties where Black people make up less than 10% of the population, the incarceration rates approach 2x the “fair” Representation Factor of 1.

In counties where Black people make up more than 10% of the population, that rate drops to around 1.4.



Figure 17: plot20prison_arrestwhitedem



The effect contrasts much more strongly when we look at counties with White majorities vs counties with White minorities. In the counties where White people are less than 50% of the population, the prison Representation Factor for the Black population drops almost to 1. 





What conclusions can we draw from this dataset?



It seems as though, all other things being equal, that arrests and prison sentences of each racial group should fall near the “fair” Representation Factor of 1 (1:1 ratio of population to arrests and arrests to prison sentences). This is not the case in this dataset.



If inner-city poverty and “ghetto culture” were to be blamed for criminal behavior, as is often implied by racist dog-whistles, you’d expect that the rates of arrests vs population would be much higher in the larger counties, but the opposite is true. In counties where there are more Black people, smaller and smaller percentages of the Black population are arrested, not the same rate, not slightly fewer; substantially fewer.

…and in those same places Black arrestees seem get a better chance at avoiding prison — read as: fair trial by a jury of their peers.



The ugly conclusion is that in New York State it seems that the higher the White population, the more likely a Black community member will be arrested, and the more likely that person will be sentenced to prison for a non-serious or misdemeanor offense.












![plot4](/images/plot4arrestvslogpopulation.png)![plot8](/images/plot8arrestvsblackpercent.png)





![plot11](/images/plot11blackdemhist.png)
![plot12](/images/plot12bararrestvsblackdem.png)
![plot13](/images/plot13unfairfactorallcounties.png)
![plot14](/images/plot14unfairfactor%25white.png)
![plot15](/images/plot15unfairfactorbarwhitedem.png)

![plot19](/images/plot19prison:arrest%25white.png)



