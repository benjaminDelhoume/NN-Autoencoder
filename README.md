# NN-Autoencoder
In this project, the goal is to create a set of NN-based transmitter and receiver that beats a conventional QAM system. This project has been done during my Artificial intelligence for Télécommunication course and created by Mathieu Goutay : https://github.com/mgoutay/. 

<img width="1111" alt="Capture d’écran 2021-09-29 à 18 39 29" src="https://user-images.githubusercontent.com/60884419/135358233-1d538334-d640-4a05-ae87-1bf144f9c996.png">

### First Section

In this first section, the goal is to create the first autoencoder. To make trainings faster, we set K = 4 here. Do not try to beat the baseline, as it might be hard for K<6

The main objectives are to :
- Define a loss function
- Create the NN-based transmitter and receiver 
- To normalize the output so that the average power per symbol is one
- Create a training loop
- Train, evaluate, and compare your system to the baseline

<img width="1106" alt="Capture d’écran 2021-09-29 à 18 39 22" src="https://user-images.githubusercontent.com/60884419/135358276-54543af4-6504-488f-be61-6dcca1dba262.png">



### Second Section - Generate a proper constellation

The idea here is to use the transmitter to generate constellation vectors that depends on the SNR, instead of directly generating the symbols to send. For one entry in the batch (one SNR), this constellation vector contains all $2^K$ symbols that can be sent, so it is a complex vector of size $2^K$.


<img width="1106" alt="Capture d’écran 2021-09-29 à 18 39 10" src="https://user-images.githubusercontent.com/60884419/135358292-90bbff8e-2b08-42d6-b174-70ae621d34f4.png">




### Third Section

Still in progress 🚀

