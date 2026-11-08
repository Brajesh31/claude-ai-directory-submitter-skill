# claude-ai-directory-submitter-skill

A Claude Code skill for preparing and submitting AI products, SaaS tools, MCP servers, and agents to relevant product directories.

## Overview

This skill organizes directory submissions into a controlled, one-at-a-time workflow. It helps prepare a factual product brief, select suitable directories, complete listing forms, track submission status, and avoid duplicate or inaccurate claims.

The quality of the listing depends on the accuracy of the product information. The skill should not invent customers, features, metrics, reviews, or launch details.

## Main Capabilities

- Prepare a reusable product brief.
- Identify suitable AI and software directories.
- Compare listing requirements and costs.
- Prepare concise product descriptions.
- Organize logos, screenshots, and product details.
- Submit to one directory at a time.
- Track pending, completed, rejected, and unavailable submissions.
- Record listing URLs and follow-up actions.
- Avoid duplicate submissions.

## Product Brief

Prepare a single verified brief containing:

- Product name and website.
- Short pitch and full description.
- Product category.
- Pricing model.
- Launch date where relevant.
- Logo and product screenshot.
- Founder or organization details when required.
- Contact information and public social links.

Review the brief before submitting it to any directory.

## Installation

```bash
git clone https://github.com/Brajesh31/claude-ai-directory-submitter-skill.git ~/.claude/skills/ai-directory-submitter
```

## Usage

Invoke the skill when listing or promoting a product:

```text
/ai-directory-submitter
```

Provide the product brief, target market, directory preferences, and any submission restrictions.

## Submission Workflow

1. Build and verify the product brief.
2. Review the directory list and current submission terms.
3. Confirm whether the listing is free or paid.
4. Check relevance and eligibility.
5. Submit one directory at a time.
6. Use only verified product facts.
7. Record the result and submission URL.
8. Follow up when required.
9. Update the status before moving to the next directory.

## Tracking Table

| Field | Purpose |
|---|---|
| Directory | Listing destination |
| Product | Product being submitted |
| Cost | Free or paid terms |
| Status | Not started, submitted, listed, rejected, or unavailable |
| Submission date | When the form was sent |
| Listing URL | Public listing when available |
| Notes | Follow-up or special requirements |

## Quality and Safety Checklist

- Product claims match the live product.
- Logo and screenshots are current.
- Pricing is accurate.
- Submission terms are checked.
- No false reviews or fabricated metrics are used.
- Contact details are approved for public use.
- Paid upgrades require explicit user approval.
- Submission status is recorded accurately.

## Repository Contents

- `SKILL.md`: Main directory submission workflow.
- `README.md`: Product brief, process, and tracking guidance.

## Practical Principle

Directory quantity is not a growth strategy by itself. Prioritize relevant directories with real audiences and track whether listings produce qualified traffic or signups.


## Supporting Resources

| File | Purpose |
|---|---|
| [Product submission brief](resources/product-submission-brief-template.md) | Store approved and verified product facts and public assets once. |
| [Directory submission tracker](resources/directory-submission-tracker.csv) | Track each directory, fee/login requirements, status, and listing URL. |
| [Submission compliance checklist](resources/submission-compliance-checklist.md) | Verify eligibility, claims, terms, costs, and approval gates before submitting. |

## Data freshness and submission safeguards

Directory availability, free/paid status, submission requirements, catalog counts, and pricing change. The upstream SKILL.md still contains an older statement of 307 directories, 123 free listings, and a $24 spreadsheet. FalcoScan's page checked on 7 November 2026 instead reported 391 directories, 167 free listings, and a $2.99 spreadsheet. Treat the SKILL.md figures as stale, refresh FalcoScan and each directory's own submission page before quoting figures or submitting: https://falcoscan.com/browse/directories. Do not create accounts, pay, accept terms, bypass CAPTCHA, or add a backlink/badge without explicit user approval. Never invent product claims, customer counts, reviews, or metrics.

## License

The root [MIT License](LICENSE) applies to original repository material. Preserve the source and terms of any directory data obtained from third parties.
