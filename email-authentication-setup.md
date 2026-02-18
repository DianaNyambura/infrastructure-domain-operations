# Case Study 3: Google Workspace Email Configuration & Authentication

## Objective
Configure domain email with proper authentication to prevent spam classification.

## Environment
- Google Workspace
- Domain DNS managed via registrar
- SMTP relay configuration

## Implementation Steps

1. Added Google Workspace MX records.
2. Configured SPF record
3. Generated and added DKIM TXT record.
4. Implemented DMARC policy:
   v=DMARC1; p=none; rua=mailto:info@admin.com
5. Verified DNS propagation.

## Validation

- Sent test emails to Gmail and Outlook.
- Confirmed SPF, DKIM, and DMARC pass status.
- Checked email header authentication results.

## Outcome

Email deliverability improved and domain reputation protected through proper authentication setup.
