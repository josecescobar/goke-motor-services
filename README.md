# Goke Motor Services — Car Buying Service Website

## What This Is
A single-page landing site for **Goke Motor Services**, a car buying service that helps people purchase vehicles at wholesale pricing through dealer-only auctions.

## Files
```
goke-motor-services/
├── index.html       ← Main landing page (all CSS/JS inline)
├── success.html     ← Thank-you page after form submission
└── README.md        ← You're reading it
```

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

## Future Enhancements
- [ ] Add real car photos/videos to the gallery section
- [ ] Add PayPal payment button/link for service fee collection
- [ ] Add Zelle QR code or payment info
- [ ] Add Google Analytics tracking
- [ ] Add Facebook Pixel for ad retargeting
- [ ] Add customer testimonials
- [ ] Connect form to a CRM (HubSpot, Mailchimp, etc.) via Netlify integrations

## Contact
- **Phone**: (469) 431-1473
- **Business**: Goke Motor Services
