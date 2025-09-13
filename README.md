# Desafío Práctico 1 - Datawarehouse y Minería de Datos  
**Materia:** DMD941 G01T  
**Docente:** MG. Karens Medrano  
**Estudiante:** Luis José Cruz Martínez - CM170741 

---

## 📌 Descripción del proyecto  
Este proyecto consiste en el desarrollo de un flujo de integración de datos con **SQL Server Integration Services (SSIS)**.  
El objetivo principal es consolidar la información de facturación del servicio de **roaming** de una compañía telefónica que opera en **Centroamérica**, utilizando como fuentes tres bases de datos en SQL Server (Costa Rica, Honduras y Guatemala).  

Se implementaron procesos de **extracción, transformación y carga (ETL)** para generar reportes en Excel que sirvan como apoyo a la toma de decisiones comerciales y operativas.  

---

## 🎯 Objetivos
- Extraer datos de las tres bases SQL Server.
- Transformar y validar la información (limpieza, normalización y agregaciones).
- Consolidar la facturación por país y por tipo de cliente.
- Generar reportes en formato Excel de manera clara y precisa.
- Documentar cada paso del proceso y versionar el proyecto con Git.  

---

## 📊 Resultados generados
1. **Consolidado de facturación por país**  
   Archivo de Excel que muestra:
   - Nombre del país  
   - Número total de ventas  
   - Monto total facturado  

2. **Consolidado de ventas por tipo de cliente**  
   Archivo de Excel que muestra:
   - Tipo de cliente  
   - Número total de ventas  
   - Monto total facturado  

---

## 🛠️ Tecnologías utilizadas
- **SQL Server**  
- **Visual Studio** 
- **SQL Server Integration Services (SSIS)**  
- **Git + GitHub**  

---
 
## 📎 Estructura del repositorio

    📦 DesafioPractico1_CM170741
        
    ├── 📂 SolucionDesafioPractico1 # Proyecto SSIS en Visual Studio
    │    └── 📂DesafioPractico1_CM170741
    │    └── 📄SolucionDesafioPractico1.sln
    ├── 📄 db_costarica.sql # Script db_roaming_costarica
    ├── 📄 db_guatemala.sql # Script db_roaming_guatemala
    ├── 📄 db_honduras.sql # Script db_roaming_honduras
    ├── 📄 ConsolidadoFacturacionPais.xlsx # Reporte por país
    ├── 📄 ConsolidadoFacturacionTipoCliente.xlsx # Reporte por tipo de cliente
    ├── 📄 .gitignore # Configuración de archivos ignorados
    ├── 📄 .gitattributes # Configuración de Git
    └── 📄 notes.txt # Notas del desarrollo
    └── 📄 README.md # Presentación 


🔗 [GitHub - Desafío Práctico 1](https://github.com/luisjosecruz/DesafioPractico1_CM170741)  

## 🚀 Ejecutar el proyecto
1. Cargar las bases de datos ejecutando los scripts `db_costarica.sql`, `db_guatemala.sql` y `db_honduras.sql`.  
2. Abrir la solución en Visual Studio desde la carpeta `SolucionDesafioPractico1`.  
3. Configurar las conexiones OLE DB a las bases de datos.  
4. Ejecutar el paquete de datos.  
5. Verificar los resultados en los archivos Excel:  
   - `ConsolidadoFacturacionPais.xlsx`  
   - `ConsolidadoFacturacionTipoCliente.xlsx`  


## 📝 Conclusiones
El proyecto cumple con todos los requisitos planteados en el enunciado:  
- La información fue consolidada en un único flujo de datos, optimizando el proceso ETL.  
- Se garantizó la integridad de los datos y la precisión de las consultas.  
- Los resultados están documentados y respaldados en este repositorio mediante el uso de Git.  