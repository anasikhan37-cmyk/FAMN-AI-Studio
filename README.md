# FAMN AI STUDIO — Starter Prototype v0.1

This is a **front-end prototype**, not a production payment or AI video service.

## Included
- Register/login screen (demo only; browser localStorage)
- Creator dashboard and sample 100-credit display
- Voice-to-text prompt input when browser supports Web Speech API
- Save video ideas as demo projects
- Sample recharge request form
- Owner dashboard preview with demo approval flow

## Important limitations
- Do not enter real passwords or payment information.
- Authentication is NOT secure and is not connected to Firebase.
- Credits and approvals are stored only in this browser and can be changed by the user.
- No real UPI payment, transaction verification, AI API, video generation, or cloud storage is connected.
- Do not publish this prototype as a live paid service.

## Preview locally
Open `index.html` in Chrome. For microphone access, use localhost or HTTPS; direct file access may block microphone features.

## Next production steps
1. Create a separate GitHub repository for this project.
2. Connect Firebase Authentication and Firestore with server-enforced access rules.
3. Implement server-side credit ledger and one-time transaction reference checks.
4. Add a server-side payment verification workflow before crediting users.
5. Add AI provider integration behind a backend; never put secret API keys in browser code.
6. Add secure video storage, job queue, rate limits, cost limits, and abuse controls.
7. Test with an adult account owner / guardian and verify payment-provider eligibility before accepting money.
