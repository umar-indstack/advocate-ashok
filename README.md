# Sarah Mitchell Law - Divorce Attorney Website

A modern, responsive website template for a divorce attorney law firm, featuring a clean design and comprehensive sections for services, testimonials, FAQ, and contact information.

## Features

- **Responsive Design**: Fully responsive layout that works on all devices (desktop, tablet, mobile)
- **Modern UI/UX**: Clean, professional design with smooth animations and transitions
- **Interactive Elements**:
  - Mobile-friendly navigation menu
  - FAQ accordion
  - Smooth scrolling navigation
  - Contact form with validation
  - Scroll-triggered animations
- **Comprehensive Sections**:
  - Hero section with call-to-action
  - Services overview
  - About section
  - Why Choose Us features
  - Client testimonials
  - FAQ section
  - Contact form and information

## File Structure

```
advocate new/
├── index.html      # Main HTML file
├── styles.css      # All CSS styling
├── script.js       # JavaScript for interactivity
└── README.md       # This file
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
    --primary-color: #1a4d7a;      /* Main brand color */
    --secondary-color: #c9a961;    /* Accent color */
    --text-dark: #2c3e50;          /* Dark text */
    --text-light: #6c757d;         /* Light text */
    /* ... */
}
```

### Contact Information

Update the contact details in `index.html`:
- Phone number: Search for `(555) 123-4567`
- Email: Search for `sarah@mitchelllaw.com`
- Address: Search for `123 Legal Avenue`

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
- **CSS3**: Modern styling with Flexbox and Grid
- **JavaScript (Vanilla)**: No dependencies required
- **Google Fonts**: Playfair Display & Inter fonts

## License

This template is free to use and customize for your law firm website.

## Notes

- All images/icons are represented by emojis. Replace with actual images as needed
- The form submission is currently handled with a simple alert. Connect to your backend service
- Update all placeholder content with your actual information
- Consider adding a privacy policy page
- Add Google Analytics or other tracking if needed

## Support

For customization help or questions, refer to the code comments in each file.


