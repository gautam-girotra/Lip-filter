# Nose-filter
Using **OpenCV**, face landmark detection is done followed by applying a filter to the nose.
First I perform face detection using the **dlib library's detector** .
Then I perform landmark detection using **shape_predictor** with a .dat file that gives 68 landmarks.
After choosing the landmarks which represent the nose, I create a mask which singles out the nose.
Then I change the colour of the nose and merge it with the original image.

### The program can be used to change the colour of any part of the face by passing the respective landmark indices while calling the filter function.
