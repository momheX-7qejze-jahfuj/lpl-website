# The Leadership Pressure Lab™ — Website
**Copyright © 2026 Joseph "Coach Joe" Clementi. All Rights Reserved.**

---

## Overview
This is the official website for The Leadership Pressure Lab™ (`coachjoeleadership.com`), a static HTML website hosted on GitHub Pages.

**The P.R.E.S.S.U.R.E. System™, The Pressure Test™, Responsible Ownership™, The Torque Drive OS™, The Pressure Lab Cohort™, and all associated content are the exclusive intellectual property of Joseph Clementi. Unauthorized reproduction is prohibited.**

---

## File Structure
```
/
├── index.html          ← Homepage (primary SEO page)
├── about.html          ← About Coach Joe
├── system.html         ← The P.R.E.S.S.U.R.E. System™
├── products.html       ← Full product suite
├── pricing.html        ← Value stack & pricing
├── keynote.html        ← The Torque Drive Keynote
├── pressure-test.html  ← The Pressure Test™
├── cohort.html         ← The Pressure Lab Cohort™
├── monday-brief.html   ← The Monday Brief signup
├── strategy-call.html  ← Strategy Call booking
├── privacy.html        ← Privacy Policy
├── terms.html          ← Terms of Service
├── sitemap.xml         ← SEO sitemap
├── robots.txt          ← Search engine directives
├── .nojekyll           ← Required for GitHub Pages
├── css/style.css       ← Shared design system
├── js/main.js          ← Shared JavaScript
└── images/             ← Place all images here
```

---

## GitHub Pages Setup (Step-by-Step)

### Step 1: Create Your GitHub Account
1. Go to [github.com](https://github.com) and create a free account
2. Verify your email address

### Step 2: Create the Repository
1. Click the **+** button → **New repository**
2. Name it: `lpl-website` (or any name you prefer)
3. Set to **Public** (required for free GitHub Pages)
4. Click **Create repository**

### Step 3: Upload Your Files
**Option A — GitHub Web Interface (Easiest):**
1. On your repository page, click **Upload files**
2. Drag all files and folders into the upload area
3. Click **Commit changes**

**Option B — GitHub Desktop App (Recommended):**
1. Download [GitHub Desktop](https://desktop.github.com)
2. Clone your repository
3. Copy all website files into the repository folder
4. Commit and push

### Step 4: Enable GitHub Pages
1. Go to your repository → **Settings** → **Pages**
2. Under **Source**: select **Deploy from a branch**
3. Under **Branch**: select `main` → `/ (root)`
4. Click **Save**
5. Wait 2–5 minutes. Your site will appear at:
   `https://YOUR-GITHUB-USERNAME.github.io/lpl-website/`

### Step 5: Connect Your Custom Domain
1. Buy `coachjoeleadership.com` from [Namecheap](https://namecheap.com) or [Cloudflare](https://cloudflare.com)
2. In GitHub Pages settings → **Custom domain** → enter your domain
3. In your domain DNS settings, add these records:
   ```
   Type: A    Name: @    Value: 185.199.108.153
   Type: A    Name: @    Value: 185.199.109.153
   Type: A    Name: @    Value: 185.199.110.153
   Type: A    Name: @    Value: 185.199.111.153
   Type: CNAME Name: www  Value: YOUR-USERNAME.github.io
   ```
4. Enable **Enforce HTTPS** (free SSL certificate)

---

## Required Configuration (Update Before Launch)

Search every file for these placeholders and replace:

| Placeholder | Replace With |
|-------------|-------------|
| `YOUR-PROFILE` | Your LinkedIn profile URL slug |
| `YOUR-FORM-ID` | Your [Formspree](https://formspree.io) form ID |
| `joe@coachjoeleadership.com` | Your real email address |
| `YOUR-LINK-HERE` | Your [Calendly](https://calendly.com) booking link |
| `coachjoeleadership.com` | Your actual domain name |

---

## Adding Your Calendly Booking Widget
1. Create a free account at [calendly.com](https://calendly.com)
2. Set up your 20-minute "Strategy Call" event
3. Click **Share** → **Embed** → **Inline Widget**
4. Copy the embed code
5. In `strategy-call.html`, replace the placeholder `<div>` with your Calendly code

---

## Setting Up Formspree (Email Forms)
1. Create a free account at [formspree.io](https://formspree.io)
2. Create a new form → copy your Form ID (looks like: `xyzabc123`)
3. Replace `YOUR-FORM-ID` in all HTML files with your actual ID
4. All form submissions will arrive in your email automatically

---

## SEO Quick Checklist
- [ ] Update all `YOUR-PROFILE` LinkedIn links
- [ ] Add your real profile photo as `images/coach-joe.jpg`
- [ ] Add OG image as `images/og-image.jpg` (1200×630px, navy background with brand)
- [ ] Submit sitemap to [Google Search Console](https://search.google.com/search-console)
- [ ] Submit sitemap to [Bing Webmaster Tools](https://www.bing.com/webmasters)
- [ ] Set up [Google Analytics 4](https://analytics.google.com) and add tracking code
- [ ] Create a [Google Business Profile](https://business.google.com) for local SEO
- [ ] Set up LinkedIn Company Page for The Leadership Pressure Lab™

---

## Making Updates
After any file change:
1. Open GitHub Desktop
2. Review changes
3. Write a commit message (e.g., "Update pricing page")
4. Click **Commit to main**
5. Click **Push origin**
6. Changes are live in ~60 seconds

---

## Intellectual Property
All content, systems, methodologies, and frameworks on this website are the exclusive intellectual property of Joseph "Coach Joe" Clementi:
- The P.R.E.S.S.U.R.E. System™
- The Pressure Test™
- Responsible Ownership™
- The Torque Drive OS™
- The Pressure Lab Cohort™
- The Pressure Suite™
- The Monday Brief
- The Leadership Pressure Lab™

**© 2026 Joseph Clementi. All Rights Reserved. Unauthorized reproduction or distribution is strictly prohibited.**

---

*This website was designed and built for exclusive use by Joseph "Coach Joe" Clementi and The Leadership Pressure Lab™.*
