# CLAUDE.md

This file describes the folder structure and operating context for this workspace.

---

## Folder Structure

### 00 Human/
Personal knowledge management — human-facing content and daily operations.

| Folder | Purpose |
|--------|---------|
| `00 Inbox/` | Capture zone for unprocessed input (links, ideas, tasks) |
| `10 Daily Notes/` | Date-stamped daily logs and reflections |
| `20 Tasks/` | Action items, to-dos, and project tasks |
| `30 Projects/` | Active projects with goals, notes, and deliverables |
| `40 Resources/` | Reference material, docs, and learning resources |
| `50 People/` | Contact notes, relationship context, and CRM-style entries |
| `60 Areas/` | Ongoing responsibilities and life/work areas to maintain |
| `70 Context/` | Background context, mental models, and situational awareness |
| `80 Templates/` | Reusable templates for human-facing workflows |
| `90 Content/` | Drafts, published content, and media assets |

---

### Machine/
Automation and AI asset library — everything that runs or is executed by a system.

| Folder | Purpose |
|--------|---------|
| `Agents/` | AI agent definitions, configurations, and prompts |
| `AI Content Only/` | AI-generated content not intended for direct human editing |
| `Chat Imports/` | Imported conversations from AI chat interfaces |
| `Content Intelligence/` | Enrichment pipelines, classification logic, and tagging rules |
| `Outputs/` | Generated outputs from automated runs |
| `Research Results/` | Saved results from automated research and web searches |
| `Scripts/` | Automation scripts (shell, Python, JS, etc.) |
| `SOPs/` | Standard operating procedures for repeatable processes |
| `Templates/` | Reusable templates for machine-executed workflows |
| `Workflows/` | n8n and other workflow definitions |

---

### System/
AI system configurations and instruction sets for each AI agent/model in use.

| Folder | Purpose |
|--------|---------|
| `CLAUDE/` | System prompts, memory, and config for Claude |
| `CODEX/` | System prompts, memory, and config for Codex |
| `GEMINI/` | System prompts, memory, and config for Gemini |
| `GEMINI AG/` | System prompts, memory, and config for Gemini Advanced |

---

### z Archive/
Long-term storage for inactive, completed, or deprecated content. Prefix `z` keeps it sorted to the bottom.

---

## Conventions

- **Inbox first**: All new, unprocessed items go to `00 Human/00 Inbox/` before being sorted.
- **Numbered prefixes** in `00 Human/` control sort order and reflect processing priority.
- **Machine vs Human**: If content is produced by automation and not meant for human editing, it belongs in `Machine/`. If it is authored or curated by a person, it belongs in `00 Human/`.
- **System configs are AI-specific**: Each subdirectory in `System/` is scoped to a single AI model or product.
- **Archive last**: Move outdated or completed work to `z Archive/` rather than deleting it.
