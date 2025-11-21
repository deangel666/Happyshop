# HappyShop v3 — E-Commerce Demo

Includes:
- Static frontend (HTML/CSS/JS)
- Shopping cart (LocalStorage)
- Node.js + Express server
- Stripe Checkout demo
- Firebase auth placeholder

## Setup

1. Install Node.js 14+
2. Run `npm install`
3. Set Stripe key:
   - macOS/Linux: `export STRIPE_SECRET_KEY=sk_test_xxx`
   - Windows: `setx STRIPE_SECRET_KEY "sk_test_xxx"`
4. Start server: `npm start`
5. Open http://localhost:4242

## Notes

- Cart stored in localStorage
- Stripe Checkout handles payments
- Firebase snippet available for registration/login
- Do not expose secret keys in client-side code
