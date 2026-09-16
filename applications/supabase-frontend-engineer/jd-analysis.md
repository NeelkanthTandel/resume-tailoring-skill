# Supabase — Frontend Engineer

**Verbatim JD received 2026-09-16 — see `jd-verbatim.md`.** This file previously held a
reconstruction built from search snippets (Ashby was egress-blocked). Corrections below.

## Corrections to the earlier reconstruction
| Earlier claim | Reality | Impact |
|---|---|---|
| "Studio is a large Next.js app in TypeScript" | JD never names Studio's stack | Conflated with a *different* Supabase frontend posting. No resume change — Next.js is still true of the candidate — but do not assert it about Studio in a cover letter or interview. |
| "R8: strong all-around web dev — APIs, Postgres, deployments" | Real wording is "Frontend UI, the API contracts it depends on, preview deploys, observability" | Postgres is **not** a stated requirement here. Narrower and more frontend-weighted than assumed. |
| "Some frontend reqs are EU-timezone-scoped" | This posting is **Remote, Global** | The timezone caution does **not** apply to this req. Candidate is IST — no constraint. |

## Confirmed correct
- The seven quality layers, verbatim: type safety at the boundaries, lint and format, unit and
  component tests, contract tests against APIs, accessibility, visual regression, bundle-size budgets.
- "A bug caught once is caught forever" — add the check at the cheapest stage that can catch it.
- Vitest, Playwright, MSW named explicitly.
- SSR, streaming, server components, edge.
- AI-agent comfort: review output, tighten architecture where they overreach, give them guardrails.
- 0→1 with iteration on real user behaviour.

## Newly surfaced, not in the reconstruction
- **"ideally something you can point us to."** They want a link to the 0→1 product. Gullynest's URL
  is on the resume — this is now load-bearing, not decorative.
- **"do it publicly, in a codebase thousands of developers read and contribute to."** Public work is
  weighted more heavily than assumed. The empty GitHub profile is a sharper liability than first scored.
- "We live and die by user feedback and relentlessly address issues every day."

## Quality-layer coverage (updated 2026-09-16)
| Layer | Status |
|---|---|
| Type safety at the boundaries | Covered — strict TypeScript |
| Lint and format | Assumed, not claimed |
| Unit and component tests | Covered — Vitest / RTL |
| **End-to-end (Playwright)** | **NOW COVERED — admin CRM E2E suites, authored with AI agents, flows specified and diffs reviewed by the candidate** |
| Contract tests against APIs | Gap |
| Accessibility | Gap |
| Visual regression | Gap |
| Bundle-size budgets | Gap |
| Regression discipline | Covered — a check added at the cheapest catching stage |
| Preview deploys + observability | Covered — Vercel previews, production error monitoring |

Five of the JD's layers evidenced, four gaps remaining. Playwright was the single most valuable one
to close because the JD names it by tool.

## Open question
Whether the Playwright suites **run in CI on every PR**. If they do, the bullet should say so — the
JD's phrasing is "wiring up pipelines" and "the CI is what keeps that speed safe", which is a
stronger claim than having tests that run locally. Currently written without the CI claim.
