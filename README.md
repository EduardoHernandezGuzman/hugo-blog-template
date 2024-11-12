# Template de Blog con Hugo

Una plantilla minimalista y elegante para crear tu blog personal usando Hugo y el tema PaperMod. Perfecta para desarrolladores, escritores y creadores de contenido.

##  Inicio Rápido

### 1. Usar esta plantilla
- Haz clic en el botón "Use this template" en GitHub
- Dale un nombre a tu repositorio
- Clónalo en tu máquina local o ábrelo en GitHub Codespaces

### 2. Configuración Local
#### Instalar Hugo (si no lo tienes)
###### En Ubuntu/Debian:
```bash
sudo apt-get install hugo
```

##### En macOS:
```bash
brew install hugo
```

##### En Windows (con chocolatey):
```bash
choco install hugo
```

### 3. Ejecutar el Blog
#### En local:
```bash
hugo server -D
```

#### En GitHub Codespaces:

```bash
hugo server --baseURL="https://${CODESPACE_NAME}-1313.${GITHUB_CODESPACES_PORT_FORWARDING_DOMAIN}" --appendPort=false -D
```



##  Personalización

### 1. Configuración Básica
Edita el archivo config.toml:
```bash
title = "Tu Título"
theme = "PaperMod"

[params]
  author = "Tu Nombre"
  description = "Tu descripción"
  
[params.profileMode]
  enabled = true
  title = "Tu Nombre"
  subtitle = "Tu descripción corta"
  imageUrl = "https://github.com/tuusuario.png"
```

### 2. Crear posts
#### Crear un nuevo post
```bash
hugo new posts/mi-post.md
```
Estructura de un post:

```bash
---
title: "Mi Post"
date: 2024-01-20
draft: false
tags: ["tag1", "tag2"]
---

Contenido de tu post aquí...
```

## Páginas
Los archivos principales están en:

- content/posts/ - Tus posts del blog
- content/about.md - Página "Sobre Mí"
- static/ - Imágenes y archivos estáticos

## Contribuir
Las contribuciones son bienvenidas:

- Fork el proyecto
- Crea tu Feature Branch (git checkout -b feature/AmazingFeature)
- Commit tus cambios (git commit -m 'Add some AmazingFeature')
- Push a la Branch (git push origin feature/AmazingFeature)
- Abre un Pull Request

## Agradecimientos
- Hugo: [Hugo](https://gohugo.io/)
- PaperMod Theme: [PaperMod](https://github.com/adityatelange/hugo-PaperMod)

## Contacto

Para cualquier consulta o colaboración, puedes contactar al autor a través de:

- GitHub: [EduardoHernandezGuzman](https://github.com/EduardoHernandezGuzman)
