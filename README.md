# 🧬 KNIME Workflow: BBDD_SOMNIUM

Este repositorio contiene el workflow de KNIME titulado **"BBDD_SOMNIUM"**, diseñado para el procesamiento y análisis de datos médicos de pacientes con trastornos del sueño.

---

## 📌 Objetivo del Workflow

Automatizar el pipeline de extracción, transformación y análisis de datos clínicos, combinando fuentes SQL Server, hojas de Excel y análisis en Power BI, siguiendo una arquitectura modular de datos.

---

## 🗂️ Estructura del Proyecto

mi-pipeline-knime/
├── BBDD_SOMNIUM.knwf ← Workflow principal de KNIME
├── .gitignore
└── README.md ← Este archivo

## ⚙️ Requisitos

- **KNIME Analytics Platform** (>= 4.7)
- Extensiones necesarias:
  - KNIME Database (Connector + Reader)
  - KNIME Excel Integration
  - KNIME Python Integration (si usas scripts)
- Conexión a base de datos SQL Server (credenciales locales)

---

## 🚀 Cómo ejecutar el workflow

1. Abre KNIME.
2. Ve a **File > Import KNIME Workflow...**
3. Selecciona el archivo `BBDD_SOMNIUM.knwf`.
4. Configura los nodos de conexión a base de datos y archivos locales.
5. Ejecuta cada sección (puedes usar nodos de metanodo o tags para dividir etapas).

---

## 🧱 Arquitectura del Pipeline


**Etapas del workflow:**

1. **Extracción** de datos clínicos.
2. **Transformación y limpieza** (nulos, formatos, codificación).
3. **Exportación** a Power BI (via archivo Excel o CSV).
4. **Análisis exploratorio** opcional dentro de KNIME.

---

## 🧠 Notas y mejores prácticas

- Asegúrate de no subir datos reales de pacientes: agrega filtros en `.gitignore`.
- Se recomienda usar entornos virtuales para scripts Python (si están integrados).
- Versión original: `Workflow_Original` (commit inicial).

---

## 📄 Licencia

Este proyecto está licenciado bajo MIT / uso interno. Personalízala según tus necesidades.

---

## ✍️ Autor

Carlos Raúl Ardila

mmmm
