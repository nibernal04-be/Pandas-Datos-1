Tarea 3 – Manipulación de Datos con Pandas

🌿 Universidad de Cundinamarca

📁 Repositorio GitHub

nicoll_bernal_pandas_agua

🎯 Objetivo general

Analizar y procesar información ambiental mediante la biblioteca pandas, aplicando lectura, filtrado, agrupamiento y generación de resúmenes estadísticos a partir del dataset:

data/resultados_calidad_hidrica.csv
🧩 Datos de referencia
Sitio	pH	Oxígeno (mg/L)	Temperatura (°C)	Turbidez (NTU)
Río Frío (Zipaquirá)	7.1	7.5	18.9	12
Quebrada La Moya (Funza)	6.4	5.8	22.1	28
Río Bogotá (Chía)	5.8	4.2	27.4	45
Río Negro (Útica)	8.0	6.9	24.0	19
Quebrada Amarilla (Villeta)	7.7	7.2	23.8	15
Río Dulce (Guaduas)	8.5	5.1	29.5	33
Río Sumapaz (Fusagasugá)	6.9	6.5	21.7	20
Quebrada Santa Rita (Facatativá)	6.1	4.7	26.3	38
Río Neusa (Cogua)	7.3	8.0	17.6	10
Río Apulo (Apulo)	8.2	5.9	30.2	41
👩‍💻 Roles por grupo (4 estudiantes)
Notebook	Descripción	Responsable
0_ejemplo_clase_pandas.ipynb	Ejemplo general de lectura y manipulación de datos.	Todos
reto1_exploracion_datos.ipynb	Cargar, explorar y describir los datos ambientales.	Estudiante 1
reto2_filtros_condiciones.ipynb	Aplicar filtros y condiciones lógicas sobre pH, temperatura y oxígeno.	Estudiante 2
reto3_estadisticas_operaciones.ipynb	Calcular estadísticas y crear nuevas columnas usando operaciones matemáticas.	Estudiante 3
reto4_diagnostico_integral.ipynb	Integrar resultados y generar un diagnóstico ambiental final.	Estudiante 4
⚙️ Pasos para completar la tarea
1️⃣ Desarrollo individual

Cada integrante debe desarrollar el notebook asignado.

2️⃣ Archivo compartido

Todos los notebooks deben trabajar sobre el archivo:

data/resultados_calidad_hidrica.csv
3️⃣ Variables ambientales

El dataset incluye variables como:

Sitio de muestreo
pH
Oxígeno disuelto
Temperatura
Turbidez
4️⃣ Presentación

Cada notebook debe incluir:

Explicaciones en Markdown
Comentarios dentro del código
Resultados organizados y claros
Tablas y análisis interpretativos
🧩 Recomendaciones

✅ Mantener nombres de columnas uniformes.

✅ Aplicar funciones de pandas vistas en clase:

.head()
.describe()
.mean()
.groupby()
.apply()
.value_counts()

✅ Documentar cada procedimiento realizado.

✅ Verificar los resultados entre todos los integrantes antes de la entrega.

📂 Estructura del proyecto
nicoll_bernal_pandas_agua/
│
├── data/
│   └── resultados_calidad_hidrica.csv
│
├── notebooks/
│   ├── 0_ejemplo_clase_pandas.ipynb
│   ├── reto1_exploracion_datos.ipynb
│   ├── reto2_filtros_condiciones.ipynb
│   ├── reto3_estadisticas_operaciones.ipynb
│   └── reto4_diagnostico_integral.ipynb
│
└── README.md
📊 Evaluación
Criterio	Descripción	Ponderación
Lectura y exploración de datos	Uso correcto de pandas para cargar y revisar información	20%
Filtros y condiciones	Aplicación de expresiones lógicas y selección de datos	20%
Funciones y operaciones	Uso de funciones estadísticas y personalizadas	20%
Integración y análisis final	Coherencia, conclusiones y calidad del diagnóstico	25%
Documentación y presentación	Comentarios, celdas Markdown y claridad visual	15%
🧠 Resultado esperado

El grupo entregará un análisis integral de calidad hídrica utilizando pandas, demostrando habilidades en:

Lectura de archivos CSV,
Exploración y filtrado de datos,
Aplicación de estadísticas,
Creación de columnas calculadas,
Integración de resultados ambientales,
Interpretación de información hidrológica y ecológica.
