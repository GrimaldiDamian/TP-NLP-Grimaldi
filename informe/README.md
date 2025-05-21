# TP-2: Procesamiento de Lenguaje Natural

## Contenido de los ejercicios

### Ejercicio 2
- Fragmentación del texto.
- Vectorización con `SentenceTransformer`.
- Búsqueda semántica por similitud de coseno.

### Ejercicio 3
- Extracción y categorización de sustantivos con spaCy (POS y NER).
- Cálculo de similitud entre sustantivos usando similitud coseno.

### Ejercicio 4
- Detección automática de idioma en archivos usando la librería `langdetect`.

### Ejercicio 5
- Clasificación de comentarios con modelo s-BERT (pipeline Hugging Face).
- Búsqueda semántica según sentimiento con embeddings.

### Ejercicio 6
- Entrenamiento y evaluación de un modelo de regresión logística para clasificación.
- Destaca la velocidad y desempeño del modelo.

---

## Librerías utilizadas

- `scikit-learn`
- `sentence-transformers`
- `pandas`
- `numpy`
- `matplotlib`
- `spacy`
- `torch`
- `re`
- `transformers`
- `nltk`
- `langdetect`

### Instalación de entorno virtual y dependencias

1. **Crear entorno virtual** (recomendado):
    ```bash
    python -m venv ./.venv
    ```

2. **Activar entorno virtual**:
    - En Windows:
      ```bash
      venv\Scripts\activate
      ```
    - En Linux/Mac:
      ```bash
      source venv/bin/activate
      ```

3. **Instalar librerías**:
    ```bash
    pip install scikit-learn sentence-transformers pandas numpy matplotlib spacy torch transformers nltk langdetect
    ```

4. **Descargar modelos adicionales** (ejemplo para spaCy):
    ```bash
    python -m spacy download es_core_news_sm
    ```

---

## Notas
- Se recomienda trabajar siempre dentro del entorno virtual.
- Consultar cada notebook o script para instrucciones específicas de ejecución.