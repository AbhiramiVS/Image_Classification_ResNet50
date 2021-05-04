# Image_Classification_ResNet50
Multi class image classification using ResNet50 pre-trained model and single instance prediction for trained model.

This is an image classification model for 5 different types of flowers. The dataset can be downloaded from https://www.kaggle.com/alxmamaev/flowers-recognition.

The dataset is already contained inside the folder 'dataset/input_dataset' Split-folder library is used for splitting the folder into train, test and validation folders. This has already done and splitted data is kept in 'dataset/preprocessed_data'. But if you really want to try out how it's done, please install split-folder library and run 'Preprocessing.ipynb' notebook.
To install split-folder, use --> pip install split-folders

The whole classification task is done in 'Flowers_classification.ipynb'.

Change 'class_index.json' for the custom data labels you have in your datset. 
Change image_util.py, line number 137, preds.shape[1] != <number of class labels you have in dataset>.
  
For any doubts, please contact https://www.linkedin.com/in/abhirami-v-s-138884b4/ or abhirami.venu96@gmail.com
