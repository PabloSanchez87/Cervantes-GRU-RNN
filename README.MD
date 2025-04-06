# Cervantes-GRU-RNN

Este proyecto entrena una red neuronal recurrente (GRU) para generar texto carácter a carácter, imitando el estilo del Quijote.

El modelo fue entrenado desde cero utilizando únicamente el texto completo del Quijote, cargado desde el Proyecto Gutenberg. La idea no es competir con los grandes modelos actuales, sino comprender cómo una arquitectura sencilla puede aprender patrones estilísticos, de puntuación y cadencia propios de un autor como Cervantes.

### ¿Qué encontrarás aquí?

- Preprocesamiento del texto y tokenización carácter a carácter.
- Implementación de una red GRU con TensorFlow.
- Función de inferencia `OneStep` para generar texto paso a paso.
- Estrategias de muestreo: Greedy Search, Top-k y Beam Search.
- Resultados generados con diferentes configuraciones de temperatura.

### Ejemplo de generación

> En un lugar de las Montañas de León tuvo principio mi linaje, con quien fue más agradecida y liberal la naturaleza que la fortuna...

### Inspirado por

- [The Unreasonable Effectiveness of RNNs – Karpathy](https://karpathy.github.io/2015/05/21/rnn-effectiveness/)  
- [Google Cloud Lab - Text Generation with RNN](https://www.cloudskillsboost.google/course_templates/543)

---

**PD:** No busca ser perfecto, pero sí mostrar que incluso con modelos simples… se pueden lograr resultados sorprendentes 😄
