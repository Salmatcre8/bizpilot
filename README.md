## 🚀 BizPilot


An intelligent, zero-friction business operating system for social commerce merchants in Africa.
BizPilot turns unstructured WhatsApp conversations and OPay transaction alerts into a fully automated backend system eliminating manual bookkeeping and enabling real-time business intelligence for micro-retailers.


---

## 📌 Problem



Millions of micro and small businesses in Africa run entirely on WhatsApp.


But this creates critical challenges:

•Orders are buried in chat threads.

•Inventory is tracked manually (or not at all)

•Payments are verified by hand across banking apps

•Revenue tracking is inconsistent or nonexistent

•No structured data → no access to credit or scaling tools


Result: Business owners spend more time managing chaos than selling.



---

## 💡 Solution


BizPilot is an invisible AI-powered business layer that sits on top of WhatsApp commerce workflows.


It automatically:

•Extracts structured order data from chat messages

•Updates inventory in real time

•Tracks payment confirmation via OPay webhooks

•Maintains a live financial ledger

•Generates business insights from raw transactions


No new app behavior required.
No workflow disruption.
Just intelligence added to what already exists.


---

## ⚙️ How It Works



1.Order Capture (WhatsApp → AI Parsing)


Customer messages are ingested and processed using Google Gemini 1.5 Flash, which converts unstructured text (including Pidgin English and informal phrasing)


2.Backend Processing (Database Sync)


Structured data is stored in Supabase (PostgreSQL):

•Inventory is automatically decremented

•Order status is set to Awaiting Payment Confirmation

•Transaction logs are created for auditability




3.Payment Reconciliation (OPay Webhooks)

BizPilot listens for real-time OPay instant transfer webhooks:


•Matches incoming payments to pending orders

•Automatically verifies transaction amounts

•Updates order status to Settled

•Finalizes ledger entry




4.Business Intelligence Layer (Dashboard)

A clean React-based dashboard gives merchants:

•Live inventory tracking

•Daily/weekly revenue analytics

•Order history management

•Exportable financial records for credit access


---

## 🧠 Key Features


•🧾 AI-powered WhatsApp order parsing

•📦 Automated inventory management

•💳 Real-time payment reconciliation (OPay integration)

•📊 Financial ledger + analytics dashboard

•🔄 End-to-end order lifecycle automation

•🧠 Multilingual + Pidgin language support


---

## 🏗️ Tech Stack


•Frontend: React

•Backend: Node.js / Serverless functions

•Database: Supabase (PostgreSQL)

•AI Engine: Google Gemini 1.5 Flash

•Payments: OPay Webhooks API

•Architecture: Event-driven, real-time sync system

---

## 🔄 System Flow


WhatsApp Message

      ⬇️
      
Gemini AI Parser

      ⬇️
Structured JSON Order

      ⬇️
Supabase DB Update

      ⬇️
Inventory Deduction + Order Created

      ⬇️
OPay Webhook Payment Match

      ⬇️
Order Marked as Settled

      ⬇️
Dashboard Analytics Updated


---

## 📈 Impact


BizPilot transforms informal social commerce into structured digital businesses.

It enables:

•Faster order processing

•Zero manual bookkeeping

•Accurate inventory tracking

•Real-time revenue visibility

•Financial identity creation for micro-merchants


Ultimately, this unlocks access to credit, scaling tools, and formal financial systems for informal retailers.

---

## 🚀 Why It Matters


In markets like Nigeria, WhatsApp is the storefront—but not the backend.

BizPilot bridges that gap by turning conversations into infrastructure.

---

## 🤝 Future Roadmap


•WhatsApp Business API integration (official channel)

•Fraud detection for payments

•Credit scoring engine for merchants

•Multi-agent AI assistant for business insights

•Offline-first support for low connectivity regions



---


📩 Built For

•Hackathons focused on fintech, AI, or African innovation

•Social commerce merchants

•WhatsApp-first economies

•Financial inclusion infrastructure






