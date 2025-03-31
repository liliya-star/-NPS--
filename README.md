
# 📊 Анализ текущего уровня потребительской лояльности по результатам NPS-опросов

## 📝 Описание
Проект направлен на анализ данных NPS (Net Promoter Score), полученных от клиентов телекоммуникационной компании, работающей на территории СНГ.

## 🎯 Цель
Определить уровень потребительской лояльности среди клиентов из России и проанализировать его в разрезе различных пользовательских признаков.

## 💾 Данные
Опрос проводился по классической шкале от 1 до 10:  
_«Оцените по шкале от 1 до 10 вероятность того, что вы порекомендуете компанию друзьям и знакомым»_  
Данные представлены в формате SQLite.

## 📈 Что делает дашборд
- Отображает текущий уровень NPS
- Показывает распределение NPS по:
  - возрастным группам
  - полу
  - городам
  - другим пользовательским сегментам
- Выявляет отклонения и паттерны в пользовательском опыте

## ⚙️ Используемые технологии
- Python
- pandas, numpy — обработка данных
- SQLite, SQLAlchemy — работа с БД
- plotly, seaborn — визуализация
- Jupyter Notebook / Google Colab — интерфейс анализа и визуализации
