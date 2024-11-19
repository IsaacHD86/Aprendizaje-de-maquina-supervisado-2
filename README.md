# Aprendizaje-de-maquina-supervisado-2
Regresion regularizada: Ridge y Lasso.

# Análisis de Regresión Ridge y Lasso para Predecir Emisiones de CO2

Este proyecto tiene como objetivo aplicar **modelos de regresión Ridge y Lasso** para construir un modelo predictivo que pronostique las emisiones de **CO2** a partir de datos sobre el consumo de combustible y las características de vehículos. Para ello, utilizamos la base de datos proporcionada en el archivo **FuelConsumptionCo2.xlsx**.

## Descripción del Proyecto

El análisis se enfoca en desarrollar modelos de **regresión múltiple** para predecir la variable **"CO2 EMISSIONS"** utilizando las demás variables numéricas del conjunto de datos. Los modelos Ridge y Lasso permiten manejar problemas de **multicolinealidad** y **sobreajuste**, optimizando así la precisión del modelo.

### Objetivos:

1. **Preparación y Limpieza de Datos**:
   - Importar los datos desde **FuelConsumptionCo2.xlsx**.
   - Eliminar columnas categóricas y verificar la existencia de datos nulos.
   
2. **Análisis Exploratorio**:
   - Visualizar la distribución de las variables y su relación con las emisiones de CO2.
   - Generar un análisis de correlación para identificar las variables más influyentes.

3. **Construcción de Modelos de Regresión**:
   - Implementar **Regresión Múltiple**, **Ridge** y **Lasso** para predecir las emisiones de CO2.
   - Evaluar el rendimiento de cada modelo utilizando métricas de bondad de ajuste:
     - Coeficiente de Determinación (**R²**)
     - Error Medio Absoluto (**MAE**)
     - Error Cuadrático Medio (**MSE**)
     - Raíz del Error Cuadrático Medio (**RMSE**)
   
4. **Pronósticos**:
   - Utilizar el modelo ajustado para predecir la emisión de CO2 para la primera observación del conjunto de prueba.
   - Comparar los coeficientes obtenidos entre los modelos Ridge y Lasso para analizar su efecto de regularización.

## Autor
Isaac Heredia Diaz
[GitHub](https://github.com/IsaacHD86)
