# Sweet Security CI Research Workflow

A competitive intelligence research workflow I built in Claude, working as if I were a product marketing manager at Sweet Security, tracking Upwind.

## What it does

- **Source registries:** a list of public sources per company (website, LinkedIn, Wayback Machine, Google Ads Transparency, AWS and GCP marketplaces, review sites).
- **Scheduled research:**
  - **Weekly:** LinkedIn post analysis.
  - **Monthly:** the main research run (about 80% of the work).
  - **Quarterly:** messaging changes, Wayback Machine comparisons, a refreshed brief and battle card.
- **Output:** each report is a Google Doc. Every finding is tagged with the Master CI Brief row it belongs in, so updating the brief is quick.

## How it works

- **Evidence rules:** public sources only; every finding labelled FACT, INTERPRETATION or HYPOTHESIS; "No evidence found" instead of guessing.
- **Manual research:** sites Claude can't open (LinkedIn, G2, Wayback Machine) are flagged in a "Manual research needed" list.
- **Tools:** Claude Pro, Claude Projects, scheduled tasks, skills and the Google Drive and Sheets connectors. $0 extra spend, 2–3 hours a week.

## What's in this repo

| Folder | What it is |
|---|---|
| `skills/ci-research-workflow` | Skill for running the full research workflow for any company |

## Related

The intel feeds my CI battle card interface: [link to the battle card repo]

## About me

[Your name] · [LinkedIn link] · [Portfolio link]
