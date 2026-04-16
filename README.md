# 📊 ETL Process: Carga de Ventas (SSIS + C#)

Este proyecto implementa un proceso ETL robusto utilizando **SQL Server Integration Services (SSIS)** para la extracción, transformación y carga de datos de ventas.

## 🚀 Tecnologías Utilizadas
* **SSIS (ETL):** Flujo de control y de datos principal.
* **C# (Script Task):** Lógica personalizada para validación de archivos.
* **SQL Server:** Almacenamiento y procesamiento de datos.
* **Excel:** Origen de datos para la carga inicial.

## 🛠️ Funcionalidades Principales
- **Extracción Dinámica:** Carga de datos desde archivos Excel con nombres variables.
- **Lógica en C#:** Scripts personalizados para manejo de errores y pre-procesamiento de datos.
- **Destino OLE DB:** Inserción optimizada en tablas de SQL Server.

## 📁 Estructura del Proyecto
- `/src`: Contiene el paquete `.dtsx`.
- `/sql`: Scripts de creación de tablas y limpieza.
