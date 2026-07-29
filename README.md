# Trade Self-Check

**A decision pause before emotional trades.**

[Try the live product](https://tradeselfcheck.com) · English and 中文

Trade Self-Check helps individual investors pause before acting. A user writes
down the trade they are considering, the reasoning behind it, and what they are
feeling. The product turns that context into a concise reflection card: what
may be driving the decision, what still needs to be made explicit, and one
small action to take before proceeding.

It does **not** predict prices, recommend securities, or tell a user to buy,
sell, or hold.

## The problem

Many investing mistakes do not come from a lack of information. They happen in
the short distance between knowing one's rules and acting under pressure:
chasing a move, reacting to regret, concentrating a position, or changing a
plan mid-trade.

I built Trade Self-Check to make that distance visible at the moment it
matters.

## How it works

1. Describe the trade in your own words.
2. Receive a calm reflection card focused on reasoning, emotion, and plan
   completeness.
3. If useful, add portfolio context for a second check on concentration,
   pacing, and cash flexibility.
4. Save past cards and revisit patterns over time.

## Product decisions

- **Pause, not predict.** The product supports decision quality without
  pretending to know what a security will do next.
- **One useful action first.** The first screen is a short anchor and a small
  next step; deeper analysis stays secondary.
- **Rules before prose.** Deterministic checks handle numerical and portfolio
  constraints. The language model explains them in calm, readable language.
- **Guardrails are part of the product.** Prompts, server-side validation, and
  interface copy all enforce the same boundary: no stock picks, timing calls,
  target prices, or invented numbers.
- **Bilingual by design.** English and Chinese are supported across the core
  product journey.

## Technical outline

- TanStack Start, React 19, TypeScript, Vite, Tailwind CSS
- Better Auth and Drizzle ORM
- Supabase/PostgreSQL in production
- Pluggable LLM providers with structured output and input safeguards
- Vercel deployment

## Status

The product is live and under active development.

The source code is private. This repository is a public product overview
covering the problem, product thinking, and implementation boundaries.

---

Trade Self-Check is an educational decision-support tool, not investment
advice.
