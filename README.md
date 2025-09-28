# 🧪 Benchmarking Expert Chatbot Personas
_A systematic evaluation of prompt-engineered AI expert personas for academic and professional use_

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Status](https://img.shields.io/badge/status-complete-success)
![Made with](https://img.shields.io/badge/Made%20with-ChatGPT%20%26%20Prompt%20Engineering-orange)

---

## 📌 Overview
This project explores **how prompt engineering shapes the performance of AI chatbot personas**.  
It was developed as part of the *IPHS 391 – Digital Humanities: Expert Systems & AI Evaluation* course at **Kenyon College**.

Our primary case study: designing and evaluating a **Professional Ballet Teacher Chatbot** — an AI persona with elite performance background, strict but supportive teaching style, and the ability to critique dance technique.

---

## ⚙️ Methodology
1. **Persona Prompt Engineering**
   - Created a **system prompt** outlining expertise, tone, and behavior.
   - Iteratively refined the persona using *metaprompting* — testing responses and adjusting rules for clarity, authority, and consistency.
   - Stored key prompt versions in:
     - `prompt_persona.txt`
     - `metaprompt_history.txt`

2. **Conversation Benchmarking**
   - Conducted structured **10-turn conversations** with the chatbot.
   - Collected transcripts (`Chatbot history.md`).

3. **Evaluation Rubric Design**
   - Built a **0–100 scoring rubric** (`chat_rubric.txt`) focusing on:
     - Accuracy of domain knowledge
     - Consistency of persona voice & tone
     - Instructional depth & actionable feedback
     - Engagement & user experience
   - Applied rubric to our test dialogue to identify strengths and weaknesses.

4. **Reporting**
   - Summarized results and design rationale in `mp1_chatbot_report.docx`.

---

## 📊 Results
- **Persona Fidelity:** The Ballet Teacher remained authoritative, disciplined, and technically detailed in most responses.
- **Strengths:**  
  ✅ Strong use of ballet vocabulary and actionable corrections  
  ✅ Maintained a clear teaching persona with “tough love” tone  
  ✅ Delivered structured class-style feedback on request
- **Weaknesses:**  
  ⚠️ Occasionally softened tone when user asked non-technical questions  
  ⚠️ Some answers lacked the rigor expected from a real professional dancer
- **Rubric Score:** ~85/100 — indicating a **high-quality but improvable persona**.

---

## 📂 Files Description
| File | Purpose |
|------|---------|
| `prompt_persona.txt` | Final system prompt for the expert chatbot persona. |
| `metaprompt_history.txt` | Iterative refinement notes during persona development. |
| `ChatGPT-Ballet teacher persona prompt (1).md` | Prompt exploration and early drafts. |
| `Chatbot history.md` | Conversation transcript used for benchmarking. |
| `chat_rubric.txt` | Detailed evaluation rubric for scoring persona quality. |
| `mp1_chatbot_report.docx` | Final write-up with design rationale and results. |

---

## 🚀 Usage Instructions
1. **Clone the repository**
   ```bash
   git clone https://github.com/adenright/iphs391_fall2025_miniproject-1_benchmarking-expert-chatbot-personas.git
   cd iphs391_fall2025_miniproject-1_benchmarking-expert-chatbot-personas
