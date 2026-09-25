# Test Log: Airline Digital Maturity Assessment

Tested in headless Chromium with Chart.js 4.4. Each scenario answered all 20 questions and submitted. Dimension order: Data, Journey, Ops, AI, Change.

## Phase 3 persona tests (required)

| Persona | Scores (Data, Journey, Ops, AI, Change) | Two lowest shown | Profile |
|---------|------------------------------------------|------------------|---------|
| Stage 2 airline | 1.75, 2.25, 1.75, 1.5, 1.75 | AI & Predictive Decisioning; then Data, Ops and Change tied | Grounded Legacy Carrier |
| Stage 4 airline | 3.75, 4.25, 4.0, 3.75, 4.25 | Data and AI (tied) | Digitally Airborne Network |

The two radar shapes are clearly different: a small pentagon inside ring 2 versus a large one near ring 4.

## Pattern and edge-case tests

| Scenario | Scores | Profile shown | Expected? |
|----------|--------|---------------|-----------|
| Data far below the rest | 1, 4, 4, 3, 4 | Siloed Flight Deck | Yes |
| Strong journey, weak AI | 3, 4, 3, 2, 3 | Slick App, Legacy Brain | Yes |
| Change far below the rest | 4, 4, 4, 3, 2 | Tools the Frontline Won't Fly | Yes |
| Data and Change tied lowest | 2, 4, 4, 4, 2 | Siloed Flight Deck (both named; airline priority picks data) | Yes |
| Data and AI tied lowest, journey high | 2, 4, 3, 2, 3 | Siloed Flight Deck (both named; data outranks AI) | Yes |
| Uneven, no archetype | 3, 3, 2, 3, 4 | No single archetype, with next steps for the lowest dimensions | Yes |
| All level at 3 | 3, 3, 3, 3, 3 | No single archetype; "no single weakest area" | Yes |

## Requirement checks

- 20 questions, 4 per dimension; every answer option carries an integer value from 1 to 5.
- The five radar axes match the five framework dimension names exactly.
- Submitting with 1 of 20 answered: results stay hidden, the 19 unanswered questions are highlighted, and a message is shown.
- Changing any answer after submitting hides the results again.
- No `localStorage`, `sessionStorage` or cookies; no backend.
- No console errors. No horizontal scrolling at 390 px phone width.
- A script confirmed that profile names, patterns, descriptions and actions in `framework.md` match the `PROFILES` data in `index.html` exactly, and that dimension names match across the tool, framework and rationale.
