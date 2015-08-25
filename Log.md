# August 25, 2015

This package uses a trained algorithm to scan text by sentence. 

## Dimensions and Training

The algorithm uses trains on a set of wikipedia articles, and uses these following criteria.

* Likelihood that preceding gram is followed by a period
* Length of Preceding gram
* Number of grams prior to period
* Capitalization of Subsequent gram

##Todo
* review [classification](https://en.wikipedia.org/wiki/Statistical_classification)
