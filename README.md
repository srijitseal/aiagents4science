# AIAgent4Science Consortium Website

A professional website for the AIAgent4Science Consortium, showcasing contributors and research in AI agents for drug discovery.

## Overview

This is a static website built with HTML, CSS, and JavaScript that highlights:
- Expert contributors from industry and academia
- Research focus on AI agents in pharmaceutical discovery
- Leadership and contact information

## Hosting on GitHub Pages

Follow these steps to host the website on GitHub Pages:

### 1. Initialize Git Repository

```bash
git init
git add .
git commit -m "Initial commit: AIAgent4Science Consortium website"
```

### 2. Create GitHub Repository

1. Go to https://github.com/new
2. Create a new repository (e.g., `aiagent4science-consortium`)
3. **Do not** initialize with README, .gitignore, or license

### 3. Push to GitHub

```bash
git remote add origin https://github.com/YOUR_USERNAME/aiagent4science-consortium.git
git branch -M main
git push -u origin main
```

### 4. Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** > **Pages** (in the left sidebar)
3. Under **Source**, select:
   - Branch: `main`
   - Folder: `/ (root)`
4. Click **Save**

### 5. Access Your Website

Your website will be available at:
```
https://YOUR_USERNAME.github.io/aiagent4science-consortium/
```

Note: It may take a few minutes for the site to become available.

## Custom Domain (Optional)

To use a custom domain:

1. Add a `CNAME` file to the repository root:
   ```bash
   echo "yourdomain.com" > CNAME
   git add CNAME
   git commit -m "Add custom domain"
   git push
   ```

2. Configure DNS with your domain provider:
   - Add a CNAME record pointing to: `YOUR_USERNAME.github.io`
   - Or add A records pointing to GitHub's IP addresses

3. In GitHub Settings > Pages, enter your custom domain

## File Structure

```
aiagent4science/
├── index.html              # Main HTML file
├── styles.css              # Stylesheet
├── script.js               # JavaScript for interactions
├── assets/
│   └── logos/             # Logo files (SVG placeholders)
├── README.md              # This file
└── .nojekyll              # Ensures GitHub Pages works correctly
```

## Local Development

To view the website locally:

1. **Simple HTTP Server (Python 3):**
   ```bash
   python3 -m http.server 8000
   ```
   Visit: http://localhost:8000

2. **Simple HTTP Server (Python 2):**
   ```bash
   python -m SimpleHTTPServer 8000
   ```

3. **Node.js (if installed):**
   ```bash
   npx http-server
   ```

4. **VS Code:**
   - Install "Live Server" extension
   - Right-click `index.html` and select "Open with Live Server"

## Customization

### Update Contributors

Edit the contributor sections in `index.html` (lines 74-175):
- Industry contributors: lines 77-139
- Academic contributors: lines 144-174

### Update Leadership

Edit the leadership section in `index.html` (lines 194-237)

### Update Styling

Modify colors and styles in `styles.css`:
- Color scheme: lines 11-18 (CSS variables)
- Section styles: throughout the file

### Update Content

- Hero section: lines 33-42
- About section: lines 46-67
- Research section: lines 178-192
- Contact section: lines 239-259

## Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance

The website is optimized for performance:
- Minimal dependencies (no external frameworks)
- SVG logos for fast loading
- Responsive design for all devices
- Smooth animations and transitions

## Contributing

To update the website:

1. Make changes to the files
2. Test locally
3. Commit and push:
   ```bash
   git add .
   git commit -m "Description of changes"
   git push
   ```

Changes will appear on GitHub Pages within a few minutes.

## License

© 2026 AIAgent4Science Consortium. All rights reserved.

## Contact

For questions or updates:
- Srijit Seal: seal@understanding.bio
- Ola Spjuth: ola.spjuth@uu.se

---

**Last Updated**: January 2026
