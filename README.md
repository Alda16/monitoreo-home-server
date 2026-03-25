# Monitoreo de la Infraestructura de un Servidor Casero (SLA & Latencia)

Este proyecto consiste en la implementación de una arquitectura de observavilidad para un servidor personal basado en **Ubtunu Server** y **Docker**, visualizando métricas críticas en **Power BI**.

## Tecnologías 
* **SO:** Ubuntu Server 24.04 LTS (Homelab).
* **Containerización:** Docker & Portainer.
* **Monitoreo:** Uptime Kuma (SQLite DB).
* **BI & Data:** Power BI Desktop + Excel (Proceso ETL).

## Dashboard de Observavilidad 
El reporte final permite monitorear: 
1.  **SLA (Service Level Agreement):** Porcentaje de disponibilidad de servicios críticos (Nextcloud).
2.  **Latencia Histórica (ms):** Análisis de rendimiento y picos de demanda.
3.  **Análisis de Tendencias:** Correlación entre el uso de recursos y tiempos de respuesta.

## Notas Finales
Este proyecto se hizo mediante datos reales proporcionados por mi servidor personal, el proceso de ETL y su posterior presentación en **Power BI** fueron hechos con una previa investigación sobre estos conceptos. Ádemas de otros conceptos no utilizados en este proyecto como el modelo con **DAX (Data Analysis Expressions)** y el **estudio de la limpieza de datos (Unix Timestamp a Fecha/Hora)**.