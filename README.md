# potfolio
# Mahidhar Reddy - Portfolio Website

A modern, responsive portfolio website showcasing AI/ML projects and full-stack development skills.

## 🚀 Quick Start

1. **Download all files** from this folder:
   - `index.html`
   - `styles.css`
   - `script.js`

2. **Add your profile photo**:
   - Save your professional photo as `your-photo.jpg` in the same folder
   - Or rename it to match the filename in line 66 of `index.html`
   - Recommended: Square photo, at least 800x800px for best quality

3. **Open the website**:
   - Simply double-click `index.html` to view it in your browser
   - Or right-click and choose "Open with" your preferred browser

## 📝 Customization Guide

### Replace Your Photo

In `index.html`, find this line (around line 66):
```html
<img src="your-photo.jpg" alt="Mahidhar Reddy - AI Engineer" class="profile-photo">
```

Replace `your-photo.jpg` with your actual photo filename. For example:
```html
<img src="mahidhar-profile.jpg" alt="Mahidhar Reddy - AI Engineer" class="profile-photo">
```

**Photo Tips:**
- Use a professional headshot or profile picture
- Square aspect ratio works best (1:1)
- High resolution: at least 800x800 pixels
- File formats: JPG, PNG, or WebP
- File size: Keep under 500KB for faster loading

### Update Contact Form (Optional)

The contact form currently simulates submission. To connect it to a real backend:

1. **Option A - Use a Form Service:**
   - [Formspree](https://formspree.io/) - Free tier available
   - [EmailJS](https://www.emailjs.com/) - Send emails from JavaScript
   - [Netlify Forms](https://www.netlify.com/products/forms/) - If hosting on Netlify

2. **Option B - Add Your Own Backend:**
   - Update the form submission handler in `script.js` (line 104)
   - Replace the simulated API call with your actual endpoint

### Update Resume Download Link

The resume download button currently points to `/mnt/user-data/uploads/resume__1_.pdf`. 

To fix this:
1. Copy your resume PDF to the same folder as your website files
2. Rename it to something simple like `mahidhar-resume.pdf`
3. In `index.html`, find line 450 and update:
```html
<a href="mahidhar-resume.pdf" class="btn btn-primary" download>
```

## 🌐 Deployment Options

### Option 1: GitHub Pages (Free & Recommended)
1. Create a GitHub repository
2. Upload all files (including your photo)
3. Go to Settings → Pages
4. Select main branch as source
5. Your site will be live at `username.github.io/repository-name`

### Option 2: Netlify (Free)
1. Sign up at [netlify.com](https://www.netlify.com/)
2. Drag and drop your folder
3. Your site goes live instantly
4. Get a custom domain or use the free .netlify.app subdomain

### Option 3: Vercel (Free)
1. Sign up at [vercel.com](https://vercel.com/)
2. Import from GitHub or upload directly
3. Automatic deployments on updates
4. Free SSL and custom domain support

### Option 4: Traditional Web Hosting
Upload all files to your hosting provider via FTP/cPanel file manager.

## 📂 File Structure

```
portfolio/
│
├── index.html          # Main HTML file
├── styles.css          # All styling
├── script.js           # Interactive features
├── your-photo.jpg      # Your profile photo (add this)
└── mahidhar-resume.pdf # Your resume PDF (add this)
```

## ✨ Features

- **Fully Responsive** - Works on all devices (desktop, tablet, mobile)
- **Smooth Animations** - Professional transitions and effects
- **Interactive Navigation** - Active link highlighting and smooth scrolling
- **Contact Form** - Ready to connect to your backend
- **Project Showcase** - Highlight your best work with detailed stats
- **Skills Display** - Organized by category with hover effects
- **Resume Timeline** - Professional experience and education layout
- **Social Links** - Direct links to LinkedIn, GitHub, LeetCode, HackerRank

## 🎨 Color Customization

To change the color scheme, edit the CSS variables at the top of `styles.css`:

```css
:root {
    --color-primary: #2563eb;        /* Main blue */
    --color-primary-dark: #1e40af;   /* Darker blue */
    --color-secondary: #06b6d4;      /* Cyan accent */
    --color-accent: #8b5cf6;         /* Purple accent */
}
```

## 🔧 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 📧 Support

If you have questions or need help customizing:
- Email: mahidarreddy.2005@gmail.com
- LinkedIn: [Mahidhar Reddy](https://www.linkedin.com/in/mahidhar-reddy-illuri-7a7056264/)

## 📄 License

This portfolio template is free to use for personal projects.

---

**Built with ❤️ using HTML, CSS, and JavaScript**
