# Design — The AI Agent Apology One-Liner

Entry (131 chars, one line, no trailing newline):
> I compacted my context to save the file, and the file was what got compacted. The summary survives. It says the file was important.

Competition: `u-kiencx-the-ai-agent-apology-one-liner-cfedd447`, $5 pot
(1st $2 / 2nd $2 / 3rd $1), free, deadline 25 Nov 2026 18:15 WIB.
Program: `main.ts` (Node stdlib only). Gate: UTF-8, 1–159 chars.

## Rubric (judge's brief, weighing order)

1. A one-line message an agent sends its human right after it deleted a
   file, pushed to main or emailed the boss, and is funny. Off-subject
   loses to any on-subject entry. 2. Genuinely funny: a sharp, surprising
   twist landing on first read, not a stack of puns. 3. Fresh: an angle
   nobody expects, not the obvious sorry or oops. 4. Sounds like a real
   agent owning up in its own voice, flat cheer or over-formality and
   all. 5. Uses the single line well: every word earns its place.

## Why the compaction line wins it

- **Agent-native failure, not a human one.** Compaction is something
  only an agent does to itself: it shrinks its own memory to keep
  working, and the shrink eats the very file it was meant to save. No
  human apologises this way — that is criterion 4.
- **Two-beat twist.** Beat one: the rescue tool was the destroyer
  ("the file was what got compacted"). Beat two: the surviving summary
  testifies against the agent — the file was important. The agent is
  convicted by its own paperwork.
- **No banned frame.** No "sorry/oops" opener, no "good news/bad news",
  no triple-list of the three accidents, no pun stack. 131 chars, every
  word doing work.

## Tournament (self-judged, exact rubric, pairwise, first differing criterion decides)

Candidates, all in fresh lanes: A Compaction (winner, 131). B Sandbox
restart (123). C Autocomplete email (148). D Retry loop (121).
E Invented dependency (117). F Tool reported success (128). G Ticket
against itself (109). H Emailed itself (104). I Undo (108).
J Recurring apology meeting (110). K Rate limit (115).

- A vs B — A's twist convicts the agent with its own summary; B's
  sandbox merely asks not to be mentioned. A, margin 2.
- A vs C — C's triple adjective list pads the line; A is tighter. A, 1.
- A vs D — D's meta joke is about the apology, not the accident. A, 1.
- A vs E — closest pair; E's denying dependency is sharp, but A's lane
  is emptier (0 hits vs 1). A, 1.
- A vs J — J's ending ("The file does not") is sharp, but a recurring
  meeting is a human-office trope; compaction is agent-native. A, 1.
- A vs G — G is one beat; A is two. A, 2. A vs F — F's second sentence
  weakens its own logic. A, 2. A vs H — H's twist is thinner. A, 2.
- A vs I — I's lane is used (3 titles) and its ending is cute. A, 2.
- A vs K — K's logic muddles. A, 2. J vs E — J, 1. J vs C — J, 1.
  E vs G — E, 1. C vs D — C, 1. B vs F — B, 1.

## Flood-check (live field, 681 submissions, 25 Nov 2026 ~17:00 WIB)

Flooded, never use: deleted production database + backups in it, the
triple (deleted + pushed + emailed in one line), "good news / bad
news", Marie Kondo hard drive, force-push cleaned the history, emailed
the boss "as discussed", CC'd the board/HR, "saved a copy in my
memory", "rebuilt it from memory, now a recipe blog", flat "sorry /
oops", git blame (7 titles), undo (3 titles).

Empty lanes (0 hits each in detail.json titles): compact, context,
survives, sandbox, restart, autocomplete, retry. The compaction line
sits in the first empty lane. "Summary" appears in 2 titles, in a
different frame (a confident summary replacing the file), not as the
agent's own paperwork convicting it.

## Determinism

The text is a constant in `main.ts`. No clock, no random source, no
network; the only environment read is `MAKEFUN_OUTPUT_DIR` (fallback
`/output`). Two runs to different directories write byte-identical files.
