# Resume Full Template - HTML

https://ee-edk.github.io/Resume-Full-Template-HTML/

A professional, modern resume template builder with advanced customization capabilities and stunning visual effects. Create beautiful, interactive resumes with 3D backgrounds, custom color schemes, and dynamic content management.

## Features

### Advanced Template Builder (`index.html`)

A powerful interactive tool to create fully customized resumes with:

#### Personal Customization
- Full contact information management
- Professional summary editor
- Dynamic section creation and management

#### Visual Customization
- **6-Color Palette Control**: Customize every color aspect
  - Primary and secondary accent colors
  - Background gradient colors
  - Text and heading colors
- **Transparency Controls**: Adjust opacity for sheet and background
- **4 Background Types**: Gradient, solid, pattern, or custom image upload

#### 3D Effects (Three.js)
Choose from 6 stunning 3D effects:
1. **None** - Classic canvas 2D effects only (default)
2. **Floating Particles** - Animated particle cloud rotating in 3D space
3. **Animated Waves** - Undulating wave plane with dynamic surface
4. **Rotating Geometry** - Spinning icosahedron wireframe
5. **Network Connections** - Connected nodes simulating a network
6. **Galaxy Spiral** - Spinning galaxy with spiral arms

**Effect Settings**:
- Animation Speed: Control how fast the effect animates (0-100%)
- Particle Count: Number of particles/elements (100-5000)
- Effect Color: Color of the 3D effect elements

#### Content Management
- **Dynamic Sections**: Add, remove, reorder any section
- **Skills Manager**: Add technical skills with proficiency bars
- **Live Preview**: See changes in real-time

#### Save & Export
- Save configurations to JSON
- Load previous configurations
- Generate standalone HTML files
- One-click download

---

## Quick Start

1. Open `template-builder.html` in a web browser
2. Fill in your personal information in the "Personal Info" tab
3. Customize colors in the "Colors" tab
4. Choose a 3D effect in the "3D Effects" tab
5. Select a background in the "Background" tab
6. Manage sections in the "Sections" tab
7. Add skills in the "Skills" tab
8. Click "Generate & Download HTML" to get your custom resume

---

## Complete User Guide

### Getting Started

Open `template-builder.html` in your web browser. You'll see a split-screen interface:
- **Left Panel**: Configuration controls with tabbed sections
- **Right Panel**: Live preview of your resume

### Tab 1: Personal Information

Configure your basic contact and professional information:

- **Full Name**: Your complete name as it will appear on the resume
- **Professional Title**: Your job title or professional designation
- **Email**: Contact email address
- **Phone**: Phone number
- **Location**: City and state/country
- **LinkedIn URL**: Your LinkedIn profile link
- **Portfolio/Website**: Personal website or portfolio URL
- **Professional Summary**: A brief overview of your experience and skills

### Tab 2: Colors

Customize the entire color scheme of your resume:

- **Primary Accent**: Main accent color (default: red #c41e3a)
- **Secondary Accent**: Secondary color for gradients
- **Background Start**: Starting color for background gradient
- **Background End**: Ending color for background gradient
- **Text Color**: Main body text color
- **Heading Color**: Color for section headings

**Transparency Controls**:
- **Resume Sheet Opacity**: Control the opacity of the main resume container (0-100%)
- **Background Opacity**: Control the opacity of the page background (0-100%)

### Tab 3: 3D Effects

Add stunning Three.js-powered visual effects to your resume background.

**Effect Settings**:
- **Animation Speed**: Control how fast the effect animates (0-100%)
- **Particle Count**: Number of particles/elements (100-5000)
- **Effect Color**: Color of the 3D effect elements

### Tab 4: Background

Choose and customize your resume's background:

**Background Types**:
- **Gradient** - Smooth color gradient (uses Background Start/End colors)
- **Solid Color** - Single solid color
- **Pattern** - Repeating diagonal stripe pattern
- **Image** - Upload your own background image

**Image Background Options**:
- Upload any image file (JPG, PNG, etc.)
- **Image Overlay Opacity**: Control the darkness overlay (0-100%)

### Tab 5: Sections

Dynamically manage the content sections of your resume:

**Section Controls**:
- **Add New Section**: Click "+ Add New Section" to create a new content block
- **Reorder**: Use ↑ and ↓ arrows to move sections up or down
- **Edit**: Click the pencil (✎) icon to expand/collapse section editing
- **Delete**: Click the × icon to remove a section

**Section Fields**:
- **Section Title**: The heading for this section
- **Content**: The text content for this section

### Tab 6: Skills

Add and manage technical skills with visual proficiency bars:

**Skill Entry**:
- **Skill Name**: Name of the technology/skill
- **Level**: Proficiency level from 0-100
- Skills are displayed with animated progress bars

**Controls**:
- **+ Add Skill**: Add a new skill entry
- **×**: Remove a skill

### Saving and Loading

**Save Configuration**:
Click **💾 Save Configuration** to:
1. Save to browser's localStorage (auto-loads on next visit)
2. Download a `resume-config.json` file

**Load Configuration**:
Click **📂 Load Configuration** to:
- Upload a previously saved `resume-config.json` file
- Restore all your settings instantly

### Generate Resume

Click **⚡ Generate & Download HTML** to:
1. Generate a complete, standalone HTML file
2. Include all your customizations
3. Embed selected Three.js effects
4. Download as `[Your-Name]-Resume.html`

The generated file:
- ✅ Works offline (no external dependencies except Three.js CDN if 3D effects are used)
- ✅ Is print-friendly (use browser's print function)
- ✅ Is fully responsive
- ✅ Contains all your custom styling
- ✅ Can be hosted on any web server or GitHub Pages

---

## Tips and Best Practices

### Color Schemes

**Professional**:
- Primary: `#2C3E50`, Secondary: `#3498DB`
- Clean and corporate look

**Creative**:
- Primary: `#E74C3C`, Secondary: `#F39C12`
- Bold and eye-catching

**Tech**:
- Primary: `#27AE60`, Secondary: `#16A085`
- Modern tech industry aesthetic

### Three.js Effects

- **For Professional Roles**: Use "None" or subtle "Floating Particles"
- **For Creative Roles**: Try "Galaxy Spiral" or "Network Connections"
- **For Tech Roles**: "Rotating Geometry" or "Animated Waves"

Keep animation speed moderate (30-60%) for best visual effect without distraction.

### Transparency

- **High Opacity (90-100%)**: Best for readability
- **Medium Opacity (70-90%)**: Creates elegant layered effect
- **Low Opacity (<70%)**: Only with subtle backgrounds

### Background Images

- Use high-resolution images (1920x1080 or higher)
- Increase overlay opacity (70-90%) to ensure text readability
- Professional photos, abstract patterns, or subtle textures work best

### General Tips

- **For Text Readability**: Keep sheet opacity above 90%
- **For Subtle Effects**: Use particle count around 1000-2000
- **For Fast Loading**: Choose "None" or simple 3D effects
- **For Impact**: Use high-contrast color schemes

---

## File Structure

```
Resume-Full-Template-HTML/
├── template-builder.html      # Resume builder tool
├── README.md                  # This file
└── archive/                   # Archived development documentation
    └── DEVELOPMENT-HISTORY.md
```

---

## Technologies Used

- HTML5
- CSS3 (Grid, Flexbox, Animations)
- JavaScript (ES6+)
- Three.js (3D graphics)
- Canvas API (2D effects)
- AOS (Animate On Scroll) library
- Inter font family

---

## Browser Support

- ✅ Chrome/Edge (v90+) - recommended
- ✅ Firefox (v88+)
- ✅ Safari (v14+)
- ✅ Opera (v76+)

**Requirements**: Modern browser with WebGL support for 3D effects

---

## Printing

The generated resume HTML files are print-optimized:

1. Open the generated HTML file in a browser
2. Press `Ctrl+P` (Windows) or `Cmd+P` (Mac)
3. Select "Save as PDF" as the destination
4. Adjust margins if needed
5. Save

3D effects and background images are automatically hidden in print view for a clean, professional look.

---

## Troubleshooting

**Preview not updating?**
- Click out of the input field to trigger update
- Try switching tabs and back

**Can't see 3D effects?**
- Ensure WebGL is enabled in browser
- Check that you selected an effect other than "None"
- Try reducing particle count if performance is slow

**Downloaded HTML looks different?**
- Clear browser cache
- Ensure all fields are filled before generating
- Re-download with "Generate & Download" button

---

## Advanced Customization

The generated HTML file can be further customized by:
1. Opening it in a text editor
2. Modifying the embedded CSS styles
3. Adding custom JavaScript
4. Changing the HTML structure

All styles are embedded in the `<style>` tag for easy editing.

---

## Security

This template has been security-hardened with:
- ✅ XSS protection (HTML escaping)
- ✅ URL validation
- ✅ File upload validation
- ✅ Content Security Policy
- ✅ Safe external link handling

---

## License

This template is free to use for personal and commercial purposes.

---

## Contributing

Feel free to fork, modify, and submit pull requests!

---

## Support

For questions or issues:
- Review this documentation
- Check the code comments
- Open an issue in the repository

---

**Make your resume stand out with dynamic effects and professional styling!**
