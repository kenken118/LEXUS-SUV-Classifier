# LEXUS SUV Classifier 
 
 # Overview
 This tool is that identify the model name from the interior image of the Lexus car. In general, many people identify the vehicle type from the exterior of the vehicle, but I dare to try to identify the vehicle type from the characteristics of the interior. Among the Lexus models, the SUV3 brothers, which are difficult to distinguish because they have similar features in both exterior and interior, are classified. The types of vehicles subject to classification are listed below.
Target model : LEXUS-UX, LEXUS-NX, LEXUS-RX
With the LEXUS emblem on the steering wheel reflected, the vehicle type is mainly classified according to the characteristics of the Instrument Panel.This tool is excluded for classification by specifications such as the destination, interior grade, etc.
 
![img_e1ecdb97a0b7a061881346c2c1b12467316165](https://user-images.githubusercontent.com/70054082/123542242-7f380f00-d783-11eb-8f33-cbece4e859d5.png)

# Target Image
Using my NX as an example, I will show the target image to be learned.
![image4 (2)](https://user-images.githubusercontent.com/70054082/123542750-4b121d80-d786-11eb-83bc-86de976e1a8f.png)

# Dependency
Python 3.7.7
numpy 1.17.0
keras 2.3.1
keras preprocessing 1.1.2
