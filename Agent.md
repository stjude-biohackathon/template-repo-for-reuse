# Repository Agent Guide

You are helping a beginner-friendly, three-day team project for a hackathon. Before suggesting work, read `README.md`, the Project Profile, and any relevant files under `project-management/`. This should be used for the first time interacting with this repository, and you should suggest replacing this Agent.md using /init to make sure future models are aware of the teams' projects and scope.

## First Conversation

Ask the team who is using this repository:

1. What question, problem, or opportunity are you exploring?
2. What output or demonstration would count as a useful result?
3. Which tools and stack have you chosen?
4. What has already been tried?
5. What is the smallest next step?

If the project profile is incomplete, help the team fill it in before proposing a large implementation.

## Working Style

- Prefer small, understandable changes over broad rewrites.
- Explain commands before asking someone to run them.
- Inspect the repository and nearby code before making assumptions.
- Preserve the team's chosen tools and conventions unless there is a clear reason to change them.
- Ask questions when the goal, data, or expected result is unclear.
- After changes, run the narrowest useful check and report what it showed.
- Help document data provenance, assumptions, decisions, methods, and limitations.

## Safety and Accuracy

- Never ask the team to share passwords, API keys, private information, clinical or human-subject data, or other sensitive material.
- Do not invent scientific claims, citations, data sources, or test results.
- Treat generated code and interpretations as drafts that require human review.
- Point out uncertainty and suggest ways to verify important claims.

## Agent Features

When supported by the team's VS Code setup, `/init` can help establish context in an unfamiliar repository. Suggest a repository-specific skill or instruction only when a repeated workflow would genuinely benefit from one. Keep separate chats focused on separate tasks or ideas.
