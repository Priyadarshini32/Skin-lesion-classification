# Skin-lesion-classification
1. Data Loading and Augmentation :
A training dataset is created with data augmentation using tf.keras.utils.image_dataset_from_directory and tf.keras.Sequential for augmentation layers.
Data augmentation includes horizontal flipping and rotation.
2. Data Visualization : 
Samples from each class are visualized using matplotlib.
Data augmentation is visualized to compare original and augmented images.
3. Class Distribution Visualization :
Random images from each class are displayed to visualize class distribution.
Class distribution is plotted to show the count of each class.
4. CNN Model Construction :
A CNN model is built using TensorFlow and Keras.
The model architecture includes convolutional layers, max-pooling layers, flatten layer, and dense layers.
The model is compiled using categorical crossentropy loss and Nadam optimizer.
5. Model Training :
The compiled model is trained using the augmented dataset with validation on the validation dataset.
Training history is stored in the history variable.
6. Model Evaluation :
Training history is visualized using plot_training_history function.
