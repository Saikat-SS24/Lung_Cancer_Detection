# Project Title

Lung Cancer Detection

# Project Description

Lung cancer is the crucial disease, which is one of the most human beings and is considered one of the deadliest cancer in the world and it causes to millions of deaths around the globe. Therefore early detection and classification of lung cancers can save millions of lives. In recent times, machine learning has been a better technique for diagnosing lung cancer. In recent times, the need for the application of machine learning in health care has become crucial. Most healthcare administrators and researchers use various machine learning techniques to improve diagnosis, detection, and prediction of health related diseases to support experts in decision making. This study focused on the application of machine learning methods to diagnose lung cancer. The research identified the exiting prediction methods and tools used to detect, predict, compare lung cancer systematically. However, the conventional methods were failed to give result the better classification performance. We present an approach to detect lung cancer from CT scans using deep learning. We depict a pipeline of pre-processing techniques to highlight lung regions to cancer and extract features. Thus, this is implemented using deep learning convolutional Neural Network, Mobilenet and VGG-16 model for lung cancer detection and classification operations. Initially, pre-processing of Computed Tomography (CT) based lung images were performed using histogram equalization and thresholding segmentation, which effectively localizes the region of interest (ROI) of cancer.

## Pre-Processing

At first CT scan images are taken as dataset and the dataset contains three types of lung cancer adenocarcinoma, large cell carcinoma, squamous cell carcinoma. For image pre-processing histogram equalization operation is performed on the dataset to get the clear images and thresholding segmentation operation is performed to get segmented images with proper outline.

- Histogram Equalization -> Histogram Equalization is a computer image processing technique used to improve contrast in images. It accomplishes this by effectively spreading out the most frequent intensity values, i.e. stretching out the intensity range of the image. This method usually increases the global contrast of images when its usable data is represented by close contrast values. This allows for areas of lower local contrast to gain a higher contrast.

- Thresholding Segmentation -> Thresholding is a type of image segmentation, where we change the pixels of an image to make the image easier to analyze. In thresholding, we convert an image from colour or grayscale into a binary image, i.e., one that is simply black and white. Most frequently, we use thresholding as a way to select areas of interest of an image, while ignoring the parts we are not concerned with.


## Neural Nets

- CNN -> A Convolutional Neural Network (CNN) is a type of deep learning algorithm that is particularly well-suited for image recognition and processing tasks. It is made up of multiple layers, including convolutional layers, pooling layers, and fully connected layers. The convolutional layers are the key component of a CNN, where filters are applied to the input image to extract features such as edges, textures, and shapes. 

- MOBILENET -> Mobilenet is a model which does the same convolution as done by CNN to filter images. It uses the idea of Depth convolution and point convolution which is different from the normal convolution as done by normal CNNs. This increases the efficiency of CNN to predict images and hence they can be able to compete in the mobile systems as well. Since these ways of convolution reduce the comparison and recognition time a lot, so it provides a better response in a very short time and hence we are using them as our image recognition model. 

- VGG-16 -> A convolutional neural network is also known as a ConvNet, which is a kind of artificial neural network. A convolutional neural network has an input layer, an output layer, and various hidden layers. VGG16 is a type of CNN (Convolutional Neural Network) that is considered to be one of the best computer vision models to date. The creators of this model evaluated the networks and increased the depth using an architecture with very small (3 × 3) convolution filters, which showed a significant improvement on the prior-art configurations. They pushed the depth to 16–19 weight layers making it approx — 138 trainable parameters.






