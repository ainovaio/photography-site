# 📸 LENS Photography Portfolio - README

## Overview
Premium photography portfolio website with 6 responsive pages featuring a dark theme with gold, brown, and silver accents.

## 🗂️ File Structure
```
portfolio/
├── home.html
├── projects.html
├── achievements.html
├── feedback.html
├── gallery.html
├── contact.html
└── images/
    ├── hero-bg.jpg
    ├── featured1-8.jpg
    ├── service-*.jpg
    ├── award*-img*.jpg
    ├── client1-10.jpg
    ├── brand1-4-logo.png
    └── gallery1-10.jpg
```

## 📏 Image Specifications

### **Home Page (home.html)**
| Image Name | Size | Format | Description |
|------------|------|--------|-------------|
| `hero-bg.jpg` | 1920x1080px | JPG | Main hero background (16:9 landscape) |
| `featured1.jpg` | 800x800px | JPG | Large feature image (square) |
| `featured2.jpg` | 400x400px | JPG | Small square |
| `featured3.jpg` | 400x400px | JPG | Small square |
| `featured4.jpg` | 400x800px | JPG | Tall portrait |
| `featured5.jpg` | 400x400px | JPG | Small square |
| `featured6.jpg` | 800x400px | JPG | Wide landscape |
| `featured7.jpg` | 400x400px | JPG | Small square |
| `featured8.jpg` | 400x400px | JPG | Small square |

### **Projects Page (projects.html)**
All service images are **600x800px** (portrait, 3:4 ratio)
| Image Name | Description |
|------------|-------------|
| `service-wedding.jpg` | Wedding photography service |
| `service-video.jpg` | Videography service |
| `service-portrait.jpg` | Portrait photography |
| `service-graduation.jpg` | Graduation photos |
| `service-party.jpg` | Party & events |
| `service-product.jpg` | Product photography |
| `service-fashion.jpg` | Fashion editorial |
| `service-corporate.jpg` | Corporate events |
| `service-custom.jpg` | Custom projects |

### **Achievements Page (achievements.html)**
All achievement images are **500x500px** (square)

**Award Set 1:**
- `award1-img1.jpg`
- `award1-img2.jpg`
- `award1-img3.jpg`
- `award1-img4.jpg`

**Award Set 2:**
- `award2-img1.jpg`
- `award2-img2.jpg`
- `award2-img3.jpg`
- `award2-img4.jpg`

**Award Set 3:**
- `award3-img1.jpg`
- `award3-img2.jpg`
- `award3-img3.jpg`
- `award3-img4.jpg`

**Award Set 4:**
- `award4-img1.jpg`
- `award4-img2.jpg`
- `award4-img3.jpg`
- `award4-img4.jpg`

### **Feedback Page (feedback.html)**

**Client Avatars (200x200px square - displayed as circles):**
- `client1.jpg` through `client10.jpg`

**Brand Logos (400x200px landscape, PNG with transparency):**
- `brand1-logo.png`
- `brand2-logo.png`
- `brand3-logo.png`
- `brand4-logo.png`

### **Gallery Page (gallery.html)**
Mixed sizes for dynamic collage layout:
| Image Name | Size | Format |
|------------|------|--------|
| `gallery1.jpg` | 800x1000px | Portrait, large |
| `gallery2.jpg` | 1200x600px | Landscape, wide |
| `gallery3.jpg` | 600x600px | Square |
| `gallery4.jpg` | 500x800px | Portrait, tall |
| `gallery5.jpg` | 800x600px | Landscape |
| `gallery6.jpg` | 600x800px | Portrait |
| `gallery7.jpg` | 900x600px | Landscape |
| `gallery8.jpg` | 900x600px | Landscape |
| `gallery9.jpg` | 600x600px | Square |
| `gallery10.jpg` | 1200x800px | Landscape, large |

### **Contact Page (contact.html)**
No images required - form-based page

## 🎨 Design Specifications

### Color Palette
- **Black**: `#0a0a0a` (Main background)
- **Dark Grey**: `#1a1a1a` (Cards, containers)
- **Brown**: `#8B6F47` (Accents)
- **Gold**: `#D4AF37` (Primary accent)
- **Silver**: `#C0C0C0` (Text, secondary accent)
- **White**: `#f5f5f5` (Main text)

### Typography
- **Headers**: Cormorant Garamond (serif)
- **Body Text**: Montserrat (sans-serif)

## 🚀 Features

### Page-by-Page Features

**1. Home Page**
- Hero section with gradient overlay on background image
- Animated text appearance
- Masonry-style collage grid (8 images)
- Statistics counter section
- Smooth scroll animations

**2. Projects Page**
- 9 service cards with hover effects
- Icon overlays
- Feature tags for each service
- Call-to-action section

**3. Achievements Page**
- Alternating layout (images left/right)
- 4 images per achievement in 2x2 grid
- Statistics display
- Award tags
- Decorative corner borders

**4. Feedback Page**
- 10 client testimonials in masonry layout
- Star ratings
- Client avatars (circular)
- 4 official photographer partnership cards
- Brand logo showcase

**5. Gallery Page**
- Creative collage layout (10 images)
- Lightbox modal for full-size viewing
- Hover overlay effects
- Smooth zoom animations

**6. Contact Page**
- Sticky contact information sidebar
- Comprehensive contact form
- Service selection dropdown
- Date picker for events
- Success message modal
- Map placeholder section

## 💡 Image Optimization Tips

### General Guidelines
1. **Resolution**: 72-150 DPI for web
2. **File Size**: Aim for <500KB per image
3. **Format**: 
   - JPG for photographs
   - PNG for logos (with transparency)
4. **Quality**: High quality, well-lit images
5. **Consistency**: Similar color tones for cohesive look

### Recommended Image Style
- Professional photography aesthetic
- High contrast, well-lit
- Colors complementing gold/brown/silver theme
- Hero image: slightly darker for text readability
- Client photos: clean backgrounds, professional headshots
- Brand logos: transparent backgrounds preferred

### Tools for Optimization
- **TinyPNG** / **TinyJPG** - Compress without quality loss
- **Adobe Photoshop** - Batch resize and optimize
- **GIMP** - Free alternative for image editing
- **ImageOptim** (Mac) - Drag-and-drop optimization
- **Squoosh** (Web) - Online image optimizer

## 📱 Responsive Design

The portfolio is fully responsive with breakpoints:
- **Desktop**: 1024px and above
- **Tablet**: 768px - 1024px
- **Mobile**: Below 768px

### Mobile Features
- Hamburger menu navigation
- Single-column layouts
- Touch-optimized interactions
- Optimized image sizes

## 🔧 Setup Instructions

1. **Create folder structure**
   ```bash
   mkdir portfolio
   cd portfolio
   mkdir images
   ```

2. **Add HTML files**
   - Copy all 6 HTML files to the root folder

3. **Add images**
   - Place all images in the `images/` folder
   - Ensure exact file names match (case-sensitive)

4. **Update image paths** (if needed)
   - If images are in a subfolder, update src paths:
   - `src="hero-bg.jpg"` → `src="images/hero-bg.jpg"`

5. **Test locally**
   - Open `home.html` in a web browser
   - Check all navigation links work
   - Verify all images load correctly

## 🌐 Deployment Options

### Option 1: GitHub Pages
```bash
git init
git add .
git commit -m "Initial commit"
git push origin main
```
Enable GitHub Pages in repository settings

### Option 2: Netlify
- Drag and drop folder to Netlify
- Automatic deployment

### Option 3: Traditional Hosting
- Upload via FTP to web host
- Ensure proper folder structure maintained

## ✨ Customization

### Updating Content
1. **Text**: Edit directly in HTML files
2. **Colors**: Modify CSS variables in `:root` section
3. **Fonts**: Change Google Fonts import and font-family
4. **Images**: Replace with same file names and sizes

### Adding More Items
- **Gallery**: Add more `.gallery-item` divs
- **Testimonials**: Duplicate `.testimonial-card` structure
- **Services**: Add new `.service-card` blocks

## 🐛 Troubleshooting

### Images Not Loading
- Check file names match exactly (case-sensitive)
- Verify images are in correct folder
- Check file extensions (.jpg vs .jpeg)

### Layout Issues
- Clear browser cache
- Check browser console for errors
- Verify all HTML tags are properly closed

### Mobile Menu Not Working
- Ensure JavaScript is enabled
- Check for JavaScript errors in console

## 📞 Support

For issues or questions:
- Check image file names and sizes
- Verify folder structure
- Test in different browsers
- Check browser console for errors

## 📄 License

This portfolio template is provided for personal and commercial use.

---

**Created with ❤️ for premium photography portfolios**

Version 1.0 | Last Updated: 2024