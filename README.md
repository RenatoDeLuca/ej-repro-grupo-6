# Template reporte reproducibilidad
Sitio publicado [**AQUÍ**](https://renatodeluca.github.io/ej-repro-grupo-6/)


Link al reporte [**AQUÍ**](https://data-soc.github.io/template-repro/)

Este repositorio contiene una plantilla para el reporte de reproducibilidad del Trabajo 1 del curso [Investigación Social Abierta](https://cienciasocialabierta.cl/2026/). La plantilla está diseñada para ser clonada y modificada por cada estudiante, siguiendo el protocolo [IPO](https://lisacoes.com/protocolos/a-ipo-rep/) (IInput-Processing-Output) y utilizando el formato Quarto.

<img src="https://lisacoes.com/protocolos/a-ipo-rep/ipo-hex.png" alt="IPO" width="220" />

## Working tree del proyecto

Este proyecto se organiza de la siguiente manera: 

<!-- WORKING_TREE_START -->
```text
ej-repro-grupo-6/
 |- .Rprofile
 |- .gitignore
 |- .vscode/
 |  |- settings.json
 |- README.html
 |- README.md
 |- README_files/
 |  |- libs/
 |  |  |- bootstrap/
 |  |  |  |- bootstrap-138a6193a3bd40baf1e627da441a4734.min.css
 |  |  |  |- bootstrap-icons.css
 |  |  |  |- bootstrap-icons.woff
 |  |  |  |- bootstrap.min.js
 |  |  |- clipboard/
 |  |  |  |- clipboard.min.js
 |  |  |- quarto-html/
 |  |  |  |- anchor.min.js
 |  |  |  |- popper.min.js
 |  |  |  |- quarto-syntax-highlighting-7f8f88aac4f3542376d5c11b86a4c14d.css
 |  |  |  |- quarto.js
 |  |  |  |- tabsets/
 |  |  |  |- tippy.css
 |  |  |  |- tippy.umd.min.js
 |- index.html
 |- index.pdf
 |- index.qmd
 |- input/
 |  |- bib/
 |  |  |- apa7.csl
 |  |  |- biblio.bib
 |  |- data/
 |  |  |- original/
 |  |  |- proc/
 |  |  |  |- proc_casen22.rds
 |  |- images/
 |  |  |- fig_2_palma_et_al_2025_original.png
 |  |  |- fig_5_palma_etal_2025.png
 |  |- original-code/
 |- libs/
 |  |- ocs.scss
 |- output/
 |  |- graphs/
 |  |  |- figura2_palmaetal2025.png
 |  |  |- figura5_palmaetal2025.png
 |  |- tables/
 |- processing/
 |  |- README-prod.md
 |  |- prod_analysis.Rmd
 |  |- prod_analysis.html
 |  |- prod_prep.Rmd
 |  |- prod_prep.html
 |- renv/
 |- renv.lock
 |  |- .gitignore
 |  |- activate.R
 |  |- settings.json
 |- scripts/
 |  |- update-working-tree.sh
```
<!-- WORKING_TREE_END -->

Este working tree incorpora las carpetas y archivos principales relevantes del repo (omite algunas) y se actualiza automáticamente al hacer commit mediante una github action que se encuentra definida en el archivo `.github/workflows/update-working-tree.yml`. El propósito de esta acción es mantener un registro actualizado de la estructura del proyecto, lo que facilita la navegación y organización de los archivos para los estudiantes.


