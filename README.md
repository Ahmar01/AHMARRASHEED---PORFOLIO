# 👨‍💻 Professional Portfolio

A modern, responsive, and professional portfolio website showcasing my work, skills, and experience. Built with clean HTML, CSS, and JavaScript - no frameworks required.

![Portfolio Preview](https://img.shields.io/badge/Status-Live-brightgreen)
![License](https://img.shields.io/badge/License-MIT-blue)
![Version](https://img.shields.io/badge/Version-1.0.0-orange)

---

## 🎯 Features

✨ **Fully Responsive Design**
- Mobile-first approach
- Works perfectly on all devices (phones, tablets, desktops)
- Smooth animations and transitions

📸 **Profile Picture Section**
- Beautiful circular profile image with professional styling
- Easy to customize with your own photo

🎨 **Professional Color Scheme**
- Navy blue and gold theme (corporate & trustworthy)
- Clean, modern design
- Easy to customize colors

🔗 **Social Links Integration**
- LinkedIn profile
- GitHub repositories
- Twitter/X account
- Personal website

📱 **Multiple Sections**
- Hero/Landing section with profile picture
- About Me section
- Skills showcase
- Portfolio/Projects display
- Contact information
- Smooth navigation with sticky header

⚡ **Performance Optimized**
- Lightweight (no heavy dependencies)
- Fast loading times
- SEO friendly
- No external frameworks required

🎯 **User-Friendly**
- Sticky navigation menu
- Smooth scroll navigation
- Hover effects and animations
- Active link highlighting
- Mobile-friendly navigation

---

## 🚀 Live Demo

👉 **[View My Portfolio](https://ahmar01.github.io)**

*(Update with your actual portfolio URL)*

---

## 📋 Sections Included

1. **Navigation Bar** - Sticky header with smooth scrolling
2. **Hero Section** - Profile picture, name, title, and CTA button
3. **About Me** - Personal introduction and background
4. **Skills Section** - Key technical and professional skills
5. **Connect With Me** - Social media links (LinkedIn, GitHub, Twitter, Website)
6. **Portfolio/Projects** - Featured projects with descriptions and technologies
7. **Contact Section** - Email and phone contact information
8. **Footer** - Copyright and closing

---

## 🛠️ Technologies Used

- **HTML5** - Semantic markup and structure
- **CSS3** - Modern styling with gradients and animations
- **JavaScript** - Smooth scrolling and interactive features
- **Responsive Design** - Mobile-first approach for all devices

---

## 📦 Installation & Setup

### Option 1: Download & Use Locally

```bash
# Clone this repository
git clone https://github.com/Ahmar01/portfolio.git

# Navigate to the folder
cd portfolio

# Open in your browser
open professional-portfolio.html
```

**On Windows:**
```bash
start professional-portfolio.html
```

**On Linux:**
```bash
xdg-open professional-portfolio.html
```

### Option 2: Use Online (No Installation Needed)

1. Download the `professional-portfolio.html` file
2. Upload to any free hosting service:
   - **Netlify Drop** - https://netlify.drop.com (Easiest - just drag & drop)
   - **Vercel** - https://vercel.com
   - **GitHub Pages** - Push to your repository

---

## ✏️ Customization Guide



<div class="profile-picture">
    <img src="1000080278.jpg" alt="Ahmar Rasheed">
</div>

**Photo Requirements:**
- Use a professional headshot or clear photo
- Recommended size: 200x200px or larger
- Format: JPG or PNG
- Save in the same folder as the HTML file
- Good quality, well-lit photo

---

### 2. ** Personal Information**

Find and update your hero section with your details:


<h1>Ahmar Rasheed</h1>
<p class="professional-title">Software Engineer | Full Stack Developer</p>
<p class="hero-description">
    Passionate about building scalable solutions and solving complex problems. 
    Experienced in web development with expertise in modern technologies.
</p>


**Change:**
- `Ahmar Rasheed`
- `Software Engineer | Full Stack Developer` 
- The description 

---

### 3. ** Social Links**




<a href="https://www.linkedin.com/feed/" target="_blank" class="social-card">
    <span class="icon">💼</span>
    <span class="platform">LinkedIn</span>
    <span class="url">linkedin.com/in/ahmar-rasheed</span>
</a>

<a href="https://github.com/Ahmar01" target="_blank" class="social-card">
    <span class="icon">🐙</span>
    <span class="platform">GitHub</span>
    <span class="url">github.com/Ahmar01</span>
</a>

<a href="https://twitter.com/ahmarasheed" target="_blank" class="social-card">
    <span class="icon">𝕏</span>
    <span class="platform">Twitter</span>
    <span class="url">twitter.com/ahmarasheed</span>
</a>

<a href="https://yourwebsite.com" target="_blank" class="social-card">
    <span class="icon">🌐</span>
    <span class="platform">Website</span>
    <span class="url">yourwebsite.com</span>
</a>


---

### 4. ** Your Projects**


<div class="portfolio-item">
    <div class="portfolio-item-image">
        <img src="project1.jpg" alt="Glassmorphism">
    </div>
    <div class="portfolio-item-content">
        <h3>Glassmorphism</h3>
        <p>AI TOOl for making Glassmorphism</p>
        <div class="tags">
            <span class="tag">html</span>
            <span class="tag">css</span>
            <span class="tag">js</span>
        </div>
    </div>
</div>




---

### 5. ** Skills Section**


<div class="skill-item">
    <h4>Frontend Development</h4>
    <p>React, Vue.js, JavaScript, HTML/CSS, Tailwind CSS</p>
</div>

<div class="skill-item">
    <h4>Backend Development</h4>
    <p>Node.js, Python, Django, Express.js, MongoDB</p>
</div>

<div class="skill-item">
    <h4>Tools & Platforms</h4>
    <p>Git, Docker, AWS, Firebase, PostgreSQL, MySQL</p>
</div>

<div class="skill-item">
    <h4>Soft Skills</h4>
    <p>Leadership, Communication, Problem-Solving, Team Collaboration</p>
</div>

---

### 6. ** Contact Information**


<a href="mailto:ahmarasheed1087@gmail.com">📧 ahmarasheed1087@gmail.com</a>
<a href="tel:+923269512757">📱 +92-326-9512757</a>
```



---

### 7. ** About Me Section**


<p class="about-text">
    I'm a passionate software engineer with 5+ years of experience in 
    full-stack development. I love solving complex problems and building 
    applications that users love. My journey in tech has taught me the 
    importance of clean code, continuous learning, and collaboration.
</p>

<p class="about-text">
    When I'm not coding, you'll find me exploring new technologies, 
    contributing to open-source projects, or sharing knowledge with the 
    developer community.
</p>

---

### 8. **Customize Colors (Optional)**

:root {
    --navy: #1a2a47;          /* Primary background color */
    --dark-navy: #0f1824;     /* Dark background variant */
    --gold: #d4a373;          /* Accent/highlight color */
    --light-gold: #e8c4a0;    /* Light accent color */
    --white: #ffffff;         /* Clean background */
    --gray: #6b7280;          /* Secondary text color */
    --text: #1a1a1a;          /* Main text color */
}


**Popular Color Schemes:**

**Modern Blue:**
```css
--navy: #0066cc;
--gold: #00d4ff;
```

**Professional Green:**
```css
--navy: #1e3a5f;
--gold: #2ecc71;
```

**Dark Mode:**
```css
--navy: #1a1a2e;
--gold: #ff6b6b;
```

---

## 📱 Responsive Breakpoints

The portfolio is fully responsive across all device sizes:

- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: Below 768px

All sections adapt automatically to screen size.

---

## 🚀 Deployment Options

### **Option 1: GitHub Pages (RECOMMENDED)**

Best for: Free hosting, professional, easy to update

**Step-by-Step:**

1. Create GitHub account at https://github.com
2. Create a new repository named: `Ahmar01.github.io`
3. Click **"Add file"** → **"Upload files"**
4. Select and upload:
   - `professional-portfolio.html` (rename to `index.html`)
   - `README.md`
   - `profile.jpg` (your photo)
5. Click **"Commit changes"**
6. Wait 2-3 minutes
7. Visit: `https://Ahmar01.github.io`

✅ Your portfolio is now live!

---

### **Option 2: Netlify (EASIEST)**

Best for: Super fast setup, instant deployment

1. Go to: https://netlify.drop.com
2. **Drag and drop** your `professional-portfolio.html` file
3. Wait 5 seconds
4. Copy your live URL (example: `https://abc123.netlify.app`)

✅ Your portfolio is live instantly!

---

### **Option 3: Vercel (FAST)**

Best for: High performance, automatic updates

1. Go to: https://vercel.com
2. Click **"New Project"**
3. Click **"Upload"** and select your HTML file
4. Click **"Deploy"**
5. Get your live URL

✅ Your portfolio is deployed!

---

### **Option 4: Custom Domain**

**If you want your own domain (e.g., ahmarasheed.com):**

1. Buy a domain from:
   - GoDaddy.com
   - Namecheap.com (Cheaper)
   - Google Domains

2. Cost: ₹100-500 per year

3. Connect to GitHub Pages/Netlify/Vercel

4. Update DNS settings (provider will guide you)

5. Your portfolio goes to your custom domain!

---

## 🎨 Color Scheme Reference

| Element | Color Name | Hex Code | Use Case |
|---------|-----------|----------|----------|
| Primary Background | Navy | `#1a2a47` | Main background |
| Dark Background | Dark Navy | `#0f1824` | Headers, dark areas |
| Accent Color | Gold | `#d4a373` | Buttons, highlights |
| Light Accent | Light Gold | `#e8c4a0` | Borders, soft accents |
| Main Text | Dark Gray | `#1a1a1a` | All text content |
| Secondary Text | Light Gray | `#6b7280` | Descriptions, meta text |
| Clean Backgrounds | White | `#ffffff` | Section backgrounds |

**Theme**: Professional, Corporate, Modern, Trustworthy

---

## 📸 Website Sections Explained

### **Navigation Bar**
- Sticky header that stays at top while scrolling
- Links to all major sections
- Professional navy background with gold accents

### **Hero Section**
- Your profile picture (circular, centered)
- Your name and professional title
- Brief introduction
- "Get In Touch" button

### **About Section**
- Personal biography
- Your story and experience
- Skills breakdown in organized cards

### **Connect Section**
- LinkedIn profile link
- GitHub repositories link
- Twitter/social media link
- Personal website link
- Beautiful card design with hover effects

### **Portfolio Section**
- Showcase 3+ of your best projects
- Include project images, descriptions
- List technologies used
- Create hover animations

### **Contact Section**
- Email contact link
- Phone number
- Professional call-to-action

### **Footer**
- Copyright information
- Clean closing

---

## 🔧 Browser Support

Tested and working on:

- ✅ Chrome (Latest version)
- ✅ Firefox (Latest version)
- ✅ Safari (Latest version)
- ✅ Edge (Latest version)
- ✅ Mobile Browsers (iOS Safari, Chrome Mobile)

---

## 📈 SEO Optimization

The portfolio includes:

✓ Semantic HTML5 structure
✓ Meta tags for customization
✓ Mobile-friendly responsive design
✓ Fast loading times (no external dependencies)
✓ Optimized images support
✓ Clean, crawlable code
✓ Structured markup

---

## 🎯 Best Practices Implemented

✓ **Responsive Design** - Works on all devices
✓ **Accessibility** - Keyboard navigation, semantic HTML
✓ **Clean Code** - Easy to read and modify
✓ **No Dependencies** - Pure HTML, CSS, JavaScript
✓ **Cross-Browser** - Works everywhere
✓ **Performance** - Fast loading
✓ **Mobile-First** - Mobile optimized
✓ **Animations** - Smooth, not distracting
✓ **Professional Styling** - Corporate look

---

## 📝 File Structure

```
Ahmar01.github.io/
│
├── index.html                    # Main portfolio (rename from professional-portfolio.html)
├── README.md                     # Documentation (this file)
├── profile.jpg                   # Your profile picture
└── .gitignore                    # Optional - ignore DS_Store, etc
```

**That's it!** Just 1 HTML file - no build process, no dependencies!

---

## 💡 Tips for Maximum Impact

1. **Professional Photo** 
   - Use a high-quality headshot
   - Good lighting, clear face
   - Dress professionally
   - Keep background simple

2. **Accurate Information**
   - Keep all details current
   - Update projects regularly
   - Verify all links work
   - Check for typos

3. **Project Descriptions**
   - Write clear, concise descriptions
   - Explain the problem and solution
   - Highlight technologies used
   - Include real projects you've built

4. **Skill Accuracy**
   - Only list skills you're proficient in
   - Be honest about experience levels
   - Include both technical and soft skills

5. **Regular Updates**
   - Add new projects quarterly
   - Update achievements
   - Refresh your bio
   - Keep links current

6. **Testing**
   - Test email and phone links
   - Check on actual mobile devices
   - Verify all social links
   - Test on different browsers

---

## 🤝 Contributing

Want to improve this portfolio template?

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Commit your work
5. Push to GitHub
6. Open a Pull Request

---

## 📄 License

This project is open source and available under the **MIT License**.

You are free to:
- ✅ Use it for your personal portfolio
- ✅ Modify it as needed
- ✅ Share it with others
- ✅ Use it commercially

---

## 👤 Author & Contact

**Ahmar Rasheed**

- 🔗 **LinkedIn**: [linkedin.com/in/ahmar-rasheed](https://www.linkedin.com/feed/)
- 🐙 **GitHub**: [github.com/Ahmar01](https://github.com/Ahmar01)
- 🐦 **Twitter**: [@AhmarRasheed](https://twitter.com)
- 📧 **Email**: ahmarasheed1087@gmail.com
- 📱 **Phone**: +92-326-9512757

---

## 🙏 Acknowledgments

Built with attention to:
- Modern web design principles
- Responsive design best practices
- Professional aesthetics
- User experience optimization
- Clean code standards

---

## ⭐ Show Your Support

If you find this portfolio template helpful:

- ⭐ **Star** this repository
- 🍴 **Fork** it for your own use
- 📢 **Share** with other developers
- 💬 **Provide feedback** to improve it

---

## 📞 Support & Help

Need assistance?

1. **Check the Customization Guide** above
2. **Review the HTML comments** in the code
3. **Open an issue** on GitHub
4. **Check browser console** for errors (Press F12)
5. **Compare with the original template** if stuck

---

## 🗓️ Version History

### Version 1.0.0 (Current - 2024)
- ✅ Initial release
- ✅ Responsive design for all devices
- ✅ Profile picture section
- ✅ Professional navy & gold color scheme
- ✅ Social media integration (4 platforms)
- ✅ Project/portfolio showcase
- ✅ Skills section with categories
- ✅ Smooth animations and transitions
- ✅ Contact information section
- ✅ Mobile-friendly navigation

---

## 📚 Useful Learning Resources

- [HTML Documentation](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [CSS Complete Guide](https://developer.mozilla.org/en-US/docs/Web/CSS)
- [JavaScript Basics](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
- [GitHub Pages Setup](https://pages.github.com/)
- [Netlify Hosting](https://www.netlify.com/)
- [Responsive Design](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Responsive_Design)
- [Web Accessibility](https://www.w3.org/WAI/fundamentals/)

---

## 🎬 Quick Start Checklist

- [ ] Download `professional-portfolio.html`
- [ ] Download `README.md`
- [ ] Add your profile picture
- [ ] Open HTML file in text editor
- [ ] Update your name and title
- [ ] Update your bio and description
- [ ] Add your social media links
- [ ] Add your projects
- [ ] Update contact information
- [ ] Test the portfolio locally
- [ ] Choose hosting platform
- [ ] Deploy your portfolio
- [ ] Share your live URL
- [ ] Update GitHub profile bio

---

## 📊 Portfolio Stats

- **File Size**: Single HTML file (~30KB)
- **Load Time**: < 2 seconds
- **Dependencies**: Zero external dependencies
- **Browser Support**: 95%+ of users
- **Mobile Friendly**: 100%
- **Lighthouse Score**: 95+ (Performance)

---

**Last Updated**: June 2026
**Status**: ✅ Active & Fully Maintained
**Quality**: Production Ready

---

*Built with ❤️ for professionals who want a clean, modern, professional portfolio*

**Ready to launch your career? Get started now! 🚀**
