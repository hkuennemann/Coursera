# Introduction to Computer Vision and Image Processing [IBM]
Description from Coursera: Computer Vision is one of the most exciting fields in Machine Learning and AI. It has applications in many industries, such as self-driving cars, robotics, augmented reality, and much more. In this beginner-friendly course, you will understand computer vision and learn about its various applications across many industries.

As part of this course, you will utilize Python, Pillow, and OpenCV for basic image processing and perform image classification and object detection.

This is a hands-on course and involves several labs and exercises. Labs will combine Jupyter Labs and Computer Vision Learning Studio (CV Studio), a free learning tool for computer vision. CV Studio allows you to upload, train, and test your own custom image classifier and detection models.  At the end of the course, you will create your own computer vision web app and deploy it to the Cloud.

This course does not require any prior Machine Learning or Computer Vision experience. However, some knowledge of the Python programming language and high school math is necessary.

Top skills gained in this course: Category: `Image Processing`, `Artificial Intelligence (AI)`, `Opencv`, `Computer Vision`, `Deep Learning`.

## Course Content and Notebooks

### Module 1
Description from Coursera: In this module, we will discuss the rapidly developing field of image processing. In addition to being the first step in Computer Vision, it has broad applications ranging anywhere from making your smartphone's image look crystal clear to helping doctors cure diseases.


### Module 2
Description from Coursera: Image processing enhances images or extracts useful information from the image. In this module, we will learn the basics of image processing with Python libraries OpenCV and Pillow.

#### Notebooks
- 2.1.1_Images_with_python_library_PIL
  - Description: This notebook provides an introduction to image processing with Python. It covers essential techniques such as loading, displaying, and manipulating images using the `Pillow` (PIL) library, and converting images to `NumPy` arrays for advanced processing. Key operations include working with image files, grayscale conversion, color channels, and quantization.
  - Main Topics:
    - *Python Image Libraries*: Overview of image processing tools in Python.
    - *Image Files and Paths*: Handling file formats and paths.
    - *Loading Images*: Using Pillow to open and display images.
    - *Plotting Images*: Visualizing images with Matplotlib.
    - *Grayscale Conversion*: Converting and analyzing grayscale images.
    - *Quantization*: Reducing color levels and observing effects.
    - *Color Channels*: Extracting and analyzing RGB channels.
    - *NumPy Arrays*: Converting Pillow images to NumPy arrays for manipulation.

- 2.1.2_Images_with_python_library_CV
  - Description: This notebook, like the previous one using Pillow (PIL), covers image processing basics but focuses on OpenCV for its advanced capabilities in computer vision. 
  - Main Topics:
    - Same as in 2.1.1_Images_with_python_library_PIL

- 2.2.1_basic_image_manipulation_PIL
  - Description: This notebook teaches image manipulation using the PIL library, focusing on copying, flipping, and cropping images. It covers changing specific pixels, drawing shapes, overlaying text, and superimposing images. The exercises involve practical applications such as flipping and mirroring images, emphasizing the avoidance of aliasing through proper image copying. Various techniques for flipping and cropping images are demonstrated using both array slicing and PIL methods.
  - Main Topics: 
    - Copying Images to Avoid Aliasing
    - Flipping Images
    - Cropping Images
    - Changing Specific Image Pixels
    - Drawing Shapes and Overlaying Text on Images

- 2.2.2_basic_image_manipulation_open_CV  
  - Description: This notebook teaches image manipulation using OpenCV, including copying to avoid aliasing, flipping, cropping, and altering specific pixels. It expands on the previous notebook by focusing on flipping images around different axes and overlaying text and shapes on images, providing additional practical examples and exercises.
  - Main Topics:
    - Same as in 2.2.1_basic_image_manipulation_PIL

- 2.3.2_Histograms_and_Intensity_Transformations
  - Description: This notebook provides a comprehensive tutorial on pixel transformations for image processing, focusing on creating histograms, applying intensity transformations, and using thresholding for image segmentation. The tutorial demonstrates various techniques to enhance image characteristics, such as adjusting contrast and brightness, generating image negatives, and equalizing histograms to improve visual analysis.
  - Main Topics:
    - *Pixel Transforms*: Histograms, Intensity Transformations, Thresholding and Simple Segmentation
    - *Histogram Analysis*: Creating and interpreting histograms, Grayscale histograms, Color channel histograms
    - *Intensity Transformations*: Image negatives, Brightness and contrast adjustments, Histogram Equalization
    - *Thresholding and Segmentation*: Manual thresholding, Automated thresholding using Otsu's method

- 2.4.1_Gemetric_transforms_PIL
  - Description: This notebook provides a tutorial on applying geometric transformations and mathematical operations to images using the Pillow library in Python. It covers techniques for scaling, translating, and rotating images, as well as performing array and matrix operations to manipulate image data.
  - Main Topics:
    - *Geometric Operations*: Scaling, Translation, Rotation
    - *Mathematical Operations*: Array Operations, Matrix Operations

- 2.4.2_Gemetric_transforms_OpenCV
  - Description: This notebook covers techniques such as scaling, translating, and rotating images, as well as performing array and matrix operations to manipulate image data. The primary difference to 2.4.1_Gemetric_transforms_PIL is the use of the cv2 module from OpenCV for image manipulations instead of the PIL module. 
  - Main Topics:
    - Same as in 2.4.1_Gemetric_transforms_PIL

- 2.5.1_Spatial_Filtering-PIL
  - Description: This notebook provides an introduction to spatial operations in image processing using the Pillow library in Python. It covers various filtering techniques, including noise reduction, Gaussian blur, and image sharpening, and demonstrates how to detect edges and apply median filtering. The notebook includes practical examples with images to illustrate the effects of different filters and operations.
  - Main Topics:
    - *Introduction to Spatial Operations in Image Processing*
    - *Linear Filtering*: Filtering Noise, Gaussian Blur, Image Sharpening
    - *Edge Detection*
    - *Median Filtering*

- 2.5.2_Spatial_Filtering
  - Description: This notebook, like the previous one, focuses on geometric operations and mathematical tools in image processing using OpenCV. However, it places a stronger emphasis on practical applications of spatial operations such as linear filtering, Gaussian blur, and edge detection. It introduces various methods for image enhancement and noise reduction, including median filtering and thresholding, and compares different techniques for image sharpening and edge detection. The practical aspect is highlighted through hands-on examples and visualizations of the effects of these techniques.
  - Main Topics:
    - Same as in 2.5.1_Spatial_Filtering-PIL
    - *Thresholding*
    - *Practical applications and visualizations of these techniques*


### Module 3
Description from Coursera: In this module, you will Learn About the different Machine learning classification Methods commonly used for Computer vision, including k nearest neighbours, Logistic regression, SoftMax Regression and Support Vector Machines. Finally, you will learn about Image features.

#### Notebooks
- 3.1_Logistic Regression With Mini-Batch Gradient Descent
  - Description:  This notebook provides a step-by-step guide on how to implement and train a logistic regression model using PyTorch and mini-batch gradient descent. The process includes creating a dataset, defining the model architecture, setting up the loss function and optimizer, and visualizing the training process.
  - Main Topics:
    - Create the Model and Total Loss Function (Cost)
    - Setting the Batch Size using a Data Loader
    - Setting the Learning Rate
    - Train the Model via Mini-Batch Gradient Descent

- 3.2_Digit_Classification_with_Softmax
  - Description: This notebook guides you through the process of building, training, and evaluating a Softmax classifier for digit classification using the MNIST dataset in PyTorch.
  - Main Topics:
    - Download the Training and Validation MNIST Digit Images
    - Create a Softmax Classifier using PyTorch
    - Create a Criterion, Optimizer, and Data Loaders
    - Create a Data Loader and set the Batch Size
    - Train a Model
    - Analyze Results and Model

- 3.3_Support_Vector_Machines_vs_Vanilla_Linear_Classifier
  - Description: This notebook classifies the popular handwritten digit dataset from sklearn, comparing the results of logistic regression and Support Vector Machines (SVM). It demonstrates the use of logistic regression with the multinomial option and SVM for image classification, and evaluates the performance using confusion matrices and k-fold cross-validation.
  - Main Topics:
    - Plotting an Image
    - Preprocess data for Logistic Regression
    - Logistic Regression with SkLearn
    - SVM for Image Classification with SkLearn
    - Comparing both SVM and Logistic Regression with K-Fold Cross Validation


### Module 4
Description from Coursera: In this module, you will learn about Neural Networks, fully connected Neural Networks, and Convolutional Neural Network (CNN). You will learn about different components such as Layers and different types of activation functions such as ReLU. You also get to know the different CNN Architecture such as ResNet and LenNet.

#### Notebooks
- 4.1_Simple_Neural_Network_for_XOR
  - Description: This notebook provides a practical guide to creating and training a neural network with one hidden layer to classify noisy XOR data. It demonstrates how varying the number of neurons in the hidden layer affects the model's performance.
  - Main Topics:
    - Neural Network Module and Training Function

- 4.2_Neural-Network_ReLU_vs_Sigmoid
  - Description: This notebook explores the performance of Sigmoid and ReLU activation functions in neural networks. It defines, trains, and evaluates neural networks with these activation functions on the MNIST dataset, and compares the results.
  - Main Topics:
    - Neural Network Module and Training Function
    - Sigmoid and Relu activation functions

- 4.3_Training_A_Neural-Network_with_Momentum
  - Description: This notebook demonstrates how varying momentum parameters affect the convergence rate of a neural network during training. It involves training different neural network models with various momentum values and comparing their results in terms of loss and accuracy.
  - Main Topics:
    - Neural Network Module and Function for Training
    - Train Different Neural Networks with Different Momentum Values

- 4.4_CNN
  - Description: This notebook demonstrates how to use a Convolutional Neural Network (CNN) to classify handwritten digits from the MNIST database. It includes steps for reshaping images for faster processing, building a CNN model, training the model, and analyzing the results.
  - Main Topics:
    - Convolutional Neural Network
    - Define Softmax, Criterion function, Optimizer, and Train the Model

- 4.5_Data_Augmentation
  - Description: In this notebook, we train a Convolutional Neural Network (CNN) on both regular and augmented (rotated) data to demonstrate how data augmentation can improve model generalization. The goal is to show that training with augmented data enhances performance on realistic, imperfect images.
  - Main Topics:
    - Convolutional Neural Network
    - Data Augmentation


### Module 5
Description from Coursera: In this module, you will learn about object detection with different methods. The first approach is using the Haar Cascade classifier, the second one is to use R-CNN and MobileNet.

#### Notebooks
- 5.1_use-objectdetection-faster-r-cnn
  - Description: This notebook provides a practical introduction to using Faster R-CNN for object detection. It is about how to detect and localize objects within images, leveraging a pre-trained model on the COCO dataset, and use the likelihood of object predictions to refine the results.
  - Main Topics:
    - Faster R-CNN
    - Object Localization
    - Object Detection


## Disclaimer
This project notebook is part of the coursework for "Introduction to Computer Vision and Image Processing" on Coursera (🔗 [Go to course](https://www.coursera.org/learn/introduction-computer-vision-watson-opencv)). It is intended for educational purposes only. For official content and certification, please refer to the Coursera course page.
