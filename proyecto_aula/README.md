# 🌆 Proyecto de aula: Concentración de PM2.5 en Pekín y su relación con variables meteorológicas

## 👩‍🔬 Autor
**Estefanía Hurtado Reina**

---

## 🎯 Objetivo
- Aplicar técnicas de **análisis exploratorio de datos (EDA)** para conocer el comportamiento y distribución de las variables relacionadas con la concentración de PM2.5, y así empezar a considerar o descartar posibles relaciones entre ellas.  
- Aplicar **técnicas de detección de datos atípicos** y tomar decisiones sobre su tratamiento posterior.

---

## 📁 Estructura del repositorio

El repositorio se organiza en los siguientes apartados principales:

1. **Introducción**
   - 1.1 Pregunta de investigación  
   - 1.2 Contexto  
   - 1.3 Relación entre el problema y la base de datos seleccionada  

2. **Librerías y Datos**
   - 2.1 Importación de librerías  
   - 2.2 Importación de datos  
   - 2.3 Descripción de la base de datos  

3. **Análisis exploratorio de las variables**
   - 3.1 Visualizaciones exploratorias básicas  
   - 3.2 Gráficas exploratorias para la variable principal (PM2.5)  
   - 3.3 Gráficas exploratorias relacionando la variable principal con las demás variables  

4. **Detección y análisis de datos atípicos**
   - 4.1 Método de Rango Intercuartílico (IQR)  
   - 4.2 Método de Isolation Forest  

5. **Conclusiones**

6. **Referencias**

---

## 💾 Fuente de los datos

- **Dataset:** [Beijing PM2.5](https://archive.ics.uci.edu/dataset/381/beijing+pm2+5+data)  
  **Repositorio:** UCI Machine Learning Repository  
  **Autor:** Song Chen  
  **Descripción:**  
  Este conjunto de datos horarios contiene las concentraciones de PM2.5 medidas en la Embajada de EE. UU. en Pekín, junto con datos meteorológicos del Aeropuerto Internacional de Pekín-Capital.

- **Paper introductorio:**  
  Liang, X., Zou, T., Guo, B., Li, S., Zhang, H., Zhang, S., ... & Chen, S. X. (2015).  
  *Assessing Beijing's PM2.5 pollution: severity, weather impact, APEC and winter heating.*  
  *Proceedings of the Royal Society A: Mathematical, Physical and Engineering Sciences, 471*(2182), 20150257.  
  [https://doi.org/10.1098/rspa.2015.0257](https://doi.org/10.1098/rspa.2015.0257)

---

## 📊 Descripción general
Este proyecto busca analizar la variación temporal de la contaminación atmosférica por material particulado fino (PM2.5) en Pekín y su relación con factores meteorológicos como temperatura, presión, punto de rocío, velocidad y dirección del viento.  
El análisis combina técnicas visuales y métodos estadísticos para identificar patrones, correlaciones y posibles anomalías en los datos.
