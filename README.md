# Análisis Exploratorio de Datos (EDA) - S&P 500

## Descripción del Proyecto

Este proyecto presenta un **Análisis Exploratorio de Datos (EDA)** del índice **S&P 500** (Standard & Poor's 500), utilizando técnicas de análisis técnico para evaluar su comportamiento desde el año 2000 hasta el 2024. A través de visualizaciones y herramientas estadísticas, se identifican patrones, tendencias y posibles predicciones del índice.

---

## 📑 **Índice de Contenidos**

1. [Introducción](#introducción)  
2. [Hipótesis](#hipótesis)  
3. [Análisis Precio de Cierre (2000–2024)](#análisis-precio-de-cierre-2000-2024)  
4. [Líneas de Tendencia y Puntos Máximos y Mínimos 2024](#líneas-de-tendencia-y-puntos-máximos-y-mínimos-2024)  
5. [Medias Móviles](#medias-móviles)  
6. [Índice de Fuerza Relativa (RSI)](#índice-de-fuerza-relativa-rsi)  
7. [Bandas de Bollinger](#bandas-de-bollinger)  
8. [Predicción (Regresión Lineal)](#predicción-regresión-lineal)  
9. [Conclusiones](#conclusiones)  

---

## 📌 **Introducción**

El S&P 500 es un índice bursátil compuesto por las 500 empresas más grandes de Estados Unidos, siendo un indicador clave del rendimiento del mercado accionario. Este análisis utiliza el **análisis técnico** como herramienta principal para evaluar la evolución histórica del índice, su comportamiento reciente y proyecciones futuras.

---

## 🎯 **Hipótesis**

El objetivo del proyecto es analizar y proyectar el comportamiento del índice S&P 500 utilizando herramientas técnicas, buscando identificar patrones de soporte, resistencia y tendencias futuras.

---

## 📊 **Análisis Precio de Cierre (2000–2024)**

- Se observan periodos de crisis y recuperación:
  - **2000–2002**: Caída durante la burbuja de las puntocom.
  - **2008–2009**: Descenso pronunciado debido a la crisis financiera global.
  - **2020–2021**: Recuperación rápida tras la pandemia de COVID-19.
- **Tendencia general**: Alcista a largo plazo con niveles récord superiores a **6,000 puntos**.

---

## 📈 **Líneas de Tendencia y Puntos Máximos y Mínimos 2024**

- Se identifican **líneas de soporte** (tendencia alcista) y **resistencia** (tendencia bajista).
- Puntos clave:
  - **Máximos**: Representan momentos de resistencia.
  - **Mínimos**: Indican niveles de soporte donde el mercado suele recuperarse.

---

## 🔄 **Medias Móviles**

Se utilizan **SMA (Medias Móviles Simples)** de **20**, **50** y **200 días**:
- **SMA 20 días**: Detecta tendencias a corto plazo.  
- **SMA 50 días**: Actúa como soporte/resistencia de mediano plazo.  
- **SMA 200 días**: Nivel clave de soporte a largo plazo.  

### Señales:
- **Compra**: Cuando la SMA 20 cruza hacia arriba a SMA 50 o SMA 200.  
- **Venta**: Cuando la SMA 20 cruza hacia abajo.  

---

## 📊 **Índice de Fuerza Relativa (RSI)**

- **Sobrecompra (RSI > 70)**: Señala posibles correcciones.  
- **Sobreventa (RSI < 30)**: Indica oportunidades de rebote.  
- El RSI oscila principalmente entre **40–70**, mostrando estabilidad en el mercado.

---

## 📉 **Bandas de Bollinger**

Las **Bandas de Bollinger** permiten identificar volatilidad y señales de compra/venta:
- **Señales de Compra**: Precio cae por debajo de la banda inferior.  
- **Señales de Venta**: Precio supera la banda superior.  
- La **media móvil de 20 días** actúa como soporte/resistencia dinámico.

---

## 📈 **Predicción (Regresión Lineal)**

Se proyecta el comportamiento del índice para los próximos **30 días**:
- La **tendencia alcista** se mantiene con un crecimiento gradual hacia **6,200 puntos**.  
- La proyección sigue una línea de crecimiento lineal moderada.

---

## 📝 **Conclusiones**

1. **Tendencia General**: El S&P 500 mantiene una **tendencia alcista** a largo plazo, con recuperaciones tras periodos de crisis.
2. **Medias Móviles**: Actúan como señales claves para identificar oportunidades de compra y venta.  
3. **RSI**: Detecta momentos de sobrecompra y sobreventa.  
4. **Bandas de Bollinger**: Identifican niveles extremos de precios y volatilidad.  
5. **Predicción**: Se proyecta un crecimiento continuo hacia niveles superiores a **6,200 puntos**.

---

## 📋 **Recomendaciones**

- Utilizar **cruces de medias móviles** para identificar puntos de entrada y salida.
- Atender las señales del **RSI** en niveles extremos (>70 o <30).
- Monitorear las **Bandas de Bollinger** para evaluar la volatilidad del mercado.
- Mantener una estrategia a largo plazo debido a la resiliencia histórica del mercado.

---

## 🛠 **Tecnologías Utilizadas**

- **Python**: Análisis y visualización de datos.
- **Librerías**: Pandas, Matplotlib, Numpy, Seaborn.
- **Herramientas de análisis técnico**: SMA, RSI, Bandas de Bollinger, Regresión Lineal.

---

## 🚀 **Autor**

- **Rommel López García**  
- Análisis Exploratorio de Datos (EDA) - S&P 500  

---

## 📝 **Notas**

El análisis aquí presentado es de carácter técnico y está sujeto a las fluctuaciones del mercado. Se recomienda validar los resultados con herramientas adicionales antes de tomar decisiones de inversión.

