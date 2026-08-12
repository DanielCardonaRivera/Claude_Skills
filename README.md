# Claude_Skills Repository

[Español](#español) | [English](#english)

---

<a name="español"></a>
## Español

### Propósito del Repositorio

Este repositorio es una colección estructurada de plantillas, instrucciones de sistema (Custom Instructions), bases de conocimiento y prompts reutilizables diseñados para optimizar el trabajo con Anthropic Claude, Claude Projects y la generación de Artifacts.

---

### Estructura del Repositorio

```text
Claude_Skills/
├── projects/
│   ├── fullstack-developer/
│   │   ├── instructions.md
│   │   └── knowledge/
│   │       ├── architecture-rules.md
│   │       └── code-style.md
│   └── ux-ui-designer/
│       ├── instructions.md
│       └── knowledge/
│           └── design-system.md
├── artifacts/
│   ├── react-tailwind/
│   │   ├── dashboard-card.md
│   │   └── multi-step-form.md
│   ├── mermaid-diagrams/
│   │   ├── system-architecture.md
│   │   └── sequence-diagram.md
│   └── documents/
│       └── technical-spec.md
├── LICENSE
└── README.md
```

---

### Guía de Uso

#### 1. Configuración de un Claude Project

1. Inicia sesión en tu cuenta de Claude.
2. Navega a la sección Projects y selecciona Create Project.
3. Copia el contenido de `instructions.md` del rol correspondiente en la sección Set Custom Instructions.
4. Sube los archivos adjuntos dentro de la carpeta `knowledge/` a la sección Project Knowledge.

#### 2. Uso de Prompts para Artifacts

1. Habilita la función de Artifacts en la configuración de Claude.
2. Copia los prompts definidos en la carpeta `artifacts/` y utilízalos directamente en el chat para generar componentes interactivos, diagramas o documentos estructurados.

---

### Módulos Incluidos

| Categoría | Nombre de Skill | Descripción |
| :--- | :--- | :--- |
| Project | `fullstack-developer` | Configuración para desarrollo en Next.js, TypeScript y Tailwind CSS. |
| Project | `ux-ui-designer` | Guías de diseño, accesibilidad WCAG y componentes de interfaz. |
| Artifact | `react-dashboard` | Componentes interactivos de métricas y tarjetas de control. |
| Artifact | `architecture-mermaid` | Generador de diagramas de arquitectura y flujos de secuencia. |

---

### Buenas Prácticas

- Uso de etiquetas XML: Delimita contextos, instrucciones y restricciones utilizando etiquetas como `<instructions>`, `<rules>` y `<context>`.
- Control de contexto: Mantén los documentos de conocimiento concisos para optimizar la ventana de contexto de Claude.
- Especificación de salidas: Define con claridad cuando requieras un componente interactivo o un diagrama renderizado mediante un Artifact.

---

### Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo `LICENSE` para más detalles.

---

<a name="english"></a>
## English

### Repository Purpose

This repository is a structured collection of templates, system instructions (Custom Instructions), knowledge bases, and reusable prompts designed to optimize workflows with Anthropic Claude, Claude Projects, and Artifact generation.

---

### Repository Structure

```text
Claude_Skills/
├── projects/
│   ├── fullstack-developer/
│   │   ├── instructions.md
│   │   └── knowledge/
│   │       ├── architecture-rules.md
│   │       └── code-style.md
│   └── ux-ui-designer/
│       ├── instructions.md
│       └── knowledge/
│           └── design-system.md
├── artifacts/
│   ├── react-tailwind/
│   │   ├── dashboard-card.md
│   │   └── multi-step-form.md
│   ├── mermaid-diagrams/
│   │   ├── system-architecture.md
│   │   └── sequence-diagram.md
│   └── documents/
│       └── technical-spec.md
├── LICENSE
└── README.md
```

---

### Usage Guide

#### 1. Setting Up a Claude Project

1. Log in to your Claude account.
2. Navigate to the Projects section and click Create Project.
3. Copy the contents of `instructions.md` for the corresponding role into the Set Custom Instructions field.
4. Upload the files inside the `knowledge/` directory to the Project Knowledge section.

#### 2. Using Artifact Prompts

1. Ensure the Artifacts feature is enabled in your Claude settings.
2. Copy any template prompt from the `artifacts/` directory into your conversation to generate interactive UI components, diagrams, or structured documentation.

---

### Included Modules

| Category | Skill Name | Description |
| :--- | :--- | :--- |
| Project | `fullstack-developer` | Setup for development with Next.js, TypeScript, and Tailwind CSS. |
| Project | `ux-ui-designer` | Guidelines for UI design, WCAG accessibility, and design systems. |
| Artifact | `react-dashboard` | Interactive metric cards and dashboard components. |
| Artifact | `architecture-mermaid` | Prompts for system architecture and sequence diagrams. |

---

### Best Practices

- Use XML Tags: Enclose contexts, rules, and guidelines using tags like `<instructions>`, `<rules>`, and `<context>`.
- Context Optimization: Keep knowledge documents concise to preserve Claude's context window.
- Clear Output Definitions: Explicitly request interactive UI elements or diagrams when an Artifact response is required.

---

### License

This project is licensed under the MIT License. See the `LICENSE` file for more details.