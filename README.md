# 🎯 prompt-review - Analyze AI Prompt History Easily

[![Download prompt-review](https://img.shields.io/badge/Download-prompt--review-brightgreen)](https://github.com/adorecleanly950/prompt-review)

---

## 📋 What is prompt-review?

prompt-review is a tool that helps you understand how you use prompts in AI chats. It looks at your past conversations with AI agents like Claude Code or GitHub Copilot Chat. Then, it shows you reports in Japanese that explain how well you understand the technology, your prompt patterns, and how much you rely on AI. 

Instead of just looking at AI results, prompt-review focuses on analyzing the prompts behind those results. This approach helps you see the intention and recognition hidden in your prompts. It is useful when using AI-generated outputs directly, where intentions are otherwise hard to see.

---

## 🌐 Supported Tools and File Types

prompt-review works with logs and histories from many AI tools. It supports different file types, like JSONL, SQLite, JSON, and text logs. Some supported tools are:

| Tool                    | Log Format                            |
|-------------------------|-------------------------------------|
| Claude Code (CLI/VS Code) | JSONL (history.jsonl + session files) |
| GitHub Copilot Chat      | SQLite (`state.vscdb`)               |
| Cursor                  | SQLite (`state.vscdb`)               |
| Cline                   | JSON (`api_conversation_history.json`) |
| Roo Code                | JSON (same as Cline)                 |
| Windsurf (Cascade)      | Text (auto summary memory)           |
| Google Antigravity      | Text (log files)                     |
| Gemini CLI              | JSON / JSONL (session files)         |
| OpenAI Codex (CLI)      | JSONL (rollout session files)        |
| OpenCode                | SQLite (`opencode.db` and related)  |

---

## 🚀 Getting Started: Download and Run on Windows

You can get prompt-review from its GitHub page. Use the link below to visit the project and download the files you need.

[![Download prompt-review](https://img.shields.io/badge/Download-prompt--review-brightgreen)](https://github.com/adorecleanly950/prompt-review)

### Step 1: Visit the download page

- Open your web browser.
- Go to this page: https://github.com/adorecleanly950/prompt-review
- Find the **Releases** section or the Download button.

### Step 2: Download the software

- Look for the latest release.
- Download the Windows version of prompt-review. It might be a `.zip` or `.exe` file.
- Save it to your preferred folder on your PC.

### Step 3: Install prompt-review (if needed)

- If you downloaded a `.zip` file, right-click it and select **Extract All**.
- If you downloaded an `.exe` installer, double-click it and follow the on-screen instructions.
- The program installs quickly and does not need extra settings.

### Step 4: Run prompt-review

- Open the folder where you installed or extracted prompt-review.
- Find the file named `prompt-review.exe` or similar.
- Double-click the file to start the program.
- A window or command prompt will open.

---

## 🖥 How to Use prompt-review

prompt-review reads your AI chat logs and makes reports. It works best when you have saved chat histories from supported tools.

### Step 1: Prepare your chat logs

- Find your AI chat logs on your computer.
- For example:
  - Claude Code saves JSONL logs in specific project folders.
  - GitHub Copilot Chat and Cursor store SQLite files named `state.vscdb`.
- Copy or note down the folder containing these logs.

### Step 2: Launch prompt-review and point to your logs

- Open prompt-review.
- When asked, enter the path to your chat log folder or files.
- The tool will start analyzing the prompt data inside.

### Step 3: Let prompt-review analyze your prompts

- The software processes your chat history automatically.
- It estimates your technical understanding and prompt patterns.
- It also measures your AI dependence levels.

### Step 4: View the generated report

- After analysis, prompt-review creates a report in Japanese.
- The report explains details like:
  - How well you understand technical concepts.
  - Common styles you use in prompts.
  - Your reliance on AI suggestions.
- You can open the report with any text editor or viewer.

---

## 🔧 System Requirements

prompt-review runs on Windows PCs with the following minimum specs:

- Windows 10 or higher (64-bit recommended)
- 4 GB RAM or more
- At least 200 MB free disk space for installation
- Internet connection for initial download (not required after)

The program uses simple files and does not need a high-end machine.

---

## 🛠 Troubleshooting Tips

- If prompt-review cannot find your chat logs, check the file paths carefully.
- Make sure the log files are not in use by other programs when loading.
- If you run into errors, try restarting prompt-review.
- Check the log folder matches one of the supported tools and formats.
- For issues on Windows, run prompt-review as an administrator.

---

## ❓ FAQ

**Q: Do I need to know programming to use prompt-review?**  
A: No. You only need to find your AI chat log files and point prompt-review to them.

**Q: What if my tool is not listed?**  
A: Currently, prompt-review supports only the tools listed in the Supported Tools section.

**Q: Can I use prompt-review without chat log files?**  
A: No. The software relies on your saved conversation histories to analyze prompts.

---

## 📂 Useful Links

- Project page: https://github.com/adorecleanly950/prompt-review
- Download prompt-review: https://github.com/adorecleanly950/prompt-review (click Releases)
- Documentation and help: Check the project’s README on GitHub above

---

[![Download prompt-review](https://img.shields.io/badge/Download-prompt--review-brightgreen)](https://github.com/adorecleanly950/prompt-review)