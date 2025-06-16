# 🏙️ Exploring NYC Public School SAT Results  
**Análisis de Resultados de SAT en Escuelas Públicas de Nueva York**

---

Cada año, los estudiantes de preparatoria en EE.UU. presentan el **SAT**, un examen estandarizado que evalúa habilidades en **lectura, matemáticas y escritura**, con un puntaje máximo de **800 por sección**.  
Este examen es clave para el proceso de admisión universitaria y sirve como métrica para evaluar el desempeño académico de las escuelas.

Este proyecto busca **explorar el rendimiento de las escuelas públicas de Nueva York** a través del análisis de datos del SAT, con el objetivo de identificar tendencias, destacar escuelas con alto rendimiento y proveer información útil para investigadores, autoridades educativas y padres de familia.

---

## 🔍 Objetivos del Análisis

### 1. 🧠 Escuelas con mejor desempeño en matemáticas  
**Pregunta:** ¿Qué escuelas de NYC tienen los mejores resultados en matemáticas?  
- Se considera un buen resultado si el promedio de matemáticas es al menos **80% de 800 puntos** (≥ 640).  
- Se guarda en un DataFrame llamado `best_math_schools`  
- Columnas: `school_name`, `average_math`  
- Ordenado de mayor a menor por `average_math`

---

### 2. 🏆 Top 10 escuelas con mejor rendimiento total en el SAT  
**Pregunta:** ¿Cuáles son las 10 escuelas con mejor rendimiento total combinando todas las secciones del SAT?  
- Se crea una columna nueva `total_SAT` que es la suma de `math`, `reading` y `writing`  
- Se guarda en un DataFrame llamado `top_10_schools`  
- Columnas: `school_name`, `total_SAT`  
- Ordenado de mayor a menor por `total_SAT`

---

### 3. 🌍 Borough con mayor desviación estándar en el puntaje SAT total  
**Pregunta:** ¿Qué borough de NYC tiene la mayor variabilidad en los resultados combinados del SAT?  
- Se analiza el `total_SAT` por borough  
- Se guarda en un DataFrame llamado `largest_std_dev`  
- Columnas:  
  - `borough`  
  - `num_schools` (número de escuelas en el borough)  
  - `average_SAT` (promedio de `total_SAT`)  
  - `std_SAT` (desviación estándar de `total_SAT`)  
- Todos los valores numéricos se redondean a **dos decimales**

---

## 📦 Herramientas Utilizadas

- **Python**  
- **Pandas**  
- **Google Colab**


---

## 📁 Resultados

Este análisis ofrece insights clave para entender la calidad académica de las escuelas públicas de NYC y puede ayudar en la toma de decisiones educativas tanto a nivel individual como institucional.

---

> ✨ *Proyecto realizado como práctica de análisis de datos con enfoque en educación. Si te interesa colaborar o dar feedback, ¡estás más que bienvenido!*
