# Event-Based Action Recognition

## Description
This project focuses on action recognition using an event-based dataset stored in `.aedat` files. These files are converted into event-based videos for processing. The dataset comprises actions performed by multiple individuals. Traditional video-based action recognition models like ConvLSTM and LRCN are known for their performance. This project aims to evaluate and compare the performance of these models when applied to event-based data.

## Dataset
The dataset used in this project is stored in the folder named `Action_recognition_dataset`. It consists of `.aedat` files for each individual performing an action. These actions are categorized into 10 different action classes. 

## Code
The main code for this project is available in the Jupyter Notebook file named `Event_Based_Action_Recognition.ipynb`. This notebook contains all the necessary steps, from data preprocessing to model evaluation.

## Models
- **ConvLSTM**: A convolutional LSTM model that combines the spatial feature extraction capabilities of CNNs with the temporal modeling capabilities of LSTMs.
  
- **LRCN (Long-term Recurrent Convolutional Networks)**: This model integrates the recognition capacity of CNNs with the sequence modeling capacity of RNNs, making it suitable for video-based action recognition.

## Objective
The primary objective of this project is to:
1. Convert the `.aedat` files into event-based videos.
2. Implement and train the ConvLSTM and LRCN models on the event-based dataset.
3. Evaluate the performance of these models on the dataset.
4. Compare the results to understand which model performs better for event-based action recognition.

## Credits
This project has been inspired by and utilizes resources from https://github.com/CrystalMiaoshu/PAFBenchmark/tree/master
