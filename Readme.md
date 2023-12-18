# Proyecto de Análisis de Datos Inmobiliarios en Nueva York

## Descripción
Este proyecto utiliza datos de ventas inmobiliarias en Nueva York para realizar análisis y predicciones. Incluye limpieza de datos, entrenamiento de modelos de regresión y evaluación del rendimiento de los modelos.

## Instrucciones de Uso
1. Clona este repositorio en tu máquina local.
2. Asegúrate de tener todas las bibliotecas necesarias instaladas. Puedes hacerlo ejecutando `pip install -r requirements.txt`.
3. Ejecuta el script principal `main.py` para cargar y procesar los datos, entrenar los modelos y evaluar el rendimiento.

## Estructura del Proyecto
- `data`: Carpeta que contiene el conjunto de datos (`nyc-rolling-sales.csv`).
- `src`: Código fuente del proyecto.
  - `main.py`: Script principal que ejecuta el análisis de datos y entrenamiento de modelos.
  - `utils.py`: Módulo con funciones de utilidad.
- `requirements.txt`: Archivo con las bibliotecas y versiones necesarias.

## Resultados
El proyecto utiliza diferentes modelos de regresión, incluyendo Support Vector Regression (SVR), RANSAC, y Huber Regression. Los resultados se evalúan utilizando el Mean Squared Error (MSE).

## Requisitos
- Python 3.x
- Bibliotecas de Python: pandas, scikit-learn, etc. (ver `requirements.txt`)

## Contribuciones
Las contribuciones son bienvenidas. Si deseas mejorar el código, agregar nuevas características o informar problemas, por favor crea un _issue_ o envía una solicitud de _pull_.

## Licencia
Este proyecto está bajo la Licencia MIT. Consulta el archivo `LICENSE` para obtener más detalles.

---
**Nota:** Asegúrate de tener los datos necesarios antes de ejecutar el código. Puedes descargar el conjunto de datos de [aquí](enlace-al-conjunto-de-datos).
