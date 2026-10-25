# Quickstart Guide: Importing and Safely Running n8n Templates

## Common errors (and fixes)
1. Webhook returns 404
   - Cause: path typo or inactive workflow.
   - Fix: activate workflow and confirm `path` is exact (e.g. `lead-capture`).

2. Variables undefined (`{{ $vars.X }}` is empty)
   - Cause: variable not created in n8n Settings → Variables.
   - Fix: create variable exactly `CRM_WEBHOOK_URL`, `SLACK_WEBHOOK_URL`, etc.

3. HTTP request fails
   - Cause: destination webhook invalid or blocked.
   - Fix: test with webhook.site; whitelist n8n Cloud IPs if needed.

4. Cron not firing
   - Cause: inactive workflow or wrong timezone.
   - Fix: activate and verify server timezone + expressions (`0 9 * * 1-5`).

## Variables used by this pack
- Lead/Sales: CRM_WEBHOOK_URL
- Email: EMAIL_WEBHOOK_URL, CLIENT_EMAIL, TEAM_EMAIL, REPORT_RECIPIENT
- Chat: SLACK_WEBHOOK_URL, TICKET_WEBHOOK_URL
- Publishing: PUBLISH_WEBHOOK_URL, LOG_WEBHOOK_URL, FEEDBACK_WEBHOOK_URL, CALENDAR_WEBHOOK_URL

## Support
Open a GitHub issue with "template request: ..." for new automations or "help" for scoped setup quotes (EUR 99 / 249 / 499+).
