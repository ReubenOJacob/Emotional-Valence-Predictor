# Emotional-Valence-Predictor
Deep Learning Framework for Emotional Valence Prediction Using Popular CNN Architectures and Efficient Data Generation.


This project proposes a deep learning-based framework for Emotional Valence Prediction in images using popular CNN architectures including VGG16, ResNet50, and InceptionV3. This paper utilised the ArtEmis dataset, which was pre-processed using a Python script. The framework utilizes pre-processed image data and labels stored as NumPy arrays on Google Drive. The core of the proposed framework lies in the createmodel and trainevaluatemodel functions. The createmodel function constructs the CNN model by combining a selected base model architecture with custom classification layers. The base model is initialized with pre-trained weights from the ImageNet dataset and its layers are frozen to preserve the learned features during training. The trainevaluatemodel function performs model training and evaluation using the provided data generators. It includes early stopping to prevent overfitting and computes the validation accuracy and a classification report for performance evaluation. The framework further includes a model selection mechanism that iterates through the specified model names and tracks the best-performing model based on validation accuracy. The framework allows researchers to easily experiment with different CNN architectures, leverage pretrained models, and assess model performance using appropriate evaluation metrics. Overall, this framework provides a valuable tool for deep learning-based emotional valence prediction research and its applications.
