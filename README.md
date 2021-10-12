# Chest X-Ray Images (Pneumonia Detector)

Table of Content 


 1. [Dataset](#Dataset)
 2. [Models_Implementation](#Models_Implementation)

## Dataset

The dataset is organized into 3 folders (train, test, val) and contains subfolders for each image category (Pneumonia/Normal). There are 5,863 X-Ray images (JPEG) and 2 categories (Pneumonia/Normal).

Chest X-ray images (anterior-posterior) were selected from retrospective cohorts of pediatric patients of one to five years old from Guangzhou Women and Children’s Medical Center, Guangzhou. All chest X-ray imaging was performed as part of patients’ routine clinical care.


![image](https://user-images.githubusercontent.com/47725118/136968970-d66cf567-bfcb-4893-b76b-daa78172630e.png)

The normal chest X-ray (left panel) depicts clear lungs without any areas of abnormal opacification in the image. Bacterial pneumonia (middle) typically exhibits a focal lobar consolidation, in this case in the right upper lobe (white arrows), whereas viral pneumonia (right) manifests with a more diffuse ‘‘interstitial’’ pattern in both lungs.

dataset : https://data.mendeley.com/datasets/rscbjbr9sj/2

## Models Implementation in Keras
### VGG16 
![image](https://user-images.githubusercontent.com/47725118/136970355-4913a3f1-eab3-458e-9346-4e9ee74ff89f.png)



Concerning Vgg16 implementation , I did some transfer learning by making the top layer Compatible for the Task , Binary Categoration ( Sigmoid activation ) 

### Efficient Net 

![image](https://user-images.githubusercontent.com/47725118/136971556-f7920db9-cfdd-4409-8812-38bb112b01f4.png)

