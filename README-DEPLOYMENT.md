# Dracula Token - Deployment Guide

## 🚀 Deployment Instructions for draculatokens.com

### 📁 Files Structure
```
website dracula 2/
├── index.html          # Main website page
├── blog.html           # Blog page with CMS
├── logo.png            # Dracula Token logo
└── README-DEPLOYMENT.md # This file
```

### 🌐 Domain Configuration
- **Main Domain:** `draculatokens.com`
- **Main Page:** `index.html` → `https://draculatokens.com`
- **Blog Page:** `blog.html` → `https://draculatokens.com/blog.html`

### 🔧 Technical Requirements

#### 1. Web Server Configuration
- **Static Hosting:** Any static web server (Apache, Nginx, GitHub Pages, Netlify, Vercel)
- **HTTPS Required:** SSL certificate mandatory
- **MIME Types:** Ensure `.html` files serve as `text/html`

#### 2. File Upload
Upload ALL files to the root directory of your hosting:
```
draculatokens.com/
├── index.html
├── blog.html
└── logo.png
```

### 🎯 Deployment Options

#### Option 1: Traditional Hosting (cPanel/Plesk)
1. Login to your hosting control panel
2. Go to File Manager
3. Upload all files to public_html or www root
4. Ensure index.html is set as default page

#### Option 2: GitHub Pages
1. Create a new repository: `dracula-token-website`
2. Upload all files to the repository
3. Go to Settings → Pages
4. Source: Deploy from a branch → Main branch
5. Your site will be live at: `https://username.github.io/dracula-token-website`
6. Configure custom domain: `draculatokens.com`

#### Option 3: Netlify
1. Sign up at netlify.com
2. Drag & drop the folder containing all files
3. Your site will be live instantly with a random URL
4. Go to Site settings → Domain management → Add custom domain
5. Add `draculatokens.com` and follow DNS instructions

#### Option 4: Vercel
1. Sign up at vercel.com
2. Import project from files
3. Deploy automatically
4. Add custom domain in project settings

### 🔍 SEO & Meta Tags Configuration

All meta tags are already configured:
- ✅ Open Graph tags for social sharing
- ✅ Twitter Card meta tags
- ✅ Proper titles and descriptions
- ✅ URLs set to `https://draculatokens.com`

### 📱 Mobile Responsiveness
- ✅ Fully responsive design
- ✅ Touch-friendly interface
- ✅ Optimized for all screen sizes

### 🎵 Audio System
- ✅ Horror ambience sounds
- ✅ Multiple simultaneous audio tracks
- ✅ User interaction required for autoplay (browser policy)

### 📝 Blog System Features
- ✅ User registration & login
- ✅ Create, edit, delete posts
- ✅ Categories and search functionality
- ✅ Local storage for data persistence

### 🔐 Security Notes
- Passwords are base64 encoded (basic security)
- For production, consider server-side authentication
- All data stored in browser localStorage

### ⚡ Performance Optimization
- ✅ Optimized images
- ✅ Minified CSS/JS where possible
- ✅ CDN resources used (Google Fonts, Font Awesome, TailwindCSS)
- ✅ Lazy loading with AOS animations

### 🌍 Browser Compatibility
- ✅ Chrome/Chromium (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Mobile browsers

### 📞 Support
If you encounter any issues during deployment:
1. Check browser console for errors (F12)
2. Ensure all files are uploaded correctly
3. Verify file permissions (644 for files, 755 for directories)
4. Test with different browsers

### 🎉 Post-Deployment Checklist
- [ ] Website loads correctly at `https://draculatokens.com`
- [ ] Blog loads at `https://draculatokens.com/blog.html`
- [ ] All navigation links work
- [ ] Audio system functions
- [ ] Blog registration/login works
- [ ] Mobile version works correctly
- [ ] SSL certificate is active
- [ ] Social media previews work

---

**🦇 Your Dracula Token website is ready for deployment! 🦇**

For any issues, check the browser console or contact support.
