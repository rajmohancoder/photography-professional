# Skyline Capture - Freelance Photographer Portfolio

A modern, minimal, and visually appealing single-page portfolio website for Skyline Capture, a freelance photographer based in Chennai.

## Features

- **Responsive Design**: Fully optimized for mobile, tablet, and desktop devices
- **Dark/Light Theme**: Toggle between dark and light modes with localStorage persistence
- **Smooth Animations**: CSS transitions and animations for enhanced user experience
- **Photo Gallery**: Filterable gallery with hover effects and image error handling
- **Testimonials Carousel**: Interactive carousel for client testimonials
- **Contact Form**: Functional contact form with validation
- **Smooth Scrolling**: Scroll-smooth behavior for anchor links
- **Mobile Menu**: Responsive hamburger menu for mobile devices

## Sections

1. **Hero**: Introduction with animated background and call-to-action
2. **About Me**: Personal information, experience, and statistics
3. **Gallery**: Filterable photo portfolio (All, Nature, Portraits, Urban, Landscape, Wildlife)
4. **Insights**: Photography tips, articles, and behind-the-scenes content
5. **Gear**: Photography equipment and tools used
6. **Classes**: Photography workshops and training information
7. **Contact**: Contact form and social media links
8. **Testimonials**: Client feedback and testimonials
9. **Footer**: Copyright information and quick links

## Technologies Used

- **HTML5**: Semantic markup
- **Tailwind CSS 3**: Utility-first CSS framework
- **JavaScript (ES6+)**: Interactive functionality
- **Google Fonts**: Syne (display) and Outfit (body) fonts
- **Picsum Photos**: Placeholder images
- **Font Awesome**: Icons (not explicitly used, but structure supports it)

## Getting Started

This is a static website that doesn't require any build process or server-side setup. You can run it directly from your local machine.

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- Basic knowledge of HTML, CSS, and JavaScript (for customization)

### Installation

1. Clone or download this repository
2. Open the `index.html` file in your web browser
3. The website is ready to use

### Deployment

You can deploy this website to any static hosting service, such as:

- GitHub Pages
- Netlify
- Vercel
- AWS S3
- Google Cloud Storage

### Project Structure

```
photography/
├── index.html          # Main HTML file
├── 31530356_bird_2.svg # Logo SVG
├── 2151657144.jpg      # About section image
├── font-options.md     # Font configuration notes
└── README.md           # This file
```

## Customization

### Updating Content

1. **Hero Section**: Modify lines 376-399 in `index.html`
2. **About Section**: Modify lines 402-463 in `index.html`
3. **Gallery**: Update the gallery items in lines 503-695 in `index.html`
4. **Insights**: Modify lines 696-785 in `index.html`
5. **Gear**: Update the gear list in lines 786-875 in `index.html`
6. **Classes**: Modify lines 876-965 in `index.html`
7. **Contact**: Update the contact form in lines 966-1055 in `index.html`
8. **Testimonials**: Update the testimonials in lines 1056-1145 in `index.html`

### Changing Colors

Modify the Tailwind CSS configuration in lines 22-47 in `index.html`:

```javascript
tailwind.config = {
  theme: {
    extend: {
      colors: {
        dark: {
          900: "#0a0a0a",
          800: "#111111",
          700: "#1a1a1a",
          600: "#242424",
          500: "#2e2e2e",
        },
        accent: {
          DEFAULT: "#c8a45e",
          light: "#dbb96e",
          dark: "#b08d4a",
        },
      },
    },
  },
};
```

### Adding Images

1. Replace the existing images in the project folder
2. Update the `src` attributes in the HTML file
3. For the gallery, ensure images have appropriate aspect ratios

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Performance

- Optimized for fast loading
- Images are loaded from CDN with appropriate dimensions
- CSS and JavaScript are minified and optimized
- Responsive images for different screen sizes

## License

MIT License - feel free to use this project for your own portfolio.

## Credits

- **Design**: Original design by the developer
- **Fonts**: Google Fonts (Syne, Outfit)
- **Images**: Picsum Photos
- **Icons**: SVG icons from Heroicons

## Contact

For any questions or feedback, please contact:

- Email: [contact@skylinecapture.com](mailto:contact@skylinecapture.com)
- Instagram: [@skylinecapture](https://instagram.com/skylinecapture)
- Facebook: [Skyline Capture](https://facebook.com/skylinecapture)

---

Built with ❤️ using HTML, Tailwind CSS, and JavaScript
