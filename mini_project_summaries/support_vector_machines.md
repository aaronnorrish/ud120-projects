### Lesson 2.28 SVM Author ID Accuracy
kernel = "linear"
accuracy of support vector machine: 0.984072810011

### Lesson 2.29 SVM Author ID Timing
kernel = "linear"
training time: 183.521 s
predicting time: 19.098 s
This is much slower than Naive Bayes.

### Lesson 2.30 A Smaller Training Set
kernel = "linear"
training time: 0.099 s
predicting time: 1.09 s
accuracy of support vector machine: 0.884527872582
Using a reduced training set is much faster, but has worse accuracy for the given test set.

### Lesson 2.31 Speed-Accuracy Tradeoff
Flagging credit card fraud and blocking transactions before they go through, as well as voice recognition are examples where a very fast algorithm is required.

### Lesson 2.32 Deploy an RBF Kernel - Reduced Training Set
kernel = "rbf"
training time: 0.126 s
predicting time: 1.311 s
accuracy of support vector machine: 0.616040955631

### Lesson 2.32 Deploy an RBF Kernel - Reduced Training Set
kernel = "rbf"
training time: 0.126 s
predicting time: 1.311 s
accuracy of support vector machine: 0.616040955631

### Lesson 2.33 Optimise C Parameter - Reduced Training Set
kernel = "rbf"
C = 10.0
training time: 0.124 s
predicting time: 1.382 s
accuracy of support vector machine: 0.616040955631

kernel = "rbf"
C = 100.0
training time: 0.131 s
predicting time: 1.379 s
accuracy of support vector machine: 0.616040955631

kernel = "rbf"
C = 1000.0
training time: 0.119 s
predicting time: 1.223 s
accuracy of support vector machine: 0.821387940842

kernel = "rbf"
C = 10000.0
training time: 0.109 s
predicting time: 1.009 s
accuracy of support vector machine: 0.892491467577

### Lesson 2.35 Optimised RBF vs. Linear SVM: Accuracy
kernel = "rbf"
C = 10000.0
training time: 119.527 s
predicting time: 12.96 s
accuracy of support vector machine: 0.990898748578

### Lesson 2.36 Extracting Predictions from an SVM - Reduced Training Set
kernel = "rbf"
C = 10000.0
training time: 0.122 s
predicting time: 1.098 s
accuracy of support vector machine: 0.892491467577
The 10th predicted element belongs to Chris, the 26th Sara and the 50th Chris (results were 1, 0, 1).

### Lesson 2.37 How Many Chris Emails Predicted?
kernel = "rbf"
C = 10000.0
training time: 121.163 s
predicting time: 11.666 s
accuracy of support vector machine: 0.990898748578
877 emails are predicted to belong to Chris.
