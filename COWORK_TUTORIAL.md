# Beginner's Tutorial: Using Claude Cowork

This is a quick-start guide to **Claude Cowork**. Claude Code (see `TUTORIAL.md`) is for coding in a terminal. Cowork is for everything else: you hand Claude a whole task, it works through many steps using your files and connected apps, and it hands back a finished file.

> Cowork changes often. If a button or command below doesn't match what you see, check the official guide: https://support.claude.com/en/articles/13345190-get-started-with-claude-cowork

## 1. What Cowork is (and when to use it)

- **Chat**: good for quick questions and a few back-and-forth messages.
- **Cowork**: good when you need a **deliverable**, meaning a document, slide deck, spreadsheet or CSV that someone will open.

A task is a good fit for Cowork when it has most of these:
1. Several inputs (files, folders, or data from connected apps)
2. A file as the result
3. Work you'll repeat regularly
4. A clear idea of what "good" looks like, so you can check the result
5. Tedious steps in the middle you'd rather hand off

Cowork runs in the cloud, so a task keeps going if you close the app. You can start it on one device and check on it from another.

## 2. Requirements

- A **paid** Claude plan: Pro, Max, Team, or Enterprise.
- Where it works: the Claude desktop app (Windows/macOS), claude.ai on the web, and the iOS/Android apps. On Enterprise plans, the web and mobile versions work only if your admin turns them on.
- To work with **files on your own computer** or use the built-in browser, you need the **Claude desktop app**, open and signed in.

## 3. First-time setup (3 steps)

1. **Open Claude.** Launch the desktop app (or go to claude.ai) and sign in. Pick the **Cowork** tab or option in the message box. If you don't see separate Chat/Cowork options, just start a new conversation; your version of Claude can turn any conversation into a Cowork task.
2. **Run guided setup.** In a new conversation, type:
   ```
   /setup-claude
   ```
   Claude will ask about your role, install a matching **plugin**, and help you connect the apps you use (e.g. Slack, Google Workspace, Microsoft 365).
3. **Choose where the work lives.** Click **Work in a folder** in the chat bar and pick a folder on your computer, or a **Project**. Claude reads from this location and saves its finished work there as real files.

## 4. Key concepts

| Term | What it means |
|------|---------------|
| **Working folder / Project** | Where Claude looks for files and saves its results. A Project keeps its files and memory from one session to the next. |
| **Connectors** | Links to outside apps (Slack, Gmail, Notion, Google Drive, etc.) that Claude can read live data from. Add them under **Customize** in the sidebar. |
| **Plugins** | Role-based bundles of skills, connectors, and ready-made prompts. |
| **Skills** | Extra abilities that plugins install. Type `/` to see the prompts they offer. |

## 5. Running your first task

1. Describe the result you want, with plenty of context, for example:
   ```
   Turn the meeting notes in this folder into a one-page project brief (Word doc).
   Audience: my manager. Keep it under 400 words.
   ```
2. Tip: ask Claude to check its understanding first. Add a line like:
   ```
   Before we begin, repeat my ask back to me, then ask me any clarifying questions you have.
   ```
3. Claude shows its plan. Read it, then let it proceed.
4. Open the finished file in your working folder and check it. If something is off, just tell Claude what to change.

Good first tasks:
- Turn research notes into a one-page brief
- Sort a messy folder of files by type or date
- Build an Excel sheet with working formulas from PDFs or CSVs
- Summarize recent Slack or email activity into a prioritized list

**The most important tip:** Claude does great work when you give it enough context, so share the files, the audience, and examples of what "good" looks like. Your exact wording matters less.

## 6. Permission modes (how much Claude can do on its own)

| Mode | Using connected apps | Creating/editing/deleting |
|------|------------|-------------------------|
| **Manual** | Asks you first | Asks you first |
| **Auto** | Allowed automatically | Claude decides, with an automatic safety check |
| **Skip** | Allowed automatically | Allowed automatically, with **no** safety checks |

Beginners should start with **Manual**. Auto mode uses more of your plan's usage allowance because of the extra safety check. Claude always asks before permanently deleting files.

> Remember: Cowork can read the folders you give it and **take real actions** for you. Only give it access to the folders and apps it needs for the task.

## 7. Scheduled (recurring) tasks

To have a task run automatically (for example, a 6am briefing every morning), type this in Cowork:
```
/schedule
```
Scheduled tasks run in the cloud, so your computer doesn't need to be on.

## 8. Saving usage

Multi-step tasks use more of your plan's usage allowance than simple chat questions. To use less:
- Put related work into one task instead of many small ones.
- Start a new conversation when you switch to an unrelated project.
- If you only need a quick answer, ask for that instead of a full document.

## 9. Current limitations

- You can't share a whole Cowork session, but you can share the individual files it creates.
- Some features (local files, browser control) work only in the desktop app.

## Sources

- [Get started with Claude Cowork (Help Center)](https://support.claude.com/en/articles/13345190-get-started-with-claude-cowork)
- [Get started in Claude Cowork in three steps (Claude Academy)](https://academy.claude.com/tutorials/get-started-in-claude-cowork-in-three-steps)
- [Best practices for getting started with Claude Cowork (Claude blog)](https://claude.com/blog/best-practices-for-getting-started-with-claude-cowork)
