# Cat vs Dog Image Classification using Convolutional Neural Networks (CNN)
<img src = 'https://cdn.analyticsvidhya.com/wp-content/uploads/2024/02/Cat-and-Dog-Classification-80.jpg' height=500, width=1000 img>

**Overview**

- This project involves building a Convolutional Neural Network (CNN) to classify images of cats and dogs. Leveraging deep learning techniques, the goal is to create an accurate and robust model that can effectively distinguish between these two classes. The project includes data preprocessing, model development, evaluation, and deployment.

**Dataset**
- The dataset used in this project is the Kaggle Dogs vs. Cats dataset, which consists of 20,000 labeled images (10,000 cats and 10,000 dogs). The dataset is divided into training, validation, and test sets to evaluate the model's performance.

**Project Structure**
1. Data Preprocessing

- Download and extract the dataset.
- Preprocess the images: resizing to 150x150 pixels, normalization, and data augmentation.
- Split the dataset into training, validation, and test sets.
2. Model Development

- Design a CNN architecture suitable for image classification.
- Implement the CNN model using TensorFlow/Keras.
- Compile the model with appropriate loss functions and metrics.
3. Training and Validation

- Train the CNN model on the training dataset.
- Validate the model using the validation dataset.
4. Evaluation

- Evaluate the final model on the test dataset.
- Generate a classification report including metrics such as accuracy, precision, recall, and F1-score.
- Plot confusion matrix to visualize the classification performance.
5. Visualization

- Visualize training history (loss and accuracy curves).
- Plot example images with their predicted and true labels.
- Implement Grad-CAM to interpret model predictions.
- 
**Clone the repository**
  - git clone https://github.com/b-akshay-k/cats-vs-dogs-classification.git
**Navigate to the project directory:**
- cd cats-vs-dogs-classification
- 
**Install the required dependencies**
- pip install -r requirements.txt
## Conclusion
This project streamlines the process of distinguishing between cat and dog images, demonstrating the practical application of CNNs in real-world image classification tasks.

**License**
This project is licensed under the Apache 2.0 License. See the LICENSE file for more details.

**Acknowledgements**
Kaggle for providing the Dogs vs. Cats dataset.
TensorFlow and Keras for the deep learning framework.

**Contact**
For any questions or feedback, please contact bogaramakshaykumar@gmail.com.



