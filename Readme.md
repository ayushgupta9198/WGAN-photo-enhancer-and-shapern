
Readme file - Deep Photo Enhancer with WGAN

Model Implementation : https://github.com/nothinglo/Deep-Photo-Enhancer

Model Description:
Model is based on single/multiple image super resolution in which it increases the resolution from lower resolution based images to high resolution images using WGAN.

Model Environment:

    1.  !pip install tensorflow==1.14.0
    2.  !pip install flask-ngrok
    3.  !pip install -U flask-cors

Model setup:

    1. Model setup can be done in two ways by using pretrained weights or training on custom datasets , here we have used pretrained data of the model and tested on pretrained images and custom images as well.

    2. Initially this model is run with the help of flask app in which we have to make some changes in main.py as this model uses flask api.

    3. After changes it ran on flask.app with starting the server also we made changes in code to run the same model with FLASK api integration so now it is running without the API Integration part.

Working :

    1. It works for single and multiple images both for single image we have to set path for specific images and for multiple images we have set folder path in place of single image path.

    2. Firstly it works on two face in which in first phase it is processing the image from LR image to enhancement picture in which it enhance the colors of picture and in second phase it converted the LR to HR by enhancing the features of images into sharp features in this we got enhanced and sharped output from the input image.

    3. I have created a function for this model to run properly without any execution error.

    4. All we have to do is put the images in the path and get the output in the output folder with HDR quality.
