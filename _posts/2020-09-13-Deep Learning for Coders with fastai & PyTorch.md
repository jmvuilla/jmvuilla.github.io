# Yet Another Book on AI!
I have been working mostly with TensorFlow and Keras so far, and decided to explore another AI framework, namely PyTorch. To learn about it, I started to read <https://learning.oreilly.com/library/view/deep-learning-for/9781492045519/>

Note that the book and associated notebooks are available at <https://course.fast.ai/>

![GitHub Logo](</images/Deep Learning for Coders with fastai & PyTorch.PNG>)
Format: ![Alt Text](url)

Here are my first thoughts & comments about this book.

## The authors
The two authors, Jeremy Howard and Sylvain Gugger, have very different backgrounds.
* Jeremy has no formal technical education, but developed a strong AI hands-on experience working on a lot of projects (as a consultant, then running his own company). 
* Sylvain has a very solid formal mathematical and technical background (as a math teacher & author of several math textbooks, with less experience on software coding & machine learning.

These different backgrounds seem appealing for a book on AI, where both software & math knowledge need to be combined. Hopefully, the rest of the book will demonstrate the power of this combination of talents!

## You don't need lots of data for deep learning
Interestingly, the authors kick off their book by busting some myths - one of them being that deep learning requires lots of data to work. They mentioned that one could achieve great results with less than 50 items of data. This is somewhat aligned with François Chollet's comments in his book <https://www.manning.com/books/deep-learning-with-python> (initially found in François' blog <https://blog.keras.io/building-powerful-image-classification-models-using-very-little-data.html>), where there is a section highlighting the relevance of deep learning for small-data problems.

By the way, I used François Chollet's book quite a lot to run my first deep learning experiments (windsurfer/no windsurfer binary classification model using my own dataset - more about this in a future post) with Keras, back in 2018. I noticed that the second edition of the book is available in Manning Early Access Program (see <https://www.manning.com/books/deep-learning-with-python-second-edition>). It is probably worth switching to this second edition in order to account for changes with TensorFlow 2.0, as well as to gain new insights from the author.

## How to learn deep learning
The authors spend some time explaining their approach to teaching deep learning, along with justifications about their choice. I would summarize their approach as a top-down one - starting from real world examples and then diving into the details explaining how things work. I don't think their approach is unique - there are actually many practical deep learning books using this approach. 

What I found unique and definitely interesting is the thought process leading to this approach.

I, myself, went through a formal technical and math education. For many years, I learnt math without passion or joy (probability, statistics, calculus, linear algebra, etc.) and with little focus on real word applications of these theories. It's only recently - a few years ago - that I discovered how to actually apply this knowledge in the context of deep learning. I had some aha! moments when discovering the actually usefulness of partial derivatives and Lagrange function for stochastic gradient descent...
