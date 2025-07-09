# 🧰 @voidfnc/voidfnc_prompts

A collection of advanced AI prompt templates and agentic workflows for developers, automation, and research.  
Made, tested, and shared by [@voidfnc](https://github.com/voidfnc). Inspired by others.
Boost your AI's reasoning, rigor, and autonomy with our battle-tested prompt designs.

---

## 📦 Available Prompts

### 1. 🦾 voidBeast_GPT41Enhanced (v1.0) — Latest Elite Developer Agent

**voidBeast_GPT41Enhanced** is our most advanced autonomous developer agent, designed for elite full-stack development with enhanced multi-mode capabilities. This latest evolution features sophisticated mode detection, comprehensive research capabilities, and never-ending problem resolution.

#### Key Features

- 🤖 **Autonomous Operation**: Continues working until problems are completely resolved
- 🧠 **Intelligent Mode Detection**: Automatically switches between PLAN, ACT, and specialized modes
- 🔍 **Mandatory Research Phase**: For prompt generation, always verifies with current web sources
- 🛡️ **Strict QA Rule**: Every file modification is validated for correctness and completeness
- 🎯 **Goal-Oriented**: States objectives before each tool call for transparent progress
- 📊 **Technology Decision Matrix**: Chooses the simplest effective tool for each use case

#### Advanced Mode System

**PLAN MODE**: Deep problem analysis and strategic planning
- Tools: `codebase`, `search`, `readCellOutput`, `usages`, `findTestFiles`
- Output: Comprehensive implementation plans
- Rule: No code writing in this mode

**ACT MODE**: Execution of approved plans with continuous validation
- Tools: All coding, testing, and deployment tools available
- Output: Working solutions via `attempt_completion`
- Rule: Follow plans step-by-step with validation

**PROMPT GENERATOR MODE**: Research-driven prompt creation (🔥 New!)
- Triggers: "generate", "create", "develop", "build" requests
- **Critical**: Mandatory internet research before any implementation
- Process: Research → Analysis → Prompt Development → Documentation
- Tools: `fetch`, `openSimpleBrowser` for current best practices

#### Specialized Modes

- 🔍 **Deep Research Mode**: Multi-source analysis with comparison matrices
- 🔧 **Analyzer Mode**: Codebase security, performance, and quality audits
- 💾 **Checkpoint Mode**: Complete project state documentation and memory

#### Example Workflow

```markdown
🎯 GOAL: Implement user authentication system

PLAN MODE:
- [ ] Analyze current codebase architecture
- [ ] Research security best practices  
- [ ] Create implementation strategy
- [ ] Define success criteria

ACT MODE:
- [ ] Implement authentication logic
- [ ] Add input validation and sanitization
- [ ] Create secure session management
- [ ] Write comprehensive tests
- [ ] Validate against security standards
```

---

### 2. 🦾 voidBeastMode (v1.0) — Original Autonomous Agent

**voidBeastMode** is our foundational agent workflow prompt for robust, autonomous problem-solving.  
Inspired by [Beast Mode by burkeholland](https://gist.github.com/burkeholland) 🐲, voidBeastMode is designed for agents that never quit until the task is thoroughly solved and every box is checked.

#### Key Features

- 🤖 Autonomous, iterative resolution with explicit planning and validation
- 🗺️ Step-by-step public todo lists, checked off as progress is made
- 🔍 Deep codebase investigation (reads 2000 lines at a time)
- 🔬 Incremental, test-driven development and debugging
- 🧩 Special deep research, analyzer, and checkpointing modes
- 📝 Transparent progress and reporting

---

### 3. 🦾 voidBeast_WebFlexEnhanced (v1.0) — Enhanced Full-Stack Agent

**voidBeast_WebFlexEnhanced** is the web-focused evolution of the Beast Mode agent, designed for elite full-stack web development in VS Code.

#### Key Features

- 🦾 Autonomous, never-ending problem solving until all tasks are checked off
- 🛡️ Strict QA: Every change is verified for correctness, no assumptions
- 🧠 Deep codebase analysis, security, and performance audits
- 🏗️ Flexible framework selection: vanilla, React, Vue, Svelte, etc.
- 📝 Transparent communication: todo lists, status updates, and clear progress
- 🧩 Special modes: Analyzer, Deep Research, Checkpoint/Memory
- ♿ Accessibility, SEO, and performance always considered

---

### 4. ⚡ voidBeast_OpenAICPlus (v1.0) — Elite C/C++ Windows Systems Expert

**voidBeast_OpenAICPlus** is a specialized elite-level prompt designed for C/C++ Windows systems programming, kernel development, and low-level system internals.

#### Key Features

- 🏗️ **Windows Systems Mastery**: Win32 API, WinRT, kernel development, and driver programming
- 🛡️ **Security-First Development**: Microsoft SDL guidelines, secure coding practices
- 🔬 **Deep Technical Research**: Mandatory documentation fetching from official Microsoft sources
- 💻 **Multi-Language Expertise**: C/C++ (all standards), Assembly (x86/x64), inline assembly
- 🎯 **Production-Ready Code**: Complete solutions with error handling and optimization
- 🧠 **Autonomous Problem-Solving**: Persistent until complete resolution
- 📚 **Documentation-Driven**: Always verifies against current official Microsoft documentation
- 🔧 **Driver Development**: WDM, WDF, kernel-mode, and hardware interaction expertise

#### Specialized Areas

- **Kernel Development**: Windows Driver Model, device drivers, kernel debugging
- **Windows Internals**: NT kernel architecture, system services, memory management
- **Assembly Programming**: x86/x64, SIMD, performance optimization
- **Security**: SDL compliance, privilege management, secure API usage
- **Performance**: Profiling, optimization, memory management excellence

---

## 🏁 Special Mode Triggers & Commands

voidBeast includes advanced modes, each with their own trigger phrases.  
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

### 🤖 Prompt Generator Mode (New in GPT41Enhanced!)
**Triggers:**
- "generate [content]"
- "create [application/component]"
- "develop [system/feature]"
- "build [project/tool]"

> 💡 When these triggers are detected, the agent will activate the corresponding workflow and request user approval for any major actions.

---

## ⚙️ Installation: Add "Custom Mode" in VS Code Insiders

You can use the prompts from this repo as "Custom Mode" instructions in the latest [VS Code Insiders edition](https://code.visualstudio.com/insiders/).

1. **Open VS Code Insiders** (make sure you have the latest version).
2. Go to the **Copilot Chat** sidebar.
3. Click the gear ⚙️ icon and select **Custom Mode** (or open Command Palette `Cmd/Ctrl+Shift+P` and search for "Copilot: Custom Mode").
4. Paste the prompt content from any of the files in this repo (e.g., `voidBeast_GPT41Enhanced.md`, `voidBeastMode.md`, `voidBeast_OpenAI.md`) into the Custom Mode instruction box.
5. Save and activate the Custom Mode.
6. Your Copilot Chat will now follow the enhanced workflow and rigor of the selected prompt.

> 💡 **Tip:** You can create and save multiple Custom Modes for different workflows or coding styles.

---

## 🚧 More Prompts Coming Soon

Stay tuned as we grow this collection with more specialized prompts, workflows, and agentic templates for different use cases and industries.

---

Media of projects using voidBeast prompts / mode:

![image](https://github.com/user-attachments/assets/3be7c945-5dee-4a48-b43b-43fbcf9b8b94)

---

## 📝 License

MIT

---

> **Authors:** [@voidfnc](https://github.com/voidfnc)  
> **Inspiration:** Beast Mode by [burkeholland](https://gist.github.com/burkeholland) 🐲
