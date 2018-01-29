# child abusive image classifier
Image Classifier to detect child abuse , using Python and Tensorflow models trained with around 15000 training images.

This is the Google Drive link for Trained Data Models for 
  1. Face Identification in the image
  2. Child Detection
  3. Abusive Content Detection
  4. The content , if found abusive is then blurred out.
  
  Find the trained model in this drive link:
  
https://drive.google.com/drive/folders/1SnEcx2YtM-soUJPXsEqkLURcrX7mBZhi?usp=sharing

Place the above three downloaded folders in the folder where $run.sh is located

# Installation: (Mac OS)
  brew install python (Python 2.7.3)
  pip install tensorflow (Tensorflow)
  pip install opencv-python (cv2)

# To run:
  $ ./run.sh
  
# Note
This is a trained model and doesnot contain the training script. This model assumes that dark coloured images with a black color bar at the bottom as abusive images. 

# Future Works
Model will be trained with real abusive images and improve the prediction accuracy over 90% 
We are also trying to train this model with more than 50,000 images. If you have any dataset for identifying faces, adult/kid, abusive images, please feel free to contribute.

Also, steps to replicate this in windows will be added

# Credits
Kevinton B, Neil S Paul, Daniel Raj, Dhinkar.

Made during SRM Hackathon 18
