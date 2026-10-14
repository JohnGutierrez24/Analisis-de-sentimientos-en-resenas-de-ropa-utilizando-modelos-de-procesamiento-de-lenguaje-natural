# Proyecto de Análisis de Sentimientos
# 🛍️ Análisis de Sentimientos en Reseñas de Comercio Electrónico
> **Comparativa de modelos de Procesamiento de Lenguaje Natural (NLP) para la evaluación de la opinión del consumidor.**

---

## 📌 Descripción del Proyecto
Este proyecto de ingeniería evalúa y compara el desempeño de distintos modelos de Procesamiento de Lenguaje Natural (NLP) aplicados a reseñas de clientes en la industria del comercio electrónico, enfocándose en el sector textil y de moda. 

A través de la aplicación de la metodología **CRISP-DM**, se analizan desde enfoques tradicionales basados en reglas hasta arquitecturas avanzadas de *Deep Learning* (*Transformers*) para determinar cuál ofrece el mejor balance entre precisión, manejo del contexto y costo computacional.

---

## 🤖 Modelos Evaluados
- **TextBlob:** Enfoque basado en reglas y diccionarios de polaridad para textos formales.
- **VADER:** Algoritmo optimizado para texto corto, modismos e intensificadores en lenguaje coloquial.
- **BERT:** Modelo de *Deep Learning* con contextualización bidireccional para capturar relaciones profundas entre palabras.
- **RoBERTa:** Variante optimizada de BERT entrenada sobre un corpus más amplio para capturar matices complejos del lenguaje con alta precisión.

---

## 📊 Metodología (CRISP-DM)
El desarrollo del proyecto siguió las fases estándar de minería de datos:
1. **Comprensión del Negocio:** Identificar patrones de satisfacción y percepción del consumidor para la toma de decisiones empresariales.
2. **Comprensión de los Datos:** Uso del dataset *Consumer Review of Clothing Product* extraído de Kaggle.
3. **Preparación de los Datos:** Limpieza de texto, tokenización y remoción de *stopwords* (conservando negaciones críticas para el análisis emocional).
4. **Modelado y Evaluación:** Entrenamiento y comparativa de precisión, velocidad y requerimientos computacionales (GPU/CPU).

---

## 📁 Estructura del Repositorio
```text
├── analisis_modelos_PLN.ipynb     # Notebook principal con todo el código y experimentos (Google Colab)
├── Análisis de sentimientos...docx # Informe final y documentación detallada del proyecto
└── README.md                      # Descripción general del repositorio
