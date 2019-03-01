# Ford GoBike Dataset Exploration

This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area in 2017. The dataset can be downloaded from https://www.fordgobike.com/system-data.

## Summary of Findings
### Univariate Findings
- The duration shows a unimodal distribution with a peek around 500s after the log transformation. The duration bigger than 20000s is seen as the outlier and filtered out.
- The birth year shows that the user born between 1980 and 1990 accounts for the largest proportion. The user aging above 80 is seen as outliers and filtered out.
- The geographic coordinate is clustered at three locations. By calculating the relative distance, the distance shows a unimodal distribution with a peek around 0.015 under the log transformation. However, there are 10000 observations which are likely to be seen as no location change.
- October shows the most frequent usage of the bike, and Saturday and Sunday shows the steep jump in usage.
- The number of subscribers are much more than that of customers, while the number of males are much more than that of female and other.

### Bivariate Findings
- The duration and distance shows a very low correlation
- Before 1994, people born in different years show a stability at 800 sec average duration, except a drastic fluctuation before 1954. After that, people have a increasing average duration of bike trip.
- The average duration shows a rapid increase before July and a stable decrease after that.
- The subscriber has a lower mode and median of duration than the customer, while this pattern of the male, female, and other keep the same. The subscriber and male show obvious even distribution when the duration is below 200 sec.
- The number of subscriber is much more than that of the customer. And the male subscriber accounts for a very huge proportion.

### Multivariate Findings
- The distribution of duration for different people is nearly the same.
- The customer has a higher average duration than the subsriber.
- The average duration of customer decreases rapidly. The average duration of the other increases rapidly and keep stable.

## Key Insights for Presentation
- People are likely to use bikes for short-distance travels.
- The bike usage shows an overall increase in 2017. People use bike more in weekdays than weekends.
- Young people are likely to use the bike for a relatively long duration.
- Compared to the subscriber, the customer has a higher duration but that duration decreases in 2017.
- The other and female has a higher duration than the male.

## Recommendations
It is recommended that Ford GoBike can take marketing efforts to attract customers to become subscribers to enhance the user loyalty. The future market can target the other as a potential.
