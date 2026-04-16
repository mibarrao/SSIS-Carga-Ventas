# 📊 ETL Proceso Carga de Ventas (Power Automate + SSIS + C#) / Sales Loading ETL Process

🇪🇸 **[ESPAÑOL]**

Este proyecto consiste en un pipeline **ETL** automatizado que integra la orquestación en la nube con el procesamiento on-premise. El flujo comienza con **Power Automate** gestionando la descarga de archivos de origen desde una ruta específica, seguido por un paquete de **SSIS** que realiza la transformación y carga final en **SQL Server**.

### 🚀 Arquitectura y Flujo de Datos
1. **Orquestación (Power Automate):** Descarga automática de archivos de ventas desde una ubicación definida (SharePoint/Email) hacia el servidor de procesamiento.
2. **Extracción (SSIS):** Captura de datos desde los archivos descargados mediante administradores de conexiones dinámicos.
3. **Transformación (Script Task C#):** Lógica en C# para validaciones de archivos y pre-procesamiento de datos.
4. **Carga (SQL Server):** Inserción masiva en tablas transaccionales mediante destinos OLE DB optimizados.

### 🛠️ Tecnologías Utilizadas

![Power Automate](https://img.shields.io/badge/Power%20Automate-0066FF?style=for-the-badge&logo=power-automate&logoColor=white)
![SQL Server](https://img.shields.io/badge/Microsoft%20SQL%20Server-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)
![Visual Studio](https://img.shields.io/badge/Visual%20Studio-5C2D91?style=for-the-badge&logo=visual-studio&logoColor=white)

* **Orquestador:** Power Automate (Desktop/Cloud)
* **Herramienta ETL:** SQL Server Integration Services (SSIS)
* **Base de Datos:** SQL Server 2019+

---

🇬🇧 **[ENGLISH]**

This project is an automated **ETL pipeline** that integrates cloud orchestration with on-premise processing. The workflow starts with **Power Automate** managing the file downloads from a specific path, followed by an **SSIS** package that performs the data transformation and final load into **SQL Server**.

### 🚀 Architecture & Data Flow
1. **Orchestration (Power Automate):** Automated download of sales files from a specific location (SharePoint/Email) to the processing server.
2. **Extraction (SSIS):** Data capture from downloaded files using dynamic connection managers.
3. **Transformation (C# Script Task):** Custom C# logic for file validation and data pre-processing.
4. **Loading (SQL Server):** Optimized bulk insertion into transactional tables via OLE DB destinations.

### 🛠️ Tech Stack & Tools

![Power Automate](https://img.shields.io/badge/Power%20Automate-0066FF?style=for-the-badge&logo=power-automate&logoColor=white)
![SQL Server](https://img.shields.io/badge/Microsoft%20SQL%20Server-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)
![Visual Studio](https://img.shields.io/badge/Visual%20Studio-5C2D91?style=for-the-badge&logo=visual-studio&logoColor=white)

---

### 📂 Archivos del Proyecto / Project Files
* `src/`: Paquete principal `.dtsx` / *Main SSIS package*.
* `sql/`: Scripts para la creación de procedimientos / *SQL table creation procedures*.
* `Carga Ventas.sln`: Solución de Visual Studio / *Visual Studio solution*.
