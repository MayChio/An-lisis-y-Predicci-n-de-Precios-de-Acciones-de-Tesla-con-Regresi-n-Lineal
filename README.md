Análisis y Predicción de Precios de Acciones de Tesla con Regresión Lineal
Descripción del Proyecto
Este proyecto utiliza técnicas de análisis de datos y aprendizaje automático para explorar y predecir los precios históricos de las acciones de Tesla. Empleamos un modelo de regresión lineal para realizar predicciones basadas en características financieras clave, como precios de apertura, cierre y volumen de transacciones.

Estructura del Proyecto
Tesla.ipynb: El archivo principal del proyecto, que contiene el análisis y el código paso a paso.
Datos: Los datos históricos de las acciones de Tesla fueron extraídos del archivo Tesla.csv.
.gitignore: Archivos y carpetas ignorados (por ejemplo, entornos virtuales como env/).
Funcionalidades
Carga y Limpieza de Datos:

Se importaron datos históricos de acciones de Tesla desde un archivo CSV.
Se limpiaron y procesaron datos faltantes.
Análisis Exploratorio:

Estadísticas descriptivas de las características principales.
Análisis de correlación para identificar relaciones entre variables.
Modelado Predictivo:

Entrenamiento de un modelo de regresión lineal para predecir precios de cierre de acciones.
Evaluación del modelo utilizando métricas como MSE y RMSE.
Visualización:

Gráficos que muestran patrones históricos y predicciones del modelo.
Requisitos del Proyecto
Este proyecto utiliza Python y las siguientes bibliotecas:

pandas
numpy
matplotlib
seaborn
scikit-learn
Para instalar estas dependencias, puedes usar el archivo requirements.txt o ejecutarlas directamente en tu entorno virtual con:

bash
Copiar
Editar
pip install pandas numpy matplotlib seaborn scikit-learn
Resultados
Métricas del Modelo:
MSE (Mean Squared Error): 2.35
RMSE (Root Mean Squared Error): 1.53
Las predicciones del modelo coinciden razonablemente bien con los precios reales en un conjunto de datos de prueba.
Visualizaciones
Se incluyen gráficos clave para entender los datos y las predicciones del modelo, como:

Series temporales de precios de las acciones.
Matriz de correlación de las variables.
Comparación entre precios reales y predichos.
Cómo Ejecutar el Proyecto
Clonar este repositorio:
bash
Copiar
Editar
git clone https://github.com/MayChio/An-lisis-y-Predicci-n-de-Precios-de-Acciones-de-Tesla-con-Regresi-n-Lineal.git
Acceder al entorno virtual:
bash
Copiar
Editar
cd An-lisis-y-Predicci-n-de-Precios-de-Acciones-de-Tesla-con-Regresi-n-Lineal
python -m venv env
source env/bin/activate  # En Windows: env\Scripts\activate
Instalar dependencias:
bash
Copiar
Editar
pip install -r requirements.txt
Ejecutar el archivo Tesla.ipynb en Jupyter Notebook o VS Code.
Contribuciones
¡Las contribuciones son bienvenidas! Si deseas colaborar, siéntete libre de abrir un issue o enviar un pull request.

Contacto
Si tienes alguna pregunta sobre este proyecto, no dudes en contactarme:

GitHub: MayChio

