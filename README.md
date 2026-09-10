# AR.com Full Platform
Premium React/Vite LMS foundation with course catalog, student dashboard, AI tutor UI, admin UI, Supabase schema, Razorpay-ready server endpoints, certificate/progress models and deployment docs.

## Run
cd app
npm install
npm run dev

## Deploy
Deploy `app` to Vercel. Build: `npm run build`; output: `dist`.

## Production integrations
Set environment variables from `.env.example`. Use Supabase for auth/database, Razorpay for payments, Mux/Cloudflare Stream/Vimeo for signed video, and an OpenAI-compatible server endpoint for the AI tutor. Never expose secret keys in VITE_ variables.

Payment signature verification, webhooks, auth policies, rate limiting and secure video signing must be completed before accepting real money or private student data.
