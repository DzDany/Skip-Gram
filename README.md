# Word2Vec - Modelo de Representación de Palabras

Este proyecto implementa un modelo **Word2Vec (Skip-Gram)** utilizando la librería `gensim` en Python.  
El modelo aprende relaciones semánticas entre palabras a partir de un conjunto de oraciones y permite explorar similitudes y contextos.

---

## Características

- Entrena un modelo **Word2Vec Skip-Gram** con ventana de contexto configurable.  
- Permite consultar las **palabras más similares** a una palabra dada.  
- Calcula la **similitud numérica** entre dos palabras.  
- Genera texto automáticamente en función de similitudes aprendidas.  
- Muestra cómo los embeddings representan significados en un espacio vectorial.

---

## Conceptos Clave

- Skip-Gram (sg=1): predice las palabras del contexto a partir de una palabra central.
- Window (window=3): tamaño del contexto (número de palabras vecinas consideradas).
- Embeddings: representación vectorial de palabras en un espacio semántico continuo.
- Similitud coseno: mide qué tan relacionadas están dos palabras.
