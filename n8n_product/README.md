# n8n Workflow Templates Pack

11 ready-to-import n8n workflows for small businesses and solopreneurs.

## What's included
1. Lead Capture & Auto-Reply
2. Invoice Payment Reminder
3. Customer Support Triage
4. Daily Standup Digest
5. Social Post Publisher
6. Webhook to Slack Notifier
7. Weekly Metrics Email
8. Webhook Row Logger
9. Customer Feedback Collector
10. Out-of-Office Auto Notice
11. Calendly Booking Logger

## How to import
1. In n8n: Workflows → Import from File → select a .json
2. Set your environment variables in n8n (Settings → Variables) or replace `{{ $vars.X }}` with values:
   - CRM_WEBHOOK_URL, CLIENT_EMAIL, EMAIL_WEBHOOK_URL, SLACK_WEBHOOK_URL, TICKET_WEBHOOK_URL, PUBLISH_WEBHOOK_URL
3. Adjust cron schedules and paths to your needs
4. Test with n8n's "Execute" before activating

## Validation
All JSON files were successfully imported into n8n (self-hosted, latest) via `n8n import:workflow`. They use only core nodes that ship with n8n.

## License
Use for your own or client projects. Do not resell unmodified JSON as-is. Support included for 30 days via email.
EOF