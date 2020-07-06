# Face-Recognition-for-Attendence-System
Working on Automatic face recognition using VGG model with Tensorflow and Keras
## Face Recognition for Attendance based system: Working on face Recognition for Attendance System with deep learning and convolutional neural networks using Tensorflow, Keras and OpenCV

###### 1. Create Database: The first step in the Attendance System is to create a database of faces that we will be using. Different subjects are taken and a camera is used to detect faces and record their frontal face. The number of frames to be taken for consideration can be modified to our accuracy. These images are then stored in the database with the Registration ID. Using the OpenCV technique we will try to take the Images from the webcam by applying Face detection cascade file. 

###### 2. Face Detection: Face detection is the process of automatically locating faces in a photograph and localizing them by drawing a bounding box around their extent. For face detection we are using a cascade .xml file. It is the pre-trained file that we used for face detection. And as mentioned above in creating a database the face detection process applied. So that the faces will detect the only person faces in terms of either Color or Gray. Extract face from images, crop face, and store as an image in a separate folder with the image name as person name

###### 3. Training Faces: After taking the dataset try to train them and create a model for recognition. There are many types of models used in the real world. Those are VGG, OpenFace, Facenet, Deep Face, etc. Here we are using the VGG16 model for training. VGG model is one of the Neural Network architecture containing 16 trained layers. Once the model is built we can set the layers weights to values trained on a larger dataset. For the VGG16 model we are using pre-trained weights and by adding weights to the model we can interact with the dataset to train. Once the model has been fully trained (architecture and weight value) we can use it to identify faces using the predict method. As the VGG weights have been trained on square/centered face images we test it on an image that has been manually cropped.

###### 4. Face Recognition: For face Recognition, Earlier we stored each cropped face image in the corresponding folder, walk through each image, load image from Keras in-built functions. Now we can recognize any face in the image if we get embeddings for the face with the help of the VGG model and feed into to classifier then get a person name. OpenCV draws a rectangle box around the face and writes a person's name for each face in the image.

###### 5. Post Preprocessing: After the xlsx sheet is applied for the system those data will be uploaded to corresponded authorities. Using matplotib, email package we did the process of sending the file and text.

# Reference : https://www.youtube.com/watch?v=p-Jf_FRqjXQ


Those who have any queries regarding the project comment me or mail me.

Mail id: manasajagannadan@gmail.com

Thanks & Regards,

Jagannadan Manasa

Undergraduate student

Electronics And Communication Engineering Department

Rajiv Gandhi University of Knowledge Technologies

IIIT RK Valley, Vempalli (M), YSR Kadapa, AP-516330

manasajagannadan@gmail.com

https://manasajagannadan.wixsite.com/manasa-jagannadan

https://www.linkedin.com/in/jagannadan-manasa-aa11b0179/

Category : Science & Technology
