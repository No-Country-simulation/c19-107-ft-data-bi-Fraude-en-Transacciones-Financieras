

# c19-107-ft-data-bi | Fraude-en-Transacciones-Financieras

## Descripción del Proyecto

Este proyecto tiene como objetivo desarrollar un modelo predictivo para detectar transacciones financieras fraudulentas, especialmente en pagos electrónicos como Tarjetas de Crédito. Además, integraremos información del BCRA relacionada con cheques rechazados, dado que la emisión de cheques sin fondos constituye una forma de fraude financiero.

## Equipo

- **PM/Data Engineer:** Javier Edgar Esteban
- **Data Analyst/BI:** Grelizet Rojas & Karina Mas Roca
- **Scrum Master:** Karina, Grelizet y Edgar
- **Team Leader:** María Mercedes Ramella

## Stack Tecnológico

### Herramientas de Comunicación y Colaboración

- **Comunicación:** Slack, Discord, Google Meet, WhatsApp
- **Gestión de Documentos:** Google Drive
- **Gestión de Tareas y Proyectos:** Jira
- **Reuniones Diarias:** Google Meet, WhatsApp, Slack, Discord
- **Planificación de Sprint:** Jira (enlace al calendario diario y semanal de actividades)

### Tecnologías y Herramientas de Desarrollo o Skills estamos usando

- **numpy**: Librería de Python que se utiliza para realizar operaciones matemáticas y numéricas de manera eficiente. 
- **pandas**: Librería de Python que proporciona estructuras de datos y herramientas para el análisis de datos. 
- **zipfile**: Módulo de Python que permite trabajar con archivos comprimidos en formato ZIP. 
- **os**: Módulo de Python que proporciona funciones para interactuar con el sistema operativo, como manipular archivos y directorios. 
- **json**: Módulo de Python que permite trabajar con datos en formato JSON (JavaScript Object Notation). 
- **requests**: Librería de Python que facilita realizar solicitudes HTTP, como enviar peticiones a servidores web y recibir respuestas. 
- **HTTPAdapter**: Clase de la librería requests que permite configurar adaptadores para manejar solicitudes HTTP. 
- **InsecureRequestWarning**: Clase de la librería requests que maneja advertencias relacionadas con solicitudes HTTP inseguras. 
- **PoolManager**: Clase de la librería requests que gestiona las conexiones HTTP. 
- **ssl**: Módulo de Python que proporciona funcionalidades para trabajar con sockets seguros (SSL) y certificados de seguridad. 
 
Manejo de Paquetes: Importar bibliotecas necesarias como requests, pandas, zipfile, y os.
Configuración de Advertencias: Deshabilitar advertencias de solicitudes inseguras para un entorno de desarrollo utilizando InsecureRequestWarning.

Manejo de Rutas y URLs: Definir las rutas locales a los archivos ZIP y la URL del endpoint de la API del BCRA.

Manejo de Archivos ZIP: Listar los archivos contenidos en un archivo ZIP utilizando zipfile.

Manejo de Archivos ZIP: Extraer archivos de un ZIP y leer datasets CSV utilizando zipfile y pandas.

Manipulación de Archivos y Datos: Verificar y leer archivos CSV de archivos ZIP, y manejar casos donde no se encuentren archivos CSV.

Consumo de APIs: Realizar solicitudes GET a una API y manejar la respuesta utilizando requests.
Manejo de Datos: Convertir la respuesta JSON en un DataFrame y guardarlo como un archivo CSV utilizando pandas.

Consumo de APIs: Realizar solicitudes GET a un endpoint específico para obtener datos de una variable.
Manejo de Datos: Convertir la respuesta JSON en un DataFrame y guardarlo como un archivo CSV utilizando pandas.


- **Entorno de Desarrollo:** Visual Studio Code con Python y librerías necesarias
- **Visualización de Datos:** Microsoft Power BI
- **Colaboración y Brainstorming:** Miro


## Conjuntos de Datos

1. **Fraude en Transacciones Financieras**
2. **Fraude en Transacciones en E-commerce**
3. **Fraude en Cheques emitidos por el BCRA**

## Presentación de Resultados

El trabajo se presentará a través de diferentes notebooks y dashboards:

- **ETL (Extract, Transform, Load):** Preparación inicial de datos
- **EDA (Exploratory Data Analysis):** Análisis exploratorio de datos
- **Notebook de Machine Learning:** Desarrollo y evaluación del modelo predictivo
- **Dashboard:** Creación de visualizaciones interactivas con Microsoft Power BI, enlazadas en novyPro para su visualización y acceso público.