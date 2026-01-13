<div align="center">

# 🌌 Flux | The Spatial Operating System

### **Unified Polymorphic Workspace for the Future of Work**

<p align="center">
  <img src="https://img.shields.io/badge/Status-Alpha-orange?style=for-the-badge" alt="Status"/>
  <img src="https://img.shields.io/badge/License-MIT-blue?style=for-the-badge" alt="License"/>
</p>

<p align="center">
  Flux is not just a tool; it's a new paradigm. It unifies <strong>Ideation</strong>, <strong>Execution</strong>, and <strong>Scheduling</strong> into a single, spatial environment where thoughts turn into actions seamlessly.
</p>

</div>

---

## 🚀 Core Vision

In the fragmentation of modern tools, context is lost. Flux bridges the gap between the whiteboard and the spreadsheet.

**"Don't just manage work. Inhabit it."**

We are building a **Spatial Operating System** where:
1.  **Canvas is the Database**: Visual arrangements carry semantic meaning.
2.  **AI is the Operator**: Agents don't just chat; they structure, plan, and execute.
3.  **Context is King**: No more switching tabs. Everything related is spatially adjacent.

---

## ✨ Features

### 🎨 Polymorphic Canvas
Draw, write, stick, and link. The canvas adapts to your content.
- **Infinite Whiteboard**: Spatial freedom to brainstorm.
- **Bi-directional Sync**: Notes on the canvas become rows in a database.
- **Smart Components**: Tables, Kanban boards, and Calendars live natively on the infinite plane.

### 🧠 AI Operator (Gen 9)
An intelligent layer that watches, learns, and assists.
- **Auto-Summarization**: Turn messy brain-dumps into structured plans.
- **Contextual Search**: "Show me the marketing plan from last Tuesday" highlights the exact region on the canvas.
- **Generative Flows**: Ask the operator to "Draw a roadmap for launch," and watch it populate cards and timelines.

### ⚡ Execution Engine
Data-first underlying architecture ensures your spatial mess is structured data.
- **Real-time Collaboration**: Multi-player by default using CRDTs.
- **Enterprise Grade Schedulers**: Gantt and Calendar views that rival dedicated project management tools.

---

## 🏗️ Technical Architecture

Flux is built on a high-performance stack designed for heavy client-side interaction and real-time reliability.

```mermaid
graph TD
    Client[Client (Next.js 15)] -->|React Three Fiber| Canvas[Spatial Canvas]
    Client -->|TRPC| Server[Edge Server]
    Client -->|WebSocket| Realtime[Realtime Service]
    
    subgraph Data Layer
        Server --> DB[(Postgres / Prisma)]
        Realtime --> Redis[(Redis Pub/Sub)]
    end
    
    subgraph AI Layer
        AI[AI Agent Service] -->|Context| VectorDB[(Vector DB)]
        AI -->|LLM API| Model[LLM Provider]
    end
```

### Tech Stack

- **Framework**: [Next.js 15](https://nextjs.org/) (App Router)
- **Database**: SQLite (Dev) / Postgres (Prod) with Prisma
- **Auth**: NextAuth v5 (Google, Apple)
- **UI**: TailwindCSS v4, Framer Motion, Radix UI
- **Spatial**: React Three Fiber / Three.js
- **State**: Roland / Zustand (for high-freq updates)

---

## 🏁 Getting Started

### Prerequisites

- Node.js 18+
- PostgreSQL (if running locally with prod config)

### Installation

1.  **Clone the repository**
    ```bash
    git clone https://github.com/officialsimranagarwal/flux.git
    cd flux
    ```
2.  **Install dependencies**
    ```bash
    npm install
    ```
3.  **Setup Environment**
    Copy `.env.example` to `.env` and configure your credentials.
    ```bash
    cp .env.example .env
    ```
4.  **Run Development Server**
    ```bash
    npm run dev
    ```

---

## 🤝 Contributing

We are in active development and welcome brave pioneers.

1.  Refer to `CONTRIBUTING.md` (coming soon).
2.  Check the Issues tab for "Good First Issue".
3.  Join our Discord community for dev discussions.

---

## 📄 License

Flux is open-source software licensed under the [MIT license](LICENSE).

---

<div align="center">
  <p>© 2026 Flux Labs. Built by Simran Agarwal.</p>
</div>
