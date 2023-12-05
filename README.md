# nn_f23_shellfish

### Project Proposal
- Team Members: Sidra Hussain, Josie Libbon, Karl Simon
### Project Overview: 
- We will be doing the Bounding Box project, which is implementing a convolutional neural network model in Tensorflow that can determine the bounding box for set objects. We plan on first implementing a single object Bounding Box model and if time allows we plan on implementing a multi-object Bounding Box model.

### Research: 
#### Karl:
1. Theory behind how object detection works. Includes explanation about how state of the art bounding box predictors work. https://machinelearningmastery.com/object-recognition-with-deep-learning/
2. Collection of TF functions for visual segmentation. This includes code details about how to draw bounding boxes on the image once an object is detected. models/official/vision/utils/object_detection/visualization_utils.py at 5a182aeccf50f1f966a8241a06063dc57886d73e · tensorflow/models · GitHub
3. Example bounding box detection implemented with detailed explanation of the layers used. https://medium.com/nerd-for-tech/building-an-object-detector-in-tensorflow-using-bounding-box-regression-2bc13992973f
#### Josie:
1. Textbook explaining object detection and bounding boxes with example code using a variety of libraries: http://d2l.ai/chapter_computer-vision/bounding-box.html
2. Comparison of bounding box pretrained models for background info: https://iopscience.iop.org/article/10.1088/1757-899X/844/1/012024/meta
#### Sidra 
1. An explanation of what bounding box is, uses, and best practices for labeling: https://www.ayadata.ai/blog-posts/bounding-boxes-in-computer-vision-uses-best-practices-for-labeling-and-more/#:~:text=Bounding%20boxes%20are%20used%20to,with%20many%20machine%2Dlearning%20algorithms 
2. A simple explanation of how bounding box enables object detection: https://infolksgroup.medium.com/how-bounding-box-enables-object-detection-999b3059974e 
3. A dataset that contains 581 images of various shellfish classes for object detection. These images are derived from the Open Images open source computer vision datasets. This could be a possible dataset to train and develop our bounding box algorithm for: https://public.roboflow.com/object-detection/shellfish-openimages 
4. DeepFashion2 is a comprehensive fashion dataset. It contains 491K diverse images of 13 popular clothing categories from both commercial shopping stores and consumers. This could be a possible dataset to train and develop our bounding box algorithm for: https://github.com/switchablenorms/DeepFashion2 
