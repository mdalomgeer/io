# Academic Personal Website

A clean, modern, and responsive academic personal website template designed for researchers, PhD students, and academics. This website features a professional two-column layout with sections for profile information, affiliations, research interests, publications, and recent news.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI**: Clean, professional design with purple accent colors
- **Easy Customization**: Simple HTML/CSS structure for easy modifications
- **Interactive Elements**: Smooth scrolling, hover effects, and animations
- **SEO Friendly**: Proper HTML structure and meta tags
- **Fast Loading**: Optimized CSS and minimal JavaScript
- **GitHub Pages Ready**: Easy deployment to GitHub Pages

## File Structure

```
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
├── profile.jpg         # Profile picture (you need to add this)
├── README.md           # This file
└── .gitignore          # Git ignore file
```

## Quick Start

1. **Clone or Download** this repository
2. **Add your profile picture** as `profile.jpg` in the root directory
3. **Customize the content** in `index.html` with your information
4. **Deploy to GitHub Pages** (instructions below)

## Customization Guide

### 1. Personal Information
Edit the following sections in `index.html`:

- **Name and Title**: Update the `<h1>` and title in the profile section
- **Email**: Change the email address in contact info and social links
- **Profile Picture**: Replace `profile.jpg` with your photo
- **Research Description**: Update the research introduction text

### 2. Affiliations
Modify the affiliations section with your:
- Current position
- Educational background
- Work experience
- Awards and honors

### 3. Publications
Update the publications section with:
- Paper titles
- Authors
- Venues
- Links to PDFs, arXiv, code, etc.

### 4. Recent News
Add your latest updates, achievements, and news items with dates.

### 5. Social Links
Update the social media links in the header and footer with your actual profiles:
- Google Scholar
- GitHub
- LinkedIn
- Twitter
- YouTube
- WhatsApp

### 6. Colors and Styling
The website uses a purple color scheme (`#6b46c1`). To change colors, edit the CSS variables in `styles.css`:

```css
/* Main accent color */
.btn-primary {
    background-color: #6b46c1; /* Change this to your preferred color */
}
```

## Deployment to GitHub Pages

### Method 1: Using GitHub Desktop
1. Create a new repository on GitHub
2. Clone it to your local machine
3. Copy all files from this template to the repository folder
4. Commit and push to GitHub
5. Go to repository Settings → Pages
6. Select "Deploy from a branch" and choose "main" branch
7. Your site will be available at `https://yourusername.github.io/repository-name`

### Method 2: Using Command Line
```bash
# Initialize git repository
git init

# Add all files
git add .

# Commit changes
git commit -m "Initial commit"

# Add remote repository (replace with your GitHub repo URL)
git remote add origin https://github.com/yourusername/your-repo-name.git

# Push to GitHub
git push -u origin main

# Enable GitHub Pages in repository settings
```

### Method 3: Direct Upload
1. Create a new repository on GitHub
2. Upload all files directly through the GitHub web interface
3. Enable GitHub Pages in repository settings

## Custom Domain (Optional)

To use a custom domain (e.g., `yourname.com`):

1. Purchase a domain from a domain registrar
2. In your GitHub repository settings, go to Pages
3. Add your custom domain in the "Custom domain" field
4. Create a `CNAME` file in your repository root with your domain name
5. Configure DNS settings with your domain registrar

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance Optimization

The website is already optimized for performance:
- Minimal CSS and JavaScript
- Optimized images (recommended: compress your profile picture)
- Fast loading fonts from Google Fonts CDN
- Efficient CSS Grid and Flexbox layouts

## Contributing

Feel free to fork this repository and customize it for your needs. If you make improvements that could benefit others, consider submitting a pull request.

## License

This template is free to use for personal and academic purposes. Please credit the original design if you use it in a public project.

## Support

If you encounter any issues or need help customizing the website:

1. Check the browser console for JavaScript errors
2. Ensure all files are in the correct directory structure
3. Verify that your profile picture is named `profile.jpg` and is in the root directory
4. Check that all links in the HTML file are valid

## Future Enhancements

Potential improvements you could add:
- Blog functionality
- Publication search/filter
- Contact form
- Analytics integration
- Dark mode toggle
- Multi-language support
- RSS feed
- Publication citations counter

---

**Happy coding! 🎓** 