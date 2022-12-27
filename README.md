# computervision
Computer Vision Final Project - Real-Time Face Detection

## This project was assigned by Asst. Prof. Dr. Mehmet Zeki Konyar in ISE 462 course.
##### Opencv 310
##### Java 11
The aim of the project is to detect the nose and mouth of the person or persons, in addition to their frontal faces, live from the camera, and the haar-cascade method was used as a method.

### Face Detection Methods
There are number of strategies for recognizing person’s face. Some of them are adaptive regional blend matching method and generalized matching face detection method. The values of the nodal points on the person’s face plays crucial task in face recognition system. Many researches had been done on LBP and Haar cascading techniques. But either they are using only one algorithm or they are detecting a single face in the image. In the current work two algorithmsare
used to detect the faces in the image containing many faces to calculate the accuracy then the acquired accuracy will becompared by plotting the curve and bar graph to find the efficient algorithm.
There are two types of image positive image and negative image. Positive images are those images which contain the face in that and negative images are the images which contains non-face image. Classifier is a device which decides whether the taken image is negative or positive. It is trained on hundreds of thousands of face and non-face images to learn to classify a new image as face or non-face image correctly. OpenCV provides two pre-trained classifiers Haar Classifier and LBP Classifier. Both
of these classifiers process images in gray-scales as it doesn’t need color information to decide if image has a face or not.

#### Haar Cascading
Haar Cascading is the machine learning method where a classifier is drilled from a great deal of positive and negative photos. The algorithm is put forwarded by Paul Viola and Michael Jones. Haar feature-based cascade classifiers are the classifiers implemented for object detection. This classifier chases machine learning procedure in which a cascade operation is inculcated from the photos to discover items in additional photos. Face detection and facial expressions in an image are also successfully detected. The exercise is finished by offering positive and negative pictures to the classifier. Then the characteristics are drawn out from the picture. Each characteristic is an individual value, which is acquired by subtracting sum of pixels in white rectangle from summation of pixels in black rectangle.In which it detects the faces of different individual in different environments. The Haar-like feature of any size can be calculated in constant time because of integral images.

#### Local Binary Patterns
Local Binary Pattern is a kind of visual course used for categorization on computer vision. LBP is the distinct case of the Texture Spectrum imitation put forwarded in 1990. LBP was first illustrated in 1994. It has since been found to be a strong factor for texture categorization. By utilizing LBP operator, individual photo is examined as a structure of micro-patterns. Then the histogram of LBP is enumerated throughout the face, which encrypts just the circumstances of micro-patterns. The figure of documentation is assembled by splitting face picture toward m minor non over lapping sections such as R0, R1,...,Rm .The original LBP labels the pixels by
threshold the 3 × 3 neighborhood in relation to the central pixel value. In a particular numerical scale the common features, such as edges, lines, point, can be represented by a value. Therefore, it is possible to recognize objects in an image using a set of values extracted a priori
//
