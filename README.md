# Week4_Day1-Assignment_5 Unread Email Summaries

**n8n Assignment: AI-Powered Gmail Summarizer — Completed ✅**

Built an n8n workflow that automatically retrieves the latest 5 unread Gmail messages, uses an AI Agent to generate concise summaries, and sends all five summaries in **one consolidated email** with a formatted HTML table.

**Workflow:** Manual Trigger → Gmail (Get Many) → AI Agent + OpenAI Chat Model → JavaScript Code → Gmail (Send)

**Key features:**
- Fetches the 5 latest unread emails.
- Summarizes each email using its sender, subject, and preview.
- Includes the received date for each email.
- Uses JavaScript to parse AI output, clean the data, and generate an HTML table.
- Sends one consolidated email instead of five separate emails.

**Outcome:** Successfully tested end-to-end, with all five email summaries delivered in a single, readable email.

