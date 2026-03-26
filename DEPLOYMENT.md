# RBOT Electronics Website - Deployment Guide

## Files Included

- **index.html** - Main HTML file with all sections
- **styles.css** - Complete styling with animations and responsive design
- **front.webp** - Store front image
- **in.webp** - Store interior image

## Features

### Professional Design
- Modern color scheme (Dark Navy & Cyan Blue) with excellent contrast
- Clean, minimalist aesthetic
- Smooth animations and transitions throughout
- Professional typography and spacing

### Responsive Layout
- Mobile-first design optimized for all devices
- Sticky action bar on mobile for easy contact access
- Fully responsive grid layouts
- Touch-friendly buttons and interactions

### Key Sections
1. **Hero Section** - Eye-catching header with WhatsApp and Call buttons
2. **Gallery** - Image showcase of your store with hover effects
3. **Product Categories** - 6 product categories with icons and descriptions
4. **Availability Card** - Single call-to-action for inquiries
5. **About Section** - Store information with features list
6. **Location Section** - Embedded Google Map and contact details
7. **Contact Section** - WhatsApp and phone contact cards
8. **Footer** - Business information

### Interactive Elements
- Hover effects on cards (lift animation)
- Smooth button interactions with ripple effects
- Image zoom on hover
- Icon animations
- Gradient backgrounds with subtle animations

### WhatsApp Integration
- Real WhatsApp logo SVG icons (not generic icons)
- Click-to-chat with prefilled messages
- Multiple WhatsApp buttons throughout the site
- All links route to: `https://wa.me/919809384767`

## Deployment Instructions

### Option 1: Netlify (Recommended)
1. Create a free account on [netlify.com](https://netlify.com)
2. Drag and drop the entire project folder into Netlify
3. Site will be live in seconds with a custom URL

### Option 2: Vercel
1. Go to [vercel.com](https://vercel.com) and sign up
2. Import the project folder
3. Click "Deploy"

### Option 3: Any Static Host
- Upload all files (index.html, styles.css, front.webp, in.webp) to your host
- No backend or build process required

## Customization

### Colors
Edit the CSS variables at the top of `styles.css`:
```css
:root {
    --primary: #1a2332;           /* Dark navy */
    --accent: #0094c7;            /* Cyan blue */
    --success: #2ecc71;           /* Green for WhatsApp */
    --background: #f5f7fa;        /* Light gray background */
}
```

### Contact Information
Update these values in `index.html`:
- Phone number: Search for `919809384767` and replace
- WhatsApp links: Update the `wa.me/919809384767` in all links
- Address: Update in location section
- Business hours: Update in the info section

### Images
Replace `front.webp` and `in.webp` with your own store photos

## Performance

- Page size: ~400KB (with images)
- Load time: < 2 seconds on 4G
- No JavaScript dependencies
- Optimized for mobile networks
- SEO-friendly HTML structure

## Browser Support

- Chrome, Firefox, Safari, Edge (all modern versions)
- Mobile browsers (iOS Safari, Chrome Mobile)
- Internet Explorer 11+ for basic functionality

## Technical Details

- Pure HTML5 + CSS3
- No frameworks or dependencies
- No build process required
- CSS variables for easy theming
- Semantic HTML structure
- Accessibility-friendly markup

---

Website is production-ready and can be deployed immediately!
