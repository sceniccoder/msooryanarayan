# Netlify Deployment for Portfolio

This directory contains the portfolio website for deployment on Netlify.

## Files Structure
- `index.html` - Main portfolio page (deployment version)
- `portfolio-premium.html` - Original portfolio file (backup)
- `netlify.toml` - Netlify configuration
- `assets/` - Images, resume, and project screenshots

## Deployment Instructions

### Option 1: Drag & Drop (Easiest)
1. Go to https://app.netlify.com/drop
2. Drag the entire `first` folder to the upload area
3. Your site will be live instantly!

### Option 2: GitHub Integration
1. Push this folder to a GitHub repository
2. Connect the repo to Netlify
3. Netlify will auto-deploy on every push

### Option 3: Netlify CLI
```bash
# Install Netlify CLI
npm install -g netlify-cli

# Login to Netlify
netlify login

# Deploy
netlify deploy --prod --dir=.
```

## Important Notes
- Make sure `assets/` folder contains your images before deploying
- Images should be in `.jpeg` format as configured
- Resume PDF should be at `assets/resume.pdf`

## Custom Domain Setup
1. Go to Netlify Dashboard → Domain Settings
2. Add your custom domain
3. Update DNS records as instructed by Netlify
