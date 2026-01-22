## Descripción del Proyecto

Este proyecto utiliza un modelo de árbol de decisión para predecir si un turista volverá a visitar Cusco. El modelo se entrena con datos de visitantes a sitios arqueológicos como Sacsayhuamán y Machu Picchu, analizando patrones de comportamiento y características demográficas para determinar la probabilidad de reembarque.

## Estructura del Proyecto

```
├── data/                    # Archivos de datos
│   └── *.csv               # Bases de datos de visitantes
├── notebooks/              # Análisis exploratorio
│   └── *.ipynb             # Jupyter Notebooks con pruebas iniciales
├── src/                    # Scripts de producción
│   └── *.py                # Modelos y scripts finales
└── README.md               # Este archivo
```

## Instalación de Dependencias

Para ejecutar este proyecto, instala las librerías necesarias:

```bash
pip install pandas numpy scikit-learn jupyter matplotlib seaborn
```

## Rendimiento del Modelo

El árbol de decisión implementado ha logrado los siguientes resultados:

- **Precisión**: [Completar con resultados reales]
- **Recall**: [Completar con resultados reales]
- **F1-Score**: [Completar con resultados reales]
- **Exactitud General**: [Completar con resultados reales]

## Uso

### Exploración de Datos

Para explorar y analizar los datos, abre los notebooks en la carpeta `notebooks/`:

```bash
jupyter notebook notebooks/
```

### Ejecución del Modelo

Para ejecutar el modelo en producción:

```bash
python src/modelo_prediccion.py
```

## Datos

Los archivos de datos se encuentran en la carpeta `data/` e incluyen registros de:
- Visitantes a Sacsayhuamán
- Visitantes a Machu Picchu
- Características demográficas y de comportamiento

## Autor

Proyecto desarrollado para análisis de Napoleon Arcondo saico
