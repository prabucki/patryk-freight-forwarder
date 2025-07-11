# Patryk - Professional Road Freight Forwarder Website

A modern, responsive website showcasing Patryk's professional road freight forwarding services across Europe.

## 🚛 Features

- **Professional Design**: Modern, clean layout with navy blue color scheme matching Patryk's professional image
- **Responsive**: Works perfectly on desktop, tablet, and mobile devices
- **Interactive Elements**: Animated truck, Europe map with route visualization, and smooth scrolling
- **Freight Forwarding Focus**: Industry-specific content, services, and portfolio examples
- **Contact Form**: Professional contact form with validation
- **Visual Animations**: Engaging graphics including floating icons, animated routes, and interactive elements

## 📁 Project Structure

```
stronkaPatrola/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and animations
├── script.js           # JavaScript functionality
├── Photo.png           # Patryk's professional photo
└── README.md           # This file
```

## 🚀 Deployment to GitHub Pages

### Method 1: Using GitHub Web Interface (Recommended)

1. **Create a new repository on GitHub**:
   - Go to [GitHub](https://github.com)
   - Click "New" or "+" → "New repository"
   - Name it `patryk-freight-forwarder` (or any name you prefer)
   - Make it **Public**
   - Don't initialize with README (we already have files)

2. **Upload your files**:
   - Click "uploading an existing file"
   - Drag and drop all files: `index.html`, `styles.css`, `script.js`, `Photo.png`, `README.md`
   - Add commit message: "Initial website deployment"
   - Click "Commit changes"

3. **Enable GitHub Pages**:
   - Go to repository "Settings" tab
   - Scroll down to "Pages" section
   - Under "Source", select "Deploy from a branch"
   - Select "main" branch and "/ (root)" folder
   - Click "Save"

4. **Access your website**:
   - Your site will be available at: `https://yourusername.github.io/repository-name`
   - GitHub will show you the exact URL in the Pages settings

### Method 2: Using Git Command Line

If you have Git installed:

```bash
# Navigate to your project folder
cd /Users/tom/Downloads/stronkaPatrola

# Initialize git repository
git init

# Add all files
git add .

# Commit files
git commit -m "Initial website deployment"

# Add remote repository (replace with your GitHub repo URL)
git remote add origin https://github.com/yourusername/patryk-freight-forwarder.git

# Push to GitHub
git push -u origin main
```

Then follow step 3 from Method 1 to enable GitHub Pages.

## 🌐 Custom Domain (Optional)

If you want to use a custom domain:

1. Add a `CNAME` file to your repository with your domain name
2. Configure your domain's DNS settings to point to GitHub Pages
3. Update the custom domain in repository settings

## 🔧 Local Development

To run locally:
1. Simply open `index.html` in your web browser
2. Or use a local server like Live Server extension in VS Code

## 📱 Browser Compatibility

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers

## 🎨 Customization

To customize the website:
- **Colors**: Edit CSS variables in `styles.css`
- **Content**: Update text in `index.html`
- **Images**: Replace `Photo.png` with your own image
- **Contact Info**: Update contact details in the contact section

## 📞 Contact Information

Remember to update the contact information in the website:
- Email address
- Phone number
- Location
- Social media links

## 🚀 Go Live!

Once deployed, your professional freight forwarding website will be live and accessible worldwide!
