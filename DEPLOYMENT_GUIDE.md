# 🚀 London Frontline Website - Deployment Guide

## Quick Deploy to Render (Recommended)

### Step 1: Create Render Account
1. Go to [render.com](https://render.com)
2. Click "Get Started" and sign up with your GitHub account
3. Verify your email

### Step 2: Deploy Your Website
1. In Render dashboard, click "New +"
2. Select "Web Service"
3. Connect your GitHub repository (if you have one) or use "Deploy from existing repository"
4. If you don't have a GitHub repo, follow the manual steps below

### Step 3: Manual Deployment (if no GitHub)
1. In Render dashboard, click "New +"
2. Select "Web Service"
3. Choose "Deploy from existing repository"
4. Upload your project files or use the GitHub integration

### Step 4: Configure Your Service
- **Name**: `london-frontline-website`
- **Environment**: `Node`
- **Build Command**: `npm install`
- **Start Command**: `npm start`
- **Plan**: `Free`

### Step 5: Deploy
1. Click "Create Web Service"
2. Wait for deployment (usually 2-3 minutes)
3. Your website will be live at: `https://your-app-name.onrender.com`

## Alternative: GitHub Pages (Static Only)

If you prefer GitHub Pages (static hosting only):

1. Create a GitHub repository
2. Push your code to GitHub
3. Go to repository Settings > Pages
4. Select source branch (main/master)
5. Your site will be at: `https://username.github.io/repository-name`

## Alternative: Netlify

1. Go to [netlify.com](https://netlify.com)
2. Sign up with GitHub
3. Click "New site from Git"
4. Select your repository
5. Build command: `npm install`
6. Publish directory: `.`
7. Deploy!

## Your Website Features

✅ **Live Server**: Express.js backend with API endpoints
✅ **Health Check**: `/health` endpoint for monitoring
✅ **API Info**: `/api/info` for server information
✅ **Professional Design**: Modern UI with interactive elements
✅ **Mobile Responsive**: Works on all devices
✅ **Security**: Helmet.js security headers
✅ **CORS Enabled**: Cross-origin requests allowed

## After Deployment

Your website will include:
- Interactive tabs with popup modals
- London Frontline branding
- Professional styling
- Discord integration
- Application process
- Department information

## Support

If you need help with deployment, check the main README.md file for detailed instructions. 