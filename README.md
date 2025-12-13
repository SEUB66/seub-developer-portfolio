# Seub Germain - Developer Portfolio & Service Hub

A modern, interactive developer portfolio and service hub built with the APPLEPUNK cyberpunk design system. Showcases custom app development, web design, video production, and branding services for small businesses.

## 🚀 Features

### Main Portfolio (`index.html`)
- **Hero Section**: Eye-catching introduction with flame background and value proposition
- **Service Showcase**: 6 service cards with hover effects and detailed descriptions
- **Mission Statement**: Clear articulation of unique value (100% custom, 100% secure, 100% autonomous)
- **Why Us Section**: 6 key differentiators highlighting competitive advantages
- **Call-to-Action**: Prominent contact section for inquiries
- **Responsive Navigation**: Fixed header with smooth scroll navigation
- **Professional Footer**: Links to services, company info, social media, and legal pages

### Interactive Presentation (`presentation.html`)
- **Service Distribution Chart**: Doughnut chart showing portfolio mix
- **Value Proposition Radar**: Visual representation of key strengths
- **Project Complexity Spectrum**: Bar chart of project capacity levels
- **Technology Stack Capabilities**: Polar area chart of technical expertise
- **Service Filtering**: Interactive filter by category (All, Design, Development, Strategy)
- **Project Timeline**: 6-step visual workflow from discovery to ongoing support
- **Download/Share/Print**: Multiple export and sharing options
- **Statistics Dashboard**: Key metrics at a glance

## 🎨 Design System

### Colors (APPLEPUNK Palette)
```css
--bg-primary: #0a0a0a (Deep black background)
--bg-surface: rgba(15, 15, 25, 0.92) (Surface with transparency)
--accent-primary: #8ACCD5 (Cyan/Turquoise)
--accent-purple: #8E7DBE (Purple)
--accent-pink: #FF90BB (Pink)
--accent-pink-light: #FFC1DA (Light pink)
--accent-cream: #F8F8E1 (Cream)
--accent-teal: #1BCFB4 (Teal)
--text-primary: #ffffff (White text)
--text-secondary: rgba(255,255,255,0.7) (Secondary text)
```

### Gradients
- **Cyan to Purple**: `linear-gradient(135deg, #8ACCD5 0%, #8E7DBE 100%)`
- **Pink to Blue**: `linear-gradient(135deg, #FF90BB 0%, #8ACCD5 100%)`
- **Full Spectrum**: `linear-gradient(135deg, #8ACCD5 0%, #8E7DBE 50%, #FF90BB 100%)`

### Typography
- **Font Family**: System fonts (-apple-system, BlinkMacSystemFont, Segoe UI, Roboto)
- **Headings**: Bold, 700 weight, with gradient text effects
- **Body**: 1rem base size with 1.6 line height

## 📁 Project Structure

```
seub-germain-portfolio/
├── client/
│   ├── public/
│   │   ├── images/
│   │   │   ├── flame-bg.jpg (Flame background)
│   │   │   ├── banner.jpg (APPLEPUNK banner)
│   │   │   └── favicon.jpg (Brand favicon)
│   ├── src/
│   │   └── styles/
│   │       ├── main.css (Main design system)
│   │       └── backgrounds.css (Background patterns)
│   ├── index.html (Main portfolio page)
│   └── presentation.html (Interactive presentation)
├── package.json
└── README.md
```

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Advanced styling with gradients, animations, and responsive design
- **JavaScript**: Interactive features and smooth scrolling
- **Chart.js**: Data visualization library for interactive charts
- **Responsive Design**: Mobile-first approach with media queries

## 📊 Chart.js Integration

The presentation page includes 4 interactive charts:
1. **Service Portfolio Mix** (Doughnut Chart)
2. **Value Proposition** (Radar Chart)
3. **Project Complexity** (Horizontal Bar Chart)
4. **Technology Stack** (Polar Area Chart)

All charts use the APPLEPUNK color palette and are fully responsive.

## 🎯 Services Offered

1. **Logo Design** - Distinctive brand identities
2. **Video Clip Ads** - Engaging video content
3. **Web Design** - Modern, responsive websites
4. **Custom Apps** - Tailored applications from scratch
5. **Employee Portals** - Internal collaboration platforms
6. **Full-Stack Solutions** - Complete digital transformation

## ✨ Key Features

### Performance
- Optimized CSS with minimal dependencies
- No external JavaScript frameworks (vanilla JS)
- Fast-loading images and assets
- Efficient animations using CSS transforms

### Accessibility
- Semantic HTML structure
- ARIA labels where needed
- Keyboard navigation support
- Reduced motion preferences respected
- High contrast text on backgrounds

### SEO
- Meta descriptions and keywords
- Semantic HTML headings
- Open Graph tags ready
- Mobile-friendly viewport

### Responsive Design
- Mobile-first approach
- Breakpoints at 768px
- Flexible grid layouts
- Touch-friendly buttons and links

## 🚀 Getting Started

### Local Development
```bash
# Navigate to project directory
cd seub-germain-portfolio

# Start local server (Python)
python3 -m http.server 3000

# Or using Node.js
npx http-server client -p 3000
```

Visit `http://localhost:3000` for the main portfolio or `http://localhost:3000/presentation.html` for the interactive presentation.

## 📱 Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🎓 Design Philosophy

**APPLEPUNK Cyberpunk Aesthetic**
- Dark, sophisticated backgrounds
- Neon gradient accents
- Smooth, fluid animations
- Modern minimalism with personality
- Emphasis on readability and usability

**Unique Value Proposition**
- 100% Custom Solutions
- 100% Secure Architecture
- 100% Autonomous Apps
- No Licensing Restrictions
- Transparent Pricing

## 📝 Customization

### Changing Colors
Edit the CSS variables in `main.css`:
```css
:root {
  --accent-primary: #8ACCD5; /* Change primary accent */
  --accent-purple: #8E7DBE; /* Change secondary accent */
  /* ... etc */
}
```

### Adding New Services
Add new service cards to the grid in `index.html`:
```html
<div class="service-card">
  <div class="service-icon">🎯</div>
  <h3>Your Service</h3>
  <p>Service description</p>
  <a href="#" class="btn btn-secondary btn-sm">Learn More →</a>
</div>
```

### Updating Charts
Modify the data arrays in `presentation.html`:
```javascript
data: [15, 20, 30, 15, 12, 8], // Update these values
labels: ['Service1', 'Service2', ...] // Update labels
```

## 📧 Contact & Support

For inquiries about services, visit the main portfolio page and use the contact section.

## 📄 License

MIT License - Feel free to use and modify for your needs.

---

**Built with ❤️ for small businesses that deserve enterprise-grade solutions.**

*100% Custom. 100% Secure. 100% Yours.*
