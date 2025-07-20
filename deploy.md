# Deployment Guide

## Quick Deployment Steps

### Step 1: Prepare Your Files
1. Make sure you have all the required files:
   - `index.html`
   - `styles.css`
   - `script.js`
   - `README.md`
   - `profile.jpg` (your profile picture)

### Step 2: Create GitHub Repository
1. Go to [GitHub.com](https://github.com)
2. Click "New repository"
3. Name it `yourusername.github.io` (for custom domain) or any name you prefer
4. Make it public
5. Don't initialize with README (we already have one)

### Step 3: Upload Files
**Option A: Using GitHub Web Interface**
1. Go to your new repository
2. Click "uploading an existing file"
3. Drag and drop all your files
4. Commit the changes

**Option B: Using Git Command Line**
```bash
# Clone the repository
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name

# Copy all files to this directory
# (Copy index.html, styles.css, script.js, README.md, profile.jpg)

# Add and commit files
git add .
git commit -m "Initial website setup"
git push origin main
```

### Step 4: Enable GitHub Pages
1. Go to your repository on GitHub
2. Click "Settings" tab
3. Scroll down to "Pages" section
4. Under "Source", select "Deploy from a branch"
5. Choose "main" branch
6. Click "Save"

### Step 5: Access Your Website
- If repository name is `yourusername.github.io`: `https://yourusername.github.io`
- If repository name is anything else: `https://yourusername.github.io/repository-name`

## Custom Domain Setup (Optional)

### Step 1: Purchase Domain
Buy a domain from providers like:
- Namecheap
- GoDaddy
- Google Domains
- Cloudflare

### Step 2: Configure GitHub Pages
1. In your repository Settings → Pages
2. Add your custom domain in the "Custom domain" field
3. Save the changes

### Step 3: Create CNAME File
GitHub will automatically create a `CNAME` file with your domain name.

### Step 4: Configure DNS
Add these DNS records with your domain provider:

**For apex domain (yourdomain.com):**
```
Type: A
Name: @
Value: 185.199.108.153
Value: 185.199.109.153
Value: 185.199.110.153
Value: 185.199.111.153
```

**For www subdomain (www.yourdomain.com):**
```
Type: CNAME
Name: www
Value: yourusername.github.io
```

## Troubleshooting

### Website Not Loading
1. Check if GitHub Pages is enabled in repository settings
2. Wait 5-10 minutes for changes to propagate
3. Check the Actions tab for any build errors

### Images Not Showing
1. Ensure image files are in the correct directory
2. Check file names match exactly (case-sensitive)
3. Verify image files are committed to the repository

### Styling Issues
1. Check browser console for CSS errors
2. Ensure `styles.css` is properly linked in `index.html`
3. Clear browser cache

### Custom Domain Not Working
1. Wait up to 24 hours for DNS propagation
2. Verify DNS records are correct
3. Check if CNAME file exists in repository
4. Ensure domain is added in GitHub Pages settings

## Performance Tips

1. **Optimize Images**: Compress your profile picture to under 500KB
2. **Minimize Files**: Keep CSS and JS files small
3. **Use CDN**: Font Awesome and Google Fonts are already using CDN
4. **Enable Compression**: GitHub Pages automatically compresses files

## Analytics (Optional)

To add Google Analytics:
1. Create a Google Analytics account
2. Get your tracking ID
3. Add this code to the `<head>` section of `index.html`:

```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_TRACKING_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_TRACKING_ID');
</script>
```

Replace `GA_TRACKING_ID` with your actual tracking ID.

## Security Considerations

1. **HTTPS**: GitHub Pages automatically provides SSL certificates
2. **No Sensitive Data**: Don't include personal information like phone numbers or addresses
3. **Regular Updates**: Keep your website content updated
4. **Backup**: Regularly backup your website files

## Support

If you encounter issues:
1. Check GitHub Pages documentation
2. Search GitHub Community forums
3. Check browser console for errors
4. Verify all file paths are correct

---

**Your website should be live in 5-10 minutes after following these steps! 🚀** 