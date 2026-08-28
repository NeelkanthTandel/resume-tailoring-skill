# Tailoring report — Supabase Frontend Engineer (Docs)

## Why this role, out of everything still open
Of the ~16 roles open at Supabase, this is the only remaining one where the candidate is genuinely
competitive. It is a Next.js/TypeScript role about **building tooling other people work inside** —
which is what he has actually been doing — rather than an infrastructure, Go, Postgres-internals,
or non-engineering role.

Runner-up: **SDK Engineer – JavaScript**. Deep TS/JS is there, but the role wants library and public
API design plus open-source maintenance, and he has neither. Worth a shot only after the GitHub gap
below is closed.

## The two bullets that do the work
This resume is not a reshuffle of the Frontend one. Two things were reframed because they map almost
one-to-one onto the docs brief:

1. **Gullynest's moderation pipeline → a content pipeline.** The JD's core responsibility is
   "maintaining documentation tools and content pipelines… for contributors." He built a
   review-before-live pipeline where every listing from three supply types passes through human
   moderation, *in tooling he built for the reviewers*. Structurally the same problem.
2. **Neev's admin portal → tooling for non-engineer colleagues.** The JD asks for "tools for product
   teams and Technical Writers." He built the internal portal non-engineering colleagues ran the
   business through. Previously this was buried in a generic "admin web portal" mention; it now
   leads the Neev block.

Also added: a "Tooling for other teams" skills line, and the marketing-site work promoted to its own
bullet, since Team Frontend owns the marketing site too.

## Requirement coverage
| Req | Status |
|---|---|
| X1 Level up docs site for indie→enterprise audience | **Strong** — Next.js depth, real product surface |
| X2 Docs tooling and content pipelines for contributors | **Strong** — moderation pipeline, admin portal |
| X3 Build Docs AI tools | **Strong** — daily agent workflows, guardrail design |
| X4 Engage OSS community on GitHub (issues, PRs) | **GAP — nothing to show** |
| X5 TypeScript / React / Next.js | **Strong** |
| X6 Writing for a technical audience | **GAP — no public writing** |
| X7 Async, autonomous, remote | **Strong** |

Five of seven are strong. Both gaps are the same underlying problem: **no public footprint.**

## The one thing to fix before applying
X4 is named explicitly in this posting and github.com/NeelkanthTandel is now printed on the resume —
a reviewer will open it. For a docs role specifically, the cheapest credible fix is a handful of
real documentation contributions: Supabase's own docs are open source, and typo/clarity/example
fixes are merged routinely. A few merged PRs against supabase/supabase would close X4 and X6 at once
and would be visible to exactly the team reading the application.

## Verification notes
- supabase.com and jobs.ashbyhq.com are blocked by this session's egress proxy. Role list and JD
  reconstructed from search; **verify the posting and its timezone requirement before applying.**
- At least one Supabase frontend req has been posted EU-timezone-scoped. Candidate is IST (UTC+5:30).
