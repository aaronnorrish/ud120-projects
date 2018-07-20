### Lesson 4.37 Your First Email DT: Accuracy
min_samples_split = 40
training time: 63.708 s
predicting time: 0.034 s
accuracy of decision tree: 0.978953356086

### Lesson 4.38 Speeding Up Via Feature Selection 1
There are 3785 features in the training data.

### Lesson 4.39 Changing the Number of Features
There are now 379 features in the training data after changing the selector percentile from 1 to 10 (in /tools/email_preprocess.py).

### Lesson 4.40 SelectPercentile and Complexity
A larger percentile results in more features being selected, therefore leading to a more complex decision tree.

### Lesson 4.41 SelectPercentile and Complexity
percentile = 1
training time: 4.938 s
predicting time: 0.003 s
accuracy of decision tree: 0.967007963595
This makes sense, less features, less complexity, less accuracy.
