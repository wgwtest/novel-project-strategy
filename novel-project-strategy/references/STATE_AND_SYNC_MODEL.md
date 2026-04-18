# State And Sync Model

Use this reference when the task depends on how chapter state, confirmation state, and structural sync should be interpreted.

## 1. Goal

The purpose of this model is to stop longform projects from collapsing all progress into one vague notion of "done."

At minimum, separate:

1. text was edited
2. user confirmed the chapter or change
3. structure-level files were synced

## 2. Recommended state dimensions

When the project is large enough to need explicit tracking, keep at least these dimensions visible.

### 2.1 Chapter work state

Examples:

- `待起稿`
- `起稿中`
- `已修订`
- `待确认`
- `已确认`

Exact labels may vary. The distinction must stay readable.

### 2.2 Structural sync state

Examples:

- `未同步`
- `部分同步`
- `已同步`

This dimension answers whether the related outline, timeline, setting, or issue files have absorbed the chapter result.

### 2.3 Risk or revisit state

Examples:

- `正常`
- `需回看`
- `阻塞中`

Use this when a chapter is textually workable but still has unresolved continuity, realism, or rule conflicts.

## 3. Recommended meanings

### 3.1 Drafted

- prose or chapter text was created or revised
- user has not yet formally confirmed it
- structure-level truth should not be assumed to have changed

### 3.2 Confirmed

- the user explicitly confirmed the chapter, section, or relevant conclusion
- confirmation should be recorded on the project surface that the local rule treats as authoritative
- confirmation does not automatically mean structure-level files are already synced

### 3.3 Synced

- the related outline, timeline, setting, issue files, or other structure surfaces were updated as required
- if a project tracks sync separately, do not mark this state until the required structure files actually match the confirmed truth

### 3.4 Pending confirmation

- the current text or conclusion is ready for user review
- downstream structural promotion should stay constrained unless the local rule explicitly allows draft-driven sync

## 4. Fact-source precedence

When project files disagree, prefer this order unless the local project rule explicitly overrides it:

1. active chapter or task state file
2. active local rule or workspace guide
3. explicit user confirmation in the current accepted project surface
4. recent edit record
5. derived structure files or summary views

Do not let a stale outline or timeline silently override a more recent chapter-state record.

## 5. Confirmation interpretation rules

- Generic acknowledgements such as "继续", "可以", "好", or "收到" should not automatically count as formal chapter confirmation unless the project rule says they do.
- If the user confirms only prose quality, do not assume they also confirmed structure-level promotion.
- If the user confirms a local chapter fix, do not assume future-chapter implications are also confirmed.
- If the meaning of confirmation would materially change the sync decision, record the ambiguity instead of pretending it is resolved.

## 6. Structural sync rules

### 6.1 Sync when required

Sync outline, timeline, setting, or issue files in the same round when:

- the project rule says confirmed chapter facts must be promoted immediately
- the round was explicitly about structure-level correction
- the chapter change would make the current structure files actively misleading if left stale

### 6.2 Do not sync prematurely

Do not promote chapter-local conclusions into structure-level truth when:

- the chapter is still pending confirmation
- the local project rule keeps chapter edits and structure sync as separate gates
- the prose is exploratory and not yet canonical

## 7. Recommended record fields

For chapter or task state tables, prefer fields such as:

- object id
- chapter or task title
- work state
- sync state
- last action
- last updated
- pending confirmation
- needs revisit
- linked files

For edit records, prefer fields such as:

- request summary
- actual changes
- affected files
- resulting state
- sync decision
- next recommended entry point

## 8. Anti-patterns

Treat the following as state-management failures:

1. using one "done" label to mean edited, confirmed, and synced all at once
2. marking structure as updated when only chapter prose changed
3. treating casual acknowledgements as formal confirmation
4. promoting local exploratory prose into global setting truth without a rule or confirmation
5. letting summary pages drift while pretending they remain authoritative
