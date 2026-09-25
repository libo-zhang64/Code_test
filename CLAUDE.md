# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project status

This is a sandbox repository for learning to use Claude Code. It has no source code yet, so there are no build, lint, or test commands. Right now it contains only `README.md` and two beginner guides: `TUTORIAL.md` (Claude Code in this project) and `COWORK_TUTORIAL.md` (Claude Cowork). Once real code is added, update this file with the toolchain commands and architecture notes.

## Environment

- Windows machine. Both PowerShell and Git Bash are available.
- Git remote `origin` → https://github.com/libo-zhang64/Code_test (branch `master`). `git push`/`git pull` work without extra setup.
- The GitHub CLI (`gh`) is installed. If it isn't found, the shell's PATH is probably stale; a new terminal fixes it. Check login with `gh auth status`.
- `.vscode/settings.json` (untracked) sets `claudeCode.useTerminal: true`.
