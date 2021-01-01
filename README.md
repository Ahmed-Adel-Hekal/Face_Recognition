# Face_Recognition

we will build a face recognition system. Many of the ideas presented here are from FaceNet. In lecture, we also talked about DeepFace. <br />

Face recognition problems commonly fall into two categories:<br/>

1. Face Verification - "is this the claimed person?". For example, at some airports, you can pass through customs by letting a system scan your passport and then verifying that you (the person carrying the passport) are the correct person. 
<br/>A mobile phone that unlocks using your face is also using face verification. This is a 1:1 matching problem.<br/>
2. Face Recognition - "who is this person?". For example, the video lecture showed a face recognition video of Baidu employees entering the office without needing to otherwise identify themselves.<br/>
This is a 1:K matching problem.<br/>

FaceNet learns a neural network that encodes a face image into a vector of 128 numbers.<br/>
By comparing two such vectors, you can then determine if two pictures are of the same person.

------------------------------------------------------------------------------------------------
# Code Overview 
In This notebook we will implement :<br/>
1. Implement the triplet loss function
2. Use a pretrained model to map face images into 128-dimensional encodings
3. Use these encodings to perform face verification and face recognition
   
 -------------------------------------------------------------------------
# Built With

1- [tensorflow v1 ](https://www.tensorflow.org/) - Machine Learning Framework<br />


# Authors

Origanally this is a part of Deep_Learning_Specialization [Coursera](https://www.coursera.org/)

***Ahmed_Hekal***
