<table>
  <tr>
    <td><img src="assets/pulp_logo.png" alt="PulpAI Logo" width="100"></td>
    <td><h1>PulpAI — All your accounts. One executable chat.</h1></td>
  </tr>
</table>

> **"Communication is fragmented. Relationships shouldn't be."**

PulpAI is a **Generative AI** communication layer engineered to eliminate friction in professional workflows. By transforming WhatsApp into a remote control for your digital ecosystem, we solve the "Information Overload" crisis through a **Human-in-the-Loop** approach—ensuring AI efficiency without the risk of losing control.

---

## 🔴 The Problem: Context-Switching Fatigue

Modern professionals lose **30% of their productivity** to "Efficiency Leaks": the constant toggling between Outlook, Slack, and LinkedIn to retrieve information and manage tasks.

* **Data Silos:** Information is trapped in disconnected platforms.
* **Response Inertia:** Drafting professional replies while on the move is a high-friction task.
* **The Trust Gap:** Users are reluctant to let autonomous agents communicate on their behalf without oversight.

---

## 🗺️ Roadmap: Three Phases to Market Dominance

### Phase 1: The "Zero-Inertia Inbox" (MVP - Active)
We bridge the gap between Gmail and WhatsApp using a sophisticated **Orchestration Layer**.
* **Style Mirroring:** Our engine analyzes the sender's tone (formal/casual) and drafts an optimized response.
* **Confidence through Control:** No message is sent without a one-tap manual approval.
* **Impact:** Rapid communication with zero friction.

### Phase 2: The Pulp App (Generative UI Platform)
Transitioning from a messaging bot to a native platform where static text is replaced by **Generative UI**.
* **Dynamic Adaptation:** The interface "invents" itself in real-time. If an email suggests a meeting, Pulp renders a calendar widget. If it contains an invoice, a payment terminal appears.
* **Platform Mirroring:** Every service (Gmail, Slack, Teams) is consolidated into dedicated streams within the Pulp ecosystem.
* **Core Tech:** Vercel AI SDK, React Server Components.

### Phase 3: Identity Aggregation (The Game Changer) 🏆
The ultimate evolution: Shifting from **Channel-Centric** to **Person-Centric** communication.
* **One Thread. Every Channel:** All interactions with a specific contact live in a single, unified chat.
* **Unified Intelligence:** A single chronological timeline merging an email from the morning, a Slack message from noon, and a LinkedIn DM from the evening.
* **Identity Mapping Engine:** Pulp automatically links disparate handles (Email, Slack ID, Socials) to a single verified human entity.

---

## ✨ Key Value Propositions (USPs)

* **Human-in-the-Loop (HITL):** We provide the velocity of an AI agent with the safety of a human signature.
* **Zero-Inertia Workflow:** We eliminate the barrier between receiving information and taking decisive action.
* **AI Efficiency with Total Oversight:** We automate the "grunt work" of drafting and formatting while leaving the final executive decision to the user.

---

## 🛠 Tech Stack

Phase 1: The "Speed-to-Market" Stack (MVP - Current)

**Focus:** Validation, Rapid Prototyping, and Low Overhead.

* **Orchestration:** n8n (Self-hosted)
* **LLM Engine:** OpenAI GPT-4o / Claude 3.5 Sonnet
* **Interface:** WhatsApp Business API (via Meta)
* **Data Handling:** n8n Binary & JSON Storage (Internal Database)
* **Connectors:** Gmail Nodes & Custom HTTP Request Nodes (API-First approach)

---

### Phase 2: The "Performance" Stack (Native Platform)

**Focus:** Scalability, Low Latency, and Custom User Experience.

* **Frontend:** **Next.js** (Web) & **React Native** (Mobile)
* **AI Framework:** **Vercel AI SDK** (Generative UI Components)
* **Backend:** **Node.js (TypeScript)** – Transitioning from low-code to custom microservices
* **Authentication & Database:** **Supabase (PostgreSQL)** – Relational data for user profiles
* **Real-time Layer:** **WebSockets (Socket.io)** – Instant sync for multi-channel pings

---

### Phase 3: The "Intelligence" Stack (Unified Platform)

**Focus:** Deep Data Integration and Cross-Channel Identity Mapping.

* **Memory & Context:** **Pinecone (Vector Database)** – Long-term RAG for cross-channel history
* **Identity Engine:** **Proprietary Mapping Logic** – Merging Email, Slack, and Social IDs
* **Event Processing:** **Redis / BullMQ** – High-volume message queue management
* **Deployment:** **AWS (Elastic Kubernetes Service)** – Global scaling and enterprise-grade infrastructure

---

## ⚙️ How it Works (Phase 1: The n8n Workflow)

The current MVP utilizes **n8n** as a powerful orchestration engine to bridge the gap between legacy email protocols and modern messaging interfaces.

### 1. Inbound Intelligence
* **Trigger:** The workflow monitors the **Gmail API** for incoming messages in real-time.
* **Pre-Processing:** A custom logic node filters for priority and extracts the core context, removing clutter like signatures and legal disclaimers.

### 2. Contextual Style Mirroring
* **Analysis:** The extracted content is sent to an **LLM (GPT-4o/Claude)** with a specific system prompt.
* **Tone Matching:** The AI analyzes the sender's professional tone and linguistic patterns.
* **Drafting:** It generates a high-quality response draft that mirrors the sender's style while addressing all action items.

### 3. Human-in-the-Loop Approval
* **Notification:** The draft is pushed to the user via the **WhatsApp Business API** as an interactive message.
* **Validation:** The user can review, edit, or approve the draft with a single tap.
* **Execution:** Upon approval, an **HTTP Request Node** triggers the final Gmail send-action, maintaining the original thread integrity.

---

### 🛡️ Core Principles

* **Privacy by Design:** Data is only processed during the active workflow execution. No emails are stored permanently in the orchestration layer.
* **Confidence through Control:** We eliminate "AI hallucinations" from reaching the client by keeping the human user as the final gatekeeper.
* **Zero-Inertia:** Decisions are made where you already spend your time: in your mobile messaging app.

---

## 🤝 Investment & Vision

PulpAI is building the **Invisible OS** for professional communication. We are currently scaling from our successful **n8n Proof-of-Concept** to a robust, native architecture.

**Are you ready to eliminate the efficiency leaks and build the future of the Unified Feed?**

---
[Contact / GitHub Link / Documentation]
