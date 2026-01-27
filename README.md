# Welcome to Donegal Town Website

A beautiful, multi-page website showcasing Donegal Town, Ireland - a destination guide for tourists featuring attractions, restaurants, activities, and practical information.

## Features

- **6 Unique Pages:**
  - Homepage with hero section and featured attractions
  - Attractions page (Donegal Castle, Diamond Square, landmarks)
  - Restaurants & Dining page (pubs, seafood, Irish cuisine)
  - Things to Do page (activities, tours, festivals, shopping)
  - Practical Information page (parking, transport, maps, visitor tips)
  - About Donegal page (history, heritage, culture)

- **Design:**
  - Traditional Irish heritage aesthetic
  - Color palette: deep greens, warm golds, cream backgrounds
  - Celtic-inspired decorative elements
  - Responsive design (mobile-first)
  - Clean, SEO-friendly HTML structure

- **Technical:**
  - Pure HTML, CSS, and JavaScript (no frameworks)
  - Fast loading, lightweight
  - Free hosting compatible (Netlify, GitHub Pages, Vercel)
  - Excellent SEO (semantic HTML, meta tags, proper structure)

## Project Structure

```
welcome_to_donegal_town/
├── index.html              # Homepage
├── css/
│   └── style.css          # Main stylesheet
├── js/
│   └── script.js          # JavaScript functionality
├── pages/
│   ├── attractions.html   # Attractions page
│   ├── restaurants.html   # Restaurants & Dining page
│   ├── things-to-do.html  # Things to Do page
│   ├── practical-info.html # Practical Information page
│   └── about.html         # About Donegal page
└── README.md              # This file
```

## Quick Start

1. Open `index.html` in your web browser to view the website

## Deployment Options

### Option 1: Netlify (Recommended - Free & Easy)
1. Go to [netlify.com](https://netlify.com) and create a free account
2. Click "Add new site" → "Deploy manually"
3. Drag and drop this entire folder onto Netlify
4. Your site will be live instantly with a free URL

### Option 2: GitHub Pages (Free)
1. Push this repository to GitHub
2. Go to repository Settings → Pages
3. Under "Source", select "main" branch and save
4. Your site will be live at `https://yourusername.github.io/welcome_to_donegal_town`

### Option 3: Vercel (Free)
1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` in this directory
3. Follow the prompts
4. Your site will be deployed with a free URL

### Option 4: Traditional Web Hosting
Simply upload all files to any web hosting provider's public directory (often called `public_html` or `www`).

## Customization

### Replace Placeholder Content
All content is placeholder text that can be easily replaced with real information about Donegal Town:
- Restaurant names, menus, and contact details
- Specific attraction information and operating hours
- Real photos of Donegal Town
- Updated contact information and social media links

### Add Images
Replace the Unsplash image URLs with your own images:
1. Place your images in the `images/` folder
2. Update the `src` attributes in HTML files to point to your images
3. Optimize images for web (recommended: JPEG for photos, PNG for graphics)

### Modify Colors
Edit the color variables in `css/style.css`:
```css
:root {
    --primary-green: #1a4d2e;
    --dark-green: #0d2818;
    --accent-gold: #c9a227;
    --warm-cream: #faf8f0;
    /* ... etc */
}
```

## Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## SEO Features

- Semantic HTML5 structure
- Meta descriptions and keywords on all pages
- Proper heading hierarchy (h1, h2, h3)
- Alt text for images
- Clean, readable URLs
- Fast loading times

## Future Enhancements

Potential additions to expand the website:
- Real image gallery
- Interactive map integration
- Contact form
- Blog/news section
- Booking integration for attractions/restaurants
- Multi-language support

## License

This website is provided as-is for educational and commercial use.

## Support

For questions or issues, please refer to the deployment documentation of your chosen hosting platform.