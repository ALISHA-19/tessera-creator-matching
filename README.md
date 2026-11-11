# Tessera: fit-first matching for a creator-brand marketplace

A product management case study by **Alisha Chaudhari**, written for the *Product Manager – Creator Economy* assignment.

**Live site:** https://alisha-19.github.io/tessera-creator-matching/
**Clickable wireframe:** https://alisha-19.github.io/tessera-creator-matching/prototype.html

> Tessera, its brands and its creators are fictional. Every figure marked **A** on the site is my assumption, and each one comes with a week-1 check.

## The problem in one line

Creators can't tell which campaigns they can win, and brands can't tell which applicants fit. Tessera doesn't capture or show fit, so creators spend unpaid hours on applications they can't win, and brands take a week to shortlist and still leave slots unfilled.

## What I propose

**Fit-first matching**, built around one core loop:

> See fit → apply to fit → rank by fit → get a reasoned decision

- **Structured brief and creator profile.** Requirements become fields instead of free text.
- **"You qualify" / "Not eligible yet".** Creators see the exact gap (e.g. "1.8K followers short"), and brands can still invite a near-miss.
- **A match score with reasons.** It uses simple, explainable rules, not AI, and both sides see the same breakdown.
- **A decision by a set date.** Brands decide with one of five reasons. Applications they don't decide count against the brand's visible response record.
- **Capped invites.** Campaigns can fill even when applicants are few, without flooding the top creators.

## How success is measured

| | Metric | Today **A** | Target |
|---|---|---|---|
| North Star | Completed paid collaborations / month | ~600 | ~645–720 |
| Primary (test) | Filled slots per campaign | 4.0 of ~6 | 4.3–4.8 |
| Brand retention | Repeat campaign within 90 days | 35% | 42% |

**The experiment:** an 8-week A/B test, split by **campaign**. Each new campaign is randomly assigned either to the new flow on both sides or to today's flow, and the two groups are compared on filled slots per campaign. I'd roll out if the lift is +0.55 or more (the smallest lift the test can confirm), as long as the guardrails hold.

## What's in the case study

1. **Problem discovery:** what creators want and fear, where the lifecycle breaks, and the four causes of under-filled campaigns
2. **Feature proposal:** the core loop, user flow, an interactive match-score playground, and success criteria
3. **PRD-lite:** goals and non-goals, user stories, requirements, acceptance criteria, states, notifications, edge cases, risks, dependencies, and a plan with questions for each team
4. **Metrics & experimentation:** a metric hierarchy, a realistic target range, guardrails, sizing, and the A/B test in plain words
5. **Trade-offs:** what I left out and why, effort estimates, and the plan if engineering capacity halves
6. **Rejected alternative:** Ops hand-picking creators for every campaign
7. **Clickable wireframe:** the full creator ↔ brand flow with shared sample data

## Files

| File | What it is |
|---|---|
| `index.html` | The case study (a single self-contained page) |
| `prototype.html` | The clickable wireframe, embedded in the case study and also usable on its own |

To view it locally, open `index.html` in any browser. There's no build step.
