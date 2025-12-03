# Elite Property Management Website

A professional Airbnb property management portfolio website.

## Features
- Full-service showcase from property acquisition to guest management
- Responsive design
- Contact form
- Featured properties section

## Deployment Instructions

### Deploy to GitHub Pages

1. Initialize git repository:
```bash
git init
git add .
git commit -m "Initial commit"
```

2. Add your GitHub repository as remote (replace with your repository URL):
```bash
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git
git branch -M main
git push -u origin main
```

3. Enable GitHub Pages:
   - Go to your repository on GitHub
   - Click "Settings"
   - Scroll to "Pages" in the left sidebar
   - Under "Source", select "main" branch
   - Click "Save"
   - Your site will be live at: `https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/`

## Files
- `index.html` - Main website file
- `styles.css` - Styling
- `script.js` - JavaScript functionality
- `property1.jpg` - Property image

## Contact Form Setup
Currently the contact form shows an alert. To collect submissions:
1. Set up Google Sheets with Apps Script (see instructions in documentation)
2. Or use a service like Formspree, Getform, or Web3Forms
