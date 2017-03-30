# __Facial Expression Recognition__

#### APMAE 4990 Introduction to Data Science in Industry 

#### Team members: Ben Lai, Cindy Zhang

#### Role: Computing kernel: Ben Lai, Website design: Cindy Zhang

Tools
--------
Python, Flask

Data Source
--------
https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data

Project Description
--------
Human-computer interaction is a very important step in the development of the humanoid robots or other machine intelligence. Being able to identify not only whether it’s a human face but also the expression or the mood of the face will surely improve the quality of the nonverbal communication between human and machine. In this project, we are trying to use the data extracted from hundreds of pictures of human faces with distinct facial expressions and classify them into six types of expressions – joy, sad, anger, disgust, fear, and surprise. These expressions will be categorized and the pictures will be transformed into pixel values. We will test different classifiers including SVM, RVM and convolutional neural network.


Audience
--------
Humanoid robot developers, machine intelligence researchers, people who are insterested in human-computer interaction.

Algorithms
--------

#### Classifiers
Classifiers like SVM, RVM and convolutional neural network will be tested, the technique of Adaboost will also be tested. The one with the highest accuracy will be inplemented.

#### Feature Learning
Feature learning algorithms like autoencoders are used to transform the pictures into data that can be exploited by computers.

Web Application
--------
Our web application allows the users to select pictures from our database, the predicted feature will be shown and compared to the actual feature. For now, the web app will be entertainment-oriented since the back end development may be too complicated.

Reference
--------
This dataset was prepared by Pierre-Luc Carrier and Aaron Courville, as part of an ongoing research project. We obtain the dataset on Kaggle: https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data

D. Datcu and L. J. M. Rothkrantz, "Facial Expression Recognition with Relevance Vector Machines," 2005 IEEE International Conference on Multimedia and Expo, Amsterdam, 2005, pp. 193-196. doi: 10.1109/ICME.2005.1521393

Lucey, P., Cohn, J. F., Kanade, T., Saragih, J., Ambadar, Z., & Matthews, I. (2010). The Extended Cohn-Kanade Dataset (CK+): A complete expression dataset for action unit and emotion-specified expression. Proceedings of the Third International Workshop on CVPR for Human Communicative Behavior Analysis (CVPR4HB 2010), San Francisco, USA, 94-101.

Philipp Michel and Rana el Kaliouby. Facial Expression Recognition Using Support Vector Machines. In Proceedings of the International Conference on HumanComputer Interaction (HCII): Human-Computer Interaction, Theory and Practice, volume 2, pages 93–94. Lawrence Erlbaum Associates, 2003.

