# 📊 ETL Proceso Carga de Ventas (SSIS & C#) / Sales Loading ETL Process (SSIS & C#)

🇪🇸 **[ESPAÑOL]**

Este proyecto es un pipeline **ETL (Extracción, Transformación y Carga)** automatizado, construido sobre **SQL Server Integration Services (SSIS)**. Su objetivo es centralizar y estandarizar la carga de datos de ventas provenientes de diversos orígenes (Excel/Archivos Planos) hacia un entorno de SQL Server, garantizando la integridad de la información mediante lógica personalizada en C#.

### 🚀 Arquitectura y Flujo de Datos
1. **Extracción:** Captura de datos desde libros de Excel y archivos de origen mediante administradores de conexiones dinámicos.
2. **Transformación (Script Task C#):** Uso de scripts en C# para validaciones avanzadas, manejo de rutas de archivos y pre-procesamiento de datos.
3. **Flujo de Control:** Implementación de tareas de limpieza de tablas y contenedores de secuencia para un flujo lógico ordenado.
4. **Carga (SQL Server):** Inserción masiva de registros optimizada mediante destinos OLE DB.

### 🛠️ Tecnologías Utilizadas

![SQL Server](https://img.shields.io/badge/Microsoft%20SQL%20Server-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)
![Visual Studio](https://img.shields.io/badge/Visual%20Studio-5C2D91?style=for-the-badge&logo=visual-studio&logoColor=white)

* **Herramienta ETL:** SQL Server Integration Services (SSIS)
* **Lenguaje de Scripting:** C# (Script Tasks)
* **Base de Datos:** SQL Server

---

🇬🇧 **[ENGLISH]**

This project is an automated **ETL (Extract, Transform, Load)** pipeline built with **SQL Server Integration Services (SSIS)**. Its purpose is to centralize and standardize the loading of sales data from various sources (Excel/Flat Files) into a SQL Server environment, ensuring data integrity through custom C# logic.

### 🚀 Architecture & Data Flow
1. **Extraction:** Data capture from Excel workbooks and source files using dynamic connection managers.
2. **Transformation (C# Script Task):** Utilizing C# scripts for advanced validations and data pre-processing.
3. **Control Flow:** Implementation of table cleanup tasks and sequence containers for an ordered logical flow.
4. **Loading (SQL Server):** Optimized bulk insertion of records via OLE DB destinations.

### 🛠️ Tech Stack & Tools

![SQL Server](https://img.shields.io/badge/Microsoft%20SQL%20Server-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)
![Visual Studio](https://img.shields.io/badge/Visual%20Studio-5C2D91?style=for-the-badge&logo=visual-studio&logoColor=white)

---

### 📂 Archivos del Proyecto / Project Files
* `src/`: Contiene el paquete principal `.dtsx` / *Main Integration Services package*.
* `sql/`: Scripts SQL para la creación de procedimientos / *SQL scripts for table creation and procedures*.
* `Carga Ventas.sln`: Archivo de solución de Visual Studio / *Visual Studio solution file*.
