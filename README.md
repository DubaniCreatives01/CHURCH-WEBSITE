# Langa Life Bible Church Website

## Overview
A modern, responsive website for Langa Life Bible Church located in Langa, Cape Town, South Africa. This website showcases the church's mission, ministries, service times, pastoral team, and provides contact information for visitors.

## Features

### 🎨 Modern Design
- Clean and professional layout
- Contemporary color scheme with church branding
- Smooth animations and transitions
- Fully responsive design for all devices

### 🚀 Performance
- Fast loading times
- Optimized CSS and JavaScript
- Mobile-first approach
- SEO-friendly structure

### ✨ Interactive Elements
- Smooth scroll navigation
- Fade-in animations on scroll
- Hover effects on cards and buttons
- Responsive mobile menu
- Active navigation highlighting
- Parallax effects on hero section

### 📱 Responsive Sections
1. **Navigation Bar** - Fixed header with smooth scroll links
2. **Hero Section** - Eye-catching introduction with call-to-action buttons
3. **Info Bar** - Quick access to location, service times, and contact
4. **About Section** - Church history and mission statement
5. **Ministries Section** - Detailed ministry descriptions with icons
6. **Service Times** - Sunday worship and weekday Bible study schedules
7. **Pastors Section** - Meet the pastoral team with social links
8. **CTA Section** - Call-to-action for visitors
9. **Contact Section** - Contact form and information
10. **Footer** - Quick links and additional information

## Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with animations
  - CSS Grid & Flexbox for layouts
  - CSS Custom Properties (variables)
  - CSS Transitions and Animations
- **JavaScript (Vanilla)** - Interactive features
  - Intersection Observer API for scroll animations
  - Smooth scroll navigation
  - Mobile menu toggle
  - Form validation
- **Font Awesome 6.4.0** - Icon library

## File Structure

```
CHURCH-WEBSITE/
│
├── index.html          # Main HTML file
├── styles.css          # Stylesheet with animations
├── script.js           # JavaScript for interactivity
└── README.md           # Project documentation
```

## Setup & Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/DubaniCreatives01/CHURCH-WEBSITE.git
   ```

2. **Navigate to the project folder:**
   ```bash
   cd CHURCH-WEBSITE
   ```

3. **Open in browser:**
   - Simply open `index.html` in your web browser
   - Or use a local server for development:
     ```bash
     # Using Python
     python -m http.server 8000
     
     # Using Node.js (http-server)
     npx http-server
     ```

## Customization

### Colors
Edit the CSS custom properties in `styles.css`:
```css
:root {
    --primary-color: #2c5f8d;      /* Main brand color */
    --secondary-color: #f39c12;     /* Accent color */
    --accent-color: #27ae60;        /* Success/highlight color */
    --dark-color: #1a1a1a;          /* Dark text */
    --light-color: #ffffff;         /* Light backgrounds */
}
```

### Content
- Update text content in `index.html`
- Replace placeholder pastor names and information
- Add actual social media links
- Update contact information

### Images
- Replace the image placeholders with actual photos
- Add church logo in the navigation
- Include pastor photos and ministry images

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Deployment

### GitHub Pages
1. Go to repository Settings
2. Navigate to Pages section
3. Select branch (main) and root folder
4. Save and wait for deployment

### Netlify
1. Connect your GitHub repository
2. Set build settings (not required for static site)
3. Deploy

### Custom Domain
1. Purchase domain (e.g., langalifebiblechurch.co.za)
2. Configure DNS settings with your hosting provider
3. Update domain in GitHub Pages or Netlify settings

## Future Enhancements

- [ ] Add sermon podcast section
- [ ] Integrate event calendar
- [ ] Add blog/news section
- [ ] Implement online giving/donations
- [ ] Add photo gallery
- [ ] Integrate live streaming for services
- [ ] Add multi-language support
- [ ] Backend for contact form (EmailJS or similar)

## Credits

**Designed & Developed by:** Dubani Creatives  
**Client:** Langa Life Bible Church  
**Location:** Langa, Cape Town, South Africa

## License

This project is created for Langa Life Bible Church. All rights reserved.

## Contact

For questions or support regarding this website:
- **Email:** info@langalifebiblechurch.co.za
- **Phone:** +1 (212)-695-1962
- **Address:** Langa, Cape Town, South Africa

---

*Built with ❤️ for the Kingdom*