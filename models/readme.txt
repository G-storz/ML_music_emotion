All models trained on quadrant labels without the score features and id.
Used both accuracy and f1-score as evaluation metric for classifiers but didnt result in different best classifiers.

All classifiers were really good on correctly predicting class 1 and 3 but struggled with classes 2 and 4, probably because happy
and sad are easily distinguishable emotions and annotations on these probably were better too.

For some reason i couldnt achieve better than 0.54 accuracy when trying to predict score_mode.
