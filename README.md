# ES Montoring System

#### This simple project was developed to keep monitoring the working of Embeded Systems amd sending data through IOT to reciever node with failsafe method

### Keypoints:- 
* The ES is based on Freertos which controls a Stepper motor
* Various Tasks are assigned different jobs
* It constantly sends data to the reciver node 
* Incase of any failure in working of the job, a fail safe method is triggered which sends log and alerts the Admin at reciver node


> This project uses Arduino and Nodemcu to communicate through serial communication  to send the data to Blynk through Nodemcu
