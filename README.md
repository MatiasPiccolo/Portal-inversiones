# Portal Dirección de Inversiones

Este repositorio contiene informes, visualizaciones interactivas de los créditos otorgados por el programa **Impulso al Comercio Bonaerense** y el programa **Emprendé tu Comercio** en diferentes etapas; y finalmente un reporte del RIGI.

---

## 📍 Informe

- [Portal Principal](https://matiaspiccolo.github.io/Portal-inversiones/index.html)
- [Informe IED](https://matiaspiccolo.github.io/Portal-inversiones/ied.html)
- [Líneas de Crédito](https://matiaspiccolo.github.io/Portal-inversiones/credito.html)
- [RIGI](https://matiaspiccolo.github.io/Portal-inversiones/rigi.html)
---

## 📂 Archivos incluidos

- `Impulso.xlsx`: Base de datos de créditos (usada en ambos mapas)
- `impulso1.R`: Script R para procesar y visualizar los datos de 2023
- `impulso2.R`: Script R para procesar y visualizar los datos de 2024 y 2025
- `mapa_interactivo_impulso1.html`: Mapa interactivo de 2023
- `mapa_interactivo_impulso2.html`: Mapa interactivo de 2024 y 2025

---

## 📦 Requisitos para correr los scripts

Paquetes necesarios en R:

```r
install.packages(c("sf", "readxl", "tmap", "ggplot2", "ggiraph", "patchwork", "RColorBrewer", "scales", "tidyverse"))
