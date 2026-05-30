# On Pace For - Marketing Website

Marketing website for **On Pace For**, an iOS health and fitness activity tracking app with smart goal projections.

## 🚀 Overview

This website supports the App Store launch of On Pace For, featuring:
- Complete product information and features
- Subscription pricing details ($0.99/month, $9.99/year)
- Privacy Policy and Terms of Service (required for App Store)
- SEO optimization for app discovery
- Responsive design for all devices

## 📋 App Information

- **App Name**: On Pace For
- **Bundle ID**: com.timhibbard.onpacefor
- **Platform**: iOS 16.0+
- **Category**: Health & Fitness
- **Monetization**: Subscription with 14-day free trial

### Subscription Plans
- **Monthly**: $0.99/month
- **Annual**: $9.99/year (16% savings)
- **Free Trial**: 14 days

### Premium Features
- Advanced analytics and detailed insights
- Unlimited custom timelines
- Smart goal recommendations
- Data export functionality
- Workout intelligence features

## 📁 Site Structure

```
/
├── index.html          # Homepage with hero, value props, premium highlights
├── features.html       # Detailed feature descriptions
├── pricing.html        # Subscription plans and FAQ
├── contact.html        # Contact form and support information
├── privacy.html        # Privacy Policy (App Store required)
├── terms.html          # Terms of Service (App Store required)
├── styles.css          # Complete responsive CSS
├── robots.txt          # SEO crawler configuration
└── sitemap.xml         # SEO sitemap
```

## 🎯 App Store Requirements Checklist

### ✅ Completed
- [x] Privacy Policy page at `/privacy.html`
- [x] Terms of Service page at `/terms.html`
- [x] Subscription pricing clearly displayed
- [x] Premium features documentation
- [x] Contact/support information
- [x] Mobile-responsive design
- [x] SEO optimization (meta tags, structured data)

### 🔄 Action Items Before Launch

1. **✅ App Store URL** - COMPLETED
   - App Store ID: `6773984353`
   - URLs updated in all pages

2. **✅ Contact Email** - COMPLETED
   - Email: `timhibbard@gmail.com`
   - Updated in privacy, terms, and contact pages

3. **Configure Contact Form**
   - Update Formspree URL in `contact.html`
   - Replace `YOUR_FORM_ID` with your Formspree form ID
   - Or use alternative form service (Netlify Forms, etc.)

4. **Add App Screenshots**
   - Create/add images to `assets/images/` directory:
     - `screenshot-hero.png` - Main app screen
     - `screenshot-dashboard.png` - Live dashboard
     - `screenshot-forecast.png` - Forecasting view
     - `screenshot-goals.png` - Goals interface
     - `screenshot-health-integration.png` - HealthKit integration
     - `og-image.png` - Social media preview (1200x630px)

5. **Set Up Domain**
   - Configure DNS for `onpacefor.com`
   - Enable HTTPS/SSL
   - Update all absolute URLs if domain differs

6. **Apple App Store Connect**
   - Add Privacy Policy URL: `https://onpacefor.com/privacy.html`
   - Add Terms of Service URL: `https://onpacefor.com/terms.html`
   - Add Marketing URL: `https://onpacefor.com`
   - Add Support URL: `https://onpacefor.com/contact.html`

## 🔍 SEO Features

### Meta Tags
- Page titles optimized for search
- Meta descriptions for all pages
- Keywords targeting fitness/health tracking
- Open Graph tags for social sharing
- Twitter Card support

### Structured Data
- MobileApplication schema on homepage
- Product/Offer schema on pricing page
- Helps Google understand app details

### Technical SEO
- `robots.txt` for crawler control
- `sitemap.xml` for page discovery
- Mobile-responsive design
- Fast loading (minimal CSS/JS)
- Semantic HTML structure

## 🎨 Design Features

- **Responsive**: Works on mobile, tablet, desktop
- **Modern**: Clean, professional design
- **Accessible**: Semantic HTML, keyboard navigation
- **Fast**: Minimal dependencies, optimized CSS
- **Brand Colors**: Blue (#007BFF) primary, gradient accents

## 📱 Testing Checklist

Before launch, test:
- [ ] All internal links work
- [ ] App Store links redirect properly (after adding real ID)
- [ ] Contact form submits successfully
- [ ] Mobile responsive design on iOS/Android
- [ ] Privacy policy is complete and accurate
- [ ] Terms of service is complete and accurate
- [ ] All subscription details are correct
- [ ] Screenshots display properly (after adding)
- [ ] Footer links work
- [ ] Cross-browser compatibility (Safari, Chrome, Firefox)

## 🚀 Deployment

### Recommended Hosting
- **Netlify**: Free tier, automatic HTTPS, easy deployment
- **Vercel**: Free tier, excellent performance
- **GitHub Pages**: Free, simple setup
- **Cloudflare Pages**: Free tier, global CDN

### Quick Deploy
```bash
# Deploy to Netlify (example)
netlify deploy --prod

# Or via GitHub Pages
# Push to gh-pages branch or configure in repo settings
```

## 📊 Analytics (Optional)

Consider adding:
- Google Analytics or Plausible for traffic tracking
- App Store attribution parameters
- Conversion tracking for App Store clicks

## 📄 Legal Compliance

The Privacy Policy and Terms of Service documents comply with:
- Apple App Store Review Guidelines
- Apple HealthKit Data Use Requirements
- California Consumer Privacy Act (CCPA)
- General Data Protection Regulation (GDPR)

**Important**: Review legal documents with a legal professional if needed.

## 🔒 Privacy Highlights

- All health data stored locally on device
- No cloud storage of user health information
- Firebase Analytics for usage (anonymized)
- No third-party data sharing
- No advertising

## 📞 Support

For questions about the website or app:
- Email: timhibbard@gmail.com
- Website: https://onpacefor.com/contact.html

## 📝 License

© 2026 On Pace For. All rights reserved.
