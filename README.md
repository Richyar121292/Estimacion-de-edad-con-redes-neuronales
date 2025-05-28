# Estimación-de-edad-con-redes-neuronales  
**Estimación de edad con redes neuronales – Optimización con GridSearchCV**

<h3> 🖼️ Predicción de Edad a partir de Imágenes </h3>  

Estimación de edad con Deep Learning basada en **ResNet50**, logrando un **MAE de 4.11** en la predicción.  
<br>

<h3> 📝 Descripción </h3>  

Este proyecto implementa un modelo de aprendizaje profundo para **predecir la edad de personas a partir de imágenes**. Se utiliza **ResNet50** como arquitectura base para el procesamiento y entrenamiento en un conjunto de **7,651 imágenes**.  

El modelo muestra una progresión positiva en el entrenamiento y validación, alcanzando un **Error Absoluto Medio (MAE) de 4.11**, optimizado mediante ajuste de hiperparámetros con **GridSearchCV**.  
<br> 

<h3> 📂 Estructura del Proyecto </h3>  

📁 `Prediccion-Edad-Imagenes`  
├── 📄 `README.md` → Documentación general  
├── 📁 `data/` → Datos y etiquetas de imágenes  
├── 📁 `notebooks/` → Análisis exploratorio, limpieza y preparación de datos  
├── 📁 `models/` → Modelos entrenados y resultados  
├── 📄 `requirements.txt` → Dependencias necesarias  
├── 📄 `main.py` → Script principal para ejecución  
<br>

<h3> 🛠️ Tecnologías Utilizadas </h3>  

✔️ **Lenguaje** → Python (Pandas, NumPy)  
✔️ **Visualización** → Matplotlib, Seaborn, Plotly  
✔️ **Deep Learning** → TensorFlow, Keras, ResNet50  
✔️ **Procesamiento de Imágenes** → PIL, ImageDataGenerator  
<br>

<h3> 🚀 Instalación </h3> 

1. Clona el repositorio: git clone https://github.com/Richyar121292/Estimacion-de-edad-con-redes-nauronales.git  
2. Instala las dependencias: pip install -r requirements.txt  
3. Ejecuta el script principal: python main.py  
<br>

<h3> 📈 Resultados </h3>

📌 Modelo basado en ResNet50  
📌 Entrenamiento con 7,651 imágenes en GPU  
📌 MAE mínimo alcanzado: 4.11  
📌 Tiempo total de entrenamiento: 89 minutos  
<br>

<h3> 📌 Contribuciones </h3>

Si deseas mejorar el modelo o agregar nuevas funcionalidades, abre un Issue o envía un Pull Request.  
🖥️ Equipo utilizado: NVIDIA GTX GeForce 1650