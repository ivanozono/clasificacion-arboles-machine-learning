# 🌳 Clasificación con Árbol de Decisión y Random Forest

Este proyecto demuestra cómo aplicar modelos de clasificación supervisada utilizando **Árboles de Decisión** y **Random Forest** con el dataset clásico de **Iris**, destacando su valor interpretativo y de predicción.

## 🎯 Objetivo del Proyecto

Predecir la especie de una flor iris a partir de medidas morfológicas utilizando modelos explicables y robustos, útiles para casos reales en distintos sectores.

---

## 🛠️ Tecnologías utilizadas

- Python 3
- Scikit-learn
- Pandas
- Matplotlib / Seaborn
- Joblib

---

## 📊 Flujo del Proyecto

1. **Carga de datos** con el dataset Iris de `sklearn.datasets`.
2. **División de datos** en entrenamiento y prueba.
3. Entrenamiento de un modelo de **Árbol de Decisión**.
4. Entrenamiento de un **Random Forest** con 100 árboles.
5. Evaluación de ambos modelos con métricas (accuracy, F1-score, etc.).
6. **Visualización** del árbol de decisión.
7. Análisis de **importancia de características** en el Random Forest.
8. Guardado y carga del modelo entrenado con `joblib`.

---

## 📁 Estructura del Repositorio
- clasificacion_arbol_random_forest.ipynb
- modelo_random_forest.pkl
- README.md
- requirements.txt

---

## 📌 Resultados clave

- El **Random Forest** obtuvo mayor precisión y generalización que el Árbol de Decisión individual.
- Se identificaron las variables más importantes para la predicción de especies.
- El modelo fue guardado y puede ser desplegado o reutilizado sin reentrenamiento.

---

## 🚀 Cómo ejecutar

1. Clona el repositorio:

```bash
git clone https://github.com/tu_usuario/clasificacion-arboles-machine-learning.git
```
2.	Instala las dependencias:
   ```
pip install -r requirements.txt
```
3.	Abre el notebook:
```
jupyter notebook clasificacion_arbol_random_forest.ipynb
```

📚 Créditos

Este proyecto fue desarrollado en Google Colab como ejercicio demostrativo de clasificación supervisada. Inspirado en buenas prácticas de ciencia de datos aplicadas a problemas reales.

⸻

🔄 Posibles mejoras
	•	Usar validación cruzada y ajuste de hiperparámetros.
	•	Aplicar el modelo a un caso real (churn, fraude, scoring).
	•	Integrar despliegue como microservicio con FastAPI o Streamlit.
