
# Don Bradman's Dominance in Numbers: Statistical Exploration of Test Averages

Don Bradman's name is synonymous with excellence and unparalleled achievements in the world of cricket. His remarkable test career spanning from 1928 to 1948 has left an indelible mark on the sport. However, I wanted to delve deeper into the numbers to unravel just how exceptional his performance truly was.

The core objective of this project was to analyze Don Bradman's test average using statistical methods, specifically utilizing the concept of Z-scores. By applying this statistical measure, I aimed to evaluate Bradman's performance relative to the larger population of cricket players.

Through meticulous data collection and analysis, I obtained a comprehensive understanding of Bradman's dominance. The project involved exploring the historical context, examining Bradman's test average across matches and series, and determining his Z-score to benchmark his performance against the norm.

By quantifying Bradman's achievements with statistical precision, this project provides valuable insights into his unparalleled batting prowess and sheds light on his iconic status as cricket's greatest player. It also offers a unique perspective for cricket enthusiasts, statisticians, and anyone intrigued by the intersection of sports and data analysis.

I am excited to share my findings, methodology, and key takeaways from this statistical exploration through this project. Join me on this journey as we delve into the numbers, celebrate cricket's legend, and appreciate the marvel of Don Bradman's test average.






## Roadmap

### Step1 - Collection of data and verification
 Data was downloaded from kaggle
 The link is https://www.kaggle.com/datasets/cclayford/cricinfo-statsguru-data
 It was further verified from https://stats.espncricinfo.com/ci/engine/stats/index.html

### Step 2 - Merging the datasets into one dataset and data cleaning in python

Then the different datasets was merged into one after a new column 'Century' was added in each of them as these were datasets from different Centuries.

There were many duplicates found in the datasets which were finally removed

### Step 3 

Calculating the Average test score of each cricketer

### Step 4

Filtering the batsman out. As you know there are both batsmen and bowlers in cricket and we just wanted to compare test Averages of batmen.
So we filtered this out using a criteria that the average score of batsman should be greater than 20 and he must have faced at least 1000 test deliveries

### Step 5

Plotting the Average test score distribution and figuring out if it is a normal distribution or not

![image](https://github.com/NishantThakurr/Don-Bradman-s-Dominance-in-Numbers-Statistical-Exploration-of-Test-Averages/assets/102639991/42aeecc7-112c-4326-9e4c-63acc94aea89)

This seems like a normal distribution

### Step 6

Final Validation using QQ Plotting
QQ plot was created in order to validate that the distribution was a normal distribution.

![image](https://github.com/NishantThakurr/Don-Bradman-s-Dominance-in-Numbers-Statistical-Exploration-of-Test-Averages/assets/102639991/cff0e07d-d2b6-4485-b77c-accd511883fe)

As we can see the QQ plot signifies that we can assume that it is a normal distribution

### Step 7 Calculating Z score and creating box plot to study Don Bradman's Dominance using numbers.

#### Calculating Z score

![image](https://github.com/NishantThakurr/Don-Bradman-s-Dominance-in-Numbers-Statistical-Exploration-of-Test-Averages/assets/102639991/00270755-a47c-449a-ad62-4b650595be95)

#### Plotting a box plot

![image](https://github.com/NishantThakurr/Don-Bradman-s-Dominance-in-Numbers-Statistical-Exploration-of-Test-Averages/assets/102639991/c267f08b-91e2-4d82-b564-0a9b96ac270a)






## Inference and Conclusions

Using a standard normal distribution table, we can find that a Z-score of 3 corresponds to approximately the 99.7th percentile. This means that the data point with a Z-score of 3 is higher than approximately 99.87% of the data points in the distribution.Image a Zscore of 6.7. It's just ridiculous

Don Bradman's test average of 6.7 Z-score highlights his remarkable performance and dominance in the sport. He achieved an average that far surpasses the performance of most other test cricketers, solidifying his reputation as one of the greatest batsmen in the history of the game.
