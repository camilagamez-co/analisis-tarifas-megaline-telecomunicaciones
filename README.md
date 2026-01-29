# 📱 Análisis de Tarifas Megaline - Telecomunicaciones

Análisis estadístico de tarifas de telecomunicaciones Megaline: comparación de ingresos entre planes Surf y Ultimate. Incluye análisis de comportamiento de 500 clientes, cálculo de ingresos mensuales, pruebas de hipótesis estadísticas y análisis regional NY-NJ vs otras áreas.

🛠️ Tecnologías Utilizadas
Python 3.8+
Pandas
Manipulación y análisis de datos
NumPy
Operaciones numéricas y estadísticas
Matplotlib
Visualización de datos
Seaborn
Visualizaciones estadísticas avanzadas
SciPy
Pruebas de hipótesis estadísticas
Jupyter Notebook
Entorno de desarrollo interactivo
📋 Descripción del Proyecto
Este proyecto analiza datos de la empresa de telecomunicaciones Megaline para determinar cuál de sus dos tarifas de prepago (Surf y Ultimate) genera más ingresos. El análisis incluye el comportamiento de 500 clientes durante 2018, cálculo de ingresos mensuales por cliente y pruebas estadísticas para validar hipótesis comerciales.

### Objetivos principales:
- Analizar el comportamiento de uso de clientes (llamadas, mensajes, datos)
- Calcular ingresos mensuales por cliente según cada tarifa
- Determinar qué tarifa genera más ingresos mediante análisis estadístico
- Comparar ingresos entre regiones (NY-NJ vs otras áreas)
- Realizar pruebas de hipótesis para validar conclusiones

### Tarifas analizadas:
- Surf: $20/mes - 500 min, 50 SMS, 15 GB
- Ultimate: $70/mes - 3000 min, 1000 SMS, 30 GB

📊 Estructura de Datos
El proyecto utiliza 3 datasets principales:

megaline_calls.csv
Registro de llamadas por cliente
megaline_internet.csv
Consumo de datos móviles
megaline_messages.csv
Registro de mensajes SMS
megaline_plans.csv
Información de tarifas
megaline_users.csv
Datos demográficos de usuarios (500 clientes)
### Variables clave analizadas:
- duration - Duración de llamadas (minutos)
- mb_used - Consumo de datos (MB)
- date - Fecha de uso del servicio
- plan - Tipo de tarifa (Surf/Ultimate)
- city - Ciudad del cliente
- age - Edad del cliente

⚙️ Funcionalidades Implementadas
### Preprocesamiento de Datos:
- Limpieza y validación de datasets
- Conversión de tipos de datos y fechas
- Agregación de datos por cliente y mes
- Cálculo de consumo mensual por servicio

### Análisis de Ingresos:
- Cálculo de ingresos mensuales: Por cliente según tarifa contratada
- Análisis de excesos: Cargos adicionales por sobrepasar límites
- Estadística descriptiva: Media, mediana, varianza de ingresos
- Segmentación: Análisis por tarifa y región

### Pruebas Estadísticas:
- Prueba t de Student: Comparación de ingresos promedio entre tarifas
- Prueba t de Student: Comparación NY-NJ vs otras regiones
- Análisis de normalidad: Verificación de distribuciones
- Intervalos de confianza: Para diferencias de medias

### Visualizaciones:
- **Histogramas de distribución de ingresos**
- **Boxplots comparativos entre tarifas**
- **Gráficos de barras de ingresos promedio**
- **Visualizaciones de consumo por servicio (llamadas, SMS, datos)**
- **Gráficos de dispersión para análisis de correlaciones**

## 🚀 Instalación y Uso

### Prerrequisitos
```bash
Python 3.8+
pip install pandas numpy matplotlib seaborn scipy jupyter
