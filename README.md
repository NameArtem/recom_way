# recom_way

Здесь собираю самые интересные статьи и работы по рекомендательным системам, которые позволили мне увеличить качество рекомендаций и/или сделать их интересными. Реализацию, наиболее интересные метрики и процесс развития эксперимента будут размещены [тут](https://github.com/NameArtem/recomy) в мае.



### Содержание :page_with_curl:
* [JustRecommendations](#jr)
* [Для доклада PyConBy 2021](#pyconby2021)
* [Подборка для доклада на AIJ 2020](#aij2020)

------------------------------------------------

</br>
</br>
</br>

### Just Recommendations

<a name="jr"></a>

Делаю эксперименты и реализую их в [telegram боте](https://t.me/just_recommendations)

**Список экспериментов**

- [x] **0.1.0** Первый запуск 11.01.2021

> Интересно опробовать контекст 2020 года и посмотреть, какие рекомендации можно получить, чтобы в 2021 реализовать всё.

Метод: Context Aware

Статья: [Статья о Context Aware](https://www.researchgate.net/publication/220605653_Context-Aware_Recommender_Systems)

</br>

- [x] **0.1.1** Добавление разного контекста (фильм, вино, еда в одной рекомендации)

> Всё ещё работаю с контекстом, но рекомендую от контекста фильма или вина.

Метод: Context Aware / Отбор по Top-N

Статья: [Top-N Recommender System via Matrix Completion](https://arxiv.org/pdf/1601.04800v1.pdf)

</br>

------------------------------------------------
</br>
</br>
</br>

### Для доклада PyConBy 2021

<a name="pyconby2021"></a>

**Презентация**
* [Доклад на YouTube](-)

* [Презентация к докладу](context/presentations/PyConBy2021.pdf)

**Статьи, которые повлияли на работу (систему рекомендаций) и помогли её сделать:**
* [Context-Aware recommender systems for real world Applications](context/papers/77724_AL-GHOSSEIN_2019_archivage.pdf)

* [Collaborative filtering for implicit feedback datasets](context/papers/als_cf.pdf)

* [Multi-gradient descent for multi-objective recommender systems](context/papers/2001.00846v3.pdf)

* [Context-aware sequential recommendation](context/papers/1609.05787.pdf)

* [Context-aware recommendations from implicit data via scalable tensor factorization](context/papers/1309.7611.pdf)


**Все ещё не получается реализовать:**
* [A missing information loss for implicit feedback datasets](context/papers/1805.00121.pdf)


**Примеры реализованных методов:**
* [ALS](context/methods/ALS%20algorithm%20from%20collaborative%20filtering%20for%20implicit.ipynb)

* [ALS and filter](context/methods/ALS%20filter.ipynb)

* [Context](context/methods/context_score.ipynb)








------------------------------------------------
</br>
</br>
</br>

### Подборка для доклада на AIJ 2020

<a name="aij2020"></a>

[Ссылка на доклад](https://youtu.be/twLBjQ-MCYI)

**Работы для включения контекста в расчет рекомендаций**

•	[Статья о Context Aware](https://www.researchgate.net/publication/220605653_Context-Aware_Recommender_Systems)

•	[Статья о Deep Context Aware](https://arxiv.org/pdf/1909.03999.pdf)

•	[Git проект №1 в этом направлении](https://github.com/uwdata/dziban)

•	[Git проект №2 в этом направлении](https://github.com/primalpop/camrs)

------------------------------------------------

**Обзор метрик для рекомендаций**

•	[Метрики](https://www.researchgate.net/publication/268381252_Setting_Goals_and_Choosing_Metrics_for_Recommender_System_Evaluations)

------------------------------------------------

**Калибровка скоринга**

•	[Трансформация ROC_AUC](https://www.researchgate.net/publication/322205695_Transforming_the_Area_under_the_Normal_Curve_AUC_into_Cohen's_d_Pearson's_r_pb_OddsRatio_and_Natural_Log_Odds-Ratio_Two_Conversion_Tables)

•	[Калибровка – общая информация](https://arxiv.org/ftp/arxiv/papers/1710/1710.08901.pdf)

•	[Калибровка классификатора в вероятность](https://www.researchgate.net/publication/263729876_Tutorial_on_logisticregression_calibration_and_fusionconverting_a_score_to_a_likelihood_ratio)

•	[Калибровка кредитного скоринга](https://www.researchgate.net/publication/318702064_Approaches_for_Credit_Scorecard_Calibration_An_Empirical_Analysis)

•	[Калибровка для рекомендательных систем](http://ethen8181.github.io/machine-learning/recsys/calibration/calibrated_reco.html)

------------------------------------------------

**Random PFM**

•	[Статья в сборнике](https://link.springer.com/chapter/10.1007/978-3-319-39937-9_17)

•	[Пример реализации 1](https://github.com/RuidongZ/Deep_Matrix_Factorization_Models)

•	[Пример реализации 2](https://github.com/hexiangnan/adversarial_personalized_ranking)

------------------------------------------------

**Cycling**

•	[Статья о Cycling](http://cinv.ro/files/ICDM17.pdf)

•	[Статья о улучшении взаимодействия при помощи Cycling](https://experts.umn.edu/en/publications/toward-better-interactions-in-recommender-systems-cycling-and-ser-2)

------------------------------------------------

**Serendipity**

•	[Статья о валидации и применении serendipity](https://paperswithcode.com/paper/user-validation-of-recommendation-serendipity)

•	[Обзорная статья](https://www.scitepress.org/Papers/2016/58798/58798.pdf)

•	[Применение в Collaborative Filtering](https://github.com/nair-p/Serendipitous-Clustering-for-Collaborative-Filtering)

•	[Git с применением метода и его описанием](https://github.com/prallis/Recommender-systems-optimization-for-coverage-diversity-and-serendipity)

<!--https://medium.com/tech-tajawal/recommendation-engine-explained-c5b8642cc0f-->
