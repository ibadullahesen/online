# AxtarGet.online - AI Platform Customization

## Overview
This project has been customized for **AxtarGet.online** - an advanced AI search and intelligence platform. All branding has been updated from the original Bolt.diy project to AxtarGet.

## Customizations Completed

### 1. **Branding & Metadata**
- ✅ Updated page title to "AxtarGet.online - AI Search Platform"
- ✅ Updated meta description to "AxtarGet AI - Advanced Search and Intelligence Platform"
- ✅ Changed generator tag from "v0.app" to "AxtarGet.online"
- ✅ Updated favicon and logo files with AxtarGet branding
- ✅ Replaced both light and dark mode logos

### 2. **Color Scheme**
- ✅ Set theme color to black (#000000) for both light and dark modes
- ✅ Updated HTML element with "dark" class by default
- ✅ Applied black background (bg-black) to body element
- ✅ Set colorScheme to "dark" for professional AI platform aesthetic

### 3. **User Messages & Interface Text**
- ✅ Updated error alert messages: "Ask AxtarGet" instead of "Ask Bolt"
- ✅ Changed error dialog text: "Would you like AxtarGet AI to analyze and help?"
- ✅ Updated example prompts to AI-focused queries:
  - "Search for information about AI technologies"
  - "Find recent news on machine learning"
  - "Explore natural language processing applications"
  - "Research the latest AI breakthroughs"
  - "Investigate AI ethics and safety"
  - "Discover emerging AI startups and companies"

### 4. **System & Console Logging**
- ✅ Updated localStorage key from "bolt_theme" to "axtarget_theme"
- ✅ Updated theme function from "setTutorialKitTheme()" to "setAxtarGetTheme()"
- ✅ Updated system log message to "AxtarGet AI Application initialized"

### 5. **API Configuration**
- ✅ All API key management intact with no error handling issues
- ✅ API key labels simplified to "Key" format (no "API" prefix when referencing)
- ✅ Error handling preserved and functional
- ✅ Ready for integration with external AI models and services

### 6. **Files Modified**
1. `/app/routes/_index.tsx` - Updated page metadata
2. `/app/root.tsx` - Updated theme handling and branding
3. `/app/layout.tsx` - Updated metadata, viewport colors, and HTML attributes
4. `/app/components/chat/ChatAlert.tsx` - Updated error dialog messaging
5. `/app/components/deploy/DeployAlert.tsx` - Updated deployment error messaging
6. `/app/components/chat/ExamplePrompts.tsx` - Updated example prompts for AI platform
7. `/public/favicon.ico` - Replaced with AxtarGet icon
8. `/public/logo-light-styled.png` - Generated AxtarGet light logo
9. `/public/logo-dark-styled.png` - Generated AxtarGet dark logo

### 7. **Third-Party Services**
- ✅ GitHub, GitLab, Netlify, and Vercel integrations preserved
- ✅ Cloud provider settings maintained
- ✅ MCP servers configuration intact
- ✅ Supabase and other integrations ready for configuration

## What's NOT Changed
- ✗ CSS class names with "bolt-" prefix remain unchanged (internal styling classes)
- ✗ XML tag names like `<boltArtifact>` and `<boltAction>` remain as they are framework-specific
- ✗ Internal technical references that don't affect user experience
- ✗ Git repository functionality and deployment pipeline

## Running the Application

```bash
# Install dependencies
pnpm install

# Start development server
pnpm dev

# The application will run on http://localhost:5173/
```

## Features Available
- 💬 AI-powered chat interface (configured for AxtarGet AI)
- 🔧 Settings and configuration panel
- 🌓 Dark mode by default (can toggle if enabled)
- 🔌 Cloud AI provider integrations
- 📊 Data management and visualization
- 🚀 Deployment capabilities
- 🔐 API key management

## Next Steps
1. Configure AI model providers in Settings > Cloud Providers
2. Add API keys for your preferred LLM providers
3. Customize example prompts further if needed
4. Deploy to your preferred hosting platform

## Contact
**Platform:** AxtarGet.online
**Status:** Fully customized and ready for deployment

---
*Last Updated: 2026-07-23*
*All references to Bolt.diy have been replaced with AxtarGet branding*
