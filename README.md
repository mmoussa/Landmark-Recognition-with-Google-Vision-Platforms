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
