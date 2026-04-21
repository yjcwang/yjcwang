# Hi, I'm Yujiachen Wang 👋

🎓 M.Sc. Informatics @ Technical University of Munich  
🇯🇵 Exchange Student @ Osaka University  
💻 Focus: AI-enabled Systems · Full-stack Engineering

---

## 🚀 Projects

### AI-Powered Japanese Reading Workflow
👉 https://github.com/yjcwang/ai-reading-workflow
[Demo Video Link Here](https://youtu.be/NV0gn7CtJrc)

Full-stack system for structured language learning workflow from real text using LLMs.

**What I built**
- Extracts key vocabulary and grammar from Japanese text (JLPT-aware)
- Supports word-level and sentence-level contextual explanation
- Allows users to build list, export PDF and save persistent result
- Provides AI-generated reading content to create a closed learning loop

**Technical Highlights**
- Designed a reusable LLM integration layer (OpenAI / DeepSeek / Ollama) with structured JSON output and schema validation  
- Built modular frontend architecture using feature hooks (analyze / explain / export)  
- Implemented FastAPI backend with clear service abstraction and Pydantic schemas  
- Handled unreliable LLM responses via JSON extraction + retry logic  

**Tech Stack**
Next.js · TypeScript · FastAPI · Pydantic · LLM APIs  

---

### TOCwise (Chrome Extension)  
👉 https://github.com/yjcwang/TOCwise
[Demo Video Link Here](https://youtu.be/NV0gn7CtJrc)

Chrome extension for generating real-time structured outlines from long LLM conversations.

**What I built**
- Generates semantic table-of-contents for long chat sessions  
- Enables quick navigation and better understanding of long context  

**Technical Highlights**
- Integrated on-device LLM (Gemini Nano) for privacy-preserving inference  
- Designed adaptive text segmentation for long-context inputs  
- Built Chrome Side Panel extension with persistent UI state  

**Tech Stack**
JavaScript · Chrome Extension API · Gemini Nano  

---

### Concept Hierarchy Visualization & Constraint Solver (Bachelor Thesis)  

Research project on robotic task planning and spatial reasoning.

**What I built**
- Designed and implemented a new method to compute feasible locations under multiple spatial constraints  
- Developed a real-time visualization system for hierarchical knowledge structures  

**Technical Highlights**
- Modeled constraint intersection as a linear constraint problem (Ax > b)  
- Solved via CNF transformation + DFS backtracking + linear programming  
- Implemented interactive graph visualization using D3.js with incremental updates  
- Addressed numerical stability and floating-point issues in geometric computation  

**Tech Stack**
C++ · D3.js · Linear Programming (CLP) · GoogleTest  

---

## 🛠 Tech Stack

**Languages**  
Python · TypeScript · JavaScript · C/C++ · Java  

**Frameworks & Tools**  
FastAPI · Next.js · React · Pydantic · Git  

**AI & Systems**  
OpenAI · DeepSeek · Ollama · OpenAI · Gemini Nano  

---

## 📫 Contact

- Email: ge84qoh@mytum.de  
- GitHub: https://github.com/yjcwang  
