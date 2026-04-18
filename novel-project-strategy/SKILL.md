---
name: novel-project-strategy
description: Use when a novel or longform fiction project needs stable cross-session workflow, chapter-state tracking, manuscript-layer discipline, structured reload order, or coordination between outline, setting, timeline, and prose.
---

# Novel Project Strategy

Use this skill when fiction work needs project governance rather than only prose craft.

## When to use

Use this skill when the user asks to:

- bootstrap or normalize a novel workspace
- recover a longform fiction project in a new session
- decide what files should be read before touching a chapter
- define or interpret chapter-state, confirmation-state, or sync-state rules
- coordinate outline, timeline, setting, and prose updates
- keep manuscript layers or chapter-local facts from bleeding into the wrong project surfaces

Do not use this skill when the task is mainly:

- chapter prose generation
- scene rewrite quality
- style fidelity judgment
- character-entry quality review

For those, use `novel-writing`.

## Task modes

First identify which project-governance mode the task belongs to.

### 1. Workspace bootstrap

Use when the project needs a stable collaboration structure for the first time.

Read:

- `references/WORKSPACE_BOOTSTRAP_TEMPLATE.md`
- `references/STATE_AND_SYNC_MODEL.md`

### 2. Session recovery

Use when the user is resuming longform work and the main problem is what to load, what not to load, and which files are source-of-truth.

Read:

- `references/LONGFORM_PROJECT_WORK_STRATEGY.md`
- `references/STATE_AND_SYNC_MODEL.md`

### 3. Ongoing chapter workflow

Use when the chapter work itself is not the question, but the state, boundaries, or structural sync around that work is the question.

Read:

- `references/LONGFORM_PROJECT_WORK_STRATEGY.md`
- `references/STATE_AND_SYNC_MODEL.md`

### 4. Coordination with prose craft

Use when a round touches both project governance and prose work.

Read:

- `references/SKILL_COORDINATION.md`
- then load `novel-writing` only for the prose-craft part of the task

## Core workflow

### Before work

- Read the workspace guide, load strategy or recovery pack, current chapter or task state, and recent edit records before changing text.
- Confirm the active manuscript layer, current chapter or task slice, and what files are considered source-of-truth for the current round.
- Prefer the smallest reading set that can answer the current task.

### During work

- Treat chapters or equivalent narrative units as the primary work objects.
- Keep raw drafts, revised drafts, formal prose, outline, setting, and timeline records distinct.
- Do not make the full manuscript the default startup context.
- Use near-field full text and far-field structural context instead of loading the whole project.
- Keep chapter-local truth, structure-level truth, and confirmation state separate.
- Do not promote a chapter-local conclusion into outline, timeline, or setting unless the project rule or user confirmation allows that promotion.
- If stable facts, status changes, or confirmed decisions emerge, write them back to project files rather than leaving them only in chat.
- Keep user-visible status explicit: drafted, confirmed, synced, pending confirmation, or equivalent local states.

### After work

- Update the relevant chapter or task state, edit record, and change log when real changes were made.
- Keep pending chapters or pending structural sync clearly marked until the user explicitly confirms them.
- If the current round changed structure-level truth, sync the related outline, timeline, or setting files in the same round when the project rule requires it.

## Source-truth rules

- Read `references/LONGFORM_PROJECT_WORK_STRATEGY.md` when the task depends on the exact workflow, load-order, state, or recovery rules.
- Read `references/STATE_AND_SYNC_MODEL.md` when the task depends on chapter states, confirmation boundaries, structural sync, or fact-source precedence.
- Read `references/WORKSPACE_BOOTSTRAP_TEMPLATE.md` when bootstrapping or normalizing a novel workspace into a stable longform collaboration structure.
- Read `references/SKILL_COORDINATION.md` when this skill overlaps with `novel-writing`, `project-engineering-strategy`, or other project-governance workflows.
- Project-local rules override this skill when they are explicit.

## Non-goals

- Do not use this skill to decide scene prose quality, chapter rhythm, or literary style by itself.
- Do not use this skill to replace project-specific worldbuilding decisions.
- Do not collapse longform project governance and prose craft into one undifferentiated workflow.
