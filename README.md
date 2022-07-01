# Image Segmentation on Nuclei Cell Project
 
Title: Image Segmentation on Nuclei Cell Project

Project Description: This project is to create image segmentation on nuclei cell using U-Net and MobileNetV2 as base model. 

Details: This project is using nuclei cell image dataset provided in https://www.kaggle.com/c/data-science-bowl-2018. The necessary zip file are stage_1_train.zip and stage_1_test.zip. Those zip file unzipped and save the train and test folders in the project folder. Every folder contains folders and every that folder contain images and masks. The masks will be a label and images will be a features. MobileNetV2 applied as base model and U-Net applied as an additional layer. The U-Net is suitable for image segmentation in which downsampling the images and upsampling the images which the output is the masks. The model is running and predict the images with suitable masks. 
