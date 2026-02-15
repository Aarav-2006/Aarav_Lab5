Lab 5: Face Detection and Clustering using K-Means Algorithm

AIM:
The primary objective of this lab is to:
1. Implement face detection using Haar Cascade classifiers 
2. Extract colour-based features (Hue and Saturation) from the detected face
3. Perform unsupervised clustering using the K-Means algorithm
4. Classify a template image (Dr Shashi Tharoor) into one of the discovered clusters
5. Visualise clustering results and analyse the effectiveness of colour-based face classification 

METHOD:
Step 1: Face Detection
1. Loaded Plaksha Faculty group image
2. Converted to grayscale
3. Applied Haar Cascade Classifier with parameters
4. Drew red bounding boxes around detected faces

![image_alt](https://github.com/Aarav-2006/Aarav_Lab5/blob/dd58684281ae32400952d8e22fe4437ca0ea2fc4/face_detection.png)

Step 2:Feature Extraction
1. Converted image to HSV colour space
2.  Extracted mean Hue and Saturation values from each detected face region
3.  Created feature vectors [hue, saturation] for clustering

Step 3: K-means clustering
1.  Applied K-Means algorithm with n_clusters=2, random_state=42
2.  Clustered faces based on Hue-Saturation features
3.  Computed cluster centroids

![image alt](https://github.com/Aarav-2006/Aarav_Lab5/blob/ec96f47970e20e8159a06a62e3b6794e62e1486b/clustering.png)

Step 4: Visualisation
1. Created scatter plots showing Cluster 0 (green), Cluster 1 (blue), and centroids (X markers)
2. Color-coded clusters for clear distinction

   
   

   



