# Diabetic Retinopathy Detection

**Motivation:**
Diabetic Retinopathy is a major cause of vision loss and blindness affecting millions of people across the globe. Although there are established screening methods - fluorescein angiography and optical coherence tomography for detection of the disease but in majority of the cases, the patients remain ignorant and fail to undertake such tests at an appropriate time. The early detection of the disease plays an extremely important role in preventing vision loss which is the consequence of diabetes mellitus remaining untreated among patients for a prolonged time period. 
My personal motivation to start this project is my grandpa, who is a diabetic patient and I noticed him losing his vision. We had taken him to the hospital in the early stage and he is perfectly well now. This project is started to help people like my grandpa where there are not often enough people to notice such vision changes and help them without their situation becoming any worse.


**Tools/technologies/methodologies:**
In this proposed methodology, diabetic retinopathy is being detected using computer vision techniques which are invoking image processing and machine learning techniques. Thus the input retinal fundus images are obtained from the public repository. From the input retinal images, image processing steps such as preprocessing, segmentation, blood vessel extraction have been performed. Machine learning techniques are applied to predict the normal abnormalities and recommend medicinal measures.  In preprocessing, the image acquisition is performed in which the obtained RGB image would be transformed into the grayscale, and also the image would be enhanced for further image processing steps. After preprocessing, optical disk segmentation has been performed. The optical disk is edged and segmented for analysis. Thus this step is very important for the feature extraction process. Canny edge detection techniques are applied to edge and extract the optical disc. The blurred edges are also improved and transmitted for the feature extraction step. In the feature extraction, blood vessel features are extracted. Feature extraction is an important step as based on the features, only classifier model accuracy is dependent. The objective of the feature extraction algorithm is that it should be able to extract meaningful features, objects assisting the normal, abnormal recognition process. The feature vectors consist of the measure values. The neural network obtains the feature vector as the input and performs the classification phase. The neural network has the training model set, which is trained with the colour, feature vector values from the input retinal images. The training model is trained until the error is minimized to an optimized level. This stage is termed the maximum trained phase. After this, the normal diabetic retinopathy is predicted efficiently from the input test images with promising results. 
The order of major steps that we perform in the project are as follows:
1.	Exploratory Data Analysis
2.	Get Train Images
3.	Morphological Operations
4.	Crop Images Again to Destroy Black Area
5.	Flatten for histogram
6.	apply CLAHE - Contrast-Limited Adaptive Histogram Equalization 
7.	Merge other channels
8.	Median Blur for Avoid Noise
9.	Mask for Bleeding Vein
10.	Apply Mask to Image
11.	One Hot Encoding for DataFrame
12.	Converting to Multi-Label
13.	Img to Array
14.	Train Test Split
15.	Data Generator
16.	Transfer Learning
17.	Save model


**Skills gained (technical and otherwise):**
I’ve become better at drawing insights from data and using it effectively and using the insights drawn for better use cases. I’ve gained a lot of technical skills throughout the process like Exploratory Data Analysis, performing Morphological Operations, applying CLAHE - Contrast-Limited Adaptive Histogram Equalization, Data Generation, Transfer Learning etc. 


**Impact/obstacles:**
This project is a bit large compared to my other projects, so this has made me learn how to deal with large projects. This project made me realise that everything is possible with technology, and we can be helpful to thousands of people out there in need in our own possible way. I’ve faced few difficulties too and was successful in most of the cases. From this, I’ve learnt that independent of the result, we should step out of our comfort zone and try! We will eventually get the result.
