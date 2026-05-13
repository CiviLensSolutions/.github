# CiviLens Solutions — Claude Code Conventions

## Organization

- **GitHub Org:** CiviLensSolutions (github.com/CiviLensSolutions)
- **Slack:** civilens.slack.com
- **Business address:** 608 E Hickory Street, Suite 128, Denton, TX 76205 (coworking space)
- **Home address:** 616 E Hickory Street, APT 102, Denton, TX 76205

## Business Context

Veteran-owned technology company, Denton TX. Founder (Shea Scott) is a 70% service-connected disabled veteran.

- 100% veteran-owned at formation, single-member LLC
- Founder retains minimum 51% permanently — required for SDVOSB and Texas HUB eligibility
- Active certifications in progress: Texas HUB, federal SDVOSB (SBA)
- Early strategy: subcontract under federal primes to build past performance

## SSH & Git

All CiviLens repo remotes use the `github.com-sheadscott` SSH alias:

```
git@github.com-sheadscott:CiviLensSolutions/<repo>.git
```

Do NOT suggest changing SSH config or using `git@github.com:` — the default `github.com` host maps to a separate work account.

## Task Management

- Primary: GitHub Issues on the relevant repo
- Fallback: create `tasks/<slug>.md` locally if GitHub is unavailable, sync to Issues when back online
- Use `gh issue create --repo CiviLensSolutions/<repo>` to create issues

## Daily Journal

Each contributor maintains their own journal:

```
journal/{gh-username}/YYYY/MM/YYYYMMDD-journal.md
```

- Create an entry for any session where work is done in the repo
- Skip days with no work
- Summarize topics discussed and decisions made

## Ownership & Structure

- Do not suggest multi-member or multi-partner processes — single-member LLC until explicitly restructured
- Any restructuring must keep founder above 51% to preserve certifications
