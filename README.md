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
git clone https://github.com/your-username/banking-bot.git
cd banking-bot
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

Live Demo : https://web-chat.global.assistant.watson.appdomain.cloud/preview.html?backgroundImageURL=https%3A%2F%2Fus-south.assistant.watson.cloud.ibm.com%2Fpublic%2Fimages%2Fupx-6df44c44-3073-4b94-b0fa-1ad943ff5bda%3A%3A7e6fa4d8-ad08-4410-ae6f-4919ddd02f14&integrationID=cf45dfb5-38cb-4d19-a138-8f7ec0de174d&region=us-south&serviceInstanceID=6df44c44-3073-4b94-b0fa-1ad943ff5bda

Connect to Whatsapp Sandbox
<img width="1487" height="676" alt="Screenshot 2025-08-01 013933" src="https://github.com/user-attachments/assets/9ac81680-0841-43d2-b66f-d4cad156d377" />


