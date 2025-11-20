# Polk Group Website

A modern, responsive website built for Azure Static Web Apps deployment.

## 🚀 Quick Start

### Local Development
1. Open the project folder in VS Code
2. Install the Live Server extension
3. Right-click on `index.html` and select "Open with Live Server"

### Deploy to Azure Static Web Apps

#### Prerequisites
- Azure subscription
- GitHub account
- VS Code with Azure Static Web Apps extension

#### Deployment Steps

1. **Initialize Git Repository** (if not already done):
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   ```

2. **Push to GitHub**:
   ```bash
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
   git branch -M main
   git push -u origin main
   ```

3. **Deploy with Azure Static Web Apps Extension**:
   - Open VS Code Command Palette (Ctrl+Shift+P)
   - Type "Azure Static Web Apps: Create Static Web App..."
   - Follow the prompts:
     - Select your Azure subscription
     - Enter a name for your Static Web App
     - Select your GitHub repository
     - Select the branch (main)
     - Build preset: Custom
     - App location: `/` (root)
     - API location: (leave empty for now)
     - Output location: `/` (since we're serving static files directly)

4. **Automatic Deployment**:
   - Azure will create a GitHub Actions workflow
   - Every push to main branch will trigger automatic deployment
   - Check the Actions tab in your GitHub repository for build status

## 📁 Project Structure

```
WebsitePolk/
├── index.html              # Main HTML file
├── styles.css              # CSS styles
├── script.js               # JavaScript functionality
├── staticwebapp.config.json # Azure SWA configuration
└── README.md               # This file
```

## 🌟 Features

- **Responsive Design**: Works on all devices
- **Modern UI**: Clean, professional appearance
- **Smooth Animations**: Engaging user experience
- **SEO Friendly**: Optimized for search engines
- **Fast Loading**: Optimized assets and caching
- **Azure SWA Ready**: Pre-configured for deployment

## 🔧 Customization

### Content
- Edit `index.html` to update text and structure
- Modify company information in the contact section
- Add your own logo and branding

### Styling
- Update colors in `styles.css`
- Modify fonts and typography
- Adjust layout and spacing

### Functionality
- Add new features in `script.js`
- Integrate with APIs or backend services
- Add contact forms or interactive elements

## 🚀 Azure Static Web Apps Benefits

- **Free Tier Available**: No cost for basic usage
- **Global CDN**: Fast loading worldwide
- **Automatic HTTPS**: Secure by default
- **Custom Domains**: Use your own domain
- **CI/CD Integration**: Automatic deployments from GitHub
- **Staging Environments**: Preview changes before going live

## 📞 Support

For questions about this template or Azure deployment, check the Azure Static Web Apps documentation or contact support.

## 📝 License

This project is licensed under the MIT License.