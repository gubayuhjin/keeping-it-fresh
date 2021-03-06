[<img src='https://community.drivendata.org/uploads/default/optimized/1X/e055d38472b1ae95f54110375180ceb4449c026b_1_690x111.png'>](https://www.drivendata.org/)
<br><br>

![Banner Image](https://s3.amazonaws.com/drivendata/comp_images/tileimage.jpg)

# Keeping it Fresh: Predict Restaurant Inspections
## Goal of the Competition
The goal for this competition is to use data from social media to narrow the search for health code violations in Boston. Competitors will have access to historical hygiene violation records from the City of Boston — a leader in open government data — and Yelp's consumer reviews. The challenge: Figure out the words, phrases, ratings, and patterns that predict violations, to help public health inspectors do their job better.

## What's in this Repository
This repository contains code volunteered from leading competitors in the [Keeping it Fresh: Predict Restaurant Inspections](https://www.drivendata.org/competitions/5/) on DrivenData.

#### Winning code for other DrivenData competitions is available in the [competition-winners repository](https://github.com/drivendataorg/competition-winners).

## Winning Submissions

Place |Team or User | Score | Summary of Model
--- | --- | --- | --- 
1 | LilianaMedina | 0.8901 | I averaged the predictions of a random forest and a gradient boosted model.
2 | qwang | 0.8931 | My approach was focused almost strictly on feature engineering. I used scikit-learn’s implementation of random forests in Python.
3 | furiouseskimo | 0.9113 | I built four models for each target (random forest, extra random trees, gradient boosting machine, l2 logistic regression) and blended the predictions from these models to get my final submission.


#### Winner's Interview: ["Announcing the Results of our Keeping It Fresh Competition"](http://blog.drivendata.org/2015/11/06/keeping-it-fresh-results/)

#### Benchmark Blog Post: ["From raw Yelp reviews to a model of hygiene violations (in 3 easy steps)"](http://blog.drivendata.org/2015/05/07/keeping-it-fresh-benchmark/)
