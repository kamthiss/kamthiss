<div align="center">

# Никита Сафронов

**Продуктовый аналитик**

Каждый проект отвечает на один бизнес-вопрос и заканчивается решением, а не графиком

<br>

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL">
<img src="https://img.shields.io/badge/SQL-336791?style=flat-square" alt="SQL">
<img src="https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white" alt="dbt">
<img src="https://img.shields.io/badge/Metabase-509EE3?style=flat-square&logo=metabase&logoColor=white" alt="Metabase">
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" alt="scikit-learn">
<img src="https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white" alt="pytest">
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker">

</div>

<br>

## Проекты

| Проект | Бизнес-вопрос | Что получилось |
|---|---|---|
| **[Воронка и удержание](https://github.com/kamthiss/product-funnel-retention)**<br><sub>Python · PostgreSQL · Metabase · pytest</sub> | Где теряются пользователи и какие сегменты хуже возвращаются | Онбординг теряет **46%** зарегистрировавшихся, на android на **11 п.п.** больше, чем на ios. Paid_social удерживается в **1,5 раза** хуже organic |
| **[Маржа и возвраты](https://github.com/kamthiss/ecommerce-margin-returns)**<br><sub>PostgreSQL · dbt · Metabase</sub> | Какие категории и каналы приносят прибыль, а какие только оборот | Electronics — **50,6%** продаж и **8%** маржинального дохода. Apparel теряет на возвратах больше всех |
| **[A/B-тест: решение, а не p-value](https://github.com/kamthiss/ab-test-decision)**<br><sub>Python · statsmodels · pytest</sub> | Окупится ли новая страница оформления заказа | Конверсия **+0,91 п.п.**, но даже верхняя граница интервала выручки ниже порога окупаемости. **Не внедрять** |
| **[Пайплайн качества данных](https://github.com/kamthiss/data-quality-pipeline)**<br><sub>Python · PostgreSQL · FastAPI · pytest</sub> | Как поймать некорректно обновлённый отчёт раньше руководителя | **12** блокирующих проверок и **11** сценариев сбоев с заранее известными исходами |
| **[Отток и экономика удержания](https://github.com/kamthiss/churn-retention-economics)**<br><sub>Python · SQL · scikit-learn · pytest</sub> | Кому предлагать скидку, чтобы она окупалась | Окупаемость определяет **сегмент**, а не риск оттока. Модель точнее правила, но прибыли не добавляет, поэтому **не внедряется** |

<br>

<div align="center">
<img src="https://raw.githubusercontent.com/kamthiss/product-funnel-retention/main/dashboard/screenshots/01_overview.png" alt="Дашборд воронки и удержания" width="100%">
<sub>Дашборд проекта «Воронка и удержание» собирается одной командой</sub>
</div>

<br>

## Как устроены проекты

- Определения метрик и правила анализа записаны до работы с данными
- Данные синтетические, с заложенными ответами: видно, находит ли анализ то, что в данных действительно есть
- Ключевые числа сверены независимым расчётом
- Каждый проект собирается с нуля одной командой и проходит свои тесты
- У каждого вывода есть раздел ограничений
