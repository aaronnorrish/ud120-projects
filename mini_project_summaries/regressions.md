### Lesson 7.39 Bonus Target and Features
The regression input is salary (x-axis) and the regression target is bonus (y-axis).

### Lesson 7.41 Extracting Slope and Intercept
The slope of the regression line is m = 5.44814029, the intercept is b = -102360.543294.

### Lesson 7.42 Regression Score: Training Data
The regression score of the training data is 0.0455091926995.

### Lesson 7.43 Regression Score: Test Data
The regression score of the testing data is -1.48499241737. If the training data was used instead, it would be expected that the performance of the regression would be overestimated, as is shown in the previous exercise.

### Lesson 7.44 Regressing Bonus Against LTI
Regressing bonus against long term incentive yields a regression score of -0.59271289995.

### Lesson 7.45 Salary vs. LTI for Predicting Bonus
If having to predict someone's bonus from their salary or long term incentive it would be preferred to use their LTI as the feature, as the regression score for bonus against LTI (-0.59271289995) is greater than that for bonus against salary (-1.48499241737) from the given dataset.

### Lesson 7.46 Sneak Peek: Outliers Break Regressions
The slope of the new regression line (outliers removed from the dataset) is m = 2.27410114. Note this has a regression score of 0.251488150398, much of an improvement from -1.48499241737.
