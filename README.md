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
