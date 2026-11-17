# Machine Learning Labs (SPbGETU LETI)

Коллекция учебных проектов по машинному обучению, охватывающая ключевые этапы ML-пайплайна — от предобработки данных до оптимизации эвристическими методами.

Каждая работа содержит:
- **Jupyter Notebook** с кодом, комментариями и визуализациями
- **PDF-отчёт** с постановкой задачи, описанием методов и анализом результатов

---

## Структура репозитория

| № | Тема | Методы | Отчёт |
|---|------|--------|-------|
| 1 | **[lb1](./lb1/)** — Подготовка данных | Очистка, EDA, Feature Engineering | [PDF](./lb1/report.pdf) |
| 2 | **[lb2](./lb2/)** — Регрессия | Linear Regression, Ridge/Lasso, Polynomial | [PDF](./lb2/report.pdf) |
| 3 | **[lb3](./lb3/)** — Классификация | kNN, Logistic Regression, SVM, Decision Trees | [PDF](./lb_3/report.pdf) |
| 4 | **[lb4](./lb4/)** — Кластеризация | K-Means, DBSCAN, Hierarchical Clustering | [PDF](./lb4/report.pdf) |
| 5 | **[lb5](./lb5/)** — Генетические алгоритмы | Эвристическая оптимизация | [PDF](./lb5/report.pdf) |

---

## Стек технологий

- **Язык:** Python 3.11
- **Обработка данных:** `Pandas`, `NumPy`
- **ML-библиотеки:** `Scikit-learn`
- **Визуализация:** `Matplotlib`, `Seaborn`
- **Среда:** Jupyter Notebook

---

## Установка и запуск

1. Клонируйте репозиторий:
   ```bash
   git clone https://github.com/samoilova-em/machine-learning-labs-leti.git
   cd machine-learning-labs-leti

2. Установка зависимостей:
    ```bash
    pip install -r requirements.txt
    ```

3. Запуск нужной лабораторной работы
    ```bash
    jupyter notebook lb_1/notebook.ipynb
    ```