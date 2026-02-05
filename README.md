# AI-Driven Content Orchestration Engine (HITL) 🚀

### **The Problem**
Maintaining a consistent professional presence on LinkedIn while undergoing an intensive career pivot is time-consuming. There is often a friction point between having a raw insight and having the time to draft a polished, high-impact post that maintains an authentic "Learning-in-Public" voice.

### **The Solution**
I architected an end-to-end **Human-in-the-Loop (HITL)** system using **Vellum** and **Gmail APIs** to automate LinkedIn content production, reducing manual drafting time by ~75%. This workflow allows me to "email a thought" and receive a fully formatted LinkedIn draft back in my inbox for final review.

---

## 🛠️ Tech Stack
- **Orchestration:** Vellum AI
- **Language Models:** LLM Integration (GPT-5 Mini OpenAI)
- **API Integration:** Gmail API
- **Scheduling:** Automated cron-triggers (Mon/Wed/Fri at 9 AM IST)

---

## ⚙️ How it Works
1.  **Flexible Triggering:** The workflow runs on a set schedule or can be triggered manually within the Vellum interface.
2.  **Topic Extraction:** It searches my Gmail for the subject "LinkedIn Topic" sent within the last 24 hours to ensure relevance.
3.  **Intelligent Fallback:** If no email is found, the **Resolve Topic** node utilizes a curated list of fallback themes, such as the transition from Investment Banking to Supply Chain AI.
4.  **AI Generation:** A prompt utilizes my background as a former **Deutsche Bank AVP** to generate an authentic post with hooks, hashtags, and engagement questions.
5.  **Human-in-the-Loop:** The finalized draft is sent back to my email, ready to be edited before posting
.

---

## 🚀 Key Features
- **Authentic Voice:** Posts reflect a real learning journey rather than "fake" expertise.
- **24-Hour Safety Window:** Prevents the system from accidentally picking up old, outdated emails.
- **Flexible Inputs:** I can send a topic via email or type it directly into the Vellum input panel.

---
