# Open questions

This section records what is not yet proven.

## 1. Platform-specific vulnerability rates

There is not enough public data to cleanly compare:
- GitHub vs. GitLab vs. self-hosted repositories
- similar projects under the same conditions
- projects with equal team size, funding, and threat model

This is the main missing dataset for a platform-level claim.

---

## 2. Active review vs passive visibility

The framework assumes:
- passive visibility is weak
- active review is strong

That is plausible, but exact thresholds are unclear.

Questions:
- how many active reviewers are enough?
- how many reviewers are needed for security-critical code?
- what counts as meaningful review?

---

## 3. Funding as causal variable

The case evidence suggests funding is a major factor, but there is no clean statistical proof that it is always decisive.

This deserves more study.

---

## 4. Public hosting and funding pipeline

It is not yet clear how often public hosting leads to:
- sponsorship
- contributor acquisition
- better maintenance support
- better security outcomes

This is a research gap, not a settled conclusion.

---

## 5. Self-hosted security costs

There is not enough measured data on:
- the cost of running secure self-hosted infrastructure
- the time required to maintain a hardened setup
- the expertise needed to keep a project secure

This matters because many unfunded projects underestimate these costs.

---

## Honest conclusion

This framework is strongest on the following points:
- visibility helps only when it becomes review
- expertise matters more than platform branding
- funding is the real gating variable
- unfunded private code can be effectively invisible to both attackers and defenders

This framework is weakest on exact statistical claims about platforms. Those remain open research questions.
