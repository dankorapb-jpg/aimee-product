# Aimée — AI Voice Manager for Clinics

Aimée is an AI voice agent that answers phone calls for private medical clinics
(dental, GP practices, aesthetics/beauty) — 24/7, in the clinic's own language,
booking, rescheduling and cancelling appointments directly in the clinic's
existing calendar/CRM.

This repository is a **public overview for grant and accelerator applications
(e.g. Y Combinator)**. It does not contain production source code.

## Contents

- [PRODUCT.md](./PRODUCT.md) — what the product does, who it's for, why it's different
- [ARCHITECTURE.md](./ARCHITECTURE.md) — top-level system architecture
- [FEATURES_AND_CRM.md](./FEATURES_AND_CRM.md) — supported CRMs/calendars and core features
- [media/demo](./media/demo/README.md) — video walkthroughs (agent setup, a real call)
- [media/screenshots](./media/screenshots/README.md) — product screenshots

## Live product

Website: https://tryaimee.com/offer

## A note on scope

⚠️ **This is not the production codebase.** The actual implementation —
prompts, conversation state machine, latency optimizations, CRM adapter
internals, and infrastructure configuration — is proprietary and kept in a
private repository. What you'll find here is intentionally limited to what's
useful for evaluating the product and team from the outside: what it does,
how it's put together at a high level, and what it looks/sounds like in use.
