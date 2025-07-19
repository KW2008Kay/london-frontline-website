# London Frontline - Official Documentation & Guidelines

🚔 **Professional Roleplay Community Website** | FiveM Server

## 🌟 Features

- **Interactive Modal System** - Clickable tabs with popup information
- **Professional Design** - Modern UI with London Frontline branding
- **Responsive Layout** - Works on desktop, tablet, and mobile
- **Express.js Server** - Secure backend with API endpoints
- **Auto-Deployment Ready** - Easy deployment to multiple platforms

## 🚀 Quick Start

### Local Development

1. **Install Dependencies:**
   ```bash
   npm install
   ```

2. **Start Development Server:**
   ```bash
   npm run dev
   ```

3. **Open Browser:**
   ```
   http://localhost:3000
   ```

### Production Deployment

1. **Install Dependencies:**
   ```bash
   npm install --production
   ```

2. **Start Production Server:**
   ```bash
   npm start
   ```

## 🌐 Deployment Options

### 1. **Render (Recommended - Free)**
- Go to [render.com](https://render.com)
- Connect your GitHub repository
- Select "Web Service"
- Build Command: `npm install`
- Start Command: `npm start`
- Your site will be live instantly!

### 2. **Railway (Free Tier)**
- Go to [railway.app](https://railway.app)
- Connect your GitHub repository
- Deploy automatically
- Get a custom domain

### 3. **Heroku (Free Tier)**
- Install Heroku CLI
- Run: `heroku create london-frontline-website`
- Run: `git push heroku main`
- Your site will be live!

### 4. **Vercel (Free)**
- Go to [vercel.com](https://vercel.com)
- Import your GitHub repository
- Deploy automatically
- Get custom domain

### 5. **Netlify (Free)**
- Go to [netlify.com](https://netlify.com)
- Drag and drop the `index.html` file
- Your site is live instantly!

## 📁 Project Structure

```
london-frontline-website/
├── index.html              # Main website file
├── server.js               # Express.js server
├── package.json            # Dependencies and scripts
├── README.md               # This file
└── assets/                 # Images and other assets (if any)
```

## 🔧 API Endpoints

- `GET /` - Main website
- `GET /health` - Health check
- `GET /api/info` - Server information

## 🎨 Customization

### Colors
- Primary Blue: `#1e3c72`
- Secondary Blue: `#2a5298`
- Gold Accent: `#ffd700`
- Orange Accent: `#ff6b35`

### Logo
- Crown symbol with "LONDON FRONTLINE" text
- Animated glow effects
- Professional gradient backgrounds

## 📱 Mobile Responsive

The website is fully responsive and works perfectly on:
- Desktop computers
- Tablets
- Mobile phones
- All modern browsers

## 🔒 Security Features

- Helmet.js security headers
- CORS protection
- Content Security Policy
- XSS protection
- NoSQL injection protection

## 🚔 Community Information

- **Discord**: [Join London Frontline](https://discord.gg/6WcxxJcCfT)
- **Server Type**: FiveM Roleplay
- **Location**: Central London
- **Departments**: Metropolitan Police, Fire Brigade, Ambulance Service
- **Status**: Recruiting

## 📞 Contact

- **Server Owner**: Jim, Benj.
- **Discord**: [EU/UK] London Frontline
- **Support**: Available 24/7 via Discord

## 🛠️ Development

### Prerequisites
- Node.js 14+ 
- npm or yarn

### Scripts
- `npm start` - Start production server
- `npm run dev` - Start development server with auto-reload
- `npm run deploy` - Deploy to production

### Environment Variables
- `PORT` - Server port (default: 3000)
- `NODE_ENV` - Environment (development/production)

## 📄 License

MIT License - Feel free to use and modify for your community!

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

---

**© 2025 [EU/UK] London Frontline. All rights reserved.**

*Professional Roleplay Community | FiveM Server* 