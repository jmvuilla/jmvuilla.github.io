# Transfer Learning and Using CNNs on non-image data

In the first chapter of "Deep Learning for Coders with fastai & PyTorch" from Jeremy Howard & Sylvain Gugger (see <https://www.oreilly.com/library/view/deep-learning-for/9781492045519/>), the authors are introducing various concepts ranging from the history of neural networks, AI frameworks, GPUs, a cat vs. dog binary classification example, positioning of AI vs. Machine Learning vs. Deep Learning, underfitting vs. overfitting, training-validation-test sets, etc.

A solid introduction - which can be found in many different shapes or forms in other books or Web sites.

There are two topics in Chapter 1 which piqued my curiosity.

![](</images/Deep Learning Specialization - Transfer Learning.PNG>)

## Transfer Learning
The first one is transfer learning. The authors stress the importance of this technique, and claim that the use of pretrained models are not highlighted enough in courses, books or software libraries. While I agree with the importance of transfer learning, I personally came accross this in many courses/books/projects I went through so far.
* Firstly, I came accross the concept of transfer learning during my AI journey while going through Andrew Ng's Deep Learning Specialization course on Coursera - see the picture above. The transfer learning content of this course is available on YouTube at <https://www.youtube.com/watch?v=yofjFQddwHE&t=393s>.
* Secondly, François Chollet's book "Deep Learning with Python" (see <https://www.manning.com/books/deep-learning-with-python>) has a strong focus on this technique with great examples on how to apply it using TensorFlow and Keras.
* Finally, I would like to highlight an FPGA-based acceleration solution offered on Microsoft Azure, which leverages transfer learning (see <https://docs.microsoft.com/en-us/azure/machine-learning/how-to-deploy-fpga-web-service>). In this case, a special device called FPGA (Field-Programmable Gate Array) is used to speed up the computations related to the pre-trained neural network inference.

## Using CNNs on non-image data
The second topic I found interesting in Chapter 1 is related to the possible use of image classification to handle non-image data. A few examples are provided by the authors where some non-image data are transformed into images, which can then be processed by a deep learning image classification models such as CNNs.
* The conversion of some audio content into a spectrogram - a visual representation of the spectrum of frequencies of a signal as a function of time for urban sounds classification,
* The conversion of time series into images for olive oil classification,
* the conversion of a series of mouse moves and clicks into an image with lines and dots for fraud detection, and
* the conversion of binary file (program) into a picture for malware detection.

The authors mentioned these approaches as state to the art ways to get great results.
