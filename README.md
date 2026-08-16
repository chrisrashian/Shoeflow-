# ShoeFlow Complete

A user-friendly unified shoe business app plus server starter.

## Included
- Dashboard: revenue, profit, orders, low-stock alerts
- Catalogue: shoes, sizes, colours, stock, buying/selling price, photos
- Orders: customer, phone, payment, delivery status
- Customer history
- WhatsApp order handoff
- Printable invoices
- M-Pesa STK Push endpoint ready for Daraja Sandbox
- M-Pesa callback endpoint
- WhatsApp webhook endpoints
- Local JSON/browser data for the demo
- Secure `.env` configuration

## Run
Node.js 18+:
npm install
copy .env.example to .env
fill private Daraja values
npm start
Open http://localhost:3000

Do not put Consumer Secret, Passkey or access tokens in browser code or commit `.env`.
For real multi-device use, deploy over HTTPS and replace local storage with a secure cloud database.
