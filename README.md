# 🛒 Análisis de Datos de Call Center

## 📋 Descripción
Este proyecto analiza los patrones de operación de los operadores de un Call Center. Se examinan 5 datasets para identificar tendencias de consumo, horarios de mayor actividad y productos más populares.

## 🎯 Objetivos
-Lleva a cabo el análisis exploratorio de datos 
- Identificar operadores ineficaces
- Prueba las hipótesis estadísticas


## 📊 Datasets Utilizados
- **telecom_dataset_us.csv**:
user_id: ID de la cuenta de cliente
date: fecha en la que se recuperaron las estadísticas
direction: "dirección" de llamada (out para saliente, in para entrante)
internal: si la llamada fue interna (entre los operadores de un cliente o clienta)
operator_id: identificador del operador
is_missed_call: si fue una llamada perdida
calls_count: número de llamadas
call_duration: duración de la llamada (sin incluir el tiempo de espera)
total_call_duration: duración de la llamada (incluido el tiempo de espera)

- **telecom_clients_us.csv**:
user_id: ID de usuario/a
tariff_plan: tarifa actual de la clientela
date_start: fecha de registro de la clientela


## 🔧 Tecnologías
Entorno de desarrollo:
- Jupyter Notebook
- Python 3.9.19
### Líbrerias:
- Pandas
- Matplotlib

## 📈 Principales Hallazgos
- Los pedidos se concentran entre las 10:00 y 16:00 horas
- Los fines de semana muestran un 30% más de actividad
- Se detectaron valores nulos cuando las cantidades superaban 64 unidades

## 🚀 Cómo Ejecutar
1. Clonar el repositorio
2. Instalar dependencias: `pip install pandas matplotlib jupyter`
3. Abrir el notebook: `jupyter notebook analisis_ecommerce.ipynb`
