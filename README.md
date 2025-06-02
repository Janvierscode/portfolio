# Data Analyst Portfolio - Janvier Iyakaremye

[![Jekyll site CI](https://github.com/janvierscode/portfolio/actions/workflows/jekyll.yml/badge.svg)](https://github.com/janvierscode/portfolio/actions/workflows/jekyll.yml)
[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-deployed-brightgreen)](https://janvierscode.github.io)

> A professional portfolio website showcasing data analysis expertise with a focus on financial markets and business intelligence.

## 🚀 Live Demo

Visit the live portfolio: [https://janvierscode.github.io](https://janvierscode.github.io)

## 📋 About This Portfolio

This portfolio demonstrates expertise in:

- **Financial Data Analysis** - Stock market analysis, risk assessment, portfolio optimization
- **Machine Learning** - Predictive modeling, classification, clustering
- **Data Visualization** - Interactive dashboards using Tableau, Power BI, and Python
- **Programming Skills** - Python, R, SQL, Excel with advanced analytics

## 🛠️ Built With

- **Jekyll** - Static site generator
- **GitHub Pages** - Hosting platform
- **HTML5 & CSS3** - Modern responsive design
- **JavaScript** - Interactive functionality
- **Font Awesome** - Icons and visual elements

## 📁 Project Structure

```
portfolio/
├── _layouts/           # Jekyll layout templates
├── _projects/          # Individual project pages
├── assets/
│   ├── css/           # Custom stylesheets
│   ├── js/            # JavaScript functionality
│   └── images/        # Images and visual assets
├── .github/
│   └── workflows/     # GitHub Actions for automated deployment
├── _config.yml        # Jekyll configuration
├── index.md           # Homepage
├── about.md           # About page
├── projects.md        # Projects overview
├── skills.md          # Skills and expertise
├── contact.md         # Contact information
└── README.md          # This file
```

## 🚀 Featured Projects

### 1. Stock Market Performance Analysis
- Comprehensive analysis of historical stock data
- Risk metrics and performance comparisons
- Interactive Tableau dashboards
- **Technologies**: Python, Pandas, Tableau, yfinance

### 2. Personal Finance Dashboard
- Interactive dashboard for spending pattern analysis
- Budget tracking and financial goal monitoring
- Automated transaction categorization
- **Technologies**: Power BI, Excel, Python, SQL

### 3. Credit Risk Analysis
- Machine learning model for loan default prediction
- Feature engineering and model evaluation
- Advanced classification algorithms
- **Technologies**: Python, Scikit-learn, Random Forest

### 4. Financial News Sentiment Analysis
- NLP-powered sentiment analysis of financial news
- Market trend prediction using sentiment scores
- API integration for real-time data
- **Technologies**: Python, NLP, VADER, API Integration

## 🔧 Local Development

### Prerequisites

- Ruby (version 3.0+)
- Bundler gem
- Git

### Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/janvierscode/portfolio.git
   cd portfolio
   ```

2. **Install dependencies**
   ```bash
   bundle install
   ```

3. **Run locally**
   ```bash
   bundle exec jekyll serve
   ```

4. **Open in browser**
   ```
   http://localhost:4000
   ```

### Making Changes

1. **Content Updates**: Edit Markdown files in the root directory
2. **Styling**: Modify CSS in `assets/css/style.css`
3. **Projects**: Add new projects in the `_projects/` directory
4. **Configuration**: Update `_config.yml` for site settings

## 📦 GitHub Pages Deployment

This portfolio is configured for automatic deployment to GitHub Pages using GitHub Actions.

### Deployment Steps

1. **Fork or clone** this repository
2. **Update `_config.yml`** with your information:
   ```yaml
   title: Your Name
   email: your.email@example.com
   github_username: yourusername
   linkedin_username: yourusername
   url: "https://yourusername.github.io"
   ```
3. **Enable GitHub Pages** in repository settings
4. **Push changes** to trigger automatic deployment

### Custom Domain (Optional)

To use a custom domain:

1. Add a `CNAME` file with your domain name
2. Configure DNS settings with your domain provider
3. Enable HTTPS in GitHub Pages settings

## 🎨 Customization

### Colors and Styling

Update CSS variables in `assets/css/style.css`:

```css
:root {
    --primary-color: #2563eb;
    --secondary-color: #64748b;
    --accent-color: #f59e0b;
    /* ... other variables */
}
```

### Adding New Projects

1. Create a new file in `_projects/`
2. Use the following front matter:
   ```yaml
   ---
   layout: project
   title: Your Project Title
   subtitle: Brief description
   technologies: [Python, SQL, Tableau]
   github_url: https://github.com/username/project
   demo_url: https://demo-link.com
   ---
   ```

### Contact Information

Update contact details in:
- `_config.yml` - Site-wide settings
- `contact.md` - Contact page content
- `_layouts/default.html` - Footer links

## 📊 Analytics and SEO

The portfolio includes:
- **SEO optimization** with meta tags and structured data
- **Google Analytics** support (add tracking ID in `_config.yml`)
- **Social media** integration for sharing
- **Performance optimization** with compressed assets

## 🤝 Contributing

Contributions are welcome! Please feel free to:

1. **Fork** the repository
2. **Create** a feature branch
3. **Commit** your changes
4. **Push** to the branch
5. **Open** a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📞 Contact

**Janvier Iyakaremye**
- 📧 Email: iyakaremyejanvier@gmail.com
- 💼 LinkedIn: [linkedin.com/in/janvierscode](https://www.linkedin.com/in/janvierscode/)
- 🐙 GitHub: [github.com/Janvierscode](https://github.com/Janvierscode)

---

## 🙏 Acknowledgments

- Jekyll community for the excellent static site generator
- GitHub for free hosting with GitHub Pages
- Font Awesome for beautiful icons
- The data science community for inspiration and knowledge sharing

---

**Built with ❤️ by Janvier Iyakaremye**
    *   Go to your repository settings on GitHub.
    *   Navigate to the "Pages" section in the left sidebar.
    *   Under "Build and deployment," select "Deploy from a branch" as the source.
    *   Choose the branch you pushed your code to (e.g., `main` or `master`).
    *   Select `/ (root)` as the folder.
    *   Click "Save".
    *   GitHub Pages will build your site. It might take a few minutes. Your portfolio will be available at `https://your-github-username.github.io/your-repository-name/`.

6.  **Review and Iterate:**
    *   Check your live portfolio for any formatting issues or broken links.
    *   Ask for feedback from peers or mentors.
    *   Continue to update and refine your projects and portfolio content.

Good luck building your portfolio!
```
