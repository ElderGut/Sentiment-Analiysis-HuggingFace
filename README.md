# Sentiment-Analiysis-HuggingFace
comparación de modelos preentrenados de HuggingFace para analisis de sentimientos

Descripcion del proyecto:
Este proyecto compara el desempeño de tres modelos preentrenados de Hugging face para una tarea de analisis de sentimientos, utilizando tecnicas de NLP. el objetivo es evaluar su precision, eficiencia y tiempo de inferencia  para determinar cual ofrece mejor equilibrio.

Modelos evaluados: 
    DistilBERT SST-2
    BERT SST-2
    RoBERTa Twitter

Entorno de ejecucion
    Google Colab
    Python 3.x
    Transformers
    Datasets
    PyTorch
    Scikit-learn
    Pandas
    Matplotlib

Pasos de ejecucion
    Instalar las dependencias del proyecto.
    Autenticarse en Hugging Face Hub.
    Cargar el dataset y los modelos preentrenados.
    Ejecutar el pipeline de inferencia.
    Calcular accuracy, precision, recall y F1-score.
    Medir la latencia promedio.
    Comparar resultados mediante tablas y gráficas.

Conclusiones:
El mejor modelo, con el mayor equilibrio en general, fue el modelo BERT SST-2. DistilBERT destacó por su menor latencia y eficiencia computacional, mientras que RoBERTa Twitter mostró un desempeño inferior en este conjunto de datos. La elección del modelo depende del equilibrio deseado entre precisión y velocidad de inferencia.
