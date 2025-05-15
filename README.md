# 🛡️ Predicción y Segmentación de Clientes – Sure Tomorrow

La compañía de seguros **Sure Tomorrow** busca aplicar técnicas de ciencia de datos para:

- Analizar el comportamiento de sus clientes.  
- Agrupar clientes con características similares.  
- Predecir el número de prestaciones de seguro que un cliente podría recibir.  
- Evaluar cómo el preprocesamiento (escalado de datos) influye en el rendimiento de los modelos.

## 🔍 Procesos

1. **Importación de Datos**  
   - Lectura del dataset original con `pandas`.

2. **Preprocesamiento y Exploración**  
   - Detección y tratamiento de valores nulos y duplicados.  
   - Verificación y conversión de tipos de dato.

3. **Segmentación con KMeans**  
   - Aplicación del algoritmo KMeans para identificar grupos de clientes.  
   - Análisis de la coherencia y separación de clústeres.

4. **Modelado de Regresión Lineal**  
   - Entrenamiento de un modelo de regresión lineal para estimar la cantidad de prestaciones.  
   - Cálculo del RMSE como métrica de error.

5. **Análisis del Escalado**  
   - Escalado de las variables numéricas con `MaxAbsScaler`.  
   - Comparativa del error (RMSE) del modelo con y sin escalado de datos.

## 🧰 Requisitos del Entorno
- Python 3.8 o superior
- pandas
- numpy
- scikit-learn
- matplotlib

seaborn
## 🚀 Cómo Clonar el Repositorio

```bash
git clone https://github.com/dsc530/Seguros.git

