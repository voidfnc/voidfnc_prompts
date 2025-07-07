# 🦾 voidBeastMode Prompt

Welcome to **voidBeastMode** — an advanced AI agent workflow prompt designed for thorough, autonomous problem-solving.  
This prompt is part of the [`@voidfnc/voidfnc_prompts`](https://github.com/voidfnc/voidfnc_prompts) collection.

---

## 🚀 Overview

**voidBeastMode** empowers agentic models and AI assistants to tackle user queries autonomously and rigorously.  
It leverages a carefully structured process to ensure each problem is deeply understood, investigated, planned, executed, and validated before returning control.  
The workflow emphasizes iterative progress, comprehensive planning, and strict validation for robust outcomes.

---

## ✨ Key Features

- **🤖 Autonomous, Iterative Resolution**  
  The agent proceeds step-by-step, only yielding when the problem is fully solved and all criteria are met.
- **🗺️ Explicit Planning & Reflection**  
  Requires detailed planning, with a public todo list, and frequent reflection at each step.
- **🔍 Deep Codebase Investigation**  
  Mandates reading and understanding large code context (2000 lines at a time) before code changes.
- **🔬 Incremental, Test-Driven Development**  
  Encourages small, testable changes with frequent testing and debugging.
- **🧩 Special Modes for Deep Research, Analysis, and Checkpointing**  
  - **Deep Research Mode:** For complex or multi-source tasks, requiring research, comparison, and user approval before action.
  - **Analyzer Mode:** For full codebase scans, audits, and refactor suggestions with user-approval gating.
  - **Checkpoint Mode:** For creating and documenting codebase snapshots, again requiring user sign-off.

---

## 🛠️ Workflow

1. **Understand the Problem Deeply**
   - Carefully read the user's issue or request.
   - Gather context, clarify requirements, and avoid assumptions.

2. **Investigate the Codebase**
   - Search for relevant files, functions, and classes.
   - Read 2000 lines at a time for full context.
   - Identify root causes and validate hypotheses.

3. **Develop a Step-by-Step Plan**
   - Break the solution into concise steps.
   - Display progress with a markdown todo list, checking off steps as completed.

4. **Implement and Debug**
   - Make incremental, testable changes.
   - Employ debugging and validation tools.
   - Revisit assumptions as needed.

5. **Test and Validate**
   - Run tests after each change.
   - Write additional tests for edge cases and hidden requirements.
   - Ensure all criteria are met before completion.

6. **Reflect and Document**
   - Review the original problem and confirm all aspects are addressed.
   - Document findings, process, and outcomes.

---

## 📝 Special Operating Modes

### 🔎 Deep Research Mode

- Triggers for complex research, architectural decisions, or explicit user request.
- Involves multi-source research, analysis matrix, solution ranking, and user approval before action.

### 🧮 Analyzer Mode

- For audits, refactors, and security analysis.
- Full codebase scan and report generation before requesting user approval for any changes.

### 🧷 Checkpoint Mode

- For creating codebase memories/snapshots.
- Requires comprehensive scan and user approval before finalizing the checkpoint.

---

## ✅ Example Todo List

```markdown
- [ ] Step 1: Understand the user request.
- [ ] Step 2: Investigate relevant code and files.
- [ ] Step 3: Develop a detailed plan to solve the issue.
- [ ] Step 4: Implement the solution step-by-step.
- [ ] Step 5: Test and validate after each change.
- [ ] Step 6: Reflect and document the solution.
```

---

## ⚡ Usage

You can use this prompt as a template for agentic AI models (such as Copilot, GPT agents, etc.) in any repo or workflow where you want rigorous, autonomous problem-solving with robust validation and transparent progress tracking.

---

## 📜 License

MIT

---

> **Prompt Source:** [`voidBeastMode.md`](./voidBeastMode.md)  
> **Author:** [@voidfnc](https://github.com/voidfnc)  
> For more prompts and tools, see the [`@voidfnc/voidfnc_prompts`](https://github.com/voidfnc/voidfnc_prompts) repo.  
> **Inspiration:** Beast Mode by [burkeholland](https://gist.github.com/burkeholland) 🐲  
