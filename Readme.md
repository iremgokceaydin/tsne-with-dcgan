
# tSNEJS

tSNEJS is an implementation of t-SNE visualization algorithm in Javascript. Check out the main repo https://github.com/karpathy/tsnejs 

t-SNE is a visualization algorithm that embeds things in 2 or 3 dimensions. If you have some data and you can measure their pairwise differences, t-SNE visualization can help you identify clusters in your data. See example below.

In this project I used the images from the result of train process of DCGAN machine learning algorithm and the discriminator and generator loss values as the 2 dimensional data points from 100 epocs to be able to see the similarities between the images generated over time. In a sense, I intent to use tSNE visualization to be able to get more involved in the learning process of an algorithm in an interactive way.

![](https://raw.githubusercontent.com/iremgokceaydin/tsne-with-dcgan/master/docs/stepwise.gif)
![](https://raw.githubusercontent.com/iremgokceaydin/tsne-with-dcgan/master/docs/bulk.gif)

# DCGAN

[Deep Convolutional Generative Adversarial Networks (GANs)](https://www.tensorflow.org/tutorials/generative/dcgan) is a class of unsupervised machine learning framework where two models are trained simultaneously by an adversarial process. A generator ("the artist") learns to create images that look real, while a discriminator ("the art critic") learns to tell real images apart from fakes. I used one of the implementations of DCGAN to generate the images for this project: https://github.com/tensorlayer/dcgan

## Online demo
The main project website has a [live example](http://cs.stanford.edu/people/karpathy/tsnejs/) and more description.

There is also the [t-SNE CSV demo](http://cs.stanford.edu/people/karpathy/tsnejs/csvdemo.html) that allows you to simply paste CSV data into a textbox and tSNEJS computes and visualizes the embedding on the fly (no coding needed).
