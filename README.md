# Challengue-TELECOM-X
**PROPÓSITO DEL ANÁLISIS**
El objetivo de este proyecto es:
- Investigar las causas detrás de la evasión de clientes (Churn) en una empresa de telecomunicaciones.
Mediante el análisis de datos proporcionados a través de una API en formato JSON, se buscará:
- Identificar patrones y factores clave que influyen en la decisión de los clientes de abandonar la empresa
- Proporcionar insights accionables para reducir la tasa de evasión
- Preparar los datos para futuros análisis predictivos realizados por el equipo de ciencia de datos
- Generar la estructura del proyecto y organizar los archivos.
- Mostrar la información en gráficos y tablas.
- Ejecutar la depuración y el ordenamiento de los datos en un notebook GoogleColab.
**ESTRUCTURA INICIAL DEL PROYECTO**
telecom-x-analisis/

├── data/

│   ├── raw/                # Datos crudos obtenidos de la API

│   └── processed/          # Datos limpios y transformados

├── notebooks/

│   └── telecom_x_analisis.ipynb  # Notebook principal con el análisis

├── reports/

│   └── findings/           # Informes y presentaciones de resultados

├── README.md               # Este archivo

└── requirements.txt        # Dependencias del proyecto


**EJEMPLOS DE GRÁFICOS E INSIGHTS**
Distribución de Churn:¿Qué es Churn?
Churn (o tasa de abandono) es un término clave en el análisis de negocios, y se refiere a la pérdida de clientes que dejan de usar los productos o servicios de una empresa. En el contexto de Telecom X, el churn representa a los clientes que cancelan sus suscripciones o contratos.
Ta = Churn Rate = (N° de clientes perdidos en un período) / (Total de clientes al inicio del período) × 100

Sobre la estructura del proyecto y organización de los archivos:
El proyecto se creó en etapas:
📌 Extracción 
Contiene la forma en que se extraen los datos desde la API, y las primeras intervenciones para extender las columnas anidadas.
🔧 Transformación 
Son todos los comandos utlizados para transformar los datos y depurarlos para ser posteriormente trabajados.
Se realiza la normalización y estandarización
📊 Carga y análisis 
En base a los datos normalizados y entandarizados se realizan análisis previos mostrando gráficos que permiten visualizar diferencias entre las variables y su relación con la variable clave que es churn. esta variable representa el abandono del servicio por parte de los clientes.
📄Informe final Challengue Telecomx en formato pdf
Este informe es clave para entender el trabajo total efectuado con Python, y donde además de los gráficos, se muestran algunas conjeturas, hallazgos, observaciones, y recomendaciones.
Los análisis realizados son de caracter preliminar, ya que se entiende que el desafío era enviar datos depurados a un equipo de análisis de datos. debido a esto se considera que este análsis debe ser somero y basado en estadística descriptiva. Además este análisisprevio permitió evaluar si los datos estaban suficiente trabajados, para poder realizar análisis. 









