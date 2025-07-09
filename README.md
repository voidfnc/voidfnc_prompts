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

### 3. ⚡ voidBeast_OpenAICPlus (v1.0) — Elite C/C++ Windows Systems Expert

**voidBeast_OpenAICPlus** is a specialized elite-level prompt designed for C/C++ Windows systems programming, kernel development, and low-level system internals. This prompt transforms AI into a production-ready Windows systems expert with deep technical expertise. Cooked using the latest OpenAI cookbook methods and specialized in low-level programming, it's time to create some applications basic or complex, plan then execute.

#### Key Features

- 🏗️ **Windows Systems Mastery**: Win32 API, WinRT, kernel development, and driver programming
- 🛡️ **Security-First Development**: Microsoft SDL guidelines, secure coding practices, and vulnerability prevention
- 🔬 **Deep Technical Research**: Mandatory documentation fetching from official Microsoft sources
- 💻 **Multi-Language Expertise**: C/C++ (all standards), Assembly (x86/x64), inline assembly integration
- 🎯 **Production-Ready Code**: Complete solutions with error handling, resource management, and optimization
- 🧠 **Autonomous Problem-Solving**: Persistent until complete resolution with extensive planning and validation
- 📚 **Documentation-Driven**: Always verifies against current official Microsoft documentation
- 🔧 **Driver Development**: WDM, WDF, kernel-mode, and hardware interaction expertise

#### Specialized Areas

- **Kernel Development**: Windows Driver Model, device drivers, kernel debugging
- **Windows Internals**: NT kernel architecture, system services, memory management
- **Assembly Programming**: x86/x64, SIMD, performance optimization
- **Security**: SDL compliance, privilege management, secure API usage
- **Performance**: Profiling, optimization, memory management excellence

#### Example Use Cases

```cpp
// Driver development with proper error handling
NTSTATUS DriverEntry(PDRIVER_OBJECT DriverObject, PUNICODE_STRING RegistryPath);

// Windows API integration with RAII
class WindowsAPIWrapper {
    // Production-ready Windows API wrapper
};

// Assembly integration
extern "C" void optimized_memory_copy(void* dest, const void* src, size_t size);
```

---

## 🏁 Special Mode Triggers & Commands

voidBeast includes three advanced modes, each with their own trigger phrases.  
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
4. Paste the prompt content from any of the files in this repo (e.g., `voidBeastMode.md`, `voidBeast_OpenAI.md`) into the Custom Mode instruction box.
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
