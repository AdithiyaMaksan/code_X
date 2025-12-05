# CODE-X — Technology Services & Solutions Website

A responsive, professional static HTML website for technology service companies, startups, and freelancers. Complete with hero section, services, pricing tiers, testimonials, features, and mobile-optimized design. Deploy in minutes to GitHub Pages or any static hosting platform.

---

## 📋 Project Overview

**CODE-X** is a **technology services platform** offering web development, UX research, React Native app development, vulnerability management, and tech consultation services.

- **Purpose:** Ready-to-deploy corporate/service website template with hero, services, pricing, testimonials, and feature sections.
- **Stack:** Plain HTML5, CSS3 (Bootstrap), and vanilla JavaScript (no build tools required).
- **Status:** Fully functional, production-ready static site.
- **Target Audience:** Tech companies, startups, agencies, freelancers, service-based businesses.
- **Deployment:** GitHub Pages, Netlify, Vercel, Firebase, or any static host.

---

## 🎯 Features & Sections

### **Hero Section**
- Eye-catching banner with tagline: *"Bad times are just an illusion for the good times to show their face."*
- Email subscription form (ready to integrate with backend service)
- Value propositions: No software install, no cards required
- Parallax layered hero images for visual depth

### **Services Section (4 Cards)**
- **Goals** — Web development information and training
- **OptimalSort** — Optimization and sorting solutions
- **Influencing** — Youth technical skill development programs
- **Technology** — Latest tech news and industry insights
- Hover animations and icon-based design

### **About Sections (2 Parts)**

#### Part 1: "Get the Perfect Solution for Your Idea's"
- Integration with popular software platforms
- Instant crowdfunding platform creation
- Bullet points highlighting key benefits
- CTA: "Get Started" button

#### Part 2: "Your Vision, Our Solutions"
- Detailed service offerings:
  - UX Research
  - React Native App Development
  - Enterprise Vulnerability Management
  - Marketing & Brand Strategy
- Emphasizes exceeding client expectations
- Visual imagery with animations

### **Pricing Section (3 Tiers)**

| Plan | Price | Limit | Features |
|------|-------|-------|----------|
| **Standard** | ₹25,000/year | 3 purchases | Web Analytics, Mobile App Modeling, Self-help Resources |
| **Pro** | ₹50,000/year | 10 purchases | ✓ All Standard + Cyber Resilience, Product Design, Marketing |
| **Premium** | ₹125,000/year | Unlimited | ✓ All Pro + Work Framing, Info Architecture, Proactive Messaging |

Each plan includes a "SELECT" CTA button for easy purchasing.

### **Testimonials Section (Carousel)**
- **4 Customer Reviews** with photos and titles:
  - Arun A — CEO
  - Kamaleash VB — Founder
  - Gopika NR — Co-Founder
  - Abhishek Yadav — COO
- Auto-rotating Owl Carousel slider
- Social proof for credibility

### **Features Section (4 Feature Cards)**
- **API Management** — Secure Access, Connectivity, Engagement
- **Scheduled Reports** — Publishing, Influencer Tools, Content Creation, Brand Preparation
- **Compliance Controls** — Animations, 3D Viewer, Creation Tools, Packaging Designer
- **Authentication** — Print Services, Mockups, Statements, Recruitment Tools
- Gradient icon backgrounds for visual hierarchy

### **Footer**
- Company branding and description
- Quick links: Overview, Customer, Product
- Social media links (Facebook, Twitter, Pinterest)
- Copyright notice
- Newsletter subscription ready

---

## 🏗️ Technology Stack

### **Frontend**
- **HTML5** — Semantic, accessible markup
- **CSS3** — Bootstrap 4.x grid system, custom responsive styles, animations
- **JavaScript (Vanilla + jQuery)**

### **JavaScript Libraries & Plugins**
| Library | Purpose |
|---------|---------|
| jQuery 3.5.1 | DOM manipulation and AJAX |
| Bootstrap 4 | Responsive grid and components |
| Owl Carousel | Testimonials slider auto-rotation |
| WOW.js | Scroll-triggered animations |
| Parallax.js | Parallax scrolling effects |
| Fancybox | Lightbox gallery and image popups |
| Isotope | Portfolio filtering and masonry layout |
| CountUp.js | Animated number counters |
| Mean Menu | Mobile-responsive hamburger menu |
| Font Awesome 5 | Icon library (Pro & Free) |
| Elegant Font | Custom icon fonts |

### **CSS & Design**
- Bootstrap 5 grid system
- Animate.min.css for entrance animations
- Custom `style.css` with gradient colors, hover effects, spacing utilities
- Mobile-first responsive design
- Preloader animations

### **No Build Tools Required**
- Zero configuration needed
- Works directly in any browser
- No npm/yarn installation required
- CDN-ready external dependencies

---

## 📁 Folder Structure

```
d:\project 1\
├── index.html (main landing page)
├── about.html
├── contact.html
├── services.html
├── services-details.html
├── portfolio.html
├── portfolio-details.html
├── blog-standard.html
├── faq.html
├── sign-in.html
├── sign-up.html
├── product-details.html
├── product-details-2.html
├── privacy-policy.html
├── terms-condition.html
├── coming-soon.html
│
├── assets/ (Primary Theme Assets)
│   ├── css/
│   │   ├── bootstrap.min.css (Bootstrap 4 framework)
│   │   ├── style.css (Custom styles)
│   │   ├── animate.min.css (Animations)
│   │   ├── owl.carousel.min.css (Carousel styling)
│   │   ├── jquery.fancybox.min.css (Lightbox styling)
│   │   ├── meanmenu.css (Mobile menu)
│   │   ├── preloader.css (Loading animation)
│   │   ├── fontAwesome5Pro.css (Icon font)
│   │   ├── elegantFont.css (Custom icon font)
│   │   ├── backToTop.css (Scroll to top button)
│   │   └── default.css (Base styles)
│   │
│   ├── fonts/ (Typography)
│   │   ├── Font Awesome Pro icons
│   │   └── Custom web fonts
│   │
│   ├── img/ (Images organized by section)
│   │   ├── hero/home-1/ (Hero section images)
│   │   ├── about/home-1/ (About section images)
│   │   ├── services/ (Service icons and images)
│   │   ├── portfolio/details/ (Portfolio showcase)
│   │   ├── testimonial/home-1/ (Customer avatars)
│   │   ├── icon/ (Section icons)
│   │   ├── logo/ (Branding)
│   │   ├── blog/ (Blog post images)
│   │   ├── client/ (Client logos)
│   │   └── cta/ (Call-to-action sections)
│   │
│   └── js/ (JavaScript)
│       ├── main.js (Custom functionality)
│       ├── ajax-form.js (Form handling)
│       ├── backToTop.js (Scroll to top)
│       ├── parallax.min.js (Parallax effects)
│       ├── wow.min.js (Scroll animations)
│       ├── bootstrap.bundle.min.js (Bootstrap JS)
│       ├── owl.carousel.min.js (Carousel)
│       ├── jquery.fancybox.min.js (Lightbox)
│       ├── jquery.meanmenu.js (Mobile menu)
│       ├── isotope.pkgd.min.js (Portfolio filtering)
│       ├── jquery.counterup.min.js (Number animations)
│       ├── imagesloaded.pkgd.min.js (Image loading)
│       └── vendor/
│           ├── jquery-3.5.1.min.js
│           └── waypoints.min.js
│
├── assets2/ (Alternate Theme Assets)
│   ├── css/
│   │   ├── style.css
│   │   ├── plugins/ (jQuery UI, feature CSS, etc.)
│   │   └── vendor/ (Bootstrap, nice-select, odometer)
│   │
│   ├── fonts/
│   │
│   ├── images/ (Alternate image set)
│   │   ├── activity/
│   │   ├── banner/
│   │   ├── blog/
│   │   ├── collection/
│   │   ├── connect/
│   │   ├── profile/
│   │   └── portfolio/
│   │
│   └── js/
│       ├── main.js (Alternate main script)
│       └── vendor/ (Alternate JS libraries)
│
├── NFT Variant Pages (marked with "nft" suffix)
│   ├── index-six(nft).html
│   ├── about(nft).html
│   ├── author(nft).html
│   ├── collection(nft).html
│   ├── coming-soon(nft).html
│   ├── connect(nft).html
│   ├── contact(nft).html
│   ├── create(nft).html
│   ├── creator(nft).html
│   ├── edit-profile(nft).html
│   ├── explore-list-column-two(nft).html
│   ├── explore-list-style(nft).html
│   ├── explore-six(nft).html
│   ├── login(nft).html
│   ├── product-details(nft).html
│   ├── product(nft).html
│   ├── ranking(nft).html
│   ├── sign-up(nft).html
│   └── support(nft).html
│
└── README.md (This file)
```

**Note:** Both `assets/` and `assets2/` provide complete theme sets. The site uses `assets/` by default. NFT pages reference specialized designs for blockchain/NFT business models.

---

## 🚀 Quick Start

### **Option 1: Preview Locally (Recommended)**

Use Python to serve the site with a local HTTP server (best for testing AJAX, forms, and full functionality):

```powershell
Set-Location -Path "D:\project 1"
py -3 -m http.server 8000
```

Then open **http://localhost:8000** in your browser.

### **Option 2: Direct File Preview**

Simply double-click `index.html` or use PowerShell:

```powershell
Start-Process "D:\project 1\index.html"
```

**Note:** This works for basic viewing but may have limitations with AJAX and relative path handling.

### **Option 3: Use a Static Server (Node.js)**

If you prefer Node.js:

```bash
npm install -g http-server
cd "D:\project 1"
http-server -p 8000
```

---

## 🛠️ Customization Guide

### **Edit Homepage Content**
Open `index.html` and modify:
- **Hero section:** Line ~150 — title, subtitle, email form
- **Services:** Line ~200 — service cards and descriptions
- **Pricing:** Line ~350 — price tiers and features
- **Testimonials:** Line ~500 — customer quotes and avatars
- **Features:** Line ~600 — feature grid and descriptions

### **Change Colors & Branding**

**Primary CSS File:** `assets/css/style.css`

```css
/* Example: Change primary brand color */
:root {
  --primary-color: #0066ff; /* Change from default */
  --secondary-color: #ff6600;
  --text-color: #333;
}
```

### **Update Images**

Replace files in `assets/img/`:
- **Logo:** `assets/img/logo/logo.png`
- **Hero Images:** `assets/img/hero/home-1/hero-*.png`
- **Service Icons:** `assets/img/icon/services/home-1/`
- **Testimonial Photos:** `assets/img/testimonial/home-1/`
- **About Images:** `assets/img/about/home-1/`

### **Integrate with Backend**

#### Email Form (Hero Section)
In `index.html`, update the form `action` attribute:
```html
<form action="https://your-backend.com/subscribe" method="POST">
  <input type="email" placeholder="Enter your email.." name="email" required>
  <button type="submit" class="w-btn w-btn-2">search</button>
</form>
```

#### Contact Form
Update `contact.html` with your backend endpoint or use services like:
- Formspree
- Netlify Forms
- AWS Lambda
- Custom Node.js API

### **Add New Pages**

1. Duplicate an existing HTML file (e.g., `about.html`)
2. Update the page title and content
3. Link to it in the navigation menu in `index.html` (line ~80)

### **Mobile Menu Updates**
Edit the navigation menu in the sidebar (line ~320):
```html
<ul>
  <li><a href="index.html">Home</a></li>
  <li><a href="about.html">About</a></li>
  <!-- Add your menu items here -->
</ul>
```

---

## 🚢 Deployment Guide

### **Deploy to GitHub Pages**

1. **Initialize Git Repository:**
```powershell
Set-Location -Path "D:\project 1"
git init
git config user.name "Your Name"
git config user.email "your.email@example.com"
```

2. **Create Initial Commit:**
```powershell
git add .
git commit -m "Initial commit: CODE-X website"
```

3. **Create GitHub Repository:**
   - Go to https://github.com/new
   - Create repo named `code-x` (or your preferred name)
   - **Do NOT** initialize with README (you already have one)

4. **Add Remote & Push:**
```powershell
git remote add origin https://github.com/YOUR-USERNAME/code-x.git
git branch -M main
git push -u origin main
```

5. **Enable GitHub Pages:**
   - Go to your repo → **Settings** → **Pages**
   - Source: Select `main` branch, `/root` folder
   - Save
   - Site will be live at: `https://YOUR-USERNAME.github.io/code-x`

### **Deploy to Netlify**

1. Install Netlify CLI:
```bash
npm install -g netlify-cli
```

2. Deploy:
```powershell
cd "D:\project 1"
netlify deploy --prod --dir=.
```

3. Or drag and drop the folder to https://app.netlify.com/drop

### **Deploy to Vercel**

```bash
npm install -g vercel
cd "D:\project 1"
vercel --prod
```

### **Deploy to Traditional Hosting (Bluehost, GoDaddy, etc.)**

1. Compress all files: `project-1.zip`
2. Upload via FTP or cPanel File Manager to `public_html/`
3. Extract files
4. Visit your domain to see the live site

---

## 📝 SEO Optimization

The site is SEO-friendly with:
- ✅ Semantic HTML5 markup (`<header>`, `<main>`, `<section>`, `<footer>`)
- ✅ Meta tags for description and viewport
- ✅ Structured heading hierarchy (H1 → H2 → H3)
- ✅ Alt text on all images
- ✅ Mobile-responsive design (mobile-first)

### **Enhance SEO:**

Update meta tags in `index.html`:
```html
<meta name="description" content="CODE-X — Technology Services & Solutions. Web Development, App Development, UX Research, and more.">
<meta name="keywords" content="web development, app development, technology services, CODE-X">
<meta name="author" content="CODE-X Team">
```

Add to footer or `<head>`:
```html
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "LocalBusiness",
  "name": "CODE-X",
  "url": "https://yoursite.com"
}
</script>
```

---

## 🔧 Troubleshooting

| Issue | Solution |
|-------|----------|
| Images not loading | Check relative paths; ensure `assets/img/` folder exists |
| CSS not applying | Clear browser cache (Ctrl+F5) or use incognito mode |
| Form submission not working | Replace action URL with your backend endpoint |
| Mobile menu not working | Verify `assets/js/jquery.meanmenu.js` is loaded |
| Carousel not rotating | Ensure `assets/js/owl.carousel.min.js` is loaded before `main.js` |

---

## 📄 License & Credits

- **Template Author:** CODE-X Team
- **Framework:** Bootstrap 5, jQuery 3.5.1
- **Icons:** Font Awesome 5 Pro, Elegant Font
- **Libraries:** Owl Carousel, WOW.js, Fancybox, Isotope, Parallax.js
