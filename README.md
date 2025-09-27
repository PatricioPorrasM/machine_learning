# Machine Learning - Quarto Report Project

Este proyecto contiene un reporte desarrollado en Quarto que demuestra conceptos básicos de análisis de datos y visualización utilizando Python.

## 📋 Descripción

El proyecto incluye un documento Quarto (`index.qmd`) que genera un reporte HTML interactivo con:

- Ejemplo básico de bucles en Python
- Análisis exploratorio del dataset de automóviles usando `vega_datasets`
- Visualizaciones interactivas con Altair
- Gráficos de dispersión con tooltips y funcionalidad de zoom/brush

## 🛠️ Tecnologías Utilizadas

- **Quarto**: Framework de publicación científica y técnica
- **Python**: Lenguaje de programación principal
- **Altair**: Biblioteca de visualización estadística
- **Vega-datasets**: Conjunto de datos de ejemplo
- **HTML**: Formato de salida del reporte

## 📁 Estructura del Proyecto

```
Machine_Learning/
├── .venv-13/           # Entorno virtual de Python
├── .vscode/            # Configuración de VS Code
├── index_files/        # Archivos generados por Quarto
├── index.qmd           # Archivo fuente de Quarto
├── index.html          # Reporte generado
├── requirements.txt    # Dependencias de Python
└── README.md           # Este archivo
```

## 🚀 Requisitos Previos

- Python 3.x
- Quarto CLI
- pip (para instalación de dependencias)

## 📦 Instalación

1. Clona o descarga este repositorio
2. Activa el entorno virtual:
   ```bash
   .venv-13\Scripts\activate
   ```
3. Instala las dependencias desde el archivo requirements.txt:
   ```bash
   pip install -r requirements.txt
   ```

## 🎯 Uso

Para generar el reporte HTML:

```bash
quarto render index.qmd
```

El archivo `index.html` se generará automáticamente y podrás abrirlo en tu navegador web.

## 📊 Contenido del Reporte

El reporte incluye:

1. **Ejemplo de programación**: Bucle simple que imprime elementos numerados
2. **Carga de datos**: Utilización del dataset de automóviles de vega_datasets
3. **Exploración de datos**: Información básica sobre el dataset
4. **Visualizaciones interactivas**: Gráficos de dispersión que muestran la relación entre millas por galón y caballos de fuerza

## 👤 Autor

**PATRICIO PORRAS**

## 📅 Fecha

2025-09-25

## 🔧 Desarrollo

Este proyecto utiliza:
- Quarto para la generación de documentos
- Python para análisis de datos
- Altair para visualizaciones interactivas
- VS Code como entorno de desarrollo

## 📝 Notas

- El proyecto genera visualizaciones interactivas que permiten zoom y selección
- Los gráficos incluyen tooltips informativos
- El entorno virtual `.venv-13` contiene todas las dependencias necesarias