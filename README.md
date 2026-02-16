# Goke Motor Services — Car Buying Service Website

## What This Is
A single-page landing site for **Goke Motor Services**, a car buying service that helps people purchase vehicles at wholesale pricing through dealer-only auctions.

## Files
```
goke-motor-services/
├── index.html       ← Main landing page (all CSS/JS inline)
├── success.html     ← Thank-you page after form submission
├── privacy.html     ← Privacy policy
├── terms.html       ← Terms of service
├── 404.html         ← Custom 404 error page
└── README.md        ← You're reading it
```

## What's Built

### Core Sections (index.html)
- **Hero** — headline, subtext, dual CTA buttons
- **Value Propositions** — Wholesale Pricing, Licensed Dealer, Wide Selection
- **Stats Bar** — animated counters (150+ cars, 120+ customers, $3,400 avg savings)
- **How It Works** — 4-step card grid
- **Pricing** — 3 tiers ($500 / $750 / $1,000) with "Most Popular" badge
- **Comparison Table** — Dealership vs. Goke Motor Services (8 rows)
- **Process Timeline** — 8-step vertical timeline from form to front door
- **Guarantees** — refund, inspection, auction warranty, no hidden fees
- **Testimonials** — 3 customer reviews with star ratings and avatar initials
- **About / Founder** — photo placeholder + personal story from Goke
- **Gallery** — 6 polished cards (4 image + 2 video) with "Coming Soon" overlays, ready for real media
- **Lead Capture Form** — Netlify Forms with honeypot spam protection
- **CTA Banner** — "Ready to Save Thousands?" with gradient background
- **Payment Section** — Zelle (copy-to-clipboard) + PayPal (direct link)
- **FAQ** — 6-question accordion (legal, timeline, refund, financing, viewing, service area)

### Mobile Features
- Hamburger nav menu (auto-closes on link click)
- Floating bottom CTA bar ("Get Started — Find Your Car")
- SMS/text floating button (bottom right)
- Back-to-top button (appears after scrolling past hero)
- Phone number in nav and mobile menu

### SEO & Technical
- Open Graph + Twitter Card meta tags
- LocalBusiness JSON-LD structured data
- Favicon (blue rounded square with "G")
- Google Analytics placeholder (commented out, ready to activate)
- Responsive design — fully mobile-optimized

### Additional Pages
- **success.html** — thank-you page after form submission with next steps
- **privacy.html** — privacy policy (data collection, no selling data, Netlify hosting)
- **terms.html** — terms of service (service fees, refund policy, warranty, liability)
- **404.html** — custom error page matching site theme

## Deployment on Netlify (Free)

### Option A: Drag & Drop (Fastest)
1. Go to [https://app.netlify.com/drop](https://app.netlify.com/drop)
2. Drag the entire `goke-motor-services` folder onto the page
3. Done! You'll get a live URL like `https://random-name.netlify.app`

### Option B: Via Claude Code / CLI
```bash
# Install Netlify CLI
npm install -g netlify-cli

# From inside this project folder:
cd goke-motor-services

# Deploy (will prompt you to log in first time)
netlify deploy --prod --dir .
```

### Option C: Connect to GitHub (Auto-deploys)
1. Push this folder to a GitHub repo
2. Go to [https://app.netlify.com](https://app.netlify.com) → "New site from Git"
3. Select the repo → deploy settings are auto-detected
4. Every push to `main` auto-deploys

## Form Setup (Netlify Forms)

The lead capture form uses **Netlify Forms** — it works automatically when deployed to Netlify. No backend code needed.

### Where do leads go?
- **Netlify Dashboard** → Your site → **Forms** → `car-request`
- All submissions (name, email, phone, vehicle, budget) show up there

### Set up email notifications:
1. Go to **Netlify Dashboard** → Site settings → **Forms** → **Form notifications**
2. Click "Add notification" → **Email notification**
3. Set the email to wherever you want leads sent
4. Every form submission will trigger an email with the lead's info

### Spam protection:
- A honeypot field is already built in (hidden from humans, catches bots)
- You can also enable reCAPTCHA in Netlify settings if needed later

## Custom Domain
1. In Netlify Dashboard → **Domain settings** → **Add custom domain**
2. Add your domain (e.g., `gokemotorservices.com`)
3. Update your domain's DNS to point to Netlify (they walk you through it)
4. Free SSL is auto-provisioned

## Remaining To-Dos
- [ ] Add real car photos/videos to the gallery section (swap in `<img>` tags — instructions in HTML comments)
- [ ] Update PayPal.me link with actual PayPal URL
- [ ] Update social media links with real Instagram/Facebook/TikTok handles
- [ ] Add Google Analytics tracking (uncomment and add Measurement ID)
- [ ] Add Facebook Pixel for ad retargeting
- [ ] Purchase and connect custom domain (e.g., gokemotorservices.com)
- [ ] Set up Netlify email notifications for form submissions
- [ ] Connect form to a CRM (HubSpot, Mailchimp, etc.) via Netlify integrations
- [ ] Replace founder photo placeholder with real photo
- [ ] Replace placeholder testimonials with real customer reviews

## Contact
- **Phone**: (469) 431-1473
- **Business**: Goke Motor Services
- **Location**: Dallas–Fort Worth area (serves nationwide)
