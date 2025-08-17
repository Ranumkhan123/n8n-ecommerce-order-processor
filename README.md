## The E-commerce Order Processor – n8n Workflow

This project demonstrates an **automated e-commerce order processing workflow** built with **n8n**.  
It shows how customer orders are received, validated, processed, and updated in real-time.

---

##  Features
- **Order Capture** – Collect customer order details (name, email, items, payment).
- **Validation** – Ensure required fields are present before processing.
- **Inventory Update** – Simulate stock update after order confirmation.
- **Email Notification** – Send confirmation email to the customer.
- **Error Handling** – Basic error checks with fallback messaging.

---

##  Repository Contents
- `workflow/` → Contains the n8n workflow JSON file (`n8n-ecommerce-order-processor workflow.json`).
- `demo-video/` → Contains a short demo video walkthrough.
- `docs/screenshots/` → Screenshots for visual understanding.

---

## Demo Video

Watch the workflow in action:

[![Watch the demo](https://img.youtube.com/vi/J059XvgT1jg/0.jpg)](https://youtu.be/J059XvgT1jg)


---

## Workflow Diagram

Here’s how the workflow is structured in n8n:

![Workflow Overview](docs/screenshots/workflow-overview.png)

---

##  How to Use
1. Clone this repository.
2. Import the workflow (`.json`) into your n8n instance.
3. Configure credentials (SMTP for emails, API keys if needed).
4. Run the workflow in **test mode** or trigger via webhook.

---

##  Notes
- Replace placeholder credentials with your own (e.g., `{{YOUR_API_KEY}}`, `{{SMTP_HOST}}`).
- You can extend this workflow by connecting it with real e-commerce APIs (Shopify, WooCommerce, etc.).

---

## Author
**Ranum Khan**  
[LinkedIn](https://www.linkedin.com/in/ranum-khan-qaengineer) | [GitHub](https://github.com/Ranumkhan123)
