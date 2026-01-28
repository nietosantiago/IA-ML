# 🤖 IA & Machine Learning  
## Trabajo Práctico 2 – Aprendizaje Supervisado

📘 **Certificación Avanzada en Ciencia de Datos**  
🏫 **ITBA**  
👤 **Autor:** Santiago Nieto  
📅 **Año:** 2025  

---

## 📊 Descripción del Trabajo
Este trabajo práctico aborda conceptos de **aprendizaje supervisado**, combinando una instancia teórica
con un ejercicio práctico de **regresión** sobre un dataset real.

El foco está puesto en la correcta **partición de datos**, el análisis exploratorio previo
y la importancia de evaluar modelos antes de su aplicación.

---

## 🧠 Parte Teórica
Se analiza la importancia de testear un modelo de Machine Learning para:
- verificar su funcionamiento
- evaluar su eficiencia
- compararlo con otros modelos
- evitar errores de generalización

---

## 📈 Dataset Utilizado
- **Nombre:** `mtcars`
- **Origen:** Librería base de R
- **Registros:** 32
- **Variables:** 11 (cuantitativas)

### 🎯 Variable objetivo
- Consumo de combustible (**mpg**)

### 📥 Variables explicativas
`cyl`, `disp`, `hp`, `drat`, `wt`, `qsec`, `vs`, `am`, `gear`, `carb`

---

## 🔍 Análisis Exploratorio
- Inspección inicial con `head()`, `dim()` y `summary()`
- Análisis de la distribución de la variable objetivo
- Visualización mediante histograma de **mpg**

---

## 🧪 Partición de Datos
Se utilizó la librería **caret** para dividir la base en:
- **75% entrenamiento** (25 registros)
- **25% testeo** (7 registros)

Configuración:
- `set.seed(39264027)`
- `createDataPartition()`

---

## 📊 Resultados y Aprendizajes
- Se verificó la correcta separación de los conjuntos
- El análisis exploratorio permitió entender rangos y escalas
- Se refuerza la importancia del testeo antes de entrenar modelos

---

## 🛠 Herramientas Utilizadas
- R  
- caret  
- Análisis Exploratorio de Datos  
- Aprendizaje Supervisado  

---

## 🌐 Visualización
El trabajo cuenta con una visualización web (`index.html`) donde se resume:
- el enfoque del problema
- el código utilizado
- los resultados principales
