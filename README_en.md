# SoloCorp OS 🏢

[English](README_en.md) | [中文](README_zh.md) | [日本語](README.md)

### An Open-Source OS designed for a single human to lead "4 AI Legions" and run a virtual enterprise solo.

> *"You are no longer a prompt engineer. You are the CEO of a one-person enterprise commanding AI legions."*

---

## What is this?

**SoloCorp OS** is a **virtual development organization template**. It assigns specific "roles" (CEO, CTO, CMO, etc.) to AI, allowing a single person to operate like a multi-dozen-person enterprise.

This is not just a collection of prompts.
It is an **"Operating System"** that forces AI to autonomously handle the entire engineering lifecycle: Planning, Design, Implementation, QA, and Release. It eliminates half-hearted human micromanagement and utilizes an "Agent-under-Agent" structure where AI reviews AI.

---

## The 4 Specialized AI Legions (Skills Breakdown)

SoloCorp OS comes pre-installed with 4 "Legions" (clusters of agents) that act on your behalf. Each legion is internally divided into specific roles and runs a highly autonomous loop (discussion, review, correction) without human intervention.

### 📈 1. Investment Legion
**Purpose:** Investment decisions, market analysis, financial modeling.
**Internal Structure:**
- **Researcher:** Gathers financial data and market trends of target companies.
- **Quant Analyst:** Builds both "Bull" and "Bear" scenarios logically based on the data.
- **Devil's Advocate:** Ruthlessly criticizes the Quant's analysis ("your premise is too optimistic") to eliminate blind spots and risks.
- **👉 Result:** Only highly accurate, stress-tested "Investment Memos" are submitted to the CEO.

### 🏢 2. Consulting Legion
**Purpose:** Client work, strategic planning, problem-solving proposals.
**Internal Structure:**
- **Strategist:** Doubts the "surface-level problem" given by the CEO and identifies the true bottleneck (using the 5 Whys).
- **Consultant:** Logically designs solutions with 3 options: Conservative, Bold, and Fastest.
- **Ruthless Partner:** Rejects generic, boring proposals ("AI slop") and polishes them into sharp, edgy strategies that clients will actually pay for.

### 🎨 3. Creator Legion
**Purpose:** Social media content, article writing, marketing.
**Internal Structure:**
- **Trend Analyst:** Identifies current buzzwords and the target audience's true desires/frustrations.
- **Copywriter:** Drafts the content, generating multiple "Hooks" (first 35 characters) and selecting the strongest one.
- **Ruthless Editor:** Detects "AI Slop" (robotic, generic styles) and forces at least two rewrites to ensure the content is viral, unique, and human-like.

### 💻 4. Dev Legion
**Purpose:** App development, website creation, GitHub management, bug fixing.
**Internal Structure:**
- **EM (Engineering Manager):** Designs the architecture and anticipates the worst-case failure modes before coding.
- **Senior Coder:** Writes robust code based on the EM's architecture.
- **QA / Debugger:** Tests the code with the intent to break it (happy path, edge cases, boundaries). If bugs are found, it autonomously forces the coder to fix them without bothering the CEO. It loops infinitely until it is "guaranteed to work".

---

## How to Use (Start in 30 Seconds)

### Step 1: Clone this repository
Open your terminal and run this in your project folder:
```bash
git clone https://github.com/0xpandadev/solocorp-os.git
```

### Step 2: Launch your AI Assistant
Open your favorite AI coding assistant (Cursor, Claude Code, OpenClaw, etc.) in this folder. The AI will automatically read `SOLOCORP.md` and awaken as your "Hub Manager".

### Step 3: Just talk to it
Simply mention a Legion and your goal:
- *"Use the Creator Legion to write a viral article about the current AI boom."*
- *"Use the Investment Legion to determine if I should invest in company X."*
- *"Use the Dev Legion to fix the bugs in this directory."*

**That's it. The AI Legions (internal agents) will handle the rest.**

---

## Context Preservation System
All your instructions and business directions are automatically stored in the `notes/` directory.
- Simply write your core vision in `notes/INTENT.md`, and the AI will execute every task aligned with that "Why".

---

## Inspired By
This OS integrates the philosophies of three great pioneers:
1. **Boris Cherny (Claude Code Creator)**: The concept of a strict "Self-Learning and Context Maintenance loop" via `CLAUDE.md`.
2. **Garry Tan (Y Combinator CEO)**: The concept of "Assigning roles to AI" and specific engineering workflows via `gstack`.
3. **Yang Tianrun (Naughty Labs CEO)**: The absolute rejection of micromanagement and the "Agent-under-Agent" (nested agents) framework prioritizing "High Agency."

---

## Contribution & License
MIT License — Fork it. Improve it. Make it yours.
Feel free to customize the legions in `.agents/skills/` to fit your exact business needs.
