This can be achived by creating a modeling pipeline where the first step is the statistical imputation, then the second step is the model, This can be achived using the pipeline class, in the Pipeline we use 
SimpleImputer with a mean strategy followed random forest model.The pipeline is evaluated using three repeats 0f 10-fold cross-validation and reports the mean classifcation accuracy on the dataset as about 86.1 percent
which is a good score.
