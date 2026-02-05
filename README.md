# Prem Chand Avanigadda - Portfolio

Professional portfolio website showcasing my experience as an Engineering Team Lead, Technical Lead, and Software Development Manager.

## 🚀 Live Demo

Visit the portfolio: `https://[your-github-username].github.io/portfolio/`

## 📋 Features

- **Responsive Design** - Works seamlessly on desktop, tablet, and mobile
- **Modern UI** - Clean, professional design with smooth animations
- **Performance Optimized** - Fast loading with vanilla JavaScript
- **SEO Friendly** - Optimized meta tags and semantic HTML

## 🛠️ Built With

- HTML5
- CSS3 (with CSS Grid & Flexbox)
- Vanilla JavaScript
- Font Awesome Icons

## 📂 Project Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # Stylesheet
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## 🎯 Sections

1. **Hero** - Introduction with key metrics
2. **About** - Professional summary and highlights
3. **Experience** - Detailed work history timeline
4. **Skills** - Technical skills organized by category
5. **Achievements** - Key accomplishments and impact
6. **Contact** - Contact information and social links

## 📦 Deployment Instructions

### Option 1: GitHub Pages (Recommended)

1. **Create a new repository:**
   ```bash
   # Create repo named 'portfolio' or 'your-username.github.io'
   ```

2. **Initialize git in portfolio folder:**
   ```bash
   cd /Users/pavanigadda/Documents/Resume_latest/portfolio
   git init
   git add .
   git commit -m "Initial portfolio commit"
   ```

3. **Connect to GitHub:**
   ```bash
   git remote add origin https://github.com/[your-username]/portfolio.git
   git branch -M main
   git push -u origin main
   ```

4. **Enable GitHub Pages:**
   - Go to repository Settings → Pages
   - Source: Deploy from branch
   - Branch: `main` → `/root`
   - Save

5. **Access your site:**
   - `https://[your-username].github.io/portfolio/`

### Option 2: Custom Domain (Optional)

1. Add a `CNAME` file with your domain:
   ```
   yourdomain.com
   ```

2. Configure DNS settings at your domain provider:
   ```
   Type: CNAME
   Name: www
   Value: [your-username].github.io
   ```

## 🎨 Customization

### Colors
Edit CSS variables in `styles.css`:
```css
:root {
    --primary-color: #2563eb;
    --secondary-color: #1e40af;
    /* ... */
}
```

### Content
Update content in `index.html` sections

### Add Resume PDF
Place your PDF in the portfolio folder and update the download link:
```html
<a href="Resume_Prem_Avanigadda.pdf" download>Download Resume</a>
```

## 🔧 Local Development

1. **Open in browser:**
   ```bash
   open index.html
   ```

2. **Or use a local server:**
   ```bash
   # Python 3
   python -m http.server 8000
   
   # Python 2
   python -m SimpleHTTPServer 8000
   
   # Node.js (with http-server)
   npx http-server
   ```

3. Visit: `http://localhost:8000`

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 📄 License

This project is open source and available under the MIT License.

## 📧 Contact

- **Email:** Pavanigadda.work@gmail.com
- **LinkedIn:** [linkedin.com/in/pavaniga](https://linkedin.com/in/pavaniga)
- **Location:** Hyderabad, India

---

Made with ❤️ by Prem Chand Avanigadda
