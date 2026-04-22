# Workshop de scRNA-seq 👾

Instructora: Dra. Evelia Coss, Posdoc del Dr. Federico Sánchez, LIIGH-UNAM

Clases para los alumnos de Maestría y Doctorado de X, Ciencias Genomicas de 6to semestre de la ENES, Juriquilla. 

Optativa X.

## Descripción

Este módulo consta de sesiones teóricas y prácticas impartidas de forma híbrida, que cubrirán aspectos básicos del tópico como:

-- Por llenar

Se ofrecerán presentaciones detalladas sobre el uso de programas clave, todos de código abierto, utilizando datos extraídos de bases de datos. Además, se introducirá el uso de scripts sencillos en Bash y R, con el objetivo de aprender los conceptos básicos de estos lenguajes para el análisis de datos transcriptómicos.

Les comparto el [plan de estudios](https://docs.google.com/spreadsheets/d/1E_V69JRrq7ZyMCPcRv3GBsTZy1ycfp5P-7KdlYx8f5c/edit?usp=sharing).

## Contenido 📌

- Clase 1. Introducción a RNA-seq de célula única (scRNA-seq) y control de calidad (11/03/2026)
- Clase 2. Control de calidad y Normalización con `Seurat` (18/03/2026)
- Clase 3. Selección de genes altamente variables, Reducción de dimensiones y clustering (25/03/2026)
- Clase 4. Identificación de genes marcadores (08/04/2026)
- Clase 5. Anotación de tipos celulares e Inferencia de trayectorias (15/04/2026)
- Clase 6. Comunicación celular (CellChat) (22/04/2026)

### Clase 1: Introducción a RNA-seq de célula única (scRNA-seq) y control de calidad

- Fecha: 11/03/2026
- Presentación: [Clase 1](https://eveliacoss.github.io/Workshop_scRNAseq_presentacion/Clase1_Intro_QC.html#1)

### Clase 2. Control de calidad y Normalización con `Seurat`

- Fecha: 18/03/2026
- Presentación: [Clase 2](https://eveliacoss.github.io/Workshop_scRNAseq_presentacion/Clase2_Normalizacion.html#1)
- Descarga el archivo: [Practica1.qmd](https://github.com/EveliaCoss/Workshop_scRNAseq_presentacion/blob/main/practica/Practica1.qmd)
- Visualización del reporte final: [Practica1](https://eveliacoss.github.io/Workshop_scRNAseq_presentacion/practica/Practica1.html)
  + 🌟 Checkpoint: [pbmc3k_tutorial.rds](https://drive.google.com/file/d/121V7fFNFKmuG5cD7ng_mYt3DMEGoFErw/view?usp=drive_link)

### Clase 3. Selección de genes altamente variables, Reducción de dimensiones y clustering

- Fecha: 25/03/2026
- Presentación: [Clase 3](https://eveliacoss.github.io/Workshop_scRNAseq_presentacion/Clase3_features.html#1)
- Descarga el archivo: [Practica2.qmd](https://github.com/EveliaCoss/Workshop_scRNAseq_presentacion/blob/main/practica/Practica2.qmd)
- Visualización del reporte final: [Practica2](https://eveliacoss.github.io/Workshop_scRNAseq_presentacion/practica/Practica2.html)
  + 🌟 Checkpoint: [pbmc3k_integrated.rds](https://drive.google.com/file/d/1D5BQAt-8x-eYQo2_6S5muEE4nbXMuL6d/view?usp=drive_link)
  
### Clase 4. Identificación de genes marcadores y Anotación de tipos celulares

- Fecha: 08/04/2026
- Presentación: [Clase 4](https://eveliacoss.github.io/Workshop_scRNAseq_presentacion/Clase4_Biomarkers_Anotacion.html)
- Descarga el archivo: [Practica3.qmd](https://github.com/EveliaCoss/Workshop_scRNAseq_presentacion/blob/main/practica/Practica3.qmd)
- Visualización del reporte final: [Practica3](https://eveliacoss.github.io/Workshop_scRNAseq_presentacion/practica/Practica3.html)
  + 🌟 Checkpoint: [pbmc3k_annotated.rds](https://drive.google.com/file/d/12SuvKiwChYNxuawaZH5UAhcDqx1IIspr/view?usp=drive_link)
  
### Clase 5. Expresión diferencial por condiciones 

- Fecha: 15/04/2026
- Descarga el archivo: [Practica4.qmd](https://github.com/EveliaCoss/Workshop_scRNAseq_presentacion/blob/main/practica/Practica4.qmd)
- Visualización del reporte final: [Practica4](https://eveliacoss.github.io/Workshop_scRNAseq_presentacion/practica/Practica4.html)
  + 🌟 Checkpoint: [variables_expression.RData](https://drive.google.com/file/d/11kZYI7w1FuwdmIKWJiu6throeKneovci/view?usp=sharing)

### Clase 6. Inferencia de trayectorias y Comunicación celular (CellChat)

- Fecha: 22/04/2026
- Presentación: [Clase 6](https://eveliacoss.github.io/Workshop_scRNAseq_presentacion/Clase5_DE_trayectoria.html)
- Materiales suplementarios:
  + [In-depth-NGS-Data-Analysis-Course](https://hbctraining.github.io/In-depth-NGS-Data-Analysis-Course/sessionIV/lessons/SC_clustering_analysis.html)
  + [Single Cell RNA-seq Analysis](https://nbisweden.github.io/workshop-scRNAseq/archive/2024/labs/seurat/seurat_01_qc.html)
  + [Trajectory Analysis using 10x Genomics Single Cell Gene Expression Data](https://www.10xgenomics.com/analysis-guides/trajectory-analysis-using-10x-Genomics-single-cell-gene-expression-data)
  + [Chapter 18 Trajectory Analysis](https://bioconductor.org/books/3.12/OSCA/trajectory-analysis.html)
  + [Single-cell network biology for resolving cellular heterogeneity in human diseases](https://www.nature.com/articles/s12276-020-00528-0)
  + [Trajectory inference using Slingshot](https://nbisweden.github.io/workshop-scRNAseq/labs/seurat/seurat_07_trajectory.html)
  + [Differential expression testing](https://satijalab.org/seurat/articles/de_vignette)
  + [Cell-Cycle Scoring and Regression](https://satijalab.org/seurat/articles/cell_cycle_vignette)  
  + [Differential expression methods](https://nbisweden.github.io/excelerate-scRNAseq/session-de/session-de-methods.html)
  + [Differential expression analysis](https://rnabio.org/module-08-scrna/0008/04/01/DE_analysis/)
  + [Introduction to Single-cell RNA-seq - ARCHIVED](https://hbctraining.github.io/scRNA-seq/lessons/pseudobulk_DESeq2_scrnaseq.html)
  + [Trajectory inference analysis: Slingshot](https://nbisweden.github.io/workshop-archive/workshop-scRNAseq/2020-01-27/labs/compiled/slingshot/slingshot.html)
  + [3_slingshot.md](https://github.com/NBISweden/single-cell_sib_scilifelab/blob/master/session-trajectories/3_slingshot.md)