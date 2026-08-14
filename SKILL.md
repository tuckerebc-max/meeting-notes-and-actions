---
name: meeting-notes-and-actions
description: Turn meeting transcripts, recordings, rough notes, agendas, emails, or chat logs into accurate, concise meeting notes with attendees, topics, decisions, open questions, risks, and actionable follow-ups. Use when summarizing a meeting, extracting action items, assigning owners or due dates, preparing minutes, or converting discussion into a trackable plan.
---

# Meeting notes and actions

Convert messy meeting material into a dependable record of what happened and what happens next. Separate evidence from interpretation, preserve uncertainty, and never invent a decision, attendee, owner, deadline, quote, or commitment.

## Workflow

1. Read all supplied material before summarizing. Identify the meeting title, date, time zone, participants, roles, agenda, source type, and any requested output format. Treat the transcript or notes as the source of truth; use an attached agenda for context, not proof that an item was discussed.
2. Normalize the discussion. Group remarks by topic, merge repeated points, remove filler and false starts, and retain disagreement when it affects a decision or next step. Distinguish what someone proposed, what the group agreed to, and what remains unresolved.
3. Extract decisions only when the source shows an explicit agreement, approval, rejection, selection, or recorded outcome. Label tentative direction as tentative and discussion as discussion.
4. Extract actions as deliverables, not vague intentions. For each action, capture the owner, exact next step, due date, dependencies, and status. If the source does not provide an owner or date, write “Unassigned” or “No date set”; do not infer from who spoke, who attended, or a typical workflow.
5. Capture open questions, risks, blockers, and dependencies separately from action items. Include the person or team responsible for resolving them only when the source supports it.
6. Draft the output using the structure below. Put high-value information first: decisions and actions before a long narrative summary.
7. Run the quality check, then return the notes. If the material is incomplete or contradictory, add a brief “Source limitations” note instead of silently repairing it.

## Default output

Use this structure unless the user requests another format:

### Meeting

- **Date:** Use the supplied date; otherwise “Not provided.”
- **Purpose:** One sentence grounded in the agenda or discussion.
- **Attendees:** List only identifiable participants. Mark uncertain names as “[unclear]”.

### Decisions

Record each decision in plain language. Include the decision owner or approver and timing only when stated. Mark proposals, preferences, and tentative direction explicitly.

### Action items

| Action | Owner | Due | Status / dependency |
|---|---|---|---|
| Verb-led deliverable | Named person/team or Unassigned | Stated date or No date set | Pending, in progress, blocked, or dependency |

Make each action independently trackable. “Discuss budget” is a topic; “Send revised FY27 budget with staffing assumptions” is an action.

### Discussion summary

Summarize the few points needed to understand the decisions, tradeoffs, and remaining work. Do not recreate the transcript or attribute every sentence.

### Open questions and risks

List unresolved questions, objections, assumptions, blockers, and external dependencies. Do not convert an unresolved concern into a decision.

### Next meeting

Include the date, purpose, and preparation requested only if stated. Otherwise write “Not set.”

## Accuracy rules

- Preserve names, titles, dates, numbers, and quoted language exactly when supplied; flag transcription uncertainty rather than guessing.
- Keep attribution when it changes meaning, especially for commitments, objections, approvals, and risks. Avoid attributing routine context unnecessarily.
- Do not turn “we should,” “maybe,” “I can,” or “let's consider” into a committed action unless the group clearly accepted it.
- Do not assign an action to the person who raised the issue unless the source assigns it.
- Do not manufacture a due date from phrases such as “soon,” “next week,” or “before the launch.” Preserve the original wording or label the date as relative.
- Record conflicts honestly. If one note says Tuesday and the transcript says Thursday, show the conflict and identify the source; do not choose silently.
- Use neutral language. Do not make a participant sound more certain, supportive, or responsible than the source indicates.
- Remove sensitive personal details that are irrelevant to the meeting record. Preserve necessary context when the user asks for a complete official record.

## Quality check

Before sending, verify:

1. Every decision is supported by explicit agreement or clearly labeled as tentative.
2. Every action has a verb-led deliverable and an evidence-backed owner and due date, or an explicit missing-value label.
3. Open questions, risks, and dependencies are not hidden inside the summary.
4. No attendee, quote, number, commitment, or outcome was invented.
5. The notes are concise enough to scan but preserve disagreements and caveats that affect execution.
6. The next step is clear for each unresolved item, or the record says that no next step was assigned.

Return the finished notes directly. Include a short “Needs confirmation” section only when unresolved source ambiguity could change ownership, timing, or the recorded decision.
