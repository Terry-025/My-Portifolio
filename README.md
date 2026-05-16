# Portfolio Website

A modern, responsive portfolio website starter template to showcase your projects and skills.

## 📁 Project Structure

```
My-Portifolio/
├── index.html          # Main HTML file
├── css/
│   └── styles.css      # Styling
├── js/
│   └── script.js       # JavaScript functionality
├── assets/
│   └── images/         # Project images folder
└── README.md           # This file
```

## 🚀 Getting Started

### 1. **Clone the Repository**
```bash
git clone https://github.com/Terry-025/My-Portifolio.git
cd My-Portifolio
```

### 2. **Customize Your Content**

Edit `index.html` and update:
- Your name and title
- About me section
- Project descriptions and links
- Skills and technologies
- Contact information (email, social links)
- Your name in the footer

### 3. **Add Your Project Images**

Create the images folder structure:
```bash
mkdir -p assets/images
```

Add your project screenshots:
- `assets/images/project1.jpg`
- `assets/images/project2.jpg`
- `assets/images/project3.jpg`

### 4. **Test Locally**

Open `index.html` in your browser or use a local server:
```bash
# Using Python
python -m http.server 8000

# Using Node.js (with http-server)
npx http-server
```

Then visit `http://localhost:8000`

## 📝 Features

✅ **Responsive Design** - Mobile, tablet, and desktop friendly
✅ **Smooth Scrolling** - Smooth navigation between sections
✅ **Contact Form** - Built-in form validation
✅ **Modern UI** - Clean and professional design
✅ **Animations** - Scroll and hover animations
✅ **Easy to Customize** - Simple HTML/CSS structure
✅ **No Dependencies** - Pure HTML, CSS, and JavaScript

## 🌐 Deployment Options

### **Option 1: GitHub Pages (Recommended)**

1. Go to your repository settings
2. Scroll to "GitHub Pages" section
3. Select `main` branch as source
4. Your site will be live at: `https://terry-025.github.io/My-Portifolio`

### **Option 2: Vercel**

1. Go to [vercel.com](https://vercel.com)
2. Sign in with GitHub
3. Import your repository
4. Click "Deploy"
5. Your site will be live with a custom domain

### **Option 3: Netlify**

1. Go to [netlify.com](https://netlify.com)
2. Sign in with GitHub
3. Click "New site from Git"
4. Select your repository
5. Deploy

### **Option 4: Custom Domain (GitHub Pages)**

After deploying to GitHub Pages:
1. Go to repository Settings
2. Find "Custom domain" in GitHub Pages section
3. Enter your custom domain
4. Update DNS records with your domain provider

## 🎨 Customization Guide

### Colors
Edit the CSS variables in `css/styles.css`:
```css
:root {
    --primary-color: #3498db;      /* Main blue */
    --secondary-color: #2c3e50;    /* Dark blue-gray */
    --accent-color: #e74c3c;       /* Red accent */
}
```

### Fonts
Change the font in `css/styles.css`:
```css
body {
    font-family: 'Your Font', sans-serif;
}
```

### Adding More Projects
Duplicate a `.project-card` div in `index.html` and update the content.

## 📧 Contact Form Integration

Currently, the form shows a success message but doesn't send emails. To enable email:

### Using Formspree (Free)
1. Go to [formspree.io](https://formspree.io)
2. Create an account
3. Get your form endpoint
4. Update the form in `index.html`:
```html
<form action="https://formspree.io/f/YOUR_ID" method="POST">
    <!-- form fields -->
</form>
```

### Using EmailJS (Free)
1. Sign up at [emailjs.com](https://emailjs.com)
2. Set up your email service
3. Update `js/script.js` with your EmailJS credentials

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 📄 License

Free to use and modify for personal projects.

## 💡 Tips

1. **Add your GitHub projects** - Link to your actual GitHub repositories
2. **Use high-quality images** - Professional project screenshots matter
3. **Keep content updated** - Regularly add new projects
4. **Optimize images** - Compress images for faster loading
5. **SEO** - Update meta tags in `index.html` for better search results
6. **Analytics** - Add Google Analytics for traffic tracking

## 🤝 Contributing

Feel free to fork this template and make it your own!

## ❓ Need Help?

Check out the inline comments in the code or reach out via the contact form on your portfolio.

---

**Happy coding! 🎉**
