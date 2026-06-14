- Intern: Omkar Sharma 
- GitHub: @omkar-editor
- Organization: WeIntern Pvt Ltd
- Program: Web Development Internship – Week 2
# Objective
- Build a fully responsive, multi-page company website that functions seamlessly across all screen sizes. The site should reflect professional design standards and include interactive navigation.
  # Live Link
  -https://omkar-editor.github.io/assignmnetweek2/

# Swift Delivery - Responsive Business Website

## 📁 Project Structure

```
swiftdelivery/
├── index.html              # Main HTML file
├── css/                    # Modular CSS files
│   ├── styles.css         # Main stylesheet (imports all modules,Every component written inside the Index fileaa)
└── README.md              # This file
```
# Screenshots
| View | Screenshots| 
|----------|----------|
| Home-Desktop | <img width="1261" height="601" alt="image" src="https://github.com/user-attachments/assets/b708edd1-be69-4d26-9caf-731afc01cfc7" />| 
| Services-Desktop |<img width="1272" height="547" alt="image" src="https://github.com/user-attachments/assets/283d862a-b3b3-41e0-adb7-b23c61f1b6c8" />|
| Pricing-Desktop |<img width="1272" height="547" alt="image" src="https://github.com/user-attachments/assets/25615a38-a672-4db1-a4a4-eacb3b7cef1a" />|
| Contact-Desktop |<img width="1272" height="547" alt="image" src="https://github.com/user-attachments/assets/734731fe-ac5f-451a-a671-5a623a4384cd" />|
| Home-Mobile    | <img width="540" height="1132" alt="swift delivery" src="https://github.com/user-attachments/assets/c08be533-49cf-46b9-9f31-f58693704065" /> |


## 🎯 Key Features

### ✅ Responsive Design
- **Mobile-first approach** (320px and up)
- **Tablet optimization** (768px breakpoints)
- **Desktop enhancement** (1024px+)
- Flexible grid layouts using CSS Grid and Flexbox
- Responsive typography with `clamp()` function

### ✅ Code Simplification
- **Modular CSS** - Each component in its own file
- **Clear naming conventions** - BEM-inspired class names
- **CSS Variables** - Easy theme customization
- **Semantic HTML** - Better accessibility and SEO
- **Minimal JavaScript** - Only what's necessary for functionality

### ✅ Mobile Navigation
- Hamburger menu button for mobile devices
- Smooth animations for menu toggle
- Auto-closes on link click
- Auto-closes when window resizes above 768px

### ✅ Components
- **Header** - Sticky navigation with logo
- **Hero Section** - Eye-catching introduction
- **Service Cards** - Hover effects and responsive grid
- **About Section** - Company information
- **Contact Section** - Call-to-action area
- **Footer** - Multi-column layout with links and social icons

## 🎨 Customization

### Colors
Edit CSS variables in `css/base.css`:
```css
:root {
  --primary: #1e90ff;        /* Main brand color */
  --secondary: #0b3d91;      /* Darker shade */
  --accent: #f59e0b;         /* Highlight color */
  /* ... more variables */
}
```

### Typography
Update font family in `css/base.css`:
```css
body {
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
}
```

### Spacing
Modify `--spacing` variable or specific padding/margin values in each CSS file.

## 📱 Breakpoints

- **480px** - Small phones
- **768px** - Tablets
- **1024px+** - Desktops
- **1120px** - Max container width

## 🚀 Usage

1. Open `index.html` in your browser
2. All styles are automatically loaded via CSS imports
3. JavaScript handles mobile menu interactions

## 🔧 Development Tips

### Adding New Sections
1. Add semantic HTML in `index.html`
2. Create corresponding CSS file in `css/` folder
3. Import it in `css/styles.css`

### Modifying Styles
- Edit individual CSS files for specific components
- Keep `base.css` for global resets and variables
- Use CSS variables for consistent theming

### Testing Responsiveness
- Use browser DevTools (F12) → Device Toolbar
- Test at 480px, 768px, 1024px viewports
- Test on real devices when possible

## ✨ Best Practices Used

- ✅ Mobile-first design
- ✅ Semantic HTML5 elements
- ✅ CSS custom properties for themes
- ✅ Minimal JavaScript footprint
- ✅ Accessibility considerations (ARIA labels)
- ✅ Progressive enhancement
- ✅ Print-friendly styles
- ✅ Performance optimized

---
#Author
-Omkar Sharma
-Front-End Developer 
