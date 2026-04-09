# ProBiz.Cards Landing Page

A modern, responsive landing page for ProBiz.Cards - Digital Business Cards That Work.

## Features

- Clean, professional design
- Mobile responsive
- Smooth scrolling navigation
- Clickable CTA buttons
- Contact form ready for Formspree integration
- Pricing cards with hover effects

## Deploy to Vercel

### Option 1: Vercel CLI

```bash
# Install Vercel CLI if you haven't already
npm i -g vercel

# Navigate to the project folder
cd probiz-landing

# Deploy
vercel --prod
```

### Option 2: Vercel Dashboard

1. Go to <https://vercel.com/new>
2. Import your GitHub repository (if you push this code to GitHub)
3. Or drag and drop the `probiz-landing` folder
4. Click "Deploy"

## Customization

### Update Contact Form

Replace `YOUR_FORM_ID` in the form action with your Formspree form ID:

```html
<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
```

Get a free form ID at <https://formspree.io>

### Update Colors

Edit the CSS variables in the `<style>` section to match your brand:

- Primary gradient: `#667eea` to `#764ba2`
- CTA button: `#ff6b6b`

### Update Content

Simply edit the HTML text to match your messaging.

## File Structure

```
probiz-landing/
├── index.html      # Main landing page
├── package.json    # Project metadata
└── README.md       # This file
```

## License

© 2026 Thrivality Balance LLC
