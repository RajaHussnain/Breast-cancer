The problem statement:

In this project 800 breast ultrasound images along with their mask(ground truth) files that have been manually classified into benign, malignant and normal labels. To train a CNN resnet model is used and the model is evaluated on an unseen test data. CNNs prove to be the most effective solutions for addressing image classification/segmentation and computer vision problems.

Two Approaches are used:

1: Without mask files

2: Utilizing mask files by creating overlay


Confusion matrix and classifcation reports are used to score the performance of the model on both approaches. The importonce of the mask(ground truth) files and overlaying the images to improve model accuracy has been done.

Further work:

A 3rd aaproach can also leverage where masks and score using the DICE coefficient can be done. Which is not cover in this notebook.

