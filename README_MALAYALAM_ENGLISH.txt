SURYA ASSOCIATES — FULL ANIMATED WEBSITE PACKAGE

IMPORTANT: Open index.html directly (double-click) to preview the FULL design.
The index.html is self-contained: CSS, animations, JavaScript and all 176 catalogue products are embedded. It does not need CMD, Python, localhost or an internet connection for the main website/catalogue (Google Fonts are optional; system fonts are used as fallback).

WHAT IS INCLUDED
- Full-screen animated solar sunrise hero: glowing sun, orbit rings, rays, stars, moving energy line and solar panel array.
- Welcome to Shop Assistant / Welcome to Surya Associates / Your Energy Power Solution.
- Responsive Home, About, Products, AI Assistant, Contact.
- 176 product catalogue items across 8 categories, search, filters, sort.
- Cart, quantity controls, estimated total, WhatsApp enquiry.
- Admin / API panel for shop contact details and API test.
- Cloudflare Pages server-side AI function in functions/api/chat.js.
- data/products.json copy for editing catalogue data.

HOW TO PREVIEW
1. Extract the ZIP.
2. Open the extracted folder.
3. Double-click index.html.
4. It opens in Chrome or your default browser. Scroll down to see all sections.
5. Click Admin / API to enter shop phone/address and view AI API setup.
No CMD needed for local visual preview.

AI/API LIMITATION
The AI chat works in local catalogue fallback mode when index.html is opened directly. A secure AI API call needs the Cloudflare Pages Function to be deployed and the secret OPENAI_API_KEY set in Cloudflare Pages → Settings → Variables and Secrets. Never put the API key inside index.html or app.js. Set optional OPENAI_MODEL (default gpt-4.1-mini). API provider usage can be chargeable; this is not guaranteed free/unlimited.

CLOUDFLARE DEPLOY
Deploy this folder as a Cloudflare Pages project with Functions enabled (Git integration or Wrangler). Keep functions/api/chat.js in place. Add OPENAI_API_KEY as a secret, optionally OPENAI_MODEL as a variable, then redeploy. The resulting *.pages.dev address is accessible publicly. Cloudflare Free plan quotas/features can change; check current Cloudflare terms. The AI provider may charge separately.

CATALOGUE NOTICE
The catalogue data is carried forward from the earlier Shop Assist package. Verify all model names, prices, stock quantities, warranty and product details with the shop before publishing or accepting orders. Values are not live inventory.

This is the website application package, not Raspberry Pi GPIO/servo hardware code.
