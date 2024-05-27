# Project Name
  Melanoma Skin Cancer Detection


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)



## General Information
In cancer, there are over 200 different forms. Out of 200, melanoma is the deadliest form of skin cancer. The diagnostic procedure for melanoma starts with clinical screening, followed by dermoscopic analysis and histopathological examination. Melanoma skin cancer is highly curable if it gets identified at the early stages. The first step of Melanoma skin cancer diagnosis is to conduct a visual examination of the skin's affected area. Dermatologists take the dermatoscopic images of the skin lesions by the high-speed camera, which have an accuracy of 65-80% in the melanoma diagnosis without any additional technical support. With further visual examination by cancer treatment specialists and dermatoscopic images, the overall prediction rate of melanoma diagnosis raised to 75-84% accuracy. The project aims to build an automated classification system based on image processing techniques to classify skin cancer using skin lesions images.

In the skin biopsy, the dermatologist takes some part of the skin lesion and examines it under the microscope. The current process takes almost a week or more, starting from getting a dermatologist appointment to getting a biopsy report.
 The aims to shorten the current gap to just a couple of days by providing the predictive model.
 The approach uses Convolutional Neural Network (CNN) to classify nine types of skin cancer from outlier lesions images. This reduction of a gap has the opportunity to impact millions of people positively.

 The overarching goal is to support the efforts to reduce the death caused by skin cancer. The primary motivation that drives the project is to use the advanced image classification technology for the well-being of the people. Computer vision has made good progress in machine learning and deep learning that are scalable across domains.


The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images.



## Technologies Used

Module_Name: Version

pathlib: built-in module, no specific version

os :    built-in module, no specific version

numpy   : 1.24.3   

pandas  : 1.5.3`

matplotlib: 3.7.1

PIL :9.4.0

tensorflow : 2.16.1


To classify skin cancer using skin lesions images. To achieve higher accuracy and results on the classification task, I have built custom CNN model.

- Rescalling Layer - To rescale an input in the [0, 255] range to be in the [0, 1] range.
- Convolutional Layer - Convolutional layers apply a convolution operation to the input, passing the result to the next layer. A convolution converts all the pixels in its receptive field into a single value. For example, if you would apply a convolution to an image, you will be decreasing the image size as well as bringing all the information in the field together into a single pixel. 
- Pooling Layer - Pooling layers are used to reduce the dimensions of the feature maps. Thus, it reduces the number of parameters to learn and the amount of computation performed in the network. The pooling layer summarises the features present in a region of the feature map generated by a convolution layer.
- Dropout Layer - The Dropout layer randomly sets input units to 0 with a frequency of rate at each step during training time, which helps prevent overfitting.
- Flatten Layer - Flattening is converting the data into a 1-dimensional array for inputting it to the next layer. We flatten the output of the convolutional layers to create a single long feature vector. And it is connected to the final classification model, which is called a fully-connected layer.
- Dense Layer - The dense layer is a neural network layer that is connected deeply, which means each neuron in the dense layer receives input from all neurons of its previous layer.
- Activation Function(ReLU) - The rectified linear activation function or ReLU for short is a piecewise linear function that will output the input directly if it is positive, otherwise, it will output zero.The rectified linear activation function overcomes the vanishing gradient problem, allowing models to learn faster and perform better.
- Activation Function(Softmax) - The softmax function is used as the activation function in the output layer of neural network models that predict a multinomial probability distribution. The main advantage of using Softmax is the output probabilities range. The range will 0 to 1, and the sum of all the probabilities will be equal to one.


## Conclusions
In this project, we developed a convolutional neural network (CNN) to detect different types of skin cancer from medical images. The objective was to leverage the power of deep learning to aid in the early diagnosis and classification of skin cancer, which is crucial for effective treatment and patient outcomes. The following key points summarize our findings and the impact of our work:

Model Performance:

Our CNN model achieved a high accuracy in distinguishing between various types of skin cancer, including melanoma, basal cell carcinoma, and squamous cell carcinoma.
Through rigorous training and validation processes, we ensured that the model is robust and generalizes well to unseen data.

Data Utilization:

We utilized a large and diverse dataset of dermoscopic images, which was essential for training an effective model.
Data augmentation techniques were employed to enhance the dataset, allowing the model to learn invariant features and improve its performance.

Technological Impact:

The implementation of CNNs for skin cancer detection demonstrates the potential of deep learning in the field of medical diagnostics.
Our model can serve as a decision support tool for dermatologists, reducing the time and effort required for manual examination and potentially increasing diagnostic accuracy.

Clinical Implications:

Early detection of skin cancer is critical in reducing mortality rates and improving patient prognosis. Our model contributes to this by providing a reliable method for early diagnosis.
The integration of this technology in clinical settings could streamline the diagnostic process, allowing for timely and more frequent screenings.


## Acknowledgements

- This project link on Github [https://github.com/sachin1311876/Melanoma_Detection_Assignment_Sachin_khandelwal).


## Contact
Created by [@sachin1311876] - feel free to contact me!

Sachin Khandelwal

