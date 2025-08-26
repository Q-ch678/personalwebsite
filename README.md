# Personal Website - MVP

A clean, responsive personal website built with HTML, CSS, and JavaScript. This MVP version showcases your professional profile, featured projects, and provides a contact form.

## 🚀 Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Professional Styling**: Clean, modern design with hover effects and smooth animations
- **Contact Form**: Functional form with client-side validation
- **Smooth Scrolling**: Seamless navigation between sections
- **Mobile Menu**: Hamburger menu for mobile navigation
- **SEO Ready**: Semantic HTML structure with proper meta tags

## 📁 File Structure

```
personalwebsite/
├── index.html          # Main HTML file
├── styles.css          # All CSS styles
├── script.js           # JavaScript functionality
├── images/             # Image assets
│   ├── profile.jpg     # Your profile photo (add this)
│   └── project-screenshots/
│       ├── project1.jpg  # Project screenshots (add these)
│       ├── project2.jpg
│       ├── project3.jpg
│       └── project4.jpg
├── scope.md            # Full project scope
├── mvp.md              # MVP specifications
├── design.md           # ASCII design mockups
└── README.md           # This file
```

## 🎨 Design

- **Color Scheme**: Professional blue theme with clean whites and grays
- **Typography**: Inter font family with proper hierarchy
- **Layout**: Mobile-first responsive design
- **Animations**: Subtle hover effects and smooth transitions

## 🛠️ Setup Instructions

### 1. Add Your Content

**Update `index.html` with your information:**
- Replace "Your Name" with your actual name
- Update the professional title/subtitle
- Modify the bio and about text
- Update social media links (GitHub, LinkedIn)
- Replace project information with your actual projects
- Update contact information (email, location)

**Key sections to customize:**
```html
<!-- Hero Section -->
<h1 class="hero-title">Hi, I'm [Your Name]</h1>
<p class="hero-subtitle">[Your Professional Title]</p>

<!-- About Section -->
<p class="about-text">[Your professional summary]</p>

<!-- Skills -->
<span class="skill-tag">[Your Skills]</span>

<!-- Projects -->
<!-- Update each project card with your project details -->

<!-- Contact -->
<a href="mailto:your.email@example.com">your.email@example.com</a>
```

### 2. Add Your Images

Add the following images to the `images/` folder:
- `profile.jpg` - Your professional headshot (400x400px recommended)
- `project-screenshots/project1.jpg` - Screenshot of your first project
- `project-screenshots/project2.jpg` - Screenshot of your second project
- `project-screenshots/project3.jpg` - Screenshot of your third project
- `project-screenshots/project4.jpg` - Screenshot of your fourth project

**Image Guidelines:**
- Profile photo: 400x400px (square), under 200KB
- Project screenshots: 600x400px (3:2 ratio), under 500KB each
- Use JPG for photos, PNG for screenshots with transparency

### 3. Launch Your Website

**Local Development:**
1. Open `index.html` in your web browser
2. Test all sections and functionality
3. Verify mobile responsiveness

**Deploy to Web:**
- **GitHub Pages**: Push to GitHub repo, enable Pages in settings
- **Netlify**: Drag and drop folder to Netlify
- **Vercel**: Connect GitHub repo or upload folder
- **Traditional Hosting**: Upload files via FTP

## 🎯 Customization Options

### Colors
Update CSS variables in `styles.css`:
```css
:root {
    --primary-color: #2563eb;    /* Main brand color */
    --secondary-color: #1f2937;  /* Dark text color */
    --accent-color: #10b981;     /* Accent/highlight color */
}
```

### Fonts
Change font family in CSS:
```css
:root {
    --font-family: 'Your Font', sans-serif;
}
```

### Content
- Add more projects by copying the project card structure
- Modify the skills list in the about section
- Update social media links throughout the site

## 🔧 Technical Details

### Browser Support
- Chrome (latest 2 versions)
- Firefox (latest 2 versions)  
- Safari (latest 2 versions)
- Edge (latest 2 versions)
- Mobile browsers

### Performance
- Optimized CSS with efficient selectors
- Minimal JavaScript for fast loading
- Image lazy loading ready
- Mobile-first responsive design

### Accessibility
- Semantic HTML structure
- Proper heading hierarchy
- Alt text for images (add descriptions)
- Keyboard navigation support
- Focus indicators

## 📱 Mobile Features

- Responsive hamburger menu
- Touch-friendly buttons and links
- Optimized typography for mobile screens
- Smooth scrolling on mobile devices

## 🚀 Future Enhancements

After MVP is live, consider adding:
- Backend contact form processing
- Blog section
- More project filtering options
- Dark mode toggle
- Analytics integration
- SEO optimization
- Progressive Web App features

## 🐛 Troubleshooting

**Images not showing:**
- Check file paths in `index.html`
- Ensure images are in the correct folders
- Verify image file names match HTML references

**Form not working:**
- Form shows success message (no backend needed for MVP)
- Check browser console for JavaScript errors
- Ensure form validation is working properly

**Mobile menu not working:**
- Check that `script.js` is loaded properly
- Verify JavaScript console for errors

## 📞 Support

If you encounter issues:
1. Check browser developer console for errors
2. Validate HTML and CSS syntax
3. Test in different browsers
4. Ensure all file paths are correct

## 📄 License

This project is open source. Feel free to use it as a template for your own personal website.

---

**Ready to launch?** 🎉
1. ✅ Customize content
2. ✅ Add your images  
3. ✅ Test locally
4. ✅ Deploy to web
5. ✅ Share with the world!
