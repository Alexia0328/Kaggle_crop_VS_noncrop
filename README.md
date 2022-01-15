# Kaggle_crop_VS_noncrop

This Kaggle competition is about the prediction of crop harvest on the subset of CropHarvest[2] dataset. In this binary classification task, each data point with feature x ∈ R18×12 is expected to be classified as crop (1) or non-crop (0) land. Machine learning models are implemented and train on a dataset of over 60, 000 labeled samples. 

In our attempt, random forest (RF), AdaBoost and XGBoost are implemented and tuned to predict the test label. Moreover, we normalize the features before learning/prediction and adopt 10-fold cross-validation on F 1 score to determine best model. The best achieved performance is 0.99757 on Kaggle public leaderboard, 0.99779 on Kaggle private leaderboard both by RF.
