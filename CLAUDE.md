# Claude Code Instructions for FreddyFit Personal Training

## CRITICAL: Always Start from Latest Code

Before making ANY changes:

1. **Fetch the latest `main` branch:**
   ```
   git fetch origin main
   ```
2. **Ensure your working branch is based on the latest `main`:**
   ```
   git rebase origin/main
   ```
3. **If there are conflicts, resolve them before proceeding.**

This ensures all changes build on top of the latest deployed version of the site,
not an outdated snapshot.

## Project Overview

- This is a static website for FreddyFit Personal Training.
- The site is deployed from the `main` branch.
- Key files: `index.html`, `about.html`, and image assets in the root directory.

## Rules

- Never overwrite or remove existing content unless explicitly asked.
- All new features/changes should be additive to the current live site.
- Always verify the current state of files before editing them.
