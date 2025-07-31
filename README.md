# 💬 IBM Watson Banking Bot with WhatsApp Integration

A smart conversational banking assistant built with IBM Watson Assistant and deployed using Twilio WhatsApp Sandbox.

## 🔧 Tech Stack
- IBM Watson Assistant
- IBM Cloud
- Twilio WhatsApp Sandbox
- Python (Flask or FastAPI)
- Webhook integration

## 🎯 Features
- Keyword-based initiation (type "banking")
- Personalized greeting with user name
- Menu-driven flow for:
  - 🏡 Home Loans
  - 💸 Personal Loans
  - 💳 Credit Card Services
  - 🏧 Debit Card Services
- Follow-up questions for selected service
- Seamless interaction via WhatsApp

## 📦 Project Structure

- `banking-bot-skill.json`: Exported Watson Assistant dialog skill
- `twilio/`: WhatsApp webhook setup and integration
- `images/`: Screenshots or chat flow demo
- `demo/`: Optional screen recording demo of bot in action

## 🚀 How to Run

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/ibm-banking-bot.git
cd ibm-banking-bot
```
2. Set Up Watson Assistant
Go to IBM Watson Assistant.

Create a new assistant and import banking-bot-skill.json.

3. Set Up Twilio WhatsApp Sandbox
Create a Twilio account.

Set up a WhatsApp Sandbox and configure the webhook.

Link the sandbox number with the webhook URL.

4. Run Webhook (Example using Flask)
bash
Copy code
cd twilio
pip install -r requirements.txt
python webhook.py
5. Test the Bot
Open WhatsApp.

Send banking to your Twilio sandbox number.

Follow the bot instructions.
