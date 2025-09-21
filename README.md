# Kape

**Kape** is an open-source **IaCD (Infrastructure-as-Code Diagram) editor** that combines code and diagrams together.
Drag-and-drop your resources, write IaC snippets inline, and export them as any text-based file such as `.yaml`. 

Kape is **vendor-agnostic**, meaning it is not tailored to any specific cloud, platform or tools. While it can be used to visualize Terraform, Kubernetes, or other infrastructure resources, it works with **any text-based IaC**.

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
git clone https://github.com/yourusername/kape.git
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

---

## Tagline / One-liner

> Kape – The open-source, vendor-agnostic IaCD editor for visual and code-driven infrastructure design
