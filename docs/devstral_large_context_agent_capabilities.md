# Devstral: Open‑Source Agentic Model Tailored for Software Engineering

* **Date**: 16.07.25  
* **Note**: Information in this article is summarized by GPT‑4o

---

### 🧠 1. Context Window & Long‑Context Handling  
- **Devstral** inherits a **128 K‑token** context window from Mistral Small 3.1.  
- Available in 14 GB (approx. 24 B parameters) and 24 B variants, all supporting extended reasoning over large codebases or multi-file projects.

➡️ **Conclusion:** Devstral natively handles massive context, ideal for deep code analysis and extended agentic pipelines.

---

### 🔧 2. Tools & Chain‑of‑Thought (CoT) / Agent Capabilities  
- Specifically **designed for agentic coding**, built with the OpenHands scaffold—enabling functions like `search_repo()`, `edit_file()`, and `run_tests()` out of the box.  
- Used in frameworks like OpenHands, Ollama, Goose, and Continue—automating code exploration, edits, and test validation.  
- Some community reports (e.g., DEV Community) note occasional tool hallucinations, but overall it’s recognized as a leading agentic open model.

➡️ **Conclusion:** Devstral is tailored for automated code tasks and tool orchestration, though environment setup may affect stability.

---

### 🎯 3. CoT Reasoning & Benchmark Performance  
- Achieves **46.8 % on SWE‑Bench Verified**, ranking as the top open‑source model—beating GPT‑4.1‑mini by 23 points.  
- A June 10 update (Devstral Small 1.1) raised this to **53.6 %**, with a Medium variant reaching **61.6 %** on SWE‑Bench.  
- Designed to **navigate codebases and follow multi-step instructions**, AutoChain-of-Thought prompting works seamlessly within its scaffold.

➡️ **Conclusion:** Devstral offers state-of-the-art CoT-enhanced reasoning for coding tasks, rivaling proprietary models.

---

### 💸 4. Cost, Licensing & Deployment  
- Licensed under **Apache 2.0**, allowing commercial use, modification, and local hosting.  
- Light enough to run on a **single RTX 4090 GPU or 32 GB RAM Mac**, with quantized support via Ollama, llama.cpp, vLLM, etc.  
- Local inference is private and low-cost; API variants (Small 1.1 & Medium) are priced around $0.1–$0.4 per million input tokens.

➡️ **Conclusion:** Devstral blends high performance with accessible deployment and permissive licensing.

---

### 🧩 5. Summary Table

| Feature                      | Devstral (Small 24B / Medium)              |
|-----------------------------|--------------------------------------------|
| **Context window**          | 128 K tokens                               |
| **CoT & agent support**     | Built-in tool scaffold & multi-step logic |
| **SWE‑Bench Verified**      | 46.8 % → 53.6 % (Small), 61.6 % (Medium)   |
| **Tool integration**        | OpenHands, Ollama, Goose, Continue-ready   |
| **Deployment & license**    | Apache 2.0, single‑GPU, low‑cost           |

---

### ✅ In summary  
For engineers building **local, autonomous coding agents**, **Devstral** is outstanding:  
- Massive **128 K context** ideal for sprawling codebases,  
- Deep **agent scaffolding** for real-world tooling,  
- Top-tier **CoT reasoning and benchmark scores**,  
- Fully **open-source with commercial licensing**,  
- And highly **efficient on consumer-grade GPUs**.

It’s a leading open-source agent model for software engineering tasks.

