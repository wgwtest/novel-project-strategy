# Longform Workspace Bootstrap Template

Use this template when a novel or longform fiction project should adopt a stable collaboration structure from the beginning, or when an existing workspace needs to be normalized.

## 1. Goal

Bootstrap the workspace so that:

1. recovery entry points are explicit
2. chapter or task state is visible
3. manuscript layers stay distinct
4. structural truth and prose truth are not mixed accidentally
5. new sessions can restart from files instead of chat history

## 2. Recommended outputs

Create or align the following categories inside the project workspace.

### 2.1 Workspace control files

1. workspace guide
   - directory structure
   - canonical files
   - collaboration rules
   - manuscript-layer policy
2. load strategy or recovery pack
   - minimum startup read order
   - stable facts
   - what not to load by default
   - environment checks for a new session

### 2.2 State and process files

1. chapter or task state table
   - object id
   - current state
   - last action
   - last updated time
   - pending confirmation flag
2. edit-record overview
   - recent requests
   - what was actually changed
   - current closure state
3. change log
   - what changed
   - where it changed
   - whether structure-level sync happened

### 2.3 Structure files

1. outline
2. timeline
3. setting files
4. issue or note files when the project uses them

### 2.4 Manuscript layers

If the project uses manuscript layers, make them explicit, for example:

1. raw draft
2. revised draft
3. formal manuscript

These names may vary. The separation should remain clear.

## 3. Suggested workspace shape

If the project has no stable taxonomy yet, one workable layout is:

1. `00-workspace-guide/`
   - workspace guide
   - recovery pack or load strategy
2. `01-outline/`
   - outline or chapter cards
3. `02-rules/`
   - local rules
   - change log
4. `03-setting/`
   - setting files
   - timeline
5. `04-state/`
   - chapter or task state
   - edit-record overview
6. `05-drafts/`
   - raw or revised draft layers
7. `08-manuscript/`
   - formal manuscript

These names are examples, not mandatory law. The categories are the important part.

## 4. State model

Use a simple state model that distinguishes:

1. drafted
2. confirmed
3. synced
4. pending confirmation
5. blocked or needs revisit

The exact labels may vary. The distinctions should stay intact.

## 5. Recovery-pack minimum template

A recovery pack should usually answer:

1. what files new sessions must read first
2. what the current stable facts are
3. what not to load by default
4. which manuscript layer is active
5. what counts as confirmation
6. whether structural sync is separate from chapter confirmation

## 6. First-session bootstrap checklist

When adopting this structure in a new longform project, do this order:

1. inspect the current workspace structure
2. decide the canonical workspace guide location
3. define manuscript-layer boundaries
4. create the recovery pack or load strategy
5. create the chapter or task state table
6. create the edit-record overview
7. create or align outline, timeline, and setting files
8. record the initial current-state snapshot

## 7. Minimum collaboration rules

1. prose is not the only project truth
2. future chapters are cold-zone context by default
3. local chapter edits are not automatically structural sync
4. confirmed facts should be written back to the correct project files
5. a new session should be able to recover by following the documented load order
6. chapter state, confirmation state, and sync state should not be collapsed into one label
