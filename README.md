# 🩺 Zoya — Production AI Healthcare Coach

> **Multilingual AI health coach with voice + text interface, prescription & lab report analysis, and persistent memory. Deployed at production scale serving thousands of daily users.**

---

## 📊 Production Impact

| Metric | Result |
|---|---|
| Deployment | Live production system |
| Languages | English + Urdu (bilingual) |
| Modalities | Text + Voice (full duplex) |
| Memory | Persistent per-user across sessions |
| Document analysis | Prescriptions + Lab reports |

---

## 🧠 What Zoya Does

Zoya is a production-grade AI healthcare coach that users interact with via **text or voice** in **English or Urdu**. She:

- Answers health, wellness, and medication questions in natural language
- **Reads and explains the user's own prescription** — medications, dosage, instructions
- **Analyzes the user's lab test reports** — what values mean, what's normal, what needs attention
- Remembers past conversations — knows the user's history, conditions, and preferences
- Responds naturally in both English and Urdu depending on what the user prefers

---

## 🛠️ Tech Stack

| Component | Technology |
|---|---|
| Agent Framework | LangGraph |
| LLM | GPT-4o |
| STT (Speech-to-Text) | Groq Whisper |
| TTS (Text-to-Speech) | ElevenLabs |
| Document Analysis | GPT-4o Vision |
| Languages | English + Urdu |
| Backend | FastAPI |
| Database | PostgreSQL |

---

## 📄 Document Intelligence

### Prescription Analysis
- User uploads their prescription image
- GPT-4o Vision extracts: medication names, dosage, frequency, duration
- Zoya explains each medication in simple language
- Flags anything unusual or important for the user to know

### Lab Report Analysis
- User uploads their lab test report
- GPT-4o Vision reads all values: CBC, LFT, RFT, blood sugar, lipids, etc.
- Zoya explains what each value means, the normal range, and whether the user's value is high/low/normal
- Provides a plain-language summary the user can actually understand

---

## 📁 Repository Structure

```
zoya-ai-health-coach/
├── results/              # Demo outputs and screenshots
├── README.md

```

## 🎬 Demo

📹 [Watch Full Demo Video](https://drive.google.com/file/d/1DU9hfVmXSkJwrUtHIt5S-5Wd0cOLFdjL/view?usp=sharing)

---

## 📬 Want to Know More?

This is a production system handling real patient data. Deeper implementation details, live demo, and code walkthrough available upon request.

📧 adnanabdullah.dev@gmail.com  
💼 [LinkedIn](https://linkedin.com/in/adnan-abdullah-b6b49b1b6) • [GitHub](https://github.com/adnanabdullah0405)
