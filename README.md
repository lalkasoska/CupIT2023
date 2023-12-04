# General information
Our team participated in the CupIT competition in which we had to develop a language model for comment ranking in a social network. We were given a dataset with posts, where each post contains a post's text and texts of four comments to it. The comments were sorted by their rating. We conducted an EDA and decided to train DistilBERT for this task.
<br /><br />
We used Pyhton3 and Google Collab for this task. We used such modules as:<br />

- scikit-learn<br />
- nltk<br />
- numpy<br />
- pandas<br />
- transformers<br /> 
- pytorch<br />
- matplotlib<br />
- json<br />
- textblob<br />
- textstat<br />
- spellchecker<br />

After training the model acheived NDCG metric value of 0.88.
# Overview
![Ранжирование комментариев с помощью ML Кабанда_page-0001](https://github.com/x-wheel-of-fortune/CupIT_2023/assets/35616551/407f2e4e-5ea8-4c37-b970-89d298fb1417)
![Ранжирование комментариев с помощью ML Кабанда_page-0002](https://github.com/x-wheel-of-fortune/CupIT_2023/assets/35616551/0eb75356-8111-4100-b996-626bde8a6c45)
![Ранжирование комментариев с помощью ML Кабанда_page-0003](https://github.com/x-wheel-of-fortune/CupIT_2023/assets/35616551/52cafc22-c6ee-4717-b932-33811bfb5712)
![Ранжирование комментариев с помощью ML Кабанда_page-0004](https://github.com/x-wheel-of-fortune/CupIT_2023/assets/35616551/2699ac32-0b9d-45c6-8514-0db48d3ebedd)
![Ранжирование комментариев с помощью ML Кабанда_page-0005](https://github.com/x-wheel-of-fortune/CupIT_2023/assets/35616551/6a809cf9-d9cf-42ca-9f62-7703013e6b34)
![Ранжирование комментариев с помощью ML Кабанда_page-0006](https://github.com/x-wheel-of-fortune/CupIT_2023/assets/35616551/226c836c-baba-451e-82eb-fb7aae4ca710)
![Ранжирование комментариев с помощью ML Кабанда_page-0007](https://github.com/x-wheel-of-fortune/CupIT_2023/assets/35616551/10300d42-a4d7-47b5-b012-1d5299bb9da4)
![Ранжирование комментариев с помощью ML Кабанда_page-0008](https://github.com/x-wheel-of-fortune/CupIT_2023/assets/35616551/5201461a-1d0f-42b5-84e8-3b526a73e20e)

# Some of the EDA histograms
Correlation between comment length and its rating (with 0 being the highest and 4 the lowest).
![image](https://user-images.githubusercontent.com/35616551/236813835-5c6eb5bf-c3da-4da1-80df-5c794fcdd26f.png)
Distribution of positive/negative comments among all.
![image](https://user-images.githubusercontent.com/35616551/236813874-4b107160-3351-4195-88d4-f6abaa287989.png)
Correlation between the percentage of spelling mistakes in a commentary and its rating (with 0 being the highest and 4 the lowest).
![image](https://user-images.githubusercontent.com/35616551/236813934-ea1faa68-5c53-4ed7-88c4-58a53bf430c0.png)
