# Histopathologic-Cancer-Detection

Project Title: Histopathologic-Cancer-Detection

Project Description: This project implements a generic binary image classifier using four pretrained models - ResNet50, DenseNet121, VGG19, and InceptionV3. The models are trained using the Adam optimizer and binary cross entropy loss. The performance of each model is evaluated using different metrics such as AUC ROC, confusion matrix, precision, and recall. The AUC ROC and confusion matrix are also plotted for each model using Matplotlib.

Motivation: The ability to classify images accurately has a wide range of applications, from medical imaging to self-driving cars. Pretrained models are an effective way to leverage existing state-of-the-art models for image classification tasks. However, the evaluation of these models can be complex and involve multiple metrics. This project aims to provide a generic implementation that can be used for different binary image classification tasks, using a variety of pretrained models, and evaluated using various metrics.

Installation: To run the code, you will need to have Python and PyTorch installed on your machine. You can install PyTorch using the following command: pip install torch. The code also requires NumPy, Pandas, and Matplotlib. You can install these packages using the following command: pip install numpy pandas matplotlib.

Usage: To use the code, you will need to provide your own dataset of binary images and modify the train_dir and test_dir variables accordingly. You can then run the code and it will train and evaluate each of the four pretrained models, outputting the performance metrics and plots.

Contributing: Contributions to this project are welcome and can be made by submitting pull requests. Please ensure that your code follows the PEP8 style guide and includes appropriate documentation and tests.

License: This project is licensed under the MIT License.
