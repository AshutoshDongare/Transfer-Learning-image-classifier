# Tensorflow-Transfer-Learning

This repo contains a sample to classify if an image has Pizza or Donuts using latest Tansorflow version 2.1.0 and transfer learning on top of MobileNet V2

Tensorflow provides a sample transfer learning using tensorflow prebuilt TFRecords based dataset. there is no clear way to use your own custom
dataset and build a custom classifier. 

This script shows how to load custom image dataset and apply transfer learning to have your own custom image classifier with low number of image
samples and low training time.

Transfer learning allows you to retrain an existing object detection model like MobileNet V2 which is pre trained on large image dataset with Multiple layer CNN 
thus you do not need to have large number of image samples for your custom classifier. 

This scrip also shows how to save, load and predict on the trained custom model.

The custom dataset used for this sample is also provided as a part of this repo. Please extract dataset and place in the same folder where the script is placed.

Please email me if you need more details / help on transfer learning or this repo.
