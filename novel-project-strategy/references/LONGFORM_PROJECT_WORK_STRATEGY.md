# Longform Project Work Strategy

## 1. Goal

Use this reference as the workflow baseline for longform fiction projects that need:

1. reliable cross-session recovery
2. separation between prose work and project-state truth
3. chapter-state and structural-sync discipline
4. predictable load order instead of full-manuscript-first reading
5. clean boundaries between manuscript layers

The goal is not to keep one conversation alive forever. The goal is to make the project recoverable from files.

## 2. Core principles

### 2.1 Files remember, sessions execute

- Do not treat chat history as the long-term truth source.
- Stable facts, state changes, confirmations, and recovery entry points should live in project files.
- Old sessions may be used as evidence, not as the default working memory container.

### 2.2 Structure before full-text expansion

- Default startup context should come from workspace guides, state files, edit records, outline, timeline, and setting.
- Near-field prose may be read in full.
- Far-field context should stay structural by default.
- Do not load the whole manuscript unless the task truly requires it.

### 2.3 Chapters are the primary work objects

- Track work primarily by chapter, scene group, arc slice, or another explicit narrative unit.
- Do not infer project status only from raw prose.
- If state files exist, treat them as the workflow source-of-truth.

### 2.4 Manuscript layers must stay distinct

Keep these layers separate when they exist:

- raw draft
- revised draft
- formal manuscript
- outline
- timeline
- setting
- issue or note records

Do not silently overwrite one layer while pretending another was updated.

### 2.5 Confirmation and sync are not the same

- Distinguish drafted, confirmed, and synced states.
- A chapter may be textually edited without being structurally synced.
- A user saying "continue" or "good" should not automatically be treated as a formal confirmation unless the local project rule says so.

### 2.6 Chapter-local truth and structure-level truth are not the same

- A chapter may introduce or test information that should remain local until confirmed.
- Outline, timeline, and setting files should not absorb chapter-local experiments by default.
- If a project treats prose as primary truth, that rule should still be explicit rather than assumed.

## 3. Standard workflow

### 3.1 Before work

- Read the workspace guide.
- Read the load strategy or minimum recovery pack.
- Read the current chapter or task state file.
- Read the recent edit-record overview or recent relevant records.
- Read the smallest necessary structural files such as outline, timeline, or setting.
- Confirm the active manuscript layer and the current task boundary before editing.

### 3.2 During work

- Use the minimum reading set that can support the task.
- Pull near-field full prose when wording, tone, rhythm, or local continuity matters.
- Keep future-chapter prose excluded by default unless a real continuity dependency requires it.
- Write stable conclusions back to files when the project depends on them.
- If a chapter-local conclusion should remain chapter-local, do not prematurely promote it into setting or outline truth.
- If state files, edit records, and structural files disagree, resolve the source-of-truth question before broad edits.

### 3.3 After work

- Update the chapter or task state when real status changed.
- Update edit records when real work was performed.
- Update the change log when structure-level or workflow-level truth changed.
- Keep unconfirmed work explicitly marked as pending confirmation or the local equivalent.
- If the round intentionally left structure unsynced, record that fact explicitly instead of leaving silence.

### 3.4 When confirmation feedback arrives

- Read the active chapter state and relevant edit record first.
- Sync confirmation state only where the local project rule allows it.
- If confirmation changes structure-level truth, update the related outline, timeline, or setting files in the same round when required.
- If the meaning of the confirmation is ambiguous, record the ambiguity instead of treating it as broad approval.

## 4. Recommended recovery artifacts

Longform projects should usually maintain some combination of:

1. workspace guide
2. load strategy or recovery pack
3. chapter or task state table
4. edit-record overview
5. change log
6. outline
7. timeline
8. setting files
9. issue or note files

The exact filenames are project-specific. The categories should stay clear.

Recommended minimum for a usable project:

1. workspace guide
2. recovery pack or load strategy
3. chapter or task state file
4. edit-record overview
5. at least one structure file such as outline or timeline

## 5. Default load order

Default recovery order:

1. workspace guide
2. load strategy or recovery pack
3. chapter or task state
4. edit-record overview
5. outline
6. timeline
7. relevant setting
8. latest relevant change log

Do not default to:

- full formal manuscript reads
- all raw-draft batches
- all future chapters
- all historical discussion notes

## 6. Task-specific loading

### 6.1 Revising a chapter

Default reads:

- chapter or task state
- target chapter full text
- adjacent chapter full text when needed
- linked raw-draft or note source when needed
- relevant issue cards or annotations

### 6.2 Updating outline or setting

Default reads:

- outline
- timeline
- relevant setting files
- edit-record overview
- latest relevant change log

Only read prose fragments needed for impact verification.

### 6.3 Checking consistency

Default reads:

- chapter or task state
- edit-record overview
- latest relevant change-log section
- outline
- timeline
- relevant setting

Do not treat the whole manuscript as the default consistency entry point.

### 6.4 Recovering from an accident or lost context

Default reads:

- recovery pack
- state file
- edit-record overview
- linked issue or recovery notes
- smallest relevant structural files

Do not start by blindly scanning every manuscript file.

## 7. Session switch rules

Prefer continuing an old session only when:

- the interruption was short
- the task slice is still narrow
- the environment has not materially changed
- the old session has not mixed too many unrelated lines

Prefer a new session when:

- the old session is long
- multiple chapter, setting, and workflow lines are mixed together
- the project already has a recovery pack or stable state files
- the user is worried about context drift or cross-thread contamination

After switching, the old session should serve mainly as historical evidence.

## 8. Environment check

Before broad reading or editing in a recovered session, confirm:

1. current working directory
2. whether the project-local rule set is loaded
3. whether the current round can write files
4. whether the current round can use network resources when that matters
5. which manuscript layer is active
6. what the minimum validation or review action will be for this round

## 9. Anti-patterns

Treat the following as workflow failures:

1. leaving the whole project truth only in chat
2. repeatedly loading the whole manuscript for narrow tasks
3. collapsing raw, revised, and formal layers into one vague notion of text
4. treating local edits as automatically synced structural truth
5. reopening old threads by habit when a clean recovery path already exists
6. confusing environment problems with context problems
7. pretending a structural-sync decision was made when it was merely omitted
