# STDA-project-proposal

### Introduction:

The dataset comes from the open data provided by all the municipalities of Italy. This repository is available at dati.gov.it. From this repository I selected the data going from 2018 to 2019 about the number of connections of foreign cellular sims' to the repeaters of the Milan's city. The problem is very interesting from my point of view because can be found many and many interactions between the presence of people from other places of the world and for example(but not restricted to) fluctuations in the stock exchange prices. It's obvious that to find correlation between a certain flucutation and a migration it should be very massive but we are lucky because the italian stock exchange takes place in the Milan city so it's easier that a massive migration to that city provokes a fluctuation. Also are available many other relations such as the calculus of how many foreign people is attracted during the fashion's week. At the end of the day we can search for two different and interesting relations: the first is about how a migration can affect italian's life and the reverse so how much the italian behaviour can affect the life of people from other nations attracting them.

### Data:

The data is composed by a date in which are present ~13 observations, the next columns have the total number of italian sims, the total number of the foreign sims, the prefix of the foreign sims and the relative country which them belong to. The last column called num is the number of sims from the country written at its left.

![](/Users/rr/Desktop/Screenshot 2020-03-23 at 22.42.25.png)

### Statistical Methods:

I would like to use the datasets about 2018 and 2019 to search for a pattern in the timeserie, this means to search for outliers but I would also like to observe the trend. Surely we will also able to recognise a certain seasonality between fall/winter/spring/summer and this fact will be also confirmed by using the data from 2 different years instead of only one year. In particular probably I'm going to use the decomposition of the time serie through a moving average to search for seasonality and trends. 