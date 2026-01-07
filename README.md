# La inteligencia distribuida
## Cómo los agentes artificiales transformarán la vida, el trabajo y el conocimiento

[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
[![Quarto](https://img.shields.io/badge/Made%20with-Quarto-blue.svg)](https://quarto.org/)
[![R](https://img.shields.io/badge/R-%3E%3D4.0-276DC3.svg)](https://www.r-project.org/)
[![DOI](https://img.shields.io/badge/DOI-10.5281%2Fzenodo-blue.svg)](https://zenodo.org/10.5281/zenodo.18172798)
[![Deploy on Vercel](https://img.shields.io/badge/Vercel-distribia-black?logo=vercel)](https://distrib-two.vercel.app/)
[![Deploy on Netlify](https://img.shields.io/badge/Netlify-distribia-00C7B7?logo=netlify)](https://distribia.netlify.app)
[![GitHub](https://img.shields.io/badge/GitHub-distribia-181717?logo=github)](https://github.com/distribia)

---

## Resumen

Esta monografía presenta un análisis detenido del impacto transformador de la inteligencia artificial generativa y los agentes artificiales en diversos dominios de actividad. Desde una perspectiva interdisciplinar que conecta con diversas fases de los estudios CTS, el trabajo examina los fundamentos técnicos de los grandes modelos de lenguaje, sus aplicaciones en medicina, investigación científica, educación y producción creativa, así como los riesgos asociados: ciberseguridad, desinformación, transformaciones laborales y gobernanza algorítmica. El documento integra evidencia empírica de fuentes académicas revisadas, sintetiza desarrollos de marcos regulatorios emergentes e incorpora visualizaciones de datos reproducibles mediante código R. Destinado a investigadores, estudiantes de posgrado y profesionales, el texto busca un equilibrio entre rigor analítico y claridad expositiva que facilite la comprensión de ideas y conceptos sin presuponer una formación técnica altamente especializada. El objetivo es proporcionar herramientas conceptuales, perspectiva sustentada en evidencia y casos relevantes para contribuir a una evaluación crítica de aplicaciones, desarrollos y tendencias que no encajan en los estereotipos simplificadores tecno-optimistas ni catastrofistas.

---

## Palabras clave

`inteligencia artificial generativa` · `inteligencia artificial agencial` · `grandes modelos de lenguaje` · `gobernanza algorítmica` · `estudios CTS` · `ética de la IA` · `autonomía cognitiva`

---

## Estructura del documento

```
📚 La Inteligencia Distribuida
│
├── 🔧 PARTE I: Fundamentos
│   ├── Arquitecturas y principios de la IA generativa
│   └── Entrenamiento, alineación y emergencia
│
├── 🔬 PARTE II: Aplicaciones
│   ├── IA en investigación científica
│   ├── IA en medicina y salud
│   ├── IA en educación
│   └── IA en producción creativa y programación
│
├── ⚠️ PARTE III: Riesgos y desafíos
│   ├── Ciberseguridad y desinformación
│   ├── Sistemas autónomos y armamento
│   ├── Impacto en el mercado laboral
│   └── Regulación y gobernanza
│
└── 🔮 PARTE IV: Perspectivas
    ├── Estudios de caso
    ├── Escenarios prospectivos
    └── Reflexiones finales
```

---

## Reproducibilidad:

- **R** ≥ 4.0
- **Quarto** ≥ 1.4
- Paquetes R: `tidyverse`, `ggplot2`, `ggrepel`, `knitr`, `kableExtra`, `scales`


### Fuentes de datos

Las visualizaciones incluidas provienen de:
- Bases de datos bibliográficas (PubMed, Web of Science, ScienceDirect)
- Repositorios académicos (arXiv)
- Informes institucionales (Stanford HAI AI Index, NIST, EU)
- Fuentes públicas documentadas

Cuando se indica explícitamente, algunas figuras se basan en simulaciones ilustrativas o proyecciones por extrapolación de datos disponibles.

---

## Citación

```bibtex
@misc{moreno2026inteligencia,
  author       = {Moreno-Mu{\~n}oz, Miguel},
  title        = {La inteligencia distribuida: c{\'o}mo los agentes artificiales transformar{\'a}n la vida, el trabajo y el conocimiento (v1.2026)},
  year         = {2026},
  doi          = {10.5281/zenodo.18172798},
  url          = {https://doi.org/10.5281/zenodo.18172798},
  publisher    = {Zenodo - CERN Research Repository},
  note         = {Desplegado en Vercel: https://distrib-two.vercel.app/ \\
                  y en Netlify: https://distribia.netlify.app/}
}
```

**Cita sugerida**: 

Moreno-Muñoz, M. (2026). *La inteligencia distribuida: cómo los agentes artificiales transformarán la vida, el trabajo y el conocimiento*. Universidad de Granada. Zenodo - CERN Research Repository. <https://doi.org/10.5281/zenodo.18172798>

---

## Proyecto asociado

Este trabajo recoge resultados de investigación derivados del proyecto:

> **AUTAI - PID2022-137953OB-I00**  
> *Inteligencia artificial y autonomía humana. Hacia una ética para la protección y la mejora de la autonomía en sistemas recomendadores, robótica social y realidad virtual*
>
> Ministerio de Ciencia e Innovación · Gobierno de España  
> Proyectos de Generación de Conocimiento 2022

[![Proyecto AUTAI](https://img.shields.io/badge/Proyecto-AUTAI-red)](https://produccioncientifica.ugr.es/proyectos/662100/detalle)

---

## Autor

**Miguel Moreno**  
Universidad de Granada

[![ORCID](https://img.shields.io/badge/ORCID-0000--0002--0746--9587-green?logo=orcid)](https://orcid.org/0000-0002-0746-9587)
[![ROR](https://img.shields.io/badge/ROR-UGR-orange)](https://ror.org/04njjy449)

---

## Licencia

Este trabajo se distribuye bajo la licencia **CC BY-NC-SA 4.0** ([Creative Commons Atribución–NoComercial–CompartirIgual 4.0 Internacional](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.es)).

[![CC BY-NC-SA 4.0](https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

Usted es libre de:
- **Compartir** — copiar y redistribuir el material en cualquier medio o formato
- **Adaptar** — remezclar, transformar y construir a partir del material

Bajo los siguientes términos:
- **Atribución** — Debe dar crédito de manera adecuada
- **NoComercial** — No puede usar el material con fines comerciales
- **CompartirIgual** — Si remezcla, transforma o crea a partir del material, debe distribuir su contribución bajo la misma licencia

---

## Versión

**v1.0** · Enero 2026

---

<p align="center">
  <img src="https://img.shields.io/badge/Universidad%20de%20Granada-Filosofía-darkred" alt="UGR Filosofía">
  <img src="https://img.shields.io/badge/Formato-Quarto%20HTML-blue" alt="Quarto HTML">
  <img src="https://img.shields.io/badge/Código-R-276DC3" alt="R Code">
</p>
