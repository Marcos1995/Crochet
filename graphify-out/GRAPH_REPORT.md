# Graph Report - Crochet  (2026-10-18)

## Corpus Check
- 15 files · ~7,173 words
- Verdict: corpus is large enough that graph structure adds value.
- Unclassified: 2 file(s) not represented in the graph (top: .mdc 2)

## Summary
- 60 nodes · 45 edges · 15 communities (10 shown, 5 thin omitted)
- Extraction: 100% EXTRACTED · 0% INFERRED · 0% AMBIGUOUS
- Token cost: 0 input · 0 output

## Graph Freshness
- Built from commit: `b2b33a5f`
- Run `git rev-parse HEAD` and compare to check if the graph is stale.
- Run `graphify update .` after code changes (no API cost).

## Community Hubs (Navigation)
- Debug
- Web design
- Contexto del proyecto
- Dashboard brief (for the Stitch prompt)
- Verify (UI)
- Agent rules
- Build judgments with Laya
- Laya
- Review
- Project
- tablas/SKILL.md
- DESIGN.md
- DECISIONES.md

## God Nodes (most connected - your core abstractions)
1. `Debug` - 6 edges
2. `Web design` - 6 edges
3. `Contexto del proyecto` - 6 edges
4. `Dashboard brief (for the Stitch prompt)` - 5 edges
5. `Verify (UI)` - 4 edges
6. `Build judgments with Laya` - 3 edges
7. `Laya` - 3 edges
8. `Review` - 3 edges
9. `Agent rules` - 3 edges
10. `Project` - 3 edges

## Surprising Connections (you probably didn't know these)
- None detected - all connections are within the same source files.

## Communities (15 total, 5 thin omitted)

### Community 0 - "Debug"
Cohesion: 0.29
Nodes (6): 1. Root cause, 2. Compare, 3. Hypothesis, 4. Fix, Debug, Red flags → back to step 1

### Community 1 - "Web design"
Cohesion: 0.29
Nodes (6): Before HECHO, Steps (only case 1 or case 2), Style = `DESIGN.md`, Web design, When Stitch does not run, When Stitch runs

### Community 2 - "Contexto del proyecto"
Cohesion: 0.29
Nodes (6): Comandos utiles, Contexto del proyecto, Estado, Notas para el agente, Produccion, Stack

### Community 3 - "Dashboard brief (for the Stitch prompt)"
Cohesion: 0.33
Nodes (5): Anatomy (always), Charts without libraries (inline SVG, no CDN), CSS, Dashboard brief (for the Stitch prompt), Data honesty (non-negotiable)

### Community 4 - "Verify (UI)"
Cohesion: 0.40
Nodes (4): 1. Screenshots, 2. Look, 3. Fix and repeat, Verify (UI)

### Community 5 - "Agent rules"
Cohesion: 0.50
Nodes (3): Agent rules, Flujo, Think → Simple → Surgical → Verify (Karpathy)

### Community 6 - "Build judgments with Laya"
Cohesion: 0.50
Nodes (3): Build judgments with Laya, Call, Design

### Community 7 - "Laya"
Cohesion: 0.50
Nodes (3): Laya, Reply (decision-only requests), Steps

### Community 8 - "Review"
Cohesion: 0.50
Nodes (3): Check, Do, Review

### Community 9 - "Project"
Cohesion: 0.50
Nodes (3): Docs, Project, Setup

## Knowledge Gaps
- **35 isolated node(s):** `1. Root cause`, `2. Compare`, `3. Hypothesis`, `4. Fix`, `Red flags → back to step 1` (+30 more)
  These have ≤1 connection - possible missing edges or undocumented components. (Counts symbols only; 50 node(s) total have ≤1 connection when file, concept and rationale nodes are included.)
- **5 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **What connects `1. Root cause`, `2. Compare`, `3. Hypothesis` to the rest of the system?**
  _35 weakly-connected nodes found - possible documentation gaps or missing edges._