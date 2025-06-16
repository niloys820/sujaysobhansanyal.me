# Sujay Sobhan Sanyal Memorial Website

A compassionate digital memorial website dedicated to Sujay Sobhan Sanyal, featuring dynamic color palettes, memorial video tribute, and comprehensive accessibility support.

## 🌟 Features

- **Memorial Video Hero Section** - Story narrated in Sujay's own voice
- **Dynamic Emotional Color Palettes** - 5 mood-based color schemes with smooth transitions
- **Quote Carousel** - 10-second auto-rotation with manual navigation
- **Site-wide Wake Lock** - Prevents screen sleep during memorial viewing
- **Full Accessibility** - Screen reader support, keyboard navigation, ARIA landmarks
- **Responsive Design** - Mobile-first approach for all devices
- **Cross-browser Compatibility** - Works on iOS/Android, Chrome/Safari

## 🚀 Quick Deploy to GitHub Pages

### Step 1: Create GitHub Repository

1. Go to [GitHub](https://github.com) and sign in
2. Click the **"+" icon** → **"New repository"**
3. Repository name: `sujaysobhansanyal.me`
4. Set to **Public** (required for GitHub Pages)
5. Click **"Create repository"**

### Step 2: Upload Files

**Option A: GitHub Website Upload**
1. In your new repository, click **"uploading an existing file"**
2. Drag and drop all files from the `github-deploy` folder
3. Write commit message: "Initial memorial website upload"
4. Click **"Commit changes"**

**Option B: Git Commands** (if you have Git installed)
```bash
# In the github-deploy folder
git init
git add .
git commit -m "Initial memorial website upload"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/sujaysobhansanyal.me.git
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository → **Settings** tab
2. Scroll down to **"Pages"** in the left sidebar
3. Under **"Source"**, select **"GitHub Actions"**
4. The deployment will start automatically

### Step 4: Access Your Website

Your memorial website will be available at:
- `https://YOUR_USERNAME.github.io/sujaysobhansanyal.me/`
- Or your custom domain if configured

## 🌐 Custom Domain Setup (Optional)

### For sujaysobhansanyal.me domain:

1. **Configure DNS** (at your domain registrar):
   - Add CNAME record: `www` → `YOUR_USERNAME.github.io`
   - Add A records for apex domain:
     ```
     185.199.108.153
     185.199.109.153
     185.199.110.153
     185.199.111.153
     ```

2. **Configure GitHub Pages**:
   - Repository Settings → Pages
   - Custom domain: `sujaysobhansanyal.me`
   - Check "Enforce HTTPS"
   - Save changes

## 🔧 Local Development

### Prerequisites
- Node.js 18 or higher
- npm or yarn

### Setup
```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

## 📁 Project Structure

```
├── client/                 # Frontend React application
│   ├── src/
│   │   ├── pages/          # Page components
│   │   ├── components/     # Reusable UI components
│   │   └── lib/           # Utility functions
│   └── index.html         # Main HTML template
├── server/                # Backend Express server (development only)
├── shared/                # Shared types and schemas
├── .github/workflows/     # GitHub Actions deployment
└── README.md             # This file
```

## 🎨 Color Palette System

The website features 5 emotional color palettes that automatically transition based on quote content:

- **Peaceful** - Soft blues and whites
- **Reflective** - Warm grays and earth tones
- **Hopeful** - Gentle greens and light blues
- **Warm** - Sunset oranges and warm yellows
- **Serene** - Deep blues and purples

## 🔒 Wake Lock Feature

The memorial website includes site-wide wake lock functionality to prevent screen sleep during viewing, ensuring an uninterrupted memorial experience.

## ♿ Accessibility Features

- **Screen Reader Support** - Full compatibility with assistive technologies
- **Keyboard Navigation** - Navigate carousel with arrow keys, Home/End
- **ARIA Landmarks** - Proper headings and regions
- **Semantic HTML** - Meaningful structure for all users
- **High Contrast** - Readable text in all color palettes

## 📱 Mobile Optimization

- Touch-friendly navigation
- Responsive video player
- Optimized carousel for mobile devices
- Cross-device compatibility testing

## 🚨 Troubleshooting

### Common Issues:

1. **Deployment Failed**
   - Check GitHub Actions tab for error details
   - Ensure all files are uploaded correctly
   - Verify repository is public

2. **Website Not Loading**
   - Wait 5-10 minutes for deployment to complete
   - Check GitHub Pages settings
   - Clear browser cache

3. **Custom Domain Issues**
   - Verify DNS settings with your domain registrar
   - Allow 24-48 hours for DNS propagation
   - Check GitHub Pages custom domain configuration

## 📞 Support

For technical issues or questions about the memorial website, please check the GitHub Issues section of this repository.

---

*In loving memory of Sujay Sobhan Sanyal (July 10, 1938 - June 03, 2025)*