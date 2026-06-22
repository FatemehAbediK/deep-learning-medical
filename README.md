# deep-learning-medical

### 1. CNN_heart_disease :
Built a TensorFlow/Keras neural network (CNN) for heart disease classification with normalization, dropout layers, and achieved ~85–87% validation accuracy over 20 epochs, based on 13 different factors on 'heart.csv' kaggle dataset


### 2. brain_tumor :
Brain tumor detection (classifying if there is a tumor in the image or not) was implemented using a CNN trained on 64×64 MRI images from a Kaggle dataset, by turning the images into numpy arrays, achieving ~96% validation accuracy with early stopping and binary cross-entropy loss.


### 3. blood_cell_image_classification :
Blood cell image classification was performed to identify four types of white blood cells: EOSINOPHIL, LYMPHOCYTE, MONOCYTE, and NEUTROPHIL. A pretrained MobileNet model was used as the backbone for feature extraction, enabling efficient learning from image data with limited training time. The model was adapted for multi-class classification and fine-tuned on the dataset to improve performance.
