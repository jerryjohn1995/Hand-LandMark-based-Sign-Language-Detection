# Hand-LandMark-based-Sign-Language-Detection

## ABSTRACT

As human being’s communication is a very crucial part of our life, it is essential
for sharing thoughts and ideas for our survival. But unfortunately for the speaking
and hearing-impaired minority it is difficult or impossible to communicate through
speech. But most of the common people have no knowledge about sign language and
its interpretations. This is one of the major problems faced by these kinds of people
during their communications. Getting an interpreter is not easy every time. To solve
this issue, a model is developed using neural networks for fingerspelling based on the
various hand gestures. In this user independent model, CNN based models are trained
using a set of images (hand skeleton dataset). The skeleton dataset is created using
mediapipe framework and is done to improve the accuracy of the model.
The main issue with the current system is that there are some groups of alphabets,
whose sign language symbols look alike. This makes the image based classification
model a bit difficult to correctly classify and the accuracy of the prediction can also be
low. This issue can be solved using a hand skeleton classifier. As in the hand skeleton
image the position and structure of each finger can be identified more accurately than
from an image. This makes the neural network model to learn better and can classify
with higher accuracy of about 97.6%.

## INTRODUCTION

### 1.1 INTRODUCTION

1.1	INTRODUCTION

Sign languages are languages which uses visual means of communication through hand signals , hand gestures, facial expressions, and body language to convey the message . These languages helps us to talk to the people who cannot communicate easily . Sign languages are often thought as regarding to the deaf community . But ,there are many situations where people with certain disabilities use them like:
1)	Autism:- people with autism have a hard time to communicate with others. So till some extent they can use sign language to communicate. This can help them with speech development, interactions and to learn new words. Thus sign language helps them to communicate.
2)	Apraxia of speech : it is a motor speech disorder which affects the messages from the mouth from the brain . This makes the person difficult to communicate with others. So they are benefited by the sign language.
3)	Cerebral palsy :- this affects the way a person moves their mouth, jaw and head making them difficult to speak . Thus they can use sign language to communicate.
4)	Down syndrome :- delay in development and can affect the learning ability of the person. Sign language is used to improve their communication skills.
5)	Speech impairment :- people suffering from any sort of speech impairment can use sign language to communicate .
Use of sign language doesn’t end here there are many conditions where people loose their speaking and hearing abilities through some disease, trauma etc.   So there are many people who are in need of this sign languages.
But even after studying the sign language it maybe difficult for them to talk to normal people as there are less than one percent of the healthy population who knows to use this sign language . So as the numbers shows it makes them difficult to com- municate with the normal people.It is even hard for them to communicate with people having the same conditions due to the difference in the sign language . As normal languages , sign languages has developed through different people of different culture interacting with each other resulting in about 138 to 300 different sign language used around the globe .Even the countries who speak the same language do not necessarily have the same sign language.
People start to learn sign language by learning the alphabet A - Z by using the hands . This use of hand for each letters for written alphabets is called as finger- spelling’.

As there are this many types of sign languages it is so difficult for them to commu- nicate with people with the same condition from a different country and to the normal people to are unaware of the language, makes it difficult for them to live independently. If they need to go somewhere even to a hospital , restaurant or even a coffee shop they need somebody else’s help to make others understand what they are saying , which makes it so much harder for them to lead a normal life . So we normally use the help of a ’translator’ to help in this conditions . But it cannot be used everywhere as this translator needs to travel everywhere with them or it takes time for the translator to come . So to solve all this problem we can more easily use a translator app which helps us to understand what the person is speaking in sign language .  As this is an app it can be used anywhere anytime which gives more value to our time and money.This kind of apps use CNN models to classify this signs, here we are trying to built one such model with high accuracy. It can also used by people having different sign languages to understand each other . By this innovative digital technology we can identify their gestures and the app converts them to sign language into text.


### 1.2 1.2	OVERVIEW OF COMPUTER VISION

Area of the project is computer vision. Computer vision tasks include methods for obtaining, processing, analysing and understanding digital images, and extraction of high-dimensional data from the actual world so as to make numerical or symbolic information, e.g. in the forms of decisions. Understanding in this context means the conversion of visual images (the input of the retina) into descriptions of the world that make sense to thought processes and can bring about appropriate action.
The scientific discipline of computer vision is concerned with the idea behind ar- tificial systems that extract data from images. The image data can be taken from many forms, such as video sequences, views from different cameras, multidimensional data from a 3D scanner, or medical scanning device. The technical discipline of com- puter vision seeks to apply its theories and models to the creation of computer vision systems.
Sub-domains of computer vision comprise of scene reconstruction, object detec- tion, event detection, video tracking, object recognition, 3D pose estimation, learning, indexing, motion estimation, 3D scene modelling, and image restoration.

