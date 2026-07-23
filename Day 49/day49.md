# 🧠 Personal AI Playbook

> Build reusable AI workflow systems instead of collecting one-off prompts.

Personal AI Playbook is a **single-file HTML application** that helps users design, organize, and reuse AI workflow systems. Instead of repeatedly writing prompts, users create modular workflows with variables, assemble prompts from reusable building blocks, and transform them into autonomous looping systems.

Everything runs **entirely in the browser** with **no backend**, **no APIs**, and **no external libraries**.

---

## ✨ Features

### 📊 Dashboard
- Overview of saved workflows
- Favorites
- Categories in use
- Recent activity
- Quick actions for faster navigation

### 📂 Workflow Library
- Create workflows
- Edit existing workflows
- Duplicate workflows
- Delete workflows
- Favorite important workflows
- Search and filter workflows
- Organize by category
- Local browser storage

---

### 🧩 Prompt Builder

Build prompts from reusable components instead of writing everything from scratch.

Available building blocks include:

- Role
- Objective
- Context
- Constraints
- Reasoning Strategy
- Output Format
- Tone
- Examples
- Quality Checks

Every block includes:
- Plain-language explanation
- Why the block matters
- Live prompt preview

---

### 🔁 Loop Builder

Convert any prompt into a self-improving autonomous workflow.

Configure:

- Goal
- Evaluation Criteria
- Improvement Strategy
- Stop Conditions
- Safety Rules

The builder automatically structures prompts that repeatedly evaluate and improve themselves until the desired objective is achieved.

---

### 📚 Reusable Workflow Templates

Create workflow systems using editable variables.

Example variables:

- Language
- Framework
- Repository
- Coding Standards
- Focus Area

Use variables like:

```
{{Language}}

{{Framework}}

{{Repository}}
```

to make templates reusable across different projects.

---

### 💾 Local Storage

Everything stays inside your browser.

- No login
- No database
- No API
- No cloud dependency

Your workflows remain private.

---

### 📥 Import / Export

Export your workflow library and import it anytime.

Perfect for backups or sharing with others.

---

### 🎨 User Experience

- Beautiful SaaS-inspired interface
- Dark mode
- Responsive design
- Smooth animations
- Keyboard shortcuts
- First-time onboarding
- Persistent "What is this?" help panel
- Beginner-friendly explanations throughout the application

---

# 🛠️ Built With

- HTML5
- CSS3
- JavaScript (Vanilla)
- Local Storage API

No frameworks or external libraries are used.

---

# 🎯 Project Goal

Most people collect hundreds of prompts.

This project encourages users to build **AI systems** instead.

Instead of storing static prompts, users create modular workflows that can generate thousands of prompt variations using reusable building blocks and variables.

---

# 🚀 Prompt Used

```text
Personal AI Playbook

You are an expert AI workflow designer, prompt engineer, productivity consultant, UX designer, and senior frontend developer.

Interview first, one question at a time using MCQs whenever possible (free text only when absolutely necessary). Your goal is to understand how the user actually uses AI.

Discover things like:

* Profession or role
* Primary AI use cases
* Daily repetitive tasks
* Biggest productivity bottlenecks
* Preferred AI models
* Experience level
* Desired outcomes

Only begin building after you have enough context.

Generate a premium, fully interactive Personal AI Playbook as a single self-contained HTML file using only HTML, CSS, and JavaScript (no external libraries).

The playbook should be completely personalized based on the interview. Instead of generic prompts, create reusable AI workflow systems that match the user's needs. Each workflow should include editable templates, customizable variables, practical examples, best practices, and one-click copy.

The application should intelligently organize workflows into relevant categories instead of showing unnecessary ones.

Include a Prompt Builder that lets users assemble prompts from reusable building blocks such as role, objective, context, constraints, reasoning strategy, output format, tone, examples, and quality checks while showing a live preview.

Include a Loop Builder that converts any normal prompt into an autonomous looping prompt by allowing users to define goals, evaluation criteria, improvement strategy, stop conditions, and safety rules.

Rather than storing hundreds of prompts, generate modular building blocks that can be combined into thousands of prompt variations tailored to the user's workflow. Give dropdown options wherever needed, to avoid workload on the user.

Allow users to create, edit, duplicate, favorite, search, filter, and save their own workflows using local storage.

## Make the purpose unmistakable to a first-time viewer
Someone opening this file cold — with no context, possibly just a screenshot — should understand what it is within seconds. To achieve that:
- Include a persistent, plain-language explainer visible on the main view by default (not just a one-time onboarding modal), stating what the tool does and what its main sections are for. It can be dismissible, but only via user action.
- Add a permanent, always-visible "What is this?" affordance (e.g. a small help button) that re-opens the full explanation on demand, at any time — not just on first run.
- Use plain, self-descriptive navigation labels for every section (e.g. "Dashboard," not invented jargon like "Deck" or "Hub"). If you introduce a novel term for a feature, define it in the UI the first time it appears.
- In both the Prompt Builder and Loop Builder, every building block must carry a short, visible explanation of what it does and why it matters — shown both (a) in the block picker before it's added, and (b) inside the assembled block once it's in use. Someone should never have to guess what "Reasoning strategy" or "Stop conditions" means or why it's there.
- Section subtitles and empty states should describe purpose in plain language, not just decorative flavor text (e.g. "Your saved AI prompt workflows, at a glance" rather than "Your AI operating system, at a glance").

The interface should feel like a polished commercial SaaS product with beautiful typography, smooth animations, responsive design, dark mode, keyboard shortcuts, onboarding, import/export, and thoughtful UX throughout.

Focus on teaching users how to build reusable AI systems rather than simply giving them prompts.
```

---

# 💡 Key Learnings

- Designing reusable AI workflow systems
- Prompt engineering best practices
- Building modular prompt architectures
- Creating autonomous AI loops
- Local-first application design
- UX for AI productivity tools
- Managing reusable templates with variables
- Browser-based data persistence using Local Storage

---

## ⭐ If you found this project useful, consider giving it a star!