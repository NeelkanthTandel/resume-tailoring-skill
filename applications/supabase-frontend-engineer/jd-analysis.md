# Supabase — Frontend Engineer: requirement map

Verbatim posting: `jd-verbatim.md` (supplied by candidate; jobs.ashbyhq.com is egress-blocked here).
This file supersedes the earlier reconstruction built from search snippets.

## Requirements

| # | Requirement | Weight | Resume coverage |
|---|---|---|---|
| R1 | 0→1 track record, **"ideally something you can point us to"** | Critical | **Strong** — Gullynest, live URL on the resume, with listings/users/closures |
| R2 | Iterated on real user feedback, not a handed-down spec | Critical | **Strong** — Gullynest bullet 4; Mixpanel/UXCam-driven prioritisation at Neev |
| R3 | TypeScript + deep React | Critical | **Strong** |
| R4 | Modern landscape: SSR, streaming, server components, **edge** | Critical | **Partial** — App Router/RSC/Server Actions/SSR-ISR claimed; **edge unclaimed** |
| R5 | AI agents: review output, tighten architecture on overreach, give guardrails to self-verify | Critical | **Strong** — dedicated bullet, near-verbatim match |
| R6 | Quality pipeline as layered checks: type safety at boundaries, lint/format, unit + component tests, **contract tests vs APIs**, **accessibility**, **visual regression**, **bundle-size budgets** | Critical | **Weak** — only strict TS + Vitest/RTL. Four of seven layers absent |
| R7 | Tooling fluency: **Vitest, Playwright, MSW** or equivalents; opinions on where a check runs and what it's worth | Critical | **Partial** — Vitest/Jest/RTL yes; **no Playwright, no MSW** |
| R8 | "A bug caught once is caught forever" — add the check that would have caught it, at the cheapest stage | Critical | **Unclaimed** — no bullet expresses regression-test discipline |
| R9 | End-to-end: frontend UI, **API contracts**, **preview deploys**, **observability** | Important | **Partial** — full-stack + API work strong; preview deploys/observability unclaimed |
| R10 | **Work in the open** — publicly, in a codebase thousands read and contribute to | Important | **Weak** — GitHub handle added, but no public/OSS work shown |
| R11 | Autonomy + async written communication | Important | **Strong** — sole engineer, remote US role, co-founder |

## What changed vs. my earlier reconstruction

Got right: Studio/marketing-docs ownership, 0→1 + user-feedback bar, "CI is what keeps that speed
safe", AI-agent comfort, TS/React + SSR/streaming/RSC/edge, Vitest/Playwright/MSW, autonomy/async.

**Missed — all material:**
1. The quality pipeline is spelled out as **seven layers**, not a general ask. Contract tests,
   accessibility, visual regression, and bundle-size budgets were entirely absent from my map.
2. The **"bug caught once is caught forever"** bullet — regression discipline as its own
   requirement — did not exist in my reconstruction.
3. **"Work end-to-end and in the open"** — preview deploys, observability, and public codebase work.
4. **"Ideally something you can point us to"** — the 0→1 claim is expected to be linkable.
   Gullynest satisfies this; worth knowing it's an explicit ask.

**Wrongly included** (came from the separate Frontend-Docs posting or older reqs, not this one):
- "Write docs, build example applications, engage the community on GitHub" as responsibilities.
- An EU-timezone constraint. This role is **fully remote, hired globally** — no timezone restriction.
- "Large Next.js app" as a stated descriptor of Studio (true in other postings, not stated here).
