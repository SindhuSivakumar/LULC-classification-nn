#Land use and Land cover classification using Eurosat data in Convolution Neural Network

EuroSAT is a comprehensive dataset comprising satellite images covering ten land use and land cover classes commonly found in Europe, including urban, agricultural, and natural areas. 
Data: Multi-Spectral Eurosat data (https://github.com/phelber/EuroSAT?tab=readme-ov-file)

CNNs, being adept at extracting spatial features from images, are well-suited for this task. Eurosat dataset contains 30000 images over 10 classes which is labeled accordingly. The data is preprocessed to uniform size and split as training and testing. During training, the CNN learns to automatically extract relevant features from the satellite images, enabling it to classify them into different land use and land cover categories. CNN architecture is developed in a way for image classification tasks. Typically, this involves stacking convolutional layers, followed by activation functions (e.g., ReLU), pooling layers, and dense layers with softmax activation for classification tasks. And then the model is trained with appropriate loss function (Categorical cross-entropy), optimizer(Adam), and matrics(accuracy). And the model is fitted for 20 epoch because of the system capacity. 

###Model validation 
F1 Score: 0.7166914828686857
Accuracy: 0.6903333333333334
Precision: 0.7476013477172536
Recall: 0.733434922343751

Confusion Matrix is used to visualize the model's performance in predicting each class and identify any misclassifications.
