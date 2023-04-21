# Labelling

Implemented a semi-supervised learning approach using BERT for labelling. For this I used both the labelled data and unlabelled data.
Below are the steps I followed:

- Used labeled data to train a BERT-based model to classify text into six labels. 
- The trained model is then used to predict the labels for the unlabeled data. The predicted labels are concatenated with the labels of the labeled data.
- The model is retrained on this combined labeled and unlabeled data. This process is repeated for a few epochs until the accuracy of the model stabilizes.
-This approach is a form of semi-supervised learning since it uses the predicted labels of the unlabeled data to improve the classification accuracy of the model.
