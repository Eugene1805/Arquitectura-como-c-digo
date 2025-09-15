# Descripción de la Arquitectura de Software
Este repositorio contiene la documentación de la arquitectura del sistema. ..
## Objetivo
Aprender a trabajar con documentación técnica usando un flujo *docs-as-code*:
- Texto plano con **AsciiDoc** .
- Control de versiones con **Git/GitHub o GitLab**.
- Publicaciön automåtica de HTML y PDF con **CI/CD**.
- Inclusiön de diagramas creados en **Enterprise Architect**.
## Estructura del proyecto
- docs/ -> Documentaciön en AsciiDoc
- images/ -> Diagramas exportados desde EA
- build/ -> Salida generada (ignorada en Git)
 
## Requisitos
- Ruby (con Asciidoctor y Asciidoctor PDF instalados) .
- VS Code con el plugin [AsciiDoc by Asciidoctor] .
## Compilación local (bash)
- asciidoctor -D build docs/indice . adoc
- asciidoctor-pdf -o build/ indice.pdf docs/indice.adoc