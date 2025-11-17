# Advanced Resume Template Builder - User Guide

## Overview

The Advanced Resume Template Builder is a powerful, interactive tool that allows you to create fully customized HTML resumes with stunning visual effects, personalized color schemes, and dynamic content management.

## Getting Started

1. Open `template-builder.html` in your web browser
2. You'll see a split-screen interface:
   - **Left Panel**: Configuration controls
   - **Right Panel**: Live preview of your resume

## Features

### 1. Personal Information Tab

Configure your basic contact and professional information:

- **Full Name**: Your complete name as it will appear on the resume
- **Professional Title**: Your job title or professional designation
- **Email**: Contact email address
- **Phone**: Phone number
- **Location**: City and state/country
- **LinkedIn URL**: Your LinkedIn profile link
- **Portfolio/Website**: Personal website or portfolio URL
- **Professional Summary**: A brief overview of your experience and skills

### 2. Colors Tab

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

### 3. 3D Effects Tab

Add stunning Three.js-powered visual effects to your resume background:

**Available Effects**:

1. **None** - Classic canvas 2D effects only (default)
2. **Floating Particles** - Animated particle cloud rotating in 3D space
3. **Animated Waves** - Undulating wave plane with dynamic surface
4. **Rotating Geometry** - Spinning icosahedron wireframe
5. **Network Connections** - Connected nodes simulating a network
6. **Galaxy Spiral** - Spinning galaxy with spiral arms

**Effect Settings**:
- **Animation Speed**: Control how fast the effect animates (0-100%)
- **Particle Count**: Number of particles/elements (100-5000)
- **Effect Color**: Color of the 3D effect elements

### 4. Background Tab

Choose and customize your resume's background:

**Background Types**:

- **Gradient** - Smooth color gradient (uses Background Start/End colors)
- **Solid Color** - Single solid color
- **Pattern** - Repeating diagonal stripe pattern
- **Image** - Upload your own background image

**Image Background Options**:
- Upload any image file (JPG, PNG, etc.)
- **Image Overlay Opacity**: Control the darkness overlay (0-100%)

### 5. Sections Tab

Dynamically manage the content sections of your resume:

**Section Controls**:
- **Add New Section**: Click "+ Add New Section" to create a new content block
- **Reorder**: Use ↑ and ↓ arrows to move sections up or down
- **Edit**: Click the pencil (✎) icon to expand/collapse section editing
- **Delete**: Click the × icon to remove a section

**Section Fields**:
- **Section Title**: The heading for this section
- **Content**: The text content for this section

**Default Sections**:
- Professional Summary
- Experience
- Education
- Skills

### 6. Skills Tab

Add and manage technical skills with visual proficiency bars:

**Skill Entry**:
- **Skill Name**: Name of the technology/skill
- **Level**: Proficiency level from 0-100
- Skills are displayed with animated progress bars

**Controls**:
- **+ Add Skill**: Add a new skill entry
- **×**: Remove a skill

## Saving and Loading

### Save Configuration

Click **💾 Save Configuration** to:
1. Save to browser's localStorage (auto-loads on next visit)
2. Download a `resume-config.json` file

### Load Configuration

Click **📂 Load Configuration** to:
- Upload a previously saved `resume-config.json` file
- Restore all your settings instantly

## Generate Resume

Click **⚡ Generate & Download HTML** to:
1. Generate a complete, standalone HTML file
2. Include all your customizations
3. Embed selected Three.js effects
4. Download as `[Your-Name]-Resume.html`

The generated file:
- ✅ Works offline (no external dependencies)
- ✅ Is print-friendly (use browser's print function)
- ✅ Is fully responsive
- ✅ Contains all your custom styling
- ✅ Can be hosted on any web server or GitHub Pages

## Tips and Best Practices

### Color Schemes

**Professional**:
- Primary: #2C3E50, Secondary: #3498DB
- Clean and corporate look

**Creative**:
- Primary: #E74C3C, Secondary: #F39C12
- Bold and eye-catching

**Tech**:
- Primary: #27AE60, Secondary: #16A085
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

## Browser Compatibility

The template builder works on:
- ✅ Chrome/Edge (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Opera

**Note**: Three.js effects require WebGL support (available in all modern browsers)

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

## Advanced Customization

The generated HTML file can be further customized by:
1. Opening it in a text editor
2. Modifying the embedded CSS styles
3. Adding custom JavaScript
4. Changing the HTML structure

All styles are embedded in the `<style>` tag for easy editing.

## Export Formats

Currently supports:
- **HTML**: Standalone web page (primary format)
- **JSON**: Configuration backup

**Printing to PDF**:
1. Open generated HTML in browser
2. Press Ctrl+P (Cmd+P on Mac)
3. Select "Save as PDF"
4. Print-optimized styles will automatically apply

## Keyboard Shortcuts

- **Tab**: Navigate between fields
- **Enter**: Submit current field
- **Ctrl+S** / **Cmd+S**: Quick save configuration (in some browsers)

## Support

For issues or feature requests, please visit the project repository or contact support.

---

**Version**: 1.0.0
**Last Updated**: 2025
**Created with**: HTML5, CSS3, JavaScript, Three.js

Enjoy creating beautiful, personalized resumes!
