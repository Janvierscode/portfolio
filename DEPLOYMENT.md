# Deployment Guide

This guide will help you deploy your Jekyll portfolio to GitHub Pages.

## Prerequisites

### Local Development Setup

1. **Install Ruby** (if you want to test locally):
   - Windows: Download from [RubyInstaller](https://rubyinstaller.org/)
   - macOS: Use Homebrew: `brew install ruby`
   - Linux: Use your package manager: `sudo apt-get install ruby-full`

2. **Install Bundler**:
   ```bash
   gem install bundler
   ```

3. **Install Dependencies**:
   ```bash
   cd portfolio
   bundle install
   ```

4. **Run Locally** (optional):
   ```bash
   bundle exec jekyll serve
   ```
   Then visit `http://localhost:4000`

## GitHub Pages Deployment

### Method 1: Direct Push (Recommended)

1. **Create GitHub Repository**:
   - Go to GitHub and create a new repository
   - Name it `your-username.github.io` for a user site, or any name for a project site
   - Make it public

2. **Initialize Git and Push**:
   ```bash
   cd portfolio
   git init
   git add .
   git commit -m "Initial portfolio commit"
   git branch -M main
   git remote add origin https://github.com/your-username/your-repo-name.git
   git push -u origin main
   ```

3. **Enable GitHub Pages**:
   - Go to repository Settings → Pages
   - Source: Deploy from a branch
   - Branch: main / (root)
   - Save

4. **Wait for Deployment**:
   - GitHub Actions will automatically build and deploy your site
   - Check the Actions tab for build status
   - Your site will be available at `https://your-username.github.io/repo-name`

### Method 2: Using GitHub Actions (Already Set Up)

The repository includes a GitHub Actions workflow (`.github/workflows/jekyll.yml`) that will automatically build and deploy your site when you push to the main branch.

## Post-Deployment Checklist

### 1. Add Real Images
Replace placeholder image paths in project files:
- Add actual project screenshots to `assets/images/`
- Update image paths in project markdown files
- Optimize images for web (under 500KB each)

### 2. Update Configuration
- Change `url` in `_config.yml` to your actual GitHub Pages URL
- Update `github_username` and social links
- Add Google Analytics ID if desired

### 3. Customize Content
- Replace placeholder text with your actual information
- Add your real GitHub repository links
- Update project dates and status
- Add your actual email and contact information

### 4. Test Functionality
- Check all navigation links
- Verify responsive design on mobile devices
- Test contact email copying functionality
- Validate all project links

## Common Issues and Solutions

### Build Errors
- Check the Actions tab in GitHub for specific error messages
- Ensure all image paths are correct
- Verify YAML front matter syntax in markdown files

### Styling Issues
- Clear browser cache if styles don't update
- Check for CSS syntax errors in `assets/css/style.css`
- Ensure all CSS variables are properly defined

### Image Loading Problems
- Verify image file names match exactly (case-sensitive)
- Check that images are in the correct directory
- Use relative paths starting with `/assets/images/`

## Performance Optimization

### Images
1. Compress images using tools like:
   - [TinyPNG](https://tinypng.com/)
   - [ImageOptim](https://imageoptim.com/)
   - [Squoosh](https://squoosh.app/)

2. Consider using WebP format for modern browsers

3. Add responsive images for different screen sizes

### SEO
1. Add meta descriptions to pages
2. Include alt text for all images
3. Submit sitemap to Google Search Console
4. Add structured data markup

### Analytics
1. Add Google Analytics:
   ```yaml
   # In _config.yml
   google_analytics: YOUR_GA_TRACKING_ID
   ```

2. Track important metrics:
   - Page views and user sessions
   - Most popular projects
   - User engagement and bounce rate

## Maintenance

### Regular Updates
- Keep Jekyll and dependencies updated
- Add new projects as you complete them
- Update skills and technologies
- Refresh project screenshots and descriptions

### Security
- Regularly update dependencies in `Gemfile`
- Monitor GitHub security alerts
- Use HTTPS for all external links

## Next Steps

1. **Deploy to GitHub Pages** using the steps above
2. **Add real project images** and data
3. **Test thoroughly** on different devices and browsers
4. **Share your portfolio** on professional networks
5. **Keep updating** with new projects and skills

## Support

If you encounter issues:
1. Check GitHub Actions logs for build errors
2. Review Jekyll documentation: https://jekyllrb.com/docs/
3. GitHub Pages documentation: https://docs.github.com/en/pages
4. Jekyll themes and customization guides

Your portfolio is now ready for professional use! 🚀
