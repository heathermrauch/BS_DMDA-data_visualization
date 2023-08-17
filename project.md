
# Baseball Statistics by Player Characteristics

## Visualization Links

- [Baseball Statistics by Player Characteristics v1](https://public.tableau.com/views/BaseballStatisticsbyPlayerCharacteristicsv1/BaseballStatisticsbyPlayerCharacteristics?:language=en-US&:display_count=n&:origin=viz_share_link)
- [Baseball Statistics by Player Characteristics v2](https://public.tableau.com/views/BaseballStatisticsbyPlayerCharacteristicsv2/BaseballStatisticsbyPlayerCharacteristicsv2?:language=en-US&:display_count=n&:origin=viz_share_link)

## Summary

The visualization is a series of scatter plots displaying the exponential relationship between baseball players' batting averages and then number of home runs they hit. There is a difference when the relationship is viewed by the players' handedness; in which right-handed players have both higher batting averages and more home runs, and switch-hitters have lower batting averages and less home runs. There is also a difference when the relationship is viewed by the players BMI category. The impact is not large, but heavier players tend to hit more home runs for right and left-handed players.

## Design

### Version 1

I chose to encode HR and Avg as planar variables because it is the most accurate way to display the relationship between them. I chose to additionally encode the relationship, split by handeness, in the form of trend lines. This was to show that there is a difference between the three handedness categories. I also calculated BMI for each player and encoded it as the size of each circle. This was mainly to show that it did not have a large impact. I chose to use a filled circle over an unfilled circle becuase the amount of color was distracting. Becuase of the amount of overplotting, I chose to go with a somewhat transparent fill for each point.

### Version 2

I split the visualization into multiples over handedness and BMI Category to help make relationships more clear and to help the trend lines better match the data. When doing so, I grouped the Overweigher and Obese categories together because there was only one player in the Obese category. I also encoded the actual BMI using a color scale to help emphasize the difference between the two BMI categories. 

## Feedback

### 1. What do you notice in the visualization?

The dots tend to trend upward exponentially. The data seems more spread out farther up in the chart (more home runs). Orange (left-handed) is more visible on the right (higher batting average) and towards the tip (more home runs).

### 2. What questions do you have about the data?

- Is this from their entire career? or is it from a single season?
- What do the lines represent? and why don't they match the data?

### 3. What relationships do you notice?

The relationship between batting average and home runs.

### 4. What do you think is the main takeaway from this visualization?

The more balls you hit (higher batting average), the more home runs you will hit.

### 5. Is there something you don't understand in the graphic?

The lines don't seem to match well to the dots. Is that a limitation of the human body?

## Resources

- Centers for Disease Control and Prevention. (2021). CDC - Calculating BMI Using the English System - BMI for Age Training Course - DNPAO. https://www.cdc.gov/nccdphp/dnpao/growthcharts/training/bmiage/page5_2.html
- National Heart, Lung, and Blood Institute. (2022). Losing Weight, Body Mass Index. https://www.nhlbi.nih.gov/health/educational/lose_wt/BMI/bmi_dis.htm
