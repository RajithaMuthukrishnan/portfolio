# My Personal Blog

A modern, responsive blog website built with HTML, CSS, and JavaScript, designed to be hosted on GitHub Pages.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI**: Clean, professional design with smooth animations
- **Interactive Elements**: Smooth scrolling, mobile navigation, contact form
- **SEO Optimized**: Proper meta tags and semantic HTML structure
- **Fast Loading**: Optimized CSS and JavaScript for quick page loads
- **Accessible**: Built with accessibility best practices

## Project Structure

```
blog_site/
├── index.html          # Main homepage
├── css/
│   └── style.css       # Main stylesheet
├── js/
│   └── script.js       # JavaScript functionality
├── posts/              # Blog post pages
│   ├── post1.html
│   ├── post2.html
│   └── post3.html
├── images/             # Image assets (placeholder)
└── README.md           # This file
```

## Getting Started

### Local Development

1. Clone or download this repository
2. Open `index.html` in your web browser
3. Or use a local server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   ```

### Customization

#### Personal Information
- Update contact information in `index.html`
- Replace placeholder content with your own
- Add your own blog posts in the `posts/` directory

#### Styling
- Modify `css/style.css` to change colors, fonts, and layout
- Update the color scheme by changing CSS custom properties
- Add your own branding elements

#### Content
- Replace sample blog posts with your own content
- Update the About section with your information
- Add your own images to the `images/` directory

## GitHub Pages Deployment

### Method 1: Direct Upload
1. Create a new repository on GitHub
2. Upload all files to the repository
3. Go to Settings > Pages
4. Select "Deploy from a branch" and choose "main"
5. Your site will be available at `https://yourusername.github.io/repository-name`

### Method 2: Using Git
1. Initialize a git repository:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   ```

2. Add your GitHub repository as remote:
   ```bash
   git remote add origin https://github.com/yourusername/your-repo-name.git
   git branch -M main
   git push -u origin main
   ```

3. Enable GitHub Pages in repository settings

## Custom Domain (Optional)

To use a custom domain:
1. Add a `CNAME` file with your domain name
2. Configure DNS settings with your domain provider
3. Update GitHub Pages settings to use your custom domain

## Features Overview

### Navigation
- Fixed navigation bar with smooth scrolling
- Mobile-responsive hamburger menu
- Active link highlighting based on scroll position

### Hero Section
- Eye-catching gradient background
- Call-to-action buttons
- Responsive layout

### About Section
- Personal information and statistics
- Clean, professional layout

### Blog Posts
- Card-based layout for blog posts
- Hover effects and animations
- Easy navigation between posts

### Contact Form
- Functional contact form with validation
- Success/error notifications
- Responsive design

### Footer
- Social media links
- Quick navigation
- Copyright information

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Performance

- Optimized CSS and JavaScript
- Minimal external dependencies
- Fast loading times
- Mobile-optimized

## Contributing

Feel free to fork this project and customize it for your own use. If you make improvements that could benefit others, consider submitting a pull request.

## License

This project is open source and available under the [MIT License](LICENSE).

## Support

If you have any questions or need help with customization, feel free to open an issue or contact me.

---

**Happy Blogging!** 🚀
