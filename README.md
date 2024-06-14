# Gesture Recognition using deep learning
> In this project, we've developed an advanced gesture recognition system for smart TVs, allowing users to control their TV experience with intuitive hand gestures captured by a webcam. The system recognizes gestures such as thumbs up (increase volume), thumbs down (decrease volume), left swipe (rewind), right swipe (fast-forward), and stop (pause). Our training dataset consists of hundreds of short videos, each segmented into 30-frame sequences, depicting diverse individuals performing these gestures.

We explored various deep learning architectures, including Conv3D for spatiotemporal analysis, TimeDistributed Conv2D with GRU for capturing temporal dependencies, and transfer learning using MobileNet combined with GRU. Extensive experimentation was conducted to optimize parameters like batch size, image index ranges, learning rate, dropout strength, and L1/L2 regularization. This comprehensive approach has enabled us to fine-tune the models for optimal performance, ensuring a seamless and intuitive gesture-based control system for smart TVs.



## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
- `Aims`: Develop a sophisticated gesture recognition system for smart TVs. Enable users to control TV functions using hand gestures captured by a webcam.
- `Objectives`: Predict and recognize specific hand gestures such as thumbs up, thumbs down, left swipe, right swipe, and stop. Enhance user experience by replacing traditional remote controls with intuitive hand gestures.
- `Dataset Overview`: Hundreds of video clips categorized into five distinct gesture classes. Each video spans 2-3 seconds, segmented into sequences of 30 frames. Diverse individuals performing gestures in front of a webcam, simulating real-world interaction

## Methods:
- Conv3D architectures for spatiotemporal analysis.
- TimeDistributed Conv2D combined with GRU for capturing temporal dependencies.
- Transfer learning with MobileNet integrated with GRU.
- Parameter tuning: batch size, image index ranges and length, learning rate, dropout strength.
- egularization techniques: L1 and L2.

## Conclusions
- Successfully developed a gesture recognition system for smart TVs.
- Integrated various deep learning architectures to improve accuracy and performance.
- Innovative approaches like TimeDistributed Conv2D with GRU provided effective temporal dependency capture.
- Transfer learning with MobileNet significantly enhanced system performance.
- Fine-tuning of parameters and regularization techniques was crucial for optimizing model performance.




## Technologies Used
- pandas - version 2.1.2
- numpy - version 1.26.1
- tensorflow - version 2.15.0
- skimage - version 0.19.3
- matplotlib - version 3.7.1
- keras - version 2.15.0


## Acknowledgements
- We would like to thank UpGrad for giving us the oppurtunity to work on this project. 


## Contact
Created by [Imliyangla](https://github.com/Imliyangla) - feel free to contact us!




<!-- You don't have to include all sections - just the one's relevant to your project -->
