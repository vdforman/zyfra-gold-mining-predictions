# zyfra-gold-mining-predictions
This projects objective was to create a machine learning model that can predict the amount of pure gold that will be attained from the purification process of gold ore.

The dataset consisted of rows of timestamps of a gold purification process. Every hour of every day, there were measurements taken of concentrations of metals at every stage of the process. There were many complications to face when cleaning the data, but with reasonable conclusions, I was able to have a dataset that I could work with.

After testing several types of models, I was able to create a model with parameters that attain a sMAPE lowest value of 8.9% which was great given that it was less than 10%. This was done with a RandomForest Model.
