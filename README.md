# Modern Portfolio Website - Ayush Uttam

A stunning, modern, and fully responsive personal portfolio website featuring smooth animations, interactive elements, and a sleek dark theme with neon accents.

## 🌟 Features

### ✨ Visual Design
- **Dark Theme** with neon cyan, blue, and magenta accents
- **Light/Dark Theme Toggle** with localStorage persistence
- **Custom Interactive Cursor** - Glowing circle that follows mouse and expands on hover
- **Smooth Animations** - Fade-ins, slide-ups, parallax effects
- **Gradient Backgrounds** - Animated floating orbs in hero section
- **Responsive Design** - Fully optimized for all devices

### 🎯 Sections

1. **Hero Section**
   - Animated typing text effect
   - Gradient background with floating orbs
   - Social media links
   - Scroll indicator

2. **About Me**
   - Personal introduction
   - Animated statistics counter
   - Professional photo with glow effect

3. **Projects**
   - Project cards with hover effects
   - Overlay with live demo and GitHub links
   - Technology tags
   - Smooth animations on scroll

4. **Skills**
   - Icon-based skill display
   - Animated progress bars
   - Categorized by Frontend, Backend, and Tools

5. **Contact**
   - Interactive contact form
   - Social media links
   - Smooth form animations

6. **Footer**
   - Quick navigation links
   - Back-to-top button
   - Copyright information

### 🚀 Interactive Features

- **Custom Cursor**: Glowing circle with hover effects
- **Smooth Scrolling**: All anchor links with smooth scroll behavior
- **Scroll Animations**: Elements fade in as you scroll
- **Theme Toggle**: Switch between dark and light themes
- **Mobile Menu**: Hamburger menu for mobile devices
- **Active Nav**: Navigation highlights current section
- **Typing Effect**: Dynamic text typing in hero section
- **Counter Animation**: Statistics count up on scroll
- **Progress Bars**: Skill bars animate on view

## 📁 File Structure

```
PORTFOLIO/
├── index.html          # Main HTML file (single-page)
├── style.css           # All styling and animations
├── script.js           # All JavaScript functionality
├── images/             # Project images and assets
│   ├── amazon-clone.png
│   ├── calculator.png
│   ├── my-image.jpg
│   ├── shikom-aboutus.png
│   ├── spotify.png
│   └── AyushUttam-resume1.pdf
└── README.md           # This file
```

## 🛠️ Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with animations
- **JavaScript (Vanilla)** - No frameworks, pure JS
- **Font Awesome** - Icons
- **Google Fonts (Poppins)** - Typography

## 🎨 Color Palette

### Dark Theme
- Background: `#0a0a0f`, `#12121a`, `#1a1a24`
- Text: `#e4e4e7`, `#a1a1aa`, `#71717a`
- Neon Accents: `#00f0ff` (cyan), `#0099ff` (blue), `#ff00ff` (magenta), `#a855f7` (purple)

### Light Theme
- Background: `#ffffff`, `#f8f9fa`
- Text: `#1a1a24`, `#4b5563`
- Accents: Purple tones with cyan highlights

## 📱 Responsive Breakpoints

- Desktop: 1200px+
- Tablet: 768px - 968px
- Mobile: < 768px
- Small Mobile: < 480px

## 🚀 Getting Started

1. **Clone or Download** this repository
2. **Open `index.html`** in a web browser
3. **That's it!** No build process needed

### For Local Development

Simply open `index.html` in your browser or use a local server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js (http-server)
npx http-server

# Using VS Code Live Server extension
# Right-click index.html > Open with Live Server
```

Then navigate to `http://localhost:8000`

## 🎯 Customization

### Update Personal Information

1. **Name & Title**: Edit in `index.html` hero section
2. **About Me**: Update text in about section
3. **Skills**: Modify skill items in skills section
4. **Projects**: Add/remove project cards in projects section
5. **Contact Info**: Update email and social links

### Change Colors

Edit CSS variables in `style.css`:

```css
:root {
    --neon-cyan: #00f0ff;      /* Change to your preferred color */
    --neon-blue: #0099ff;
    --neon-magenta: #ff00ff;
}
```



## 🔧 Performance Optimizations

- **Debounced scroll events** for better performance
- **Intersection Observer API** for scroll animations
- **CSS animations** instead of JavaScript where possible
- **Optimized images** (compress before use)
- **Lazy loading** ready structure

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 📝 Notes

- All images should be optimized for web use
- Custom cursor may not work on touch devices (tablets/phones)
- Theme preference is saved in localStorage
- Form submission uses mailto: (can be replaced with backend API)

## 🎓 Credits

- **Design**: Custom modern design
- **Icons**: Font Awesome
- **Fonts**: Google Fonts (Poppins)
- **Developer**: Ayush Uttam

## 📄 License

This project is open source and available for personal use.

---

**Built with ❤️ by Ayush Uttam**

For questions or suggestions, feel free to reach out!
