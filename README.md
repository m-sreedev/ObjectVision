# ObjectVision
 A SVC and RF model that can detect simple shapes.

 ## Data
 The training data for the model was taken from two sources:
 - [Kaggle Four Shapes Dataset](https://www.kaggle.com/datasets/smeschke/four-shapes)
 - [2D geometric shapes dataset](https://data.mendeley.com/datasets/wzr2yv7r53/1)

Out of the six shapes, the four shapes namely triangle,star,square circle were taken from\
Kaggle dataset and the pentagon and hexagon were taken from Mendely Dataset.

## Pre- Processing
OpenCV library was used to detect shapes from images and draw contours.\
The contours form the basis for the vectorization.

## Models
The SVC and RandomForestClassifier modules from the scikit-learn libray\
was used to train the dataset.Accuarcy metrics for each model is calculated.

A function is also made based on the trained model,\
which can take any image with many shapes and label the shapes present in them.

**PLEASE NOTE: Kindly unzip the shapes files before running the notebook.**
