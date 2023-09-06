# EEG Sleep Stage Classification (ML/DL)

I have used a sleep dataset from Haaglanden Medisch Centrum (HMC), containing EEG signals from different brain lobes. It can be found [here](https://www.kaggle.com/datasets/rafsanjany44/rem-and-nrem-sleep-classification), in Kaggle. The dataset has 154 sleep recordings with 75 features and two classes: NREM and REM sleep stages. The dataset has 89096 examples in total. I applied machine/deep learning models including Random Forest and XGBoost, as well as a Convolutional Neural Network (CNN) with three Conv1D layers (64, 128, and 256 filters) for feature extraction. Batch normalization and dropout layers were used to improve model performance and prevent overfitting. The CNN architecture ends with fully connected layers for classification, using a sigmoid activation function and the Adam optimizer. You can check out the details including the accuracy of each model in the notebook.