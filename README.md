# 📊 Análisis de Rentabilidad de Tarifas Megaline

## 📋 Descripción del Proyecto

Este proyecto analiza el comportamiento de usuarios y la rentabilidad de dos planes de tarifas de la empresa de telecomunicaciones **Megaline**: **Surf** y **Ultimate**. El objetivo principal es determinar cuál de los dos planes genera más ingresos para optimizar la asignación del presupuesto publicitario.

### 🎯 Objetivos

- Analizar patrones de consumo de 500 usuarios durante 2018
- Comparar la rentabilidad entre los planes Surf y Ultimate  
- Realizar pruebas estadísticas para validar diferencias significativas
- Proporcionar recomendaciones estratégicas para el departamento comercial

### 📊 Datos Analizados

- **500 usuarios** de Megaline
- **Período**: Año 2018 completo
- **Servicios**: Llamadas, SMS y tráfico de internet
- **Planes**: Surf ($20/mes) y Ultimate ($70/mes)

## ⚙️ Funcionalidades Implementadas

### 🔍 Análisis Exploratorio de Datos
- Limpieza y preparación de 5 tablas de datos interrelacionadas
- Conversión de tipos de datos y manejo de valores faltantes
- Aplicación de reglas de negocio específicas de Megaline (redondeo de minutos y GB)

### 📈 Análisis Estadístico Descriptivo
- Cálculo de estadísticas por plan: media, varianza, desviación estándar
- Análisis de distribuciones de consumo mensual
- Identificación de patrones estacionales de uso

### 💰 Cálculo de Ingresos
- Implementación de lógica de facturación por plan
- Cálculo de cargos por excesos de límites incluidos
- Agregación mensual de ingresos por usuario

### 📊 Visualizaciones
- Histogramas de distribución de consumo por servicio
- Gráficos de barras comparativos entre planes
- Diagramas de caja para análisis de variabilidad
- Gráficos de ingresos mensuales y por usuario

### 🧪 Pruebas de Hipótesis
- **Hipótesis 1**: Comparación de ingresos promedio entre planes Surf y Ultimate
- **Hipótesis 2**: Comparación de ingresos entre usuarios de NY-NJ vs otras regiones
- Uso de t-tests bilaterales con nivel de significancia α = 0.05

## 🚀 Instalación y Uso

### Prerrequisitos
```bash
Python 3.7+
Jupyter Notebook
