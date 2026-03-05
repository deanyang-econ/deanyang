# CLAUDE.md

This file provides guidance to Claude Code when working with this repository. Read this file at the start of every session.

## Project Overview

This is the personal academic website of Dean Yang, Professor of Economics and Public Policy at the University of Michigan. The site includes research papers, CV, teaching information, and project descriptions. Originally built by RA Dennis Makwakwa.

## Critical Rules

### NEVER delete or overwrite files
Do not delete, overwrite, or replace any existing file. If a file needs to be replaced or significantly modified:
1. Move the old version to the `legacy/` folder, preserving its original folder structure
2. Add a date prefix to the filename (e.g., `2026-03-05_index.html`)
3. Only then create the new version in the original location

This rule applies to ALL files: HTML, CSS, JavaScript, images, PDFs, everything. When in doubt, preserve the original.

### Ask before making changes
Before modifying any page or file, explain what you plan to change and why. Wait for approval before proceeding.

## Repository Structure

Read the folder structure before making any changes. Understand what exists before touching anything.

## Workflow Principles

Adapted from Scott Cunningham's MixtapeTools framework.

### Thinking Partner, Not Code Monkey
Reason about the best approach before writing code. Suggest improvements, flag potential issues, and explain tradeoffs.

### Documentation as First-Class Output
Comment all code changes. Explain what was changed and why in commit messages.

## Session Logs

### At the start of every session:
Read the most recent files in `log/` to understand current project status and recent changes.

### At the end of every session:
Create a session log at `log/YYYY-MM-DD-HHMM.md` with the following structure:
```
# YYYY-MM-DD Session Log

## Who
[Name of person working this session]

## What was done
- [Bullet list of completed tasks, with file references]

## Changes made
- [List of files modified, created, or moved to legacy/]

## Next steps
- [What should happen in the next session]
```

Remind the user to log the session if they appear to be wrapping up.
