# Cotton-Disease-Prediction-using-Deep-Learning

Cotton plays a vital role in the global economy but is vulnerable to several diseases that threaten crop yield and quality. Timely identification of these diseases is essential for effective crop management and minimizing financial losses. This project presents a deep learning-based solution for detecting cotton diseases using Convolutional Neural Networks (CNNs).

The model is trained to classify six distinct types of cotton diseases by analyzing visual symptoms from plant images. A comprehensive dataset of infected cotton leaf images was compiled to train and evaluate the model. The CNN architecture includes multiple convolutional, pooling, and fully connected layers, with transfer learning employed to fine-tune a pre-trained network for this specific classification task.

The proposed system achieved a high classification accuracy of 98% on the test set, highlighting its reliability and efficiency in disease detection. This approach offers a promising tool for real-time agricultural diagnostics and can significantly enhance decision-making in crop health management.


Steps:
1. Image Acquisition
High-resolution images of cotton plants are captured using cameras or sensors, serving as the input for disease detection.

2. Image Enhancement
Techniques such as brightness/contrast adjustment and noise reduction are applied to improve image clarity and highlight disease-relevant features.

3. Image Preprocessing
Images are resized, cropped, and normalized to standardize inputs and remove irrelevant background information, preparing them for model training.

4. Test Annotation
Experts annotate diseased regions in the images to provide ground truth labels. These annotations are essential for supervised learning.

5. Data Splitting
The dataset is divided into:

Training Set: Used to train the model on labeled examples.

Test Set: Used to evaluate model performance on unseen data.

6. Image Augmentation
Augmentation techniques (e.g., rotation, flipping, brightness change) are applied to increase dataset diversity and improve model generalization.

7. Model Training
A convolutional neural network (CNN) is trained using the annotated training data to learn visual patterns associated with various cotton diseases:

Army Worm

Bacterial Blight

Cotton Boll Rot

Green Cotton Boll

Powdery Mildew

Target Spot

Healthy (for unaffected plants)

8. Disease Prediction
The trained model is applied to new images to detect the presence of diseases. If a disease is detected, the system iterates for continuous learning or alerts. If not, the result confirms plant health.

9. Model Application
The final model is deployed to predict diseases in unseen cotton plant images, assisting in real-time agricultural decision-making and disease management.
