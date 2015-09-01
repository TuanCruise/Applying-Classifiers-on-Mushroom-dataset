# Introduction
This is a data mining experiment on Mushroom dataset. With classification model, we can distinguish  poisonous and edible mushrooms through some characteristics such as smell and color.

Blog: https://ongxuanhong.wordpress.com/2015/08/25/ap-dung-cac-phuong-phap-phan-lop-classification-tren-tap-du-lieu-mushroom/

# Exploratory analysis
mushrooms described in terms of physical characteristics; classification: poisonous (p) or edible (e).
* Number of instances: 8124.
* Number of attributes: 22.
* Data type: nomial.
* Missing value at: stalk-root, missing instances: 2480 (31%).
* Distrubution in each class is balance.
* Using filter > unsupervised > attribute > ReplaceMissingValues for replacing missing values.
* 
# Evaluating with hold-out method

|Classifier|Precision|Recall|F-measure|Confusion matrix|
|---|---|---|---|---|
|Naive Bayes|0.946|0.942|0.942|   a    b   <-- classified as
1763  212 |    a = p
  22 2065 |    b = e|
