# Personal-Portfolio

A modern, responsive personal portfolio website to showcase your work, skills, and projects.

## Features

- ✨ Clean and modern design
- 📱 Fully responsive (mobile, tablet, desktop)
- 🎨 Smooth animations and transitions
- 🚀 Fast and lightweight
- 🌐 Ready for deployment on GitHub Pages

## Sections

- **Home**: Eye-catching hero section with call-to-action buttons
- **About**: Tell your story and background
- **Skills**: Showcase your technical skills and expertise
- **Projects**: Display your featured projects with descriptions
- **Contact**: Multiple ways for people to reach you

## Deployment to GitHub Pages

### Option 1: Using GitHub Pages Settings (Recommended)

1. Go to your repository on GitHub
2. Click on **Settings**
3. Scroll down to **Pages** section in the left sidebar
4. Under **Source**, select the branch you want to deploy (usually `main` or `master`)
5. Select the root folder (`/`)
6. Click **Save**
7. Your site will be published at `https://yourusername.github.io/Personal-Portfolio/`

### Option 2: Using GitHub Actions

The repository is already configured for GitHub Pages. Once you push your changes, GitHub will automatically build and deploy your site.

## Customization

### Update Personal Information

Edit `index.html` and replace:
- `Your Name` with your actual name
- `your.email@example.com` with your email address
- GitHub and LinkedIn URLs with your profile links
- Update project descriptions and links

### Change Colors

Edit `styles.css` and modify the CSS variables in the `:root` section:
```css
:root {
    --primary-color: #6366f1;
    --secondary-color: #8b5cf6;
    /* ... other colors */
}
```

### Add Your Projects

In `index.html`, update the projects section with your actual projects:
- Replace placeholder emojis with project images
- Update project titles and descriptions
- Add correct demo and GitHub links

## Local Development

To view the website locally:

1. Clone the repository
2. Open `index.html` in your web browser
3. Or use a local server like `python -m http.server` or Live Server extension in VS Code

## Technologies Used

- HTML5
- CSS3
- JavaScript (Vanilla)
- GitHub Pages for hosting

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

Feel free to use this template for your own portfolio!

---

Made with ❤️ for showcasing amazing work