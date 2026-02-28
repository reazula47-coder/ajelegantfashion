# 🎯 AJELEGANTFASHION - Ultra Premium Landing Funnel

> **Premium Facebook Ads Conversion Funnel** | Meta Pixel Integrated | Mobile Optimized | Zero Configuration

---

## 📊 What's Included

✅ **4 Optimized Pages:**
- `index.html` - Hero Landing Page with Product Showcase
- `product.html` - Premium Product Catalog
- `order.html` - High-Converting Checkout Form
- `thank-you.html` - Order Confirmation Page

✅ **Meta Pixel Integration (ID: 951370043895258):**
- **PageView** - Automatic page visit tracking
- **ViewContent** - Product view tracking
- **AddToCart** - Product selection tracking
- **Purchase** - Order completion tracking
- **Lead** - Successful order tracking

✅ **Premium Features:**
- Dark + Gold luxury design
- Fully responsive mobile-first layout
- Smooth animations & micro-interactions
- Low-friction checkout flow
- Fast loading & optimized performance

---

## 🚀 Quick Deploy

### Option 1: GitHub Pages (FREE & RECOMMENDED)

1. **Enable Pages:**
   - Go to **Settings** → **Pages**
   - Select `main` branch
   - Click **Save**

2. **Your site is live at:**
   ```
   https://reazula47-coder.github.io/AJELEGANTFASHION/
   ```

### Option 2: Custom Domain

Use Vercel, Netlify, or Firebase Hosting:
- Point domain to GitHub Pages, OR
- Deploy directly to your preferred platform

---

## 📱 Meta Pixel Setup

### Already Configured With:
- **Pixel ID:** `951370043895258`
- **Events:** PageView, ViewContent, AddToCart, Purchase, Lead

### To Update Pixel ID:

1. Find & replace `951370043895258` with your pixel ID in all HTML files
2. Or search for `fbq('init',` in each file

### To Verify Pixel Works:

1. Install [Meta Pixel Helper Chrome Extension](https://chrome.google.com/webstore)
2. Visit your live site
3. Extension will show pixel firing events ✅

---

## 🎯 Integration with Facebook Ads

1. **Go to Meta Ads Manager**
2. **Create Campaign** → Select **Conversions**
3. **Select Website** → Choose **Purchases** event
4. **Paste your live URL** (e.g., `https://reazula47-coder.github.io/AJELEGANTFASHION/`)
5. **Meta validates pixel** → Ready to launch ads! 🚀

---

## 📊 Tracked Events

| Event | Triggers On | Value |
|-------|-----------|-------|
| **PageView** | Every page load | Auto |
| **ViewContent** | Product click | Product price |
| **AddToCart** | Product selection | Product price |
| **Purchase** | Order submission | Order total |
| **Lead** | Thank you page | Fixed (1) |

---

## 🛠️ Customization

### Change Business Name
Replace `AJELEGANTFASHION` with your brand name in:
- `index.html` - Logo & navigation
- `product.html` - All pages
- `order.html` - Header & branding
- `thank-you.html` - Footer

### Change Products & Prices
Edit the `priceMap` object in `order.html`:
```javascript
const priceMap = {
  'Your Product - ৳PRICE': PRICE_INT,
  // Add more products here
};
```

### Change Images
Replace image URLs with your own:
- Product images: `https://images.unsplash.com/...`
- Hero slides: Background images in `.slide` classes

### Change Currency
Replace `৳` (Bengali Taka) with your currency symbol:
- Search for `৳` in all files
- Replace with your currency

---

## 📈 Performance Tips

✅ **Already Optimized For:**
- Mobile responsiveness
- Fast load times
- SEO-friendly structure
- Accessibility standards
- Meta Pixel best practices

**Additional Tweaks:**
- Compress images further using TinyPNG
- Lazy load images on slow connections
- Use CDN for image hosting

---

## 🔗 Links

- **Live Demo:** https://reazula47-coder.github.io/AJELEGANTFASHION/
- **Meta Pixel Docs:** https://developers.facebook.com/docs/facebook-pixel
- **Facebook Ads Help:** https://www.facebook.com/business/help

---

## 📞 Support

**Questions about Meta Pixel?**
- Check [Meta Pixel Helper Extension](https://chrome.google.com/webstore)
- Visit [Meta Business Help](https://www.facebook.com/business/help)

**Need to modify?**
- Edit HTML files directly in GitHub
- Or clone locally: `git clone https://github.com/reazula47-coder/AJELEGANTFASHION.git`

---

## 📜 License

Free to use & modify for your business.

---

## 🎁 What You Get

- ✨ Premium dark + gold design
- 🚀 Production-ready code
- 📊 Meta Pixel fully integrated
- 📱 Mobile-optimized
- 🎯 Conversion-focused layout
- 🔄 Easy to customize
- 🆓 Free hosting on GitHub Pages

---

**Ready to launch your premium fashion funnel? Go live in minutes! 🎉