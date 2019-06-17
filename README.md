# Submission for Safety Challenge for Grab AI Competition

## Personal Objectives and Aims
This is purely for personal interested in exploring a dataset that is different from what I've previously worked with. In particular, one of the main challenges I feel is feature extraction from time series data from each trip. As such, the notebook does not explore much algorithm selection or indepth ensembling/stacking etc. My personal aim is to explore different feature extraction methods/ideas which would allow for decent results using a low footprint algorithm (read: probably not neural networks with more than 3 layers). I've also unfortunately not had as much time as I hoped during the competition period.

Hopefully there will be some ideas which anyone reading this might find interesting!

## Brief Explanation

There is one preprocessing step which I've not included in the code, which is joining up the 10 CSV files with the raw feature data. My personal choice is to use bash for this job.

* The first section is on preprocessing, including deleting duplicates and erroneous entries in the data set
* Section 2 covers some ideas on augmenting the raw features, using some basic physics
* Section 3 covers using tsfresh and some ideas on manually getting features
* Sections 4 and 5 are rather incomplete, in which I try running a few sklearn algorithms and simple neural networks to test the features.

