# Clasificador de Géneros Musicales

## Descripción del Proyecto

Este proyecto implementa un modelo de machine learning para clasificar géneros musicales basado en características de audio. Utiliza técnicas de procesamiento de señales y aprendizaje automático para identificar automáticamente el género musical de una canción.

## Objetivos

- 🎵 Extraer características relevantes de archivos de audio
- 🤖 Entrenar modelos de clasificación (CNN, Random Forest, SVM, etc.)
- 📊 Evaluar el rendimiento del modelo
- 🎯 Alcanzar una precisión > 85%

## Tecnologías Utilizadas

- **Python 3.8+**
- **Librosa**: Análisis de audio
- **Scikit-learn**: Modelos de ML
- **TensorFlow / Keras**: Deep Learning
- **Pandas & NumPy**: Procesamiento de datos
- **Matplotlib & Seaborn**: Visualización

## Estructura del Proyecto

```
clasificador-generos-musicales/
├── README.md
├── requirements.txt
├── data/
│   ├── raw/              # Datos sin procesar
│   └── processed/        # Datos preprocesados
├── notebooks/
│   ├── 01_exploracion.ipynb
│   ├── 02_preprocesamiento.ipynb
│   └── 03_entrenamiento.ipynb
├── src/
│   ├── __init__.py
│   ├── audio_processing.py
│   ├── feature_extraction.py
│   ├── model.py
│   └── utils.py
└── results/
    ├── models/           # Modelos entrenados
    ├── plots/            # Gráficos y visualizaciones
    └── metrics.json      # Métricas de evaluación
```

## Conjunto de Datos

- **Fuente**: [GTZAN Genre Collection / FMA / Spotify API]
- **Clases**: [10 géneros musicales principales]
- **Tamaño**: [Especificar número de canciones]

## Características Extraídas

- MFCC (Mel-frequency cepstral coefficients)
- Espectrograma
- Zero Crossing Rate
- Spectral Centroid
- Spectral Rolloff
- Chroma Features

## Modelos Probados

- [ ] Random Forest
- [ ] SVM
- [ ] Neural Network (MLP)
- [ ] CNN (Convolutional Neural Network)
- [ ] XGBoost

## Resultados

| Modelo | Precisión | Recall | F1-Score |
|--------|-----------|--------|----------|
| (Completar) | - | - | - |

## Cómo Usar

### Instalación de Dependencias

```bash
pip install -r requirements.txt
```

### Entrenar el Modelo

```bash
python src/train.py
```

### Hacer Predicciones

```bash
python src/predict.py --audio archivo_musica.mp3
```

## Notebooks

1. **01_exploracion.ipynb**: Análisis exploratorio del dataset
2. **02_preprocesamiento.ipynb**: Extracción de características
3. **03_entrenamiento.ipynb**: Entrenamiento y evaluación de modelos

## Próximos Pasos

- [ ] Aumentar el dataset
- [ ] Optimizar hiperparámetros
- [ ] Implementar validación cruzada
- [ ] Crear API REST para predicciones
- [ ] Desplegar modelo en producción

## Contribuciones

¡Las sugerencias y contribuciones son bienvenidas!

## Autor

jordavy

## Licencia

MIT