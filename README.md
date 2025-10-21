# 🚀 Desafío: Tipos y Estructuras de Datos (Parte II)

Este repositorio contiene la solución al desafío de manipulación de datos usando **pandas** en Python, enfocado en la validación de candidatos a astronautas según criterios físicos y evaluativos.

## 📂 Archivo base

- `resumen_resultados_astronautas.csv`: contiene los datos de los postulantes, incluyendo peso, altura, evaluaciones y experiencia.

## 🧪 Objetivos del desafío

1. Crear un DataFrame a partir del archivo CSV.
2. Calcular el **IMC** (Índice de Masa Corporal) usando la fórmula:  
   `IMC = peso / (altura_en_metros)^2`
3. Calcular el **promedio de evaluaciones** a partir de 4 columnas.
4. Filtrar los candidatos con IMC entre 18.5 y 24.9.
5. Filtrar los que además tengan promedio de evaluaciones ≥ 87.
6. Reiniciar el índice del DataFrame filtrado.
7. Modificar la columna `califica` para que diga `"Si"` en todos los casos seleccionados.
8. Exportar el resultado a un nuevo archivo:  
   `astronautas_calificados.csv`

## 🧠 Análisis y ciencia de datos

Este ejercicio permite aplicar conceptos clave de la ciencia de datos como limpieza, transformación y filtrado de información. A través del uso de pandas, se simula un proceso de selección técnica basado en métricas objetivas, lo que demuestra cómo el análisis de datos puede apoyar decisiones estratégicas en contextos reales. Además, es una excelente base para introducir visualización, modelado o análisis exploratorio en futuras etapas.
