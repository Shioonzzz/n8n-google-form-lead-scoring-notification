# n8n – Google Form Lead Automation & Scoring

Automated lead management workflow using n8n:
- Capture leads from Google Form via Webhook
- Data normalization & validation
- Lead scoring (Hot / Warm / Cold)
- Save to Google Sheets (CRM)
- Real-time Telegram notification based on priority

## 🔧 Tech Stack
- n8n
- JavaScript (Code Node)
- Google Sheets API
- Telegram Bot API

## 🧠 Workflow Overview
1. Webhook receives Google Form submission
2. Data cleanup (email, WhatsApp normalization)
3. Lead scoring logic
4. Save to CRM (Google Sheets)
5. Priority-based Telegram notification

## 🔥 Lead Scoring Rules
| Criteria | Score |
|--------|-------|
| Service Interest | 0–40 |
| Lead Source | 0–30 |
| Working Hours Bonus | 0–10 |

Category:
- 🔴 Hot (≥ 60)
- 🟡 Warm (40–59)
- 🔵 Cold (< 40)

## 🚀 How to Use
1. Import workflow JSON into n8n
2. Setup credentials (Google Sheets, Telegram)
3. Deploy webhook
4. Connect Google Form to webhook URL

## 📸 Screenshots
(see /screenshots)

## 📄 License
MIT
