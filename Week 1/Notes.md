## Week 1

> AI is the new electricity. 


### Table of Content
1. [What is a Neural Network?](#what-is-a-neural-network)
2. [Supervised Learning with Neural Networks](#what-is-a-neural-network)
3. [Why is Deep Learning Taking Off?](#why-is-deep-learning-taking-off)


### What is a Neural Network?
- a single neuron is a single unit that takes an input to return an output, which is analogous to a *function*
- x features as the input layer, number of unit on the input layer depends on the number of features
- fully-connected hidden layer, is the computational layer
- y target at the output layer

### Supervised Learning with Neural Networks
**Types of Neural Networks**
1. Standard Neural Network: Regressions and Classifications
2. Convolutional Neural Networks (CNNs): For Images
3. Recurrent Neural Networks (RNNs): For Sequence data and language processing
4. Custom or Hybrid Neural Networks

- Structured data include a table of rows and columns (with varrying data structure)
- Unstructured data includes audio, images, text, etc

### Why is Deep Learning Taking Off?
<figure>
  <img src="Scale Driving Deep Learning.png" alt="Scale Driving Deep Learning">
  <figcaption>Scale Driving Deep Learning</figcaption>
</figure>

- increasing the data availability
- increasing computational capability
- design algorithms
    - switching from sigmoid functions make gradient descent works faster due to derivative of sigmoid might yield learning rate, so the solution is using Rectified Linear Unit (ReLU)


