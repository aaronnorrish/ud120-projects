## Lesson 15.28 Number of POIs in Test Set
There are 4 POIs in the test set.

## Lesson 15.29 Number of People in Test Set
There are 29 people in total in the test set.

## Lesson 15.30 Accuracy of a Biased Identifier
If the identifier predicted that everyone in the test set was not a POI, its accuracy would be 0.8621 (25/29).

## Lesson 15.31 Number of True Positives
There are no true positives in the test set.

## Lesson 15.32 Unpacking Into Precision and Recall
The precision of the POI identifier is 0.0.

## Lesson 15.33 Recall of Your POI Identifier
The recall of the POI identifier is 0.0.

## Lesson 15.34 How Many True Positives?
There are 6 true positives.

## Lesson 15.35 How Many True Negatives?
There are 9 true negatives.

## Lesson 15.36 False Positives?
There are 3 false positives.

## Lesson 15.37 False Negatives?
There are 2 false negatives.

## Lesson 15.38 Precision
The precision of the classifier is 0.6667 (6/9).

## Lesson 15.39 Recall
The recall of the classifier is 0.75 (6/8).

## Lesson 15.40 Making Sense of Metrics 1
My true positive rate is high, which means that when a *POI* is present in the test data, I am good at flagging him or her.

## Lesson 15.41 Making Sense of Metrics 2
My identifier doesn’t have great *precision*, but it does have good *recall*. That means that, nearly every time a POI shows up in my test set, I am able to identify him or her. The cost of this is that I sometimes get some false positives, where non-POIs get flagged.

## Lesson 15.42 Making Sense of Metrics 3
My identifier doesn’t have great *recall*, but it does have good *precision*. That means that whenever a POI gets flagged in my test set, I know with a lot of confidence that it’s very likely to be a real POI and not a false alarm. On the other hand, the price I pay for this is that I sometimes miss real POIs, since I’m effectively reluctant to pull the trigger on edge cases.

## Lesson 15.43 Making Sense of Metrics 4
My identifier has a really great *F1 score*. This is the best of both worlds. Both my false positive and false negative rates are *low*, which means that I can identify POI’s reliably and accurately. If my identifier finds a POI then the person is almost certainly a POI, and if the identifier does not flag someone, then they are almost certainly not a POI.

## Lesson 15.
