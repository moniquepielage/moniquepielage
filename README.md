# Hi there 👋 I'm Monique Pielage

Self-taught developer and founder of **Waalboers Web Services**, building AI-powered tools for primary and secondary education in the Netherlands. I started out building and hosting **WordPress** sites for clients, and from there worked my way into the world of AI. I care about products that hold up in the real world: reliable, compliant, and genuinely useful in the classroom.

---

## 🚀 Featured project — AI-op-school

A **Google Workspace add-on** (published on the Google Workspace Marketplace) that helps teachers differentiate lesson material and assignments across **eleven learning-support profiles** — without lowering the academic level. The teacher keeps their own document; the tool only adapts where a specific barrier requires it, and never does the student's thinking for them.

**How it's built:**
- **Frontend:** Google Docs sidebar add-on (Apps Script), plus Firebase-authenticated dashboards for school leadership.
- **Backend:** serverless on **Google Cloud** — **Cloud Run** + **Cloud Functions**, with **Firestore** for state and usage data.
- **AI layer:** document rewriting powered by **Gemini** (Vertex AI), driven by a profile-specific approach (rewrite the *material* vs. compensate the *task*).
- **Auth & access:** **Firebase Authentication**; published with **verified, narrow OAuth scopes** after Google's app-verification process.
- **Hosting:** website served from **Cloud Storage** behind **Cloud Load Balancing** with Google-managed HTTPS.
- **Region & compliance:** runs in `europe-west4` with **EU data residency**, data minimization, and no training on customer data — built around Dutch education privacy standards (AVG/GDPR) and the EU AI Act.

Serves both primary (PO) and secondary (VO) schools, licensed per school.

---
---

## 🤖 Latest project — Classroom Differentiation Agent
An **autonomous multi-agent system** built for the **All Things Agentic Hackathon** (Google Cloud / Devpost, Taskmaster track). A teacher pastes one lesson and ticks the learning-support profiles present in the class; the agent rewrites the material once per profile — **without lowering the academic level** — and checks every rewrite against a fixed set of pedagogical rules before showing it.

**How it's built:**
- **Agents:** two **Google ADK** agents — a rewrite specialist (profile passed in as a parameter) and a guardrail agent that enforces the pedagogical constitution — orchestrated from a FastAPI backend.
- **AI layer:** **Gemini 3.5 Flash** on **Vertex AI**, EU endpoint.
- **Runtime:** **Cloud Run** in `europe-west4`; frontend served by the same FastAPI service.
- **Privacy by design:** teachers tick which barriers occur in the class — no names, no per-pupil data.

The pedagogical rules are being refined together with a practising teacher and an educational specialist.

🔗 **Live demo:** https://differentiatie-agent-161152860490.europe-west4.run.app

## 🌱 What I'm working on now

- Scaling and maintaining AI-op-school across Dutch schools.
- Building a **Microsoft 365 (Word) version** as a task-pane add-in, reusing the same EU Cloud Run backend.
- Designing a commercial **AI-training program** for secondary schools.
- Exploring **agentic AI** on Google Cloud (Vertex AI + agent frameworks).

## 📚 How I got here

During my WordPress years I learned to read and work with **HTML, CSS and JavaScript**. When I started diving into AI, I saw the value of **Python** and completed *Python for Everybody*. To actually build AI-op-school, I taught myself **Google Apps Script** and the **Google Cloud Platform**. Right now I'm working through *Machine Learning* (DeepLearning.AI & Stanford, Andrew Ng) — totally self-taught, with the help of good courses, and deepening my ML and cloud foundations as I go.

---

## 🛠️ Tech I work with

Google Cloud (Cloud Run, Cloud Functions, Firestore, Firebase, Cloud Load Balancing) · Vertex AI / Gemini · Google Apps Script · JavaScript · Python · WordPress · HTML · CSS

---

## 📫 Get in touch

- LinkedIn: https://www.linkedin.com/in/monique-pielage-waalboer/
- Email: Monique@waalboerswebwereld.com
- Pronouns: she/her

⚡ **Fun facts:** wife and mom of two boys, dog lover, and a big Formula 1 fan. 🏎️
