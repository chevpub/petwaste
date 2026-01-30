# Image Placeholders Guide

This file documents the images you'll need to add to make the website fully functional.

## Required Images

### 1. team-photo.jpg
- **Location**: Root directory
- **Recommended Size**: 800x600px
- **Format**: JPG
- **Description**: Photo of your team members working or posing with equipment
- **Alt Text**: "Doodie Soldiers Team"
- **Usage**: About section - shows your professional team

### 2. service-photo.jpg
- **Location**: Root directory
- **Recommended Size**: 800x600px
- **Format**: JPG
- **Description**: Photo showing your service in action (yard cleaning, equipment)
- **Alt Text**: "Service in action"
- **Usage**: Expectations section - demonstrates your work process

### 3. map.jpg
- **Location**: Root directory
- **Recommended Size**: 1200x800px
- **Format**: JPG
- **Description**: Map showing your service coverage area
- **Alt Text**: "Service Area Map"
- **Usage**: Service areas section - shows where you operate
- **Alternative**: You can use Google Maps embedded iframe or a custom interactive map

### 4. mascot.png
- **Location**: Root directory
- **Recommended Size**: 400x600px (approx)
- **Format**: PNG with transparency
- **Description**: Your company mascot or character (soldier character)
- **Alt Text**: "Doodie Soldiers Mascot"
- **Usage**: FAQ section - adds personality and branding

## Image Optimization Tips

1. **Compress images** before uploading to improve load times
   - Use tools like TinyPNG, ImageOptim, or Squoosh
   - Target: Under 200KB for photos, under 50KB for graphics

2. **Use appropriate formats**:
   - JPG for photographs
   - PNG for graphics with transparency
   - SVG for logos and icons (already provided)

3. **Responsive images**: Consider creating multiple sizes
   - Desktop: Full resolution
   - Tablet: 75% of desktop size
   - Mobile: 50% of desktop size

4. **Alt text**: Always include descriptive alt text for accessibility

## Creating Placeholder Images

If you don't have images ready, you can use these placeholder services temporarily:

1. **Placeholder.com**
   - Example: `https://via.placeholder.com/800x600/003DA5/FFFFFF?text=Team+Photo`

2. **Unsplash** (free stock photos)
   - Search for: "team", "yard work", "map", "cartoon dog"

3. **Pexels** (free stock photos)
   - Good for professional service photos

## Updating Images in HTML

Once you have your images, simply replace the filenames in `index.html`:

```html
<!-- Replace these lines -->
<img src="team-photo.jpg" alt="Doodie Soldiers Team">
<img src="service-photo.jpg" alt="Service in action">
<img src="map.jpg" alt="Service Area Map">
<img src="mascot.png" alt="Doodie Soldiers Mascot">
```

## Custom Logo

A basic SVG logo is provided (`logo.svg`). For a professional logo:
1. Hire a designer on Fiverr or 99designs
2. Use logo maker tools like Canva or LogoMaker
3. Ensure you get SVG format for best quality
4. Replace the existing `logo.svg` file

## Background Patterns

The hero section uses CSS-generated patterns. If you want to add custom background images:

1. Create large, subtle patterns (2000x1000px recommended)
2. Save as optimized JPG or PNG
3. Update the CSS in `styles.css`:

```css
.hero::before {
    background: url('hero-pattern.jpg');
    /* ... */
}
```

## Social Media Icons

Currently using simple text placeholders. For better icons:
1. Use Font Awesome (free CDN)
2. Use SVG icons from Font Awesome or Heroicons
3. Replace text with proper icon elements

## Future Enhancements

- Add favicon (16x16, 32x32, 64x64 PNG)
- Create Open Graph images for social sharing (1200x630px)
- Add Apple touch icon (180x180px)
- Consider using a CDN for image hosting

---

**Note**: All images should be professionally taken or properly licensed. Avoid using copyrighted images without permission.
