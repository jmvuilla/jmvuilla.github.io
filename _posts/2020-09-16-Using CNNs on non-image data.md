# Using CNNs on non-image data

In the first chapter of "Deep Learning for Coders with fastai & PyTorch" from Jeremy Howard & Sylvain Gugger (see <https://www.oreilly.com/library/view/deep-learning-for/9781492045519/>), the authors are introducing various concepts ranging from the history of neural networks, AI frameworks, GPUs, a cat vs. dog binary classification example, positioning of AI vs. Machine Learning vs. Deep Learning, underfitting vs. overfitting, training-validation-test sets, etc.

A solid introduction - which can be found in many Web sites or books.

There are two topics in Chapter 1 which piqued my curiosity.

## Transfer Learning
The first one is transfer learning. The authors stress the importance of this technique, and claim that that the use of pretrained models are not highlighted enough in courses, books or software libraries. While I agree with the importance of transfer learning, I personally came accross this in many courses/books/projects I went through so far.
* Firstly, I came accross the concept of transfer learning during my AI journey while going through Andrew Ng's Deep Learning Specialization course on Coursera (see <https://www.youtube.com/watch?v=yofjFQddwHE&t=393s> for the corresponding video).     
* Secondly, François Chollet's book "Deep Learning with Python" (see <https://www.manning.com/books/deep-learning-with-python> has a strong focus on this technique with great examples on how to apply it using TensorFlow and Keras.
* Finally, I would like to hihglight an FPGA-based acceleration solution offered on Microsoft Azure, which is leveraging transfer learning (see <https://docs.microsoft.com/en-us/azure/machine-learning/how-to-deploy-fpga-web-service>). In this case, a special device called FPGA (Field-Programmable Gate Array) is used to speed up the computations related to the pre-trained neural network.

## Using CNNs on non-image data
