# SATNAMI SOCIAL starter

मोबाइल-फ्रेंडली frontend prototype.

## Demo features
- Feed, text post, image/video preview, likes, profile, chat UI, wallet UI, admin demo.
- Login केवल demo है; यह वास्तविक authentication नहीं है.
- Wallet ₹0 demo है; वास्तविक भुगतान/कमाई/withdrawal नहीं होता.

## Backend अभी जोड़ना बाकी
Firebase Authentication, Firestore, Storage, security rules, live chat, admin roles, server-side payment verification/webhooks, creator ledger, KYC/payout integration, Android packaging.

Razorpay secret key, Firebase service-account key, passwords या OTP कभी भी frontend या public GitHub repository में न रखें.

## GitHub Pages
Repository root में `index.html` रखें. GitHub Settings → Pages → Deploy from a branch → `main` → `/ (root)` → Save.
GitHub Pages static files host करता है; database और payment backend अलग service पर चाहिए.
