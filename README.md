# cs335---assignment-5-solved
**TO GET THIS SOLUTION VISIT:** [CS335 – Assignment 5 Solved](https://www.ankitcodinghub.com/product/cs335-assignment-5-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;111166&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS335 - Assignment 5 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
Instructions

• This assignment should be completed individually.

• Do not look at solutions to this assignment or related ones on the Internet.

• The files related to the assignment are present in lab5-rollno.zip folder. Extract it and upload it on moodle in the same .zip format after completion and after replacing the string “rollno” with your actual roll number. For example, if you roll number is 00405036, then single zip folder that you will upload will be named “lab5-00405036.zip”. Also collate all the CS337 based theory solutions into ONE pdf file named answers.pdf. Include answers.pdf inside the zip folder mentioned above and submit the zip folder.

• Answers to all subjective questions need to be placed in single pdf answers.pdf including all plots and figures and uploaded.

• Only add/modify code between TODO and END TODO unless specified otherwise. You must not import any additional libraries.

• Files to submit – layers.py, nn.py, trainer.py and model.p

1 CS 337: Directed Graphical models

1.1 D-Separation

1.2 Probability distribution

(a) C ⊥ B ?

(b) C ⊥ B | A ?

(c) C ⊥ B | A,J ?

(d) C ⊥ B | A,J,D ?

(e) C ⊥ G ?

(f) C ⊥ G | B ?

(g) C ⊥ G | B,D ?

(h) C ⊥ G | B,D,H ?

(i) C ⊥ G | B,D,H,E ?

(j) B ⊥ I | J ?

Figure 1: D-Separation Questions

1.3 Number of parameters required to learn the probability distribution

Assume that all the nodes in the DGM represent Bernoulli Random variables. i.e. each node takes value 1 with probability θ and value 0 with probability 1−θ. Further assume that we know the node I always takes what F takes (i.e., I = F) and the node H takes the value E logical OR F (i.e., H = E ∨F). We know that learning Bernoulli random variable amounts to learning just one parameter θ. i.e. P(A = a) = θa(1 − θ)1−a Specify the minimum number of parameters we need to learn the joint probability distribution. In process of doing so, complete the following table:

Prob. distribution # Parameters

P(A) 1

P(A,B,C,D,E,F,G,H,I,J) Total parameters

2 CS337: CNN Theory Questions

In this problem, assume that every input image has the same size: 1024 × 1024.

Task 1: Detecting Image

Containing

Single Object

Figure 2: List of 1024 × 1024 images for Task1.

1. Task 1: In the class we discussed the Convolutional and pooling layers of a CNN and motivated the kernel (sparse interaction, patches, strides) for classification of images. Suppose our input image contains exactly one vehicle (either a bicycle or a car or a motorbike or any one of N vehicles) and we have trained a CNN-based network to distinguish between images based on the kind of vehicle that the image contains. Specifically, the output layer of our network consists of a soft-max layer that can classify an image into one of N vehicular categories. Thus, our CNN-based network is trained to distinguish that the image in the first row, first column of Figure 2 is a car and that the image in the first row, second column of Figure 2 is a motor-bike.

Figure 3: Explain roughly how the CNN-based network helps address/correctly classify the images here. Recall that each image is of the same size, viz., 1024 × 1024

Task 3:

Objects

Figure 4: List of 1024 × 1024 images for the three tasks in this problem.

3 CS 337: Feed Forward Networks

In this problem, we will implement a feed forward network to predict digit from a image (using MNIST dataset) and flower type from flower dataset given in the data folder. In MNIST dataset each element in 28×28 2D array and in flowers dataset each element is a vector of length 2048.

(ii) Complete functions sigmoid,sigmoid prime,tanh,tahn prime, relu and relu prime functions to implement respective activation functions and their derivatives and invoke them in forward and backward functions of ActivationLayer.

(iii) Complete functions mse,mse prime,cross entropy and cross entropy prime functions to implement respective loss functions and their derivatives and invoke them while training the feed forward network.
