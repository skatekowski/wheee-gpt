# wheee-gpt

**A ChatGPT assistant for product design and UI design** — for projects using the WHEEE Protocol. You set it up once and use it only via chat: send messages, upload files, request prototypes or documents. **No coding, no technical tools.**

**Repo:** [github.com/skatekowski/wheee-gpt](https://github.com/skatekowski/wheee-gpt)

---

## For designers — in short

- **What is this?** Instructions to create your **own assistant** (“WHEEE Product Design Companion”) in ChatGPT. The assistant speaks your language (UX/UI terminology), supports you through discovery, design system, prototyping, and handoff.
- **What do you need?** A ChatGPT account (e.g. Plus) to create a Custom GPT. Access to your project files or short text outputs from the project (e.g. project status, plan) — whatever your team uses.
- **What you don’t need:** No programming, no API, no dev environment. Everything runs in chat.

---

## How to set up the companion (step by step)

1. **Open ChatGPT** and go to **Explore**, then choose **Create a GPT**.  
   *(This is the feature for creating your own assistant with fixed rules and style.)*

2. **Enter the name:** e.g. **WHEEE Product Design Companion**.  
   The exact name and a short description are in [Protocol-GPT-Product-Design.md](Protocol-GPT-Product-Design.md) under “1. Name & short description” — you can copy them.

3. **Paste the instructions:** In the same file [Protocol-GPT-Product-Design.md](Protocol-GPT-Product-Design.md), select and copy the **entire “2. Instructions” section** (including the lines between the \`\`\`). Paste this text into the **Instructions** field in the Create a GPT dialog.  
   *(Instructions = the rules and “role” your assistant follows in chat.)*

4. **Conversation starters (optional):** In section “3. Conversation starters” of the same file you’ll find suggested opening questions. You can add some of them in ChatGPT under “Conversation starters” — then the assistant has suitable entry points from the start.

5. **Done.** No “Actions”, no API, no code. The assistant works only via chat.

---

## How to use the companion

- **Type in chat:** Describe what you need (e.g. “Create a prototype for the landing page” or “Summarize the design decisions from the journal”).
- **Upload files:** You can upload project files (e.g. process journal, project status) into the chat — the companion evaluates them and responds.
- **Paste text:** If someone on your team gives you a text output from the project (e.g. “project status” or “dependencies for component X”), paste it into the chat and ask the companion to explain it or suggest next steps.
- **Request files:** You can ask the companion to provide something for **download** or **copy-paste**: e.g. a clickable prototype (HTML), a design spec, a style guide, or a context file for a new chat. It will tell you how to save or paste the file.

**You don’t install apps or write code** — everything via messages, upload, and download/copy-paste.

---

## What you’ll find in this repo

| File | What for? |
|------|-----------|
| [Protocol-GPT-Product-Design.md](Protocol-GPT-Product-Design.md) | **Instructions for the WHEEE Product Design Companion.** Contains name, short description, full instructions to copy, and suggested conversation starters. Everything you need to create the assistant in ChatGPT. |
| [chat-context-template.md](chat-context-template.md) | **Template for a new chat.** When you start a new chat, fill in this template (or have the companion fill it) and upload or paste the content in the new chat — then the assistant has the right context (project, phase, last decisions, open points). |

---

## What the companion can do (no tech skills required)

- **Prototype:** On request a **file for download** (a clickable web preview) or text for copy-paste. Good for single screens, navigation, layout, typography, and colors. Export for **Figma** (no Pencil).
- **Documentation & planning:** On request **files for download** or text for copy-paste: e.g. process journal entry, project status, plan sketch, **style guide**, **UI spec** (color system, typo, spacing), component documentation, accessibility checklist. The companion always suggests a filename and folder (e.g. `architecture/`, `docs/`).
- **Context for the next chat:** A **short context file** (download or copy-paste) with project name, phase, last decisions, and open points. When starting a new chat, upload the file or paste the text — the new chat has the right context immediately.

---

## What is WHEEE? (Background)

**WHEEE** is a **workflow and planning protocol** for software projects. It defines how planning, design, and implementation are done — with clear phases, folders, and processes. **Mode D (Design)** is the mode for product and UI design: discovery, prototyping, design system, validation, and handoff to implementation.

If your project uses WHEEE, there are e.g. planning folders (`.planning/`, `project/`, `architecture/`) and consistent workflows. The **Product Design Companion** knows this structure and speaks the same language (user flows, design tokens, style guide, usability validation, handoff).  
Technical details: [WHEEE Protocol](https://github.com/wheee-protocol).

---

## Credits

- **[Get Shit Done (GSD)](https://github.com/glittercowboy/get-shit-done)** — Light-weight meta-prompting, context engineering, and spec-driven development (Claude Code, OpenCode, Gemini CLI). WHEEE builds on GSD methodology.
- **[Boris Cherny – How I use Claude Code](https://threadreaderapp.com/thread/2007179832300581177.html)** — Thread with setup and tips from the creator of Claude Code (plan mode, slash commands, verification).
- **[Boris Cherny on X](https://x.com/bcherny/status/2017742741636321619)** — More tips from the Claude Code team (parallel sessions, plan-first, verification).

---

## License

**MIT License** — this repo is open source. See [LICENSE](LICENSE).
