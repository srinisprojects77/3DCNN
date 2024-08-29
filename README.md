# Build an ML model 3D CNN + RNN, to recognise five different gestures.
> **Outline a brief description of your project**.
To recognise five different gestures, build and train 3D Convolutional Neural Network (CNN) + RNN -  video frames are given for training and validation, those are pre-processed with generator and fed into the model with fit_generator.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- **Provide general information about your project here.**
  This project is about to train the ML model with images as pre-processed(crop & resize) images of different gestures by generators.
- **What is the background of your project?**
  We use 3D conv for ML model. Generators(which are used to convert images as cropped and resized and to be feed into the model using fit_generator) are being used to generate around 663 (Train sequences, consists of video frames in each folder, which different classification, 100 sequences for validation.
- **What is the business probem that your project is trying to solve?**
  Develop a feature that is used by smart TV recognizes the movmenet of hands with different gestures,and be controlled. 
- **What is the dataset that is being used?**
  Video frames for each video with different classes(as move up, down, swipe directions...) contains 663 sequences/videos (30 frames for each video contained in the respective forlder) for training, 100 sequences for validation.
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- **Conclusion 1 from the analysis**
  More the batch size increased the load get increased in GPU , but overall steps gets reduced for each epoch. The lesser the batch size , the more the steps increased for each epoch , in addition to the change performance model
- Conclusion 2 from the analysis
- Conclusion 3 from the analysis
- Conclusion 4 from the analysis

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->
## Technologies Used
- Tensorflow - version 2.17.0
- Keras      - version 3.4.1
- skimage    - version 0.23.2
- Python     - version 3.10.12
- Google colab - Tool
- Processor   - GPU used with T4
<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->
## Acknowledgements
Give credit here.
- This project was inspired by...
- References if any...
- This project was based on upgrad : Convolutional Neural Networks(http:learn.upgrad.com)
- 
## Contact
Created by [@srinisprojects77] - feel free to contact me!

<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
