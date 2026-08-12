# 🚀 Claude Projects & Artifacts Skills Repository

Un repositorio curado de plantillas, instrucciones de sistema (*Custom Instructions*), archivos de contexto y componentes reutilizables diseñados para potenciar el uso de **Claude Projects** y la generación de **Artifacts**.

---

## 📌 Tabla de Contenidos

- [🎯 Propósito del Repositorio](#-propósito-del-repositorio)
- [📂 Estructura del Repositorio](#-estructura-del-repositorio)
- [📦 Guía de Uso](#-guía-de-uso)
  - [1. Configuración de un Claude Project](#1-configuración-de-un-claude-project)
  - [2. Uso de Artifacts Prompts](#2-uso-de-artifacts-prompts)
- [🛠️ Módulos y Plantillas Incluidas](#️-módulos-y-plantillas-incluidas)
- [⚡ Buenas Prácticas de Prompting en Claude](#-buenas-prácticas-de-prompting-en-claude)
- [🤝 Cómo Contribuir](#-cómo-contribuir)
- [📄 Licencia](#-licencia)

---

## 🎯 Propósito del Repositorio

Este proyecto busca estandarizar y acelerar el desarrollo asistido por IA utilizando el ecosistema de **Anthropic Claude**. Aquí encontrarás:
* **Instrucciones Personalizadas (System Prompts)** optimizadas mediante sintaxis XML.
* **Bases de Conocimiento (Knowledge Base Documents)** listas para subir a tus *Claude Projects*.
* **Prompts Generadores de Artifacts** para componentes UI (React + Tailwind), diagramas de arquitectura (Mermaid.js), y documentos estructurados.

---

## Estructura del Repositorio

```text
claude_skills/
├── 📁 projects/
│   ├── 📁 fullstack-developer/
│   │   ├── instructions.md         # Custom Instructions del Proyecto
│   │   └── 📁 knowledge/            # Documentos de contexto inicial
│   │       ├── architecture-rules.md
│   │       └── code-style.md
│   └── 📁 ux-ui-designer/
│       ├── instructions.md
│       └── 📁 knowledge/
│           └── design-system.md
├── 📁 artifacts/
│   ├── 📁 react-tailwind/          # Plantillas de UI interactivas
│   │   ├── dashboard-card.md
│   │   └── multi-step-form.md
│   ├── 📁 mermaid-diagrams/        # Flujos y arquitectura
│   │   ├── system-architecture.md
│   │   └── sequence-diagram.md
│   └── 📁 documents/               # Reportes y documentaciones
│       └── technical-spec.md
├── 📄 LICENSE
└── 📄 README.md
```

---

## Guía de Uso

### 1. Configuración de un Claude Project

1. Entra a tu cuenta de **Claude** (requiere plan *Pro* o *Team*).
2. Ve a la pestaña **Projects** y haz clic en **Create Project**.
3. Asigna un nombre al proyecto (ej. `Fullstack Dev Assistant`).
4. En la sección **Project Knowledge**, sube los archivos Markdown ubicados en `projects/<nombre-proyecto>/knowledge/`.
5. En la sección **Set Custom Instructions**, copia y pega el contenido del archivo `instructions.md` correspondiente.

### 2. Uso de Artifacts Prompts

1. Abre cualquier chat dentro de tu proyecto o un chat general.
2. Asegúrate de tener habilitada la función de **Artifacts** en tu configuración.
3. Copia una de las plantillas de `artifacts/` y adáptala a tu requerimiento especificando el tipo de artefacto deseado (ej. React, SVG, Mermaid, HTML).

---

## 🛠️ Módulos y Plantillas Incluidas

| Categoría | Nombre de Skill | Descripción |
| :--- | :--- | :--- |
| **Project** | `fullstack-developer` | Configuración para desarrollo en Next.js, TypeScript y Tailwind CSS con estándares estrictos de Clean Code. |
| **Project** | `technical-writer` | Instrucciones para generar documentación técnica, API Specs y manuales en Markdown claro. |
| **Artifact** | `react-dashboard` | Generador de Dashboards interactivos con controles de estado locales y gráficos visuales. |
| **Artifact** | `architecture-mermaid` | Plantilla para renderizar diagramas C4 y flujos de secuencia limpios. |

---

## Buenas Prácticas de Prompting en Claude

Para obtener el máximo rendimiento de estas plantillas, ten en cuenta:
* **Uso de Etiquetas XML:** Claude interpreta excepcionalmente bien etiquetas como `<context>`, `<rules>`, e `<instructions>`.
* **Delimitación de Tareas:** Define explícitamente cuándo quieres que genere un *Artifact* separado frente a cuándo prefieres una explicación en texto directo.
* **Context Window Management:** Mantén los archivos en la *Knowledge Base* concisos y evita redundancias para no saturar la ventana de contexto.

---

## Cómo Contribuir

¡Las contribuciones son bienvenidas! Si deseas agregar una nueva plantilla de Proyecto o un prompt para Artifacts:

1. Haz un **Fork** de este repositorio.
2. Crea una rama para tu función (`git checkout -b feature/nueva-skill`).
3. Agrega tu módulo siguiendo la estructura de carpetas definida.
4. Asegúrate de probar la plantilla directamente en Claude.
5. Envía un **Pull Request** describiendo el caso de uso y adjuntando capturas/ejemplos del *output*.

---

## 📄 Licencia

Este repositorio se distribuye bajo la licencia **MIT**. Siéntete libre de usarlo, modificarlo y compartirlo en tus propios proyectos.
