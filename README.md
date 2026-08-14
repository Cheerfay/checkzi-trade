# Checkzi

[English](README.md) | [简体中文](README.zh-CN.md)

**Check before you decide.**

[Try Checkzi Trade](https://checkzi.app/) · English and 中文

Checkzi is a decision self-check platform for moments when emotion, urgency,
or incomplete information can outrun judgment. It helps people put a decision
into words, inspect what is driving it, and take one useful step before acting.

[Checkzi Trade](https://checkzi.app/) is the first and currently only live
scenario. It focuses on trading rationale, position size, and emotion without
predicting prices or making the decision for the user.

## Why it exists

Some costly decisions are not caused by a lack of information. They happen in
the short distance between knowing one's rules and acting under pressure.

Checkzi is built for that distance: a structured pause that makes the current
reasoning visible without pretending that software should take over the final
choice.

## Current live scenario: Checkzi Trade

1. Describe the trade in your own words.
2. Receive a concise self-check card focused on reasoning, emotion, and plan
   completeness.
3. If useful, add portfolio context for a second check on concentration,
   pacing, and cash flexibility.
4. Save past cards and revisit patterns over time.

Checkzi Trade does **not** predict prices, recommend securities, or tell a user
to buy, sell, or hold.

## Platform direction

Future Checkzi scenarios may address other decisions where a short,
well-bounded self-check is useful. Each scenario should keep the same core:

- capture the real decision in the user's own words;
- separate facts, assumptions, pressure, and missing information;
- apply rules specific to the scenario before generating explanatory prose;
- offer one proportionate next action instead of an authoritative answer;
- preserve the user's agency and make the product boundary explicit.

Only Trade is live today. Other scenarios are product direction, not shipped
capabilities.

## Product decisions

- **Pause, not predict.** Improve decision quality without claiming certainty.
- **One useful action first.** Keep the first result concise; deeper analysis
  stays secondary.
- **Rules before prose.** Deterministic checks handle scenario constraints;
  the language model explains them in calm, readable language.
- **Guardrails are part of the product.** Prompting, server-side validation,
  and interface copy enforce the same boundary.
- **Bilingual by design.** English and Chinese are supported across the core
  product journey.

## Technical outline

- TanStack Start, React 19, TypeScript, Vite, Tailwind CSS
- Better Auth and Drizzle ORM
- Supabase/PostgreSQL in production
- Pluggable LLM providers with structured output and input safeguards
- Vercel deployment

## Status

Checkzi Trade is live and under active development. The source code is private.
This repository is a public product overview covering the problem, product
thinking, current capabilities, and implementation boundaries.

---

Checkzi Trade is an educational decision-support tool, not investment advice.
