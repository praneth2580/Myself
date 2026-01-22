# Praneth V. Pujari - Portfolio

A modern, responsive portfolio website showcasing my work as a FullStack Developer and Android Developer. Built with HTML, CSS, JavaScript, and Tailwind CSS.

## 🚀 Features

- **Responsive Design**: Fully responsive layout that works seamlessly on desktop, tablet, and mobile devices
- **Dark/Light Mode**: Toggle between dark and light themes with persistent preference storage
- **Smooth Animations**: Scroll-triggered animations and smooth transitions throughout the site
- **Dynamic Project Loading**: Projects are dynamically loaded from JSON and displayed with filtering capabilities
- **Modern UI/UX**: Clean, modern interface with glassmorphism effects and smooth interactions
- **Performance Optimized**: Efficient code with lazy loading and optimized animations

## 📋 Sections

1. **Hero Section**: Introduction with call-to-action buttons
2. **Selected Works**: Showcase of featured projects
3. **Services**: Frontend Development, Backend Engineering, and Android Development
4. **Experience**: Professional work history timeline
5. **Tech Stack**: Technologies and tools I work with
6. **Highlights**: Key achievements and statistics
7. **Contact**: Get in touch section with social links

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Custom styles and animations
- **JavaScript (ES6+)**: Dynamic functionality and interactions
- **Tailwind CSS**: Utility-first CSS framework
- **Google Fonts**: Playfair Display, Inter, Space Grotesk, JetBrains Mono
- **Material Symbols**: Icon library

## 📁 Project Structure

```
.
├── index.html          # Main portfolio page
├── projects.html       # All projects page with filtering
├── projects.json       # Project data in JSON format
├── favicon.svg        # Site favicon
├── styles.css         # Additional custom styles
├── LICENSE            # MIT License
└── README.md          # This file
```

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- A local web server (optional, for development)

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd Myself
```

2. Open `index.html` in your web browser, or use a local server:
```bash
# Using Python
python -m http.server 8000

# Using Node.js (http-server)
npx http-server

# Using PHP
php -S localhost:8000
```

3. Navigate to `http://localhost:8000` in your browser

## 📝 Customization

### Updating Personal Information

1. **Name and Title**: Edit the hero section in `index.html`
2. **Experience**: Update the experience section with your work history
3. **Projects**: Modify `projects.json` to add/update your projects
4. **Contact Info**: Update email and GitHub URL in the JavaScript section

### Changing Colors

The color scheme is defined in the Tailwind config within `index.html`. Modify the `colors` object to change the theme:

```javascript
colors: {
    "primary": "#0d59f2",
    "primary-light": "#3b82f6",
    // ... other colors
}
```

### Adding Projects

Edit `projects.json` to add new projects:

```json
{
  "id": "project-id",
  "name": "Project Name",
  "description": "Project description",
  "category": "Web",
  "tags": ["React", "TypeScript"],
  "language": "TypeScript",
  "url": "https://github.com/username/project",
  "license": "MIT",
  "updated": "2026-01-01",
  "image": "project-image-url",
  "featured": true
}
```

## 🎨 Features in Detail

### Dark/Light Mode
- Automatic theme detection based on system preferences
- Manual toggle button in navigation
- Theme preference saved in localStorage

### Animations
- Scroll-triggered fade-in animations
- Staggered animations for grid items
- Smooth hover effects
- Page load animations

### Project Filtering
- Filter projects by category (All, Web, Mobile, AI/ML, Security, Game)
- Pagination with "Load More" functionality
- Smooth transitions between filters

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👤 Author

**Praneth Vasudeo Pujari**

- Portfolio: [View Live](https://your-portfolio-url.com)
- GitHub: [@praneth2580](https://github.com/praneth2580)
- Email: praneth2580@gmail.com

## 🙏 Acknowledgments

- [Tailwind CSS](https://tailwindcss.com/) for the utility-first CSS framework
- [Google Fonts](https://fonts.google.com/) for beautiful typography
- [Material Symbols](https://fonts.google.com/icons) for icons

---

⭐ If you like this portfolio, please give it a star!
