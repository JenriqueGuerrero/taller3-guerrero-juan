# Herpetofauna del Caribe Colombiano — Análisis Exploratorio

Repositorio reproducible del **Taller 3** del curso *20953 · Análisis de Datos
Biológicos bajo R* (Universidad del Atlántico). Contiene un documento [Quarto](https://quarto.org)
que explora 60 registros de herpetofauna —reptiles y anfibios— recolectados en el
Caribe colombiano durante 2023.

## Contenido del análisis

- Carga y exploración del dataset (`dim`, `head`, `str`).
- **Gráfico 1:** número de registros por ecosistema.
- **Gráfico 2:** longitud corporal (SVL) según clase taxonómica.
- Reflexiones sobre reproducibilidad y ciencia abierta.

## Estructura del repositorio

```
taller3-guerrero-juan/
├── taller3_guerrero_juan.qmd    ← documento Quarto principal
├── taller3_guerrero_juan.html   ← informe renderizado
├── datos/
│   └── herpetofauna_caribe_listo.csv
└── README.md
```

## Datos

`datos/herpetofauna_caribe_listo.csv` — 60 registros y 21 variables (taxonomía,
ubicación, ecosistema, medidas morfométricas y estado UICN) de herpetofauna de los
departamentos de Atlántico, Magdalena y Córdoba.

## Cómo reproducir

1. Clonar el repositorio y abrir `taller3-guerrero-juan.Rproj` en RStudio.
2. Tener instalados R y Quarto.
3. Abrir `taller3_guerrero_juan.qmd` y pulsar **Render** para regenerar el HTML.

## Autor

Juan Enrique Guerrero Guerrero — Programa de Biología, Facultad de Ciencias Básicas.
