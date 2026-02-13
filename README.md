# 🚀 Shridhar Shinde - Portfolio Website

A modern, visually striking portfolio website showcasing web development skills, projects, and professional experience. Features an editorial-inspired aesthetic with bold typography, sophisticated animations, and a unique design system.

## 👨‍💻 About

This portfolio website represents Shridhar Shinde's journey as a Web Development Intern at Prodigy InfoTech, with over 8 years of professional experience across web development, project management, and customer service. The site showcases technical skills, featured projects, and professional background in an engaging and interactive format.

## ✨ Features

### Design Highlights
- **Editorial-Inspired Aesthetic**: Professional layout with Playfair Display headlines and DM Sans body text
- **Distinctive Color Palette**: Navy blue (#0A0E27), cream (#F5F1E8), and coral accent (#FF6B35)
- **Advanced Animations**: Smooth entrance animations, hover effects, and scroll-triggered reveals
- **Unique Profile Frame**: Geometric photo frame with offset coral shadow and rotating experience badge

### Sections Overview

#### 🏠 Hero Section
- Professional headline: "Crafting Digital Experiences"
- Current role displayed: Web Development Intern @ Prodigy InfoTech
- Educational background: BCA in Computer Science
- Core technology stack: Python, CSS, JavaScript, HTML, PHP
- Dual call-to-action buttons for projects and contact

#### 👤 About Me
- Comprehensive professional summary highlighting 8+ years of experience
- Career journey from retail management to tech
- Visual timeline showcasing:
  - **Current**: Web Development Intern at Prodigy InfoTech (2026-Present)
  - **Previous**: Back Office Executive at Addnectar Solutions (2021-2026)
  - **Education**: BCA from Tilak Maharashtra Vidyapeeth, Pune (8.3 CGPA)

#### 💼 Featured Projects

**1. Form Builder Lite**
- Technologies: PHP, MySQL, HTML, CSS
- Dynamic Google Forms-like system
- [View on GitHub](https://github.com/shindeshridhar07-walle/form-builder.git)

**2. Interactive E-Commerce Navigation Menu**
- Technologies: HTML, CSS, JavaScript
- Responsive navigation with dynamic scroll effects and smooth animations
- [View on GitHub](https://github.com/shindeshridhar07-walle/PRODIGY_WD_01.git)

**3. Premium Stopwatch Web Application**
- Technologies: HTML, CSS, JavaScript
- Black-themed stopwatch with lap tracking and neon effects
- [View on GitHub](https://github.com/shindeshridhar07-walle/PRODIGY_WD_02.git)

#### 🛠️ Skills & Technologies
Organized into 6 categories:
- **Frontend**: React, Vue.js, TypeScript, Next.js, Tailwind CSS, SASS
- **Backend**: Node.js, Python, Django, RESTful APIs, GraphQL, PostgreSQL, MongoDB
- **DevOps**: AWS, Azure, Docker, Kubernetes, CI/CD, Git, Testing
- **Design**: UI/UX, Figma, Adobe XD, Responsive Design, Accessibility
- **Mobile**: React Native, PWA, Mobile-First Design, Flutter
- **Other**: Agile, Code Review, Technical Writing, Performance Optimization

#### 📧 Contact Section
- **Email**: shindeshridhar07@gmail.com
- **Phone**: +91 76203 72780
- **Location**: Mumbai, India
- **GitHub**: [shindeshridhar07-walle](https://github.com/shindeshridhar07-walle)
- **LinkedIn**: [shridhar-shinde](https://www.linkedin.com/in/shridhar-shinde)

### Technical Features
- ✅ Fully responsive design (mobile, tablet, desktop)
- ✅ Smooth scroll navigation between sections
- ✅ Intersection Observer API for scroll-triggered animations
- ✅ CSS keyframe animations and transitions
- ✅ Semantic HTML5 markup
- ✅ Vanilla JavaScript (no framework dependencies)
- ✅ Optimized performance
- ✅ Cross-browser compatible

## 🚀 Quick Start

### View the Website

1. **Download the file**
   ```bash
   git clone <repository-url>
   ```

2. **Ensure your image is in place**
   - Make sure `shridhar profile.jpg` is in the same directory as the HTML file

3. **Open in browser**
   - Double-click `portfolio.html`
   - Or right-click → Open With → Your preferred browser

## 📁 File Structure

```
portfolio/
│
├── portfolio.html           # Main website file
├── shridhar profile.jpg    # Profile photo
└── README.md               # This file
```

## 🎨 Design System

### Color Palette
```css
--primary: #0A0E27      /* Navy blue - Headers & important elements */
--secondary: #F5F1E8    /* Cream - Backgrounds */
--accent: #FF6B35       /* Coral - CTAs & highlights */
--accent-dark: #C44D2C  /* Darker coral - Hover states */
--text: #2C3E50         /* Dark gray - Body text */
--text-light: #5A6C7D   /* Medium gray - Secondary text */
```

### Typography
- **Display Font**: Playfair Display (Headlines)
- **Body Font**: DM Sans (Paragraphs)
- **Monospace Font**: Fira Code (Technical elements)

### Spacing
- Section padding: 8rem vertical
- Grid gaps: 3rem - 6rem
- Element spacing: Multiples of 0.5rem

## 🔧 Customization Guide

### Update Profile Photo
Replace the image source in the hero section (line ~1078):
```html
<img src="your-new-photo.jpg" alt="Shridhar Shinde">
```

**Recommended specs:**
- Format: JPG or PNG
- Dimensions: 500x600px (portrait)
- File size: Under 500KB

### Update Experience Badge
Modify the floating badge text (line ~1079):
```html
<div class="floating-badge">Your Years</div>
```

### Add More Projects
Copy a project card block and modify:
```html
<div class="project-card">
    <div class="project-image">🚀</div>
    <div class="project-content">
        <div class="project-tags">
            <span class="project-tag">Tech1</span>
            <span class="project-tag">Tech2</span>
        </div>
        <h3 class="project-title">Project Name</h3>
        <p class="project-description">Description...</p>
        <a href="link" class="project-link">View Project →</a>
    </div>
</div>
```

### Update Contact Information
Modify the contact section (lines ~1318-1330):
```html
<a href="mailto:your.email@example.com" class="contact-method">
    <span class="contact-icon">📧</span>
    <span>your.email@example.com</span>
</a>
```

### Customize Colors
Update CSS variables at the top (lines ~10-17):
```css
:root {
    --primary: #YourColor;
    --accent: #YourAccent;
    /* etc */
}
```

## 📱 Responsive Breakpoints

- **Desktop**: > 1024px (Full layout)
- **Tablet**: 768px - 1024px (2-column grids become single column)
- **Mobile**: < 768px (Optimized mobile experience)

## 🚀 Deployment Options

### Option 1: GitHub Pages (Recommended)
1. Create a GitHub repository
2. Upload files (rename HTML to `index.html`)
3. Go to Settings → Pages
4. Select main branch → Save
5. Access at: `https://yourusername.github.io/repo-name`

### Option 2: Netlify
1. Sign up at [netlify.com](https://netlify.com)
2. Drag and drop your files
3. Instant deployment with HTTPS
4. Optional: Connect custom domain

### Option 3: Vercel
1. Sign up at [vercel.com](https://vercel.com)
2. Import your repository
3. Deploy with automatic HTTPS
4. Optional: Custom domain

### Option 4: Traditional Hosting
1. Purchase hosting and domain
2. Upload files via FTP/cPanel
3. Ensure `portfolio.html` is renamed to `index.html`

## 🎯 SEO Optimization

Add these meta tags in the `<head>` section:

```html
<meta name="description" content="Shridhar Shinde - Web Development Intern showcasing projects, skills and experience in web development">
<meta name="keywords" content="web developer, portfolio, Shridhar Shinde, PHP, JavaScript, Python, HTML, CSS">
<meta name="author" content="Shridhar Shinde">

<!-- Open Graph / Social Media -->
<meta property="og:title" content="Shridhar Shinde - Web Developer Portfolio">
<meta property="og:description" content="Web Development Intern at Prodigy InfoTech">
<meta property="og:image" content="shridhar profile.jpg">
<meta property="og:url" content="https://yourwebsite.com">

<!-- Twitter Card -->
<meta name="twitter:card" content="summary_large_image">
<meta name="twitter:title" content="Shridhar Shinde - Web Developer">
<meta name="twitter:description" content="Web Development Intern showcasing projects and skills">
<meta name="twitter:image" content="shridhar profile.jpg">
```

## 📊 Performance Tips

1. **Optimize Images**
   - Compress profile photo using TinyPNG or similar
   - Convert to WebP format for better compression
   - Use appropriate dimensions (max 500x600px)

2. **Lazy Loading**
   ```html
   <img src="shridhar profile.jpg" loading="lazy" alt="Shridhar Shinde">
   ```

3. **Minify CSS**
   - Use online CSS minifiers before deployment
   - Remove comments and whitespace

4. **Enable Caching**
   - Configure proper cache headers on your server
   - Set long cache times for static assets

## 🔍 Browser Compatibility

Tested and working on:
- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+
- ✅ Opera 76+

## 🐛 Troubleshooting

### Profile Photo Not Displaying?
- Ensure `shridhar profile.jpg` is in the same folder as HTML
- Check file name spelling and case sensitivity
- Verify image file is not corrupted

### Animations Not Working?
- Clear browser cache (Ctrl+Shift+R)
- Ensure JavaScript is enabled
- Try a different browser

### Layout Issues on Mobile?
- Check viewport meta tag is present
- Test in browser developer tools
- Try different mobile devices

### Links Not Working?
- Verify GitHub/LinkedIn URLs are correct
- Check for typos in href attributes
- Ensure external links have `target="_blank"`

## 📈 Future Enhancements

Potential improvements to consider:
- [ ] Add a blog section for articles
- [ ] Implement dark/light theme toggle
- [ ] Add project filtering by technology
- [ ] Include testimonials section
- [ ] Add animations library (AOS, GSAP)
- [ ] Implement contact form with backend
- [ ] Add Google Analytics
- [ ] Create multi-language support
- [ ] Add certifications section
- [ ] Implement progressive web app (PWA) features

## 📄 Project Information

- **Author**: Shridhar Shinde
- **Role**: Web Development Intern @ Prodigy InfoTech
- **Education**: BCA, Tilak Maharashtra Vidyapeeth, Pune (8.3 CGPA)
- **Location**: Mumbai, India
- **GitHub**: [@shindeshridhar07-walle](https://github.com/shindeshridhar07-walle)
- **LinkedIn**: [Shridhar Shinde](https://www.linkedin.com/in/shridhar-shinde)

## 🤝 Connect

Feel free to reach out for:
- Collaboration opportunities
- Web development projects
- Technical discussions
- Freelance work
- Internship inquiries

**Email**: shindeshridhar07@gmail.com  
**Phone**: +91 76203 72780  
**Location**: Mumbai, India

## 📜 License

This portfolio website is free to use as inspiration for your own portfolio. Feel free to fork and customize for your personal use.

## 🙏 Acknowledgments

- Design inspired by modern editorial layouts
- Google Fonts for typography (Playfair Display, DM Sans, Fira Code)
- Prodigy InfoTech for the internship opportunity
- Open source community for continuous learning

## 💡 Tips for Success

1. **Keep Updated**: Regularly add new projects and skills
2. **Optimize Images**: Always compress before uploading
3. **Mobile First**: Test on mobile devices frequently
4. **Fast Loading**: Keep file sizes minimal
5. **Proofread**: Check for typos and errors
6. **Get Feedback**: Ask peers to review your portfolio
7. **Track Analytics**: Monitor visitor behavior
8. **Stay Current**: Update technologies and trends

---

**Built with ❤️ by Shridhar Shinde | 2026**

*Ready to make an impact in web development!* 🚀

For any questions or suggestions, feel free to open an issue or reach out directly!
