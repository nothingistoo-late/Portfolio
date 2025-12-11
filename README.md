# Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript. This template provides a clean and professional design for showcasing your work, skills, and experience.

## Features

- **Responsive Design**: Fully responsive layout that works on all devices
- **Modern UI/UX**: Clean and professional interface with smooth animations
- **Portfolio Showcase**: Display your projects with filtering capabilities
- **Skills Section**: Highlight your technical and soft skills
- **Contact Form**: Integrated contact form for inquiries
- **Smooth Scrolling**: Smooth navigation between sections
- **Customizable**: Easy to customize colors, content, and layout

## Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with custom properties and animations
- **JavaScript**: Interactive features and animations
- **Bootstrap 5**: Responsive grid system and components
- **Bootstrap Icons**: Icon library
- **AOS (Animate On Scroll)**: Scroll animations
- **Typed.js**: Typing animation effects
- **Isotope**: Portfolio filtering
- **GLightbox**: Image lightbox gallery

## Project Structure

```
portfolio/
├── index.html              # Main HTML file
├── assets/
│   ├── css/
│   │   └── main.css        # Main stylesheet
│   ├── js/
│   │   └── main.js         # Main JavaScript file
│   ├── img/                # Images and assets
│   └── vendor/             # Third-party libraries
├── forms/                  # Contact form handler
└── README.md               # This file
```

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- A local web server (optional, for development)

### Installation

1. Clone or download this repository
2. Extract the files to your desired location
3. Open `index.html` in your web browser

### Local Development

For local development, you can use a simple HTTP server:

**Using Python:**
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

**Using Node.js:**
```bash
npx http-server
```

**Using PHP:**
```bash
php -S localhost:8000
```

Then open `http://localhost:8000` in your browser.

## Customization

### Updating Content

1. **Personal Information**: Edit the content in `index.html`
   - Update name, title, and description in the Hero section
   - Modify About section with your information
   - Add your projects to the Portfolio section
   - Update contact information

2. **Skills**: Edit the Skills section to reflect your technical skills

3. **Projects**: Add your projects in the Portfolio section with images and links

4. **Social Links**: Update social media links in the header and footer

### Changing Colors

The color scheme can be customized by modifying CSS variables in the `<style>` section of `index.html`:

```css
:root {
  --accent-color: #6ba3d8;        /* Primary accent color */
  --accent-color-alt: #8bc4e8;   /* Secondary accent color */
}
```

### Adding Sections

To add new sections:

1. Create a new section in `index.html` following the existing pattern
2. Add a navigation link in the nav menu
3. Update the section with your content

### Images

Replace placeholder images in `assets/img/` with your own:
- `my-profile-img.jpg`: Your profile picture
- `hero-bg.jpg`: Hero section background
- `portfolio/`: Project screenshots

## Features Breakdown

### Hero Section
- Animated typing effect for job titles
- Background image support
- Social media links

### About Section
- Personal introduction
- Profile image
- Key information

### Skills Section
- Technical skills organized by categories
- Soft skills display
- Modern card-based layout

### Services Section
- Service offerings
- Icon-based presentation

### Resume Section
- Work experience
- Education
- Certifications
- Projects

### Portfolio Section
- Project showcase with filtering
- Image gallery
- Project links

### Contact Section
- Contact information
- Contact form
- Map integration

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Opera (latest)

## Performance

- Optimized images
- Lazy loading for images
- Minified vendor files
- Efficient CSS and JavaScript

## License

This project is open source and available under the [MIT License](https://opensource.org/licenses/MIT).

## Credits

- Template based on iPortfolio by BootstrapMade
- Icons by Bootstrap Icons
- Fonts by Google Fonts

## Support

For issues, questions, or contributions, please open an issue in the repository.

## Version

Current version: 1.0.0

---

**Note**: Remember to update all placeholder content, images, and links with your own information before deploying.

