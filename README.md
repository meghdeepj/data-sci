# Data Science
Independent Projects and Competition Submissions on Data Science, Machine and Deep Learning

1. Titanic Survival Prediction - Kaggle [Link](https://www.kaggle.com/c/titanic)
   - Position: Top 33% [78% Accuracy]
   - Model: Random Forest (/w Parameter gridsearch)
   - Data Preprocessing: Missing values and outliers removal (cleaning), replaced age data to categorical bins
      
2. MNIST Digit Recognizer - Kaggle  [Link](https://www.kaggle.com/c/digit-recognizer)
   - Position: Top 18% [94.5% Accuracy] (91% without data augmentation)
   - Model: CNN (Modified LeNet, 2Conv, 2FC)
   - Data Preprocessing: Normalization and Data Augmentation (Translate and Rotate-Crop)
   - Optimizer: SGD + momentum with Step LR decay
   - Regularization: Dropout (0.2)
   
3. CIFAR-10 Image Classification - Kaggle [Link](https://www.kaggle.com/c/cifar-10)
   - Position: 81% Accuracy (74% without data augmentation)
   - Model: CNN (4 Conv, 3FC) 
   - Optimizer: Adam with LR decay
   - Data Preprocessing: Normalization and Data Augmentation (Translate, Rotate and Zoom)
   - Regularization: Dropout (0.25) or BatchNormalisation [Both gave similar performance]
   
3. Facial Keypoint Detection - Kaggle [Link](https://www.kaggle.com/c/facial-keypoints-detection)
- Position: 2.456 (Mean Average Error)
- Model: CNN (3 Conv, 3FC) 
- Optimizer: Adam with LR decay
- Data Preprocessing: Normalization
- Regularization: Dropout (0.25)

