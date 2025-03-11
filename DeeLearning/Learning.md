# Deep Learning

First It is the subset of Machine Learning.
DeepLearning inspired by human brain just like human brain relies on neural network similarly deeplearning use artificial neural network for decision making , image Processing and natural language Processing.

Artificial Neural network have multiple layer of neurons .Each layer process the information and result goes to the next layer as input.

# why deep learning comes in picture as we have macine learning.

Ans.: ML models require manual feature extraction, which is difficult for complex data like images or speech.While Deep Learning automatically learns features e.g., edges, shapes, objects in images using neural network , machine learning model not handles the unstructured data

# Procedure of Deep learning

**1.Data Processing:** First the raw data is processed and remove the noise from the data.
Assume if any text is there like what is variable first it process and convert into tokenization.

**2.Neural NetworkL**
We have various neural network like CNN,RNN and GAN .It depends on the problem different problem require different architecture.

--Feedforward Neural Networks.
--Convolutional Neural Networks.
--Recurrent Neural Networks.
--Transformers.
--Generative Adversarial Networks

**3.Forward Propagation:** Input goes to multiple layers of neurons where each neurons applies a mathematical function (weighted sum + activation function) to extract the information.

Activation function:
Without activation fucntion it just a linear model who does not handle complex problems and can't find out the reltionship between data.

**4.Loss calculation:**
It is the process to compare the value, how far a neural network prediction value compared to the actule value.

for example model predicts the 7 ,but the actual value is 10 so the loss could be 10 - 7 = 3

**5.Backpropogation and optimization:**
Backpropogation is used for improve the accuracy of the model by adjusting the internal parameters of mdoel like weights and biases.

Gradient Descent help us the updates the weights to reduce errors.

for example: predicted model value is 8 and the actual value is 5 .first we compare predicted and actual by using loss fucntion after find out the error the backpropogation comes into the picture the error is sent backward to the network,the model adjust the wieghts to reduce the loss. the process repeats many times unti the erro becomes to small.

