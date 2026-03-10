<div align="center">
  <img src="assets/pulp_logo_text.png" alt="PulpAI Logo" width="150">
  <h1>PulpAI — Your Identity. One Stream.</h1>
  <p><strong>PulpAI is your personal action layer.</strong></p>
</div>

PulpAI aggregates your fragmented digital communications into a single, executable stream. Instead of context-switching between dozens of apps like Email, Slack, WhatsApp, Instagram, or CRM tools, PulpAI extracts tasks and intent from your messages. 

It acts as the operating system for your digital identity—presenting everything in one unified chat where you can decide, approve, and act instantly. Whether for professional project management or personal life, PulpAI merges your worlds into one interface.

<div align="center">
  <a href="#roadmap">Roadmap</a> · <a href="#how-it-works">How it works</a> · <a href="https://docs.pulpai.com">Docs</a> · <a href="#getting-started">Getting Started</a>
</div>

---

## 🗺️ The Roadmap

### Phase 1: The WhatsApp Inbox
Your emails and messages arrive as summarized WhatsApp notifications with clear buttons (CTAs) to act immediately.
* **Style Mirroring:** Analyzes sender tone to draft perfectly optimized, context-aware replies.
* **Confidence through Control:** Keeps you in the loop with one-tap manual approvals before any action is taken.
* **Executable CTAs:** Turns wordy emails into simple buttons, enabling instant replies while you're on the move.

### Phase 2: The Pulp App
A single, smart interface that adapts to your tasks and replaces communication via scattered apps.
* **Generative UI:** The interface changes based on content; get a meeting request, and a calendar widget appears. Get an invoice, and a payment button pops up.
* **Platform Mirroring:** Consolidates all your services (Gmail, Slack, Teams) into one clean, unified feed.
* **Fluid Experience:** Built with Vercel AI SDK and React Server Components for a fast, native-feeling experience.

### Phase 3: Identity Aggregation 🏆
The end of channel-based messaging. All messages from one person—no matter if email, Slack, or LinkedIn—are bundled into one thread.
* **One Thread, Every Channel:** Stop hunting through apps. All interactions with a specific contact live in a single, chronological timeline.
* **Identity Mapping Engine:** Automatically links disparate handles (Email, Slack ID, Socials) to a single verified human entity.
* **Unified Intelligence:** Provides a holistic view of your relationships, decoupling your communication from the platform silos.

---

## ✨ Why PulpAI?

* **Eradicate Response Inertia:** Transform passive, wordy data into bite-sized, executable tasks. Go from "request received" to "decisive resolution" in just one tap.
* **Your Executive Command Center:** Stop managing apps; start managing outcomes. We handle the grunt work—summarizing, drafting, and structuring—while you make the final executive calls.
* **Unified Identity Architecture:** Move from channel-based noise to person-centric intelligence. We map all your fragmented accounts to one verified human entity.
* **Velocity with Vigilance (HITL):** Get the raw speed of autonomous AI, anchored by the security of human oversight. You stay the final authority; we provide the automated execution.

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
