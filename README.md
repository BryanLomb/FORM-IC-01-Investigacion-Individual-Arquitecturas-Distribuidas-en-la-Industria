# FORM-IC-01 · Microservicios en Allegro

Investigación individual sobre la transición del monolito de Allegro a microservicios.

## Compilar el análisis

El archivo principal es `main.tex`. Se requiere una distribución TeX Live o MiKTeX con **pdfLaTeX**, **Biber** y los paquetes `babel` con soporte para español, `csquotes`, `geometry`, `graphicx`, `biblatex`, `biblatex-ieee` y `hyperref`.

Desde la raíz del repositorio, ejecuta:

```sh
pdflatex main.tex
biber main
pdflatex main.tex
pdflatex main.tex
```

El resultado es `main.pdf`. La bibliografía se carga desde `referencias.bib`; la captura de la fuente principal debe guardarse como `evidencias/allegro-anotada.png`. El espacio reservado para la imagen aparece si aún no está disponible. En la versión final, comprueba que el análisis y sus evidencias ocupen una sola página, además de la carátula y las referencias.
