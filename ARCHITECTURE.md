# Workflow Architecture

## Input
- Google Form → Webhook (POST)

## Processing
- Field normalization (email, WhatsApp)
- Validation (IF node)
- Lead scoring (Code Node – JavaScript)

## Output
- Google Sheets (CRM)
- Telegram notification:
  - Hot Lead → Urgent alert
  - Warm/Cold → Regular follow-up

## Error Handling
- Validation check before processing
- Default values for missing fields
