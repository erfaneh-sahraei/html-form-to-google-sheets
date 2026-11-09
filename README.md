# HTML Form to Google Sheets Webhook Integration

A lightweight, simple project demonstrating how to capture data from a standard HTML form and instantly transmit it to a Google Sheet using a POST Webhook.

---

## 🚀 How It Works

1. **User Input:** The user fills out the simple HTML form (`index.html`) with their name, family name, email, and phone number.
2. **Webhook Trigger:** Upon submitting the form, the data is sent via the `POST` HTTP method directly to the Webhook URL (configured in the form's `action` attribute).
3. **Data Destination:** The workflow (e.g., n8n or server endpoint) intercepts the payload and automatically appends a new row to your Google Sheet.

---

## 📂 Project Structure
├── index.html            # فرم HTML تستی
├── sample-payload.json   # نمونه ساختار داده (JSON) ارسال‌شده
└── README.md             # مستندات پروژه

