# Graphs coverage and review

Reviewed 2026-11-02 against all five supplied parts of *Graphs*, printed pages 1–46.
This is a source-alignment review, not verification against an instructor's syllabus
or a guarantee of examination coverage.

## Included

All 39 nodes, 156 question keys/explanations, and 47 glossary entries were reviewed.
The 66 prerequisite edges match the node dependencies, form an acyclic graph, and
permit every node to become ready. The map covers the chapter's three main areas:
graph structure/families/isomorphism, paths/connectivity/traversals, and vertex coloring.

Labs provide degrees, components, bipartiteness, unweighted BFS distance, Euler trails
with distinct edge identities, Hamilton-cycle search, exact small-graph vertex coloring,
and counts of proper assignments from labeled palettes. The isomorphism challenge uses
a separate fixed five-vertex path pair. The tripartite lesson starts with K1,2,3.
Existing source corrections are retained and documented in [references](references.md).

## Remaining depth and lab limits

- Questions mainly assess definitions, theorem selection, and short computations.
  They do not reproduce all 64 source exercises or grade complete written proofs.
  Girth, the ferryman state-space puzzle, cube/tesseract constructions, and several
  degree-sequence construction exercises have no dedicated mastery node.
- BFS and algorithm implementations are learning extensions. The UI limits editing
  to 2–9 vertices and undirected graphs; it is not a general graph-analysis service.
  Distances between disconnected vertices are treated as infinite. Hamilton cycles
  use at least three vertices; the automatic search returns a cycle, not a solver
  for Hamilton paths without a cycle.
- Planarity is explained through examples and counterexamples. There is no general
  planarity test, crossing-free layout solver, or proof checker.
- TSP introduces weighted optimization, but its lab explores unweighted Hamilton
  tours. It does not optimize the source's six-city weighted instance.
- Chromatic-polynomial controls count proper assignments for a selected integer
  palette, rather than deriving symbolic polynomial coefficients. Unused colors
  are allowed. Counts remain exact within the displayed small-graph limits.
- Each mastery check reuses a four-question pool with shuffled presentation. A 4/4
  score is a practice signal, not evidence of durable retention or proof proficiency.
  Mixed Practice does not update individual-node mastery.

## Validation

Validated in headless Chrome on November 2, 2026:

- Compared 1,104 graph cases with independently generated Python reference results:
  every labeled simple graph on 2–5 vertices, plus selected loop, parallel-edge,
  disconnected, and isolated-vertex cases. Degrees, components, bipartiteness,
  shortest paths, Euler/Hamilton existence and route validity, minimum vertex
  coloring, and counts from palettes of 0–3 colors agree.
- Checked cycle-coloring counts through 9 vertices and 6 colors, plus the
  10,077,696 assignments for an edgeless 9-vertex graph with 6 labeled colors.
  The independent algorithm suite passed 45,372 assertions.
- All 39 lessons and their four-question checks render. Incomplete submissions
  reveal no feedback; 0/4, 3/4, and 4/4 score correctly. Repeated submissions do
  not add attempts, current/best scores update, answer shuffles preserve keys,
  and reset/reload/malformed-storage recovery work. Mixed sets use the actual
  available count and leave mastery unchanged.
- Checked edge edits, preset isolation, parallel-edge highlighting, small-graph
  Hamilton restrictions, theorem guards, BFS endpoints after vertex removal,
  coloring and polynomial controls, isomorphism challenge, search, and reset.
  Keyboard focus survives graph, matrix, and slider redraws.
- All nine topic navigations and local documentation links resolve. Guide layouts
  use 3/2/1 card columns at 1440/900/390px. All Graphs lessons were checked at 390px
  without page-level horizontal overflow; wide maps/tables scroll within panels.
  Desktop and mobile screenshots were visually inspected. No browser exceptions
  were observed.

These are targeted content and browser checks, not a complete accessibility or
cross-browser audit.
