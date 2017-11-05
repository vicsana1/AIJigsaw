# Some problems are too difficult to solve by manually coding
So far you have taken your first baby steps into programming and creating your own software. As you may know by now, software is created by specifying how to solve a problem step-by-step, or instruction by instruction. We have to define the sequence of steps that the computer would need to follow to solve the problem. Now imagine the following complex application.

<p align="center">
<img src="https://github.com/vicsana1/AIJigsaw/blob/master/ml1.png" width="80%">
</p>

Let's say that we need to build a software application that automatically controls the entrance to the European Parliament by using a video surveillance camera. Clearly, this application would need to take a photo of whoever is standing in front of the door and identify if that person is part of the Eurochamber. So, the application would need to open the door in case that the individual is authorized such as Theresa May, Françoise Hollande, Angela Merkel or Mariano Rajoy. On the other hand, it should not open the door when an unauthorized individual attempts to enter the parliament.

<p align="center">
<img src="https://github.com/vicsana1/AIJigsaw/blob/master/ml2.png" width="80%">
</p>

For that purpose, you would need to make your software identify familiar faces in images. It sounds simple, right? We just try to exactly match the face with our records. But it is actually more complex that it seems. Faces can be presented in a multitude of positions (i.e, different degrees of inclination), show a vast variety of expressions (i.e., anger, fear, happiness, neutral expressions), or even show stylistic changes (i.e., different haircuts, glasses on/off, moustaches, etc). Obviously, we want to make our software robust to all of these situations. If you recall your programming lessons, you can always consider special scenarios by using *if-statements*. However, how many *if-statements* would you need to recognize one's face? There is an almost infinite number of possible ways in which one single face can be presented!!! That seems like too many cases to be programmed. And even if we could account for all of them, how do you tell a computer to identify a face in an image? Yes, your brain knows how to do it, but can you translate that into a sequence of steps? The answer to this question is not trivial, as we are not even sure how we recognize faces. It is pure instinct for us.

# Teaching software/machines how to learn: Machine learning
Sometimes, we cannot tell a computer how to solve a problem, but we can specify how a computer **could learn to solve a problem**. This is the foundation of machine learning. In machine learning, we **teach computers how to learn by looking at examples or data**. The rationale behind this approach is that **data often shows patterns that are likely to help us to solve a particular problem**. For instance, in the previous example, Angela may show very different expressions. However, it is also true that in many of these images there are going to be similar facial features such as the type of nose, particular wrinkles, shapes, and so forth that can help us to tell if the image has Angela on it. Instead of programming how Angela's face can be presented in every single situation, we rather write steps that a computer can take to learn to identify those interesting patterns. We call these steps a **machine learning algorithm**. In the end, once our software has learned from examples, we want it to **make predictions** when presented with new examples or cases. In the previous application, that would be when presented with new images. Watch the following explanatory video on what is machine learning.

<p align="center">
<a href="https://www.youtube.com/watch?v=f_uwKZIAeM0"><img align="center" src="https://img.youtube.com/vi/f_uwKZIAeM0/0.jpg" alt="ML I"></a>
</p>

Depending on how the data is presented, we have three different types of machine learning problems:
- **Supervised Learning**: In our previous application, we can ask our colleagues to tag the pictures used to learn by the computer with the name of the individuals in the photos. So, now we and the computer know who are the individuals in the pictures and can use this information to "supervise" how the learning is carried out.  Once our algorithm learns how to classify images we can use it on new data and predict labels or tags on previously unseen images. We say that we have a supervised learning problem when **the data used to learn is labelled with the output that should be learned**.
- **Unsupervised Learning**: Now assume that our colleagues forgot to tag the images! Our data would not have any labels to supervise how the learning is carried out. It is still possible to learn that there are several different individuals (although we do not know who they are!) in our images by focusing on the inherent characteristics of the pictures and grouping those images that are similar. We say that we have an unsupervised learning problem when **the data is not labelled with the output that should be learned**.
- **Reinforcement Learning**: In some cases, machines and software have to learn to interact with a particular environment they can act upon. For instance, think about a computer trying to teach a computer how to play a videogame. The computer can observe the game/screen and it knows it can apply some actions (e.g., moving around the screen, shooting lasers, etc), but it does not know what are the best actions to take when playing the game. A computer can learn how to play a game by performing actions/playing and observing the feedback in the game in the form of positive rewards (e.g., more points, extra lives) or negative rewards (e.g., losing points, game over, losing lives). Then, after many games, it can learn and analyze what actions were more successful. In reinforcement learning, The computer **learns how to behave in a particular problem by interacting with that problem and receiving feedback** from the problem, and then **using that feedback to determine which actions are likely to achieve better feedback in the problem**.


# Research more on Machine Learning!

Now it is time to kick off your research. Check the following resources and look for additional explanations on what machine learning is: 

<p align="center">
<a href="https://www.youtube.com/watch?v=gNkE3tFUFuw"><img align="center" src="https://img.youtube.com/vi/gNkE3tFUFuw/0.jpg" alt="ML I"></a>
</p>

<p align="center">
<a href="https://www.youtube.com/watch?v=l95h4alXfAA"><img align="center" src="https://img.youtube.com/vi/l95h4alXfAA/0.jpg" alt="ML I"></a>
</p>

<p align="center">
<a href="https://www.youtube.com/watch?v=U4BW8WFTenY"><img align="center" src="https://img.youtube.com/vi/U4BW8WFTenY/0.jpg" alt="ML I"></a>
</p>







