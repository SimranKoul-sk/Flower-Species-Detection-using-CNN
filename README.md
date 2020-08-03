# Flower-Species-Detection-using-CNN

PROPOSED METHODOLOGY:
Modern search engines provide methods to visually search for a query image that contains a flower, but it lacks robustness because of the intra-class variation among millions of flower species around the world. So, we use a Deep learning approach using Convolutional Neural Networks (CNN) to recognize flower species with high accuracy. We use the Oxford dataset which was made by the use of electronic items like a built-in camera in mobile phones and also a digital camera. Feature extraction of flower images is performed using a Transfer Learning approach (i.e. extraction of complex features from a pre-trained network). We also use image augmentation and image processing techniques to extract the flower images more efficiently. 

EXPECTED OUTPUT:
After the experimental analysis and using different pre-trained models, we achieve an accuracy of 85%. Further advancements can be made by using optimization parameters in the neural nets.

ARCHITECTURE:-

RESEARCH FRAMEWORK:
In Deep Learning, CNNs are usually applied for Computer Vision applications that involve Image Classification and Object Recognition. We use VGG19 net, which has pre-trained CNNs, padding and pooling layers embedded in the architecture which is applied to the dataset after the segmentation part, this increases the accuracy of the model. This variant net is built by Visual Geometry Group with model size of 528MB and Top-1 Accuracy being 70.5% and Top-5 Accuracy being 90.0%. This is built by using Convolutional layers (used only 3*3 size), max pooling layers (used only 2*2 size), fully connected layers at the end, and a total of 16 layers. The following are the description of layers that constitute the framework:
1.	Convolution using 64 filters
2.	Convolution using 64 filters + Max pooling
3.	Convolution using 128 filters
4.	Convolution using 128 filters + Max pooling
5.	Convolution using 256 filters
6.	Convolution using 256 filters
7.	Convolution using 256 filters + Max pooling
8.	Convolution using 512 filters
9.	Convolution using 512 filters
10.	Convolution using 512 filters + Max pooling
11.	Convolution using 512 filters
12.	Convolution using 512 filters
13.	Convolution using 512 filters + Max pooling
14.	Fully connected with 4096 nodes
15.	Fully connected with 4096 nodes
16.	Output layer with Softmax activation with 1000 nodes

COMPONENTS EXPLAINED:
1. ANACONDA Software: Anaconda is a free and open-source distribution of the Python and R programming languages for scientific computing (data science, machine learning applications, large-scale data processing, predictive analytics, etc.), that aims to simplify package management and deployment. Package versions are managed by the package management system conda. 
2. Gray Level Co-occurrence Matrix (GLCM): A co-occurrence matrix or co-occurrence distribution is a matrix that is defined over an image to be the distribution of co-occurring pixel values (gray-scale values, or colours) at a given offset. Co-occurrence matrices are also referred to as GLCMs (gray-level co-occurrence matrices). Whether considering the intensity or gray-scale values of the image or various dimensions of colour, the co-occurrence matrix can measure the texture of the image. Because co-occurrence matrices are typically large and sparse, various metrics of the matrix are often taken to get a more useful set of features. Texture analysis is often concerned with detecting aspects of an image that are rotationally invariant. To approximate this, the co-occurrence matrices corresponding to the same relation, but rotated at various regular angles (e.g. 0, 45, 90, and 135 degrees), are often calculated and summed. Texture measures like the co-occurrence matrix, wavelet transforms, and model fitting have found application in medical image analysis in particular. Any matrix or pair of matrices can be used to generate a co-occurrence matrix, though their most common application has been in measuring texture in images, so the typical definition, as above, assumes that the matrix is an image. It is also possible to define the matrix across two different images. Such a matrix can then be used for colour mapping.

