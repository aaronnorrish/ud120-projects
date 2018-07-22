### Lesson 6.13 Size of the Enron Dataset
There are 146 data points (people) in the Enron dataset.

### Lesson 6.14 Features in the Enron Dataset
There are 21 features available for each person in the dataset.

### Lesson 6.15 Finding POIs in the Enron Data
There are 18 persons of interest.

### Lesson 6.16 How Many POIs Exist?
There are 35 persons of interest in total (taken from final_project/poi_names.txt).

### Lesson 6.17 Problems with Incomplete Data
Having some POIs missing from the dataset may cause a problem when trying to train the classifiers. 18 data points is not a large amount to draw patterns from. As discussed in Lesson 6.3 Accuracy vs Training Set Size, small training sets usually lead to more inaccurate predictions.

### Lesson 6.18 Query the Dataset 1
The total value of the stock belonging to James Prentice is $1,095,040.

### Lesson 6.19 Query the Dataset 2
There are 11 email messages from Wesley Colwell to persons of interest.

### Lesson 6.20 Query the Dataset 3
The value of stock options exercised by Jeffrey K Skilling is 19250000.

### Lesson 6.21 Research the Enron Fraud
Enron was involved in the following schemes:
    1. selling assets to shell companies at the end of each month, and buying them back at the beginning of the next month to hide accounting losses.
    2. causing electrical grid failures in California.
    3. a plan in collaboration with Blockbuster movies to stream movies over the internet.

### Lesson 6.22 Enron CEO
Jeffrey Skilling was the Enron CEO during most of the time that the fraud was being perpetrated.

### Lesson 6.23 Enron Chairman
Ken Lay was the chairman of the Enron board of directors during this time.

### Lesson 6.24 Enron CFO
The CFO during this time was Andrew Fastow.

### Lesson 6.25 Follow the Money
Ken Lay made the most money out of the above three $103,559,793.

### Lesson 6.26 Unfilled Features
Unfilled Features are denoted by "NaN".

### Lesson 6.27 Dealing with Unfilled Features
95 people in the dataset have a quantified salary and 111 have a known email address.

### Lesson 6.29 Missing POIs 1
21 people in the dataset have "NaN" as their total payments, this represents 14.38% of the dataset.

### Lesson 6.30 Missing POIs 2
0% of the (18) POIs have "NaN" as their total payments.

### Lesson 6.31 Missing POIs 3
If a machine learning algorithm were to use total_payments as a feature, it would be expected that it would associate a "NaN" value with non-POIs.

### Lesson 6.32 Missing POIs 4
By adding 10 more data points which were all POI’s with “NaN” for the total payments, the total number of people would increase to 156, and the number having "NaN" as their total payments to 31 - 19.87% of the new dataset.

### Lesson 6.33 Missing POIs 5
Similarly the number of POIs would increase to 28 and that of those having "NaN" as their total payments to 10 - 35.71% of POIs.

### Lesson 6.34 Missing POIs 6
Adding these data points would likely lead a supervised classification algorithm to interpret “NaN” for total_payments as a clue that someone is a POI.
