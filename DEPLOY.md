# Free Deployment Options

## 1. Vercel (Recommended)
```bash
npm install -g vercel
vercel --prod
```
- Frontend + API in one deployment
- Automatic HTTPS
- Global CDN

## 2. Railway
```bash
# Install Railway CLI
npm install -g @railway/cli
railway login
railway init
railway up
```
- Full-stack deployment
- Automatic builds
- Free tier: 500 hours/month

## 3. Render
1. Connect GitHub repo to Render
2. Create Web Service
3. Use render.yaml config
- Free tier: 750 hours/month
- Auto-deploy from Git

## 4. Netlify (Frontend only)
```bash
npm install -g netlify-cli
cd frontend
npm run build
netlify deploy --prod --dir=.next
```

## 5. Heroku
```bash
# Install Heroku CLI
heroku create your-app-name
git push heroku main
```

## Quick Setup:
1. Push code to GitHub
2. Connect to Vercel/Railway/Render
3. Deploy automatically

**Login:** demo / demo123