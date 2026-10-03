# Project Notes

Supplementary detail to the [profile README](https://github.com/Aquib2004).
The README is the canonical source; this file exists for per-project status.

> **Accuracy policy.** Demo links are listed only when they are live and
> verified. Unverified deployments are marked as such rather than linked, and
> star counts are never estimated. Where a project is a work in progress, it
> says so.

---

## Projects

### Multilingual Communication Assistant

**Status:** Active · MIT · Python + TypeScript

Approval-gated workflow for multilingual community communication: plain-language
rewriting → human approval → translation → verification → escalation.

What makes it interesting is what happens around the model call:

- The approval gate is enforced server-side and cannot be skipped.
- Protected values (names, phone numbers, dates, IDs) are extracted, masked as
  placeholders before translation, then restored — so a model never
  "translates" a deadline.
- Every critical fact is verified against the source deterministically, with
  back-translation and risk classification.
- High-consequence content escalates to professional human translation rather
  than being published.

**Status:** Backend 79 tests, frontend 26 tests, `mypy --strict` clean, three
GitHub Actions workflows green. Docker images and the live OpenAI/local providers
have **not** been verified — see the README's verification table.

[Repository](https://github.com/Aquib2004/multilingual-communication-assistant)

---

### AMUCS Nexus

**Status:** Active · MIT · Python + Next.js

Source-grounded information platform for the AMU Department of Computer
Science. Answers carry citations, and an extractive fallback ensures the system
never invents URLs, dates, or exam information.

**Status:** Actively developed. Not yet deployed publicly.

[Repository](https://github.com/Aquib2004/amu-cs-nexus)

---

### MakeMyTrip Clone

**Status:** Prototype · JavaScript (React)

Travel booking UI integrating the TravClan sandbox API for authentication,
flight search, and hotel search.

**Status:** Sandbox-only. No production deployment. Not publicly deployed.

[Repository](https://github.com/Aquib2004/makemytrip-app)

---

### AI Fusion

**Status:** Early / incomplete · Python

Early work unifying multiple AI providers behind a single interface. The
repository currently contains a README only and is **not** a working application
despite earlier descriptions of it as one.

[Repository](https://github.com/Aquib2004/ai-fusion)

---

### Lab Weeks

**Status:** Archived reference material

Academic lab work. Kept for reference.

[Repository](https://github.com/Aquib2004/lab-weeks)

---

## Notes on this file

An earlier version of this document listed demo URLs and star ratings that could
not be verified, including links to deployments that no longer resolve. Those
have been removed rather than left to mislead. If a project gains a working
public deployment, it can be listed here with the link.

<p align="center">
  <sub>Last reviewed: October 2026</sub>
</p>
