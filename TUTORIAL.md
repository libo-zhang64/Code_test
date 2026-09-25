# Beginner's Tutorial: Using Claude Code in the Terminal (Code_test project)

This is a quick-start guide for using Claude Code with this project (`C:\Shell\Claude_Projects\Code_test`, GitHub: https://github.com/libo-zhang64/Code_test).

## 1. Starting Claude Code

Open a terminal (PowerShell or Git Bash), move into the project folder, and launch Claude Code:

```
cd C:\Shell\Claude_Projects\Code_test
claude
```

This starts an interactive session. Everything you type after this is a conversation with Claude, scoped to the current folder.

## 2. Talking to Claude

Just type in plain English what you want done, e.g.:

```
add a Python script that prints "hello world"
```

```
explain what this function does
```

Claude will read files, write/edit code, and run commands as needed, showing you each action it takes.

## 3. Slash commands

Special built-in commands start with `/`. Useful ones:

- `/init` — scans the codebase and generates a `CLAUDE.md` file with project-specific guidance for future Claude sessions.
- `/help` — lists help topics.
- `/clear` — clears the conversation history (starts fresh, keeps the same folder).

## 4. Running your own shell commands

If you want to run a command yourself (not have Claude run it), prefix it with `!`:

```
! git status
```

The output is shown directly in your terminal/session, and Claude can see the result too.

## 5. Typical workflow in this project

1. Ask Claude to make a change (add a file, fix a bug, write a test).
2. Claude edits files and shows you a diff-style summary of what changed.
3. Review the changes.
4. Ask Claude to commit, or do it yourself:
   ```
   ! git add -A
   ! git commit -m "Describe your change"
   ! git push
   ```
   (Claude will also do this for you if you ask, e.g. "commit and push this.")

## 6. Notes specific to this machine/project

- This project's GitHub remote is already set up (`origin` → https://github.com/libo-zhang64/Code_test), so `git push`/`git pull` work out of the box.
- The GitHub CLI (`gh`) is installed but newly-installed tools sometimes aren't picked up by an already-open terminal. If a command like `gh` isn't found, open a **new** terminal window (or restart your shell) so it picks up the updated PATH.
- `gh auth status` shows whether you're logged in to GitHub from the CLI.

## 7. Asking for help

If you're not sure what Claude Code can do, just ask it directly, e.g. "what can you do?" or "how do I undo my last commit?" — Claude can explain its own features and standard git/dev workflows.
