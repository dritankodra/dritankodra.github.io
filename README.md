# Personal Portfolio Website

A modern, responsive portfolio website showcasing my work as a Data Scientist specializing in Generative AI, with a background in Physics and Astronomy.

## Features

- **Modern Design**: Clean, professional interface with smooth animations
- **Fully Responsive**: Works seamlessly on desktop, tablet, and mobile devices
- **Smooth Navigation**: Fixed navbar with smooth scrolling between sections
- **Project Showcase**: Highlight your best work with detailed project cards
- **Skills Display**: Organized presentation of technical skills and expertise
- **Education Timeline**: Visual timeline of your academic achievements
- **Contact Links**: Easy access to your professional profiles and contact information

## Sections

1. **Hero Section**: Eye-catching introduction with call-to-action buttons
2. **About**: Personal background and professional journey
3. **Projects**: Featured projects with links to GitHub and live demos
4. **Skills**: Technical skills organized by category
5. **Education**: Academic qualifications and achievements
6. **Contact**: Links to email, LinkedIn, GitHub, and other profiles

## Customization

Before deploying, make sure to customize the following:

### 1. Personal Information
- Replace "Your Name" throughout `index.html` with your actual name
- Update the email address in the contact section
- Add your social media profile URLs (LinkedIn, GitHub, Twitter, etc.)

### 2. About Section
- Update the about text with your personal story and professional focus
- Modify the description to reflect your specific research interests

### 3. Projects
- Replace the example projects with your actual projects
- Update project titles, descriptions, and tags
- Add links to your GitHub repositories and live demos
- Update the technology tags for each project

### 4. Skills
- Modify the skills lists to match your actual expertise
- Add or remove skill categories as needed
- Update skill items to reflect your technical stack

### 5. Education
- Replace the education entries with your actual degrees
- Update university names, years, and descriptions
- Add or remove education items as needed

### 6. Styling (Optional)
- Modify color scheme in `styles.css` by updating CSS variables in `:root`
- Adjust fonts, spacing, or layout as desired
- Customize animations and transitions

## Deployment to GitHub Pages

### Method 1: Using GitHub Repository (Recommended)

1. **Create a new repository** on GitHub:
   - Repository name: `yourusername.github.io` (replace `yourusername` with your GitHub username)
   - Make it public
   - Don't initialize with README, .gitignore, or license

2. **Initialize git and push your files**:
   ```bash
   cd portfolio-site
   git init
   git add .
   git commit -m "Initial commit: Portfolio website"
   git branch -M main
   git remote add origin https://github.com/yourusername/yourusername.github.io.git
   git push -u origin main
   ```

3. **Enable GitHub Pages**:
   - Go to your repository on GitHub
   - Click on "Settings"
   - Scroll down to "Pages" in the left sidebar
   - Under "Source", select "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Click "Save"

4. **Your site will be live** at `https://yourusername.github.io` within a few minutes!

### Method 2: Using a Custom Repository Name

If you want to use a different repository name (e.g., `portfolio`):

1. Follow steps 1-2 above, but use your desired repository name
2. In GitHub Pages settings, select the branch and folder as above
3. Your site will be available at `https://yourusername.github.io/portfolio/`
4. **Important**: Update all internal links in `index.html` to use relative paths (they already do)
5. Update the `href` attributes in navigation links if needed

## Local Development

To preview your site locally:

1. **Using Python** (if installed):
   ```bash
   cd portfolio-site
   python3 -m http.server 8000
   ```
   Then open `http://localhost:8000` in your browser

2. **Using Node.js** (if installed):
   ```bash
   cd portfolio-site
   npx http-server -p 8000
   ```
   Then open `http://localhost:8000` in your browser

3. **Using VS Code**:
   - Install the "Live Server" extension
   - Right-click on `index.html` and select "Open with Live Server"

## File Structure

```
portfolio-site/
├── index.html          # Main HTML file
├── styles.css          # All styling and responsive design
├── script.js           # JavaScript for interactivity
└── README.md           # This file
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Tips for Job Applications

1. **Keep it updated**: Regularly update your projects and skills
2. **Show your best work**: Feature 3-5 of your strongest projects
3. **Be specific**: Include concrete examples and achievements
4. **Add a resume**: Consider adding a downloadable PDF resume
5. **Optimize for SEO**: Update meta tags and descriptions
6. **Test thoroughly**: Check all links and ensure mobile responsiveness

## License

This portfolio template is free to use and modify for personal and commercial purposes.

## Credits

- Font: [Inter](https://fonts.google.com/specimen/Inter) by Google Fonts
- Icons: Custom SVG icons
- Design: Modern, minimalist portfolio design

---

**Need help?** Feel free to open an issue or reach out if you need assistance customizing your portfolio!

