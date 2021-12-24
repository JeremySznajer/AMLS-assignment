APPLIED MACHINE LEARNING SYSTEM ELEC0134 21/22

Introduction

Data obtained from:

Sartaj Bhuvaji, Ankita Kadam, Prajakta Bhumkar, Sameer Dedge, and Swati Kanchan, “Brain Tumor Classification (MRI).” Kaggle, 2020, doi: 10.34740/KAGGLE/DSV/1183165

contained 3000 images of brain MRIs which were used for training and 200 which the algorithm did not learn from which were used for testing. 3 Algorithms were produced 2 which used binary regression to determine if the patient had a tumor or not and one classification algorithm which not only detected the presence of a tumor but also which of three types it could be. One of the regression algorithms was done via SVM and one using Deep Learning. The multiclass algorithm used Deep Learning.

All algorithms were tested and had hyper-parameters tailored.

This repository includes the models labelled final or Fin for the final version and testing versions and also earlier versions to show changes made. It also includes the datasets and other files which output the results at various stages to check on errors.

plot_learning_curve.py contains a modified version of a file by the same name which can be found at:

https://scikit-learn.org/stable/auto_examples/model_selection/plot_learning_curve.html

It was used at the end of the SVM to plot 3 sets of curves.

Instructions:
Ensure when running the files in the correct environment that all the necessary libraries have been downloaded. If they are not then install them before attempting to run the code. If using Anaconda search for them when building your environment otherwise you can make use of Pip install. In case of errors update any libraries or function names to their most recent versions.

Note that changing any names or labels will require consistency throughout the algorithm and also that certain functions require different types and therefore should be kept in the same type. If using different datasets note that some functions such as the PCA take as an argument the maximum value and therefore if using a different dataset make sure there aren't fewer items than 150.
