# HTML Form to Google Sheets Webhook Integration

A lightweight, professional project demonstrating how to capture data from a standard HTML form and instantly transmit it to a Google Sheet using a POST Webhook (via n8n).

---

## 🚀 How It Works

1. **User Input:** The user fills out the simple HTML form (`index.html`) with their details (Name, Family, Email, Phone).
2. **Webhook Trigger:** Upon submitting the form, the data is packaged and sent via the `POST` HTTP method directly to the Webhook URL.
3. **Data Destination:** The automation workflow intercepts the payload and automatically appends a new row to your Google Sheet.

---

## 📂 Project Structure
```text
├── index.html                    # Simple HTML test form
├── HTML Form to Google Sheets.json # n8n workflow export file
└── README.md                     # Project documentation
