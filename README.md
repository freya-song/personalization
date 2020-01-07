# Personalization Final Project
project-2-final-jlyc-fp created by GitHub Classroom

Team members: Xiao Ji (xj2247@columbia.edu, xj2247), Xinyi Liu (xl2904@columbia.edu, xl2904), 
Jiaying Chen (jc5299@columbia.edu, jc5299), Duanyue Yun (dy2400@columbia.edu, dy2400)

In this project, we used the Yelp dataset to build a recommendation system. We implemented 2 models: collective matrix factorization using the cmfrec package and factorization machine using the lightFM package. We compared the models against 2 baselines (bias and pure matrix factorization) and evaluated the models based on accuracy metrics and catalog coverage.

Please find the **Final Report.ipynb** for our final report.

Repository contents:
* Codes folder
  + Bias baseline & user, item segmentation.ipynb: bias baseline model, user and item segmentation, build user attributes
  + CMF.ipynb: code for collective matrix factorization
  + Business.ipynb: exploratory analysis on business.json
  + MF baseline - ALS.ipynb: Matrix Factorization (using Spark ALS) baseline model
  + lightFM - Feature selection.ipynb: Factorization machine model feature selection
  + lightFM - cross validation.ipynb: Factorization machine model hyper-parameter cross validation
  + lightFM full dataset - overall results.ipynb: Factorization machine model full dataset precision and AUC
  + lightFM full dataset - precision by segment.ipynb: Factorization machine model full dataset precision by active/moderate/non-active users and popular/moderate/unpopular items
  + lightFM full dataset - auc by segment.ipynb: Factorization machine model full dataset AUC by active/moderate/non-active users and popular/moderate/unpopular items
* Images folder
  + Images included in final report
