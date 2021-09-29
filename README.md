# NN-Autoencoder
In this project, the goal is to create a set of NN-based transmitter and receiver that beats a conventional QAM system. This project has been done during my Artificial intelligence for Télécommunication course and created by Mathieu Goutay : https://github.com/mgoutay/. 

<img src="https://github.com/mgoutay/ml_course/blob/master/Images/standard_system.png?raw=true" alt="Drawing" style="width: 700px;"/>

### Our objective

In this first section, the goal is to create the first autoencoder. To make trainings faster, we set K = 4 here. Do not try to beat the baseline, as it might be hard for K<6

The main objectives are to :
- Define a loss function
- Create the NN-based transmitter and receiver 
- To normalize the output so that the average power per symbol is one
- Create a training loop
- Train, evaluate, and compare your system to the baseline

<img src="https://github.com/mgoutay/ml_course/blob/master/Images/NN-based_system.png?raw=true" alt="Drawing" style="width: 700px;"/>
