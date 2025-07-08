# 🧰 @voidfnc/voidfnc_prompts

A collection of advanced AI prompt templates and agentic workflows for developers, automation, and research.  
Made, tested, and shared by [@voidfnc](https://github.com/voidfnc). Inspired by others.
Boost your AI's reasoning, rigor, and autonomy with our battle-tested prompt designs.

---

## 📦 Available Prompts

### 1. 🦾 voidBeastMode (v1.0) — First Release

**voidBeastMode** is our first agent workflow prompt for robust, autonomous problem-solving.  
Inspired by [Beast Mode by burkeholland](https://gist.github.com/burkeholland) 🐲, voidBeastMode is designed for agents that never quit until the task is thoroughly solved and every box is checked. Special modes added and triggers for Deep Research (Planning/Sourcing), Analyzer (Refactors/Security Audit/Optimizations), and Checkpointing / Memory mode for project saving and documentation. 
> **Note:** The core difference between `voidBeastMode` and `voidBeast_WebFlexEnhanced` is the "brain"—the main prompt logic and agentic workflow powering each mode.

#### Key Features

- 🤖 Autonomous, iterative resolution with explicit planning and validation
- 🗺️ Step-by-step public todo lists, checked off as progress is made
- 🔍 Deep codebase investigation (reads 2000 lines at a time)
- 🔬 Incremental, test-driven development and debugging
- 🧩 Special deep research, analyzer, and checkpointing modes
- 📝 Transparent progress and reporting

#### Example Workflow

```markdown
- [ ] Step 1: Understand the user request.
- [ ] Step 2: Investigate relevant code and files.
- [ ] Step 3: Develop a detailed plan to solve the issue.
- [ ] Step 4: Implement the solution step-by-step.
- [ ] Step 5: Test and validate after each change.
- [ ] Step 6: Reflect and document the solution.
```

---

### 2. 🦾 voidBeast_WebFlexEnhanced (v1.0) — Enhanced Full-Stack Agent

**voidBeast_WebFlexEnhanced** is the latest evolution of the Beast Mode agent, designed for elite full-stack web development in VS Code. It features:
> **Note:** The "brain" (main prompt/agent logic) in `voidBeast_WebFlexEnhanced` is more advanced and web-focused than the original `voidBeastMode`.

- 🦾 Autonomous, never-ending problem solving until all tasks are checked off
- 🛡️ Strict QA: Every change is verified for correctness, no assumptions
- 🧠 Deep codebase analysis, security, and performance audits
- 🏗️ Flexible framework selection: vanilla, React, Vue, Svelte, etc.
- 📝 Transparent communication: todo lists, status updates, and clear progress
- 🧩 Special modes: Analyzer, Deep Research, Checkpoint/Memory
- ♿ Accessibility, SEO, and performance always considered


---

## 🏁 Special Mode Triggers & Commands

voidBeastMode includes three advanced modes, each with their own trigger phrases.  
Type or say one of these commands to activate the corresponding mode:

### 🔎 Deep Research Mode
**Triggers:**
- "deep research"
- Task requires multi-source verification
- Complex architectural decisions needed
- Multiple viable solutions exist

### 🧮 Analyzer Mode
**Triggers:**
- "refactor [codebase/project/file]"
- "debug [codebase/project/file]"
- "analyze [codebase/project/file]"
- "secure [codebase/project/file]"

### 🧷 Checkpoint Mode
**Triggers:**
- "checkpoint [codebase/project/file]"
- "memorize [codebase/project/file]"
- "memory [codebase/project/file]"

> 💡 When these triggers are detected, the agent will activate the corresponding workflow and request user approval for any major actions.

---

## ⚙️ Installation: Add "Custom Mode" in VS Code Insiders

You can use the prompts from this repo as "Custom Mode" instructions in the latest [VS Code Insiders edition](https://code.visualstudio.com/insiders/).

1. **Open VS Code Insiders** (make sure you have the latest version).
2. Go to the **Copilot Chat** sidebar.
3. Click the gear ⚙️ icon and select **Custom Mode** (or open Command Palette `Cmd/Ctrl+Shift+P` and search for "Copilot: Custom Mode").
4. Paste the prompt content from any of the files in this repo (e.g., `voidBeastMode.md`) into the Custom Mode instruction box.
5. Save and activate the Custom Mode.
6. Your Copilot Chat will now follow the enhanced workflow and rigor of the selected prompt.

> 💡 **Tip:** You can create and save multiple Custom Modes for different workflows or coding styles.

---

## 🚧 More Prompts Coming Soon

Stay tuned as we grow this collection with more specialized prompts, workflows, and agentic templates for different use cases and industries.

---

## 📝 License

MIT

---

> **Prompt Source:** [`voidBeastMode_GPT41.md`](./voidBeastMode_GPT41.md)  
> **Authors:** [@voidfnc](https://github.com/voidfnc)  
> **Inspiration:** Beast Mode by [burkeholland](https://gist.github.com/burkeholland) 🐲  
