# scaling-journey

A research framework for the practical tradeoff between self-hosting, GitHub, and GitLab for security research and small software projects.

## Research question

Does public visibility materially improve security outcomes when a project is unfunded or under-resourced?

This framework compares:
- self-hosted repositories
- GitHub public repositories
- GitLab public repositories

It uses the “many eyes” argument — especially Linus’s Law — as a test case, but it does not treat visibility as a guarantee. In practice, the real variables are:
- funding
- expertise
- visibility
- active review
![](/screenshot.jpeg)
## Cenral claim

Public visibility is not security by itself.

A project is safer when it has:
- enough funding to maintain infrastructure
- enough expertise to review and fix issues
- enough active contributors to inspect code and respond to reports

For unfunded work, public hosting is often the only viable review layer. For funded work, self-hosting can be reasonable because the project can afford the cost of expertise and infrastructure.

The real question is not “private or public?” but:
- how much review capacity does the project actually have?
- how much maintenance burden can it support?
- how much visibility does it need to compensate for limited expertise?

---

## Why this matters

The common assumption is that privacy creates safety and public hosting creates exposure. That is an oversimplification.

The practical problem for many small security projects is:
- no paid security staff
- limited infrastructure budget
- weak review capacity
- no clear disclosure process
- no security audit

In those conditions, public hosting can be a meaningful safety net. A private repository with no reviewers is not safer in any useful sense. It is merely invisible.

---

## Core model

Security outcomes are not determined by platform branding alone.

They are shaped by:
- funding
- expertise
- visibility
- code review activity
- maintenance maturity

A project with strong funding and weak visibility may be safer than a project with high visibility and no review capacity.

---

## Comparison

This framework compares three operating modes:

- private or self-hosted repositories
- public GitHub repositories
- public GitLab repositories

The question is not “which one is universally best?”
The question is:
- when does visibility improve outcomes?
- when does isolation become a liability?
- when does self-hosting become safe?
