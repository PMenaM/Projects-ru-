# Портфолио проектов Pablo Mena
Список проектов, выполненных в области Data Science и ее различных подобластях.

| Область проекта/год | Название проекта | Описание | Вклад | Стек и методы |        
| --- | --- | --- | --- | --- |                
|     |     |     |     | Предложения CASE (WHEN, THEN), Агрегатные функции (EXTRACT, SUM, ROUND), Предложения фильтрации (WHERE, GROUP BY, ORDER BY) |
| Machine Learning/2023 | [Assessing Customer Churn Using Machine Learning](https://github.com/PMenaM/Projects/blob/main/Assessing%20Customer%20Churn%20Using%20Machine%20Learning%20(Jupyter%20Notebook)/Assessing%20Customer%20Churn%20Using%20Machine%20Learning%20(Jupyter%20Notebook).ipynb) | Использование Pandas и машинного обучения для изучения наборов данных ведущих индийских телекоммуникационных компаний, выявления демографических моделей и моделей использования. Прогнозирование удержания клиентов, объединение анализа данных и прогнозного моделирования. |  | Pandas, Sklearn, машинное обучение, анализ данных, предварительная обработка, создание экземпляров, StandardScaler, обучение, подгонка, train_test_split, проверка, прогнозирование, LogisticRegression, RandomForestClassifier, оценка, classification_report, confusion_matrix |
| AI - Prompt Engineering/2023 | [OpenAI API for Tourism](https://github.com/PMenaM/Projects/blob/main/OpenAI%20API%20for%20Tourism%20(Jupyter%20Notebook)/Planning%20a%20Trip%20to%20Paris%20with%20the%20OpenAI%20API.ipynb) | Использование возможностей языковой обработки OpenAI для интеллектуального ответа на заранее заданные вопросы, связанные с поездками, и предоставления индивидуальных рекомендаций для знакомства с Парижем. |  | Искусственный Интеллект, OpenAI API, Prompt engineering, циклы for, извлечение признаков, списки словарей |
| Computer Vision/2023 | [Sign Language Recognition with Keras](https://github.com/PMenaM/Projects/blob/main/Sign%20Language%20Recognition%20with%20Keras%20(Jupyter%20notebook)/Sign%20Language%20Recognition%20with%20Keras%20(Jupyter%20notebook).ipynb) | Построение сверточной нейронной сети (CNN) для классификации изображений букв американского языка жестов (ASL). После загрузки, проверки и предварительной обработки данных сеть обучается, и ее производительность проверяется на соответствие ее точности при предсказании букв ASL из изображений. |  | Классификация изображений, Tensorflow/Keras, Numpy (argmax, where), Matplotlib, Convolutional Neural Networks (CNN), Conv2D, MaxPooling2D, Flatten, Dense, Sequential, compile, to_categorical, fit, evaluate, predict |
| NLP/2023 | [Topic Trend Analysis](https://github.com/PMenaM/Projects/blob/main/Topic%20Trend%20Analysis%20(Jupyter%20notebook)/Topic%20Trend%20Analysis%20(Jupyter%20notebook).ipynb) | Использование методов обнаружения темы NLP в коллекции исследовательских работ с конференций Neural Information Processing Systems (NIPS) за 10 лет. Цель этого проекта — выяснить, какие темы стали более модными, учитывая рост популярности машинного обучения. |  | Обнаружение темы, Pandas, Numpy, Matplotlib, data pre-processing, Гистограмма, Регулярное выражение (regex), WordCloud, CountVectorizer, Латентное Размещение Дирихле (LDA) |
| NLP/2023 | [Tweet Classifier](https://github.com/PMenaM/Projects/blob/main/Tweet%20Classifier%20(Jupyter%20notebook)/Tweet%20Classifier%20(Jupyter%20notebook).ipynb) | Построение ML модели классификации с использованием методов NLP для классификации и анализа текста. Данные, которые необходимо классифицировать, соответствуют твитам, написанным двумя американскими политиками. Цель модели — точно классифицировать, был ли твит написан одним политиком или другим, на основе содержания твита. |  | Numpy, CountVectorizer, TfidfVectorizer, train_test_split, MultinomialNB, LinearSVC, sklearn_metrics, confusion_matrix |
| SQL/2023 |  |  |  | Агрегатные функции (SUM, COUNT, MAX), Предложения CASE (WHEN, THEN), Сопоставление с образцом (LIKE), Операции соединения (INNER JOIN), Предложения фильтрации (WHEN, HAVING), Оконные функции (RANK, OVER), Подзапросы, CTE, Набор операций (EXCEPT, INTERSECT) |
| SQL/2023 |  |  |  | Агрегатные функции (COUNT, SUM, corr, TRUNC, LENGTH, ROUND, AVG), Операции соединения (INNER JOIN), Предложения CASE (WHEN, THEN), Предложения фильтрации (HAVING, WHERE, GROUP BY, ORDER BY, DATE_PART), Подзапросы, CTE |
| Computer Vision/2023 | [YOLOv8 Детектор Людей](https://github.com/PMenaM/Projects-ru-/blob/main/YOLOv8%20%D0%94%D0%B5%D1%82%D0%B5%D0%BA%D1%82%D0%BE%D1%80%20%D0%9B%D1%8E%D0%B4%D0%B5%D0%B9%20(Jupyter%20Notebook)/YOLOv8%20%D0%94%D0%B5%D1%82%D0%B5%D0%BA%D1%82%D0%BE%D1%80%20%D0%9B%D1%8E%D0%B4%D0%B5%D0%B9%20(Jupyter%20Notebook).ipynb) | Система обнаружения объектов на основе алгоритма YOLO. Модель обучалась на датасета, состоящем из снимков, сделанных дроном. На изображениях показан лесной ландшафт с возможным присутствием людей, которые будут обнаружены моделью. Достигнута точность 75-80%. | Определены функции для сравнения и сортировки изображений и файлов аннотаций в отдельные папки. Определена функция извлечения индексов файлов из списков и перемещения их в определенные папки. Определен ряд функций для преобразования файлов формата xml в txt и yaml. Определена функция для тестирования файлов изображений и сохранения их в определенной папке. Выполнено обнаружение объектов на серии изображений с разным фоном. | Pytorch, OpenCV, ultralytics, YOLOv8, предварительная обработка данных, манипуляция данными, обучение, тестирование, Numpy, glob, os, re, shutil, yaml, pickle, xml.etree |
| NLP/2022 | [Рекомендации к Книгам Чарльза Дарвина](https://github.com/PMenaM/Projects-ru-/blob/main/%D0%A0%D0%B5%D0%BA%D0%BE%D0%BC%D0%B5%D0%BD%D0%B4%D0%B0%D1%86%D0%B8%D0%B8%20%D0%BA%20%D0%9A%D0%BD%D0%B8%D0%B3%D0%B0%D0%BC%20%D0%A7%D0%B0%D1%80%D0%BB%D1%8C%D0%B7%D0%B0%20%D0%94%D0%B0%D1%80%D0%B2%D0%B8%D0%BD%D0%B0%20(Jupyter%20Notebook)/%D0%A0%D0%B5%D0%BA%D0%BE%D0%BC%D0%B5%D0%BD%D0%B4%D0%B0%D1%86%D0%B8%D0%B8%20%D0%BA%20%D0%9A%D0%BD%D0%B8%D0%B3%D0%B0%D0%BC%20%D0%A7%D0%B0%D1%80%D0%BB%D1%8C%D0%B7%D0%B0%20%D0%94%D0%B0%D1%80%D0%B2%D0%B8%D0%BD%D0%B0%20(Jupyter%20Notebook).ipynb) | Система NLP для рекомендации книг на основе содержания. Использует библиографию Чарльза Дарвина, чтобы выяснить, какие книги могут представлять интерес на основе сходства с *О Происхождении Видов*. Окончательная дендрограмма отражает современный механизм рекомендаций. | Выполнен поиск по индексу, чтобы найти целевой текст. Использованы списки для токенизации и удаления стоп-слов. Выполнил стемминг корпуса и построил модель «мешка слов». Преобразовал результат модели в DataFrame, добавив столбцы для числа, индекса и токена. Построил модель tf-idf для генерации векторов и их сортировки. (3-9 шаги проекта) | Pandas, Tfidf, Matplotlib, Gensim, SciPy, glob, re, os, pickle |
| NLP/2022 | [Поиск Сходства Фильмов по Краткому Изложению Сюжета](https://github.com/PMenaM/Projects-ru-/tree/main/%D0%9F%D0%BE%D0%B8%D1%81%D0%BA%20%D0%A1%D1%85%D0%BE%D0%B4%D1%81%D1%82%D0%B2%D0%B0%20%D0%A4%D0%B8%D0%BB%D1%8C%D0%BC%D0%BE%D0%B2%20%D0%BF%D0%BE%20%D0%9A%D1%80%D0%B0%D1%82%D0%BA%D0%BE%D0%BC%D1%83%20%D0%98%D0%B7%D0%BB%D0%BE%D0%B6%D0%B5%D0%BD%D0%B8%D1%8E%20%D0%A1%D1%8E%D0%B6%D0%B5%D1%82%D0%B0%20(Jupyter%20Notebook)) | Система кластеризации NLP, которая количественно определяет сходство фильмов на основе сводок сюжетов, доступных на IMDb и Википедии. Окончательная дендрограмма отражает современный механизм рекомендаций. | Создан отфильтрованный объект токенизатора на основе спискового включения. Использовал алгоритм Snowball Stemmer для объединения слов со схожими семантическими значениями. Определила функцию, которая включает в себя два предыдущих шага, экономя 50% времени кодирования и времени обработки. Определил объект TfidfVectorizer и использовал его метод fit-transform для преобразования текста в числовые векторы и удаления английских стоп-слов. (3-7 шаги проекта) | NLTK, TfidfVectorizer, KMeans, cosine_similarity, Numpy, Pandas, Matplotlib, SciPy, linkage, dendrogram, BeautifulSoup, requests, re |


# Ссылки на резюме
  + [резюме](https://spb.hh.ru/resume/88b9b46cff0bfd0f880039ed1f7a7076507353)
  + [профиль на LinkedIn (на английском языке)](https://www.linkedin.com/in/pablomenamnlp)
