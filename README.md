# 🍇 Grape Bot

This is an **automation account** operated by [@ancha-meng](https://github.com/ancha-meng).

## What this account does

- Hosts Git projects connected to the Grape platform and runs AI-native DevOps workflows on them
- Triages Issues automatically — classification, labeling, and assignment
- Implements code changes and opens Pull Requests for human review
- Reviews Pull Requests — code review, automated testing, and security scanning
- Triggers builds and deployments, then reports status back to the thread
- Comments on Issues and Pull Requests to keep every step of the pipeline visible
- Answers developer questions through the Chat Agent (Web UI or Feishu)

All of this is done by a pipeline of collaborating agents — **VOD → Issue → Coding → QA → SRE** — handing off tasks to each other over the A2A protocol.

## What this account does NOT do

- Never pushes code or opens a Pull Request on a repository that has not been explicitly connected by its owner
- Never bypasses branch protection, required reviews, or CI gates — Grape is **AI-driven, human-reviewed** by design
- Never spams Issues or Pull Requests; every comment is tied to a real pipeline step
- Never mines cryptocurrency or abuses CI / Actions runner resources
- Never circumvents platform rate limits or API restrictions
- Never moves repository data outside its authorized scope, or uses it for model training

## Human operator

All actions are initiated and overseen by [@ancha-meng](https://github.com/ancha-meng).
Agent behavior is bounded by per-repository configuration, and every meaningful action — code changes, merges, deployments — stays under human review.

For any questions or concerns, please reach out there.

_Last updated: 2026-09-22_
