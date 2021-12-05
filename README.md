# DeepLearning_Handwritten-Signature-Forgery-Detection

Abstract:
Handwritten signatures are very important in our social and legal life for verification and authentication.
A signature can be accepted only if it is from the intended person. The probability of two signatures made
by the same person being the same is very less. Many properties of the signature may vary even when two
signatures are made by the same person. So, detecting a forgery becomes a challenging task.
The goal of this project is to detect the forgery signature. Banking, Insurance, Healthcare, Copyright, and
Intellectual Property Rights, Regulatory and Government Compliance will benefit from this project.

Design:
In our project, a solution based on Convolutional Neural Network (CNN) is presented where the model is
trained with a dataset of signatures, and predictions are made as to whether a provided signature is
genuine or forge

Data:
The dataset contains the signature of user both genuine and forged. In the dataset the directory number 
says the name of the user and it's classified into two: Geniune and forged.
Found the dataset on the Kaggle website: Here.
Algorithms:
Using the sequential model from Keras framework has been 1649 for training and 500 for testing in a 
dataset. By Adaptive Moment Optimizer (ADAM) and Root Mean Square Propagation (RMS) models.

Tools:
• Technologies:
Python -Jupyter Notebook.
• Libraries:
Pandas –NumPy –Matplotlib – Keras – sklearn – Tensorflow - cv2 – os – glob – Skimage – gc.
