# Letter-Recognition-Using-SVM

It's now time to get your hands dirty and solve an interesting letter recognition problem using SVMs. It contains the 26 English alphabets as classes, so it's a multiclass classification problem with 26 classes.
The data set is taken from the UCI repository. You can access the data dictionary of the letter recognition data set here. 
Each row in the data set represents an image of a handwritten alphabet, . Using some basic image processing, the images are converted into m X n pixels , where m and n depend on the size and resolution of the original image. Each pixel contains numeric values, with higher values denoting the presence of dense 'ink'. In the pixels where nothing is written, the pixel value is 0.
A pixel is called 'on' if it contains to a positive numeric value, else it is called 'off'.
Using the pixelated images, 16 features are derived for each image, such as the width of the box, the ratio of the mean variance of x divided by the width of the box, etc.  

 
