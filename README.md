# n8n-vapi-twilio-voice-agent
Advanced Inbound &amp; Outbound AI Voice Agent built on n8n using Vapi and Twilio. Features live call routing, automated data logging, and CRM synchronization.
# 📞 Automated AI Voice Agent Hub (n8n + Vapi + Twilio)

A cutting-edge, production-ready AI Voice Agent workflow orchestrated using **n8n**. This system integrates **Vapi** and **Twilio** to handle fully automated, human-like voice conversations for both **Inbound** customer support and **Outbound** sales calling, with instant data logging.

## 🚀 Key Features

- **Bidirectional Calling:** Fully supports **Inbound calling** (answering customer queries 24/7) and **Outbound calling** (triggering automated calls to new leads).
- **Vapi & Twilio Integration:** Leverages Vapi's ultra-low latency conversational AI engine with Twilio's powerful telecommunication infrastructure.
- **Automated CRM & Data Logging:** Instantly captures and parses customer data collected during the phone call (e.g., name, appointment dates, requirements).
- **Call Transcription & Recording Saved:** Automatically fetches the call recording link and full text transcript after the call ends, saving them directly into the database for quality control.

## 🛠️ Built With

- **n8n** (Webhook Handling & Core Automation Routing)
- **Vapi API** (Voice AI Agent & LLM Orchestration)
- **Twilio API** (VoIP & Phone Number Hosting)
- **Supabase / Airtable** (For saving customer profiles and call logs)

## 📦 How to Deploy This Workflow

1. **Import the JSON:** Download the `vapi-voice-agent.json` file from this repository and import it into your n8n workspace.
2. **Setup Vapi Assistant:** Create your AI assistant in the Vapi dashboard, configure its system prompt, and get your `Assistant ID`.
3. **Configure Webhooks:** Link the n8n webhook URL to Vapi's end-of-call or status-update hooks to instantly capture the call data and recording.
4. **Database Configuration:** Connect your preferred database node in n8n to log call summaries and lead data automatically.

---
*Developed by Ahmed Tamer - AI Automation Engineer*
