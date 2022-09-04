# Portfolio-Project-3
Tensorflow 2 Object Detection API

# Abstract

We train an object detection model from the Tensorflow 2 Object Detection API on a public dataset of people wearing facemasks taken from the [Roboflow Public Datasets](https://public.roboflow.com/). Specifically we use the dataset from this link [Mask Wearing Dataset
](https://public.roboflow.com/object-detection/mask-wearing)

Additionally, we evaluate the trained model on a validation dataset and a test dataset. We use Tensorboards to display the results of evaluation. 

Finally, we also use a trained model to do inference on photos taken from a webcam photos.  

In this repo there are two colab notebooks - one for training a model and one for performing inference with a webcam, a SavedModel file containing a trained model, and a .py script that is was made to replace a file from the TF2 OD source code for the goals of this project. 
