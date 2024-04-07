# Explainable AI in the Diagnosis and Classification of Diabetic Retinopathy 
This project aims to use transfer learning to fine-tune a Deep Learning Model and use this model to predict the diagnosis and classification of Diabetic Retinopathy, with XAI tools used to explain the model's classifications.
***
**Objectives:**
- Pre-process images from the APTOS dataset
- Use transfer learning to train a ResNet-50 deep learning model (pretrained on ImageNet) and fine-tune it for the classification of Diabetic Retinopathy from retinographs
- Evaluate the model's performance
- Apply LIME and SHAP explanations to the model's predictions for each class of Diabetic Retinopathy
***
The project was primarily carried out on Google Colab due to the increased computational power there needed to efficiently train a deep learning model.

Google Colab / Drive was also used to house the APTOS dataset, the Preprocessed Dataset and the saved fine-tuned model, which cannot be found on this GitHub repository due to the space constraints with uploading and storing on Github.

This GitHub repository is used instead to house the jupyter notebooks including all of their results / produced graphs for visualisation of the completed project. Thus, the experiment cannot be recreated here.

The link to the Google Drive / Colab folder which houses all aspects of the project (including datasets, jupyter notebooks and resulting graphs) is shown below, where the experiment can be reproduced:

[The Google Drive folder for this project can be found here](https://drive.google.com/drive/folders/1cIBkJjVbjrElY0HEZBc7Q5wL6G46ZVN7?usp=sharing)
***
**Resources Used:**
- APTOS 2019 Blindness Detection Dataset - [(Kaggle Competition)](https://www.kaggle.com/competitions/aptos2019-blindness-detection/data)
- Ben Graham's Preprocesseing Method for Retinographs - [(GitHub)](https://github.com/btgraham/SparseConvNet/tree/kaggle_Diabetic_Retinopathy_competition)
- ResNet-50 Deep Learning Model (Pretrained on ImageNet)
- SHAP Explainer - [(GitHub)](https://github.com/shap/shap)
- LIME Explainer - [(GitHub)](https://github.com/marcotcr/lime)
