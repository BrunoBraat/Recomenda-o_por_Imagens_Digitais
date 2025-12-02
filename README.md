# 🖼️ Sistema de Recomendação por Imagens

Este projeto foi desenvolvido por **Bruno** e implementa um sistema de recomendação que sugere produtos **visualmente semelhantes** com base em suas **características visuais** (formato, cor, textura), utilizando **Deep Learning** e técnicas de **similaridade de embeddings**.

---

## 🎯 Objetivo

Criar um modelo capaz de classificar imagens por similaridade e recomendar produtos relacionados, **sem depender de dados textuais** como marca ou preço — apenas pela **aparência física**.

---

## 🧠 Tecnologias Utilizadas

- **Python**
- **TensorFlow / Keras**
- **OpenCV**
- **scikit-learn** (alternativa ao FAISS)
- **Jupyter Notebook / VS Code**
- **Google Colab** (opcional para GPU gratuita)

---

## 🛠️ Funcionalidades

- Extração de **embeddings visuais** com CNN pré-treinada (ResNet50).
- Cálculo de **similaridade por cosseno**.
- Recomendação de imagens mais próximas visualmente.
- Visualização dos resultados lado a lado.

