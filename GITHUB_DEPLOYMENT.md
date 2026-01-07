# 🚀 Deploy AutoVista to GitHub Pages

## Quick Guide (No Git Installation Required)

### Step 1: Create GitHub Repository

1. **Go to GitHub**: https://github.com/new
2. **Repository name**: `autovista` (or any name you prefer)
3. **Description**: "Modern automobile marketplace for Cars & Bikes"
4. **Visibility**: Public (required for free GitHub Pages)
5. **Initialize**: ❌ Do NOT check "Add a README file"
6. Click **"Create repository"**

### Step 2: Upload Your Files

**Option A: Drag & Drop (Easiest)**
1. On your new repository page, click **"uploading an existing file"**
2. Open File Explorer: `c:\Users\Yugant\autovista`
3. Select ALL files and folders (Ctrl+A)
4. Drag them into the GitHub upload area
5. Add commit message: "Initial commit - AutoVista website"
6. Click **"Commit changes"**

**Option B: Using GitHub Desktop (Alternative)**
1. Download GitHub Desktop: https://desktop.github.com/
2. Clone your repository
3. Copy all files from `c:\Users\Yugant\autovista` to the cloned folder
4. Commit and push

### Step 3: Enable GitHub Pages

1. Go to your repository **Settings** tab
2. Click **"Pages"** in the left sidebar
3. Under "Source":
   - Branch: Select **`main`** (or `master`)
   - Folder: Select **`/ (root)`**
4. Click **"Save"**
5. Wait 1-2 minutes for deployment

### Step 4: Access Your Live Site

Your site will be available at:
```
https://YOUR-USERNAME.github.io/autovista/
```

Example: `https://yugant.github.io/autovista/`

---

## 📋 Files to Upload

Make sure these files are uploaded:

```
✅ index.html
✅ cars.html
✅ bikes.html
✅ detail.html
✅ compare.html
✅ reviews.html
✅ README.md
✅ .gitignore
✅ assets/
   ✅ css/
      ✅ variables.css
      ✅ style.css
   ✅ js/
      ✅ data.js
      ✅ app.js
   ✅ images/
      ✅ hero-bg.jpg
      ✅ car_placeholder.jpg
      ✅ bike_placeholder.jpg
```

---

## 🔧 Troubleshooting

**Issue**: "404 - File not found"
- **Fix**: Make sure `index.html` is in the root folder, not in a subfolder

**Issue**: "CSS/Images not loading"
- **Fix**: All paths are already relative, so this should work automatically

**Issue**: "Page not updating"
- **Fix**: 
  1. Clear browser cache (Ctrl+Shift+R)
  2. Wait 2-3 minutes for GitHub to rebuild
  3. Check the "Actions" tab for deployment status

---

## 🎯 Custom Domain (Optional)

Want `autovista.com` instead of `username.github.io/autovista`?

1. Buy a domain from Namecheap/GoDaddy (~$10/year)
2. In GitHub Pages settings, add your custom domain
3. Update DNS records at your domain registrar
4. GitHub provides free SSL certificate automatically!

---

## 🔄 Updating Your Site

**Method 1: Web Interface**
1. Go to your repository
2. Click on the file you want to edit
3. Click the pencil icon (Edit)
4. Make changes
5. Commit changes

**Method 2: Re-upload**
1. Make changes locally
2. Go to repository → "Add file" → "Upload files"
3. Drag updated files
4. Commit

---

## ✅ Verification Checklist

After deployment, test:
- [ ] Homepage loads correctly
- [ ] Navigation works (Cars, Bikes, Compare, Reviews)
- [ ] Vehicle cards display properly
- [ ] Detail page works (click any vehicle)
- [ ] Mobile responsive (resize browser)
- [ ] Images load correctly
- [ ] Search box displays properly

---

## 🚀 Your Site is Live!

Once deployed, share your link:
- 📱 Social Media
- 💼 LinkedIn Portfolio
- 📧 Email Signature
- 📝 Resume/CV

**Congratulations! Your AutoVista website is now live on the internet!** 🎉
