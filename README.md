# MacroSnap 🥗

MacroSnap is an AI-powered nutrition assistant that estimates calories and macronutrients from meal photos or text descriptions.

## Features

- Analyze meal photos using AI
- Describe meals using text
- Estimate calories
- Estimate protein, carbohydrates, and fat
- Chat with the AI about food and nutrition
- WhatsApp summary support through Twilio

## Requirements

- Python 3
- Google Gemini API key
- Twilio account for WhatsApp functionality

## Installation

Clone the repository:

```bash
git clone https://github.com/subhankarpradhan53-sudo/macrosnap.git
cd macrosnap

Create and activate a virtual environment:
python -m venv venv

Windows:
venv\Scripts\activate

Install the required packages:
pip install -r requirements.txt

Configuration
Create the file:
.streamlit/secrets.toml

Add your own API credentials:
GEMINI_API_KEY = "your-gemini-api-key-here"

TWILIO_ACCOUNT_SID = "your-twilio-account-sid-here"
TWILIO_AUTH_TOKEN = "your-twilio-auth-token-here"

TWILIO_WHATSAPP_FROM = "whatsapp:+14155238886"

TWILIO_CONTENT_SID = "your-content-template-sid-here"

Never share your real API keys or authentication tokens publicly.
Run the Application
Start MacroSnap with:
streamlit run app.py

Then open the local Streamlit URL shown in the terminal.
How to Use
1. Enter your name and WhatsApp number.
2. Upload a photo of your meal or describe your meal using text.
3. MacroSnap analyzes the meal using Gemini.
4. The application provides estimated calories and macronutrients.
5. You can continue chatting with MacroSnap about your meals.
Project Structure
macrosnap/
├── app.py
├── prompts.py
├── requirements.txt
├── .gitignore
└── .streamlit/
    └── secrets.toml

## Note
Nutrition values provided by MacroSnap are estimates and may vary depending on ingredients, portion sizes, and preparation methods.



