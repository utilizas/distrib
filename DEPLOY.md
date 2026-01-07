# 📦 Despliegue y reproducibilidad  

Este documento describe los procedimientos de despliegue en **GitHub Pages**, **Vercel** y **Netlify**, así como los requisitos para reproducir el entorno localmente.  

# 📦 Deployment and Reproducibility

This document describes the deployment procedures for **GitHub Pages**, **Vercel**, and **Netlify**, as well as the requirements for reproducing the environment locally.

---

## 🚀 Despliegue / Deployment

## 1. GitHub Pages

**ES:**  
El repositorio está configurado para desplegar automáticamente el sitio mediante *GitHub Actions*. No se requiere intervención manual salvo cambios en la configuración del workflow.

**EN:**  
The repository is configured to automatically deploy the site using *GitHub Actions*. No manual intervention is required unless the workflow configuration is modified.

---

## 2. Vercel

### Despliegue rápido / Quick deploy

**ES:**  
Puedes clonar y desplegar el proyecto directamente desde Vercel.  

**EN:**  
You can clone and deploy the project directly from Vercel.

Deploy with Vercel (vercel.com in Bing) [(bing.com in Bing)](https://www.bing.com/search?q="https%3A%2F%2Fwww.bing.com%2Fsearch%3Fq%3D%2522https%253A%252F%252Fvercel.com%252Fnew%252Fclone%253Frepository-url%253Dhttps%253A%252F%252Fgithub.com%252Fdistribia%252Fdistribia%2522")

### CLI

```bash
# ES: Instalación
# EN: Installation
npm i -g vercel

# ES: Despliegue
# EN: Deployment
vercel --prod
```

### Configuración (`vercel.json`)  
### Configuration (`vercel.json`)

```json
{
  "buildCommand": "quarto render el_giro_cognitivo.qmd",
  "outputDirectory": "_site",
  "installCommand": "npm install"
}
```

---

## 3. Netlify

### Despliegue rápido / Quick deploy

Deploy to Netlify (app.netlify.com in Bing) [(bing.com in Bing)](https://www.bing.com/search?q="https%3A%2F%2Fwww.bing.com%2Fsearch%3Fq%3D%2522https%253A%252F%252Fapp.netlify.com%252Fstart%252Fdeploy%253Frepository%253Dhttps%253A%252F%252Fgithub.com%252Fdistribia%252Fdistribia%2522")

### CLI

```bash
# ES: Instalación
# EN: Installation
npm install -g netlify-cli

# ES: Despliegue
# EN: Deployment
netlify deploy --prod
```

### Configuración (`netlify.toml`)  
### Configuration (`netlify.toml`)

```toml
[build]
  command = "quarto render el_giro_cognitivo.qmd"
  publish = "_site"

[build.environment]
  QUARTO_VERSION = "1.4"
```

---

# 🔁 Reproducibilidad / Reproducibility

## Requisitos / Requirements

**ES:**  
- R ≥ 4.0  
- Quarto ≥ 1.4  
- Paquetes R: `tidyverse`, `ggplot2`, `ggrepel`, `knitr`, `kableExtra`, `scales`

**EN:**  
- R ≥ 4.0  
- Quarto ≥ 1.4  
- Required R packages: `tidyverse`, `ggplot2`, `ggrepel`, `knitr`, `kableExtra`, `scales`

---

## Renderizado local / Local rendering

```bash
# ES: Clonar repositorio
# EN: Clone repository
git clone https://github.com/distribia/distribia.git
cd distribia

# ES: Instalar dependencias R
# EN: Install R dependencies
Rscript -e "install.packages(c('tidyverse', 'ggplot2', 'ggrepel', 'knitr', 'kableExtra', 'scales'))"

# ES: Renderizar documento
# EN: Render document
quarto render el_giro_cognitivo.qmd
```

---

# 🗂️ Notas adicionale

- Los despliegues en Vercel y Netlify son independientes y pueden usarse como entornos alternativos.  
- La carpeta `_site` contiene el sitio generado y no debe editarse manualmente.  
- Para cambios en el flujo de despliegue, se recomienda abrir un *pull request*.


# 🗂️ Additional notes

- Deployments on Vercel and Netlify are independent and can be used as alternative environments.  
- The `_site` directory contains the generated site and should not be edited manually.  
- For changes to the deployment workflow, please open a pull request.

---

