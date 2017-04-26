Image Classifier for classifying paintings based on Google's Inception engine.
Trains the last layer of the inception engine's CNN (Retraining).

Requirements:

1. Docker
2. Tensorflow

Usage:

If you want to add new painters, just add folders in the painter_images folder.
To classify an image:

python label_images.py img_name.jpg

NOTE: image must be of jpg format
