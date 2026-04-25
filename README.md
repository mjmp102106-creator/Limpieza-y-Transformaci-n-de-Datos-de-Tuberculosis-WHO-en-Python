# Caso Práctico Python – Análisis de Tuberculosis (OMS)

Este proyecto implementa un flujo de trabajo en Python para la **limpieza, transformación y estructuración de datos** relacionados con casos de tuberculosis, siguiendo principios de *tidy data*.  

El objetivo es preparar la información para su posterior análisis por parte de tomadores de decisiones en el contexto de la **Organización Mundial de la Salud (OMS)**.

---

## 🎯 Objetivo

- Estandarizar y limpiar los datasets `who` y `population`
- Transformar los datos a un formato ordenado (*tidy data*)
- Integrar múltiples fuentes en un solo dataset estructurado
- Facilitar su uso para análisis posteriores

---

## 📂 Conjuntos de Datos

- **who**: Información de casos de tuberculosis por país, año, género y grupo etario  
- **population**: Datos de población por país y año  

Fuente: https://tidyr.tidyverse.org/reference/who.html

---

## ⚙️ Procesos Realizados

### Limpieza de Datos
- Manejo de valores nulos
- Estandarización de nombres de columnas
- Conversión de tipos de datos

###  Transformación
- Reestructuración de columnas (wide → long)
- Separación de variables embebidas (edad, género, tipo de caso)
- Creación de variables limpias y analizables

### Integración de Datos
- Unión de datasets (`who` + `population`)
- Alineación por país y año
- Generación de dataset final consolidado

---

## 🛠️ Tecnologías Utilizadas

- Python 3  
- Pandas  
- NumPy  
- Jupyter Notebook  

