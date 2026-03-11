# AGENTS.md

This file provides operational guidelines for AI agents working on this repository.

Agents must read this file before implementing features.

---

## Project Objective

Build a platform where influencers launch product campaigns and followers can pre-order products before production.

The system must support campaign creation, campaign discovery, payments, and order tracking.

---

## Core Principles

Mobile First  
The platform must be designed for mobile usage first. Most users will access the platform through social media links on mobile devices.

Performance  
Pages must load quickly, especially campaign pages.

Security  
Payments and personal data must be handled securely.

Scalability  
The architecture must support traffic spikes during campaign launches.

---

## Development Guidelines

When implementing features, agents must:

Understand the relevant documentation inside `/docs`.

Follow the functional and non-functional requirements defined in the documentation.

Avoid introducing new frameworks or libraries unless necessary.

Write clean, modular code.

Document significant changes.

---

## Documentation Policy

When implementing a feature that changes product behavior, the agent must update the relevant documentation inside `/docs`.

Examples:

Campaign logic changes → update `business-rules.md`  
New UI flow → update `user-flows.md`

---

## UI Guidelines

All interfaces must follow mobile-first principles described in:

docs/ui-mobile-first.md

Desktop layouts should be adaptations of mobile layouts.

---

## Implementation Strategy

Features should be implemented incrementally.

Each feature should:

- respect existing architecture
- avoid breaking existing flows
- maintain system consistency
