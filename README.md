# Proyecto de Análisis de Sentimientos
# 🛍️ Análisis de Sentimientos en Reseñas de Comercio Electrónico
> **Comparativa de modelos de Procesamiento de Lenguaje Natural (NLP) para la evaluación de la opinión del consumidor.**

---

## 📌 Descripción del Proyecto
Este proyecto de ingeniería evalúa y compara el desempeño de distintos modelos de Procesamiento de Lenguaje Natural (NLP) aplicados a reseñas de clientes en la industria del comercio electrónico, enfocándose en el sector textil y de moda. 

A través de la aplicación de la metodología **CRISP-DM**, se analizan desde enfoques tradicionales basados en reglas hasta arquitecturas avanzadas de *Deep Learning* (*Transformers*) para determinar cuál ofrece el mejor balance entre precisión, manejo del contexto y costo computacional.

---

## 🤖 Modelos Evaluados
- **TextBlob:** Enfoque basado en reglas y diccionarios de polaridad para textos formales[cite: 2].
- **VADER:** Algoritmo optimizado para texto corto, modismos e intensificadores en lenguaje coloquial[cite: 2].
- **BERT:** Modelo de *Deep Learning* con contextualización bidireccional para capturar relaciones profundas entre palabras[cite: 2, 3].
- **RoBERTa:** Variante optimizada de BERT entrenada sobre un corpus más amplio para capturar matices complejos del lenguaje con alta precisión[cite: 2, 3].

---

## 📊 Metodología (CRISP-DM)
El desarrollo del proyecto siguió las fases estándar de minería de datos[cite: 4]:
1. **Comprensión del Negocio:** Identificar patrones de satisfacción y percepción del consumidor para la toma de decisiones empresariales[cite: 4].
2. **Comprensión de los Datos:** Uso del dataset *Consumer Review of Clothing Product* extraído de Kaggle[cite: 4].
3. **Preparación de los Datos:** Limpieza de texto, tokenización y remoción de *stopwords* (conservando negaciones críticas para el análisis emocional)[cite: 4].
4. **Modelado y Evaluación:** Entrenamiento y comparativa de precisión, velocidad y requerimientos computacionales (GPU/CPU)[cite: 3].

---

## 📁 Estructura del Repositorio
```text
├── analisis_modelos_PLN.ipynb     # Notebook principal con todo el código y experimentos (Google Colab)
├── Análisis de sentimientos...docx # Informe final y documentación detallada del proyecto
└── README.md                      # Descripción general del repositorio
