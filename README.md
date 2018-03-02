# Description of this project
In this report, we use the handwritten characters to do the feature extraction and classify the identifying characters among our training data set. 
* Our goal is to classify three characters, period ".", "0" and "1". 
* We first prepare our images from the zip file "pngs" and glob all images that we want to use as our training set in the future. 
* Then we determine six features of the images in order to recognize among our data. 
* After that, we solve the determined matrix to classify the three characters. 
* The approach is the following: We first use quadratic programming to seperate '.' from numbers then use another quadratic programming to differentiate '1' and '0'.
