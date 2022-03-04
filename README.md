# Machine-Learning-Project

The machine-learning model is based on a task to identify images of flowers with different features.

## Is your model based on supervised learning?

The program attached is based on supervised learning as it has the capability of labelling datasets in order to train the algorithm so that it could identify/classify the flowers and provide with much more accurate predictions.

![image](https://user-images.githubusercontent.com/84967025/156681831-5846d335-bc4c-421d-a3a6-56bd90584dd8.png)

## Is your model based on unsupervised learning? If not, research + hypothesise about what changes could be made to adopt to this approach.

The program is not based on supervised learning as it already has labelled datasets. The chnages required to make the program based off unsupervised would be by not labelling any dataset and having one central dataset. Then, we would let the program decide on its own to create different class of subsets which would make it highly inaccurate in the starting but slowly gain accuracy after going through volumes of pictures, refining the program.

![image](https://user-images.githubusercontent.com/84967025/156682508-b388cc6b-2d86-494e-94ef-8c15898a556f.png)

## Does your model include reinforcement learning? If not, research + hypothesise about what changes could be made to adopt to this approach.

Reinforcement learning is the training of machine learning models to make a sequence of decisions. The agent learns to achieve a goal in an uncertain, potentially complex environment. In reinforcement learning, an artificial intelligence faces a game-like situation.

This model does not include reinforcement learning. In order to adapt to reinforcement learning, addition such as an agent which would closely monitor the progress of the learner( in this case the program), a complex environment, set of policies and an indication to the learner for a reward after a task has been completed. These tasks are based on  Markov Decision Processes (MDP). Some of the most popular algorithms are Q-learning and SARSA(State–action–reward–state–action).

![image](https://user-images.githubusercontent.com/84967025/156683520-e177230e-3da6-40e4-80c2-17c15af32810.png)

## Explain if your chosen model is a clustering / (linear? multiple?) regression / classification algorithm. Again - for any model that your program does not fit into, suggest how it could be adapted / altered to do so.


The Classification algorithm is a Supervised Learning technique that is used to identify the category of new observations on the basis of training data. In Classification, a program learns from the given dataset or observations and then classifies new observation into a number of classes or groups.

It is a classification algorithm built to classify different types of flowers by training itself with its database which has upto 3670 images of flowers. 

Epoch 1/10
92/92 [==============================] - 3s 16ms/step - loss: 1.2769 - accuracy: 0.4489 - val_loss: 1.0457 - val_accuracy: 0.5804
Epoch 2/10
92/92 [==============================] - 1s 11ms/step - loss: 0.9386 - accuracy: 0.6328 - val_loss: 0.9665 - val_accuracy: 0.6158
Epoch 3/10
92/92 [==============================] - 1s 11ms/step - loss: 0.7390 - accuracy: 0.7200 - val_loss: 0.8768 - val_accuracy: 0.6540
Epoch 4/10
92/92 [==============================] - 1s 11ms/step - loss: 0.5649 - accuracy: 0.7963 - val_loss: 0.9258 - val_accuracy: 0.6540
Epoch 5/10
92/92 [==============================] - 1s 11ms/step - loss: 0.3662 - accuracy: 0.8733 - val_loss: 1.1734 - val_accuracy: 0.6267
Epoch 6/10
92/92 [==============================] - 1s 11ms/step - loss: 0.2169 - accuracy: 0.9343 - val_loss: 1.3728 - val_accuracy: 0.6499
Epoch 7/10
92/92 [==============================] - 1s 11ms/step - loss: 0.1191 - accuracy: 0.9629 - val_loss: 1.3791 - val_accuracy: 0.6471
Epoch 8/10
92/92 [==============================] - 1s 11ms/step - loss: 0.0497 - accuracy: 0.9871 - val_loss: 1.8002 - val_accuracy: 0.6390
Epoch 9/10
92/92 [==============================] - 1s 11ms/step - loss: 0.0372 - accuracy: 0.9922 - val_loss: 1.8545 - val_accuracy: 0.6390
Epoch 10/10
92/92 [==============================] - 1s 11ms/step - loss: 0.0715 - accuracy: 0.9813 - val_loss: 2.0656 - val_accuracy: 0.6049

Regression is a supervised machine learning technique which is used to predict continuous values. The ultimate goal of the regression algorithm is to plot a best-fit line or a curve between the data. The three main metrics that are used for evaluating the trained regression model are variance, bias and error.

This program cannot be implemented with a regression algorithm as shown in the previous image, because this algorithm can only be implemented on continuous values and not discrete values(in this program), thus preventing from having this algorithm.
![image](https://user-images.githubusercontent.com/84967025/156684182-413e5970-88e1-4423-a34f-4d5ccec125aa.png)

Cluster analysis, or clustering, is an unsupervised machine learning task. It involves automatically discovering natural grouping in data. Unlike supervised learning (like predictive modeling), clustering algorithms only interpret the input data and find natural groups or clusters in feature space.

This program has not been implemented with a cluster algorithm. It can be implemented by not seperating the data inputs into different subsets and rather target on data clusters or groups.

![image](https://user-images.githubusercontent.com/84967025/156685064-6dd6d8f2-1e8d-4308-b908-8fcad4fd86be.png)


## Does your program represent a deep learning model / artificial neural network? If so, how is 'back propagation of errors' used?

The program uses an artificial neural network.



