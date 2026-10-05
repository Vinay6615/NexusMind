# NexusMind — Universal Knowledge-Graph & Mind Map Generator

NexusMind is a powerful, production-grade universal knowledge-graph and mind map generator powered by Gemini AI and real-time **Google Search Grounding**. It converts any concept, topic, historical event, technical specification, or input text into a rich, structured, hierarchical interactive mind map.

---

## 🌟 Key Features

1. **Google Search Grounding (`gemini-3.5-flash`)**:
   - Integrates real-time Google Search data to ensure all generated concepts, facts, dates, and metrics are up-to-date and accurate.
   - Automatically displays live web grounding source citations and reference links in the node inspector sidebar.

2. **Interactive Visual Canvas & Navigation**:
   - **Radial & Hierarchical Layout**: Automatically calculates clean, balanced radial trees connecting root concepts to main topics, sub-topics, and granular details.
   - **Keyboard Traversal**: Navigate smoothly across connected nodes using your keyboard's **Arrow Keys** (`↑`, `↓`, `←`, `→`).
   - **Node Jump Search**: Instantly search and center on any node in the graph using the built-in quick jump selector.
   - **Pan & Zoom**: Smooth drag-to-pan and zoom controls.

3. **High-Resolution PNG Image Export**:
   - Render and download your entire mind map (including nodes, bezier curve edges, color-coded categories, and rich descriptions) as a pristine PNG image file with a single click.

4. **AI Deep Dive & Node Expansion**:
   - Click on any sub-topic node to ask Gemini to generate additional child branches and expand the knowledge tree further.

5. **Robust Rate-Limit Resilience & Intelligent Fallbacks**:
   - Built-in automatic retry logic and topic-aware fallback knowledge graph generators ensure the application remains 100% operational and informative even during API quota exhaustion.

6. **Multiple View Modes**:
   - **Canvas Graph**: Interactive visual node workspace.
   - **Tree Outline**: Structured expandable hierarchical document view.
   - **Mermaid.js**: Instant diagram syntax export for markdown documentation.

---

## 🛠️ Tech Stack

- **AI SDK**: `@google/genai` (Server-side Gemini API integration)
- **Frontend**: React 19, Vite, Tailwind CSS (via `@tailwindcss/vite`), Lucide Icons
- **Backend**: Node.js & Express server with Vite middleware integration
- **Database**: MongoDB may be included in an improved version, where mind map history is maintained - with the graphs and tree outlines stored in a format more flexible than JSON, using a relaxed schema.
---

## 🚀 Getting Started

1. **Install Dependencies**:
   ```bash
   npm install
   ```

2. **Run Development Server**:
   ```bash
   npm run dev
   ```

3. **Build for Production**:
   ```bash
   npm run build
   start
   ```
