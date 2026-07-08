# Online Portfolio

A modern, responsive personal portfolio website built with HTML, CSS, and JavaScript.

## Features

- **Responsive Design**: Mobile-friendly layout that works on all devices
- **Smooth Navigation**: Sticky navbar with smooth scrolling
- **Mobile Menu**: Hamburger menu for mobile devices
- **Multiple Sections**:
  - Hero section with call-to-action
  - About me section
  - Skills showcase
  - Projects portfolio
  - Contact information
  - Footer
- **Modern Styling**: Clean, professional design with smooth animations
- **Accessibility**: Semantic HTML and accessibility-friendly code

## Project Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styling
├── script.js           # JavaScript functionality
├── package.json        # Project metadata and scripts
├── README.md           # This file
├── .vscode/
│   └── tasks.json      # VS Code tasks
├── assets/             # Placeholder for images and media
└── .github/
    └── copilot-instructions.md
```

## Getting Started

### Prerequisites

- A modern web browser
- Python 3 (for running the development server) OR Node.js (for npm)

### Installation

1. Clone or open this project in VS Code
2. No additional dependencies needed - the portfolio is built with vanilla HTML, CSS, and JavaScript

### Running the Portfolio

**Option 1: Using Python**
```bash
npm run start
```

**Option 2: Using Node.js**
```bash
npm run serve
```

**Option 3: Manual**
- Open `index.html` directly in your browser
- Or right-click `index.html` and select "Open with Live Server" if you have the Live Server extension

The portfolio will be available at `http://localhost:8000`

## Customization

### Update Your Information

1. **Name and Title**: Edit the hero section in `index.html`
   - Change "Your Name" and job title

2. **About Section**: Update the about content
   - Edit the paragraph text in the about section

3. **Skills**: Add or modify your skills
   - Edit the skill cards in the skills section

4. **Projects**: Add your project information
   - Edit project cards with project names, descriptions, and links

5. **Contact**: Update contact information
   - Replace email and social media links

6. **Styling**: Customize colors
   - Edit CSS variables in `styles.css` (lines 1-10)
   - Available variables:
     - `--primary-color`: Main dark color
     - `--secondary-color`: Blue accent color
     - `--accent-color`: Red accent color

### Adding Media

- Add images to the `assets/` folder
- Reference them in your HTML with relative paths: `<img src="assets/image.png" alt="description">`

## Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Tips for Success

1. **Update placeholder text**: Replace all "Your Name" and placeholder content with your actual information
2. **Add real project links**: Update GitHub and live demo links
3. **Social media links**: Add your actual social media profiles
4. **Profile image**: Add a professional headshot (create an image element in the hero section)
5. **Content**: Make sure descriptions are clear and concise

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Support

For questions or issues, feel free to reach out through the contact section of the portfolio.

---

**Happy building! 🚀**
