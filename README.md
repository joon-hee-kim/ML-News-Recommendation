# ML_News_Recommendation
This is the result of news articles' recommendation systems using machine-learning algorithms.

## Motivation
Our team initiated this project to tackle the issue of information overload in digital news consumption. By using the MIND dataset (The data source is listed below), we aim to develop a personalized news recommendation system that enhances user engagement and satisfaction. This project allows us to apply machine learning techniques to real-world challenges, deepening our understanding and skills in recommendation system development.

## End-to-End Process (with Output)
1. Business objective </br>
-  Develop a news recommendation system for "Personalized News Delivery, User Engagement Enhancement, Market Competitiveness"</br>
2. Data exploration </br>
-  news.tsv - 51282 news info </br>
<img width="250" alt="image" src="https://github.com/user-attachments/assets/05117afd-048e-4f8b-b9b9-60468fcbb766"> </br>
<img width="250" alt="image" src="https://github.com/user-attachments/assets/b4bebd13-30f5-4f37-a211-514b530aba90"> </br>

- news.tsv - 17 categories </br>
<img width="450" alt="image" src="https://github.com/user-attachments/assets/99b6da81-9292-4a63-8af3-070572ee29d7"> </br>

-  news.tsv - 264 subcategories </br>
![image](https://github.com/user-attachments/assets/322ce4da-3e2a-472c-ab7c-7078f886fd3d) </br>

- news.tsv - Subcategories for news </br>
<img width="450" alt="image" src="https://github.com/user-attachments/assets/adee6eef-afb7-45b6-90f9-0c726f4073a7"> </br>
- news.tsv - Subcategories for sports</br>
<img width="450" alt="image" src="https://github.com/user-attachments/assets/885e9555-56aa-4a60-9e2c-d6a58ff151b6"> </br>
- news.tsv - Subcategories for food</br>
<img width="450" alt="image" src="https://github.com/user-attachments/assets/ffd34f0b-831f-4189-912f-1f0ffb15efca"> </br>
- news.tsv - Subcategories for finance</br>
<img width="450" alt="image" src="https://github.com/user-attachments/assets/7a963754-5709-4a5c-8665-47d7c93a2402"> </br>
-  news.tsv - Top 10 titles</br>
<img src="https://github.com/user-attachments/assets/cbdcd363-54a0-4ca7-9314-e7c0d883b24d" width="650"> </br>
-  news.tsv - titles sentiment_polarity</br>
<img width="452" alt="image" src="https://github.com/user-attachments/assets/1c5f8a73-0fe2-4d0d-af32-d37088438ec1"> </br>
- behaviors.tsv - 50000 users info </br>
<img src="https://github.com/user-attachments/assets/a8b3f232-fb12-4961-9b81-937ab10c4624" width="650"> </br>
- behaviors.tsv - Frequent read time </br>
<img src="https://github.com/user-attachments/assets/8594cdd6-9173-4bfc-9824-54cb4474b5d0" width="650"> </br>

- behaviors.tsv - user click history </br>
<img src="https://github.com/user-attachments/assets/8594cdd6-9173-4bfc-9824-54cb4474b5d0" width="650"> </br>
<img src="https://github.com/user-attachments/assets/33169626-a4ac-4f84-af3b-0f491b4855e0" width="650"> </br>

3. Data preprocessing </br>
-  news.tsv - Create Content feature to merge texts </br>
<img src="https://github.com/user-attachments/assets/264bead9-df54-4e4f-9ed0-4ea855da777f" width="650"> </br>

-  news.tsv - Create Embedding Vectors </br>
<img src="https://github.com/user-attachments/assets/1a51bbf2-1876-4603-be17-c7d2b8b304d6" width="650"> </br>

<img src="https://github.com/user-attachments/assets/ebe97cab-db01-4309-894d-fd8a29b3f276" width="650"> </br>


-  behavior.tsv - History to Click(1) or Not(0) </br>
<img src="https://github.com/user-attachments/assets/6b53e505-4cce-4cbc-be14-9fb9fff3cc2f" width="650"> </br>


4. Modeling  </br>
- Collaborative Filtering: User-based filtering </br>
<img src="https://github.com/user-attachments/assets/e5702926-ba8a-44a5-963b-519154a4db35" width="650"> </br>


- Content-Based Filtering: Using Embedding Vec </br>
<img src="https://github.com/user-attachments/assets/40b168ab-8063-44c6-adec-d6ccf9442430" width="650"> </br>


- Content-Based Filtering: Using TF-IDF </br>
<img src="https://github.com/user-attachments/assets/84c0f038-b398-423d-9f76-28e45af80d6e" width="650"> </br>


5. Data Analysis </br>
5. Learning model evaluation and analysis 
- Three Results - User based, Embedding vec, TF-IDF </br>
<img src="https://github.com/user-attachments/assets/7647a56b-cf72-45a0-81a1-4461aed97837" width="650"> </br>


-  </br>


## 👥 Team Member
201934219 Kim Joonhee </br>
202035302 Kang Jiyun</br>
202234879 Kim Chungyoung </br>
202235128 Cho Jaehyeon </br>

 
## ✔️ Source
* ChatGPT </br>
* [MIND Dataset: MIcrosoft News Dataset](https://www.kaggle.com/datasets/arashnic/mind-news-dataset?resource=download) </br>


