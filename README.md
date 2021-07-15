# Репозиторий-портфолио для моих DA проектов

Ниже для каждого проекта будет приведена ссылка на его просмотр через **NBViewer**, поскольку гитхаб не рендерит оглавления проектов и интерактивные графики.

**Для связи со мной**: 
- vk: https://vk.com/zlotsky
- telegram: https://t.me/da_zlotsky


## О проектах:
- это проекты с курса 'Профессия аналитик данных' от Яндекс.Практикума;
- нумерация проектов (project1, project2...) соответствует хронологическому порядку прохождения курса;
- примерные времязатраты на выполнение 9 проектов (это 2/3 курса, впереди еще 3 проекта) около 180 часов чистого времени. Затраты на изучение теории (тренажер ЯП, теоретические блоки и доп. материалы): еще около 60 часов.

## Краткое описание проектов по порядку (описание данных, цель исследования, основные инструменты):
#### 1. [project1_bank_scoring_system](https://nbviewer.jupyter.org/github/VladislavZlotsky/data_analysis_projects/blob/main/project1_bank_scoring_system/project1_bank_scoring_system.ipynb):
 - Данные о клиентах банка. 
 - Цель: определить факторы, влияющие на платежеспособность. 
 - Инструменты: numpy/pandas/seaborn/pymystem3(лемматизация для категоризации целей кредита);
#### 2. [project2_real_estate_data_saint_petersburg](https://nbviewer.jupyter.org/github/VladislavZlotsky/data_analysis_projects/blob/main/project2_real_estate_data_saint_petersburg/project2_real_estate_data_saint_petersburg.ipynb):
 - Данные о недвижимости Санкт-Петербурга и Ленобласти. 
 - Цель: определить факторы, влияющие на стоимость недвижимости, а также выявить аномалии. 
 - Инструменты: numpy/pandas/plotly;
#### 3. [project3_telecom_tariffs](https://nbviewer.jupyter.org/github/VladislavZlotsky/data_analysis_projects/blob/main/project3_telecom_tariffs/project3_telecom_tariffs.ipynb): 
 - Данные об активности выборки пользователей телеком-услуг по двум тарифам. 
 - Цель: проанализировать поведение клиентов, определить перспективный тариф. 
 - Инструменты: numpy/pandas/plotly/scipy.stats(тестирование гипотез);
#### 4. [project4_gaming_platforms_market](https://nbviewer.jupyter.org/github/VladislavZlotsky/data_analysis_projects/blob/main/project4_gaming_platforms_market/project4_gaming_platforms_market.ipynb):
 - Данные о продажах игр и их платформах с 1980 по 2016 гг. 
 - Цель: выявить определяющие успешность игры закономерности. Это позволит сделать ставку на потенциально популярный продукт. 
 - Инструменты: numpy/pandas/plotly/scipy.stats;
#### 5. 5-й проект был выполнен наполовину в среде тренажера Практикума через SQL, поэтому здесь не приведен;
#### 6. [project6_cohort_analysis_marketing_metrics](https://nbviewer.jupyter.org/github/VladislavZlotsky/data_analysis_projects/blob/main/project6_cohort_analysis_marketing_metrics/project6_cohort_analysis_marketing_metrics.ipynb):
 - Данные: логи визитов, логи покупок и данные динамики маркетинговых затрат с сервиса Яндекс.Афиши. 
 - Цель: помочь маркетологам оптимизировать расходы, отказаться от невыгодных источников трафика и перераспределить маркетинговый бюджет. 
 - Инструменты: numpy/pandas/plotly/scipy.stats;
#### 7. [project7_online_shop_ab_testing](https://nbviewer.jupyter.org/github/VladislavZlotsky/data_analysis_projects/blob/main/project7_online_shop_ab_testing/project7_online_shop_ab_testing.ipynb):
 - Логи интернет-магазина о визитах и покупках пользователей с разделением на A/B группы, а также данные о гипотезах и их оценке. 
 - Цель: приоритизировать гипотезы, провести тесты гипотез, проанализировать результаты A/B-теста. 
 - Инструменты: numpy/pandas/plotly/scipy.stats;
#### 8. [project8_geoanalytics_API_moscow_restaurants](https://nbviewer.jupyter.org/github/VladislavZlotsky/data_analysis_projects/blob/main/project8_geoanalytics_API_moscow_restaurants/project8_geoanalytics_API_moscow_restaurants.ipynb):
 - Данные об объектах общественного питания Москвы. 
 - Цель: анализ рынка, формулирование рекомендаций для инвесторов. 
 - Инструменты: numpy/pandas/plotly/scipy.stats/re(регулярки для вычленение улицы из адреса)/geocoder(для получения геоданных с API Google Maps)/pymorphy2(для приведения названий районов к нормальной форме)
#### 9. [project9_conversion_funnel_multiple_testing](https://nbviewer.jupyter.org/github/VladislavZlotsky/data_analysis_projects/blob/main/project9_conversion_funnel_multiple_testing/project9_conversion_funnel_multiple_testing.ipynb):
 - Данные: событийные логи из приложения, продающего продукты питания. 
 - Цель: изучить воронку событий, конверсии, провести множественное тестирование гипотез и исследовать результаты A/A/B-эксперимента. 
 - Инструменты: numpy/pandas/plotly/scipy.stats.
