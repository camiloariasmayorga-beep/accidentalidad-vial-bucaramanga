[README.md](https://github.com/user-attachments/files/26231274/README.md)# accidentalidad-vial-bucaramanga[Uploading README.m# 🚦 Análisis de Accidentalidad Vial en Bucaramanga (2012–2023)

**Google Data Analytics Professional Certificate — Capstone Case Study**
**Track:** Choose Your Own Dataset | **Herramienta:** Excel / Google Sheets

---

## 📋 Descripción del proyecto

Este caso de estudio analiza **39.193 registros de accidentes de tránsito** ocurridos en el municipio de Bucaramanga, Colombia, entre 2012 y 2023. El análisis fue realizado como proyecto final del curso **Google Data Analytics Professional Certificate** de Coursera.

El proyecto sigue el marco de análisis de datos de Google: **Ask → Prepare → Process → Analyze → Share → Act**.

---

## ❓ Pregunta de negocio

> **¿Cuáles son los patrones de accidentalidad vial en Bucaramanga entre 2012 y 2023, y qué factores (hora, comuna, tipo de vehículo) se asocian con accidentes de mayor gravedad?**

**Cliente simulado:** Secretaría de Movilidad de Bucaramanga  
**Audiencia:** Funcionarios de movilidad y planeación urbana

---

## 📂 Archivos del repositorio

| Archivo | Descripción |
|---------|-------------|
| `Analisis_Accidentalidad_Bucaramanga.xlsx` | Dataset limpio + 7 hojas de análisis con gráficas |
| `caso_estudio_accidentalidad_bucaramanga.docx` | Documento completo del caso de estudio (Ask→Act) |
| `README.md` | Este archivo |

---

## 🗂️ Fuente de datos

- **Dataset:** Accidentes de Tránsito — Municipio de Bucaramanga
- **Fuente:** [Datos Abiertos Colombia](https://www.datos.gov.co)
- **Entidad:** Agentes de Tránsito de Bucaramanga (DTB)
- **Período:** Enero 2012 – 2023
- **Registros:** 39.193 eventos | 24 columnas originales
- **Licencia:** Datos abiertos para uso público

---

## 🔍 Proceso de análisis

### 1. Ask — Definición del problema
Se definió la pregunta de negocio, los stakeholders (Secretaría de Movilidad, Alcaldía, Policía de Tránsito) y las métricas clave a analizar.

### 2. Prepare — Evaluación del dataset
Se verificó la integridad del dataset usando el criterio **ROCCC** (Reliable, Original, Comprehensive, Current, Cited). El dataset no presentó valores nulos en ninguna de sus 24 columnas.

### 3. Process — Limpieza de datos
- Estandarización de la columna `GRAVEDAD` (unificación de variantes textuales)
- Extracción de `HORA_NUM` desde el campo timestamp original
- Creación de columna `FRANJA_HORARIA` (Madrugada / Mañana / Tarde / Noche)
- Creación de columna `TOTAL_VEHICULOS` (suma de todos los tipos de vehículo por accidente)
- Limpieza de columnas `MES`, `DÍA` y `COMUNA` para eliminar prefijos numéricos
- Verificación de duplicados: 0 registros duplicados encontrados

### 4. Analyze — Hallazgos principales

| # | Hallazgo |
|---|----------|
| 1 | Los accidentes bajaron de **4.342 (2012)** a **2.220 (2022)**, con caída marcada en 2020 por COVID-19 |
| 2 | **5 comunas** concentran el **62%** de todos los accidentes (Cabecera del Llano, San Francisco, Oriental, Centro, La Concordia) |
| 3 | Las **motocicletas** tienen mayor proporción de accidentes fatales pese a estar en segundo lugar en frecuencia |
| 4 | La **franja 12h–17h** registra más accidentes (14.961), seguida por la mañana (12.354) |
| 5 | Los accidentes **nocturnos** (29.7% del total) presentan mayor proporción de heridos y muertos |

### 5. Share — Visualizaciones
El archivo Excel incluye 7 hojas de análisis con gráficos:
- 📈 Tendencia anual 2012–2023 (líneas)
- 🍩 Distribución por gravedad (torta)
- 📊 Top 10 comunas (barras apiladas)
- 🚗 Vehículos involucrados (barras horizontales)
- 📅 Accidentes por día de semana
- 🌙 Diurno vs. nocturno (barras 100% apiladas)
- 🕐 Franjas horarias (barras apiladas)

### 6. Act — Recomendaciones
1. Reforzar operativos en las 5 comunas críticas, especialmente en horario nocturno
2. Implementar campañas de seguridad vial dirigidas a motociclistas
3. Instalar controles de velocidad en Cabecera del Llano y San Francisco
4. Diseñar operativos nocturnos de control de alcoholemia y velocidad
5. Monitorear la tendencia post-pandemia para verificar sostenibilidad de la reducción

---

## 🛠️ Herramientas utilizadas

- **Microsoft Excel / Google Sheets** — Limpieza, análisis y visualización
- **Python (pandas)** — Exploración y validación inicial del dataset

---

## 👤 Autor

**Camilo Arias Mayorga**  
Google Data Analytics Professional Certificate — Coursera  
[LinkedIn](#) | [GitHub](https://github.com/camiloariasmayorga-beep)
d…]()

Análisis de accidentes de tránsito en Bucaramanga (2012–2023) 
