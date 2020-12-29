# classification-galaxies-stars-and-quasars

## Project description: 

This project aims to use machine learning classification techniques to classify stellar objects: galaxies, stars and quasars. We are using data from the Sloan Digital Sky Survey. The Sloan Digital Sky Survey is a project which offers public data of space observations. 

For this purpose a special 2.5 m diameter telescope was built at the Apache Point Observatory in New Mexico, USA. The telescope uses a camera of 30 CCD-Chips with 2048x2048 image points each. The chips are ordered in 5 rows with 6 chips in each row. Each row observes the space through different optical filters (u, g, r, i, z) at wavelengths of approximately 354, 476, 628, 769, 925 nm.

The telescope covers around one quarter of the earth's sky - therefore focuses on the northern part of the sky.

**For more information about this project - please visit their website. Our dataset is provided there**

http://www.sdss.org/



## Methodologies:

We start exploring visually the data in order to try to understanding patterns in the quantitative variables gathered from the measurements. In order to solve the classification problem, after doing some feature engineering and a train/test split of 33% size, we use the ensemble learning XGBoost algorithm in order to retrieve the features hierarchy importances. In a second step in order to validate the model we use GridSearchCV with 2 folds and obtain the score on the test set  for the 1st fold 0.9904477611940299 and 0.991044776119403 for the second.




## Code and resources used:
**Python version:** 3.7
**Packages/libraries used:** pandas, numpy, matplotlib, seaborn, scikitlearn
**Dataset:** available at http://www.sdss.org/
