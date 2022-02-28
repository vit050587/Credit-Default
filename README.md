# Kaggle-Competition-Credit-Default
![MarkDown](https://github.com/vit050587/Kaggle-Competition-Credit-Default/blob/master/kaggle.png)
## Description
* Ваша задача этом соревновании - предсказать факт невыполнения кредитных обязательств в датасете test.csv. Вам будут даны два датасета: train.csv (содержит признаки и факт невыполнения кредитных обязательств) и test.csv (только признаки).
* Invite link for this competition: https://www.kaggle.com/t/629f0f9238324b9d819d26838be92544
## Evaluation
* The evaluation metric for this competition is F1-Score.

$$
F1 = 2\frac{p \cdot r}{p+r}\ \ \mathrm{where}\ \ p = \frac{tp}{tp+fp},\ \ r = \frac{tp}{tp+fn} 
$$

The F1 metric weights recall and precision equally, and a good retrieval algorithm will maximize both precision and recall simultaneously. Thus, moderately good performance on both will be favored over extremely good performance on one and poor performance on the other.
