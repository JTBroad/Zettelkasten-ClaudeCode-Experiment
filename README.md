# 🗂️ Zettelkasten-ClaudeCode-Experiment

> An intelligent note-taking system where AI agents create and organize atomic knowledge cards using the Zettelkasten method.

## 📖 Overview

This project implements an agentic memory system built around the [Zettelkasten methodology](https://zettelkasten.de/overview/) - a powerful knowledge management technique that breaks complex ideas into interconnected atomic notes.

## ✨ Features

- **AI-Powered Note Generation** - Claude agents automatically create atomic notes from conversations
- **Smart Linking** - Automatic backlinking and tagging for knowledge graph construction
- **Flexible Workflow** - Brainstorm in a single file, then atomize into organized notes
- **Obsidian Compatible** - View and edit your knowledge graph visually

## 🏗️ Architecture

| Component | Purpose |
|-----------|---------|
| `Claude.md` | Configuration file that instructs Claude how to operate within this project |
| `_index.md` | Main interaction thread for brainstorming and conversation with the agent |
| `/Generated/` | Repository for all atomized notes created over time |
| **AI Agent** | Reads/writes to `_index.md` and manages files in `/Generated/` |
| **Obsidian** *(Optional)* | Visual graph editor for exploring note connections |

## 🚀 Getting Started

### Prerequisites

- An AI agent with file system access (read/write capabilities)
- [Obsidian](https://obsidian.md/) *(optional but recommended for visualization)*

### Usage Workflow

1. **Initialize Conversation**
   - Open `_index.md`
   - Add your initial prompt in the User section

2. **Collaborative Brainstorming**
   - Ask your agent to evaluate `_index.md`
   - The agent adds notes to its designated section
   - Continue the back-and-forth dialogue either:
     - Within the agent interface directly
     - By editing `_index.md` and notifying the agent of changes

3. **Knowledge Atomization**
   - When ready, request the agent to process and organize the conversation
   - The agent will:
     - Break down `_index.md` content into single-topic atomic notes
     - Create appropriately named files in `/Generated/`
     - Add relevant tags and backlinks for proper graph connectivity

## 📚 Learn More

For a comprehensive understanding of the Zettelkasten method, visit: [zettelkasten.de/overview](https://zettelkasten.de/overview/)

## 🤝 Contributing

This is an experimental project exploring AI-augmented knowledge management. Contributions and ideas are welcome!

## 📝 License

*License information to be added*
