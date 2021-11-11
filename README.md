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

Sign languages are languages which uses visual means of communication through hand
signals , hand gestures, facial expressions, and body language to convey the message .
These languages helps us to talk to the people who cannot communicate easily . Sign
languages are often thought as regarding to the deaf community . But ,there are many
situations where people with certain disabilities use them like:
1) Autism:- people with autism have a hard time to communicate with others. So
till some extent they can use sign language to communicate. This can help them with
speech development, interactions and to learn new words. Thus sign language helps
them to communicate.
2)Apraxia of speech : it is a motor speech disorder which aects the messages
from the mouth from the brain . This makes the person dicult to communicate with
others. So they are beneted by the sign language.
3)Cerebral palsy :- this aects the way a person moves their mouth, jaw and head
making them dicult to speak . Thus they can use sign language to communicate.
4) Down syndrome :- delay in development and can aect the learning ability of
the person. Sign language is used to improve their communication skills.
5) Speech impairment :- people suering from any sort of speech impairment can
use sign language to communicate .
Use of sign language doesn't end here there are many conditions where people loose
their speaking and hearing abilities through some disease, trauma etc. So there are
many people who are in need of this sign languages.
But even after studying the sign language it maybe dicult for them to talk to
normal people as there are less than one percent of the healthy population who knows
to use this sign language . So as the numbers shows it makes them dicult to com-
municate with the normal people.It is even hard for them to communicate with people
