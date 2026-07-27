
```markdown
#  Research Paper Assistant

[![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)](https://python.org)
[![Google Gemini](https://img.shields.io/badge/Google_Gemini-2.5--flash-blueviolet.svg)](https://aistudio.google.com/)
[![FAISS](https://img.shields.io/badge/FAISS-Vector_Search-green.svg)](https://faiss.ai)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Production_Ready-brightgreen.svg)]()

>  An interactive academic research compilation application combining local FAISS dense abstract vectors and Google Gemini 2.5-Flash JSON parsing modes to produce targeted peer-review critiques, cross-paper thematic synthesis reports, and clear citation maps.

---

##  Table of Contents
- [Overview](#overview)
- [System Architecture](#system-architecture)
- [Key Features](#key-features)
- [Tech Stack](#tech-stack)
- [Jupyter Cell Sequence Blueprint](#jupyter-cell-sequence-blueprint)
- [Installation & Environment Setup](#installation--environment-setup)
- [Project Directory Architecture](#project-directory-architecture)
- [License](#license)

---

##  Overview

The **Research Paper Assistant** system helps researchers bypass manual literature matrix aggregation loops. By extracting structural segments from indexed manuscripts, it creates semantic representations using sentence embedding modules, performs lookups against a local FAISS store, and uses large language models to construct holistic multi-paper surveys automatically.

---

##  System Architecture




Academic Manuscript Data Streams / Domain Queries
│
▼
┌──────────────────────────────┐
│    Sentence-Transformers     │  稳定 Encodes text blocks to dense dimensions
└──────────────┬───────────────┘
│
▼
┌──────────────────────────────┐
│   FAISS Local Index FlatIP   │  稳定 Maps semantic similarity fields
└──────────────┬───────────────┘
│
▼
┌──────────────────────────────────────────────────────────────┐
│             Gemini 2.5-Flash Academic Engine                 │
│  ┌───────────────────────────┐ ┌──────────────────────────┐  │
│  │ Structural Peer Reviewer  │ │ JSON Mode Review Blender │  │
│  └───────────────────────────┘ └──────────────────────────┘  │
└────────────────────────┬─────────────────────────────────────┘
│
▼
┌──────────────────────────────────────────────────────────────┐
│               Gradio Interface Application Multi-Tab Hub     │
│  ┌───────────────────────────┐ ┌──────────────────────────┐  │
│  │ Critique Breakdown Pane   │ │ Literature Review Sheet  │  │
│  └───────────────────────────┘ └──────────────────────────┘  │
└──────────────────────────────────────────────────────────────┘

```

---

##  Key Features

* **Grounded Academic RAG System:** Queries local research files using a high-speed FAISS inner-product index framework, reducing hallucination tendencies during synthesis reviews.
* **JSON-Forced Review Compiler:** Leverages Gemini `response_mime_type` mechanics to aggregate text sources into verified thematic maps and matrix sheets without data truncation.
* **Automated Peer Critique Engine:** Evaluates selected manuscripts across research boundaries, documenting innovations, basic limitations, and underlying assumptions.
* **Precedent Citation Map Builder:** Traces historical references to build clean visual markdown tables detailing foundational literature connections.
* **Unified Workspace UI Display:** Features an isolated Gradio blocks interface layout with separate tabs for text review summaries and cross-paper literature synthesis operations.

---

##  Tech Stack

* **AI Processing Engine:** Google Gemini 2.5-Flash (`google-generativeai`)
* **Vector Document Store Index:** Facebook AI Similarity Search (`faiss-cpu`)
* **Dense Semantic Embeddings:** HuggingFace `sentence-transformers` (`all-MiniLM-L6-v2`)
* **Visual Presentation Interface:** Gradio Blocks Dashboard Grid (Gradio 6.0+ compatible)
* **Terminal Data Format Layouts:** Rich Console Panels formatting frameworks

---

##  Jupyter Cell Sequence Blueprint

| Cell # | Type | Target Context Module | Technical Core Purpose |
| :--- | :--- | :--- | :--- |
| **Cell 1** |  Markdown | **Documentation Cover** | System summary badges, features indices, and blueprint flow maps. |
| **Cell 2** |  Code | **Package Downloads** | Installs AI libraries, FAISS layers, and document data infrastructure tools. |
| **Cell 3** |  Code | **Global Initializations** | Standard imports, data classes configuration blueprints, and API settings. |
| **Cell 4** |  Code | **Academic Vector store** | Implements `AcademicRAGSystem` parsing semantic values across FAISS indexes. |
| **Cell 5** |  Code | **Research Assistant Agent** | Drives `ResearchPaperAssistant` handling reviews synthesis and peer critiques. |
| **Cell 6** |  Code | **Diagnostics Diagnostics** | Validates internal operations via safe try-except boundaries to skip endpoint quota caps. |
| **Cell 7** |  Code | **Gradio App UI Layout** | Launches the multi-tab interactive academic platform dashboard right inside your notebook browser session. |

---

## Installaion & Environment Setup

### 1. Build Local Workspace Target Project Directory
```bash
git clone [https://github.com/yourusername/Research_Paper_Assistant.git](https://github.com/yourusername/Research_Paper_Assistant.git)
cd Research_Paper_Assistant
python -m venv venv
source venv/bin/activate # Windows Terminal: .\venv\Scripts\activate

```

### 2. Deploy Pinned Dependencies Manifest

```bash
pip install -r requirements.txt

```

### 3. Setup Gemini Access Token

Get a free API access key directly from [Google AI Studio](https://aistudio.google.com/). Paste your secret key parameter inside **Cell 3** configuration rows:

```python
os.environ["GEMINI_API_KEY"] = "AIzaSyYourSecretKeyStringHere"

```

---

##  Project Directory Architecture

```text
Research_Paper_Assistant/
├── notebooks/
│   └── Research_Paper_Assistant.ipynb   # Main interactive development notebook workspace
├── output/                              # Target directory containing saved report files
├── .gitignore                           # Git configuration element tracking blocks
├── README.md                            # Comprehensive system documentation (This file)
└── requirements.txt                     # Pinned application dependencies manifest

```

---

##  Author

**Divya** — AI/ML Developer |
```
```
