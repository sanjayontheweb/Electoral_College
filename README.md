# Electoral_census
Big shoutout to UC Berkeley Datathon picking this as the Novice/Intermediate Category winner! 

## Project Description

### Intro
Below we map the electoral vote per capita per state, and place it side by side with population density per state (author: Aref Malek). We see a clear discrepancy where the states with lower population density consistently have higher vote representation, but what are the demographics of these enfranchised states.
![density plot](https://github.com/arefmalek/Electoral_census/blob/main/aref/images/Electoral_capita.png)
![Electoral College per Capita plot](https://github.com/arefmalek/Electoral_census/blob/main/aref/images/Density.png)

### Methodology
Use the vote per capita for each state to find the number of total votes each demographic of the state had (i.e. by race, age, gender, etc.). Sum the totals of these per state votes per demographics to create a country-wide vote per demographic table. Can compare this to the "true" proportion of electoral votes for these demographics, that would ideally be exactly equal to their representation in the population.

In other words, if males make up 48% of the population, they should receive 48% of the electoral votes. Any discrepancy between this on the national level and the sum of the male representations per state means that the electoral college is misrepresenting the proportion of men solely based on how votes are partitioned across states.

We got demographic information for the voting population of each state from census data for 2017, 2018, and 2019.

### Results
We found the strongest differences between "Expected" and "Actual" voter representation across gender, race, and income.

![Disparities](https://github.com/arefmalek/Electoral_census/blob/main/aref/images/Disparities.PNG)

### Impact

The legacy of rich, white, landowning men holding the power in our voting system still seems to exist, though hidden in the intricacies of the electoral college. The only way to truly represent individual populations accurately is to abolish the electoral college completely. An interesting solution is the National Popular Vote Interstate Compact, which you can read more about below.

[Presentation of our findings](https://docs.google.com/presentation/d/1sinLWGFZFcr_NRR1wc04M2LVNnh-9tA8XyjAdd9Ksps/edit?usp=sharing)