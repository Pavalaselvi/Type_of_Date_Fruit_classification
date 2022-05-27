# Type_of_Date_Fruit_classification

PROBLEM STATEMENT:
 Create a classification model to type of the Date Fruits based on external
 appearance features provided in the dataset.
 
 
 CONTEXT:
 A great number of fruits are grown around the world, each of which has various types.
 The factors that determine the type of fruit are the external appearance features such
 as color, length, diameter, and shape. The external appearance of the fruits is a major
 determinant of the fruit type. Determining the variety of fruits by looking at their external
 appearance may necessitate expertise, which is time-consuming and requires great effort. The
 aim of this study is to classify the types of date fruit, that are, Barhee, Deglet Nour, Sukkary,
 Rotab Mozafati, Ruthana, Safawi, and Sagai by using different machine learning methods. In
 accordance with this purpose, 898 images of seven different date fruit types were obtained via
 the computer vision system (CVS). Through image processing techniques, a total of 34
 features, including morphological features, shape, and color, were extracted from these images.
 
DETAILS OF FEATURES:
The columns names are as follows:
1. AREA
2. PERIMETER
3. MAJOR_AXIS
4. MINOR_AXIS
5. ECCENTRICITY
6. EQDIASQ
7. SOLIDITY
8. CONVEX_AREA
9. EXTENT
10.ASPECT_RATIO
11.ROUNDNESS
12.COMPACTNESS
13.SHAPEFACTOR_1
14.SHAPEFACTOR_2
15.SHAPEFACTOR_3
16.SHAPEFACTOR_4
17.MeanRR
18.MeanRG
19.MeanRB
20.StdDevRR
21.StdDevRG
22.StdDevRB
23.SkewRR
24.SkewRG
25.SkewRB
26.KurtosisRR
27.KurtosisRG
28.KurtosisRB
29.EntropyRR
30.EntropyRG
31.EntropyRB
32.ALLdaub4RR
33.ALLdaub4RG
34.ALLdaub4RB
35.Class (DOKOL, SAFAVI, ROTANA, DEGLET, SOGAY, IRAQI, BERHI)



BRIEF DESCRIPTION :
In this Project,I have coded in such a way that first handled the null values in the dataset and after removing it , splited the data into training and test data.Then applied the following models on the training dataset and generated the predicted value for the test dataset.
a) Decision Tree Classification
b) Random Forest Classification
c) KNN Classification
d) Logistic Regression
then predicted the type of date fruits for the test data and computed the confusion matrix and classification report for each of these models.
