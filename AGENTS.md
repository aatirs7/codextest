# Codex Agent Authentication

This document describes how the Codex agent can authenticate and push to this GitHub repository.

## GitHub User Credentials

- **Username:** aatirs7  
- **Personal Access Token:** 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

## Git Configuration for Codex Agent

Run the following commands to set up Git and enable push access:

```bash
git config --global user.name "aatirs7"
git config --global user.email "your-email@example.com"

git remote set-url origin https://aatirs7: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@github.com/aatirs7/<REPO>.git
