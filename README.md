# MKEL1123-Milestone-5

This repository contains the code for a small project.

## Introduction 

The aim of this project is to create a simple Convolutional Neural Network (CNN) based facial recognition that is made by using STM32F4 series development board. The image dataset is acquired from faces94 and 5 inviduals are selected for training the network using tensorflow framework. After the network is trained, the network is converted to lighter version to meet with the requirement of smaller or tiny devices. To display the results, , 16x2 LCD type has been used. The 16x2 comprises of 16 characters able to be displayed on the 2 lines, however limited to 224 characters only and unable to display images. HD44780 parallel interface chipset LCD has been used to display the output result in text form from after the images has been processed. The text expected to be displayed on the LCD in the form of people’s name.

## Procedure 

1. Open up the .project file (STM32Cube_Facial_Recognition/.project).
2. STM32CubeIDE should load up along with the trained network (X-CUBE-AI directory).
3. Run the code in Core/Src/main.c and the code should be error free.

## Results
The follow code snippet shows the creation of neural network in STM32 board and prediction result
![image](https://user-images.githubusercontent.com/93202001/178223755-4376cee5-eb2f-4265-8017-746773b4fa4d.png)

The result shows that the neural network instance is created but failing to run the inference.
![image](https://user-images.githubusercontent.com/93202001/178223639-6a3d6bf2-6462-48fc-a49c-a8122a7b1954.png)
