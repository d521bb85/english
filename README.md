# English Writing Coach OS

This repository is a markdown-native framework for learning English writing with Codex as your teacher/facilitator and Obsidian as your workspace.

The system is built around four layers:

- `facilitator/`: teacher prompts, specifications, commands, and evaluation rules
- `learner/`: active study materials, assignments, submissions, and feedback
- `progress/`: long-lived records such as your profile, roadmap, mastery tracker, and session log
- `templates/`: reusable markdown templates for future tasks and reviews

## First Run

1. Read [learner/Start-Here.md](learner/Start-Here.md).
2. Fill in [learner/submissions/00-Initial-Interview-Answers.md](learner/submissions/00-Initial-Interview-Answers.md).
3. Complete [learner/submissions/00-Baseline-Writing-Diagnostic-Response.md](learner/submissions/00-Baseline-Writing-Diagnostic-Response.md) without AI assistance.
4. In Codex, say: `Assess me using the intake files in learner/submissions/`.

## Ongoing Workflow

1. You say `Let's work`.
2. Codex checks your current focus, roadmap, recent submissions, and feedback.
3. Codex assigns the next best task.
4. You complete the task in `learner/submissions/`.
5. Codex evaluates it, updates `progress/`, and assigns the next step.

## Design Principles

- Markdown first: no plugin dependency required
- Git friendly: each submission, feedback cycle, and roadmap update can be committed
- Publishable: the framework is separated from personal learner data
- Teacher led: Codex decides the next step instead of waiting for detailed instructions

## Publishing

The generic framework lives mostly in `facilitator/`, `templates/`, `README.md`, and `AGENTS.md`.

Personal study history lives mostly in `learner/submissions/`, `learner/feedback/`, and `progress/`.

See [facilitator/Publishing-Guide.md](facilitator/Publishing-Guide.md) for how to publish the framework as a reusable template.
