# Resume Full Template - HTML

A professional, modern resume template with advanced customization capabilities and stunning visual effects.

## Features

### 🎨 Original Resume Template (`index.html`)
- Professional, clean design
- Animated scroll effects (AOS)
- Canvas-based visual effects (lens flare, circuit board, hexagons)
- Responsive and print-friendly
- Dark gradient background with white content container
- Skill bars with progress animations

### ⚡ NEW: Advanced Template Builder (`template-builder.html`)

A powerful interactive tool to create fully customized resumes with:

#### Personal Customization
- Full contact information management
- Professional summary editor
- Dynamic section creation and management

#### Visual Customization
- **6-Color Palette Control**: Customize every color aspect
- **Transparency Controls**: Adjust opacity for sheet and background
- **4 Background Types**: Gradient, solid, pattern, or custom image upload

#### 3D Effects (Three.js)
Choose from 6 stunning 3D effects:
- Floating Particles
- Animated Waves
- Rotating Geometry
- Network Connections
- Galaxy Spiral
- Classic 2D Canvas (default)

#### Content Management
- **Dynamic Sections**: Add, remove, reorder any section
- **Skills Manager**: Add technical skills with proficiency bars
- **Live Preview**: See changes in real-time

#### Save & Export
- Save configurations to JSON
- Load previous configurations
- Generate standalone HTML files
- One-click download

## Quick Start

### Using the Original Template
1. Open `index.html` in a web browser
2. Edit the HTML directly with your information
3. Customize colors and styles in the embedded CSS
4. Print or save as PDF

### Using the Template Builder
1. Open `template-builder.html` in a web browser
2. Fill in your personal information in the "Personal Info" tab
3. Customize colors in the "Colors" tab
4. Choose a 3D effect in the "3D Effects" tab
5. Select a background in the "Background" tab
6. Manage sections in the "Sections" tab
7. Add skills in the "Skills" tab
8. Click "Generate & Download HTML" to get your custom resume

## Documentation

### Current Documentation
- This README provides quick start and overview information

### Archived Documentation
Historical project documentation has been archived in `archive/docs/`:
- **[Template Builder Guide](archive/docs/TEMPLATE-BUILDER-GUIDE.md)** - Complete user guide
- **[Code Review Report](archive/docs/CODE-REVIEW-REPORT.md)** - Code quality analysis
- **[Validation Success](archive/docs/VALIDATION-SUCCESS.md)** - Validation results
- **[Test Report](archive/docs/TEST-REPORT.md)** - Testing documentation
- **[Fixes Applied](archive/docs/FIXES-APPLIED.md)** - Bug fixes and improvements

## File Structure

```
Resume-Full-Template-HTML/
├── index.html                    # Original resume template
├── template-builder.html         # Advanced resume builder tool
├── README.md                     # This file
├── KCNSC-logo.jpg               # Sample logo image
└── archive/
    └── docs/                     # Archived documentation
        ├── TEMPLATE-BUILDER-GUIDE.md
        ├── CODE-REVIEW-REPORT.md
        ├── VALIDATION-SUCCESS.md
        ├── TEST-REPORT.md
        └── FIXES-APPLIED.md
```

## Technologies Used

- HTML5
- CSS3 (Grid, Flexbox, Animations)
- JavaScript (ES6+)
- Three.js (3D graphics)
- Canvas API (2D effects)
- AOS (Animate On Scroll) library
- Inter font family

## Browser Support

- ✅ Chrome/Edge (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Opera

**Requirements**: Modern browser with WebGL support for 3D effects

## Customization Examples

### Professional Theme
```json
{
  "colors": {
    "accent": "#2C3E50",
    "secondary": "#3498DB"
  },
  "threeJs": {
    "effect": "none"
  }
}
```

### Creative Theme
```json
{
  "colors": {
    "accent": "#E74C3C",
    "secondary": "#F39C12"
  },
  "threeJs": {
    "effect": "galaxy"
  }
}
```

### Tech Theme
```json
{
  "colors": {
    "accent": "#27AE60",
    "secondary": "#16A085"
  },
  "threeJs": {
    "effect": "network"
  }
}
```

## Printing

Both templates are print-optimized:
1. Open the HTML file in a browser
2. Press `Ctrl+P` (Windows) or `Cmd+P` (Mac)
3. Select "Save as PDF" as the destination
4. Adjust margins if needed
5. Save

## Tips

- **For Text Readability**: Keep sheet opacity above 90%
- **For Subtle Effects**: Use particle count around 1000-2000
- **For Fast Loading**: Choose "None" or simple 3D effects
- **For Impact**: Use high-contrast color schemes

## License

This template is free to use for personal and commercial purposes.

## Contributing

Feel free to fork, modify, and submit pull requests!

## Support

For questions or issues:
- Check the [Template Builder Guide](archive/docs/TEMPLATE-BUILDER-GUIDE.md)
- Review the code comments
- Open an issue in the repository

---

**Make your resume stand out with dynamic effects and professional styling!**
