# Содержание
Задания выполненные в ходе обучения NLP в OTUS


| **Название проекта**  | **Описание**           | **Используемые библиотеки** |
| :-------------------- | :--------------------- |:----------------------------|
| [Откуда беруться датасеты](https://github.com/karasevdy/OTUS_NLP/tree/main/parser) | Спарсить сайт, содержащий тексты и оценки. Провести предобработку и EDA. | *requests, beautifulsoup4, fake_useragent, selenium, webdriver-manager, pandas, numpy, re, random, time, tqdm, matplotlib, seaborn, wordcloud, sklearn, collections, natasha* |
| [Практика Py-Torch](https://github.com/karasevdy/OTUS_NLP/tree/main/pytorch) | Написать нейросеть, апроксимирующую синусоидальную функцию. Прогнозы визуализировать. | *torch, numpy, math, copy, matplotlib* |
| [Тематическое моделирование корпуса текстов](https://github.com/karasevdy/OTUS_NLP/tree/main/LDA) | Загрузка тестов новойстей (РИА Новости из корпуса Тайга) в оперативную память. Предобработка текстов. Выявление оптимального количества основных тем, визуализация распределения тем в корпусе и ключевых слов в темах. | *nltk, gensim, pymorphy2, re, os, pickle, collections, pandas, numpy, matplotlib, wordcloud* |
| [Что в векторе твоем?](https://github.com/karasevdy/OTUS_NLP/tree/main/w2v_embeddings) | Получить средние векторы спарсенных текстов, используя word2vec/fasttext векторизацию c весами tf-idf. На полученных эмбеддингах спрогнозировать оценки текстов градиентным бустингом. | *nltk, gensim, natasha, pyaspeller, re, collections, pandas, numpy, sklearn, lightgbm, catboost* |
| [Почувствуй мощь трансформеров в бою](https://github.com/karasevdy/OTUS_NLP/tree/main/RAG) | Зафайнтюнить RuBert, RuRoBerta, T5 на задачу классификации приемлемости предложений на датасете RuCola. Файнтюнинг выполнить на GPU. | *transformers, torch, sklearn, datasets, accelerate, pandas, numpy* |
| [RAG для вопросно-ответной системы](https://github.com/karasevdy/OTUS_NLP/tree/main/RAG) | Подоготовить ретривер для вопросно-ответной системы связанный с YandexGPY на основе библиотеки LangChain. Подгрузить произвольную базу знаний и задать вопрос по ней. | *langchain, YandexGPY, datasets, dotenv, pypdf, pandas, os* |
