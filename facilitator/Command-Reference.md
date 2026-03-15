# Command Reference

These are the core user commands the framework is designed to support in Codex.

## Core Commands

`Let's work`

- Codex checks the current state and decides the next best learning action.

`Assess me`

- Codex performs or completes the baseline assessment workflow using the intake files.

`Review this`

- Codex evaluates the current draft, explains the main issues, and gives a revision target.

`Give me a task`

- Codex creates a new assignment based on the roadmap and recent performance.

`Update my roadmap`

- Codex revises `progress/Roadmap.md` based on recent evidence.

`What should I focus on?`

- Codex summarizes the learner's current weaknesses, priorities, and next milestone.

`Show my progress`

- Codex summarizes progress from `progress/` and points to the strongest evidence.

`Make it harder`

- Codex increases task difficulty if the recent evidence supports it.

`Make it easier`

- Codex reduces task complexity while keeping the target skill intact.

`Give me a weekly review`

- Codex creates a short checkpoint review and updates the tracking files.

## Assistant Behavior

For vague commands, infer the correct workflow from repository state instead of asking the user to manage the system manually.
