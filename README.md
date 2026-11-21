# reviewpulse--sandbox

Smart Google Review Management, Local-Language Auto-Reply & QR Review Funnel SaaS for Indian Local Businesses

ReviewPulse is a mobile-first micro-SaaS web application built for commercial businesses across India—including Cafes & Restaurants, Medical Clinics & Pharmacies, Petrol Bunks, Coworking Spaces, and Retail / Commercial Buildings.

# Key Features

Supabase Authentication: Email/Password Sign-In, Sign-Up, Google OAuth flow, and an Instant Demo mode (owner@kovaicafe.in) for testing.

1. Business Setup: Configure Business Name, Category, City/Area (for local SEO keywords), Google Maps Review Link, Reply Tone (Warm, Professional, Short & Crisp), Default Local Language, and Auto-Post / Auto-Detect toggles.

2. AI Reply Generator & Local-Language Auto-Posting:

Automatically detects the reviewer's language (Tamil, Tanglish, Hindi, Malayalam, Kannada, Telugu, or English) and auto-posts tailored replies to Google Business Profile.

Generates 3 distinct, SEO-friendly reply options with 1-click Copy Reply and Post to Google actions.

Medical Clinic Privacy Guard: Strictly avoids mentioning or confirming any patient medical conditions, symptoms, or prescriptions in replies.

3. Smart QR Review Funnel:

Generates a downloadable PNG and printable counter QR standee poster.

4–5 Stars: Routes happy customers to the business's Google Maps Review Link.

1–3 Stars: Captures private feedback (Name, Phone, Issue) into the owner's Private Feedback Inbox for immediate resolution.

4. Billing & Plans (Razorpay Ready):

Free Plan (₹0/month): 10 AI replies/month + basic QR review page.

Pro Plan (₹499/month or ₹4,999/year): Unlimited AI replies, local SEO optimization, printable QR standees, and Razorpay checkout integration.

Public Verification Pages: Includes dedicated footer pages for Pricing, Privacy Policy (DPDP Act 2023 aligned), Terms & Conditions, and Refund Policy for Razorpay merchant onboarding.

# Quick Deploy to Vercel

Ensure index.html and vercel.json are in the root of your GitHub repository.

Go to Vercel, click Add New → Project, and import your repository.

Keep the default static settings (no build command required) and click Deploy.

Or deploy via Vercel CLI:
npx vercel --prod
