# n8n Automation Templates for Small Teams

11 tested, import-ready n8n workflows built only from core nodes so they run without external credential setup.

Included:
- Lead Capture & Auto-Reply
- Invoice Payment Reminder
- Customer Support Triage
- Daily Standup Digest
- Social Post Publisher
- Webhook to Slack Notifier
- Weekly Metrics Email
- Webhook Row Logger
- Customer Feedback Collector
- Out-of-Office Auto Notice
- Calendly Booking Logger

Buy: https://flowcraftpro.gumroad.com/l/n8n-workflows

Import each `.json` via n8n (Workflows -> Import from File), then set the environment variables listed in `n8n_product/README.md` or replace `{{ $vars.X }}` placeholders.

Checksums: `CHECKSUMS.txt`

## Free samples vs. paid outcome

The workflow JSONs in this repository are free samples you can import to see the quality of implementation.

- **Free (this repo):** 11 importable workflows, test scripts, docs.
- **Paid (done-for-you):** scoped install, configuration, handover video, tests on your real webhook, and 30-day support.

The same templates are also available under a free download from the Gumroad listing; what you pay for is support + install certainty, not the JSON files themselves.

## Request help or install service

Need it installed/configured? Open a GitHub Issue with the included template; reply within one business day with a scoped quote (€99 starter, €249 growth, custom from €499).

---

## Feedback wanted

11 tested n8n workflows here (core nodes only). Would these save you time? Open an Issue titled 'template request: <your automation>' with the problem you are solving, and I'll prioritize a battle-tested version.

Beta / questions / custom build: open an issue in this repo.

This README acts as the public demand log; purchase link: https://flowcraftpro.gumroad.com/l/n8n-workflows

## Quick start (60 seconds)

1. Open n8n -> Workflows -> Import from File -> pick any JSON, e.g. customer_support_triage.json.
2. Set env vars in n8n (or replace the {{ $vars.X }} placeholders) for at least one target webhook. A https://webhook.site/ URL works for a dry run.
3. Click Execute Workflow, confirm the expected payload, then activate.

## Need it installed for you?

Open an Issue titled `help wanted: <workflow or endpoint>` with a short description of your current setup, and I'll reply with a scoped installation quote (€99 starter, €249 growth pack, custom from €499). All quotes are scoped and fixed-price. The 11 workflows above are the proof-of-work, not the whole offering.
