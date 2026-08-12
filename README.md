# StockFlow — Animated Inventory Website

A responsive, animated frontend demo for an Inventory + Live Stock + Live MRP + Orders + Billing product.

## Included
- Modern responsive landing page
- Animated hero dashboard
- KPI cards
- Sales chart
- Stock health donut
- Live product catalogue UI
- Search + category filter
- Add Product modal
- Login modal
- Demo booking modal
- Order pipeline
- Billing / demo invoice modal
- Dark / light mode
- Toast notifications
- Mobile responsive layout

## Run
Open `index.html` directly in a browser, or serve the folder with any static web server.

## Important for production
This is a frontend demo. The displayed data is mock data.

To make it truly live:
1. Obtain the required Marg ERP/API access from the client.
2. Build a secure backend integration layer.
3. Fetch products, MRP, stock, invoices/orders as permitted by the API.
4. Add authentication and role-based access.
5. Add database, logging, validation and error handling.
6. Connect payment gateway / GST invoice provider if required.
7. Never expose ERP/API credentials in browser JavaScript.

## Suggested stack for production
Frontend: Next.js / React
Backend: Node.js / Laravel
Database: PostgreSQL / MySQL
Hosting: VPS / managed cloud
Integration: Marg ERP/API through backend
