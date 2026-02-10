# Kailash Hotel Website - Setup Instructions

## 📁 Folder Structure

Your website files should be organized like this:

```
your-website-folder/
├── index.html
├── styles.css
├── script.js
└── images/
    ├── 1.jpg
    ├── 2.jpg
    ├── 3.jpg
    ├── 4.jpg
    ├── 5.jpg
    ├── 6.jpg
    ├── 7.jpg
    ├── 8.jpg
    ├── 9.jpg
    ├── 10.jpg
    ├── 11.jpg
    ├── 12.jpg
    ├── 13.jpg
    ├── 14.jpg
    ├── 15.jpg
    ├── 16.jpg
    ├── 17.jpg
    ├── 18.jpg
    ├── 19.jpg
    ├── 20.jpg
    ├── 21.jpg
    ├── 22.jpg
    ├── 23.jpg
    ├── 24.jpg
    └── 25.jpg
```

## 🖼️ Image Setup

1. Create a folder named `images` in the same directory as your HTML file
2. Place your 25 hotel images in this folder
3. Rename them as: `1.jpg`, `2.jpg`, `3.jpg`, ... up to `25.jpg`
4. If your images have different extensions (like .png, .jpeg), either:
   - Rename them to .jpg, OR
   - Update the image paths in `index.html` to match your file extensions

## 📝 Important: Update Contact Information

Before publishing your website, replace the placeholder contact details:

In `index.html`, search and replace:
- `+977-1-XXXXXXX` → Your actual Nepal phone number
- `977XXXXXXXXX` → Your actual WhatsApp number (in the WhatsApp link)

## 🌐 Image File Formats Supported

The website supports:
- `.jpg` / `.jpeg`
- `.png`
- `.webp`

If your images are in different formats, update the file extensions in the HTML file.

## 🚀 How to Launch Your Website

### Option 1: Simple (For Testing)
1. Create the folder structure as shown above
2. Double-click `index.html` to open it in your browser

### Option 2: Web Hosting
1. Upload all files (including the `images` folder) to your web hosting service
2. Make sure the folder structure is maintained
3. Access your website via your domain name

## 🔧 Customization Tips

### Changing Slider Speed
In `script.js`, find this line:
```javascript
autoSlideInterval = setInterval(nextSlide, 4000); // Change slide every 4 seconds
```
Change `4000` to adjust the speed (in milliseconds):
- 3000 = 3 seconds
- 5000 = 5 seconds
- etc.

### Adding More Images
If you have more than 25 images:
1. Add more `<div class="slide">` elements in `index.html`
2. Follow the same pattern with sequential numbering

### Removing Images
If you have fewer than 25 images:
1. Delete the extra `<div class="slide">` elements from `index.html`
2. Keep only the slides you need

## 🎨 Image Recommendations

For best results:
- **Resolution**: At least 1920x1080 pixels (Full HD)
- **Aspect Ratio**: 16:9 or similar landscape orientation
- **File Size**: Optimize to under 500KB per image for faster loading
- **Format**: JPG for photos (best compression)

## 📱 Languages Supported

The website supports three languages:
- English
- हिंदी (Hindi)
- नेपाली (Nepali)

Users can switch languages using the dropdown in the navigation bar.

## ✅ Checklist Before Going Live

- [ ] All 25 images are in the `images/` folder
- [ ] Images are named correctly (1.jpg, 2.jpg, etc.)
- [ ] Phone number updated in HTML
- [ ] WhatsApp number updated in HTML
- [ ] All files are in the same folder
- [ ] Tested the website in a browser
- [ ] Website looks good on mobile devices

## 🆘 Troubleshooting

**Images not showing?**
- Check that the `images` folder is in the same directory as `index.html`
- Verify image filenames match exactly (1.jpg, not 01.jpg or 1.JPG)
- Check that image files aren't corrupted

**Slider not working?**
- Make sure `script.js` is in the same folder as `index.html`
- Check browser console for errors (F12 > Console)

**Layout broken on mobile?**
- Clear browser cache
- Test in different browsers

---

Need help? The website is fully self-contained and doesn't require any server-side processing!
