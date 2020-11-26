# Vgg-Model-with-transfer-learning
Prerequisite- 
Cohn kanade Dataset or any facial expression detection dataset with image shape more than 75*75.
THe cohn canade dataset can be found at http://www.jeffcohn.net/wp-content/uploads/2020/04/CK-AgreementForm.pdf

This notebook implements the transfer learning with Vgg Model on Cohn Kanade Dataset which consist of 563 facial images towards solving the problem of facial expression detection 

To implement this notebook on Cohn Kanade Dataset, first you need to create two directories namly 'Training dataset' and 'Testing dataset'. 
Then you need to seprate the Cohn kanade dataset images into seven different directories each for different categories
namely Neutral,
Angry,
Disgust,
Sad,
Happy,
Surprise,
and Scared.
Then store these directories into both training and testing directory folder with appropriate number of images.

After the training, the model will be saved attomatically into your current directory. 

