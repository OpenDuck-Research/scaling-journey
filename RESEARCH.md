# Research framework

## Question

What matters more for security outcomes:
- the hosting platform, or
- the project’s actual capacity to review, fix, and maintain code?

This framework looks at self-hosting, GitHub, and GitLab through a practical security lens rather than a platform ideology lens.

---

## Background

The simplified version of the “many eyes” argument is:

> public code is safer because more people can see it.

This idea is often summarized as Linus’s Law:
> “Given enough eyeballs, all bugs are shallow.”

The problem is that “eyeballs” are not an objective unit. A project can have:
- many passive viewers
- few active reviewers
- many watchers but no security expertise
- active review but little public visibility

Security outcomes depend less on whether the project is public, and more on whether it is actively reviewed by people who understand the code and can respond to reports.

---

## Working hypothesis

Public visibility increases the chance of vulnerability discovery only when it becomes active scrutiny.

Thus, the useful model is not:

- platform security = hosting choice

The better model is:

- security outcome = funding + expertise + visibility + review activity

---

## Key assumptions

### 1. Visibility alone is weak
Public code does not automatically produce secure code.

### 2. Review capacity matters more than hosting format
A public repository with no active reviewers is not meaningfully safer than a private one with no review.

### 3. Funding gates expertise
Funding enables:
- paid reviewers
- auditing
- infrastructure maintenance
- better incident response
- safer operational practices

### 4. Self-hosting is not automatically safer
Control is useful, but it carries maintenance and security costs. Without enough expertise or support, it can create hidden risk rather than security.

---

## Why comparing platforms is difficult

Security outcomes depend on:
- project complexity
- team size
- maintenance maturity
- threat model
- funding
- code age
- disclosure policy
- review culture

That makes clean platform experiments rare. The better method is case-based analysis:
- compare real projects
- identify repeated patterns
- avoid treating platform branding as cause

---

## Research approach

This framework examines:
- projects with public code and low review capacity
- projects with public code and strong review capacity
- funded projects using self-hosting
- projects that failed despite public visibility

The purpose is not to declare one platform “best.”
The purpose is to identify when public visibility helps, and when it does not.

---

## Main conclusion

For unfunded work, public hosting often becomes the only practical review surface.

This does not imply that public hosting is sufficient. It means:
- a private repository with no review is a risk
- a public repository with no review is also a risk
- visibility matters only when it becomes observable, testable, and actionable

The important distinction is:
- passive visibility
- active scrutiny

This framework treats active scrutiny as the critical variable.

---

## Decision rule

- funded and expert → self-hosting may be reasonable
- unfunded and lacking expertise → public hosting is the safer default
- funded but inexperienced → public visibility still helps
- unfunded and isolated → high-risk configuration

---

## Key phrase

Visibility is not security. Active review is.

---

## Limits

This is a research framework, not a universal law.

The main limitation is that platform-specific security outcomes are under-studied. The evidence is stronger on the role of funding and review capacity than on the superiority of any single hosting model.