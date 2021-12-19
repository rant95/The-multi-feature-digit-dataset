# The-multi-feature-digit-dataset
R project

We will analyze a data set including 1500 individuals representing each one a number from 0 to 9. Each of these numbers is modeled by 650 variables. The goal of our report is to find the best ways to predict a digit described by these different variables, either from a point of view of temporal performance (a criterion particularly in the context of massive data analysis) and and the accuracy of the predictions.

Dataset Pixel
https://rpubs.com/lov95/635421

Dataset Fourier & fac
https://rpubs.com/lov95/635429


This dataset consists of features of handwritten numerals (`0'--`9')
extracted from a collection of Dutch utility maps. 200 patterns per
class (for a total of 2,000 patterns) have been digitized in  binary
images. These digits are represented in terms of the following six
feature sets (files): 

1. mfeat-fou: 76 Fourier coefficients of the character shapes; 
2. mfeat-fac: 216 profile correlations; 
3. mfeat-kar: 64 Karhunen-Love coefficients; 
4. mfeat-pix: 240 pixel averages in 2 x 3 windows; 
5. mfeat-zer: 47 Zernike moments; 
6. mfeat-mor: 6 morphological features. 

In each file the 2000 patterns are stored in ASCI on 2000 lines. The
first 200 patterns are of class `0', followed by sets of 200 patterns
for each of the classes `1' - `9'. Corresponding patterns in different
feature sets (files) correspond to the same original character.
