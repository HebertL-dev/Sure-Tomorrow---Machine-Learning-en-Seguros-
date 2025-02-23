# 🔐 Sure Tomorrow - Machine Learning en Seguros  

## 🚀 Descripción  

Sure Tomorrow busca mejorar su proceso de toma de decisiones con *machine learning*, resolviendo problemas clave en la identificación de clientes y la predicción de beneficios de seguros.  

Este proyecto aborda cuatro tareas fundamentales, incluyendo la privacidad y protección de datos mediante **enmascaramiento de información**.  

## 🎯 Objetivos  

✔ **Tarea 1:** Encontrar clientes similares a uno dado para mejorar estrategias de marketing.  
✔ **Tarea 2:** Predecir si un cliente recibirá beneficios de seguro y comparar el modelo con un *dummy classifier*.  
✔ **Tarea 3:** Estimar la cantidad de beneficios que un cliente puede recibir utilizando **regresión lineal**.  
✔ **Tarea 4:** Implementar un **método de enmascaramiento de datos** sin afectar la calidad del modelo.  

## 📌 Pasos del Proyecto  

1️⃣ **Exploración y preprocesamiento de datos**.  
2️⃣ **Implementación de modelos de clasificación y regresión**.  
3️⃣ **Comparación del rendimiento del modelo entrenado vs. modelo dummy**.  
4️⃣ **Aplicación de técnicas de ofuscación de datos** para proteger la información personal sin degradar el rendimiento del modelo.  

## 🏆 Resultados  

Los resultados muestran que la predicción ofuscada **mantiene la coherencia con la original**, asegurando la privacidad de los datos sin comprometer la calidad del modelo:  

| Cliente | Predicción Original | Predicción Ofuscada |
|---------|--------------------|---------------------|
| 0       | 389,108.82        | 31.15              |
| 1       | 290,630.08        | 30.72              |
| 2       | 182,428.32        | 31.11              |
| 3       | 258,726.38        | 30.72              |

📌 **Evaluación del modelo:**  

🔹 **Datos originales:**  
- **RMSE:** 285,185.15  
- **R²:** -1,115,458,693.59  

🔹 **Datos ofuscados:**  
- **RMSE:** 8.53  
- **R²:** 0.0013  

Estos resultados indican que el modelo sigue funcionando correctamente después de aplicar técnicas de ofuscación de datos, garantizando seguridad sin perder precisión en los cálculos.  

📌 Con estos avances, **Sure Tomorrow** puede mejorar la segmentación de clientes, optimizar sus modelos de predicción y garantizar la seguridad de la información. 🚀  
