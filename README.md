# ✈️ Flight Deal Notifier

A tool that helps users track the best flight deals from their origin city to multiple destinations. It checks for cheaper flights using the Tequila Kiwi API and sends email or SMS notifications when a great deal is found.


## 📌 Features

- Automatically scans for the cheapest flight deals from your origin (e.g., Gujarat, India).
- Notifies users via email or SMS if a flight price drops below a predefined threshold.
- Integrates with Google Sheets to manage destination data and price thresholds.
- Environment variables used for secure API key and user configuration.


## 🔧 Tech Stack

| Layer         | Technology          |
|---------------|---------------------|
| Programming   | Python 3.10+        |
| APIs          | [Tequila Kiwi API](https://tequila.kiwi.com/), [Sheety API](https://sheety.co/) |
| Notifications | SMTP (email), [Twilio](https://www.twilio.com/) (SMS - optional) |
| Data Format   | JSON, Google Sheets |


## ⚙️ Configuration

Create a `.env` file in the project root:


## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/flight-deal-notifier.git
   cd flight-deal-notifier
