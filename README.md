# Mountains Snowboarding - Premium Snowboards Website

Professional single-page website for selling snowboards and winter equipment. The project is built using modern web technologies and best development practices.

## 🚀 Features

- ✅ **Responsive Design** - fully responsive for all devices
- ✅ **SEO Optimization** - meta tags, Open Graph, structured data
- ✅ **Accessibility (A11y)** - ARIA attributes, keyboard navigation, screen reader support
- ✅ **Performance** - lazy loading images, optimized CSS
- ✅ **Modern Code** - ES6+, SCSS with variables, modular structure
- ✅ **Form Validation** - client-side email validation
- ✅ **Swiper.js** - modern slider for snowboard gallery

## 📁 Project Structure

```
Vladihka-Snouborde/
├── #source/              # Source files
│   └── scss/
│       ├── variables.scss # Variables (colors, fonts, spacing)
│       ├── mixin.scss     # Adaptive mixins
│       ├── null.scss      # CSS reset
│       └── style.scss     # Main styles
├── css/                  # Compiled CSS
│   └── style.css
├── js/                   # JavaScript files
│   └── script.js         # Main JavaScript
├── img/                  # Images
│   ├── features/         # Feature images
│   ├── footer/           # Footer images
│   ├── fullscreen/       # Background images
│   ├── header/           # Logo and icons
│   ├── mountain/         # Mountain section background
│   └── snoubord/         # Snowboard images
├── index.html            # Main page
├── prepros.config        # Prepros configuration
└── README.md             # Documentation
```

## 🛠 Technologies

- **HTML5** - semantic markup
- **SCSS** - CSS preprocessor with variables and mixins
- **JavaScript (ES6+)** - modern JavaScript without frameworks
- **jQuery 3.7.1** - for compatibility and DOM manipulation
- **Swiper.js 11** - modern slider
- **Prepros** - SCSS to CSS compilation

## 📦 Installation and Setup

### Requirements

- Prepros or any other SCSS compiler
- Local web server (optional)

### Installation Steps

1. Clone the repository or download the project
2. Open the project in Prepros or another SCSS compiler
3. Make sure SCSS compiles to `css/style.css`
4. Open `index.html` in a browser

### Prepros Configuration

The project already contains `prepros.config` configuration. Prepros automatically:
- Compiles SCSS from `#source/scss/` to `css/`
- Adds autoprefixes
- Minifies CSS (optional)

## 🎨 Styling

### Variables

All main values are in `variables.scss`:
- Colors (`$color-black`, `$color-white`, etc.)
- Fonts (`$font-family-base`, `$font-family-semibold`)
- Font sizes
- Spacing (`$spacing-*`)
- Breakpoints (`$breakpoint-*`)

### Adaptive Mixins

Mixins are used for adaptive values:
- `adaptive_font()` - adaptive font sizes
- `adaptive_padding_*()` - adaptive padding
- `adaptive_width/height()` - adaptive dimensions

### Breakpoints

- `280px` - very small screens
- `480px` - mobile devices
- `657px` - tablets (small)
- `767px` - tablets
- `865px` - desktop (small)
- `970px` - desktop
- `1230px` - large screens

## 📱 Responsiveness

The project is fully responsive and optimized for:
- Mobile devices (320px+)
- Tablets (768px+)
- Desktops (1024px+)
- Large screens (1920px+)

## ♿ Accessibility

The project follows WCAG 2.1 principles:
- Semantic HTML markup
- ARIA attributes for interactive elements
- Keyboard navigation
- Screen reader support
- Contrast colors
- Skip links for quick navigation

## 🔍 SEO

Included:
- Meta tags (title, description, keywords)
- Open Graph tags for social networks
- Twitter Card tags
- Structured data (JSON-LD)
- Semantic markup
- Alt texts for images

## ⚡ Performance

Optimizations:
- Lazy loading for images
- Optimized CSS (duplicates removed)
- JavaScript minification (via Prepros)
- Preconnect for external resources
- Optimized images

## 🎯 Functionality

### JavaScript Functions

- **Burger Menu** - mobile menu with animation
- **Swiper Slider** - snowboard slider with autoplay
- **Newsletter Form** - form validation and submission
- **Smooth Scroll** - smooth scrolling to anchors
- **Accessibility** - accessibility enhancements
- **Lazy Loading** - deferred image loading

## 📝 Components

### Header
- Logo
- Navigation menu
- Search
- Shopping cart
- Burger menu (mobile version)

### Hero Section
- Fullscreen banner
- Call to action

### Snowboards Section
- Snowboard slider (Swiper.js)
- Responsive grid

### Mountain Section
- Company information
- Background image

### Features Section
- 4 image cards
- Responsive grid

### Footer
- Navigation links
- Newsletter subscription form
- Social networks
- Region selection

## 🐛 Known Issues

No known critical issues.

## 🔮 Future Improvements

- [ ] Add real backend integration for forms
- [ ] Implement search functionality
- [ ] Add shopping cart
- [ ] Add more animations
- [ ] Optimize images (WebP format)
- [ ] Add PWA functionality
- [ ] Add tests

## 📄 License

© 2024 Mountains Snowboards. All rights reserved.

## 👨‍💻 Development

The project is developed using best practices:
- Clean and readable code
- Code comments
- Modular structure
- Standards compliance

## 📞 Contact

For questions and suggestions, please contact us through the form on the website.

---

**Version:** 2.0  
**Last Update:** 2024
