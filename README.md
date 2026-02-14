# Vyapaar Analytics Website

This website is fully responsive and works on both desktop and mobile devices.

## Files Included

1. **index.html** - Home page
2. **about.html** - About Us page
3. **contact.html** - Contact page
4. **styles.css** - All styling for the website
5. **script.js** - JavaScript for mobile menu and animations

## Important: Where to Add Your Content

### Google Form Links
Search for `<!-- GOOGLE FORM LINK:` in the HTML files to find where to add your Google Form URL.
Replace `#` with your actual Google Form link in these locations:
- index.html (3 places): Navigation "Free Audit" button, Hero section button, and WhatsApp consultation button
- about.html (1 place): Navigation "Free Audit" button
- contact.html (1 place): Navigation "Free Audit" button

### About Us Content
In **about.html**, find this section:
```html
<!-- ========================================== -->
<!-- ADD YOUR ABOUT US CONTENT BELOW THIS LINE -->
<!-- ========================================== -->
```
Add your company history, mission, vision, team info, etc. between the marked lines.

### Contact Details
In **contact.html**, find this section:
```html
<!-- ============================================ -->
<!-- ADD YOUR CONTACT DETAILS BELOW THIS LINE -->
<!-- ============================================ -->
```
Add your email, phone number, WhatsApp, address, etc. between the marked lines.

## Publishing to GitHub Pages

1. Create a new repository on GitHub
2. Upload all files (index.html, about.html, contact.html, styles.css, script.js)
3. Go to repository Settings → Pages
4. Select the branch (usually 'main') and root folder
5. Click Save
6. Your website will be live at: https://yourusername.github.io/repository-name/

## Images/Icons Note

The design references several images and icons. You'll need to:
1. Create or source the following images:
   - Logo icon (SVG is already in the code, you can customize colors)
   - Hero illustration (businessman with dashboard)
   - Challenge icons (4 icons)
   - Service icons (4 icons)
   - Testimonial photo

2. Save them in the same folder as your HTML files
3. The file names are already referenced in the HTML:
   - hero-illustration.svg
   - icon-inventory.svg
   - icon-reports.svg
   - icon-profit.svg
   - icon-sales.svg
   - icon-dashboard.svg
   - icon-optimization.svg
   - icon-analysis.svg
   - icon-automation.svg
   - testimonial-person.jpg

Alternatively, you can use placeholder images from services like:
- https://placeholder.com/
- https://unsplash.com/
- https://www.flaticon.com/ (for icons)

## Customization

### Colors
Edit the `:root` section in styles.css to change the color scheme:
```css
:root {
    --primary-color: #2D8B7F;
    --secondary-color: #48A999;
    --dark-blue: #1B3B5F;
    /* etc. */
}
```

### Fonts
The website uses system fonts by default. To use custom fonts (like Google Fonts), add the link in the `<head>` section of each HTML file.

## Browser Compatibility

This website works on:
- Chrome, Firefox, Safari, Edge (latest versions)
- Mobile browsers (iOS Safari, Chrome Mobile)
- Tablets and all screen sizes

## Need Help?

If you need to make changes, the code is well-commented. Look for the section titles in CSS like:
- `/* NAVIGATION */`
- `/* HERO SECTION */`
- `/* CHALLENGES SECTION */`
etc.

Good luck with your website! 🚀
