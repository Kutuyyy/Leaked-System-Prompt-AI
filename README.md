# 🔍 AI Systems Transparency & Observability

> **Making AI systems more transparent, understandable, and observable.**

[![AI Transparency](https://img.shields.io/badge/Focus-AI%20Transparency-blue)](#)
[![Research](https://img.shields.io/badge/Type-Research-green)](#)
[![Documentation](https://img.shields.io/badge/Type-Documentation-orange)](#)
[![Open Source](https://img.shields.io/badge/Community-Open%20Research-purple)](#)

---

## 📖 About

This project is dedicated to **AI systems transparency, research, and observability**.

It collects and documents system prompts, behavioral instructions, tool definitions, guidelines, and other system-level information from major AI models and agent platforms.

The goal is simple:

> **Understand how AI systems are instructed, configured, and guided — not just what they output.**

---

> ⚠️ **DO THIS AT YOUR OWN RISK.**
>
> Make sure you understand what you're doing before using any information or tools from this repository with your AI account.

---

## 🌐 Systems & Platforms

This project covers research and documentation related to major AI systems and agent platforms, including:

| Platform | Category |
|:---|:---|
| 🤖 **OpenAI** | AI Models & Assistants |
| 🔵 **Google** | AI Models & Agents |
| 🟣 **Anthropic** | AI Models |
| ⚫ **xAI** | AI Models |
| 🟠 **Perplexity** | AI Search & Agents |
| 🟢 **Cursor** | AI Coding Agent |
| 🌊 **Windsurf** | AI Coding Agent |
| 🧠 **Devin** | AI Software Engineer |
| 🟡 **Manus** | AI Agent |
| 🟦 **Replit** | AI Development Platform |
| ➕ **Others** | AI Models & Agents |

> The list is continuously evolving as new systems and research become available.

---

# 🎯 Why This Exists

> **"In order to trust the output, one must understand the input."**

Modern AI systems are often controlled by multiple layers of instructions and configuration.

These layers can influence:

- 🗣️ What an AI can or cannot say
- 🎭 What persona or behavior it follows
- 🚫 How refusals and restrictions are handled
- 🔄 How the system redirects certain requests
- 🛠️ Which tools and capabilities are available
- 📋 Which behavioral guidelines are applied
- 🧠 How the system is expected to respond
- ⚖️ What safety, ethical, or policy frameworks affect its behavior

Understanding these instructions provides valuable context when studying AI behavior.

---

# 🔬 The AI Instruction Stack

A simplified representation of how an AI system may process a request:

```text
┌─────────────────────────────┐
│         USER INPUT          │
└──────────────┬──────────────┘
               │
               ▼
┌─────────────────────────────┐
│    SYSTEM INSTRUCTIONS      │
└──────────────┬──────────────┘
               │
               ▼
┌─────────────────────────────┐
│ DEVELOPER / APPLICATION     │
│        INSTRUCTIONS         │
└──────────────┬──────────────┘
               │
               ▼
┌─────────────────────────────┐
│    POLICIES & GUARDRAILS    │
└──────────────┬──────────────┘
               │
               ▼
┌─────────────────────────────┐
│     TOOL DEFINITIONS &      │
│        CAPABILITIES         │
└──────────────┬──────────────┘
               │
               ▼
┌─────────────────────────────┐
│          AI MODEL           │
└──────────────┬──────────────┘
               │
               ▼
┌─────────────────────────────┐
│      GENERATED OUTPUT       │
└─────────────────────────────┘
```

The visible conversation is only one part of the overall system.

---

# 🧩 What We Document

Where available, entries may contain:

| 🔎 Information | 📝 Description |
|:---|:---|
| 🤖 **Model** | AI model or system name |
| 🏷️ **Version** | Specific model/system version |
| 📅 **Date** | Date the information was obtained |
| 🧾 **System Prompt** | Available system-level instructions |
| 📋 **Guidelines** | Behavioral and operational instructions |
| 🛠️ **Tools** | Available tools and capabilities |
| 🔧 **Configuration** | Relevant system configuration |
| 📝 **Context** | Additional observations |
| 🔗 **Sources** | Supporting references |

---

# 📂 Repository Structure

```text
.
├── providers/
│   ├── openai/
│   ├── google/
│   ├── anthropic/
│   ├── xai/
│   ├── perplexity/
│   └── others/
│
├── agents/
│   ├── cursor/
│   ├── windsurf/
│   ├── devin/
│   ├── manus/
│   └── replit/
│
├── prompts/
├── tools/
├── research/
├── documentation/
└── README.md
```

The structure may evolve as the project grows.

---

# 🧪 Research & Methodology

Information in this repository may come from:

- 🔍 Publicly accessible interfaces
- 🧪 Security and behavioral research
- 📚 Existing documentation
- 🔬 Reverse engineering research
- 📝 Community contributions
- 🗂️ Historical documentation
- 🔗 Publicly available sources

Whenever possible, entries should include the **date, version, context, and source** associated with the information.

---

# 📊 Research Principles

This project follows several principles:

### 1. Transparency

Document what can be observed and verified.

### 2. Context

Preserve information about where and when an observation was made.

### 3. Reproducibility

Provide enough information for others to understand how a finding was obtained.

### 4. Accuracy

Clearly distinguish confirmed information from assumptions, reconstructions, or speculation.

### 5. Preservation

Keep historical records useful even when systems and models change over time.

---

# ⚠️ Disclaimer

This repository is intended for:

- 📚 Research
- 🎓 Education
- 🔬 Analysis
- 📝 Documentation
- 🌐 Transparency

Information may become outdated or change without notice.

Some entries may represent a specific version, environment, or point-in-time observation rather than the current production configuration of a system.

> **Always verify important information against the original source when possible.**

This project does not claim that every documented instruction represents the current or official configuration of a platform.

---

# 🛠️ Contributing

Found something interesting?

Have a new extraction, system prompt, tool definition, or research finding?

**Contributions are welcome.**

## 📋 Please Include

```text
✅ Model / System Name
🏷️ Version (if known)
🗓️ Date of Extraction
🔗 Source / Reference
🧾 Extracted Information
📝 Context / Notes
```

## 💡 Example Contribution

```text
Model:
Example AI v2.1

Date:
2026-10-02

Source:
[Source / Reference]

Context:
Obtained during analysis of the system's publicly accessible interface.

Notes:
Additional observations or relevant context.
```

---

# 🤝 Contribution Guidelines

Before submitting a contribution:

1. Verify the information as much as possible.
2. Clearly distinguish confirmed information from speculation.
3. Include the model/system version when available.
4. Include the date of collection.
5. Preserve the original context.
6. Avoid exposing personal or sensitive information.
7. Do not present reconstructed or modified prompts as official originals.
8. Include relevant sources whenever possible.

> **Quality, accuracy, and context are more valuable than simply adding more entries.**

---

# 📜 Attribution

This project was originally created by **Claritas**.
This repository is an **updated and modified version of the original project**, built upon its original foundation with additional improvements, fixes, documentation, research, and features.
The original project and its contributors deserve full credit for establishing the foundation on which this version is built.



## 🔄 Project Relationship

```text
Original Project
      │
      ▼
Updated & Modified Version
      │
      ├── ✨ Improvements
      ├── 🐛 Fixes
      ├── 📚 Documentation
      ├── 🔬 Research
      ├── 🧩 Additional Features
      └── 🛠️ Tooling
```

> This repository does not claim original authorship of the underlying project concept or materials inherited from the original project.

---

# ❤️ Credits

Special thanks to:

- **Claritas** — Original project and foundation
- **Contributors** — Research, documentation, and improvements
- **Researchers** — AI transparency and system analysis
- **Open-source community** — Tools, knowledge, and collaboration

---

# ⭐ Support the Project

If you find this project useful, consider:

- ⭐ **Starring the repository**
- 🐛 **Reporting issues**
- 🔍 **Sharing research**
- 📝 **Improving documentation**
- 🤝 **Contributing new findings**

Every contribution helps improve our collective understanding of modern AI systems.

---

# 🔐 Responsible Research

This project promotes responsible research and documentation.

Contributors are encouraged to:

- Respect privacy
- Avoid publishing personal information
- Avoid exposing credentials or authentication secrets
- Clearly label reconstructed or inferred information
- Preserve relevant context
- Respect applicable laws and platform terms
- Report security-sensitive findings responsibly

---

<div align="center">

# 🔍 Understand the System. Understand the Output.

**AI Transparency • Research • Documentation • Observability**

<br>

Made for researchers, developers, and curious minds.

</div>
