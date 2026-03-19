---
name: github-profile-optimizer
description: >
  Optimiza, rediseña y crea perfiles de GitHub profesionales para desarrolladores y estudiantes de ingeniería.
  USAR SIEMPRE que el usuario diga "mejora mi GitHub", "cómo se ve mi perfil de GitHub", "hazme un README para GitHub",
  "quiero mejorar mi GitHub", "optimiza mi perfil", "estructura de GitHub profesional", "cómo hacer mi GitHub atractivo",
  "perfil de GitHub para conseguir trabajo", "README de GitHub", "cómo me ven en GitHub", o cuando comparta
  una captura de pantalla de su perfil de GitHub y pregunte cómo mejorarlo. También activar para frases como
  "quiero que mi GitHub se vea profesional", "qué le falta a mi GitHub", "badges para GitHub", "estadísticas de GitHub".
  Produce: análisis del estado actual + README.md completo y listo para copiar + guía de mejoras prioritarias.
---

# GitHub Profile Optimizer

Skill especializado en transformar perfiles de GitHub genéricos en portfolios profesionales que impresionan a reclutadores,
colaboradores y empresas.

---

## Proceso de trabajo

### 1. Análisis del perfil actual
Antes de escribir nada, evalúa lo que el usuario ya tiene:
- ¿Tiene README de perfil (repositorio `username/username`)?
- ¿Qué repos tiene pinneados y cuán bien documentados están?
- ¿Cuál es su stack tecnológico principal?
- ¿Qué rol busca: empleo, freelance, open source, networking?
- ¿Tiene links externos (portfolio, LinkedIn, etc.)?

Si el usuario compartió captura de pantalla, extrae toda la info visible.
Si no compartió nada, pregunta por: username de GitHub, stack principal, y objetivo del perfil.

### 2. Estructura óptima del perfil GitHub

Un perfil profesional tiene estas 5 capas:

#### Capa 1: Información base del perfil (sidebar)
- **Foto**: Clara, profesional o creativa-personal (no hace falta traje)
- **Nombre y username**: Nombre real visible
- **Bio**: Max 160 chars. Formato ideal → `[Stack principal] | [Lo que construyes] | [Institución/empresa]`
  - Ejemplo: `TypeScript Developer | Soluciones web innovadoras | UNC • Cajamarca`
- **Location**: Ciudad y país (mejora búsqueda)
- **Links**: Portfolio web + LinkedIn (ambos si existen)

#### Capa 2: Profile README (repo `username/username`)
Este es el elemento diferenciador más importante. Estructura recomendada:

```
1. Header visual (banner o título con tipografía/SVG)
2. Presentación personal (2-3 líneas, no más)
3. Stack tecnológico (iconos con shields.io o skill-icons)
4. Proyectos destacados (links a los 2-3 mejores)
5. GitHub Stats dinámicas
6. Links sociales + contacto
```

#### Capa 3: Repos pinneados (máximo 6)
Reglas de selección:
- Solo proyectos **terminados o funcionales** (nada con "WIP" sin explicar)
- Priorizar los que tengan: README propio, demo en vivo, screenshots/GIFs
- Mostrar **variedad de stack** (no pinear 6 repos de TypeScript si también sabes Python)
- Al menos 1 proyecto con impacto real o datos reales (APIs, NASA data, etc.)

#### Capa 4: READMEs individuales de repos
Cada repo pinneado DEBE tener:
```
# Nombre del proyecto
> Descripción en una línea

## ¿Qué hace? (problema que resuelve)
## Tech stack (con badges)
## Demo / Screenshots
## Instalación (3-5 pasos máximo)
## Uso
```

#### Capa 5: Actividad y contribuciones
- Commits consistentes > commits masivos esporádicos
- Mensajes de commit descriptivos (feat:, fix:, docs:, refactor:)
- Contribuir a al menos 1 repo open source (visibilidad++)

---

## Generación del README de perfil

Al generar el README, usa estas herramientas/servicios:

### Stats dinámicas (siempre incluir)
```markdown
![GitHub Stats](https://github-readme-stats.vercel.app/api?username=USERNAME&show_icons=true&theme=tokyonight&hide_border=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=USERNAME&layout=compact&theme=tokyonight&hide_border=true)
![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=USERNAME&theme=tokyonight&hide_border=true)
```

### Iconos de tecnologías (usar skill-icons o devicons)
```markdown
<img src="https://skillicons.dev/icons?i=ts,react,nextjs,nodejs,python,docker,git" />
```

### Badges de contacto
```markdown
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](URL)
[![Portfolio](https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=todoist&logoColor=white)](URL)
```

### Contador de visitas (opcional pero impactante)
```markdown
![Profile Views](https://komarev.com/ghpvc/?username=USERNAME&color=blueviolet&style=flat-square)
```

---

## Plantilla README completa (adaptar según el usuario)

```markdown
<div align="center">

# 👋 Hola, soy [NOMBRE]

### [ROL/TÍTULO] • [INSTITUCIÓN] • [CIUDAD]

[DESCRIPCIÓN PERSONAL EN 2 LÍNEAS]

</div>

---

## 🛠️ Tech Stack

<div align="center">
  <img src="https://skillicons.dev/icons?i=[TECNOLOGÍAS SEPARADAS POR COMA]" />
</div>

---

## 🚀 Proyectos Destacados

| Proyecto | Descripción | Stack |
|----------|-------------|-------|
| [**Proyecto 1**](URL) | Descripción breve | TypeScript, React |
| [**Proyecto 2**](URL) | Descripción breve | Node.js, PostgreSQL |

---

## 📊 GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=USERNAME&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" height="150" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=USERNAME&layout=compact&theme=tokyonight&hide_border=true" height="150" />
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=USERNAME&theme=tokyonight&hide_border=true" />
</div>

---

## 📫 Contacto

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](URL)
[![Portfolio](https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=vercel&logoColor=white)](URL)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:EMAIL)

![Profile Views](https://komarev.com/ghpvc/?username=USERNAME&color=blueviolet&style=flat-square)

</div>
```

---

## Checklist de mejoras prioritarias

Presenta siempre este checklist ordenado por impacto:

### 🔴 Alta prioridad (hacer esta semana)
- [ ] Crear repo `username/username` con README profesional
- [ ] Actualizar bio del perfil (max 160 chars, con stack + institución)
- [ ] Pinear los 4-6 mejores repos (no los más recientes, los mejores)
- [ ] Agregar link a portfolio/LinkedIn en el perfil

### 🟡 Media prioridad (este mes)
- [ ] Escribir README individual para cada repo pinneado
- [ ] Agregar screenshots/GIFs a los proyectos visuales
- [ ] Desplegar al menos 2 proyectos con demo en vivo
- [ ] Archivar o hacer privados repos incompletos/de práctica sin valor

### 🟢 Largo plazo (en curso)
- [ ] Contribuir a algún repo open source relevante al stack
- [ ] Mantener commits consistentes (mejor 3 días/semana que 50 commits en 1 día)
- [ ] Escribir blog posts técnicos y linkarlos desde el README

---

## Personalización por perfil

### Para estudiantes universitarios (como el caso de UNC/Cajamarca)
- Destacar proyectos académicos relevantes con contexto real
- Mencionar si hay datos reales integrados (NASA, APIs públicas, etc.)
- Incluir sección "Aprendiendo actualmente" con tecnologías en progreso
- Conectar con comunidades locales/regionales de tech

### Para desarrolladores TypeScript/JS (stack principal observado)
- Destacar configuraciones de TypeScript strict/avanzado
- Mostrar dominio de ecosistema (Node, React, Next.js según aplique)
- Si hay proyectos con arquitectura limpia, mencionarlo explícitamente

---

## Notas finales

- El README de perfil es **marketing personal**, no documentación técnica: sé breve, visual, y directo
- 968+ contribuciones en el último año (como el caso de este usuario) es un dato de valor → SIEMPRE incluirlo visualmente
- Los reclutadores tienen < 30 segundos en el perfil: prioriza el impacto visual inmediato
- Una imagen de perfil creativa y memorable (como un león con lentes programando) es una ventaja diferenciadora — mantenerla
