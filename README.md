# 🧟‍♂️ [Mr. Frankenstein UI Builder](https://mr-frankenstein.vercel.app/)

> **"IT'S ALIVE!"** — Build, Preview, and Export beautiful React interfaces at lightning speed.

**Mr. Frankenstein** is a state-of-the-art, drag-and-drop UI component builder specifically engineered for the modern React ecosystem. Instead of exporting generic HTML snippets, Mr. Frankenstein understands your architecture and exports **production-ready Shadcn UI JSX** components perfectly tailored for your codebase.

---

## ✨ Features

- **⚡ Lightning Fast Drag-and-Drop:** Powered by `@dnd-kit/core`, visually construct complex, nested UI layouts intuitively without writing a single line of layout code.
- **🎨 Dynamic Theming Engine:** Swap between gorgeous, hand-crafted global themes (like *Freaky*, *90s*, *Modern*, and *Light*) instantly. The entire UI repaints instantly without reloading.
- **📱 Responsive Viewports:** Seamlessly toggle the canvas between `Mobile`, `Tablet`, `Desktop`, and `Fluid` dimensions to ensure your layout behaves perfectly on all devices.
- **👁️ Live Preview Mode:** Strip away the editor UI with a single click. The Live Preview modal renders a pure, 1:1 React representation of what your users will actually see.
- **💾 Auto-Save (Persistent State):** Accidentally closed the tab? No problem. The canvas state, layer tree, and theme settings are safely persisted to your browser's local storage utilizing `Zustand` persist middleware.
- **🔒 Highly Secure:** Dynamic user-injected properties (like SVG icons) are strictly sanitized client-side using `DOMPurify` to prevent Cross-Site Scripting (XSS) vulnerabilities.

### 📦 The "Component Forge" Export Engine

Stop wasting time translating visual prototypes back into code. Mr. Frankenstein features a bespoke Export Engine that offers two distinct modes:

1. **Standard HTML Export:** Generates clean, semantic HTML5 markup wrapped in Tailwind CSS classes.
2. **Shadcn JSX Export:** Generates fully modular React code, intelligently detecting which Shadcn components you used and automatically generating the exact `import` statements required for your project (e.g. `import { Card } from "@/components/ui/card"`).

---

## 🚀 Use Cases

- **Rapid Prototyping:** Instantly spin up authentication screens, dashboards, and complex forms in minutes during hackathons or sprint planning.
- **Developer Handoff:** Designers can build the exact component structure they want visually, and hand the developer perfect, ready-to-paste Shadcn JSX.
- **Headless CMS templating:** Quickly design article layouts or landing pages and copy the structural code directly into your headless repository.
- **Learning Tailwind & Flexbox:** Visually interact with layout properties (Flex vs Grid, Directions, Padding/Margins) in the Inspector Panel and instantly see how the Tailwind CSS classes are generated in real-time.

---

## 🛠️ Tech Stack

Mr. Frankenstein is built with cutting-edge tooling:

- **Framework:** Next.js 16 (App Router + Turbopack)
- **Styling:** Tailwind CSS v4 (Inline Theme Variables)
- **State Management:** Zustand
- **Drag & Drop Engine:** Dnd-Kit (`@dnd-kit/core`)
- **UI Components:** Radix UI / Shadcn UI
- **Security:** DOMPurify (XSS Sanitization)
- **Icons:** Lucide React


*Built with passion, electricity, and a few borrowed body parts.* ⚡
