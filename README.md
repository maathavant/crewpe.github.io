# CrewPE Website

A professional single-page website for CrewPE - An Agentic Crew of Product and Engineering Team capitalizing the power of LLM, RAG, Agents, MCPs for Autonomous SDLC.

## Live Website

🌐 **[crewpe.com](https://crewpe.com)**

## Features

- **Modern Design**: Clean, professional design with smooth animations
- **Responsive Layout**: Optimized for all devices (desktop, tablet, mobile)
- **Interactive Elements**: Smooth scrolling, hover effects, and dynamic content
- **SEO Optimized**: Proper meta tags and semantic HTML structure
- **Fast Loading**: Optimized CSS and JavaScript for quick page loads
- **Accessibility**: Keyboard navigation and screen reader friendly

## Technologies Used

- **HTML5**: Semantic markup and modern web standards
- **CSS3**: Flexbox, Grid, animations, and responsive design
- **JavaScript**: Interactive features and smooth user experience
- **Font Awesome**: Professional icons
- **Google Fonts**: Inter font family for modern typography

## Project Structure

```
crewpe-website/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript functionality
├── CNAME              # Custom domain configuration
└── README.md          # Project documentation
```

## GitHub Pages Deployment

### Prerequisites

1. **GitHub Account**: Ensure you have a GitHub account
2. **Custom Domain**: You mentioned you already have the domain `crewpe.com`
3. **Domain DNS Access**: Access to your domain's DNS settings

### Step 1: Create GitHub Repository

1. Create a new repository on GitHub
2. Name it something like `crewpe-website` or `crewpe.com`
3. Make sure it's set to **Public** (required for GitHub Pages free tier)

### Step 2: Upload Files

1. Upload all the files from this directory to your GitHub repository:
   - `index.html`
   - `styles.css`
   - `script.js`
   - `CNAME`
   - `README.md`

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on **Settings** tab
3. Scroll down to **Pages** section in the left sidebar
4. Under **Source**, select **Deploy from a branch**
5. Choose **main** branch and **/ (root)** folder
6. Click **Save**

### Step 4: Configure Custom Domain

The `CNAME` file is already configured with `crewpe.com`. GitHub Pages will automatically detect this and set up the custom domain.

1. In the **Pages** settings, you should see your custom domain listed
2. Make sure **Enforce HTTPS** is checked (recommended for security)

### Step 5: Configure DNS Settings

Configure your domain's DNS settings with your domain registrar:

#### Option A: Apex Domain (crewpe.com)
Add these A records pointing to GitHub Pages:
```
185.199.108.153
185.199.109.153
185.199.110.153
185.199.111.153
```

#### Option B: Subdomain (www.crewpe.com)
Add a CNAME record:
```
CNAME: www -> username.github.io
```

### Step 6: Verify Deployment

1. DNS changes may take 24-48 hours to propagate
2. Check your website at `https://crewpe.com`
3. GitHub will automatically generate an SSL certificate

## Local Development

To run the website locally for development:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/crewpe-website.git
   cd crewpe-website
   ```

2. Open `index.html` in your browser or use a local server:
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js (if you have live-server installed)
   npx live-server
   ```

3. Visit `http://localhost:8000` in your browser

## Customization

### Colors
The website uses a gradient color scheme. Main colors:
- Primary: `#667eea` to `#764ba2`
- Background: `#f5f7fa` to `#c3cfe2`
- Text: `#333` (dark) and `#666` (medium)

### Content Updates
- **Hero Section**: Update the main title and description in `index.html`
- **Features**: Modify the features grid to highlight different capabilities
- **Contact Info**: Update email, website, and contact details
- **Company Info**: Adjust the about section content

### Styling
- **Fonts**: Currently using Inter from Google Fonts
- **Layout**: CSS Grid and Flexbox for responsive design
- **Animations**: CSS animations and JavaScript for interactive elements

## SEO Optimization

The website includes:
- Proper meta tags and descriptions
- Semantic HTML structure
- Open Graph tags for social media sharing
- Structured data markup
- Fast loading times
- Mobile-first responsive design

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance

- Optimized images and assets
- Minified CSS and JavaScript (for production)
- Lazy loading for images
- Efficient animations using CSS transforms

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## License

This project is proprietary to CrewPE. All rights reserved.

## Support

For technical support or questions about the website, please contact:
- Email: hello@crewpe.com
- Website: crewpe.com

---

**CrewPE** - Revolutionizing Software Development with Autonomous AI Agents