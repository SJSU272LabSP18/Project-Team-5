# Project-Team-5

PROJECT GROUP NO . 5
TEAM MEMBERS : Sayali Pisal, Sneha Patil, Chunchen Lin

INTRODUCTION :

Image captioning to convert a given input image into a natural language description.
The project uses the encoder-decoder framework for achieving efficient caption
generation for live images giving a hit rate of upto 95%. The image encoder is a
convolutional neural network (CNN) and the text generator is a recurrent neural network (RNN).

DATASET :

The dataset can be downloaded from :

http://msvocds.blob.core.windows.net/annotations-1-0-3/captions_train-val2014.zip
http://msvocds.blob.core.windows.net/coco2014/train2014.zip
http://msvocds.blob.core.windows.net/coco2014/val2014.zip

FILE INCLUSION FOR THE SAID MODEL IS :

build_vocab = generating and storing the trained vocabulary model for prediction.
data_loader = for ingestion and processing of datasets
model = actual model generation
resize = preprocessing of testing images for prediction
sample = sampling of images and vocabulary sets
train = training of the generated model

MODELLING FLOW IS AS FOLLOWS :

1. Data Ingestion
2. Data Preprocessing
3. Deep Learning Model
4. Training the model
5. Evaluating Model
6. Generating New Captions
7. Google text to speech translator API for caption description 

MODEL TESTING IS DONE BY THE COMMAND :

$ python (sampling file name) --image='(input prediction image name)'






                                  IDEAS PRESENTATION :


---------------------------------------------------------------------------------------------
1]	Project idea 1

Project title:
## Car Collision detection using machine learning  - I love this idea , go for it.

Project description:
The traffic in bay area is notoriously bad. One of the reasons is the traffic jam caused by car collisions.  Machine learning or AI has been made many things 'smart'. It would be very beneficial if we can use it to solve the car collision problem. It is actually possible to detect the possible collision and worn the drivers to take action. However, most the cars down the road does not have this function installed. It is expensive and only available to some new version of cars. We are thinking we may design and implement an affordable car collision prevention application using computer vision and machine learning method.
Proposed methodology/resources:
One method to detect potential car collision is to track taillight. Analyzing the behavior of the front vehicle can prevent possible accidents. First, the software detect the vehicle. Then it will search for taillight. As we know, face detection in computer vision is possible. We can try to modify it to detect taillight in the vehicle.  We can set threshold to extract red regions. We also can use deep learning to find the taillight. There are computer vision and deep learning  software available, such as OpenCV and Caffe. We will code part of the project ourself to suit our goals. All of us can program in Java.

2]	Project idea2

Project title:
Personal health and weight watch application

Project description:
There are about 1/3 of US population overweight. One of the issues of overweight is it causes health problems, which cost a huge amount of money and decrease the quality of life. Triggering by the idea of personal medicine, we propose a personal health and weight watch app using machine learning to target people individually. Since we all unique in our gene, health, life style and habits, a program specific for each one of us would be more efficient. To reach the goal, we use machine learning to train the data that input by the user and make suggestion according to the training results. For weight watch and stay healthy, the factors can be healthy diet, exercise, and calories count.
Proposed methodology/resources:
The most convenient form of this application is a smartphone app. There are many calories count apps available. We are trying to combine calories count, diet, and exercise to form a personal health and weight watch advisor. The first step is to train the app. The user has to record the food he/she eat by taking a picture of it. There are apps that can count the calories based on the picture. The user has to record the daily weight too, so the app can learn the right calories for the person. The user has to provide the calories burned in exercise,such as walk 30 minutes. The app calculates how many calories for that. By building a machine learning model and training it with the data user provided, we can create a personal advisor for the user to stay healthy.  We will program it in the form of Android or Apple app and use machine learning method to provide 'smart' advise.

3] Project Idea 3

Project title:
Buy/Sell Nearby

Project description:
This project aims at designing a Website/App that helps people sell their stuff to group of people who are physically present in that area. Most of the times we upload the pictures of the things to be sold on Facebook pages. There is a gap between the buyers and sellers. Potential buyers sometimes would not have signed up as a member for the respective page. There are other websites like craigslist which show a list of things sold by others based on various filters like the area.
This Website/App aims at providing solution that will help the potential buyers to look for potential sellers are who are located within the fixed radius. Let's take a simple example where a person is waiting for a friend or waiting for a cab they would simply open the website or app and look for people who are selling used stuffs near them. In the same way the person can even look up for nearby yard sale that is happening.
Proposed methodology/ resources Developing a Website or a App. Track using the location API's

3] Project Idea 4

Project title:
Project Name: Bloom and Flourish Plant Reminder

Project description:
There is a constant need to remember small tasks to be completed on time. With the help of arduino and few lines of code you could water your plants or change the location of the plants placed in the patio. Certain plants require specific amount of sunlight like some require 4 hours of sunlight and others just require just 1 hour of sunlight. This project aims at sending reminders when the moisture of the soil falls below a certain level. Or when a plant has already been exposed to a certain amount of sunlight. You could then take the necessary action to water the plant or change the position of the pot.
Proposed methodology/ resources Use of Sensors, arduino or Raspberrypi as hardware and developing a simple app to read the notifications.
