# AI Automation — n8n Workflows

Hands-on n8n automation projects by **Youssef Wessam** (cybersecurity student, Alexandria University).
Each workflow is a practice project built to learn by building. Exports are in the `workflows/` folder.

| # | File | What it does | Status |
|---|------|--------------|--------|
| 1 | `01-sales-lead-routing.json` | Pulls products from a public API, merges them with sample leads, filters by budget (1,500+), and routes leads to US, EU or Asia teams. Low-budget leads follow a separate path. | Practice, sample data |
| 2 | `02-ai-chat-agent.json` | Chat assistant with the n8n AI Agent node, Google Gemini, and 30-message memory. | Practice (needs your Gemini credential) |
| 3 | `03-weather-chatbot.json` | Detects weather questions, calls Open-Meteo for Cairo, declines other topics. | In progress (reply still uses a fixed temperature) |
| 4 | `04-contact-form-intake.json` | Webhook that normalizes form fields, validates email and message, returns JSON success or a 400 error. | Built, ready to test |
| 5 | `05-morning-weather-brief.json` | Daily schedule that fetches the Alexandria forecast and writes a short brief. No API key needed. | Built, ready to test |
| 6 | `06-daily-tech-news-digest.json` | Reads a public tech RSS feed daily, keeps the top 5 stories, formats one digest message. | Built, ready to test |
| 7 | `07-social-post-approval-routing.json` | Approved posts are routed to LinkedIn or Instagram by platform; the rest go to a revision path. | Practice, sample data |
| 8 | `08-employees-to-google-sheets.json` | Appends sample employee records to a Google Sheet. | Practice (set your own sheet and credential) |

## How to import
1. In n8n create a new workflow.
2. Menu (⋯) → **Import from file** and choose a `.json` from `workflows/`.
3. Attach your own credentials where a node asks for them (Gemini, Google Sheets).
4. Click **Execute workflow** to test.

## Notes
- No API keys, credentials, personal sheet links or private webhook URLs are included.
- Sample data is used where noted; no client results are claimed.

## Contact
youssefwessam219@gmail.com · https://www.linkedin.com/in/youssef-wessam-584a90414/
