# Ritesh Zambre - Senior Data Scientist Portfolio Website

A premium, modern personal website showcasing expertise in Data Science, MLOps, Generative AI, and Agentic AI.

## 🚀 Features

### Core Features
- **Dark Theme Design**: Premium glassmorphism UI with electric blue accents
- **Fully Responsive**: Mobile-first design that looks perfect on all devices
- **Multi-Language Support**: English, German, French, Spanish, Japanese, and Chinese
- **Animated Background**: Interactive particle system in hero section
- **Smooth Animations**: Fade-in, slide-up effects with Intersection Observer
- **SEO Optimized**: Proper meta tags and semantic HTML

### Sections
1. **Hero Section**: Eye-catching introduction with animated particles
2. **Expertise Section**: 6 core competency areas with detailed descriptions
3. **Tech Stack Section**: Organized by categories (AI/ML, MLOps, Cloud, Data, Languages)
4. **Tools Section**: Placeholder for future AI tools and utilities
5. **Contact Section**: Multiple contact methods with downloadable documents
6. **Navigation**: Sticky navbar with smooth scroll and active section highlighting

### Interactive Elements
- Floating contact button (auto-hides on contact section)
- Hover effects with glow on all cards
- Mobile hamburger menu
- Language selector
- Smooth scroll navigation
- Download buttons for Resume and Cover Letter

## 📁 Project Structure

```
ritesh-portfolio-website/
├── index.html          # Main HTML file
├── styles.css          # All styles and responsive design
├── script.js           # JavaScript for interactivity and animations
├── assets/             # Folder for documents and images
│   ├── Ritesh_Zambre_Resume.pdf (TO ADD)
│   ├── Ritesh_Zambre_Cover_Letter.pdf (TO ADD)
│   └── profile.jpeg (TO ADD)
└── README.md           # This file
```

## 🛠️ Setup Instructions

### 1. Add Your Files
Place these files in the `assets/` folder:
- `Ritesh_Zambre_Resume.pdf` - Your resume
- `Ritesh_Zambre_Cover_Letter.pdf` - Your cover letter
- `profile.jpeg` - Your profile picture

### 2. Update Personal Information

#### In `index.html`:

**Contact Information** (around lines 340-390):
```html
<!-- Email -->
<a href="mailto:YOUR_EMAIL@email.com">YOUR_EMAIL@email.com</a>

<!-- WhatsApp -->
<a href="https://wa.me/YOUR_PHONE_NUMBER">+YOUR NUMBER</a>

<!-- LinkedIn -->
<a href="https://linkedin.com/in/YOUR_LINKEDIN">linkedin.com/in/YOUR_LINKEDIN</a>

<!-- GitHub -->
<a href="https://github.com/YOUR_GITHUB">github.com/in/YOUR_GITHUB</a>
```

**Profile Picture** (if you want to add it to hero section):
Add after line 60:
```html
<div class="hero-image">
    <img src="assets/profile.jpeg" alt="Ritesh Zambre">
</div>
```

### 3. Customize Content

#### Update Keywords (line 50-60):
```html
<div class="hero-keywords">
    <span class="keyword">Your Keyword 1</span>
    <span class="keyword">Your Keyword 2</span>
    <!-- Add more keywords -->
</div>
```

#### Update Tech Stack:
Modify the tech items in each category (lines 200-330) to match your actual skills.

#### Update Expertise Cards:
Customize the 6 expertise cards (lines 85-200) with your specific experience and technologies.

### 4. Optional Customizations

#### Change Color Scheme:
Edit `styles.css` root variables (lines 2-20):
```css
:root {
    --accent-primary: #6366f1;  /* Change to your preferred color */
    --accent-secondary: #8b5cf6;
    /* ... */
}
```

#### Add Profile Picture Styles:
Add to `styles.css`:
```css
.hero-image {
    width: 200px;
    height: 200px;
    border-radius: 50%;
    overflow: hidden;
    border: 4px solid var(--accent-primary);
    box-shadow: var(--shadow-glow);
    margin-bottom: 30px;
}

.hero-image img {
    width: 100%;
    height: 100%;
    object-fit: cover;
}
```

## 🌐 Deployment

### Option 1: GitHub Pages
1. Create a GitHub repository
2. Upload all files
3. Go to Settings → Pages
4. Select main branch
5. Your site will be live at `https://Ritesh0710.github.io/repository-name`

### Option 2: Netlify
1. Create account at netlify.com
2. Drag and drop the entire folder
3. Site goes live instantly
4. Custom domain available

### Option 3: Vercel
1. Create account at vercel.com
2. Import from GitHub or upload files
3. Automatic deployment

### Option 4: Traditional Hosting
Upload all files to your web hosting via FTP/cPanel file manager.

## 📱 Mobile Responsive Breakpoints

- **Desktop**: 1200px and above (full layout)
- **Tablet**: 968px - 1199px (adjusted grid)
- **Mobile**: 640px and below (single column, hamburger menu)

## 🎨 Design Specifications

### Typography
- **Font Family**: Inter (Google Fonts)
- **Hero Title**: 68px (desktop), 36px (mobile)
- **Section Titles**: 52px (desktop), 32px (mobile)
- **Body Text**: 17px
- **Line Height**: 1.7 for readability

### Colors
- **Background**: #0a0e1a (deep charcoal)
- **Cards**: rgba(20, 25, 37, 0.8) with glassmorphism
- **Accent**: #6366f1 (electric blue)
- **Text Primary**: #e2e8f0
- **Text Secondary**: #94a3b8

### Spacing
- **Section Padding**: 120px (desktop), 60px (mobile)
- **Card Gap**: 32px
- **Element Spacing**: Consistent 16px/24px/32px scale

## 🔧 Customization Tips

1. **Add New Sections**: Copy existing section structure and modify
2. **Add Tools**: Update the tools grid when ready to showcase your tools
3. **Blog Integration**: Can add a blog section using same card structure
4. **Analytics**: Add Google Analytics by including tracking code in `<head>`
5. **Contact Form**: Can integrate FormSpree, Netlify Forms, or custom backend

## 🌍 Supported Languages

The website includes translations for:
- 🇬🇧 English (default)
- 🇩🇪 German
- 🇫🇷 French
- 🇪🇸 Spanish
- 🇯🇵 Japanese
- 🇨🇳 Chinese

All translations are in `script.js` and can be edited in the `translations` object.

## ⚡ Performance

- **Lightweight**: Minimal dependencies, only Google Fonts
- **Fast Loading**: Optimized CSS and JavaScript
- **Smooth Animations**: GPU-accelerated transforms
- **Responsive Images**: Optimized for all screen sizes

## 🔒 Browser Compatibility

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📝 License

This is a personal portfolio website. Feel free to use the structure as inspiration for your own portfolio.

## 🆘 Support

For questions or issues:
1. Check this README first
2. Verify all files are in correct locations
3. Test in multiple browsers
4. Check browser console for JavaScript errors

## 🎯 Next Steps

1. ✅ Add your personal information
2. ✅ Upload resume, cover letter, and profile picture
3. ✅ Customize colors and content
4. ✅ Test on mobile devices
5. ✅ Deploy to your preferred platform
6. ✅ Share your new portfolio!

---

**Built with**: HTML5, CSS3, JavaScript (Vanilla)
**Design Philosophy**: Minimal, Professional, Future-focused
**Target Audience**: International clients seeking AI/ML expertise

Good luck with your international client outreach! 🚀
