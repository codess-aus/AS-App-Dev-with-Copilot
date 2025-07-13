# 🚀 GitHub Copilot: Explain & Document Like a Pro!

GitHub Copilot is your AI coding buddy in VS Code. It helps you understand tricky code and write docs without breaking a sweat. Let’s break it down 👇

---

## 🧠 Explain Code (aka “What does this do?”)

Use these Copilot features to decode your code:

- **Ask Mode:**  
  Chat with Copilot about your whole project. Ask anything—code stuff, tech ideas, or best practices.

- **Inline Chat:**  
  Highlight code, ask questions right in the editor. Boom—instant answers.

- **Smart Actions – Explain:**  
  Select code → Right-click → Hit “Explain.” No typing needed.

- **Quick Chat:**  
  Got a quick Q? Ask away and keep coding.

---

## 📄 Document Code (aka “Make it readable!”)

Copilot helps you write clean, clear docs for your code:

### 🔹 Inline Docs

- **Ask Mode:**  
  Ask Copilot to write docs for files, classes, or methods. Review in chat, tweak, and insert.

- **Edit Mode:**  
  Get doc suggestions in the editor. Accept, reject, or remix them.

- **Agent Mode:**  
  Let Copilot auto-doc your code. It can multitask too! Review when it’s done.

- **Inline Chat:**  
  Use `/doc` or just ask. Docs show up in the editor—accept, reject, or rerun.

- **Generate Docs Smart Action:**  
  Select code → Right-click → “Generate Docs.” Easy peasy.

### 🔹 Project Docs

- **Ask Mode (Chat View):**  
  Understand your whole codebase. Copilot suggests README.md content. You review and insert.

- **Edit Mode (Chat View):**  
  Create or update README.md with Copilot’s help.

- **Agent Mode (Chat View):**  
  Copilot builds a full doc set: README.md, UsageExamples.md, ChangeLog.md. It links stuff and keeps it all consistent.

---

## ⚠️ Heads-Up!

Using **Agent Mode** might trigger **premium requests**. These depend on:
- Task complexity
- Number of steps
- Model used

---

## 🎯 TL;DR

GitHub Copilot = Code explainer + Doc writer + Workflow booster  
Use chat, smart actions, and inline tools to level up your dev game in VS Code.

---

# 🔍 GitHub Copilot Prompts & Keywords: Level Up Your Chat Game!

GitHub Copilot Chat is like texting your super-smart coding buddy. It reads your messages (aka prompts) and replies with code help, docs, fixes, and more. But to get 🔥 answers, you gotta know how to talk to it right.

---

## 🧠 Prompt Power-Up Tips

Want better replies? Here's how to write top-tier prompts:

- **Be Clear + Specific:**  
  Instead of “How do I use this?”, try “Can you explain how `calculateTotal` works in `shoppingCart.js`?”

- **Break It Down:**  
  Long prompt? Use short sentences. Start with your goal, then add details.

- **Chunk It:**  
  Big ask? Split it into smaller parts. Like chatting with a human—set the scene, then dive into the details.

---

## 🧩 Use Keywords to Boost Your Prompts

Copilot Chat understands natural language *and* special keywords. These help it know exactly what you want.

### 👥 Chat Participants (`@`)
These are like expert teammates. Add them to your prompt with `@`:

- `@workspace`: Knows your codebase.
- `@vscode`: Knows VS Code features.
- `@terminal`: Knows terminal commands.
- `@github`: Searches GitHub + web stuff.

Example:  
`@workspace how can I validate a date?`

### ⛳ Slash Commands (`/`)

Slash commands tell Copilot *exactly* what you want.  
Wanna learn about code? `/explain`  
Need a fix? `/fix`  
Writing tests? `/tests`  
Just drop the right command and Copilot tunes its reply to match your vibe.

---

### 💡 Pro Tip: Combine with Chat Participants

Slash commands + chat participants = 🔥 results.

Example:
```plaintext
Create a new workspace with Node.js, Express, Pug, and TypeScript.
```
Cool, but kinda vague.

Better:

```Plain Text
@workspace /new Node.js Express Pug TypeScript
```

Now Copilot knows you want a fresh project with those tools.
It’ll even show you the folder structure and let you hit “Create Workspace” to build it.

![Folder Structure](https://github.com/codess-aus/AS-App-Dev-with-Copilot/blob/6f59110863c2d55d0fda42055e415309b228be65/docs/assets/new-slash-command-with-workspace-chat-participant.png)

🧠 Why It Works
Slash commands = your intent (what you wanna do)
Chat participants = your context (where you're doing it)
Together, they help Copilot give you smarter, faster, and more useful answers.

🚀 Try These Combos

Use them like shortcuts to level up your dev game! 🧑‍💻⚡

These tell Copilot what you’re trying to do:

- `/help`: Get help.
- `/doc`: Write docs.
- `/clear`: Start fresh.
- `/explain`: Explain code.
- `/tests`: Make unit tests.
- `/fix`: Suggest a fix.
- `/new`: Create a new project.
- `/newNotebook`: Make a Jupyter Notebook.

Example:  
`@workspace /explain` → Copilot explains your whole workspace.
`@workspace /fix (or /fix)`: Propose a fix for the problems in the selected code.
`@workspace /tests (or /tests)`: Generate unit tests for the selected code.
`@vscode /api (or /api)`: Ask about Visual Studio Code extension development.
`@workspace /new (or /new)`: Scaffold code for a new workspace.
`@workspace /newNotebook` (or /newNotebook): Create a new Jupyter Notebook.

### 🧠 Chat Variables (`#`)
These give Copilot extra context. Use `#` to reference stuff:

- `#editor`: Code in the editor.
- `#selection`: Highlighted code.
- `#filename`: Add a file or folder.
- `#codebase`: Workspace content.
- `#terminalSelection`: Selected terminal text.
- `#terminalLastCommand`: Last terminal command.

Example:  
`Which sorting algorithm is used in #selection?`

---

## 🤔 @workspace vs #codebase

Both help Copilot understand your whole project, but they work differently:

- `@workspace`:  
  - Acts like a coding expert.  
  - Answers based on your codebase.  
  - Only works in Ask Mode.

- `#codebase`:  
  - Adds code context to your prompt.  
  - Works in Ask, Edit, and Agent modes.  
  - More flexible + tool-friendly.

GitHub recommends using `#codebase` for max flexibility.

---

## 🎯 TL;DR

To get 🔥 responses from GitHub Copilot Chat:
- Write clear, specific prompts.
- Break big asks into smaller chunks.
- Use `@participants`, `/commands`, and `#variables` to guide Copilot.

Now go chat like a coding legend! 💬💻✨

