# Cars-Leasing-Data-Analysis
# Sistema de Gestión de Leasing - Case Study 🚗💻

Este proyecto simula la arquitectura de base de datos para la gestión operativa de contratos de leasing y pagos en un entorno financiero automotriz.

## 🚀 Objetivo
Diseñar e implementar una base de datos relacional robusta que permita:
- Gestionar la información de clientes y flota de vehículos.
- Controlar contratos de leasing con integridad referencial.
- Analizar flujos de caja y estados de pago mediante SQL avanzado.

## 🛠️ Tecnologías utilizadas
- **SGBD:** MySQL
- **Modelado:** Diagrama Entidad-Relación (E/R) normalizado (3FN).
- **Herramientas:** DBeaver / MySQL Workbench.

## 📊 Capacidades del Proyecto
El sistema permite realizar análisis de negocio complejos, tales como:
1. **Reportes consolidados:** Cruce de datos entre clientes, vehículos y contratos mediante `INNER JOIN`.
2. **Análisis financiero:** Cálculo de recaudación total y segmentación por modelos mediante funciones de agregación (`SUM`, `GROUP BY`).
3. **Auditoría de riesgos:** Identificación de cuotas por encima de la media mediante subconsultas.

## 📂 Estructura del Repositorio
-  Definición de tablas y restricciones de integridad.
-  Set de datos de prueba (modelos BMW i4, X5, etc.).
-  Consultas de análisis de negocio.
