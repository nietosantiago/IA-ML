# 🤖 IA & Machine Learning  
## Trabajo Práctico 3 – Aprendizaje No Supervisado

📘 **Certificación Avanzada en Ciencia de Datos**  
🏫 **ITBA**  
👤 **Autores:**  
- Santiago Nieto  
- Aitor Ortuño Rossetto  
📅 **Año:** 2025  

---

## 📊 Descripción del Trabajo
Este trabajo práctico introduce técnicas de **aprendizaje no supervisado** mediante
la aplicación del algoritmo **K-Means** para el agrupamiento de datos.

El objetivo es identificar patrones y segmentos dentro de un dataset sin variable objetivo definida.

---

## 📈 Dataset Utilizado
- **Nombre:** `cheddar`
- **Origen:** Librería `faraway`
- **Registros:** 30
- **Variables:**
  - `taste`: puntaje subjetivo de sabor
  - `Acetic`: concentración de ácido acético (log)
  - `H2S`: concentración de sulfuro de hidrógeno (log)
  - `Lactic`: concentración de ácido láctico

---

## 🧪 Metodología
- Análisis descriptivo del dataset (`summary`)
- Definición de semilla basada en DNI
- Aplicación de **K-Means** con:
  - `k = 4` grupos
  - parámetros por defecto

---

## 🔢 Resultados del Clustering
- Tamaño de los grupos:  
  - Grupo 1: 12 elementos  
  - Grupo 2: 9 elementos  
  - Grupo 3: 4 elementos  
  - Grupo 4: 5 elementos  

- El primer registro pertenece al **grupo 1**

---

## 📊 Interpretación de Resultados
- El **grupo 3** presenta el mayor puntaje promedio de sabor (`taste`)
- También posee las concentraciones más altas de Acetic, H2S y Lactic
- Se observa una relación positiva entre componentes químicos y percepción de sabor
- El **grupo 4** presenta los valores más bajos en todas las variables

---

## 🛠 Herramientas Utilizadas
- R  
- faraway  
- K-Means  
- Aprendizaje No Supervisado  

---

## 🌐 Visualización
El trabajo incluye una visualización web (`index.html`) con:
- código utilizado
- resultados del clustering
- análisis de los centroides
