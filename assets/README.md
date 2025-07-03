# Assets Directory

This directory contains all the static assets for the Cablity website.

## 📁 Structure

```
assets/
├── images/          # Website images and graphics
├── icons/           # Icon files and graphics
├── fonts/           # Custom font files (if any)
└── README.md        # This file
```

## 🖼️ Images

The website uses optimized images from Pexels CDN for:
- Hero background (fiber optic cables)
- Team/about section images
- Testimonial customer photos

All images are loaded via CDN links for optimal performance.

## 🎨 Icons

Icons are implemented as inline SVG for:
- Logo and branding
- Service icons
- Navigation elements
- Social media links
- Contact information

## 🎯 Optimization

- **WebP Format** preferred for modern browsers
- **Lazy Loading** implemented for below-the-fold images
- **Responsive Images** with appropriate sizes
- **CDN Delivery** for fast loading times

## 📱 Responsive Assets

Images are optimized for multiple screen sizes:
- Mobile: 320px - 767px
- Tablet: 768px - 1023px
- Desktop: 1024px+

## 🔧 Usage

To add new assets:
1. Place files in appropriate subdirectories
2. Update references in HTML/CSS
3. Ensure proper optimization
4. Test across devices

---

**Note**: This website uses external CDN resources for images to ensure optimal performance and reduce hosting requirements.