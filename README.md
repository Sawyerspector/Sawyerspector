# 👋 Hi, I'm Sawyer Spector

I'm a Duke University computer science student concentrating in **AI and Machine Learning**.
As an NLP intern at **SAS**, I built and evaluated a RAG pipeline over SAS's technical documentation. I've also led product and UX design for **GreySun Technologies**, a wearable health-tech startup.

---

## Experience

### 🔹 SAS Institute — Natural Language Processing Intern (Summer 2026)
Built and evaluated an end-to-end RAG pipeline over ~1,350 PDFs and ~20K HTML pages of SAS documentation.
- Improved a semantic chunker that outperformed SAS's standard chunker on 6 of 8 retrieval and evaluation metrics
- Developed a reusable evaluation harness comparing 3 chunking strategies across models and datasets, adopted for future team projects
- Presented results to 100+ members of SAS R&D and at the intern expo

*Code is proprietary to SAS and not public.*

### 🔹 [GreySun Technologies — Inventor & Digital Design Director (2021–Present)](https://github.com/Sawyerspector/Greysun-Greyband-Portfolio)
Led UI/UX architecture and prototyping for GreyBand, a wearable breathalyzer and companion app.
- Designed web and mobile interfaces in Figma and Adobe
- Co-inventor on a pending patent for the wearable BAC device

---

## Technical Focus Areas
- **AI/ML:** RAG pipelines, LLM evaluation (RAGAS, retrieval metrics), agentic systems, PyTorch, Hugging Face Transformers, LangChain, MCP, quantization
- **Software Engineering:** Python, TypeScript, Java, C/C++, SQL, Git, Docker, Linux/Bash
- **Full-Stack:** Next.js, Supabase/PostgreSQL, pgvector
- **Systems & Architecture:** C, MIPS assembly, CPU/datapath design, digital logic (Logisim Evolution)
- **Game Development:** Unreal Engine 5, C++, Blueprint scripting

---

## Featured Projects

### 🔹 [Medical Document Assistant](https://github.com/Sawyerspector/medical-document-assistant) *(in development)*
Medical records are scattered across portals and health systems and hard to keep track of. This local-first app brings documents, schedules, and visit history into one place for clinicians and patients, organizes records automatically, and answers questions about them with citations back to the source document and page.
Built with **Python/FastAPI**, **ChromaDB**, a local **Llama 3.1 8B** model via Ollama (swappable for any OpenAI-compatible endpoint), and a **React, Vite, and TypeScript** frontend.
- Page-aware chunking, a calibrated retrieval distance cutoff, and citation validation, so answers say "not found" instead of guessing
- Synthetic QA evaluation suite with pytest covering retrieval hits, citation source matching, document scoping, and not-found behavior
- Explicit parse status for every upload (parsed, empty, needs OCR, failed), so problem files never disappear silently
- Privacy-first by design: runs entirely on the user's machine, and remote LLM use is off by default
- Refined with feedback from healthcare professionals; awaiting server integration to run AI locally inside a clinic

### 🔹 [Silk — Unified LLM Marketplace](https://github.com/Sawyerspector/silk-llm-marketplace)
Full-stack platform to discover, compare, and test LLMs, co-built with three teammates in **Next.js, TypeScript, and Supabase/PostgreSQL** for Duke CS316.
Features a streaming model sandbox, a metered API gateway, atomic prepaid billing via Stripe, and pgvector-powered hybrid search. I implemented the cart and model-access flow.

### 🔹 [CS250 Computer Architecture Portfolio](https://github.com/Sawyerspector/cs250-computer-architecture-projects)
- A full **16-bit single-cycle CPU** designed from scratch in Logisim Evolution
- C systems programs with manual memory management and data structures
- MIPS assembly implementations (recursion, data parsing, linked lists)
- Digital logic circuits (16-bit adder/subtractor, FSMs)

### 🔹 [Light Runner](https://github.com/Sawyerspector/Light-Runner)
Third-person platformer built in **Unreal Engine 5 with C++ and Blueprints**, featuring custom grappling and dash systems and light-dependent traversal.

### 🔹 More
- [UCLA Game Lab Portfolio](https://github.com/Sawyerspector/UCLA-GameLab-Portfolio): four games prototyped at the UCLA Game Lab Summer Institute

---

## Contact
- **Email:** sawyer.spector@gmail.com
- **LinkedIn:** https://www.linkedin.com/in/sawyer-spector-2b89a5302/

---

Thanks for stopping by! I'm always interested in collaborating on ML systems, LLM tooling, and projects where models have to work on real data.
