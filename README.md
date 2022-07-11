# MKEL1123-Milestone-5

This repository contains the code for a small project.

## Introduction 

The aim of this project is to create a simple Convolutional Neural Network (CNN) based facial recognition that is made by using STM32F4 series development board. The image dataset is acquired from faces94 and 5 inviduals are selected for training the network using tensorflow framework. After the network is trained, the network is converted to lighter version to meet with the requirement of smaller or tiny devices. To display the results, , 16x2 LCD type has been used. The 16x2 comprises of 16 characters able to be displayed on the 2 lines, however limited to 224 characters only and unable to display images. HD44780 parallel interface chipset LCD has been used to display the output result in text form from after the images has been processed. The text expected to be displayed on the LCD in the form of people’s name.

## Procedure 

1. Open up the .project file 
2. STM32CubeIDE should load up along with the trained network (X-CUBE-AI directory).
3. Run the code in Core/Src/main.c and the code should be error free.

*Added trained CNN file (tensorflow lite format), just in case user need to reload the deep learning network
