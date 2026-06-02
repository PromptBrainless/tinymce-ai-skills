# tinymce-ai-skills

A collection of AI skills for TinyMCE products — compatible with Claude Code, Codex, and Cursor.

## What is an AI skill?

An AI skill is a set of files that gives an AI assistant deep, specialised knowledge about a specific task. Add one to your AI tool of choice to unlock guided, context-aware assistance for that topic.

## Available skills

| Skill | Description |
|---|---|
| [tinymce-setup](skills/tinymce-setup/skill.md) | Guides you through installing and configuring TinyMCE in any framework |

## Usage

### Claude Code
1. Copy the skill folder into your project (e.g. `skills/tinymce-setup/`)
2. Add a reference to `skill.md` in your `CLAUDE.md` file
3. Claude Code will apply the skill automatically across your session

### Codex
1. Copy the skill folder into your project (e.g. `skills/tinymce-setup/`)
2. Register it as a Codex Skill so the agent can discover and apply it automatically

### Cursor
1. Copy the skill folder into your project (e.g. `skills/tinymce-setup/`)
2. Reference `skill.md` from your `.cursor/rules` file

## Contributing

Skills are maintained by the TinyMCE team. To request a new skill or report an issue, open a GitHub issue.
