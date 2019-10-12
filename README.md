# Gender-Classifier-Flutter-APP-with-Render-Stripe-and-Firebase
Gender Classifier Flutter APP with Render, Stripe and Firebase

Using Fast.Ai deep learning i have developed one Flutter App "Man/Woman classifier" which will take picture either uploading from your andriod/iphone devices or you can capture from camera and classify to Man/Woman. Used render for web implementation, signin and signup i have used firestore/firebase and for payments, used Stripe.

Go to below render implementation of Man/Woman Classification:

https://gender-classifier.onrender.com/

## Credits

Credits go to the FastAI team, Naveen Chanakya, and the Flutter team. I integrated a few different pieces together to form a SaaS pipeline. There are 3 components here; A web API, a model training script, and a mobile app. 

### Step 1: Find an Image Dataset

- Got the Dataset from Kaggle for Gender Classification. It's set of images od Man and woman pictures.

### Step 2: Transfer Learning

- fast.ai jupyter notebook for Gender Classification --> gender-detection-face-with-fastai.ipynb.
  It's retraining a 'resnet34' image classification model. This is transfer learning.
- Save the resulting model pkl file to google drive, save the download link.

### Step 3: Signup for Firebase + Stripe
- [Firebase](http://firebase.com)
- [Stripe](https://stripe.com)

### Step 4: Deploy the Web API 

- Deployed in Render Web API --> https://gender-classifier.onrender.com/

Example-1:
![Alt text](/Output/screenshots/render_1.png?raw=true "Optional Title")

Example-2:
[Alt text](/Output/screenshots/render_2.png?raw=true "Optional Title")

Example-3:
[Alt text](/Output/screenshots/render_3.png?raw=true "Optional Title")



### Step 5: Build the Mobile App

- Install Flutter [here](https://flutter.dev/docs/get-started/install) 

Example-1:
![Alt text](/Output/screenshots/flutter_1.png?raw=true "Optional Title")

Example-2:
![Alt text](/Output/screenshots/flutter_2.png?raw=true "Optional Title")

Example-3:
![Alt text](/Output/screenshots/flutter_1.png?raw=true "Optional Title")



### Future Plan:

1. Some more useful features and incorporate more payment options.
2. Currently works fine with only Man/Woman pictures, if you upload other picture, my app doesn't take care that stuff. Will enhance and more scalable.
