# PLANT-DISEASE-DETECTION
Implemented Machine Learning and Artificial Intelligence model to detect the different disease on plants using the images.
# High Level Diagram:- 
![image](https://github.com/yashrajgupta1/PLANT-DISEASE-DETECTION/assets/170006396/35dfcfd7-4129-480d-8a5e-d768611045fd)

# Technology Stack
- Python
- Convolutional Neural Networks (CNN)
- Machine Learning
- Flask
# Project Execution Video's :- 
"C:\Users\91766\Downloads\deployment video.mp4"



# Screenshots of Application and Deployment :- 
image_1 : ![WhatsApp Image 2024-06-19 at 14 44 01_a9c4962b](https://github.com/yashrajgupta1/PLANT-DISEASE-DETECTION/assets/170006396/a5b0a982-380c-41ae-95d3-38cfcfb34da2)
image_2 : ![WhatsApp Image 2024-06-19 at 14 44 01_64bf6ad1](https://github.com/yashrajgupta1/PLANT-DISEASE-DETECTION/assets/170006396/79df81ac-5c80-428a-8c53-2ddc1d611fc9)
image_3 : ![WhatsApp Image 2024-06-19 at 14 44 00_497887ce](https://github.com/yashrajgupta1/PLANT-DISEASE-DETECTION/assets/170006396/682502fc-98e7-4b77-90d4-43d426ccd769)

# How to Use :-
1). Use [Plant Disease Detection Dataset]-Kaggle: https://www.kaggle.com/datasets/rashikrahmanpritom/plant-disease-recognition-dataset
Data Preprocessing:

2).Label the images according to their disease category.
Resize images to a consistent size suitable for your model (e.g., 224x224 pixels).
Normalize pixel values (e.g., scaling pixel values to the range [0, 1]).
Augment the data to increase the diversity (e.g., rotate, flip, zoom).
Model Design:

3).Choose a CNN architecture (e.g., VGG16, ResNet, or design a custom CNN).
Define the model layers (convolutional layers, pooling layers, fully connected layers).
Model Compilation:

4). Choose a loss function (e.g., categorical cross-entropy for multi-class classification).
Select an optimizer (e.g., Adam, SGD).
Define evaluation metrics (e.g., accuracy).

5). Model Training:
Split data into training, validation, and test sets.
Train the model on the training set, validate on the validation set.
Monitor training using metrics like accuracy and loss.
Use callbacks (e.g., early stopping, model checkpoint) to improve training efficiency.

6). Model Evaluation:
Evaluate the model on the test set to assess its performance.
Check metrics such as accuracy, precision, recall, F1-score.

7). Model Fine-tuning:
Fine-tune the model by adjusting hyperparameters, changing the architecture, or using techniques like transfer learning.

8). Model Deployment:
Save the trained model.
Deploy the model to an environment where it can be used for inference (e.g., web server, mobile app).

9). Inference:
Load the saved model.
Preprocess new plant images similarly to training data.
Use the model to predict the disease class of new images.

10). Monitoring and Maintenance:
Continuously monitor the model's performance in the real world.
Update the model periodically with new data to maintain accuracy.
