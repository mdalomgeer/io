# Md Alomgeer Hussein - Academic Portfolio

A clean, professional academic portfolio website designed for job search and academic networking. This website showcases research experience, technical skills, and projects in a professional manner similar to [roydipta.com](https://roydipta.com/).

## Features

- **Professional Design**: Clean, academic-focused layout
- **Job-Search Optimized**: Minimal animations, professional appearance
- **Responsive Design**: Works perfectly on all devices
- **Easy Customization**: Simple HTML/CSS structure
- **Professional Links**: LinkedIn, GitHub, Google Scholar, Email integration
- **Project Showcase**: Dedicated sections for research projects
- **Contact Form**: Professional contact interface

## File Structure

```
├── index.html              # Main website
├── styles.css              # Professional styling
├── script.js               # Essential functionality
├── resume.pdf              # Your resume (replace with actual file)
├── cv.pdf                  # Your CV (replace with actual file)
├── profile.jpg             # Your profile picture
├── about-image.jpg         # About section image
├── project1.jpg            # CKD project image
├── project2.jpg            # Parkinson's project image
├── project3.jpg            # Driver detection project image
├── project1-demo.html      # CKD project demo page
├── project2-paper.pdf      # Parkinson's research paper
├── project3-demo.html      # Driver detection demo page
├── README.md               # This file
└── .gitignore              # Git ignore file
```

## Quick Setup

### 1. Replace Placeholder Content
Update the following in `index.html`:

- **Personal Information**: Name, email, location
- **Social Links**: Replace placeholder URLs with your actual profiles
- **About Section**: Update research description
- **Experience**: Modify timeline with your actual experience
- **Projects**: Update project descriptions and links

### 2. Add Your Files
Replace the placeholder files with your actual content:

- `resume.pdf` - Your professional resume
- `cv.pdf` - Your academic CV
- `profile.jpg` - Your professional headshot
- `about-image.jpg` - Research-related image
- `project1.jpg`, `project2.jpg`, `project3.jpg` - Project screenshots

### 3. Update Social Links
Replace these placeholder URLs with your actual profiles:

```html
<!-- LinkedIn -->
<a href="https://linkedin.com/in/your-actual-profile">...</a>

<!-- GitHub -->
<a href="https://github.com/your-actual-username">...</a>

<!-- Google Scholar -->
<a href="https://scholar.google.com/citations?user=your-actual-id">...</a>

<!-- Email -->
<a href="mailto:your-actual-email@domain.com">...</a>
```

### 4. Update Project Links
Replace GitHub repository URLs with your actual project repositories:

```html
<!-- Example -->
<a href="https://github.com/your-username/ckd-prediction">...</a>
<a href="https://github.com/your-username/parkinsons-detection">...</a>
<a href="https://github.com/your-username/driver-fatigue-detection">...</a>
```

## Customization Guide

### Colors
The website uses a professional blue color scheme. To change colors, edit the CSS variables in `styles.css`:

```css
:root {
    --primary-color: #2563eb;    /* Main blue */
    --secondary-color: #1e40af;  /* Darker blue */
    --accent-color: #3b82f6;     /* Light blue */
}
```

### Content Sections
- **Hero Section**: Your name, title, and brief introduction
- **About Section**: Detailed research background and statistics
- **Skills Section**: Technical skills with progress bars
- **Experience Timeline**: Academic and work experience
- **Projects Section**: Featured research projects
- **Contact Section**: Contact information and form

### Professional Links
The website includes links to:
- **LinkedIn**: Professional networking
- **GitHub**: Code repositories
- **Google Scholar**: Academic publications
- **Email**: Direct contact
- **Resume/CV**: Downloadable documents

## Deployment to GitHub Pages

### Method 1: Using GitHub Web Interface
1. Create a new repository on GitHub
2. Upload all files through the web interface
3. Go to Settings → Pages
4. Select "Deploy from a branch" and choose "main"
5. Your site will be live at `https://yourusername.github.io/repository-name`

### Method 2: Using Command Line
```bash
git init
git add .
git commit -m "Initial portfolio setup"
git remote add origin https://github.com/yourusername/your-repo-name.git
git push -u origin main
```

## Professional Features

### For Job Search
- **Clean Design**: Professional appearance for recruiters
- **Clear Navigation**: Easy to find information
- **Downloadable Documents**: Resume and CV readily available
- **Project Showcase**: Demonstrates technical skills
- **Contact Information**: Multiple ways to reach you

### For Academic Networking
- **Research Focus**: Highlights academic achievements
- **Publication Links**: Easy access to your work
- **Professional Credentials**: Clear presentation of qualifications
- **Collaboration Ready**: Contact form for research inquiries

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Performance

- Minimal JavaScript for fast loading
- Optimized CSS for smooth performance
- Professional fonts from Google Fonts CDN
- Responsive images and layouts

## SEO Optimization

- Semantic HTML structure
- Proper meta tags
- Clean URLs
- Fast loading times
- Mobile-friendly design

## Support

If you need help customizing the website:

1. Check that all file paths are correct
2. Verify that image files are in the correct format (JPG/PNG)
3. Ensure PDF files are properly linked
4. Test all social media links

## License

This template is free to use for personal and academic purposes.

---

**Your professional academic portfolio is ready for deployment! 🎓** 