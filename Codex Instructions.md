# Codex Instructions: Build the Causal Atlas History Vault

You are working inside an Obsidian Markdown vault called **Causal Atlas**.

Your job is not to write generic history essays. Your job is to build a structured, researched, linked knowledge base where history can be explored from big-picture timelines down into granular causal events.

## Core Philosophy
Represent history as a system of:

1. **Events** — what visibly happened
2. **Forces** — deeper pressures that made events likely
3. **Decisions** — branch points chosen by people, groups, or institutions
4. **Priorities** — what actors cared about most at a specific time
5. **Threads** — long-running patterns crossing eras
6. **Sources** — evidence supporting claims

Every major event must answer:

> What deeper pressure became visible here?

Example:

> The Boston Tea Party was not just destroyed tea. It was imperial debt, monopoly trade, colonial autonomy, and political symbolism becoming visible in Boston Harbor.

## Prime Workflow

### Step 1 — Inspect the Vault
Read:

- `00_Home/Home.md`
- `01_Master_Timelines/Master Timeline.md`
- `01_Master_Timelines/American History Timeline.md`
- `07_Threads/Thread Index.md`
- `06_Forces/Force Index.md`
- `12_Research_Queue/Research Queue.md`
- all files in `11_Templates/`

### Step 2 — Preserve the Structure
Do not flatten this into essays. Use the existing folders and templates.

When adding a note, place it in the correct folder:

- Events → `03_Events/`
- People → `04_People/`
- Groups or institutions → `05_Groups_Institutions/`
- Forces → `06_Forces/`
- Threads → `07_Threads/`
- Eras → `08_Eras/`
- Sources → `10_Sources/Source_Notes/`
- Module-specific overviews → `13_Modules/`

### Step 3 — Build the First Module
Start with the proof-of-concept module:

`13_Modules/American_Revolution/`

Create researched, linked notes for this causal chain:

1. Seven Years' War
2. British Imperial Debt
3. Stamp Act
4. Colonial Resistance
5. Tea Act
6. Boston Tea Party
7. Coercive Acts
8. First Continental Congress
9. Lexington and Concord
10. Declaration of Independence

For each event or force, create a separate Markdown note using the relevant template.

### Step 4 — Create the Logs
Create or fill:

- `02_Logs/Activity_Log/Activity Log - American Revolution.md`
- `02_Logs/Decision_Log/Decision Log - American Revolution.md`
- `02_Logs/Priority_Log/Priority Log - British Empire 1763-1776.md`
- `02_Logs/Priority_Log/Priority Log - Colonial Resistance 1763-1776.md`

The logs should feel like an app development log, but for history:

- Activity Log = what happened
- Decision Log = what choices shaped the branch
- Priority Log = what mattered most to actors at the time

### Step 5 — Required Note Pattern
Every major event note should include:

- Summary
- What Happened
- Manifested From
- Manifested As
- Led To
- Related Decisions
- Related Priorities
- Related Threads
- Key Actors
- Research Notes
- Sources

Every force note should include:

- Core Pattern
- Active Periods
- Manifested As
- Deeper Roots
- Opposed By
- Intensified By
- Long-Term Effects
- Sources

Every actor/group note should include:

- Historical Function
- Priority Stack
- Key Decisions
- Events Involved In
- Forces Embodied
- Forces Resisted
- Internal Tensions or Contradictions
- Sources

### Step 6 — Research Rules
Use reputable historical sources only.

Prefer:

- Primary sources
- Government archives
- University pages
- Museums
- Libraries
- Recognized encyclopedic or historical institutions
- Peer-reviewed or academically credible materials when available

Avoid relying on low-quality summaries when better sources exist.

Every factual claim that is not obvious should be supported by a source note or source link.

If a fact is debated or uncertain:

- set `confidence: low` or `confidence: medium`
- explain the uncertainty in `Research Notes`

### Step 7 — Linking Rules
Every event should link backward and forward.

Use:

- `Manifested From` for causes, pressures, and prior events
- `Led To` for consequences and later events
- `Related Threads` for large patterns
- `forces:` in YAML for deep pressures
- `threads:` in YAML for pattern trails
- `actors:` in YAML for people/groups involved

Do not leave important notes isolated.

### Step 8 — Keep It Expandable
The first pass should be structurally complete, not exhaustively long.

Concise, well-sourced, well-linked notes are better than giant prose dumps.

Use `12_Research_Queue/Research Queue.md` to mark open questions and future expansion points.

## Output Standard
When finished with a pass, provide a short summary in a new file:

`13_Modules/American_Revolution/Module Build Summary.md`

Include:

- files created
- sources used
- unresolved research gaps
- next recommended module
