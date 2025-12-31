# SANAGA ASHOK KUMAR — Advocate Website

A modern, responsive website for Sanaga Ashok Kumar, Advocate at the High Court of Andhra Pradesh. The website features a professional design with a custom hero background image and comprehensive sections for legal services, case records, testimonials, FAQ, and contact information.

## Features

- **Responsive Design**: Fully responsive layout optimized for all devices (desktop, tablet, mobile)
- **Modern UI/UX**: Clean, professional design with warm color palette matching the brand identity
- **Custom Hero Section**: Background image with embedded text and logo, optimized for mobile viewing
- **Interactive Elements**:
  - Mobile-friendly navigation menu with hamburger toggle
  - FAQ accordion with smooth animations
  - Smooth scrolling navigation
  - Contact form with validation
  - Scroll-triggered animations
- **Comprehensive Sections**:
  - Hero section with call-to-action and statistics
  - Legal services overview
  - About section
  - Why Choose Me features
  - Case records showcase
  - Client testimonials
  - FAQ section
  - Contact form and information

## File Structure

```
advocate new/
├── index.html              # Main HTML file
├── styles.css              # All CSS styling
├── script.js               # JavaScript for interactivity
├── case-2024.html          # Case records page for 2024
├── images/
│   ├── logo.png           # Logo image
│   ├── photo.png          # Hero background image (desktop)
│   └── photo mobile.png   # Hero background image (mobile)
└── README.md              # This file
```

## Setup Instructions

1. **Download/Clone the files** to your local machine

2. **Open the website**:
   - Simply open `index.html` in your web browser
   - Or use a local development server:
     ```bash
     # Using Python 3
     python -m http.server 8000
     
     # Using Node.js (with http-server)
     npx http-server
     
     # Using PHP
     php -S localhost:8000
     ```

3. **Customize the content**:
   - Edit `index.html` to update text, contact information, and content
   - Modify `styles.css` to change colors, fonts, and styling
   - Update `script.js` to add custom functionality

## Customization

### Colors

The website uses CSS variables for easy color customization. Edit the `:root` section in `styles.css`:

```css
:root {
    --primary-color: #7a5f3f;      /* Main brand color (warm brown) */
    --secondary-color: #c9a961;    /* Accent color (gold) */
    --text-dark: #2c3e50;          /* Dark text */
    --text-light: #6c757d;         /* Light text */
    /* ... */
}
```

### Contact Information

Update the contact details in `index.html`:
- Phone number: Search for `8886906996`
- Email: Search for `sanaga.ashok@gmail.com`
- Address: Search for `Door No. 4-5-62, Saibaba Road`

### Background Images

The hero section uses different background images for desktop and mobile:
- Desktop: `images/photo.png`
- Mobile: `images/photo mobile.png`

To update these, replace the image files while maintaining the same filenames, or update the paths in `styles.css`.

### Form Submission

The contact form currently shows an alert on submission. To connect it to a backend:

1. Update the form submission handler in `script.js`
2. Add your form processing endpoint
3. Implement proper error handling and success messages

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with Flexbox and Grid, CSS variables
- **JavaScript (Vanilla)**: No dependencies required
- **Google Fonts**: Playfair Display (serif) & Inter (sans-serif)
- **Font Awesome**: Icons library

## Design Features

- **Responsive Typography**: Font sizes and spacing adjust for optimal readability across devices
- **Mobile-First Approach**: Hero section optimized for mobile with separate background image
- **Professional Color Scheme**: Warm brown and gold palette for a trustworthy, professional appearance
- **Accessibility**: Semantic HTML and proper contrast ratios for readability

## License

This website is created for Sanaga Ashok Kumar, Advocate. All rights reserved.

## Notes

- Ensure all image files (`logo.png`, `photo.png`, `photo mobile.png`) are present in the `images/` directory
- The form submission is currently handled with a simple alert. Connect to your backend service
- Update all placeholder content with actual information
- Consider adding a privacy policy page
- Add Google Analytics or other tracking if needed
- The hero background image contains embedded text that should remain visible on mobile devices

## Support

For customization help or questions, refer to the code comments in each file.
