# Landmark-Recognition-with-Google-Vision-Platforms
Landmark recognition tutorials using Google Cloud Vision and AutoML Vision

# Use Google Cloud Vision to Recognize Landmarks
1. Download the Code from:

   https://github.com/mmoussa/cloud-vision/tree/feature/landmark-detection

2. Go to the Google Cloud Platform Console at:

   https://console.cloud.google.com
   
   <img src="https://github.com/mmoussa/Landmark-Recognition-with-Google-Vision-Platforms/blob/master/images/cloud-vision-tutorial/1.PNG" width=300>
   
3. Go to Navigation Menu -> APIs & Services -> Credentials

   <img src="https://github.com/mmoussa/Landmark-Recognition-with-Google-Vision-Platforms/blob/master/images/cloud-vision-tutorial/2.PNG" width=300>
   
4. Create an API key and copy it

   <img src="https://github.com/mmoussa/Landmark-Recognition-with-Google-Vision-Platforms/blob/master/images/cloud-vision-tutorial/3.PNG" width=300>
   
   <img src="https://github.com/mmoussa/Landmark-Recognition-with-Google-Vision-Platforms/blob/master/images/cloud-vision-tutorial/4.PNG" width=300>
   
5. Open the Android project
6. In gradle.properties, add the following:

   ```
   ApiKey = \”your-api-key-here\”
   ```
7. Use app to recognize landmarks from images

   <img src="https://github.com/mmoussa/Landmark-Recognition-with-Google-Vision-Platforms/blob/master/images/cloud-vision-tutorial/scr.jpg" width=175>

---

# Create Custom Models with AutoML Vision
1. Go to Google Cloud Platform Console at:

   http://console.cloud.google.com
   
   <img src="https://github.com/mmoussa/Landmark-Recognition-with-Google-Vision-Platforms/blob/master/images/cloud-vision-tutorial/1.PNG" width=300>
   
2. Go to Navigation Menu -> Vision

   <img src="https://github.com/mmoussa/Landmark-Recognition-with-Google-Vision-Platforms/blob/master/images/automl-vision-tutorial/b1.PNG" width=200>
   
3. Select AutoML Vision Image Classification

   <img src="https://github.com/mmoussa/Landmark-Recognition-with-Google-Vision-Platforms/blob/master/images/automl-vision-tutorial/b2.PNG" width=300>
4. Create a new dataset

   <img src="https://github.com/mmoussa/Landmark-Recognition-with-Google-Vision-Platforms/blob/master/images/automl-vision-tutorial/b3.PNG" width=300>
   
5. Use the user interface to upload and label images of custom landmarks

   <img src="https://github.com/mmoussa/Landmark-Recognition-with-Google-Vision-Platforms/blob/master/images/automl-vision-tutorial/b4.PNG" width=300>
   
6. Create a None_of_the_above label and label images that are not landmarks
7. Go to the Train tab and train a new model. Wait for the model to train.
   
   <img src="https://github.com/mmoussa/Landmark-Recognition-with-Google-Vision-Platforms/blob/master/images/automl-vision-tutorial/b5.PNG" width=300>
   
8. Go to the Evaluate tab and make sure the model has acceptable accuracy

   <img src="https://github.com/mmoussa/Landmark-Recognition-with-Google-Vision-Platforms/blob/master/images/automl-vision-tutorial/b6.PNG" width=300>
9. Go to the predict tab and test your model

   <img src="https://github.com/mmoussa/Landmark-Recognition-with-Google-Vision-Platforms/blob/master/images/automl-vision-tutorial/b7.PNG" width=300>
