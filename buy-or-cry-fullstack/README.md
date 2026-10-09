# BUY OR CRY — Full-stack 90s Disaster

Requires Node.js 18+. No npm install or third-party dependencies needed.

```bash
npm start
```

Open http://localhost:3000

Features: 60 products, server-side product search and categories, persisted visitor count, public parody reviews, cart saved in browser localStorage, server-validated fake checkout and order history in local JSON files, retro visual chaos buttons, meme sound effects, timer, popups, responsive design, reduced-motion support.

API: GET /api/products?q=&category=, GET /api/stats, POST /api/visit, GET/POST /api/reviews, POST /api/checkout.

**Important:** No real checkout, payment, or shipping. All prices and reviews are fictional/parody. JSON persistence is a local demo, not a production database; add authentication, rate limiting, moderation, and a database before public deployment. Do not collect real customer data in this demo.
