# ArabicHandWrittenResources
Collect codes,articles,papers about 

# [Handwritten Arabic Numeral Recognition using Deep Learning Neural Networks](https://arxiv.org/pdf/1702.04663.pdf)
- This paper proposes a novel algorithm for recognizing
numerals in handwritten Arabic with the help of CNN. Our
proposed CNN model uses several convolutional layers along
with ReLU activation, with dropout used as a regularization
layer. Then the output is fed into a fully connected layer
(which is the same as MLP model) with softmax activation to
obtain prediction for each class. Our proposed novel method
achieves better accuracy then the method discussed in Section
II. We also propose a modification of the method in Section
II using MLP. In the MLP model, we implement dropout
regularization to reduce overfitting in between fully connected
layers. The output layer, consisting of 10 neurons with softmax
activation, predicts the probability for 10 individual digit
classes (0-9). Our proposed MLP method achieves identical
accuracy score compared to the method of Das et al. [1].
The proposed methods are described in detail, and the performances are compared.
