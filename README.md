# n8n Automation Templates for Small Teams

Keywords: n8n workflow templates, n8n automation, lead capture automation, invoice reminder workflow, customer support triage, webhook to Slack, weekly metrics email, small business automation, import-ready n8n JSON.

## Free samples (2 workflows)
This repository contains **2 free, import-ready workflow templates** you can use today to verify quality and import behavior before buying the full pack.

- `lead_capture_and_auto-reply.json` — validates an incoming lead, then forwards it to your CRM webhook (CRM_WEBHOOK_URL).
- `webhook_to_slack_notifier.json` — receives a webhook payload and posts a formatted message to Slack (SLACK_WEBHOOK_URL).

Each uses only core n8n nodes. Import via Workflows → Import from File, configure 2 variables, and execute manually.>

## Full pack (Gumroad — €29)
The complete set of **11 production-ready workflows** (this free sample set plus 9 more: invoice reminder, support triage, daily standup, weekly metrics, webhook logger, customer feedback collector, out-of-office notice, social publisher, and Calendly booking logger) is available as a single download:
- Buy: https://flowcraftpro.gumroad.com/l/n8n-workflows

## 60-second import test (free sample)
1. Import `webhook_to_slack_notifier.json` into n8n.
2. Set `SLACK_WEBHOOK_URL` to a test endpoint (e.g., webhook.site).
3. Execute manually or POST:
   ```json
   { "message": "hello from n8n" }
   ```
4. Confirm the message arrives at your test endpoint.

## Methodology / scope notes
- All workflows use placeholder webhooks (`{{ $vars.X }}`); no credentials are included.
- `n8n_product/README.md` documents setup, required variables, and a 5-minute test.
- Support included: 30 days email + one free correction.
- Workflows are delivered inactive (`active=false`) by design; test before activating.

## Service (installation / handover)
Need it installed or configured? Open a **GitHub Issue** with the included template (button below) to request a scoped quote:
- Starter: €99 (1 workflow installed, 48h handover)
- Growth: €249 (3 workflows, 48h → 72h)
- Custom: from €499 (tailored integrations)

All scoped, fixed-price, no monthly retainer unless separately agreed.

## Request help or services
Open an issue using the "Service request" template in this repo. We reply within one business day.

## Contributing samples / feedback
- Open an issue titled `template request: <your automation>` with a detailed, non-sensitive problem description. We prioritize based on credible fit.
