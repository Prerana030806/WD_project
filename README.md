# LearnoHub - Modern Learning Website

A clean, modern, and fully responsive learning platform website built with pure HTML, CSS, and minimal JavaScript.

## Features

✅ **Fully Responsive Design**

- Mobile-first approach
- Works perfectly on desktop, tablet, and mobile devices
- Optimized for all screen sizes

✅ **Modern UI/UX**

- Clean and professional design
- Smooth animations and transitions
- Intuitive navigation
- Beautiful color scheme (Indigo + Amber)

✅ **All Required Sections**

- **Header/Navbar**: Sticky navigation with mobile menu toggle
- **Hero Section**: Eye-catching heading with CTA button
- **Courses Section**: 4 featured courses with cards
- **Learning Paths Section**: 2 structured learning paths (Frontend & Python)
- **Features Section**: 3 key benefits
- **FAQ Section**: Expandable accordion with 3 questions
- **Footer**: Clean footer with copyright info

✅ **Interactive Features**

- Mobile menu toggle (hamburger menu)
- FAQ accordion expansion/collapse
- Smooth scrolling navigation
- Button hover effects
- Welcome alert on CTA button click

✅ **Beginner-Friendly Code**

- Well-commented HTML
- Organized CSS with variables and sections
- Simple, readable JavaScript
- No frameworks or complex libraries

## File Structure

```
wd_project/
├── index.html          (Main HTML file - all content)
├── styles.css          (Complete styling)
├── script.js           (JavaScript interactivity)
└── README.md          (This file)
```

## Key Features Explained

### 1. Responsive Navigation

- Sticky navbar stays on top while scrolling
- Mobile hamburger menu that toggles on small screens
- Links smoothly scroll to sections

### 2. Hero Section

- Beautiful gradient background
- Large, impactful heading
- CTA button with hover effects and click alert

### 3. Course Cards

- 4 courses: HTML, CSS, JavaScript, Python
- Card hover animations (lift effect)
- Course level badges and duration

### 4. Learning Paths

- 2 learning paths with skills lists
- Clean design with left border accent
- Checkmark icons for skills

### 5. Features Section

- 3 key benefits with icons
- Hover animations
- Descriptive text

### 6. FAQ Accordion

- Click to expand/collapse
- Smooth transitions
- Plus icon rotates on open

### 7. Mobile Responsive

- Hamburger menu on mobile
- Single column layout on small screens
- Optimized typography and spacing

## Color Scheme

- **Primary**: Indigo (#6366f1)
- **Secondary**: Amber (#f59e0b)
- **Background Light**: #f8fafc
- **Text Dark**: #1e293b
- **Text Gray**: #64748b

## Typography

- **Font Family**: Segoe UI, System UI (no external fonts needed!)
- **Font Sizes**: Responsive and scalable
- **Font Weights**: 500, 600, 700, 800

## Customization Guide

### Change Colors

Edit the CSS variables in `styles.css`:

```css
:root {
  --primary-color: #6366f1; /* Change to your color */
  --secondary-color: #f59e0b; /* Change to your color */
}
```

### Change Course Names

Edit the course cards in `index.html`:

```html
<h3 class="course-title">Your Course Name</h3>
```

### Add/Remove Sections

Simply add or remove section elements in `index.html` - the CSS is already set up!

### Modify JavaScript

Edit `script.js` to add more interactivity or change button messages.

## Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Performance

- No external dependencies
- Lightweight CSS (~2000 lines)
- Simple, efficient JavaScript (~100 lines)
- Fast loading time
- Clean code structure

## Accessibility

- Semantic HTML structure
- Proper heading hierarchy
- Readable contrast ratios
- Smooth scroll behavior
- Keyboard navigation support

## How to Use

1. **Open in Browser**
   - Simply open `index.html` in any web browser
   - Or drag the file to your browser window

2. **Customize**
   - Edit HTML for content changes
   - Edit styles.css for design changes
   - Edit script.js for interactivity changes

3. **Deploy**
   - Upload all 3 files to your web server
   - No build process needed!
   - Works with any hosting service

## JavaScript Features Explained

### Mobile Menu Toggle

```javascript
// Toggles the navigation menu visibility on mobile
menuToggle.addEventListener("click", function () {
  navMenu.classList.toggle("open");
});
```

### FAQ Accordion

```javascript
// Expands/collapses FAQ items
function toggleFAQ(button) {
  const faqItem = button.closest(".faq-item");
  faqItem.classList.toggle("open");
}
```

### CTA Button Alert

```javascript
// Shows welcome message when "Start Learning" is clicked
ctaButton.addEventListener("click", function () {
  alert("Welcome to LearnoHub! 🎉");
});
```

## Tips for Beginners

1. **Understanding the Structure**
   - HTML provides content and structure
   - CSS provides styling and layout
   - JavaScript provides interactivity

2. **CSS Variables**
   - Variables make it easy to change colors globally
   - Just update the `:root` section

3. **Responsive Design**
   - The `@media` queries handle small screens
   - Mobile-first approach makes it responsive

4. **JavaScript Comments**
   - All JavaScript is well-commented
   - Easy to understand and modify

## Future Enhancements

You can add:

- Enrollment buttons (link to form)
- Search functionality
- Course filtering
- User testimonials
- Newsletter signup
- Blog section
- Contact form
- Social media links

## License

Free to use and modify for personal and commercial projects.

## Created By

LearnoHub Learning Platform
Built with ❤️ for learners everywhere

---

**Happy Learning! 🎓**
