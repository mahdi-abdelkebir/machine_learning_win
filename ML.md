
# Methodology to learn Machine Learning.

Become familiar with math used in Machine Learning
Libraries Python
Data Preparation
Practice and Compare Results and Improve!


# How can it benefit us?

It gives us the ability to learn things about our world from the huge amount of data which we as human beings can't possibly process ourselves.


# How does it do that?

## simple answer?

At first, we set a goal for the machine and then give the machines hundreds or millions of examples of data related to the subject to learn and train from.

The machine will try to find patterns in these examples and develop it's own logic, in an attempt to explain why things the way they are, sometimes even find patterns which we couldn't have possibly thought of.

For example: If the question was 'is this animal a cat or a dog?'. At first we'll give it many pictures of cats and dogs with the answers readily written to train from. From these pictures, it'll try to find patterns such as the postures, the ears, the nose, height, etc. Then if we gave it a random picture, it'll try to 'guess' the best answer based on what it previously trained.

## detailed answer?

At first, we write an ML *learning algorithm* where we'll specify a way for the machine to learn what we want it to learn.

Then, we have prepare a lot samples of data, with each example is a pair consisting of an input and the desired output.

And run our algorithm on our machine using these data, which will perform pattern recognition. and output an ML *model* compromised of *model data* and a *prediction algorithm*, to represent what was learned from the examples.

### technical terms definitions:

- Algorithm: An step-by-step procedures to be followed, in order to fulfil a certain purpose.

- Learning algorithm: A type of a type of automated programming, how to learn things.
- Labeled Data: Data consisting of a set of training examples, where each example is a pair consisting of an input and a desired output value (also called the supervisory signal, labels, etc).

- Model Data: An abstract model that organizes elements of data and shows how they relate to each other and to the properties of real-world entities.
- Prediction algorithm: A procedure for using the data to make a prediction.

## machine learning algorithms:

Machine Learning algorithms are commonly divided into categories according to their purpose.

[Defining some algorithms](https://duckduckgo.com)

### main categories:

- Supervised learning: 
    **This method is useful when you have existing data for the output you are trying to predict.**
    - Main Goal: Predictive Model.
    - Objectives include: 
        > Classification of data: like images or voices.
        > Regression: like risk estimation or score prediction.
    - Input: Labeled data.
    - Output: A model representing the relationships between the output and input features.
    - Examples of algorithms: Linear Regression, Neural Networks, Decision Trees...


- Unsupervised Learning:
    **This method is particularly useful in cases where the human expert doesn’t know what to look for in the data. Because there's no teacher, the machine might teach you new things while finding patterns.**
    - Main Goal: Descriptive Model.
    - Objectives include: 
        > Clustering of data: grouping similar patterns (also called cluster): in biology, market...
        > Association: finds interesting relations between different variables in big datasets.
        > Dimensionality reduction: simplifying data by taking only the most important parts: face or image recognition, text mining...
    - Input: Unlabeled data.
    - Output: Mines for rules, detects patterns, summize and group data points which may help deriving meaningful insights and describe the data better to the users.
    - Examples of algorithms: K-Means Clustering, Hidden Markov, Neural Networks...


- Semi-supervised Learning: 
    **Essencially a mix of supervised and unsupervised learning. It's most suitable for model building, in the absense of labels in the majority of data and presense of only a few. These methods exploit the idea that even though the group memberships of the unlabeled data are unknown, this data carries important information about the group parameters.**
    - Main Goal: Both Predictive and Descriptive Model.


- Reinforcement Learning: 
    **Famously used in chess. The reinforcement learning algorithm (called the agent) continuously interact and learn from the environment in an iterative fashion, aiming at maximizing the reward and minimizing the risk by determining the most ideal behaviour in a certain context.** 
    *When this step is repeated, the problem is known as a Markov Decision Process.*
    *For the agent to learn from its behaviour, a simple reward feedback is required also known as the reinforcement signal.*
    - Main Goal: Most Optimal Model.
    - Input: Random. Observed directly.
    - Output: Every action is associated with an estimable reward based on how it went.
    - Examples of algorithms: Q-Learning, Temporal Difference (TD), Deep Adversarial Networks...


### Characteristics of machine learning algorithms:

- Machine learning algorithms can be described using math and pseudocode.

- The efficiency of machine learning algorithms can be analyzed and described, so it can be further improved.


# In what domains can we make use of it?

Companies can use it in ads, to send better recommandations to costumers, which may possibly lead to less spending in publicity.

Spotify used it to recommand better songs by looking at what music we listened to, how much time we spent, our playlist, favourites, etc...

It could also be used to predict the weather, or where and when natural disaster like hurricanes and earthquakes will hit and how much damage they'll cause.


# What are two weaknesses of machine learning?

One. Machines may be very good at predicting based on what they seen in the past, but they need to see millions of examples to do that. Whereas, humans can easily implement something they seen only once or twice in the real-world, so we are more flexible. 

Two. Machines cannot create goals for themselves, simply because they don't have an imagination or thoughts about the future. 

They can invent new different ways, which we haven't thought of, to capitalizing unstructured data, which we gave them, to reach a specific end result. Whereas, humans are super good at inventing, we can spontanously come up with new, maybe weird, ideas. We're the ones who give these robots a purpose to fullfil. 



# What are some libraries used in machine learning?
