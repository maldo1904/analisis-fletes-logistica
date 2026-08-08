LogiSense AI — Analítica Logística Avanzada

🚀 Descripción del Proyecto
LogiSense AI es una herramienta de Business Intelligence y análisis logístico desarrollada en Python con Streamlit, diseñada para automatizar la auditoría de gastos de transporte, la comparativa de desempeño y la detección de anomalías financieras. A diferencia de los reportes estáticos, esta herramienta permite realizar análisis multidimensional de cualquier periodo (días, semanas o meses) bajo filtros específicos por cliente, transportista, tipo de transporte, tipo de embarque y rutSas geográficas (origen y destino).

🛠️ Tecnologías UtilizadasLenguaje: Python 3.x  
Interfaz Web: Streamlit  
Análisis y Manipulación de Datos: Pandas, NumPy  
Visualización Interactiva: Plotly (Express y Graph Objects)  
Procesamiento de Archivos: OpenPyXL

🔑 Funcionalidades Principales
Flexibilidad Temporal Dinámica: Permite comparar cualquier par de periodos de forma cruzada (ej. Semana vs. Semana, Mes vs. Mes, o Rango de Días Calendario personalizado).
Filtros de Segmentación Multidimensional: Aislamiento instantáneo del impacto financiero mediante filtros combinados de:
    Cliente y Transportista.  
    Tipo de Transporte y Tipo de Embarque.  
    Origen y Destino de los viajes.  
Análisis Estadístico Robusto (Media vs. Mediana): Incorpora cálculo de medianas por viaje (FLETE FACTURA) para evitar distorsiones por valores atípicos (outliers) y explica de forma automatizada las desviaciones entre promedios y valores centrales.  
Auditoría Inteligente de Anomalías: Identificación automática de los viajes del periodo actual que superan la tarifa media del periodo base, generando una tabla de auditoría detallada y gráficos de dispersión de Fletes vs. KG.  
Generador de Prompts Ejecutivos: Construcción automática de un prompt estructurado para IA (listo para copiar y descargar) con todos los indicadores clave de desempeño (KPIs) y variaciones porcentuales, diseñado para la toma de decisiones gerenciales.  
Exportación de Datos: Descarga de reportes en formato Excel (.xlsx) tanto de los desgloses de gastos como de las auditorías de anomalías.  

📊 ¿Qué problemas resuelve?
Eliminación de Procesos Manuales: Automatiza la limpieza de bases de datos de fletes y la generación de reportes comparativos que tradicionalmente tomaban horas en hojas de cálculo.
Negociación Estratégica con Proveedores: Proporciona visibilidad matemática sobre las tarifas y economías de escala (costo por KG y por tarima), dándole al equipo de tráfico argumentos sólidos para renegociar con transportistas.
Detección Inmediata de Riesgos Financieros: Permite auditar al instante qué rutas o viajes específicos están disparando el presupuesto de operación logística.

📋 Cómo utilizar la herramienta
Ejecución: Corre la aplicación ejecutando en tu terminal:
streamlit run app.py
Carga de Datos: Sube tu archivo corporativo en formato Excel (.xlsx) o CSV a través de la interfaz lateral.
Filtrado: Selecciona los filtros operativos de tu interés (clientes, rutas, transportistas).
Selección de Periodos: Elige el modo de comparación (Semana, Mes o Día) y define el Periodo Base contra el Periodo Actual.
Análisis y Reportes: Navega entre las pestañas para revisar los gráficos financieros, auditar los outliers de costos y exportar los prompts o reportes en Excel.
