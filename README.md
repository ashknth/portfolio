# Modern Portfolio Website

A clean, elegant, and responsive portfolio website built with HTML, CSS, and JavaScript. Features a modern design with soft shadows, smooth animations, and a light/dark mode toggle.

## Features

✨ **Modern Design**
- Clean and minimal aesthetic
- Soft shadows and large rounded corners
- Beautiful gradients and typography
- Google Fonts (Inter) integration

🎨 **Light/Dark Mode**
- Toggle between light and dark themes
- Preferences saved in localStorage
- Smooth theme transitions

📱 **Fully Responsive**
- Mobile-first design approach
- Optimized for all screen sizes
- Touch-friendly navigation

🚀 **Smooth Animations**
- Scroll reveal animations
- Hover effects and transitions
- Floating avatar animation
- Parallax background effects

⚡ **Performance Optimized**
- Efficient CSS Grid and Flexbox layouts
- Intersection Observer for animations
- Throttled scroll events
- Image preloading

## Sections

1. **Hero Section** - Welcome message with gradient text and professional avatar
2. **About Me** - Bio, workspace image, and skills showcase
3. **Experience** - Timeline of work experience with tags
4. **Projects** - 6 featured project cards with hover effects
5. **Gallery** - Grid of beautiful placeholder images
6. **Contact** - Contact form and social media links
7. **Footer** - Simple footer with copyright

## Getting Started

1. **Clone or download** the files to your local machine
2. **Open `index.html`** in your web browser
3. The website is ready to use!

## Customization

### Personal Information

Edit the content in `index.html`:

- Replace "Alex Doe" with your name
- Update the hero section text and description
- Replace the avatar image URL
- Update the about section bio
- Modify work experience entries
- Add your real projects and links
- Update contact information and social links

### Images

Replace the Unsplash placeholder images with your own:

```html
<!-- Hero Avatar -->
<img src="your-photo.jpg" alt="Your Name" class="avatar">

<!-- Project Images -->
<img src="project1-screenshot.jpg" alt="Project Name">
```

### Colors and Styling

Customize the design in `styles.css`:

```css
:root {
  --primary-color: #6366f1;    /* Main brand color */
  --secondary-color: #10b981;  /* Accent color */
  --gradient-primary: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
}
```

### Skills Section

Update your skills in the HTML:

```html
<div class="skill-item">
  <i class="fab fa-your-icon"></i>
  <span>Your Skill</span>
</div>
```

## File Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # All CSS styles
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with Grid/Flexbox
- **JavaScript ES6+** - Interactive functionality
- **Font Awesome** - Icons
- **Google Fonts** - Typography
- **Unsplash** - Placeholder images

## Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers

## Performance Features

- Lazy loading for images
- Optimized animations
- Minimal JavaScript bundle
- Efficient CSS
- Scroll performance optimization

## Deployment

You can deploy this website to any static hosting service:

- **GitHub Pages** - Free hosting for public repositories
- **Netlify** - Drag and drop deployment
- **Vercel** - Git-based deployment
- **Surge.sh** - Simple command-line deployment

## Contributing

Feel free to customize this template for your own use. Some ideas for enhancements:

- Add a blog section
- Integrate with a CMS
- Add more interactive animations
- Include a testimonials section
- Add project filtering functionality

## License

This project is open source and available under the MIT License.

---

**Happy coding!** 🚀

For questions or suggestions, feel free to reach out through the contact form on the website.