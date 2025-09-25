# Kape

**Kape** is an open-source **IaCD (Infrastructure as CodeDiagram) editor** that combines code and diagrams together.
Drag-and-drop your resources, write IaC snippets inline, and export them as any text-based file such as `.yaml`. 

Kape is **vendor-agnostic**, meaning it is not tailored to any specific cloud, platform or tools. While it can be used to visualize Terraform, Kubernetes, or other infrastructure resources, it works with **any text-based IaC**.

---

## Motivation

Infrastructure design often begins with sketching diagrams on paper or using GUI tools. These methods help in visualizing the architecture. However, when transitioning to implementation, we move to writing configuration files. This shift can create a disconnect: tracing a specific piece of infrastructure back to its corresponding code becomes challenging, especially as the codebase grows. Even with modularization and file separation, navigating large-scale infrastructures can be a headache.

While some tools offer drag-and-drop interfaces to design infrastructure and generate code, they introduce significant limitations. Translating diagrams into code requires continuous maintenance for updates from various providers, often resulting in tools that are narrowly scoped and quickly outdated. Moreover, these abstractions can obscure the actual code, making it difficult to locate and modify specific configurations when needed.

This project introduces a new approach which I'm not aware of any existing tools: a "code-diagram" (which is the term I came up with) editor. In this tool, code and diagram coexist on the same page. Each resource is represented as a draggable node on a visual canvas, with its configuration directly editable within the diagram. This approach allows for intuitive visualization, seamless editing, and straightforward export of infrastructure code, all within a unified interface.

---
## Features

* **Drag-and-drop nodes** representing resources
* **Embedded code editor** (Monaco) inside each node
* **Custom icons** for resources
* **Export your snippets** as text-based files in any extension
* **Visual organization**: collapse nodes, arrange workflow, see relationships

---

## Screenshot / Demo

![Kape Demo]()

---

## Getting Started

1. Clone the repository:

```bash
git clone https://github.com/jaykape/kape.git
cd kape
```

2. Install dependencies:

```bash
npm install
```

3. Run locally:

```bash
npm start
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser.

---

## Tech Stack

* **React** – UI components
* **React Flow** – Canvas and drag-drop nodes
* **Monaco Editor** – Embedded code editor
* **CSS / Tailwind** – Node styling and layout

---

## License

This project is licensed under the **MIT License**.
See the [LICENSE](LICENSE) file for details.

