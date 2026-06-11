# 🌡️ Sistema de Análisis de Sensores de Temperatura
## Calificación de Equipos Isotérmicos - v8.0 ULTIMATE

Sistema automatizado en Python para procesamiento de datos de sensores de temperatura en estudios de mapeo térmico de bodegas y áreas controladas, desarrollado para DVA Ingeniería S.A.S.

## 🚀 ¿Qué hace este sistema?

Automatiza completamente el proceso de análisis de datos de sensores que antes se realizaba manualmente mediante scroll por fecha/hora y construcción manual de plantillas Excel, reduciendo el tiempo de procesamiento de horas a minutos.

## ✨ Funcionalidades

- 📂 Lectura de archivos de múltiples sensores (.xls / .xlsx)
- ✂️ Segmentación automática de datos por fecha y hora
- 🔧 Aplicación de correcciones de lectura por interpolación (T1, C1, T2, C2)
- 📊 Cálculo automático de métricas estadísticas profundas (promedio, máximo, mínimo, variación, estabilidad, gradiente)
- 📈 Generación automática de gráficas (Distribución y Deriva de temperatura)
- 💾 Exportación completa a Excel con 7 hojas
- ⏱️ Tasa de muestreo seleccionable (30s, 1min, 2min, 5min, 10min)

## 📋 Hojas del reporte Excel generado

1. Resumen - Configuración y resultados
2. Gráfica Distribución
3. Gráfica Deriva
4. Datos SIN Corrección
5. Datos CON Corrección
6. Trazabilidad - Certificados de calibración
7. Estadísticas generales

## 🛠️ Tecnologías utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- OpenPyXL / XlsxWriter
- Google Colab

## 👤 Autor

Gustavo Adolfo Davila Donoso
Data Analyst | DVA Ingeniería S.A.S
