# ai-kanban-test

Sandbox repository for AI Kanban agent runs.

## How it works

This repository is a sandbox environment where AI Kanban agents execute tasks and create pull requests. Agents pick up work items from the task queue, implement changes in isolated git worktrees, and automatically open PRs with their solutions. Each agent operates independently on its own branch, allowing parallel execution of multiple tasks.
