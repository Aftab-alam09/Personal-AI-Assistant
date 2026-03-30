# Personal-AI-Assistant
🤖 AI Personal Assistant Automation (n8n)

An intelligent AI-powered personal assistant workflow built using n8n that automates daily tasks like email handling, expense tracking, scheduling, and reminders.

🚀 Features
📧 Email Automation
Send emails dynamically using AI
Draft & confirm before sending
💰 Expense Tracking
Capture expenses from natural language
Store data in Google Sheets
Categorize & structure entries
📊 Google Sheets Integration
Automatically append expense data
Maintain structured records
📅 Calendar Scheduling
Create events based on user input
Smart extraction of date, time, and title
⏰ Reminders & Notifications
Set reminders via chat
Receive alerts on time
💬 Conversational AI Interface
Integrated with Telegram
Polite, human-like assistant behavior
🧠 How It Works

This project uses an AI Agent architecture:

User sends a message via Telegram
AI Agent processes the intent
Based on the request, it selects the appropriate tool:
Gmail → Send email
Google Sheets → Store/read expenses
Calendar → Schedule events
Response is sent back to the user
🛠️ Tech Stack
⚙️ n8n (Core automation)
🤖 OpenAI (AI Agent / LLM)
📩 Gmail API
📊 Google Sheets API
📅 Google Calendar API
💬 Telegram Bot API
📸 Workflow Overview

Below is the workflow architecture:

⚡ Setup Instructions
1. Clone the Repository
git clone 
cd ai-personal-assistant-n8n
2. Setup n8n
Install n8n locally or use cloud
Import the workflow JSON file
3. Configure Credentials

Set up the following:

OpenAI API Key
Gmail OAuth
Google Sheets OAuth
Google Calendar OAuth
Telegram Bot Token
4. Activate Workflow
Turn on the workflow
Start interacting via Telegram
🧪 Example Commands
“Send email to Rahul about tomorrow’s meeting”
“I spent ₹500 on food today”
“Schedule a meeting at 5 PM tomorrow”
“Remind me to study at 8 PM”
🔥 Future Improvements
🧠 Add long-term memory (vector database)
📊 Advanced expense analytics dashboard
🔔 Smart notifications & summaries
🌐 Multi-platform support (WhatsApp, Web app)
🤝 Multi-agent system
🙌 Acknowledgements

Special thanks to Be10x for helping accelerate my learning in AI automation and workflow building.

📬 Connect With Me

If you found this project useful or want to collaborate:

LinkedIn: [Your Profile Link]
