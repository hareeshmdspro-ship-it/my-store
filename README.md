# Fresh Basket – Mobile Store App (Next.js PWA)

A mobile-first store app built with Next.js. It installs on a phone like a native app (PWA), has product search, categories, a cart, and sends orders to your WhatsApp. No backend or database is needed, so it costs nothing to host.

## 1. Customise your store

Open `app/config.js` and change:
- `name`, `tagline`, `themeColor`
- `whatsapp` – your number with country code, digits only (e.g. `919876543210`)
- `PRODUCTS` – your items, prices and emojis

## 2. Run it on your computer

```bash
npm install
npm run dev
```
Open http://localhost:3000

## 3. Host it for free (Vercel)

1. Create a free account at https://github.com and make a new repository.
2. Upload this project (or run `git init && git add . && git commit -m "first" && git push`).
3. Go to https://vercel.com, sign in with GitHub, click **Add New → Project**, pick the repository and click **Deploy**.
4. In about a minute you get a free live link like `https://your-store.vercel.app`. Every time you push changes to GitHub, the site updates automatically.

Other free options: Netlify, Cloudflare Pages (all work with Next.js and have free plans).

## 4. Install it on a phone

- **Android (Chrome):** open your link → menu (⋮) → **Install app** / **Add to Home screen**.
- **iPhone (Safari):** open your link → Share → **Add to Home Screen**.

## 5. Next steps (still free)

- Own domain: buy one (~₹700/year) and connect it in Vercel → Settings → Domains.
- Real product database / admin panel: Supabase or Firebase free tiers.
- Online payments: Razorpay (no monthly fee, a per-transaction charge applies).
- Google Play Store: wrap the site with Bubblewrap/PWABuilder (one-time $25 Google fee).
