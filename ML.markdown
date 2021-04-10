---
layout: page
#layout: default
title: Machine Learning
#permalink:"/vm_home"
---

> **"A baby learns to crawl, walk and then run. We are in the crawling stage when it comes to applying machine learning"**
>                                  
>*D. Waters*

<p align="justify">
Even though you might haven't noticed yet, machine learning is everywhere. It drives our algorithms for demand forecasting, recommender systems, email spam, fraud detection, customer segmentation, virtual personal assistants, and many other applications you might not even be aware of. 
</p>

<p align="justify">
Since I am very excited about how machine learning and AI are changing our lives and our society, I have created this entry to publish here some of the applications I have worked with.
</p>


## Multi-class classification with Convolutional Neural Networks
<img src="/img/CNN_final.png" alt="drawing"  width="825"/>

<p align="justify">
One of the most popular applications in machine learning consists of finding the category or label to which an object belongs, if the object belongs to one of three or more classes, then it's a multi-class classification problem. Examples where this kind of task arises are very numerous, ranging from classifying the types of movies you like to identifying types of coronavirus or to label images of animals from an encyclopedia, etc.
</p>

<p align="justify">
There are plenty of popular algorithms that have been developed to perform this type of task such as k-nearest neighbors, decision trees, support vector machines, and much more. Although mostly used for image classification, there is a class of
 <a href='https://playground.tensorflow.org/#activation=tanh&batchSize=10&dataset=circle&regDataset=reg-plane&learningRate=0.03&regularizationRate=0&noise=0&networkShape=4,2&seed=0.45780&showTestData=false&discretize=false&percTrainData=50&x=true&y=true&xTimesY=false&xSquared=false&ySquared=false&cosX=false&sinX=false&cosY=false&sinY=false&collectStats=false&problem=classification&initZero=false&hideText=false'> Neural Network</a> 
called  <i>Convolutional Neural Network</i> (CNN), which has proved to be a very powerful tool to perform multi-class classification. The CNN can feature convolutional layers within the network architecture. As you can see in the image above, we distinguish three basic layers: a convolutional layer (to extract all the features), a pooling layer (to try to extract the dominant features), and a fully connected layer (a type of neural network with all the nodes in one layer connected to the others in the next layer). A more detailed explanation of how does this type of neural network works can be found <a href='https://www.youtube.com/watch?v=K_BHmztRTpA'> here </a>.
</p>

<p align="justify">
Inspired by a hackathon, I developed a project where I studied the implementation of CNN to perform a multi-classification with real earthquake data.
<span style="color:OrangeRed">
<a href='https://github.com/vmmunoza/MulticlassClassification'>Have a look at it!</a>
</span>
</p>


<!---
#(I think I'm going to comment this below:)

## Time series forecasting with Recurrent Neural Networks

<img src="/img/time_series.png" alt="drawing"  width="500"/>

 
<p align="justify">
Time series forecasting is another common problem that is solved using ML techniques. 
</p>
-->