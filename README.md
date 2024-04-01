# Neural-network

# Unsupervised Neural Network
An unsupervised neural network is a type of artificial neural network (ANN) used in unsupervised learning tasks. Unlike supervised neural networks, trained on labeled data with explicit input-output pairs, unsupervised neural networks are trained on unlabeled data. In unsupervised learning, the network is not under the guidance of features. Instead, it is provided with unlabeled data sets (containing only the input data) and left to discover the patterns in the data and build a new model from it. Here, it has to figure out how to arrange the data by exploiting the separation between clusters within it. These neural networks aim to discover patterns, structures, or representations within the data without specific guidance.

There are several components of unsupervised learning. They are:

- Encoder-Decoder: As the name itself suggests that it is used to encode and decode the data. Encoder basically responsible for transforming the input data into lower dimensional representation on which the neural network works. Whereas decoder takes the encoded representation and reconstruct the input data from it. There architecture and parameters are learned during the training of the network.
- Latent Space: It is the immediate representation created by the encoder. It contains the abstract representation or features that captures important information about the data’s structures. It is also known as the latent space.
- Training algorithm: Unsupervised neural network model use specific training algorithms to get the parameters. Some of the common optimization algorithms are Stochastic gradient descent, Adam etc. They are used depending on the type of model and loss function.
- Loss Function: It is a common component among all the machine learning models. It basically calculates the model’s output and the actual/measured output. It quantifies how well the model understands the data


# Advantages of Unsupervised Neural network models
- Feature Learning: makes the model proficient in automatic learning and extracting relevant feature.
Dimensionality Reduction: Since it works on the principle of dimensionality reduction, it preserves a lot of important information.
- Generative model: Generates new data samples which is valuable in tasks like data argumentation and data synthesis.
- Data Preprocessing: It can serve as a preprocessing step for supervised learning tasks. Extracted features or reduced-dimension representations can improve the performance of subsequent supervised models.

# Disadvantages of Unsupervised Neural network models
- Lack of labels: Unlabeled data somehow reduces the precise prediction
- Complexity: It is complex and computationally expensive as it needs careful tuning of hyperparameters.
- Difficulty in Evaluation: Evaluating the performance of unsupervised models is more challenging than in supervised learning as there is no ground truth to compare against, making it harder to measure success.
- Limited Applicability: It is not suitable for all types of data or task as effectiveness depends on the quality and nature of the data.
