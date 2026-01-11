# OG Image Setup Guide

## What You Need
An Open Graph image for social media sharing. Dimensions: **1200x630px** (2:1 ratio)

## File Location
Place `og-image.png` in the root directory (same level as `index.html`)

The landing page is already configured to use it:
- **OG Image URL**: `https://stockathon.com/og-image.png`
- Twitter, LinkedIn, Facebook will all use this image

## Recommended Design

Think like Stripe, Gumroad, Loom:
- **Dark background** (matching your site's dark theme #0a0a0a)
- **Bright accent color** (your green #00ff66)
- **Clear app name/logo** (Stocksathon)
- **One key benefit** (e.g., "Pick Stocks. Win Real Competition.")
- **Mobile phone mockup** (optional but high-impact)

## Quick Creation Options

### Option 1: Using a Design Tool (Recommended)
- Figma: 1200x630px canvas
- Canva: Choose "Custom 1200x630"
- Adobe Express: Template size 1200x630

### Option 2: Screenshot-Based
1. Use your `screenshot.png` as the hero
2. Add text overlay with the green accent (#00ff66)
3. Export as 1200x630 PNG

### Option 3: Design Template
Create a minimal but stunning design:
```
[Dark Background #0a0a0a]
  
  STOCKSATHON
  [Green accent line]
  
  Pick Stocks. Compete. Win.
  
  [Optional: Phone mockup of app]
```

## Implementation Checklist
- [x] Updated Open Graph meta tags in `index.html`
- [x] Updated Twitter Card meta tags
- [x] Added image width/height/type attributes
- [x] Added alt text for accessibility
- [ ] **Create and place `og-image.png` in root directory**
- [ ] Test on social sharing preview tools

## Testing
After uploading `og-image.png`:
1. Test on [Open Graph Debugger](https://www.facebook.com/sharing/debugger/)
2. Test on [Twitter Card Validator](https://cards-dev.twitter.com/validator)
3. Test on [LinkedIn URL Inspector](https://www.linkedin.com/feed/)

## Notes
- Keep it simple and scannable
- Use your brand colors (#00ff66, #0a0a0a)
- Make text large enough to read at thumbnail size
- No tiny fonts or complex graphics
- Consider including your Android app badge or Play Store button
