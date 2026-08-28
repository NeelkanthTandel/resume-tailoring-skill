# Tailoring report — Supabase Frontend Engineer

## What changed and why

| Change | Requirement served |
|---|---|
| Added a 2-line summary leading with Gullynest, "blank editor to paying users", and the AI-agent workflow | R5, R6 — the JD's two loudest differentiators, now visible in the first 3 seconds |
| Gullynest added as the lead block, 5 bullets, above the blockchain work | R6 — "launched something, watched real people use it, improved it on that feedback" |
| Retitled "Full-stack developer" → "Frontend / Full-Stack Engineer"; added a `Frontend / Full-Stack Engineer` tagline under the name | Positioning — frontend-forward without overclaiming; the JD still wants Postgres/API/deploy range |
| Skills reordered: Frontend first, with App Router / Server Components / Server Actions / SSR-ISR spelled out | R2 — the old resume had zero SSR/RSC vocabulary |
| Supabase (Auth, RLS, Storage) called out explicitly, plus Postgres RLS in a Gullynest bullet | R8 + applying to Supabase as an actual user of the product |
| New "Quality & Delivery" skills line; quality framed inside the AI bullet as what makes generated code fail at build time | R3, R4 — quality as a velocity lever, not a checkbox |
| New "AI-assisted development" skills line | R5 |
| Neev intern merged into one company block; Tvisi, Freelance, EkAyana compressed to one line each | Fit — one page, with space spent on what this JD rewards |
| GitHub handle added to the header | Supabase frontend explicitly mentions community engagement on GitHub |

## Metrics used
- 296 live listings; 954 users; 10–15 paid move-ins in the last two months; launched April 2026; sole engineer.
- Deliberately framed as a conversion story rather than a scale story — 954 users producing 296 listings
  and ~12 closures/month reads far better than the raw user count alone.
- No revenue figure stated. The 50%-of-one-month's-rent model is named so a reader can infer the unit
  economics without the candidate putting a number on paper he'd have to defend.

## Known gaps — interview prep
*(Rewritten against the verbatim posting in `jd-verbatim.md`. The real JD is materially more
demanding on quality than the reconstruction this resume was first built against.)*

**1. The quality pipeline is the gap, and it is bigger than it looked.**
The posting names seven layers: type safety at the boundaries, lint/format, unit and component
tests, contract tests against APIs, accessibility, visual regression, and bundle-size budgets.
The resume currently evidences two — strict TypeScript and Vitest/RTL. Ranked by leverage per hour
on Gullynest before applying:
   - **Playwright over the core flows** (search → listing → lead capture) + a **GitHub Actions gate**
     on typecheck/lint/tests. Named tooling, and it converts R7 from partial to strong.
   - **Bundle-size budget** — cheapest item on the list. `next build` already reports route sizes;
     a CI threshold is an afternoon.
   - **Accessibility** — `eslint-plugin-jsx-a11y` plus an axe pass in Playwright. Also cheap.
   - **MSW** for API mocks; **visual regression** (Playwright snapshots) if time allows.

**2. "A bug caught once is caught forever" is its own requirement, and nothing on the resume
   speaks to it.** If any Gullynest or Neev bug fix came with a regression test, that is a bullet
   worth writing — the JD asks specifically for adding the check *at the cheapest stage that can
   catch it*. Needs confirmation before it goes on the page.

**3. "Work in the open."** The JD wants public work in a codebase thousands read. The GitHub handle
   is on the resume; the profile needs to show something real. Any OSS contribution, or making a
   slice of Gullynest public, would answer this directly.

**4. Edge runtime still unclaimed.** Listed explicitly under the modern-landscape requirement.
   If Gullynest touches Vercel Edge or Supabase Edge Functions, say so — it completes R4.

**5. Preview deploys and observability** are named under "work end-to-end". Vercel preview deploys
   are likely already in use on Gullynest; error monitoring may not be. Both are claimable if true.

**6. Location line reads "Gujarat, India"** as on the source resume, though Unwrap Labs and
   Gullynest are Bengaluru. Fully remote role hired globally, so it is low-stakes — but pick one.

## Verification notes
- Requirement map rebuilt from the candidate-supplied verbatim posting on 2026-08-28.
- Two errors in the earlier search-based reconstruction are corrected in `jd-analysis.md`: this role
  has **no EU-timezone constraint** (fully remote, global), and docs/example-apps/community
  engagement are **not** responsibilities of this req — they belong to the separate Docs posting.
