---
name: Story
about: New story following the standard As-a/Context/Acceptance-criteria format
title: ''
labels: story
assignees: ''
---

## As a [user]
I want [capability] so that [outcome]

## Context
[Why this matters, what exists today, relevant dependencies or constraints an
agent needs that isn't already in the code — prior decisions, user research,
what the current behavior is.]

## What "solved" looks like
[Qualitative description of the end state — the feeling of done, not a checklist.]

## Acceptance criteria
- [ ] [Testable assertion, verifiable from the outside — UI behavior, API response, or DB state]
- [ ] ...

## Sequencing
[One line: why this ships before/after its neighbors, or "No ordering dependency."
Always present — never omit.]

## Out of scope
[Explicit list of what this story does NOT do. At least one line. Prevents scope
creep during the build.]

## Performance impact
[None | brief description of how this affects load time, API calls, or UX responsiveness.]

## Implementation Plan

### Files to change
| File | What changes |
|---|---|
| [path] | [one-line description] |

Always required, even for a one-file story. Group by repo when a story spans more than one.

### Data / process flow
[ASCII diagram — include for medium (2–4 files) or complex (5+ files / data model)
stories when the change moves data between steps or alters control flow (a hook
firing, a sync path, a request lifecycle, a state transition). Skip when the
change is local to one function or a simple, single-file story.]

### Key logic
[Old vs. new logic in a few lines, before → after, so the diff is predictable
before it's written. Include for medium/complex stories with changed behavior.
Skip for a simple, single-file change.]

### UI sketch
[ASCII layout of what the user sees. Include whenever the story changes the UI —
required for complex stories, only if UI changes for medium stories. Skip if
there's no UI surface.]

### Edge cases
[Empty states, failure modes, what could break. Include for medium/complex stories.]

### Testing
[Which test file(s) ship with the story, what each verifies, and the exact run
command (e.g. `npm run test:unit`, `bash ~/claude-memory/tests/foo.sh`). Every AC
must be covered by at least one automated check. Always required, even for a
one-file story.]
