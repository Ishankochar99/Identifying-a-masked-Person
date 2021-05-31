# Identifying-a-masked-Person
 I primarily used OpenCV to process the dataset of images and TensorFlow for actually training and testing the models. I considered a lightweight Convolutional Neural Network structure called MobileNet as my Deep Learning model. I then tailored the model for binary classification (Ishan or Not Ishan) by using a Sigmoid function to configure my output. After about 10 epochs, I managed to acheive a ~97% validation accuracy on the validation folds. I took lots of pictures of my face with a mask on and combined with the a dataset of other people's faces with masks 
<img width="210" alt="1" src="https://user-images.githubusercontent.com/65892146/120164882-a77e2d80-c218-11eb-9517-726d350376a1.PNG">
<img width="212" alt="2" src="https://user-images.githubusercontent.com/65892146/120164924-b1a02c00-c218-11eb-8e15-c0702ef1a03d.PNG">
Masked Images Obtained From: https://github.com/prajnasb/observations/tree/master/experiements/data

