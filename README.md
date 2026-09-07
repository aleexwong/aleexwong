# Alex Wong — Full-Stack Developer / SDET

I build and ship production web apps end to end: React and TypeScript on the front, Node and serverless APIs on the back, with automated tests and CI so releases stay safe.

Vancouver, BC 🇨🇦 · [LinkedIn](https://linkedin.com/in/aleexwong) · [GitHub](https://github.com/aleexwong)

---

## What I Ship

### TrainPace — training platform for runners
**Live:** [trainpace.com](https://www.trainpace.com) · React 18, TypeScript, Vite, Tailwind, Firebase, Vercel

A real product with real users, not a demo. I designed and built the whole stack.

- Pace, VDOT and training-plan calculators with a shareable, saveable dashboard
- GPX course analysis: elevation profiles, grade-adjusted pace, race-course comparison
- AI race-fuel planner built on the Google Gemini API
- Metered, cached Mapbox layer that keeps map costs predictable under load
- Firebase Auth and Firestore, with a localStorage path so guests can use every tool
- 80+ prerendered SEO pages plus Markdown mirrors so AI agents can read the site
- Playwright end-to-end suite running in GitHub Actions on every push and PR

### Burnerate — subscription expense tracker
**Live:** [burnerate.com](https://burnerate.com) · Next.js App Router, TypeScript, Firebase, Stripe, OpenAI

A PWA that turns messy recurring spending into one clear number.

- Upload a bank CSV and GPT-4o-mini detects your subscriptions, with a pattern-matching fallback when no API key is set
- Natural-language input ("Netflix 20 a month") parsed into structured data
- Stripe one-time checkout that unlocks a public profile page at `/u/<username>`; the webhook claims the handle, so nobody can reserve a name for free
- Monthly snapshots written only by the Admin SDK, with Firestore rules blocking client writes
- Free regional cost calculators (US/CA/AU/UK) and a no-account try mode
- Sentry, PostHog funnel events, dark mode, Playwright smoke tests

### TriggerMap — product case study
21 days of manual UX observation mapping how a consumer app drives engagement. No scraping, just systems thinking applied to product design.
[Read the case study](https://shrub-shift-a82.notion.site/TriggerMap-UberEats-21-Days-213ec0fe600280c1bb91e4fbc1058dfb)

---

## Strengths

- **Product sense.** I pick the feature that helps the user, then cut the scope that does not.
- **Testing as a habit.** Playwright suites in CI, page-object models, and QA experience from the other side of the fence.
- **Cost and performance awareness.** Request budgets, caching layers, and prerendering because bills and Core Web Vitals are real constraints.
- **Security on money paths.** Server-side validation of payments, usernames and database rules — never trusting the client.
- **Clear code.** Typed, feature-scoped modules and docs that let the next person move fast.

---

## Stack

**Languages** TypeScript · JavaScript · Python · Java · SQL  
**Frontend** React 18 · Next.js · Vite · Tailwind · shadcn/ui · React Hook Form + Zod  
**Backend** Node.js · Express · Next.js Server Actions · Firebase Auth/Firestore · MongoDB · MySQL  
**AI** Google Gemini · OpenAI (Vercel AI SDK) · MCP  
**Testing** Playwright · WebdriverIO · Appium · GitHub Actions  
**Platform** Vercel · Docker · AWS · Stripe · Sentry · PostHog

---

## Now

Building AI race prediction and coaching agents for TrainPace on MCP + Firebase.

**Open to full-stack and SDET roles.** Reach me on [LinkedIn](https://linkedin.com/in/aleexwong).
