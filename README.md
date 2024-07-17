Dataset Download Link: https://www.kaggle.com/datasets/ananthu017/emotion-detection-fer

Collect a dataset of facial images with labeled expressions. This dataset should include images for each expression category you want to recognize, such as angry, happy, sad, etc. Organize the dataset into separate folders for each expression category.

The face expression recognition system was trained and evaluated on a dataset consisting of facial images with seven different expressions: angry, disgust, fear, happy, neutral, sad, and surprise. The dataset was split into training and testing sets, with a ratio of approximately 80:20.

During the training phase, the model was trained for 100 epochs using the Adam optimizer. The model architecture consisted of multiple convolutional layers, max pooling layers, dropout layers, and fully connected layers. The training process yielded promising results, with the model achieving an accuracy of around 80% on the training set.
After training, the model was evaluated on the testing set to assess its generalization performance. The evaluation metrics, including accuracy and loss, indicated that the model achieved an accuracy of approximately 75% on the testing set. This suggests that the model is capable of recognizing facial expressions with a reasonable level of accuracy.
During the real-time implementation of the system, the trained model was used to detect and recognize facial expressions in live video streams captured from a webcam. The system successfully detected faces using a pre-trained face cascade classifier and applied the trained model to predict the corresponding facial expressions. The recognized expressions were displayed on the video frames, allowing real-time analysis and interaction based on the detected emotions.
