# Deployment Guide

## Deploy to Netlify

### Option 1: Deploy via Netlify UI (Recommended)

1. Go to [Netlify](https://app.netlify.com/)
2. Click "Add new site" → "Import an existing project"
3. Connect to your GitHub account
4. Select the `yns-web-studio` repository
5. Netlify will automatically detect the `netlify.toml` configuration
6. Click "Deploy site"

Your site will be live in minutes!

### Option 2: Deploy via Netlify CLI

```bash
# Install Netlify CLI
npm install -g netlify-cli

# Login to Netlify
netlify login

# Deploy
netlify deploy --prod
```

## Deploy to Other Platforms

### GitHub Pages
1. Go to repository Settings → Pages
2. Select branch: `copilot/create-yns-web-studio-website`
3. Select folder: `/ (root)`
4. Click Save

### Vercel
```bash
# Install Vercel CLI
npm install -g vercel

# Deploy
vercel --prod
```

### Any Static Host
Simply upload these files to your web hosting:
- index.html
- style.css
- logo.svg

## Custom Domain

Once deployed, you can add a custom domain in your hosting platform's settings.

### Netlify Custom Domain
1. Go to Site settings → Domain management
2. Click "Add custom domain"
3. Follow the DNS configuration instructions

## Testing

After deployment, verify:
- ✅ All sections load properly
- ✅ Mobile responsiveness works
- ✅ Call and WhatsApp buttons work
- ✅ Page loads quickly (< 2 seconds)

## Contact

For questions: +91 9352563337
