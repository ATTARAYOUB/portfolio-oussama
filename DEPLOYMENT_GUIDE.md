# 🚀 Deployment Guide - Oussama Kirene Portfolio

Your enhanced portfolio is ready to deploy! Follow these steps to get your site live on GitHub and Vercel.

## 📋 Prerequisites

- GitHub account: https://github.com
- Vercel account: https://vercel.com (free)
- Git installed on your computer

## 🔧 Step 1: Create GitHub Repository

### Option A: Using GitHub Web Interface (Easiest)

1. Go to https://github.com/new
2. **Repository name:** `oussama-kirene-portfolio`
3. **Description:** Professional portfolio for Oussama Kirene - Automotive Technician
4. **Visibility:** Public
5. **Initialize with:** Leave unchecked (we already have files)
6. Click **Create repository**

### Option B: Using GitHub CLI

```bash
gh repo create oussama-kirene-portfolio --public --source=. --remote=origin --push
```

## 📤 Step 2: Push Code to GitHub

### From Command Line (Windows PowerShell/CMD)

```bash
# Navigate to your portfolio folder
cd "C:\Users\THE BOSS\Desktop\all-files"

# Add GitHub remote (replace YOUR_USERNAME with your GitHub username)
git remote add origin https://github.com/ATTARAYOUB/oussama-kirene-portfolio.git

# Rename branch to main (if needed)
git branch -M main

# Push to GitHub
git push -u origin main
```

### Verify Push

Visit: `https://github.com/ATTARAYOUB/oussama-kirene-portfolio`

You should see all your files there!

## 🌐 Step 3: Deploy to Vercel

### Option A: Using Vercel Web Interface (Recommended)

1. Go to https://vercel.com/dashboard
2. Click **Add New** → **Project**
3. Click **Import Git Repository**
4. Paste: `https://github.com/ATTARAYOUB/oussama-kirene-portfolio`
5. Click **Import**
6. **Framework Preset:** Select "Other" (it's static HTML)
7. **Build Command:** Leave empty
8. **Output Directory:** Leave empty
9. Click **Deploy**

**Wait 1-2 minutes for deployment...**

### Option B: Using Vercel CLI

```bash
# Install Vercel CLI
npm install -g vercel

# Deploy from your project folder
cd "C:\Users\THE BOSS\Desktop\all-files"
vercel

# Follow the prompts
```

## ✅ Step 4: Verify Deployment

After deployment completes, Vercel will show you:
- **Production URL:** `https://oussama-kirene-portfolio.vercel.app`
- **Git Integration:** Connected to your GitHub repo

### Test Your Live Site

1. Visit: https://oussama-kirene-portfolio.vercel.app
2. Test features:
   - ✓ Bilingual toggle (FR/EN)
   - ✓ Smooth scrolling
   - ✓ Back-to-top button
   - ✓ Download CV button
   - ✓ WhatsApp contact link
   - ✓ Mobile responsiveness
   - ✓ Print preview (Ctrl+P)

## 🔄 Step 5: Set Up Auto-Deployment

Your portfolio is now set up for **automatic deployment**:

- Every time you push to GitHub, Vercel automatically deploys
- No manual steps needed
- Deployment takes 1-2 minutes

### To Update Your Portfolio

```bash
# Make changes to files
# Then:
git add .
git commit -m "Update portfolio content"
git push origin main

# Vercel automatically deploys!
```

## 🎯 Optional: Custom Domain

To use your own domain (e.g., `oussama-kirene.com`):

1. In Vercel Dashboard → Project Settings → Domains
2. Add your custom domain
3. Update DNS records at your domain registrar
4. Vercel provides DNS instructions

## 📊 Monitoring & Analytics

### Vercel Dashboard

- View deployment history
- Check build logs
- Monitor performance
- See analytics

### GitHub Repository

- Track changes with commits
- Manage versions
- Collaborate with others

## 🐛 Troubleshooting

### Deployment Failed

**Check:**
1. All files are committed: `git status`
2. No large files (>100MB)
3. vercel.json is valid JSON
4. index.html exists in root

### Site Shows 404

**Solution:**
1. Verify files uploaded to Vercel
2. Check Vercel deployment logs
3. Clear browser cache (Ctrl+Shift+Delete)

### Images Not Loading

**Check:**
1. Image filenames match exactly (case-sensitive)
2. Images are in the same folder as index.html
3. File paths in HTML are correct

## 📝 File Checklist

Your deployment includes:

- ✅ `index.html` - Main portfolio (49 KB)
- ✅ `cv.html` - CV page (7.8 KB)
- ✅ `cv.pdf` - Downloadable CV (136 KB)
- ✅ `photo_4k_final.png` - Profile photo (8.8 MB)
- ✅ `README.md` - Project documentation
- ✅ `vercel.json` - Deployment configuration
- ✅ `.gitignore` - Git ignore rules

## 🎉 You're Live!

Your portfolio is now live at:
### 🌐 https://oussama-kirene-portfolio.vercel.app

### Share Your Portfolio

- **LinkedIn:** Add to profile
- **Email:** Include in job applications
- **GitHub:** Link in bio
- **WhatsApp:** Share with contacts

## 📞 Support

If you need help:

1. **Vercel Docs:** https://vercel.com/docs
2. **GitHub Docs:** https://docs.github.com
3. **Portfolio Issues:** Check browser console (F12)

## 🔐 Security Notes

Your portfolio is:
- ✅ HTTPS encrypted
- ✅ No sensitive data stored
- ✅ Static files only (no backend)
- ✅ Safe for all users

## 🚀 Next Steps

1. ✅ Deploy to GitHub
2. ✅ Deploy to Vercel
3. ✅ Test all features
4. ✅ Share your portfolio
5. ✅ Update content as needed

---

**Deployment Date:** May 18, 2026  
**Status:** Ready for Production  
**Version:** 2.0 Enhanced
