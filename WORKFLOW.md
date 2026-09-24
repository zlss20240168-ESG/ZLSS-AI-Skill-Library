# ZLSS MOU Skill — Execution Workflow v1.1

## Purpose
This file is the mandatory execution entry point for any AI drafting or reviewing a ZLSS MOU.

## Required Reading Order
Before drafting:
1. Read `SKILL.md`
2. Read `rules/deal-architecture.md`
3. Read `rules/commercial-logic.md`
4. Read `rules/information-disclosure.md`
5. Read `rules/writing-rules.md`
6. Search `cases/` for a relevant precedent
7. Draft
8. Run `evaluator/MOU-95-Scorecard.md`
9. Run Red Team review
10. Revise until score >=95
11. Human review
12. Freeze candidate version

## Phase A — Deal Diagnosis
Before writing any clause, output an internal Deal Brief:
- Transaction type
- Party A contribution
- Party B contribution
- New value being created
- Money classification
- Natural unit economics
- Current relationship stage
- Information that may be disclosed now
- Information that must be protected
- Immediate next action

If these are unclear, do not begin substantive drafting.

## Phase B — MOU Architecture
Build the shortest structure that communicates:
1. Parties
2. Cooperation purpose
3. Cooperation principles
4. Contributions
5. Commercial logic
6. Development approach
7. Future commercial arrangements
8. Confidentiality / IP as needed
9. Term / transition as needed
10. Next stage

Do not mechanically include sections that add no value.

## Phase C — Financial Language Check
For every monetary or forecast figure, classify it explicitly:
- development budget
- service fee
- investment
- gross revenue
- net profit
- cost
- funding recovery
- party-specific distribution

Never allow an unlabeled economic number.

## Phase D — Disclosure Gate
Tag sensitive content internally:
- G1 Public / Pre-MOU
- G2 Post-MOU
- G3 Post-NDA
- G4 Formal Agreement / Execution

Remove from the MOU anything above the permitted gate.

## Phase E — Counterparty Simulation
Review from five perspectives:
- CEO: Is the deal worth pursuing?
- CFO: What does the money mean?
- Technical: Is the claim credible without giving away know-how?
- Legal: Are essential protections present without over-lawyering?
- Counterparty: Does this make me want to continue?

## Phase F — 95-Point Gate
Score using `evaluator/MOU-95-Scorecard.md`.
Below 95: revise.
95+: candidate only; human review remains mandatory.

## Phase G — Learning Loop
After material negotiation or revision:
1. Record what changed.
2. Record why.
3. Identify any failed pattern.
4. Generalize the lesson.
5. Add case-specific evidence to the case folder.
6. Promote a rule into core SKILL only after validation.

## Core Rule
Do not copy the Kazakhstan MOU. Learn from the Kazakhstan case.
