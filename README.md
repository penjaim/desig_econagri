## **Mapeo de la Desigualdad en las Economías Agrícolas**

### *Marco Teórico para el Instituto Municipal de Planeación de Penjamillo (IMPLAN)*

### Periodo 2025–2027

Vidal Mendoza Tinoco
2025

---

# Introducción

Las economías agrícolas constituyen el eje productivo central de municipios rurales como Penjamillo, donde cultivos como el maíz, sorgo y aguacate generan empleo, ingresos y encadenamientos productivos. Sin embargo, la evidencia internacional (Deininger & Squire, 1998; Barrett et al., 2019) muestra que los territorios agrícolas presentan fuertes desigualdades derivadas de variaciones en productividad, acceso a mercados, infraestructura, tenencia de la tierra y dinámicas de precios.

En México, la desigualdad agrícola se manifiesta espacialmente: localidades cercanas a corredores agroexportadores presentan altos ingresos, mientras que zonas con agricultura de subsistencia enfrentan bajos niveles de bienestar. Analizar esta desigualdad **desde una perspectiva territorial y econométrica** es indispensable para la planeación municipal.

Con fundamento en las atribuciones del IMPLAN —generación de información geoestadística (Art. 6-B-III), creación y dirección del Banco Municipal de Información (Art. 23-VI), elaboración de estudios técnicos y de identificación de zonas prioritarias (Art. 23-VII) del Reglamento del IMPLAN— se presenta este proyecto técnico-institucional de investigación.

Además, este estudio corresponde al segundo proyecto estratégico del *Plan de Innovación para el Desarrollo Municipal 2025–2027*, donde se establece que el objetivo es *“analizar la relación entre la producción agrícola y la desigualdad territorial mediante datos públicos y técnicas econométricas como Difference-in-Differences y correlación espacial”* .

Este documento se estructura con rigor académico y técnico, siguiendo el estilo metodológico del *Atlas de Desigualdad Espacial de Penjamillo* , y está listo para presentarse ante el IMPLAN, Cabildo y autoridades estatales.

---

# Justificación Técnica

La economía agrícola de Penjamillo es heterogénea: algunos ejidos y unidades de producción presentan alta rentabilidad, acceso a cadenas de exportación y tecnificación, mientras que otros mantienen sistemas de bajo rendimiento y alta vulnerabilidad climática. Esta heterogeneidad genera desigualdades espaciales en:

* ingreso agropecuario,
* acceso a infraestructura productiva,
* acceso a agua y tecnificación,
* productividad agrícola,
* rentabilidad por hectárea,
* participación en cadenas de valor,
* exposición a choques de precios agrícolas.

Estas desigualdades tienen implicaciones directas en oportunidades de desarrollo local, lo cual se alinea a los objetivos del IMPLAN, especialmente la elaboración de estudios estratégicos y programas de fortalecimiento económico (Art. 23 y Art. 24) .

Un diagnóstico territorial robusto permitirá:

* Identificar zonas agrícolas vulnerables.
* Evaluar si la dinámica agrícola aumenta o reduce desigualdad territorial.
* Comprender cómo choques de precios y rendimientos afectan el bienestar local.
* Detectar si actividades agrícolas de alto valor (ej. aguacate) generan efectos derrame o, por el contrario, desigualdad espacial.

---

# Marco Teórico

## 1. Desigualdad y desarrollo territorial

Autores como **Kanbur & Venables (2005)** y **Barca (2009)** destacan que la desigualdad territorial surge de diferencias persistentes en dotaciones productivas, conectividad e instituciones locales. En contextos rurales, la base agrícola puede amplificar estas brechas.

## 2. Economía agrícola y desigualdad

La literatura económica identifica que variaciones en productividad agrícola determinan ingresos rurales (Restuccia et al., 2008). La falta de acceso a mercados y tecnología perpetúa desigualdades espaciales (Barrett et al., 2019).

## 3. Choques de precios y desigualdad

Donaldson (2018) muestra que mejoras en conectividad reducen desigualdad regional; en contraste, choques positivos en precios agrícolas pueden aumentar desigualdad si sus beneficios se concentran en pocas zonas.

## 4. Econometría aplicada: Difference-in-Differences

Utilizada ampliamente en economía agrícola para medir efectos de mercados y políticas (Angrist & Pischke, 2009). En este proyecto se aplicará para distinguir dinámicas entre:

* municipios altamente agrícolas de Michoacán vs. no agrícolas;
* AGEB con agricultura comercial vs. de subsistencia.

## 5. Autocorrelación espacial

La desigualdad rural también debe evaluarse espacialmente mediante Moran’s I y LISA (Anselin 1995).

---

# Marco Normativo

(Con citas explícitas del Reglamento del IMPLAN) 

El proyecto se sustenta en los artículos siguientes:

* **Art. 6-B-III**: El IMPLAN debe *“generar la información geoestadística que se requiere y facilite el proceso de planeación”*.
* **Art. 23-VI**: Crear, actualizar y dirigir el *Banco Municipal de Información Estadística Básica*.
* **Art. 23-VII**: Elaborar estudios e identificar *zonas prioritarias de atención*, incluyendo productivas.
* **Art. 24-X**: Elaborar programas que fortalezcan actividades económicas y mejoren condiciones de vida.
* **Art. 7-I**: Mantener actualizado el Sistema Municipal de Información para generar estadísticas sobre hechos económicos.

Este marco obliga al IMPLAN a producir análisis como este: económico, territorial, estadístico y con enfoque de desigualdad.

---

# Preguntas de Investigación

1. ¿Cómo se distribuyen territorialmente la productividad agrícola y los ingresos agropecuarios en Penjamillo?
2. ¿Existen clusters espaciales de alta y baja productividad?
3. ¿La presencia de cultivos de alto valor (como aguacate) incrementa o reduce desigualdad territorial?
4. ¿Qué determinantes (infraestructura, acceso a agua, tamaño de parcela) explican las disparidades agrícolas?
5. ¿Los choques de precios agrícolas generan efectos heterogéneos entre localidades?

---

# Hipótesis

1. **H1:** Las localidades con agricultura comercial presentan mayores niveles de ingreso y productividad que las agrícolas de subsistencia.
2. **H2:** La actividad agroexportadora incrementa desigualdad territorial en el corto plazo.
3. **H3:** Acceso a infraestructura productiva reduce significativamente brechas intra-municipales.

---

# Metodología

## 1. Fuentes de Datos (todas públicas)

Del Plan de Innovación 2025–2027 :

* **SIAP (2003–2023):** Producción agrícola municipal.
* **INEGI Censos Económicos 2019:** productividad y empleo agrícola.
* **BIE (INEGI):** precios, empleo y variables económicas.
* **FAO:** precios internacionales agrícolas.
* **Censo 2020:** infraestructura y características territoriales.
* **Marco Geoestadístico INEGI**: AGEB y localidades.

## 2. Variables clave

* Rendimiento (ton/ha) por cultivo.
* Ingreso agrícola estimado.
* Uso de suelo agrícola vs. pecuario.
* Acceso a agua (pozos, riego).
* Infraestructura productiva (tractor, maquinaria).
* Precios agrícolas (nacionales e internacionales).

## 3. Análisis descriptivo territorial

Mapas temáticos por AGEB/localidad:

* productividad,
* estructura agrícola,
* ingreso estimado.

## 4. Autocorrelación espacial

Aplicación de:

* **Moran’s I**
* **LISA** (HH, LL, HL, LH)

## 5. Modelos econométricos

### 5.1 Difference-in-Differences (DID)

Comparación entre:

* AGEB con agricultura comercial (tratamiento),
* AGEB con agricultura de subsistencia (control).

Modelo base:
$$
Y_{it} = \alpha + \beta(T_i \times Post_t) + \gamma X_{it} + \epsilon_{it}
$$

### 5.2 Modelos espaciales

* SAR
* SEM
* SDM

### 5.3 Regresiones GWR

Para identificar variaciones espaciales en los determinantes de productividad.

---

# Técnicas Computacionales y Geoespaciales

* Procesamiento en Python/R (tidyverse, sf, spdep).
* Modelos espaciales (spatialreg, spdep).
* GWR (GWmodel).
* Paneles DID (fixest, plm).
* Teledetección opcional (NDVI con Landsat).

---

# Cronograma 2025–2027

| Etapa                                            | Periodo             | Actividades                                                       |
| ------------------------------------------------ | ------------------- | ----------------------------------------------------------------- |
| Preparación institucional e integración de datos | Nov 2025 – Ene 2026 | Marco teórico; descarga, depuración y normalización de SIAP/INEGI |
| Diagnóstico agrícola territorial                 | Ene – Mar 2026      | Mapas, indicadores agrícolas, clusters espaciales                 |
| Modelos econométricos                            | Mar – Jul 2026      | DID, SAR/SEM, GWR                                                 |
| Redacción del informe                            | Ago – Dic 2026      | Capítulos, anexos, mapas                                          |
| Publicación                                      | Ene – Abr 2027      | PDF, dashboards                                                   |
| Evaluación final                                 | May – Jul 2027      | Integración al Banco Municipal de Información                     |

---

# Beneficios para el Ayuntamiento

1. **Focalización de inversión pública rural.**
2. **Argumentos técnicos para obras productivas (pozos, caminos, riego).**
3. **Justificación para gestión de recursos estatales y federales.**
4. **Complemento directo del Atlas de Desigualdad.**
5. **Cumplimiento normativo del IMPLAN (Arts. 6, 23, 24).**
6. **Integración de un sistema agrícola municipal para el Banco de Información.**

---

# Resultados Esperados

* Mapa municipal de desigualdad agrícola.
* Base de datos geoespacial unificada.
* Modelos econométricos reproducibles.
* Identificación de zonas agrícolas prioritarias.
* Recomendaciones de política pública.
* Reporte técnico final 2027.

---

# Conclusiones

El *Mapeo de la Desigualdad en las Economías Agrícolas* representa un instrumento estratégico para el Ayuntamiento y para el IMPLAN. Aporta un diagnóstico profundo del territorio agrícola, permite priorizar zonas vulnerables y fortalece la planeación basada en evidencia, cumpliendo con el Reglamento del IMPLAN y los objetivos del Plan de Innovación 2025–2027.

Su realización no solo incrementa la capacidad técnica municipal, sino que genera una herramienta institucional de largo plazo para monitorear desigualdades productivas, orientar inversión pública y mejorar el bienestar rural.

---

# Bibliografía

* Angrist, J. & Pischke, J. (2009). *Mostly Harmless Econometrics*.
* Anselin, L. (1995). *Local Indicators of Spatial Association*.
* Barca, F. (2009). *An Agenda for a Reformed Cohesion Policy*.
* Barrett, C. et al. (2019). *Agricultural Development and Poverty Reduction*.
* Deininger, K. & Squire, L. (1998). *Inequality and Growth*.
* Donaldson, D. (2018). *Railroads of the Raj*.
* Restuccia, D. et al. (2008). *Agricultural Productivity and Development*.
* SIAP, INEGI, BIE, FAO datasets.
