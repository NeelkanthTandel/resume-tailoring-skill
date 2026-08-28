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
1. **No E2E tests, no CI merge gate.** The single weakest point against this JD, which names Playwright
   and MSW and says "the CI is what keeps that speed safe." Nothing on the resume claims otherwise.
   Highest-leverage fix before applying: Playwright over Gullynest's core flows (search → listing →
   lead capture) plus a GitHub Actions workflow gating typecheck + tests on every PR.
2. **MSW is absent entirely.** Worth an afternoon on Gullynest's API mocks if there's time.
3. **Edge runtime** is claimed nowhere. If Gullynest uses Vercel Edge or Supabase Edge Functions, say so —
   it completes R2.
4. **Location line still reads "Gujarat, India"** as on the source resume, though Unwrap Labs and
   Gullynest are both Bengaluru. Supabase is remote-global so it matters little, but pick one deliberately.
5. **Public work.** github.com/NeelkanthTandel is now on the resume — make sure the profile shows
   something real before submitting.

## Verification notes
- jobs.ashbyhq.com and supabase.com are blocked by this session's egress proxy. The JD was reconstructed
  from search snippets; requirements in `jd-analysis.md` should be checked against the live posting.
