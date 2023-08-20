# Репозиторий учебных проектов из Яндекс Практикум «Аналитик данных»
**Projects by [Practicum Yandex](https://practicum.yandex.ru)**

**Certificates: [Russian version](Сертификат_Русский.pdf), [English version](Certificate_English.pdf)**

| Название проекта | Описание проекта | Импользуемые библиотеки |
| :---         |     :---:      |          ---: |
| [Исследование продаж видеоигр](Исследование_продаж_видеоигр.ipynb)   | На основе исторических данных о продажах игр за 2016 год изучена зависимость продаж видеоигр от платформ, построены показательные графики. Определены наиболее прибыльные платформы. Исследовано влияние отзывов пользователей и критиков на продажи внутри одной популярной платформы. Проверены гипотезы о средних рейтингах определенных платформ и жанров игр.    | Предобработка данных в pandas, визуализация в matplotlib и seaborn, проверка гипотез с помощью scipy.  |
| [Анализ бизнес-показателей мобильного приложения](Анализ_бизнес-показателей_мобильного_приложения.ipynb)    | Изучено откуда приходят пользователи и какими устройствами они пользуются; сколько стоит привлечение пользователей из различных рекламных каналов; сколько денег приносит каждый клиент; когда расходы на привлечение клиента окупаются; какие факторы мешают привлечению клиентов. Составлены профили пользователей, рассчитаны метрики LTV, CAC, Retention rate, ROI. |Предобработка данных в pandas и datetime, визуализация в matplotlib и seaborn |
| [АВ-тестирование. Приоритезация гипотез](АВ-тестирование_Приоритезация_гипотез.ipynb)    | Проведена приоретитзация гипотез с помощью фреймворков ICE и RICE. Проведено A/B-тестирование, сделаны выводы на основе графиков куммулятивных метрик и проверке гипотез о статистической значимости групп.  | Предобработка данных в pandas и datetime, визуализация в matplotlib и seaborn, проверка гипотез с помощью scipy.    |
| [Изучение воронки продаж. Исследование результатов A/A/B-эксперимента](Анализ_поведения_пользователей_мобильного_приложения.ipynb)   | В данном проекте мной были изучены принципы событийной аналитики. Я построила воронку продаж, исследовала путь пользователей до покупки. Проанализировала результаты A/B-теста введения новых шрифтов. Сравнила 2 контрольных группы между собой, убедилась в правильном разделении трафика, а затем сравнила с тестовой группой. Выявлено, что новый шрифт значительно не повлияет на поведение пользователей.  | pandas, datetime, matplotlib, numpy, scipy, math, seaborn, plotly, statsmodels, proportions_ztest   |
