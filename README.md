# CS7641 Assignment 4

## Project Setup on Ubuntu

Follow instructions below in order to get the code working

1. clone the repository

   git clone https://github.com/truzmeto/RL_MDP.git 

2. install maven 

   sudo apt-get install maven

3. change dir to RL_MDP dir and compile burlap

   cd RL_MDP

   mvn compile

4. run the code

   mvn exec:java -Dexec.mainClass="assignment4.EasyGridWorldLauncher" > output/easy.txt
   mvn exec:java -Dexec.mainClass="assignment4.HardGridWorldLauncher" > output/hard.txt

