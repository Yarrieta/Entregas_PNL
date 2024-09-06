![image](https://github.com/user-attachments/assets/721962a0-6174-427d-95f5-d5e05abdc3be)

# Entregas_PNL

El presente repositorio contiene 5 desafíos de machine learning resueltos con algoritmos de procesamiemto del lenguaje natural en los idiomas español e inglés.

### Desafío 1
Se trabajó con los vectorizadores de texto TfidfVectorizer y CountVectorizer para luego aplicar el modelo de clasificación Naïve Bayes en las versiones MultinomialNB, ComplementNB con el dataset 20 newsgroups. Enlace al desafio: https://github.com/Yarrieta/Entregas_PNL/blob/Desafio1/Desafio_1.ipynb

### Desafío 2
Se trabajó con la creación de embeddings con Gensim en el contexto del libro Orgullo y prejuicio de Jane Austen. Enlace al desafio: https://github.com/Yarrieta/Entregas_PNL/blob/Desafio2/2c_Custom_embedding_con_Gensim.ipynb

### Desafío 3
Se trabajó en la creación de dos modelos de lenguaje con tokenización por carácteres con las arquitecturas SimpleRNN y GRU: https://github.com/Yarrieta/Entregas_PNL/blob/Desafio3/3_modelo_lenguaje_char.ipynb. Así como se trabajó con las arquitecturas LSTM sin capa bidireccional y LSTM con capa bidireccional: https://github.com/Yarrieta/Entregas_PNL/blob/Desafio3/desafio3_modelo_lenguaje_word.ipynb. Ambos modelos permiten generar nuevas secuencias a partir de secuencias de contexto con las estrategias de greedy search y beam search determístico y estocástico. 

### Desafío 4
Se trabajó el la creación de un BOT para responder a las preguntas del usuario. Para el modelo de hizo uso de los embeddings de glove, se crearon dos capas LSTM para el encoder y el decoder, así como una capa de salida densa. Enlace al desafio: https://github.com/Yarrieta/Entregas_PNL/blob/Desafio4/6_bot_qa.ipynb

### Desafío 5
Se trabajó con el modelo transformer de BERT base, al cual se le añadió dos capas densas. A partir de este modelo base se realizó fine tuning. Se predijo la clase en base al texto proporsionado como input para ambos modelos, con el fin de realizar la clasificación de las 5 clases de los sentimientos. Para el entrenamiento se usó el dataset reviews.csv. Enlace al desafio: https://github.com/Yarrieta/Entregas_PNL/blob/Desafio5/7d_bert_sentiment_analysis_multicategorial1.ipynb
