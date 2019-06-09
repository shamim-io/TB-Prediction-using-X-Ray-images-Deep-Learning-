# TB-Prediction-using-X-Ray-images-Deep-Learning-
TB Prediction using X-Ray images (Deep Learning)

Description: The standard digital image database for Tuberculosis is created by the National Library of Medicine, Maryland, USA in collaboration with Shenzhen No.3 People’s Hospital, Guangdong Medical College, Shenzhen, China. The Chest X-rays are from out-patient clinics, and were captured as part of the daily routine using Philips DR Digital Diagnose systems. Number of X-rays:

336 cases with manifestation of tuberculosis, and
326 normal cases. Image parameters:
Format: PNG
Image size varies for each X-ray. It is approximately 3K x 3K.
Problem Statement: Using Deep Learning detect Tuberculosis of a patient by analysing his X-Ray report.

Deep Learning problem
1. Using VGG-19, ResNet50 and Inception-V3 networks build models.
2. Use accuracy to compare performance of the three models.
3. Write a function to tune the threshold of the best model such that the AUC of the model is above x%(let default be 90%) and plot the confusion matrix with that tuned threshold.
