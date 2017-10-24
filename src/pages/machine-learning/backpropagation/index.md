---
title: Backpropagation
---
## Backpropagation

This is a stub. <a href='https://github.com/freecodecamp/guides/tree/master/src/pages/machine-learning/backpropagation/index.md' target='_blank' rel='nofollow'>Help our community expand it</a>.

<a href='https://github.com/freecodecamp/guides/blob/master/README.md' target='_blank' rel='nofollow'>This quick style guide will help ensure your pull request gets accepted</a>.

<!-- The article goes here, in GitHub-flavored Markdown. Feel free to add YouTube videos, images, and CodePen/JSBin embeds  -->

#### More Information:
<!-- Please add any articles you think might be helpful to read before writing the article -->


Backpropagation is a method used in artificial neural networks to calculate the error contribution of each neuron after a batch of data (in image recognition, multiple images) is processed. This is used by an enveloping optimization algorithm to adjust the weight of each neuron, completing the learning process for that case.

Technically it calculates the gradient of the loss function. It is commonly used in the gradient descent optimization algorithm. It is also called backward propagation of errors, because the error is calculated at the output and distributed back through the network layers.

Backpropagation requires a known, desired output for each input value—it is therefore considered to be a supervised learning method (although it is used in some unsupervised networks such as autoencoders).

Backpropagation is a generalization of the delta rule to multi-layered feedforward networks, made possible by using the chain rule to iteratively compute gradients for each layer. The backpropagation algorithm has been repeatedly rediscovered and is a special case of a more general technique called automatic differentiation in reverse accumulation mode. It is closely related to the Gauss–Newton algorithm, and is part of continuing research in neural backpropagation.

Backpropagation can be used with any gradient-based optimizer, such as L-BFGS or truncated Newton[citation needed][clarification needed].

Backpropagation is commonly used to train deep neural networks [1], a term used to describe neural networks with more than one hidden layer.
