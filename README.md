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

# Some of the EDA histograms
Correlation between comment length and its rating (with 0 being the highest and 4 the lowest).
![image](https://user-images.githubusercontent.com/35616551/236813835-5c6eb5bf-c3da-4da1-80df-5c794fcdd26f.png)
Distribution of positive/negative comments among all.
![image](https://user-images.githubusercontent.com/35616551/236813874-4b107160-3351-4195-88d4-f6abaa287989.png)
Correlation between the percentage of spelling mistakes in a commentary and its rating (with 0 being the highest and 4 the lowest).
![image](https://user-images.githubusercontent.com/35616551/236813934-ea1faa68-5c53-4ed7-88c4-58a53bf430c0.png)
