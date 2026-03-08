# Half-Done Project Recovery Builder Runbook

Purpose: turn half-finished projects into shippable increments using Tenchi Flux Studio Agents.

## 60-Min Recovery Sprint

### 1) Triage (10 min)
- **Senior Project Manager**: convert current state into exact TODOs.
- Output: `recovery/<project>/task-scope.md`

### 2) Build (25 min)
- **Rapid Prototyper** + **Frontend Developer** (+ Backend Architect if needed).
- Output: `recovery/<project>/patch-v1.md` + changed files.

### 3) Proof QA (15 min)
- **Evidence Collector** + **Reality Checker**
- Output: `recovery/<project>/qa-proof.md` (screens + checks + pass/fail)

### 4) Ship Note (10 min)
- **Executive Summary Generator**
- Output: `recovery/<project>/ship-note.md` (what changed, what’s next)

## Builder Prompt (copy/paste)

"Use Agents Orchestrator mode. Recover a half-done project to one shippable increment in 60 minutes.

Project: <name>
Goal: <single measurable outcome>
Constraints: <time/tech constraints>

Required outputs:
1) task-scope.md
2) patch-v1.md (with exact file changes)
3) qa-proof.md (evidence + pass/fail)
4) ship-note.md

Do not polish endlessly. Artifact-first delivery only."

## Suggested first targets (from current board)
1. BBD one-page product template (finish v1 structure + CTA + mobile pass)
2. Aesthetic Tile blog milestone update (publish-ready draft + proof)
3. YouTube Intake V1 fallback hardening (single failing URL + payload fix)
