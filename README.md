# An-lisis-de-xito-en-Ventas-de-Videojuegos
Project_Sprint-6 -- Las reseñas de usuarios y expertos, los géneros, las plataformas (por ejemplo, Xbox o PlayStation) y los datos históricos sobre las ventas de juegos están disponibles en fuentes abiertas. Tienes que identificar patrones que determinen si un juego tiene éxito o no.
# Análisis de Éxito en Ventas de Videojuegos

Este proyecto analiza datos históricos de videojuegos (hasta 2016) para identificar patrones que determinan el éxito comercial de un título. El objetivo es apoyar a **Ice**, una tienda online de videojuegos, en la selección de proyectos prometedores y la planificación de campañas publicitarias para 2017.

## 🎯 Objetivos principales
- Identificar factores clave que influyen en las ventas: género, plataforma, puntuaciones de críticos/usuarios y clasificación ESRB.
- Analizar tendencias por región (Norteamérica, Europa, Japón).
- Comparar el rendimiento de plataformas y géneros a lo largo del tiempo.
- Probar hipótesis sobre diferencias en calificaciones entre plataformas y géneros.

## 📁 Datos
- Archivo: `games.csv`
- Variables clave: ventas por región, año de lanzamiento, plataforma, género, puntuaciones (críticos y usuarios) y clasificación ESRB.
- Las ventas totales por juego se calcularon como la suma de todas las regiones.

## 🔍 Metodología
1. **Limpieza y preparación**: estandarización de nombres, conversión de tipos, manejo de valores faltantes (incluyendo "TBD").
2. **Análisis exploratorio**: tendencias por año/plataforma, distribución de ventas, correlación con reseñas.
3. **Segmentación por región**: plataformas y géneros más populares en NA, EU y JP.
4. **Pruebas de hipótesis**:
   - ¿Las calificaciones de usuarios en Xbox One y PC son iguales?
   - ¿Difieren las calificaciones entre los géneros Acción y Deportes?

## 🛠️ Tecnologías
- Python (pandas, numpy, matplotlib, seaborn, scipy)
- Jupyter Notebook

---

💡 *Proyecto educativo realizado como parte de un curso de análisis de datos.*
