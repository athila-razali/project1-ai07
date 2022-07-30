# Heart Disease Prediction using FeedForward Neural Network
## Summary
**Aim** : To construct a deep learning model in order to predict whether a patient has a heart disease or not.   
The "target" field indicates to the patient's having heart illness. 0 = no disease, while 1 = disease.   
**Data Source** : Dataset credits all to [Kaggle: Heart Disease Dataset](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset)
## Methodology
### 1. Data Pipeline
Data is loaded and preprocessed. After data is cleaned, the features and labels are identified.
Then, data is split into train and test set with ratio of 70:30. Data normalization has been made using StandardScaler() module from scikit-learn library.
### 2. Model Pipeline
As data is ready to being trained, the classification problem is addressed with a feedforward neural network model. 
The model has a rather straightforward structure. The model's structure is depicted in the figure below:    
        
![P1structure](https://user-images.githubusercontent.com/91872382/181879146-0e9975cc-e171-427f-abaa-b382e2cff291.png)    
        
The model is trained with a batch size of 32 and for 20 epochs. Only two hidden layers with 64 nodes is applied in this training to reduce overfitting.
The results of the training process are shown in the graph visualized by Matplotlib below:     
       
<img width="292" alt="image" src="https://user-images.githubusercontent.com/91872382/181879358-f49b1899-6051-4dbf-93f8-98205cfb5a07.png"> <img width="306" alt="image" src="https://user-images.githubusercontent.com/91872382/181879373-83257f14-0e09-4a39-8eaa-846e22e98382.png">
       
## Results
The model has been evaluated. The evaluation result is shown in the figure below:        
     
   <img width="552" alt="image" src="https://user-images.githubusercontent.com/91872382/181879753-aa2aae9c-11ec-4adf-bd67-a8388e5fe401.png">

      
Since both the train and test results have an accuracy above 90%, we can say that the model are accurate.

### Credits
**Instructor : Kong Kah Chun**      
**Selangor Human Resource Development Center**
