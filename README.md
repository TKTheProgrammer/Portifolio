# Portfolio Website - Takudzwa Percy Tawodzera

A modern, retro-tech inspired portfolio website showcasing game development and software engineering projects.

## 🚀 Live Demo

Once deployed to GitHub Pages, your portfolio will be available at:
`https://tktheprogrammer.github.io`

## 📋 Table of Contents

- [Quick Start](#quick-start)
- [Deployment to GitHub Pages](#deployment-to-github-pages)
- [Customization Guide](#customization-guide)
- [Adding New Projects](#adding-new-projects)
- [Updating Content](#updating-content)
- [Technical Details](#technical-details)
- [Troubleshooting](#troubleshooting)

## ⚡ Quick Start

1. **Download the Files**: Save `index.html` to your computer

2. **Create a GitHub Repository**:
   - Go to [GitHub](https://github.com) and log in
   - Click the "+" icon in the top right, select "New repository"
   - Name it: `tktheprogrammer.github.io` (this should be your actual GitHub username)
   - Make it public
   - Click "Create repository"

3. **Upload Your Portfolio**:
   - On your repository page, click "uploading an existing file"
   - Drag and drop `index.html` or click to select it
   - Add a commit message like "Initial portfolio upload"
   - Click "Commit changes"

4. **Enable GitHub Pages**:
   - Go to repository Settings → Pages
   - Under "Source", select "Deploy from a branch"
   - Select "main" branch and "/ (root)" folder
   - Click "Save"

5. **View Your Site**: Visit `https://yourusername.github.io` (it may take a few minutes to go live)

## 🌐 Deployment to GitHub Pages

### Method 1: Web Interface (Easiest)

1. Create repository named `yourusername.github.io`
2. Upload `index.html` via GitHub's web interface
3. Enable Pages in Settings → Pages
4. Select main branch, root folder
5. Wait 1-2 minutes and visit your URL

### Method 2: Git Command Line

```bash
# Initialize repository
git init
git add index.html README.md
git commit -m "Initial commit"

# Connect to GitHub
git remote add origin https://github.com/yourusername/yourusername.github.io.git
git branch -M main
git push -u origin main
```

### Method 3: GitHub Desktop (Recommended for beginners)

1. Download [GitHub Desktop](https://desktop.github.com/)
2. Create a new repository locally
3. Add your `index.html` file
4. Publish to GitHub
5. Enable Pages in repository settings

## 🎨 Customization Guide

### 1. Update Personal Information

Open `index.html` and find these sections:

**Your Name and Title** (around line 180):
```html
<h1>TAKUDZWA PERCY TAWODZERA</h1>
<h2>Game Developer • Software Engineer • Digital Creator</h2>
```

**About Section** (around line 195):
```html
<div class="about-content">
    <p>I'm <strong>Takudzwa Percy Tawodzera</strong>, a passionate...</p>
    <!-- Update with your own story -->
</div>
```

### 2. Update Contact Information

Find the Contact section (around line 320) and update:

```html
<a href="mailto:tk.tawodzera@gmail.com" class="contact-card">
    <div class="contact-icon">📧</div>
    <h3>Email</h3>
    <p>tk.tawodzera@gmail.com</p>
</a>

<a href="https://github.com/TKTheProgrammer" target="_blank" class="contact-card">
    <div class="contact-icon">💻</div>
    <h3>GitHub</h3>
    <p>@TKTheProgrammer</p>
</a>
```

Update your:
- Email address
- GitHub username
- Google Play Developer link
- LinkedIn profile URL

### 3. Customize Colors

Find the `:root` section (around line 10) to change colors:

```css
:root {
    --primary: #00ff88;      /* Main accent color (green) */
    --secondary: #ff0066;    /* Secondary accent (pink) */
    --accent: #00ccff;       /* Third accent (cyan) */
    --dark: #0a0e1a;         /* Card backgrounds */
    --darker: #050810;       /* Page background */
    --text: #e0e6ff;         /* Main text color */
    --text-dim: #8b95c9;     /* Secondary text */
}
```

### 4. Update Skills

Find the Skills section (around line 240) and modify the skill lists:

```html
<div class="skill-category">
    <h3>Game Development</h3>
    <ul class="skill-list">
        <li>Your Skill Here</li>
        <li>Another Skill</li>
        <!-- Add or remove skills -->
    </ul>
</div>
```

## 📦 Adding New Projects

To add a new project, find the Projects section and duplicate this template:

```html
<div class="project-card">
    <span class="project-type">GAME</span>  <!-- or WEB APP, SOFTWARE, etc. -->
    <h3>Your Project Name</h3>
    <p>Description of what the project does, technologies used, and what makes it unique.</p>
    <div class="project-tech">
        <span class="tech-badge">Technology 1</span>
        <span class="tech-badge">Technology 2</span>
        <span class="tech-badge">Technology 3</span>
    </div>
</div>
```

**Example - Adding a Pico 8 Game**:

```html
<div class="project-card">
    <span class="project-type">GAME</span>
    <h3>Space Shooter Deluxe</h3>
    <p>A retro-style space shooter with progressive difficulty, power-ups, and boss battles. 
    Features pixel-perfect collision detection and chip-tune soundtrack.</p>
    <div class="project-tech">
        <span class="tech-badge">Pico 8</span>
        <span class="tech-badge">Lua</span>
        <span class="tech-badge">Pixel Art</span>
    </div>
</div>
```

**Example - Adding Platform Links (like BOTS)**:

```html
<div class="project-card">
    <span class="project-type">GAME</span>
    <h3>BOTS</h3>
    <p>An action-packed, pixelated 2D mech-based game with tactical challenges...</p>
    <div class="project-tech">
        <span class="tech-badge">Game Maker Studio 2</span>
        <span class="tech-badge">2D Graphics</span>
        <span class="tech-badge">Pixel Art</span>
    </div>
    <div style="margin-top: 1rem; display: flex; gap: 0.5rem; flex-wrap: wrap;">
        <a href="YOUR_GAME_LINK" target="_blank" class="project-link">
            📱 Google Play
        </a>
        <span class="project-platform">🎮 GX.games</span>
    </div>
</div>
```

## 🔄 Updating Content

### Regular Updates

1. **Edit the file**: Open `index.html` in any text editor
2. **Make changes**: Update projects, skills, or information
3. **Upload to GitHub**:
   - Drag the updated file to your repository
   - Or use Git: `git add index.html`, `git commit -m "Update projects"`, `git push`
4. **Changes go live**: Usually within 1-2 minutes

### Version Control Best Practices

```bash
# Before making changes
git pull origin main

# After making changes
git add index.html
git commit -m "Add new game project: Space Shooter"
git push origin main
```

## 🛠 Technical Details

### Technologies Used
- **HTML5**: Structure and content
- **CSS3**: Styling, animations, and responsive design
- **Vanilla JavaScript**: Interactions and scroll effects
- **Google Fonts**: Orbitron and JetBrains Mono

### Features
- ✅ Fully responsive (mobile, tablet, desktop)
- ✅ Animated grid background
- ✅ Smooth scroll effects
- ✅ Hover animations
- ✅ No external dependencies (except fonts)
- ✅ Fast loading
- ✅ SEO-friendly

### Browser Support
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 🎯 Customization Ideas

### Add Project Links

Make projects clickable by wrapping them in links:

```html
<a href="https://yourgame.com" target="_blank" style="text-decoration: none;">
    <div class="project-card">
        <!-- project content -->
    </div>
</a>
```

### Add Project Screenshots

Add images to your projects (make sure the image is in the same directory as index.html):

```html
<div class="project-card">
    <img src="your-game-image.png" alt="Game screenshot" class="project-image">
    <span class="project-type">GAME</span>
    <!-- rest of project card -->
</div>
```

The image will automatically have a hover effect that makes it glow and lift slightly when visitors hover over the project card.

### Add a Navigation Menu

Insert this before the hero section:

```html
<nav style="text-align: center; padding: 2rem 0;">
    <a href="#about" style="margin: 0 1rem; color: var(--primary);">About</a>
    <a href="#skills" style="margin: 0 1rem; color: var(--primary);">Skills</a>
    <a href="#projects" style="margin: 0 1rem; color: var(--primary);">Projects</a>
    <a href="#contact" style="margin: 0 1rem; color: var(--primary);">Contact</a>
</nav>
```

## 📱 Social Media Integration

### Add More Social Links

```html
<a href="https://twitter.com/yourhandle" target="_blank" class="contact-card">
    <div class="contact-icon">🐦</div>
    <h3>Twitter</h3>
    <p>@yourhandle</p>
</a>

<a href="https://itch.io/yourprofile" target="_blank" class="contact-card">
    <div class="contact-icon">🎮</div>
    <h3>Itch.io</h3>
    <p>Game Portfolio</p>
</a>
```

## 🐛 Troubleshooting

### Site Not Loading
- Wait 5-10 minutes after enabling GitHub Pages
- Check Settings → Pages is set to "main" branch
- Ensure repository is named `yourusername.github.io`

### Changes Not Appearing
- Clear browser cache (Ctrl+Shift+R or Cmd+Shift+R)
- Wait 1-2 minutes for GitHub to deploy changes
- Check if file was actually uploaded to GitHub

### Mobile Display Issues
- The site is fully responsive
- Test on different devices
- Use browser developer tools to test (F12 → Device toolbar)

### Custom Domain
To use your own domain (e.g., www.yourname.com):
1. Buy domain from registrar
2. Add CNAME file to repository with your domain
3. Configure DNS settings at registrar
4. Enable custom domain in GitHub Pages settings

## 📈 Analytics (Optional)

To track visitors, add Google Analytics or similar:

```html
<!-- Add before closing </head> tag -->
<script async src="https://www.googletagmanager.com/gtag/js?id=YOUR-ID"></script>
<script>
    window.dataLayer = window.dataLayer || [];
    function gtag(){dataLayer.push(arguments);}
    gtag('js', new Date());
    gtag('config', 'YOUR-ID');
</script>
```

## 🎓 Learning Resources

- [GitHub Pages Documentation](https://docs.github.com/pages)
- [HTML/CSS Tutorial](https://www.w3schools.com/)
- [Git Basics](https://git-scm.com/book/en/v2/Getting-Started-About-Version-Control)
- [Markdown Guide](https://www.markdownguide.org/)

## 📝 License

This portfolio template is free to use and modify for personal and commercial purposes.

## 🤝 Contributing

This is your personal portfolio, but if you want to share improvements:
1. Fork this repository
2. Make your changes
3. Submit a pull request

## 💬 Support

If you have questions:
- Check the troubleshooting section
- Search GitHub Pages documentation
- Ask in GitHub Discussions
- Create an issue in this repository

---

**Built with 💚 by Takudzwa Percy Tawodzera**

Good luck with your portfolio! Remember to update it regularly with your latest projects and achievements. 🚀
