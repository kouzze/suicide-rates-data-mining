# Suicide Rates and Economy Indicators

## Descripción del Proyecto
Este estudio analiza la relación entre tasas de suicidio y diversos indicadores económicos, como la tasa de inflación y el PIB per cápita. El análisis incluye visualizaciones gráficas y técnicas de reducción de dimensionalidad, como PCA (Análisis de Componentes Principales) y Análisis Factorial, para identificar patrones y correlaciones relevantes.

## Objetivos del Estudio
1. Visualizar y entender la distribución de las tasas de suicidio y los indicadores económicos.
2. Identificar posibles relaciones entre factores económicos y tasas de suicidio.
3. Aplicar PCA y Análisis Factorial para reducir la dimensionalidad y encontrar patrones subyacentes.

## Contenido del Análisis

### 1. Visualizaciones
- **Distribución de Variables:** Histogramas para entender la distribución de cada indicador.
- **Diagramas de Dispersión:** Relación entre "InflationRate" y "DeathRatePer100k", y entre "GDPPercapita" y "DeathRatePer100k".
- **Boxplots:** Visualización de la variabilidad de las tasas de suicidio en función de diferentes indicadores económicos.

### 2. Análisis Estadístico
- **PCA (Análisis de Componentes Principales):** Reducción de dimensionalidad para identificar componentes principales que expliquen la mayor variabilidad de los datos.
- **Análisis Factorial:** Identificación de factores comunes que influyen en las tasas de suicidio y los indicadores económicos.

## Tecnologías Utilizadas
- **Lenguaje:** Python  
- **Librerías:**
  - `pandas` para el manejo de datos
  - `numpy` para cálculos matemáticos
  - `matplotlib` y `seaborn` para visualizaciones
  - `scikit-learn` para PCA
  - `factor-analyzer` para el Análisis Factorial

## Estructura del Proyecto
```
Suicide-Rates-Economy-Analysis/
├── data/
│   └── dataset.csv          # Dataset utilizado
├── visuals/
│   └── figures/             # Imágenes generadas
├── notebooks/
│   └── analysis.ipynb       # Notebook principal con el análisis
└── README.md                # Este archivo
```

## Instrucciones para Ejecutar el Proyecto
1. Clona el repositorio:
   ```bash
   git clone https://github.com/tu-usuario/suicide-economy-analysis.git
   ```
2. Instala las dependencias:
   ```bash
   pip install -r requirements.txt
   ```
3. Abre el notebook y ejecuta las celdas:
   ```bash
   jupyter notebook notebooks/analysis.ipynb
   ```

## Contribuciones
Las contribuciones son bienvenidas. Si deseas mejorar el código o agregar nuevas visualizaciones, por favor realiza un fork del repositorio y envía un pull request.

## Licencia
Este proyecto está licenciado bajo la licencia **MIT**.

---

*Este proyecto fue desarrollado como parte de un estudio académico sobre la relación entre economía y salud mental.*

