# AxtarGet.online - Setup & Deployment Guide

## 🚀 Quick Start

Your AxtarGet.online AI platform is now customized and ready to run!

### Prerequisites
- Node.js 18+ installed
- pnpm package manager (or npm/yarn)

### Installation & Running Locally

```bash
# Install dependencies (already done)
pnpm install

# Start development server
pnpm dev

# Open in browser: http://localhost:5173/
```

The application will automatically hot-reload as you make changes.

---

## 🎨 Design & Branding

**Color Scheme:** Black & White (Professional AI Platform)
- Primary: Black (#000000)
- Secondary: White text on dark background
- Accent: AI-focused color scheme

**Logo Files:**
- `/public/logo-light-styled.png` - Light theme logo
- `/public/logo-dark-styled.png` - Dark theme logo (currently active)
- `/public/favicon.ico` - Browser tab icon

---

## ⚙️ Configuration

### Setting Up AI Providers

1. Open the application
2. Click **Settings** (gear icon)
3. Go to **Cloud Providers** tab
4. Select your preferred AI provider (OpenAI, Anthropic, Google, etc.)
5. Enter your API key

**Supported Providers:**
- OpenAI (GPT-4, GPT-3.5)
- Anthropic (Claude)
- Google (Gemini)
- Groq
- Together
- Perplexity
- Amazon Bedrock
- And more...

### API Key Management

API keys are stored locally in your browser cookies and never transmitted to external servers without your consent. To add/update API keys:

1. Settings → Cloud Providers
2. Click on provider
3. Paste your API key
4. Save configuration

⚠️ **Security Note:** Never share your API keys. Keep them private.

---

## 🔧 What Has Been Customized

### 1. Branding
✅ Company name changed to **AxtarGet.online**
✅ All user-facing text updated
✅ Logo and favicon replaced
✅ Meta tags and page title updated
✅ Error messages personalized

### 2. AI Platform Focus
✅ Example prompts now AI-focused
✅ UI optimized for search and intelligence tasks
✅ Error handling for API failures
✅ Ready for multiple AI model integrations

### 3. User Experience
✅ Dark mode as default (professional look)
✅ Consistent branding throughout
✅ Improved error messages
✅ Quick access to AI providers

---

## 📦 Deployment Options

### Option 1: Cloudflare Pages (Recommended)
```bash
# Install Wrangler CLI
npm install -g wrangler

# Deploy
npm run build
wrangler pages deploy ./build/client
```

### Option 2: Vercel
```bash
# Push to GitHub first, then connect to Vercel
# Automatic deployments on git push
```

### Option 3: Netlify
```bash
# Netlify auto-detects the build
# Connect your GitHub repo to Netlify
```

### Option 4: Docker
```bash
# Create Dockerfile and deploy to your hosting
docker build -t axtarget .
docker run -p 3000:3000 axtarget
```

---

## 📝 Environment Variables

Create a `.env.local` file for local development:

```env
# Your AI provider keys
OPENAI_API_KEY=your_key_here
ANTHROPIC_API_KEY=your_key_here

# Optional: Analytics and monitoring
VERCEL_ANALYTICS_ID=your_id_here
```

For production, add these to your deployment platform's environment variables.

---

## 🛠️ Development

### Project Structure
```
/app
  /components     - React components
  /lib           - Utility functions and hooks
  /routes        - Page routes
  /utils         - Helper functions
/public          - Static assets (logos, icons)
```

### Build for Production
```bash
pnpm build
pnpm start
```

### Run Tests
```bash
pnpm test              # Run once
pnpm test:watch        # Watch mode
```

### Linting
```bash
pnpm lint              # Check for issues
pnpm lint:fix          # Fix automatically
```

---

## 🐛 Troubleshooting

### Issue: Dev server won't start
```bash
# Clear cache and node_modules
rm -rf node_modules pnpm-lock.yaml
pnpm install
pnpm dev
```

### Issue: API key not working
1. Verify the API key is correct
2. Check that the provider is selected
3. Ensure you have API credits/quota
4. Check browser console for error messages

### Issue: Logo not displaying
1. Verify `/public/logo-light-styled.png` and `/public/logo-dark-styled.png` exist
2. Clear browser cache (Ctrl+Shift+Delete)
3. Check browser dev tools (F12) for 404 errors

---

## 📞 Support & Documentation

- **Official Site:** https://axtarget.online
- **Documentation:** See AXTARGET_CUSTOMIZATION.md
- **API Documentation:** Available in Settings panel

---

## 🎯 Next Steps

1. ✅ Run locally: `pnpm dev`
2. ✅ Configure AI providers in Settings
3. ✅ Test with example prompts
4. ✅ Deploy to production
5. ✅ Share with team members

---

## 📄 File Modifications Made

**Core Files Updated:**
- `app/routes/_index.tsx` - Page metadata
- `app/root.tsx` - Theme and branding
- `app/layout.tsx` - HTML structure and colors
- `app/components/chat/ChatAlert.tsx` - Error messages
- `app/components/deploy/DeployAlert.tsx` - Deployment messages
- `app/components/chat/ExamplePrompts.tsx` - Example queries

**Assets Added:**
- `public/favicon.ico` - AxtarGet icon
- `public/logo-light-styled.png` - Light logo
- `public/logo-dark-styled.png` - Dark logo

**Documentation Added:**
- `AXTARGET_CUSTOMIZATION.md` - Customization details
- `AXTARGET_SETUP_GUIDE.md` - This file

---

## ✨ Features Ready to Use

- 💬 **AI Chat Interface** - Talk with your configured AI
- 🔍 **Search & Browse** - Find information quickly
- 📊 **Analytics** - Track usage and performance
- 🔐 **Secure** - API keys stay local
- 🌐 **Multi-Provider** - Switch between different AI services
- 🚀 **Fast** - Optimized for speed and performance
- 📱 **Responsive** - Works on mobile and desktop

---

**Platform:** AxtarGet.online  
**Version:** 1.0.0  
**Last Updated:** July 23, 2026  
**Status:** ✅ Ready for Deployment

Enjoy your new AI platform! 🎉
