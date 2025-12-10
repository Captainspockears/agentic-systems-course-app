# Agentic Systems Mastery Roadmap

An interactive web app for tracking your progress through a comprehensive 7-level learning path from noob to world-class agent systems architect.

## 🎯 Overview

This roadmap guides you through mastering agentic systems, with 42 topics organized across 7 levels. Each topic includes:
- **What it is**: A clear explanation of the concept
- **Copy-paste prompt**: Ready-to-use prompts for fresh AI chats to learn the topic

## 🚀 Getting Started

1. Open `course.html` in your web browser
2. Start at Level 1 and work through topics sequentially
3. Check off topics as you complete them
4. Copy prompts to use in your AI chat sessions

## ✨ Features

### Progress Tracking
- ✅ Checkbox system for each topic
- 📊 Real-time progress bars for each level
- 📈 Overall journey percentage
- 💾 Automatic local storage (no account needed)

### Gamification
- 🎮 **XP System**: Earn 10 XP per completed topic (420 XP total)
- 🏆 **Rank System**: Progress through 7 ranks:
  - Observer (0 XP)
  - Apprentice Agent Engineer (60 XP)
  - Practitioner (120 XP)
  - Senior Agent Architect (180 XP)
  - Principal Agent Systems Engineer (240 XP)
  - World-Class Agentic Systems Architect (300 XP)
  - Master Architect (420 XP)

### Interactive Features
- 📜 **Show/Hide Prompts**: View learning prompts inline
- 📋 **Copy Prompt**: One-click copy to clipboard
- 🧹 **Reset Progress**: Start fresh anytime
- 📱 **Responsive Design**: Works on desktop and mobile

## 📚 Learning Path Structure

### Level 1 – Noob: Agentic & LLM Foundations (~1h)
Core mental models for agents, LLMs, and planning.

### Level 2 – Amateur: Single-Agent Architecture & Tools (~1h)
Single-agent loops, tools, and safety basics.

### Level 3 – Practitioner: Memory, RAG & Knowledge Agents (~1h)
Retrieval, memory, and knowledge-grounded agents.

### Level 4 – Systems Engineer: Production & Microservices (~1h)
Distributed systems, observability, evals, and security.

### Level 5 – Senior Agent Architect: Multi-Agent & Orchestration (~1h)
Planner–executor patterns, orchestration, and debugging.

### Level 6 – Research Engineer: Learning & Optimization (~1h)
Capability acquisition, RL intuition, and self-improvement.

### Level 7 – World-Class: Cutting Edge & Portfolio (~1h+)
Realtime, computer-use, Deep Research, and portfolio polish.

## 💾 Data Storage

Progress is stored locally in your browser using `localStorage`:
- **Storage Key**: `agentRoadmapProgress`
- **Format**: JSON array of completed topic IDs
- **Location**: Browser's local storage (per domain)
- **Privacy**: All data stays on your device

Your progress persists across browser sessions but is specific to:
- The browser you use
- The device you're on
- The domain/origin (file:// vs http://)

## 🛠️ Technical Details

- **Pure HTML/CSS/JavaScript**: No dependencies, no build step
- **Single File**: Everything in `course.html`
- **No Backend**: Fully client-side
- **Works Offline**: Once loaded, no internet needed

## 📝 Usage Tips

1. **Work Through Sequentially**: Each level builds on previous concepts
2. **Use Fresh Chats**: Copy prompts into new AI chat sessions for focused learning
3. **Take Notes**: Consider keeping your own notes alongside the roadmap
4. **Build Projects**: After each level, try building a small project to reinforce learning
5. **Track Your Journey**: Watch your rank and XP grow as you progress

## 🎓 Learning Approach

Each topic is designed to take 5–10 minutes:
1. Read the "What it is" summary
2. Copy the prompt
3. Paste into a fresh AI chat
4. Engage with the learning session
5. Check off the topic when complete

## 🔄 Resetting Progress

Click the "Reset progress" button in the header to clear all checkmarks and start over. This will:
- Clear all completed topics
- Reset XP to 0
- Reset rank to Observer
- Clear localStorage data

## 📄 License

This is a learning tool. Feel free to customize the roadmap content in `course.html` to match your needs.

---

**Happy Learning! 🚀**
