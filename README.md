<h3>About Dataset</h3>
The dataset is a collection of images of alphabets from the American Sign  Language, separated in 29 folders which represent the various classes.<br>
The dataset contains: <br>
-The training data set contains 87,000 images which are 200x200 pixels.<br> 
-There are 29 classes, of which 26 are for the letters A-Z and 3 classes for SPACE, DELETE and NOTHING.<br>
-These 3 classes are very helpful in real-time applications, and classification.<br>
-The test data set contains a mere 29 images, to encourage the use of real-world test images.<br>

<h3>Dataset Link</h3>
Below is the link for dataset: <br>
(https://www.kaggle.com/datasets/grassknoted/asl-alphabet) 

<h3>Approach</h3>
Here we used and applied the concept of transfer learning. <br>
A pre trained VGG16 model is used to create the structure and then convolution layers are changed accordingly.<br>
We tested the model on test dataset and then it was put to real time usage and was tested on webcam images. <br>
The webcam captured the users hand notation and predicted the symbol shown by the user. <br>

<h3>Result Snapshots</h3>
<img
  src="Letter K.png"
  alt="Alt text"
  title="Letter K"
  style="display: inline-block; margin: 0 auto; max-width: 300px">
