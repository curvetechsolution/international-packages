# 🌍 Curve Tech Solution - International Website

**AI-Powered Digital Services for Modern Businesses**

---

## 📋 About This Project

This is the **International Version** of Curve Tech Solution's services website.

**Key Features:**
- ✅ All pricing in **USD ($)**
- ✅ No phone number (contact via Calendly only)
- ✅ Same design as original
- ✅ All 8 services included
- ✅ Responsive & fast
- ✅ Ready to deploy

---

## 🚀 Quick Start

### 1. Install Dependencies
```bash
npm install
```

### 2. Run Development Server
```bash
npm run dev
```
Website opens at: `http://localhost:5173`

### 3. Build for Production
```bash
npm run build
```

### 4. Deploy
- **Vercel**: `vercel deploy --prod`
- **Netlify**: Connect GitHub repo
- **Other**: Upload `dist/` folder

---

## 📦 What's Included

```
curve-services-international/
├── src/
│   ├── App.tsx              ← International with USD pricing
│   └── main.tsx
├── public/
│   ├── logo.png
│   └── favicon.svg
├── index.html
├── package.json
├── tsconfig.json
├── vite.config.ts
└── README.md (this file)
```

---

## 💱 Pricing (USD)

### Services Included:

1. **🤖 Chatbot Automation**
   - Basic: $43/mo + $79 setup
   - Standard: $79/mo + $129 setup ⭐
   - Pro: $126/mo + $194 setup

2. **🌐 Website Development**
   - Starter: $36/project
   - Standard: $101/project ⭐
   - Premium: $187/project

3. **📱 Social Media Marketing**
   - Custom pricing
   - Multiple platforms
   - Posts, reels, ads

4. **🔍 SEO**
   - Local: $54/mo
   - Growth: $101/mo ⭐
   - Authority: $180/mo

5. **📢 Google Ads**
   - Launch: $54/mo
   - Scale: $90/mo ⭐
   - Full Funnel: $144/mo

6. **📞 Calling Agent**
   - Basic: $65/mo + $72 setup
   - Standard: $108/mo + $126 setup ⭐
   - Enterprise: $180/mo + $198 setup

7. **🎯 Lead Generation**
   - Starter: $72/mo
   - Growth: $126/mo ⭐
   - Enterprise: $216/mo

8. **🎬 AI Video Creation**
   - 3 Videos: $43/mo
   - 6 Videos: $76/mo ⭐
   - 10 Videos: $115/mo

### 📦 Combo Packages:
- Starter Combo: $162/mo (20% savings)
- Business Combo: $288/mo (25% savings) ⭐
- Ultimate Combo: $468/mo (30% savings)

---

## 📊 Features

### Services
- ✅ 8 different digital services
- ✅ Multiple pricing tiers
- ✅ Feature comparison
- ✅ Custom combo builder

### Integration
- ✅ Calendly booking
- ✅ Supabase database
- ✅ Form submission
- ✅ WhatsApp removed (contact via Calendly)

### Mobile
- ✅ Fully responsive
- ✅ Touch-optimized
- ✅ Fast loading
- ✅ SEO friendly

---

## 🔧 Technology Stack

- **Frontend**: React 18 + TypeScript
- **Styling**: Inline CSS + Tailwind ready
- **Build**: Vite
- **Hosting**: Vercel / Netlify / Custom
- **Database**: Supabase (optional)
- **Booking**: Calendly integration

---

## 📝 Configuration

### Update These Files:

**1. Calendly Link** (in `src/App.tsx`):
```javascript
const CALENDLY = "https://calendly.com/your-username/meeting";
```

**2. Website URL** (in `src/App.tsx`):
```javascript
const SITE = "https://your-domain.com";
```

**3. Supabase Keys** (in `src/App.tsx`):
```javascript
const SUPABASE_URL = "your-url";
const SUPABASE_KEY = "your-key";
```

---

## 🚀 Deployment Options

### Option 1: Vercel (Recommended)
```bash
npm install -g vercel
vercel login
vercel deploy --prod
```

### Option 2: Netlify
1. Push to GitHub
2. Connect repo to Netlify
3. Auto-deploys on push

### Option 3: Self-Hosted
```bash
npm run build
# Upload 'dist' folder to your server
```

---

## 📱 Invoice Integration

This website connects to the invoice system:
1. Client clicks "Get Started"
2. Fills form with details
3. You create invoice in invoice system
4. **Currency automatically: USD** ✅
5. Send to client

---

## ✅ Pre-Deployment Checklist

- [ ] Updated Calendly URL
- [ ] Updated website URL
- [ ] Updated Supabase keys (if needed)
- [ ] Tested on mobile
- [ ] Tested all service pages
- [ ] Tested forms
- [ ] Prices showing in USD
- [ ] No console errors

---

## 🎯 Key Changes from Original

| Item | Original (PKR) | International (USD) |
|------|---|---|
| Pricing | Rs. 12,000 | $43 |
| Currency | PKR | USD |
| Format | Rs. X,XXX | $X,XXX.XX |
| Phone | Included | Removed |
| Contact | WhatsApp | Calendly only |

---

## 📞 Contact Methods

**For your clients:**
- 📅 Calendly: Book meeting
- 🌐 Website: curvetechsolution.online

---

## 📚 Documentation

Included with this project:
- DEPLOYMENT-GUIDE.md - How to deploy
- PRICE-CONVERSION-REFERENCE.md - All prices
- INVOICE-SYSTEM-GUIDE.md - Invoice integration
- SALES-QUICK-REFERENCE.md - Sales guide

---

## 🆘 Troubleshooting

### Port already in use?
```bash
npm run dev -- --port 3000
```

### Old prices showing?
```
Hard refresh: Ctrl+Shift+R (or Cmd+Shift+R on Mac)
```

### Build fails?
```bash
rm -rf node_modules
npm install
npm run build
```

### Blank page after deploy?
- Check Vercel/Netlify logs
- Check browser console (F12)
- Make sure all files are deployed

---

## 📈 Analytics & Tracking

To add Google Analytics:

Edit `src/main.tsx` and add:
```html
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_ID"></script>
```

---

## 🔒 Security

- ✅ No sensitive data in code
- ✅ Supabase keys should be private
- ✅ Use environment variables
- ✅ HTTPS only for production

---

## 📄 License

Private - For Curve Tech Solution use only

---

## ✨ Support

For questions or issues:
1. Check DEPLOYMENT-GUIDE.md
2. Check error messages in console
3. Review the code comments

---

## 🎉 Ready to Deploy!

This is a **complete, production-ready** website.

Just:
1. Update configuration
2. Run `npm install`
3. Run `npm run build`
4. Deploy to Vercel/Netlify

**That's it!** 🚀

---

**Version**: 1.0 International  
**Last Updated**: June 2026  
**Status**: ✅ Ready for Production  
**Currency**: USD ($)  
**Phone**: Removed  
**Invoice Ready**: YES ✅
