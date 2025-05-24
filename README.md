# Personal Portfolio

A modern, responsive personal portfolio website built with HTML, CSS, and JavaScript. This portfolio is designed to be hosted on GitHub Pages and features a clean black and white design with subtle color accents.

## Features

- Responsive design that works on all devices
- Smooth scrolling navigation
- Mobile-friendly navigation menu
- Contact form
- Projects showcase
- Certifications section
- Skills display
- Social media links

## Getting Started

1. Clone this repository:
```bash
git clone https://github.com/yourusername/portfolio.git
```

2. Navigate to the project directory:
```bash
cd portfolio
```

3. Customize the content:
   - Update the personal information in `index.html`
   - Modify the styling in `styles.css` if desired
   - Add your own projects and certifications
   - Update social media links

## Deploying to GitHub Pages

1. Create a new repository on GitHub

2. Push your code to the repository:
```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/yourusername/portfolio.git
git push -u origin main
```

3. Go to your repository settings on GitHub

4. Scroll down to the "GitHub Pages" section

5. Under "Source", select the "main" branch

6. Click "Save"

Your portfolio will be available at `https://yourusername.github.io/portfolio`

## Customization

### Colors
The color scheme can be modified by changing the CSS variables in the `:root` selector in `styles.css`:

```css
:root {
    --primary-color: #000000;
    --secondary-color: #ffffff;
    --accent-color: #4a90e2;
    --text-color: #333333;
    --background-color: #ffffff;
}
```

### Content
Update the content in `index.html` to include your personal information, projects, and certifications.

### Contact Form
The contact form currently only shows a success message. To make it functional, you'll need to:
1. Set up a backend service to handle form submissions
2. Update the form submission code in `script.js`

## Contributing

Feel free to fork this repository and customize it for your own use.

## License

This project is open source and available under the [MIT License](LICENSE). 