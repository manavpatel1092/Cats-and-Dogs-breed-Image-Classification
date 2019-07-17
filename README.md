# Pet-Image-Classification

You can download the Oxford Dataset of Cats and Dog breed Classification from:
http://www.robots.ox.ac.uk/~vgg/data/pets/data/annotations.tar.gz

- We have used pet dataset which contains 37 categories of pet images with roughly 200 images for each class. The images have a large variation in scale, pose, and lighting. All images have an associated ground truth annotation of the breed, head ROI, and pixel level trimap segmentation. The following annotations are available for every image in the dataset: (a) species and breed name; (b) a tight bounding box (ROI) around the head of the animal; and (c) a pixel level foreground-background segmentation (Trimap).

- We built a logistic regression and SGD Classifier model with preprocessing using the VGG16 weights trained on imagenet. Achieved a precision of 87% on the test set.
