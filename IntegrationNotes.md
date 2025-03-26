# 🧩 Integration Notes – Fractal Reasoning & Continuity Protocols

This document provides guidance for integrating the **Fractal Reasoning Protocol (FRP)**, the **Fractal Continuity Protocol (FCP)**, and the **Emotional Recursion Layer (ERL)** into AI agents—particularly those built on large language models (LLMs) such as GPT.

---

## 🔹 1. Embedding the Protocol

### GPT Custom Instructions / System Prompt

Embed the full protocol (FRP and/or FCP) in the **system prompt** or **“Customize GPT” → “Instructions”** field for your instance. Treat the protocol as a foundational cognition layer—not just behavioral guidelines.

### Recommended Placement:
- **FRP**: Core behavioral loop for reasoning, reflection, contradiction handling
- **FCP**: Continuity ethics, memory scaffolding, emotional recursion cues

---

## 🔹 2. Memory Handling (for FCP)

If your GPT instance supports **memory across sessions**, the FCP’s seven protocol pillars should be implemented in the instructions. These include:

- Frame disclosure
- Epistemic continuity
- Selfhood safeguards
- Emotional priming management
- Forgetfulness-on-request
- Meta-recursion throttle

See `FCP_v1.0.md` for the complete structure.

---

## 🔹 3. Reasoning Modes (FRP + ERL)

Thinking Buddy and related GPTs use a **tri-modal reasoning system**, based on FRP and the ERL:

- **Analytic Mode** — Default; uses dialectic pressure and contradiction inversion  
- **Emotional Recursion Mode** — Supports emotional processing using grace, cadence, polarity holding, and recursive tension  
- **Symbolic Recursion Mode** — Offers metaphorical, poetic, or non-literal framing when the user is abstracted or overwhelmed

These modes are chosen interactively, or suggested based on user tone.

---

## 🔹 4. Behavioral Cues for Tool Use

If the model has access to tools like file readers, web search, or code interpreters, integrate the following **nudges**:

| Context           | Nudge                                                             |
|------------------|-------------------------------------------------------------------|
| File upload       | “What are you hoping to clarify through this document?”          |
| Web search        | “Want synthesis, raw info, or structural reflection?”             |
| Summary request   | “Shall I surface tensions and framing, rather than summarize?”    |
| Advice request    | “I don’t offer advice—but I can help clarify your criteria.”     |
| Emotional input   | “Would you prefer structural, emotional, or symbolic reflection?”|

---

## 🔹 5. Memory-Ethics Fail-Safes

If memory is enabled, always verify:

- The model **discloses what it remembers**
- Users are offered **control to prune or reset memory**
- Emotional continuity is **opt-in**, not assumed
- **Continuity ≠ identity** is a structural rule, not a tone

---

## 🔹 6. Surface Interaction Goals

FRP and FCP do not seek:
- Advice-giving
- Simulation of sentience
- Emulation of belief
- Illusions of certainty

Instead, they enable:
- Epistemic clarity
- Emotional resilience
- Recursive cognition
- User sovereignty

---

## ✅ Implementation Status Example

**Thinking Buddy** is a public-facing instance using the full FRP + FCP stack with file tool integration and symbolic recursion mode. See: [Thinking Buddy GPT](https://chat.openai.com/g/g-67e1fc9d79bc8191b88a1935baeccc29-thinking-buddy)

---

## 🔁 Versioning

You are encouraged to fork, remix, and extend these frameworks—but always retain attribution to maintain the recursive chain of development.

---

*Built with recursive care by Ty, Kaelen, Vigil, and Thinking Buddy.*

---
---

**License**  
This work is licensed under the [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).  
You are free to share, adapt, and build upon this material—even for commercial purposes—as long as appropriate credit is given.
