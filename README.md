# AI Story Factory - Landing Page

A modern and responsive landing page for an ebook about creating children's stories using Artificial Intelligence.

## 📋 About the Project

This landing page was developed to promote the ebook "AI Story Factory", which teaches parents to create educational stories for children using AI tools. The page presents the product benefits, customer testimonials, and a clear call-to-action.

## 🚀 Technologies Used

- **HTML5**: Semantic and accessible structure
- **CSS3**: Modern styles with animations and responsiveness
- **JavaScript**: Interactivity and dynamic features
- **Tailwind CSS**: CSS framework via CDN for quick styling
- **Google Fonts**: Inter typography for a professional appearance

## 📁 Project Structure

```
landingpage/
├── .github/
│   └── copilot-instructions.md    # GitHub Copilot instructions
├── css/
│   └── main.css                   # Custom styles
├── js/
│   └── main.js                    # JavaScript functionalities
├── index.html                     # Main page
└── README.md                      # This file
```

## 🎨 Features

### Design
- **Responsive**: Adapted for desktop, tablet, and mobile
- **Modern**: Clean design with gradients and smooth animations
- **Accessible**: Semantic structure and keyboard navigation
- **Performance**: Optimized loading with fonts and external resources

### Functionalities
- **Animations**: Fade-in and hover effects on elements
- **Smooth navigation**: Smooth scrolling between sections
- **Interactivity**: Buttons with visual effects
- **Configurability**: Configuration system for customization

### Sections
1. **Hero**: Main presentation with CTA
2. **Benefits**: Three main product advantages
3. **Content**: What will be learned in the ebook
4. **Testimonials**: Satisfied customer feedback
5. **Final CTA**: Secondary call to action
6. **Footer**: Copyright information

## 🛠️ How to Run

### Option 1: Open directly in browser
1. Navigate to the project folder
2. Double-click on the `index.html` file
3. The page will open in your default browser

### Option 2: Local server (recommended)
1. Open the terminal in the project folder
2. Run one of the commands below:

**With Python:**
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

**With Node.js:**
```bash
# Install http-server globally
npm install -g http-server

# Run the server
http-server
```

**With Live Server (VS Code):**
1. Install the "Live Server" extension in VS Code
2. Right-click on `index.html`
3. Select "Open with Live Server"

3. Access `http://localhost:8000` in the browser

## 🔧 Customization

### Colors
The main colors can be changed in the `css/main.css` file:

```css
:root {
  --primary-color: #40E0D0;      /* Primary color (turquoise) */
  --secondary-color: #FFC72C;     /* Secondary color (yellow) */
  --surface-color: #98FF98;       /* Surface color (light green) */
  --text-color: #333333;          /* Text color */
  --background-color: #FFFFFF;    /* Background color */
}
```

### Content
Texts can be changed by editing the corresponding elements in `index.html` or through the configuration system in `js/main.js`.

### Typography
To change the font, modify the import in `index.html` and update the `font-family` property in CSS.

## 📱 Responsiveness

The landing page is fully responsive with breakpoints for:
- **Mobile**: < 768px
- **Tablet**: 768px - 1024px
- **Desktop**: > 1024px

## ♿ Accessibility

- Semantic HTML5 structure
- Adequate color contrast
- Keyboard navigation
- Alternative text for icons
- Readable font sizes

## 🚀 Performance

### Implemented optimizations:
- Asynchronous font loading
- Minified CSS via CDN (Tailwind)
- Optimized images (SVG placeholders)
- Modular and efficient JavaScript

### Expected metrics:
- **First Contentful Paint**: < 1.5s
- **Largest Contentful Paint**: < 2.5s
- **Cumulative Layout Shift**: < 0.1

## 🔄 Versioning

For future updates:
1. Keep the folder structure organized
2. Document significant changes
3. Test on different devices and browsers
4. Validate HTML and CSS before deployment

## 📞 Support

For questions or suggestions about the code:
1. Check the documentation in code comments
2. Consult the structure in the `copilot-instructions.md` file
3. Test functionalities in different browsers

## 📄 License

This project is an educational example. Adapt as needed for your specific use.

---

**Developed with ❤️ for the AI Story Factory project**