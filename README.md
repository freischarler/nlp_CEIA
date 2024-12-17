# Desafíos de Inteligencia Artificial - UBA

Este repositorio contiene el desarrollo de **cuatro desafíos** enfocados en procesamiento de lenguaje natural (NLP) y aprendizaje automático, como parte de la Especialización en Inteligencia Artificial en la UBA.

---

## Desafío 1: Vectorización y Clasificación de Documentos

- **Objetivo**: Analizar la similaridad entre documentos y palabras utilizando técnicas de vectorización.  
- **Resumen**:
  - Medir la **similaridad** entre documentos seleccionados y evaluar la coherencia en relación al contenido y etiquetas de clasificación.
  - Entrenar y optimizar modelos de clasificación **Naïve Bayes** (Multinomial y ComplementNB) maximizando el desempeño (F1-score macro).
  - Analizar la **similaridad entre palabras** a partir de una matriz término-documento transpuesta.

---

## Desafío 2: Creación de Word Embeddings con Canciones

- **Objetivo**: Generar embeddings de palabras utilizando el contexto de la biblia.  
- **Resumen**:
  - Utilizar el corpus de todo el texto de la biblia para entrenar modelos que representen las palabras como vectores.
  - Capturar el lenguaje en la biblia para analizar patrones contextuales.

---

## Desafío 3: Modelado de Lenguaje con Redes Recurrentes

- **Objetivo**: Implementar modelos de lenguaje basados en redes neuronales recurrentes para generar nuevas secuencias de texto.  
- **Resumen**:
  - Seleccionar y preprocesar un **corpus** de texto, estructurar datasets y dividir en entrenamiento/validación.
  - Implementar modelos **SimpleRNN**, **LSTM** y **GRU**.
  - Generar texto utilizando estrategias de **Greedy Search** y **Beam Search**.
  - Evaluar el efecto de la **temperatura** en la generación de texto.

---

## Desafío 4: Construcción de un Chatbot Conversacional

- **Objetivo**: Crear un chatbot capaz de responder preguntas de usuario utilizando datos del **ConvAI2** (Conversational Intelligence Challenge 2).  
- **Resumen**:
  - Preprocesar el dataset de conversaciones en inglés.
  - Implementar un modelo **QA** basado en secuencias para generar respuestas coherentes a preguntas del usuario.  
  - Dataset: [ConvAI2 Challenge](http://convai.io/data/)

---

## Instalación y Ejecución

1. **Clonar el repositorio**:
   ```bash
   git clone https://github.com/freischarler/nlp_CEIA.git

