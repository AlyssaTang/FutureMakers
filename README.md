# Responses

## 7/6
It was really inspiring to hear the stories of middle school and high school girls making a real impact on their community through their app that allows residents to make appointments for water distribution. During the first day, I learned how to use anaconda as opposed to pip to download libraries, and experimented with using Pycharm since I had previously used mostly Colab and Jupyter notebooks.

I have previously learned about the basic concepts of AI and machine learning, how computer vision and NLP work at an introductory level. I’m excited to have more time and guidance in this program to learn more about various ML models and the appropriate use for each one. I hope to improve my Python programming skills and to gain the skills to be able to tackle future research projects.
##

## 7/7
Dr. Kong showed us the power of storytelling with the videos and examples. They were so compelling and we were clearly moved to action. After his talk, I went through introspection to think of my own story. I’m still trying to dig deeper to find the true motivation for my passions for AI and health. It was such a privilege to be part of Dr. Kong’s leadership development session.
##

## 7/8
I learned about the steps of machine learning, the ML algorithm framework, and types of machine learning. The mentors gave great explanations and analogies to help us better understand the concepts. Previously, I hadn't known the difference between standardization (a mean of zero and a standard deviation of one [-1,1]) and normalization [0,1]. From Ms. Yohn, the scenarios of students feeling excluded and discussing solutions was helpful as a reminder. 

i. What is the difference between supervised and unsupervised learning?

In supervised machine learning: the program fed labels that correspond with the training examples. When given new data, it is able to decide the classification based on the labeled training data. On the other hand, in unsupervised machine learning, the program is given no labels and a bunch of data. It must find patterns and relationships within the data and use clustering methods.

ii. Describe why the following statement is FALSE: Scikit-Learn has the power to visualize data without a Graphviz, Pandas, or other data analysis libraries.

SkiKit Learn provides supervised and unsupervised learning algorithms but not visualization methods. Graphviz, Pandas, or other data analysis libraries are necessary to visualize the data.
##

## 7/9
Waste management is an issue in the US since most of the wastes end up in landfills. Eutrophication of lakes, consumption of toxic waste by animals, and land, water, air pollution are resulting problems. This dataset classifies household waste by Organic (O) and Recyclable (R). I would utilize the CNN deep learning model since neural networks are the best fit for image classification. 

Dataset: https://www.kaggle.com/beyzanks/waste-classification-with-cnn
##

## 7/12
1. What are “Tensors” and what are they used for in Machine Learning?

Tensors are multidimensional data arrays that neural networks can perform on. Plane vectors are a type of tensor in which there is a x,y coordinate system that a vector is plotted on. Covectors and linear operators are other types of tensors. I learned about ranks of tensors in N-dimension spaces and that tensors generally refer to a vector that is three or more dimensions. Tensors are used in Machine Learning with Tensorflow as the library does numerical computations on tensors. Tensors are the basic building blocks of modern machine learning. They can be thought of as a container storing arrays of data.


2. What did you notice about the computations that you ran in the TensorFlow programs (i.e. interactive models) in the tutorial?

I noticed that the images were different dimensions which is the reason preprocessing data to ensure all of them are the same length is important. It was interesting to experiment with the subplot function and see how the bar graph corresponded to the number of pictures of each type of sign (Label 1-61). I also encountered errors due to version differences. Most of the cells of code required transformation from TensorFlow 1 to TensorFlow 2, so I had to do a lot of googling of errors that resulted from the change. 
##

## 7/13
The head mentors taught us a lot about the ANN architecture and the different types of neural networks. We learned about weights, neurons with thresholds, activation functions, weights and biases. I learned the difference between feed-forward and back propagation neural networks. I knew what RNNs were generally, but hadn’t known that the information cycles in a loop so that was interesting.
##

## 7/14
I learned about CNNs and the element-wise matrix multiplication of the pixel value with the filter size that is then summed up to create a new feature map.Activation layer, fully-connected layer and pooling operation were also discussed.
##

## 7/15
1. How do you think Machine Learning or AI concepts were utilized in the design of this game?

The “Survival of the Best Fit” game demonstrates sample bias since a majority of the applicants that applied initially when a human was screening the applicants were yellow, so the machine learning model assumed that yellow people are candidates that we want more than blue people. This bias led a perfectly qualified applicant to be rejected simply because he was a blue applicant. Additionally, the game demonstrated the importance of recognizing that historical data may reflect biases both explicit and implicit in the machine learning algorithm. 

2. Can you give a real-world example of a biased machine learning model, and share your ideas on how you make this model more fair, inclusive, and equitable? Please reflect on why you selected this specific biased model.

Unfortunately, banks using AI to make credit decisions are unknowingly discriminating against people on the basis of race, gender, and sexual orientation due to the historical data it was fed. Biased data leads to bias models which can exacerbate pre-existing disparities. Being able to get a loan to buy a house is the first step to building financial security and bridging the wealth gap. It is important to make the model more fair, inclusive, and equitable in order to level the playing field for this minority group. Even though the bank companies do not explicitly ask for those specific pieces of demographic data, they can learn the association of zip codes to ethical minorities. Adversarial AI-driven models can be used to detect these protected characteristics and correct the bank loaning model. According to the Harvard Business Review, “this re-tunes the model to increase the influence of variables which contribute to equity and reduce those that contribute to bias,until the challenger model is no longer able to predict ethnicity by using zip codes as a proxy.”
##

## 7/16
Today, I was able to get a deeper understanding of CNN components from flattening to parameters such as the depth, stride, and padding. I also explored implementing a CNN for the MNIST dataset. 
##

## 7/19
I learned about loss functions for regression and classification. There are two types of classification - binary and multi-class classification which use different types of loss functions. We also explored MSE, MAE, and MSLE for regression and cross-entropy for classification. 
##

## 7/20
I learned about linear and nonlinear activation functions and which ones are used for regression and classification as well as hidden and output layers. 

Action Item: The ReLU activation function is the most common function used for hidden layers. One of the advantages is that it is easy to implement. Another benefit is that it is effective at overcoming the limitations, such as vanishing gradients, of other previously popular activation functions, such as Sigmoid and Tanh. Models that use it are also easier to train and often achieve better performance. It only requires a max() function unlike previously popular ones that require the use of an exponential calculation allowing the computations to be cheaperIt can also outpt a true zero value which also accelerates learning and simplifies the model. Since it looks and acts like a linear activation function, it is more easily optimized. Their use cases would be on CNNs and Multilayer perceptrons for hidden layer activation functions. 
##

## 7/21
I learned about the importance of ethical AI and the difficulties that come with regulation since companies often do not fully disclose algorithmic details. When COMPAS was used to evaluate risk of violent recidivism as a score, it was severely biased towards blacks.
##

## 7/22
I learned how to build an Image Classification model and adjusted some of the hyperparameters and model architecture to try to improve the accuracy and minimize the loss for the CNN model predicting dogs and cats from images. 
##

## 7/23
I learned about overfitting and underfitting, how to determine based on graphs if it is doing either of the two, as well as methods to fix these issues. Overfitting models can be detrimental if they perform badly on testing data. If an overfitting model was used at a bank and therefore classify a person as unlikely to pay back their loans when they could have, then the person may be denied credit unfairly.
##

## 7/26
I learned about autoencoders as well as downsampling (decreasing size of input images) and upsampling (opposite of downsampling; returning input to original size). I developed an autoencoder based reconstruction and noise removal and added upscaling layers to a deep
learning mode.
##

## 7/27
Today, I learned about affective computing and using computer vision to detect facial expressions of drivers. It was used to detect the level of drowsiness. From the guest speaker, we learned about the STAR (Situation, task, action, result) technique which would be very helpful in interviewing!
##

## 7/28
I learned about NLP and the different applications, considerations, and the different steps involved in the preprocessing.

As for the ethical implications of big NLP models such as GPT-2, although it can be a wonderful tool, it can also learn from biased data it is fed. If some of the text the model is trained on is making descriminatory remarks on the basis of gender, race, color, religion, sex, national origin, age, or disability, the model could reflect that sentiment in the paragraphs they generate. 
##

## 7/29
I learned about the uses of computer vision and the differences between traditional CV and deep learning. Deep Learning-based Emotion Classification from Face and affective computing were also interesting topics that were covered.
##

## 7/30
Today, we reviewed the topics we had covered in the past weeks as well as the python libraries and machine learning tasks.
##

## 8/2
Today, my team researched our potential ideas for the create-a-thon and decided to focus on the broad topic of Physical Health and Mental Well-being Management. We each researched more specific issues within this field individually or in small groups to pitch the next day.
##

## 8/3
Today, we decided to continue to pursue the topic Sahana and I had researched the previous day: an app or wearable device that uses computer vision and emotion recognition technology to give instant feedback on real interactions for people with autism as well as emotion regulation software that warn them if they’re starting to get aggravated and implement calming mechanism of their choice (ex: a calming/favorite song, video or book, counting to ten w/ deep breath, meditation, etc). We also worked on a questionnaire to survey people with autism and their family and friends.
##

## 8/4

##

## 8/5

##
