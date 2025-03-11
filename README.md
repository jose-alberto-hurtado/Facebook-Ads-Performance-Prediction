# 📢 Análisis de Campañas de Facebook Ads y Predicción de Interacciones

## 🌍 Introducción
Facebook Ads es una plataforma clave en la publicidad digital, permitiendo a las marcas llegar a audiencias específicas. Sin embargo, comprender el impacto de las visualizaciones en la generación de "likes" es crucial para optimizar estrategias de marketing.

Este proyecto tiene como objetivo analizar el desempeño de campañas publicitarias en Facebook Ads, explorando la relación entre visualizaciones (views) y likes. Además, se aplican modelos de Machine Learning para predecir la interacción de los usuarios y optimizar futuras campañas.

## 📊 Dataset y Diccionario de Datos
El conjunto de datos contiene información sobre las interacciones de anuncios en Facebook Ads, específicamente la relación entre views (visualizaciones) y likes (me gusta).

### 📂 Datos disponibles en el proyecto:

facebook_ads_data.csv: Contiene información sobre visualizaciones y likes en campañas publicitarias.
Cada columna representa una métrica clave utilizada para el análisis y la predicción de engagement en anuncios de Facebook.

## 📂 Archivos Incluidos
Facebook_Ads_Performance_Prediction.ipynb: Jupyter Notebook con todo el análisis y modelado.
facebook_ads_data.csv: Dataset utilizado para el estudio.
README.md: Documentación del proyecto.

## 🤖 Tecnologías y Herramientas Utilizadas
Python: Lenguaje principal para el análisis.
Pandas: Manipulación y limpieza de datos.
Matplotlib & Seaborn: Visualización de datos.
Scikit-Learn: Modelado de Machine Learning.
XGBoost: Algoritmo avanzado para predicción.
Jupyter Notebook: Desarrollo y documentación del proyecto.

## 🏗️ Estructura del Proyecto
### 1️⃣ Carga y Limpieza de Datos
Importación del dataset y exploración de datos.
Conversión de valores numéricos.
Eliminación de valores nulos y datos inconsistentes.
### 2️⃣ Análisis Exploratorio de Datos (EDA)
Histogramas para entender la distribución de views y likes.
Matriz de correlación para evaluar relaciones entre variables.
### 3️⃣ Creación y Entrenamiento de Modelos
División de datos en entrenamiento y prueba.
Escalado de datos con StandardScaler.
Modelos entrenados:
Random Forest: Modelo base para predicción.
XGBoost: Modelo optimizado para mejorar precisión.
### 4️⃣ Optimización de Modelos
Ajuste de hiperparámetros con GridSearchCV.
Comparación de métricas de rendimiento (MAE, R²).

## 🎨 Visualización de Resultados
###🔎 Principales hallazgos:
Correlación entre views y likes: Se encontró una correlación baja (-0.16), lo que sugiere que otros factores podrían influir en la interacción.
Random Forest vs. XGBoost: Random Forest tuvo mejor desempeño en términos de error absoluto medio (MAE), pero XGBoost podría mejorar con más ajustes.
Optimización con hiperparámetros: Se identificaron valores óptimos para mejorar la predicción.

## 🚀 Conclusiones y Recomendaciones
### ✅ Principales conclusiones:

El número de visualizaciones (views) no siempre se traduce en más likes. Otras métricas como el tiempo de visualización y la segmentación de audiencia pueden influir en la interacción.
Random Forest ofrece mejor rendimiento que XGBoost, aunque este último podría optimizarse con más datos y ajustes.
Las campañas publicitarias pueden mejorarse con segmentación más detallada y ajustes en el contenido visual.
🔹 Recomendaciones para futuros estudios:

Explorar más variables como CTR (Click-Through Rate) y tiempo de visualización.
Probar modelos más avanzados como LightGBM o redes neuronales.
Evaluar diferentes estrategias de segmentación para mejorar el engagement.

## 📑 Reproducir el Análisis
Para ejecutar este análisis en tu entorno local, sigue estos pasos:

### 1️⃣ Clonar este repositorio:

bash
Copiar
Editar
git clone https://github.com/jose-alberto-hurtado/Facebook-Ads-Performance-Prediction.git

### 2️⃣ Instalar dependencias:

bash
Copiar
Editar
pip install pandas matplotlib seaborn scikit-learn xgboost

### 3️⃣ Abrir el archivo Jupyter Notebook:

bash
Copiar
Editar
jupyter notebook Facebook_Ads_Performance_Prediction.ipynb

## 👥 Contacto
📧 Email: josealberto1829@gmail.com
🐍 GitHub: [GitHub](https://github.com/jose-alberto-hurtado)  
💼 LinkedIn: [LinkedIn](https://www.linkedin.com/in/josé-alberto-hurtado-echeverría-77910a319/)

### 🌟 Si te gustó este proyecto, dale una estrella en GitHub! ⭐
