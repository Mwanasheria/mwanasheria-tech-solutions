MWANASHERIA TECH SOLUTIONS Website

![MWANASHERIA TECH SOLUTIONS Preview](https://images.unsplash.com/photo-1523268755253-2b7d2b2b5f9e?q=80&w=800&auto=format&fit=crop&ixlib=rb-4.0.3&s=abcd)

Professional website for MWANASHERIA TECH SOLUTIONS - A Tanzania-based tech company specializing in custom software development, web design, and mobile applications.

 Features

- 🚀 **Modern Design**: Clean, responsive layout with gradient backgrounds
- 📱 **Mobile-First**: Fully responsive across all device sizes
- 📧 **Contact Form**: Functional contact form with validation
- 🖼️ **Portfolio Showcase**: Display your projects with images and descriptions
- ⚡ **Fast Performance**: Optimized static site with minimal dependencies

 Technologies Used

- HTML5
- CSS3 (with CSS Variables)
- JavaScript (minimal for contact form)
- Google Fonts (Inter font family)
- SVG icons

 Project Structure

```
mwanasheria-tech-website/
├── index.html          # Main website file
├── README.md           # This documentation file
└── assets/             # (Optional folder for future assets)
    ├── images/         # Project images and logos
    └── css/            # CSS files if separated
```

Setup Instructions

1. **Clone or Download**:
   ```bash
   git clone https://github.com/yourusername/mwanasheria-tech-website.git
   ```
   Or download the ZIP file

2. Edit Content:
   - Open `index.html` in any text editor
   - Modify text, images, and contact information
   - Replace placeholder images with your actual project screenshots

3. Hosting:
   - See hosting options in the "Deployment" section below

 Customization Guide

 Change Colors
Edit the CSS variables in the `<style>` section:
```css
:root {
  --accent: #00b894;       /* Primary brand color */
  --accent-2: #00a1d6;     /* Secondary brand color */
  --bg: #0f1724;           /* Background color */
  --card: #0b1220;         /* Card backgrounds */
}
```

Update Contact Information
Locate these sections in the HTML:
```html
<!-- In the Contact card -->
<p><strong>Email:</strong> mwanasheriatechsolutions@gmail.com</p>
<p><strong>Phone:</strong> +255 687 030 949</p>

<!-- In the contact form mailto: link -->
window.location.href = 'mailto:mwanasheriatechsolutions@gmail.com?subject='...;
```

### Add Portfolio Items
Duplicate and modify the project divs:
```html
<div class="project">
  <img src="your-image.jpg" alt="Project Name">
  <div class="meta">
    <h4>Project Name</h4>
    <p style="color:var(--muted)">Project description</p>
  </div>
</div>
```




 Form Handling

The current contact form uses a `mailto:` fallback. For proper form submission:



License

This project is open-source under the MIT License. Feel free to use as a template for your business website.

 Contact

For support or inquiries:
- Email: mwanasheriatechsolutions@gmail.com
- Phone: +255 687 030 949
- Office: Mbeya, Tanzania
