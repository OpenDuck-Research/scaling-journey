# Case studies

## 1. OpenSSL before Heartbleed

### Summary
OpenSSL had public source code and a large user base, but a small maintenance base. It still shipped a critical vulnerability that remained undetected for years.

### Relevant facts
- vulnerability: Heartbleed (CVE-2014-0160)
- discovered: 2014
- likely introduced: 2011-2012
- public code: yes
- maintainers at discovery: very small team
- impact: critical

### What this case shows
Visibility alone did not create effective scrutiny. The problem was not secrecy. The problem was weak review capacity.

This is a strong counterexample to the simplistic idea that public code is automatically secure.

### Lesson
Public code without strong review capacity remains vulnerable.

---

## 2. Tor Project

### Summary
Tor is one of the clearest examples of self-hosted infrastructure combined with public project visibility.

### Relevant facts
- funding: nonprofit support and grants
- team: paid engineering and security staff
- hosting: self-hosted canonical infrastructure and public mirrors
- security model: formal review, disclosure process, audits

### What this case shows
Tor’s security posture is not explained by self-hosting alone. It is explained by:
- institutional funding
- trained staff
- review culture
- active maintenance
- public visibility through mirrors

### Lesson
Self-hosting can be safe when the project has the resources to maintain it correctly. Self-hosting is not automatically safer.

---

## 3. Linux kernel

### Summary
Linux is the strongest example of large-scale distributed review and maintenance.

### Relevant facts
- large contributor base
- distributed review process
- institutional funding
- public visibility
- formal patch review and disclosure practices

### What this case shows
The best outcomes are associated with:
- scale
- active review
- professional maintenance
- sustained funding

This is not a case for one platform. It is a case for scale and capacity.

### Lesson
The strongest security outcomes come from funding and review capacity, not from one hosting model alone.

---

## 4. GitHub and GitLab

GitHub and GitLab matter mostly because they provide visibility, tooling, and exposure.

But they do not create security expertise.

A project can be on GitHub or GitLab and still:
- have weak code review
- have no active security contributors
- suffer from slow disclosure
- lack the expertise to fix critical issues

### Practical conclusion
Platforms provide a surface for review and discovery. They do not replace the need for responsible maintenance or expertise.

---

## Cross-case pattern

| Project | Visibility | Review capacity | Funding | Outcome |
|---|---|---|---|---|
| OpenSSL before Heartbleed | high | low | low | weak |
| Tor | high | high | high | strong |
| Linux | very high | very high | high | strong |

The recurring pattern is not platform superiority. It is the combination of:
- funding
- expertise
- active review
- infrastructure maturity

---

## The Main insight

The strongest predictor of a project’s security outcome is not whether it is self-hosted or public. It is whether the project has enough resources and expertise to review, maintain, and respond to issues.
