# 🏃 Agile Documentation: Summarizer.ai

## 🔭 Project Vision
To empower researchers and students with a high-performance, AI-driven assistant that deconstructs complex academic literature into actionable insights, saving time and enhancing comprehension.

---

## 👤 User Personas

| Persona | Role | Primary Goal | Favorite Feature |
| :--- | :--- | :--- | :--- |
| **Dr. Elena** | Academic Researcher | Quickly identify state-of-the-art methodologies. | Paper Comparison Tool |
| **Arjun** | Graduate Student | Understand dense jargon and complex math in papers. | AI-RAG Chat |
| **Sarah** | Industry Professional | Stay updated with new research during commutes. | Email Summaries |

---

## 📝 User Stories

### Core Analysis (MVP)
- **Paper Intake**: *As a user, I want to upload PDF/DOCX files so I can process them without manual copying.* (DONE)
* **Summarization**: *As a student, I want a 3-4 sentence summary so I can quickly decide if a paper is relevant.* (DONE)
- **Insight Extraction**: *As a researcher, I want the top 5 key findings extracted automatically so I can save time scanning.* (DONE)

### Interactive Learning (Sprint 1-2)
- **Contextual Q&A**: *As a user, I want to ask questions directly to the document so I can clarify specific points.* (DONE)
- **Paper Comparison**: *As a researcher, I want to see word-overlap and AI-generated differences between two papers.* (DONE)
- **History Tracking**: *As a student, I want to save my analyses so I can reference them later without re-uploading.* (DONE)

### Organization & Productivity (Sprint 3-4)
- **Research Timeline**: *As a user, I want a visual timeline of my research history so I can see my learning journey.* (IN PROGRESS)
- **Sharing**: *As a professional, I want to email summaries to myself or colleagues for easy access.* (DONE)
- **Reading Analytics**: *As a user, I want to know how much time I've spent reading each paper.* (DONE)

---

## 📋 Product Backlog

### High Priority (Sprinting)
- [x] **Core RAG Engine**: Integrate FAISS and Groq Llama 3.3.
- [x] **Multi-format Support**: Support for PDF and DOCX.
- [x] **Auth System**: Secure JWT login/signup.
- [ ] **Visual Citation Network**: Implement D3.js visualization for cross-paper references.
- [ ] **Folder Organization**: Allow users to group analyses into folders/projects.

### Medium Priority
- [ ] **Research Landscape Explorer**: Interactive map of topics and trends.
- [ ] **Batch Processing**: Upload multiple papers at once for comparative summaries.
- [ ] **Markdown Export**: Add support for exporting analysis in MD format.

---

## 🗺️ Roadmap

### Phase 1: The Core (Completed)
- Basic text extraction, Groq integration, and JWT-based Auth.
- Summary and Insight generation.

### Phase 2: Interactivity (Current)
- RAG Chat widget implementation.
- Side-by-side paper comparison tool.
- PDF/TXT exports.

### Phase 3: Visual Intelligence (Upcoming)
- Citation network visualization.
- Research timeline refinement.
- Topic modeling and landscape explorer.

### Phase 4: Collaboration & Scale
- Multi-user collaboration on "Research Projects".
- Chrome Extension for one-click ArXiv analysis.

---

## 🛠️ Definition of Done (DoD)
- [ ] Unit tests for new API endpoints pass.
- [ ] Frontend components are responsive (tested on mobile/desktop).
- [ ] AI prompts are optimized for accuracy and JSON output.
- [ ] Code is documented with clear JSDoc or Python type hints.
- [ ] Zero critical console errors in the UI.
