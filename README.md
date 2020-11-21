### Problem Description

Kaggle "Real or Not? NLP with Disaster Twets" aims to create a model that can detect tweets about crisis situations that are posted in real time.

### Data Analysis

<img src="./img/data_analysis_1.png" width="400" >

<img src="./img/data_analysis_2.png" width="400" >

##### Preprocess

URL, html, emoji and special characters and meaningless stopwords such as "a" and "the" were removed. Also, we changed the abbreviation that is commonly used on Twitter into the original sentence.

<img src="./img/preprocessed_data.png" width="600" >

### Model
1. GloVE

   <img src="./img/GloVe_model.png" width="250" >

2. XGBoost

3. BERT
    1. BERT + transfer learning
    
       <img src="./img/transfer_learning_outline.png" width="350" >
       
    2. BERT + joint learning
           
       <img src="./img/joint_learning_outline.png" width="350" >
