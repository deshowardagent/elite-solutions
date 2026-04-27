# Elite Business Systems — Website

Static HTML/CSS/JS website for Elite Business Systems consulting.

## Pages
- `index.html` — Home
- `services.html` — Services
- `how-it-works.html` — How It Works
- `refund-policy.html` — Refund Policy & Fulfillment
- `contact.html` — Contact

## Deployment (GitHub Pages)

1. Push this folder to a GitHub repo (e.g. `elite-business-systems`)
2. Go to repo Settings → Pages → Source: `main` branch, `/ (root)`
3. Site will be live at `https://yourusername.github.io/elite-business-systems`

## Custom Domain (GoDaddy → GitHub Pages)

1. In GitHub Pages settings, enter your custom domain (e.g. `elitebusinesssystems.com`)
2. GitHub will create a `CNAME` file automatically
3. In GoDaddy DNS, add:
   - Type: `A` — Host: `@` — Value: `185.199.108.153`
   - Type: `A` — Host: `@` — Value: `185.199.109.153`
   - Type: `A` — Host: `@` — Value: `185.199.110.153`
   - Type: `A` — Host: `@` — Value: `185.199.111.153`
   - Type: `CNAME` — Host: `www` — Value: `yourusername.github.io`
4. Check "Enforce HTTPS" in GitHub Pages settings after DNS propagates (~30 min)

## Contact Form
The form uses Formspree (free tier). Replace the `action` URL in `contact.html` with your own Formspree endpoint at formspree.io.
