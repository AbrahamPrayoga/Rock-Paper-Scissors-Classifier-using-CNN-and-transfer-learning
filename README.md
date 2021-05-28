# Rock-Paper-Scissors-Image-Classifier
This is my final submission of intro to machine learning course I took in Dicoding Academy. 
I created my first image classifier that can classify whether the image are rock, paper or scissors. 
I'm using CNN and also improved it by using pretrained model called MobileNetV2. 

## The dataset
The dataset has 3 folder that represent rock, paper and scissor. You can find it on this link below:
<br> https://www.kaggle.com/drgfreeman/rockpaperscissors

Here are the datas we have looks like. 
![image](https://user-images.githubusercontent.com/64680057/119947832-6260be00-bfc2-11eb-93f6-3afdd4543763.png)

## Checkpoint
In order to get 5 stars score, I need to meet this criterias:
1. Dataset should be split into train and validation set
2. The size of validation set must be 40% of the total data (training data has 1314 sampel and validasi data has 874 sampel).
3. Should conduct data augmentation. 
4. Implement image data generator.
5. Model should using sequential model.
6. Duration of the training should not exceed 30 minutes.
7. Worked on Google Colaboratory.
8. Can predict the image that we upload to the Colab
9. 96% or more accuracy.
10. Implement 3 techniques outside the modul

## Steps
I'm doing this project based on machine learning workflow I learnt from this course and other sources from Data Expert.
1. Data Collecting (download & extract)
2. Data Preprocessing
    - Dataset split
    - Data Augmentation
3. Build basic sequential model
    - Preparation (Create Callback & Visual Function)
    - Create Basic Model with CNN
4. Model Fitting, Visualize
5. Create Improved Model: Transfer Learning using MobileNetV2
6. Predict photo using trained models




