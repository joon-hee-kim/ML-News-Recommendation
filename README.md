# ML_News_Recommendation
This is the result of news articles' recommendation systems using machine-learning algorithms.

## Notice! ##
Go to the following site and download ‘behaviors.tsv’, ‘entity_embedding.vec’, and ‘news.tsv’ and run the code with them. Please understand that files cannot be uploaded due to file size issues.
* [MIND Dataset: MIcrosoft News Dataset](https://www.kaggle.com/datasets/arashnic/mind-news-dataset?resource=download) </br>

## Motivation
Our team initiated this project to tackle the issue of information overload in digital news consumption. By using the MIND dataset (The data source is listed below), we aim to develop a personalized news recommendation system that enhances user engagement and satisfaction. This project allows us to apply machine learning techniques to real-world challenges, deepening our understanding and skills in recommendation system development.

## End-to-End Process (with Output)
## 1. Business objective </br>
-  Develop a news recommendation system for "Personalized News Delivery, User Engagement Enhancement, Market Competitiveness"</br>

## 2. Data exploration </br>
-  news.tsv - 51282 news info </br>
<img width="422" alt="image" src="https://github.com/user-attachments/assets/05117afd-048e-4f8b-b9b9-60468fcbb766"> </br>
<img width="350" alt="image" src="https://github.com/user-attachments/assets/b4bebd13-30f5-4f37-a211-514b530aba90"> </br>

- news.tsv - 17 categories </br>
<img width="750" alt="image" src="https://github.com/user-attachments/assets/99b6da81-9292-4a63-8af3-070572ee29d7"> </br>

-  news.tsv - 264 subcategories </br>
<img width="950" alt="image" src="https://github.com/user-attachments/assets/322ce4da-3e2a-472c-ab7c-7078f886fd3d"> </br>

- news.tsv - Subcategories for news </br>
<img width="452" alt="image" src="https://github.com/user-attachments/assets/80d9cedc-2c83-40b8-b80c-1a7a2d814799"> </br>
- news.tsv - Subcategories for sports</br>
<img width="452" alt="image" src="https://github.com/user-attachments/assets/28b16a51-14f1-47bc-9500-51cd022f60d9"> </br>
- news.tsv - Subcategories for food</br>
<img width="452" alt="image" src="https://github.com/user-attachments/assets/c1350c76-f282-4a36-ad29-5c95233dddc5"> </br>
- news.tsv - Subcategories for finance</br>
<img width="452" alt="image" src="https://github.com/user-attachments/assets/26076d53-79b9-4405-8e7c-bedb57dd0fa9"> </br>

-  news.tsv - Top 10 titles </br>
<img src="https://github.com/user-attachments/assets/cbdcd363-54a0-4ca7-9314-e7c0d883b24d" width="550"> </br>

-  news.tsv - titles sentiment_polarity</br>
<img width="750" alt="image" src="https://github.com/user-attachments/assets/1c5f8a73-0fe2-4d0d-af32-d37088438ec1"> </br>

- behaviors.tsv - 50000 users info </br>
<img src="https://github.com/user-attachments/assets/a8b3f232-fb12-4961-9b81-937ab10c4624" width="650"> </br>

- behaviors.tsv - Frequent read time </br>
<img src="https://github.com/user-attachments/assets/8594cdd6-9173-4bfc-9824-54cb4474b5d0" width="750"> </br>

- behaviors.tsv - user click history </br>
<img src="https://github.com/user-attachments/assets/33169626-a4ac-4f84-af3b-0f491b4855e0" width="550"> </br>

## 3. Data preprocessing </br>
-  news.tsv - Create Content feature to merge texts </br>
<img src="https://github.com/user-attachments/assets/264bead9-df54-4e4f-9ed0-4ea855da777f" width="850"> </br>

-  news.tsv - Create Embedding Vectors </br>
<img src="https://github.com/user-attachments/assets/1a51bbf2-1876-4603-be17-c7d2b8b304d6" width="850"> </br> </br>

<img src="https://github.com/user-attachments/assets/ebe97cab-db01-4309-894d-fd8a29b3f276" width="650"> </br>

-  behavior.tsv - History to Click(1) or Not(0) </br>
<img src="https://github.com/user-attachments/assets/6b53e505-4cce-4cbc-be14-9fb9fff3cc2f" width="650"> </br>


## 4. Modeling & Data Analysis (Detailed explanations are described in CoLab) </br>
- Compare Three Results For Evaluating Common Characteristics And Recommendation Quality (Such as Overlapping Items) - Collaborative Filtering: User-based filtering, Content-Based Filtering: Using Embedding Vec, Content-Based Filtering: Using TF-IDF </br>
- While User-Based and TF-IDF had some overlapping items, the embedding method produced independent recommendation results that did not overlap with the other two methods. </br> 

<img src="https://github.com/user-attachments/assets/7647a56b-cf72-45a0-81a1-4461aed97837" width="850"> </br>

## 5. Model Evaluation (Detailed explanations are described in CoLab) </br>
- Two Results - Precision@K showed high performance, whereas Cross-validation-based evaluation showed poor performance </br>
<img src="https://github.com/user-attachments/assets/352c68e7-dc71-4840-8963-3e8db50243b3" width="450"> </br>
<img src="https://github.com/user-attachments/assets/c0411fc7-bdb0-432d-9c5b-c8e7bbddec97" width="850"> </br>


## 👥 Team Member
201934219 Kim Joonhee </br>
202035302 Kang Jiyun</br>
202234879 Kim Chungyoung </br>
202235128 Cho Jaehyeon </br>

 
## ✔️ Source
* ChatGPT </br>
* [MIND Dataset: MIcrosoft News Dataset](https://www.kaggle.com/datasets/arashnic/mind-news-dataset?resource=download) </br>
* [Introduction to MIND and MIND-small datasets](https://github.com/msnews/msnews.github.io/blob/master/assets/doc/introduction.md) </br>
* [Text classification using movie reviews](https://www.tensorflow.org/tutorials/keras/text_classification?hl=ko) </br>
* [GlobalAveragePooling1D layer](https://keras.io/api/layers/pooling_layers/global_average_pooling1d/) </br>
* [How to use Keras embedding layer](https://colinch4.github.io/2023-09-07/11-55-40-102484/) </br>
* [Embeddings](https://kaggler-tv.github.io/dku-kaggle-class/lectures/14-embeddings.html) </br>



