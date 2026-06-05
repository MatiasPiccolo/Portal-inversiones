# Portal de Inversiones — Dirección de Promoción y Desarrollo de Inversiones

Portal de informes y visualizaciones interactivas de la **Dirección de Promoción y Desarrollo de Inversiones**, dependiente de la Subsecretaría de Desarrollo Comercial y Promoción de Inversiones del **Ministerio de Producción, Ciencia e Innovación Tecnológica · PBA**.

---

## 🌐 Acceso al portal

| Sección | URL |
|---|---|
| Portal principal | [index.html](https://matiaspiccolo.github.io/Portal-inversiones/index.html) |
| Informe IED | [ied.html](https://matiaspiccolo.github.io/Portal-inversiones/ied.html) |
| Líneas de Crédito | [credito.html](https://matiaspiccolo.github.io/Portal-inversiones/credito.html) |
| Impulso al Comercio Bonaerense | [impulso.html](https://matiaspiccolo.github.io/Portal-inversiones/impulso.html) |
| Emprendé tu Comercio | [emprende.html](https://matiaspiccolo.github.io/Portal-inversiones/emprende.html) |
| Fenómenos Naturales | [fenomenos.html](https://matiaspiccolo.github.io/Portal-inversiones/fenomenos.html) |
| RIGI | [rigi.html](https://matiaspiccolo.github.io/Portal-inversiones/rigi.html) |

---

## 📂 Estructura del repositorio

### Páginas del portal
| Archivo | Descripción |
|---|---|
| `index.html` | Portada con navegación a todas las secciones |
| `ied.html` | Informe IED — flujos trimestrales por sector (2023–2025) |
| `credito.html` | Índice de líneas de crédito |
| `impulso.html` | Programa Impulso al Comercio Bonaerense — ediciones 2023, 2024 y 2025 |
| `emprende.html` | Programa Emprendé tu Comercio — ediciones 2024 y 2025 |
| `fenomenos.html` | Línea de crédito para afectados por fenómenos naturales |
| `rigi.html` | Régimen de Incentivos para Grandes Inversiones |

### Datos y scripts
| Archivo | Descripción |
|---|---|
| `Impulso.xlsx` | Base de datos de créditos otorgados (Impulso y Emprendé) |
| `Informe_IED_4to_2025.xlsx` | Datos de flujos de IED por sector y trimestre |
| `impulso1.R` | Script R — procesa y visualiza datos de Impulso 2023 |
| `impulso2.R` | Script R — procesa y visualiza datos de Impulso 2024 y 2025 |

### Mapas interactivos (generados por los scripts R)
| Archivo | Descripción |
|---|---|
| `mapa_interactivo_impulso1.html` | Mapa interactivo de créditos Impulso — edición 2023 |
| `mapa_interactivo_impulso2.html` | Mapa interactivo de créditos Impulso — ediciones 2024 y 2025 |
| `mapa_interactivo_RIGI_detallado.html` | Mapa interactivo de proyectos RIGI por provincia |

---

## 📊 Contenido por sección

### Informe IED
Análisis de flujos de Inversión Extranjera Directa en la industria manufacturera argentina para el período 2023–2025. Incluye:
- KPIs generales por año
- Gráfico de flujo trimestral con filtros por sector
- Gráfico de líneas con sectores destacados (Alimentos, Automotriz, Químicos)
- Tabla comparativa de acumulados anuales por sector
- Análisis desagregado por sector (Industria manufacturera disponible; Minería, Comercio, Bancos y Servicios próximamente)

### Líneas de Crédito
Tres programas de financiamiento productivo de la Provincia de Buenos Aires:

**Impulso al Comercio Bonaerense** — ediciones 2023, 2024 y 2025 con mapas interactivos por partido y KPIs de cada edición. Incluye comparador de ediciones lado a lado.

**Emprendé tu Comercio** — ediciones 2024 y 2025 con la misma estructura. Incluye comparador de ediciones.

**Fenómenos Naturales** — edición 2025 para afectados por eventos climáticos y desastres naturales.

### RIGI
Seguimiento del Régimen de Incentivos para Grandes Inversiones. Incluye:
- KPIs generales (proyectos totales, inversión comprometida, provincias y sectores)
- Mapa de distribución territorial
- Ranking de provincias con indicador de proyectos compartidos
- Tabla de proyectos con filtros por provincia, sector y estado
- Ficha detallada de cada proyecto con exportación a PDF

---

## 📦 Requisitos para correr los scripts R

```r
install.packages(c(
  "sf", "readxl", "tmap", "ggplot2", "ggiraph",
  "patchwork", "RColorBrewer", "scales", "tidyverse"
))
```

---

## 🎨 Diseño

El portal utiliza una paleta de colores institucional y tipografía **Encode Sans** (Google Fonts). Incluye modo oscuro persistente entre secciones y versión optimizada para impresión/PDF.

Paleta principal:
- Rosa: `#e72276`
- Violeta: `#826993`
- Azul: `#2f6485`
- Cyan: `#00aec3`

---

## 📅 Última actualización

4º trimestre 2025 — Dirección de Promoción y Desarrollo de Inversiones · PBA
