# 🛒 Análisis de Datos de Call Center

## 📋 Descripción
Este proyecto analiza los patrones de operación de los operadores de un Call Center. Se examinan 5 datasets para identificar tendencias de consumo, horarios de mayor actividad y productos más populares.

## 🎯 Objetivos
- Limpiar y procesar datos de transacciones de e-commerce
- Identificar patrones de compra por horario y día de la semana
- Analizar la relación entre productos, pasillos y departamentos
- Detectar y corregir inconsistencias en los datos

## 📊 Datasets Utilizados
- **orders.csv**: Información de pedidos (fecha, hora, usuario)
- **products.csv**: Catálogo de productos
- **order_products.csv**: Relación pedidos-productos
- **aisles.csv**: Información de pasillos
- **departments.csv**: Información de departamentos

## 🔧 Tecnologías
- Python 3.8+
- Pandas
- Matplotlib
- Jupyter Notebook

## 📈 Principales Hallazgos
- Los pedidos se concentran entre las 10:00 y 16:00 horas
- Los fines de semana muestran un 30% más de actividad
- Se detectaron valores nulos cuando las cantidades superaban 64 unidades

## 🚀 Cómo Ejecutar
1. Clonar el repositorio
2. Instalar dependencias: `pip install pandas matplotlib jupyter`
3. Abrir el notebook: `jupyter notebook analisis_ecommerce.ipynb`
