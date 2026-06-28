# SentriAI – Intelligent Content Moderation

## Overview

SentriAI is an AI-powered content moderation system that automatically analyzes text, images, and videos to detect harmful, abusive, hateful, and inappropriate content in real time. The solution uses UiPath Maestro Case to orchestrate AI agents and human reviewers, ensuring transparent, secure, and scalable moderation workflows.

---

## Key Features

* Real-time AI content moderation
* Text, Image, and Video analysis
* AI-powered classification (Safe, Flagged, Blocked)
* Human-in-the-loop review using UiPath Action Center
* Complete audit trail with UiPath Orchestrator
* Secure and scalable case management

---

## Workflow

```text
User Upload
      │
      ▼
UiPath Maestro Case
      │
      ▼
Content Intake Agent
      │
 ┌────┼────┐
 ▼    ▼    ▼
Text Image Video
Agent Agent Agent
 └────┼────┘
      ▼
Decision Agent
      │
 ┌────┼──────┐
 ▼    ▼      ▼
Safe Flagged Blocked
 │      │       │
 │      ▼       │
 │ Human Review │
 │      │       │
 └──────┴───────┘
      ▼
 Publish / Reject
```

---

## Technologies Used

### UiPath

* Maestro Case
* Agent Builder
* Action Center
* Orchestrator

### AI & Backend

* Python
* FastAPI
* Hugging Face Transformers
* OpenCV
* Whisper AI
* PyTorch

### Frontend

* React.js
* HTML
* CSS
* JavaScript

---

## Benefits

* Faster AI-powered moderation
* Reduced manual review effort
* Human-in-the-loop governance
* Improved platform trust and safety
* Enterprise-ready architecture

---

## Repository Structure

```text
frontend/
backend/
ml-engine/
docs/
screenshots/
README.md
```

---

## Documentation

* `docs/architecture.md` – System architecture
* `docs/demo-proof.md` – Demo instructions
* `docs/examples/` – Sample agent outputs
* `docs/screenshots/` – Submission screenshots

---

## Hackathon

**UiPath AgentHack 2026**

**Track:** UiPath Maestro Case

---

## Team

Team Novatrix : Jagadeesh R(Team Lead),Indra priyadharshini V, Anusha S

**Project:** SentriAI – Intelligent Content Moderation
