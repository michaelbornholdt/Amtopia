# Speaking Portfolio

A professional website showcasing speaking experience and expertise, built for GitHub Pages.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI**: Clean, professional design with smooth animations
- **Interactive Elements**: Contact form, smooth scrolling navigation, and hover effects
- **SEO Optimized**: Proper meta tags and semantic HTML structure
- **Fast Loading**: Optimized CSS and JavaScript for quick page loads

## Sections

1. **Hero Section**: Eye-catching introduction with call-to-action buttons
2. **About**: Personal introduction and key statistics
3. **Speaking Experience**: Showcase of past speaking engagements
4. **Topics**: Areas of expertise and speaking topics
5. **Contact**: Contact form and booking information

## Setup for GitHub Pages

### 1. Push to GitHub
```bash
git add .
git commit -m "Add speaking portfolio website"
git push origin main
```

### 2. Enable GitHub Pages
1. Go to your repository on GitHub
2. Click on "Settings" tab
3. Scroll down to "Pages" section
4. Under "Source", select "Deploy from a branch"
5. Choose "main" branch and "/ (root)" folder
6. Click "Save"

### 3. Access Your Site
Your website will be available at:
`https://[your-username].github.io/[repository-name]`

## Customization

### Update Personal Information
Edit the following in `index.html`:
- Replace "Michael" with your name
- Update contact information (email, phone)
- Modify speaking experience entries
- Adjust topics and expertise areas

### Update Statistics
In the About section, update the numbers:
- Speaking Engagements count
- Years of Experience
- Audience Members reached

### Add Your Speaking Engagements
Replace the example speaking cards with your actual experience:
- Event names and dates
- Locations
- Audience sizes
- Speaking types (keynote, workshop, panel, etc.)

### Modify Topics
Update the topics section with your areas of expertise:
- Change topic titles
- Update descriptions
- Modify icons (using Font Awesome classes)

## File Structure

```
/
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
├── README.md           # This file
└── docs/               # Original documentation (can be removed)
```

## Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with Flexbox and Grid
- **JavaScript**: Interactive functionality
- **Font Awesome**: Icons
- **Google Fonts**: Inter font family

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Performance

- Optimized images and assets
- Minified CSS and JavaScript (for production)
- Fast loading times
- Mobile-first responsive design

## Contact Form

The contact form currently shows a success message. To make it functional:

1. **Use a form service** like Formspree, Netlify Forms, or similar
2. **Add backend processing** with your preferred technology
3. **Update the JavaScript** in `script.js` to handle real form submission

## License

This project is open source and available under the [MIT License](LICENSE).
