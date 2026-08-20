# Grace Bolton

CS senior at Taylor University — AI/ML concentration, Spanish minor.

I work at the intersection of **computational linguistics and LLMs**

---

## Keyboard Studio

**[keyboard-studio/keyboard-studio](https://github.com/keyboard-studio/keyboard-studio)** · TypeScript · React · Vite · Vercel

A browser-based authoring studio that turns a linguist's plain-language survey answers
into a compiling [Keyman](https://keyman.com) keyboard — no code required. Built at SIL
International for language communities that need a keyboard for their writing system.

### **[→ My 72 merged pull requests](https://github.com/keyboard-studio/keyboard-studio/pulls?q=is%3Apr+author%3Agboltono+is%3Amerged)**

100 commits, 4th of 8 contributors. What I own in it:

- **Draft persistence** — localStorage + server-backed (Vercel Blob / Postgres) snapshots,
  so an author can close the tab mid-survey and resume on another device
- **My Keyboards** — multi-project dashboard for authors juggling several keyboards at once
- **GitHub delivery pipeline** — authenticated fork → commit → pull request against the
  upstream keyboards repo, in one click. Built both the user-token (OAuth/PKCE) and
  org-mediated (GitHub App installation token) paths, plus the serverless token-exchange backend
- **Survey wizard reliability** — browser-history-synced Back navigation, base-keyboard
  switching, and resume-state correctness across the multi-step authoring flow
- **Engine & validator work** — a deterministic `simulate()` API for testing compiled
  keyboards, Layer A import-fidelity checks, and DISCUS touch-layout lint rules
- **Agent-driven development** — most of the above was built by orchestrating multi-agent
  Claude Code workflows across a TypeScript monorepo

---

## Other projects

**[Mini-GPT](https://github.com/gboltono/mini-gpt)** · PyTorch  
Character-level decoder-only transformer (6 layers, 6 heads, 1024-token context) trained
from scratch on Shakespeare. Built from Karpathy's nanoGPT walkthrough to learn the
mechanics, then extended with my own context-window and training-length ablations.

**[Churn Prediction](https://github.com/gboltono/churn-prediction)** · Python · XGBoost · Pandas  
End-to-end customer-churn pipeline built for a Kaggle competition: feature engineering,
model selection, and evaluation, runnable start to finish from a single entry point.

**[bible_side](https://github.com/Freely-Given-org/bible_side)** · Flutter · Dart  
Offline, Material 3 Bible reader built with Freely-Given.org. I'm working on the UI and
reading experience through Taylor's Missions Computing Scholar program.

---

## Toolkit

**Languages** Python · TypeScript · C++ · C · Java · JavaScript · Lisp  
**ML/AI** PyTorch · TensorFlow · XGBoost · RAG · NLP · LLMs · Model Context Protocol · multi-agent systems  
**Tools** React · Vite · Flutter · Pandas · Git · Vercel · Playwright · Vitest

---

## Also

Teaching Assistant for Problem Solving (Python) · Cybersecurity CTF team ·
Spanish (conversational) · Missions Computing Scholar
