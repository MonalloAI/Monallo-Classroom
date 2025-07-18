### What is Machine Learning?

#### Definition and Core Idea

Machine Learning (ML) is a core subfield of Artificial Intelligence (AI). It is formally defined as the study of computer algorithms that can improve automatically through experience and by the use of data. The core idea is to enable computer systems to learn from data, identify patterns within it, and make decisions or predictions based on those patterns, without being explicitly programmed for each specific task.

> In essence, traditional programming involves a human providing the machine with explicit rules to solve a problem. In contrast, machine learning involves providing the machine with vast amounts of data and allowing it to "infer" the rules for problem-solving on its own.

This learning process typically involves a sequence of steps: data collection, data preprocessing, model selection, model training, evaluation and tuning, and finally, deployment of the trained model into a production environment.

#### Major Categories of Machine Learning

Based on the nature of the training data and the learning approach, machine learning is primarily categorized into three types: Supervised Learning, Unsupervised Learning, and Reinforcement Learning.

|Category|Core Idea|Data Requirement|Primary Tasks|Global Examples|
|:-|:-|:-|:-|:-|
|Supervised Learning|Learning a mapping function from input variables to an output variable based on labeled training data.|Labeled Data (e.g., each email is tagged as "spam" or "not spam").|Classification (predicting a category) <br><br> Regression (predicting a continuous value)|Spam filters (Gmail, Outlook), face recognition (Apple's Face ID), medical diagnosis from images.|
|Unsupervised Learning|Discovering hidden patterns or intrinsic structures in unlabeled data.|Unlabeled Data (e.g., a large set of user purchase histories without predefined groups).|Clustering (grouping data) <br><br> Dimensionality Reduction (compressing information)|Customer segmentation (Spotify, Netflix), anomaly detection in financial transactions (HSBC, Visa), social network analysis.|
|Reinforcement Learning|An agent learns to make optimal decisions by performing actions in an environment to maximize a cumulative reward.|No fixed dataset; data is generated through interaction with an environment.|Decision-making & Control (maximizing long-term reward)|Game AI (DeepMind's AlphaGo), robotic control (Boston Dynamics), autonomous vehicle navigation (Waymo).|