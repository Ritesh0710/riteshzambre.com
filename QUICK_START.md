# 🚀 QUICK START GUIDE - Ritesh Zambre Portfolio Website

## ⚡ IMMEDIATE NEXT STEPS

### Step 1: Add Your Personal Files (2 minutes)

1. Create an `assets` folder (if not present)
2. Add these 3 files:
   - `Ritesh_Zambre_Resume.pdf` (your resume)
   - `Ritesh_Zambre_Cover_Letter.pdf` (your cover letter)
   - `profile.jpeg` (your profile picture - optional)

### Step 2: Update Contact Information (5 minutes)

Open `index.html` and find/replace:

1. **Email** (around line 350):
   ```html
   <!-- FIND THIS: -->
   <a href="mailto:riteshz.aiworks@gmail.com">riteshz.aiworks@gmail.com</a>
   
   <!-- REPLACE WITH YOUR EMAIL: -->
   <a href="mailto:youremail@domain.com">youremail@domain.com</a>
   ```

2. **WhatsApp** (around line 365):
   ```html
   <!-- FIND THIS: -->
   <a href="https://wa.me/917028224490">+91 70282 24490</a>
   
   <!-- REPLACE WITH YOUR NUMBER (no + sign, no spaces): -->
   <a href="https://wa.me/917028224490">+91 70282 24490</a>
   ```

3. **LinkedIn** (around line 380):
   ```html
   <!-- FIND THIS: -->
   <a href="https://linkedin.com/in/riteshz/">linkedin.com/in/riteshz/</a>
   
   <!-- REPLACE WITH YOUR LINKEDIN: -->
   <a href="https://linkedin.com/in/riteshz">linkedin.com/in/riteshz</a>
   ```

4. **GitHub** (around line 395):
   ```html
   <!-- FIND THIS: -->
   <a href="https://github.com/riteshzambre">github.com/riteshzambre</a>
   
   <!-- REPLACE WITH YOUR GITHUB: -->
   <a href="https://github.com/Ritesh0710">github.com/Ritesh0710</a>
   ```

### Step 3: Test Locally (3 minutes)

1. Double-click `index.html` to open in your browser
2. Check all sections look correct
3. Click all links to verify they work
4. Try the language selector
5. Test on your phone

### Step 4: Deploy Online (10 minutes)

Choose ONE of these options:

#### OPTION A: Netlify (Easiest - Recommended)
1. Go to [netlify.com](https://netlify.com)
2. Sign up for free account
3. Drag all website files (index.html, styles.css, script.js, assets folder) into Netlify
4. Done! Your site is live instantly
5. Optional: Add custom domain in settings

#### OPTION B: GitHub Pages (Free + Professional)
1. Create account at [github.com](https://github.com)
2. Create new repository named `portfolio`
3. Upload all files
4. Go to Settings → Pages
5. Select `main` branch → Save
6. Your site will be at: `https://Ritesh0710.github.io/portfolio`

#### OPTION C: Vercel (Alternative to Netlify)
1. Go to [vercel.com](https://vercel.com)
2. Sign up with GitHub account
3. Import your files
4. Deploy automatically

## 📱 MOBILE TESTING

Before going live, test on mobile:
1. Open website on your phone
2. Check if text is readable without zooming
3. Verify hamburger menu works
4. Test all buttons are tappable
5. Verify WhatsApp link opens WhatsApp app

## ✅ PRE-LAUNCH CHECKLIST

- [ ] Resume PDF added to assets folder
- [ ] Cover letter PDF added to assets folder
- [ ] Email address updated in index.html
- [ ] WhatsApp number updated and tested
- [ ] LinkedIn URL updated
- [ ] GitHub URL updated
- [ ] Tested website in browser
- [ ] Tested on mobile phone
- [ ] All links work correctly
- [ ] Language selector works
- [ ] Documents download correctly

## 🎨 OPTIONAL CUSTOMIZATIONS

### Change Colors
Edit `styles.css` (line 3-5):
```css
--accent-primary: #6366f1;  /* Change this color */
```

Try these colors:
- Purple: `#8b5cf6`
- Green: `#10b981`
- Orange: `#f59e0b`
- Red: `#ef4444`
- Teal: `#14b8a6`

### Add Your Photo to Hero Section
In `index.html`, add after line 60:
```html
<div class="hero-image">
    <img src="assets/profile.jpeg" alt="Ritesh Zambre">
</div>
```

Then add to `styles.css`:
```css
.hero-image {
    width: 200px;
    height: 200px;
    border-radius: 50%;
    overflow: hidden;
    border: 4px solid var(--accent-primary);
    margin: 0 auto 30px;
}
.hero-image img {
    width: 100%;
    height: 100%;
    object-fit: cover;
}
```

## 🆘 TROUBLESHOOTING

**Problem**: Resume won't download
- **Solution**: Make sure the PDF file is in the `assets` folder and named exactly `Ritesh_Zambre_Resume.pdf`

**Problem**: WhatsApp link doesn't work
- **Solution**: Format must be `https://wa.me/917028224490` (country code + number, no + or spaces)

**Problem**: Website looks broken on mobile
- **Solution**: The website is fully responsive. Try different browsers or clear cache.

**Problem**: Animations not working
- **Solution**: Make sure `script.js` is in the same folder as `index.html`

## 🎯 YOUR WEBSITE IS READY!

Once you've completed Steps 1-4 above, you're ready to start attracting international clients! 🚀

**Next Steps After Deployment:**
1. Add website URL to LinkedIn profile
2. Include in email signature
3. Add to resume header
4. Share with your network
5. Update regularly with new projects and tools

Good luck landing those high-value international projects! 💼✨
