# Yechiel's Fishery Farm - Children's Books Website

## About This Website
A beautiful, responsive website for Yechiel's magical children's book series about aquatic life and marine biology. Features include:
- 📚 Book showcase (published, coming soon, in progress)
- 🗺️ Interactive farm map
- 🐠 Character profiles
- 👤 Author biography with real photos
- ✉️ Newsletter signup
- 📱 Fully mobile responsive

## Installation Instructions

### Option 1: Local Testing (Before Uploading to Web)
1. Download this folder to your computer
2. Open `index.html` in any web browser
3. The website will work perfectly offline with all images embedded

### Option 2: Upload to Web Server (via FTP/SFTP)
Your hosting provider (GoDaddy, Bluehost, etc.) should provide FTP credentials.

**Steps:**
1. Connect to your server using FTP software (FileZilla is free)
2. Upload all files and folders from this folder to your web server
3. The main file is `index.html` — this is your homepage
4. Keep the `uploads/` folder in the same directory
5. Visit your domain — the website will appear!

**Example structure on server:**
```
public_html/
  ├── index.html
  └── uploads/
      ├── front cover.png
      ├── map 2.png
      ├── image 5.png
      └── ... (all other images)
```

### Option 3: GitHub (Free, Recommended for Updates)
**Yes! GitHub is completely free.** Here's how:

1. **Create a GitHub account** → https://github.com/signup
2. **Create a new repository** (click "+" → "New repository")
   - Name it: `yechiel-fishery-farm`
   - Check "Add a README file"
   - Click "Create repository"
3. **Upload files:**
   - Click "Add file" → "Upload files"
   - Drag-and-drop all files from this folder
   - Click "Commit changes"
4. **Go to Settings** → **Pages** → Select "Deploy from branch" → Choose `main` branch → Save
5. **Your site is live!** GitHub gives you a free URL like: `https://yourusername.github.io/yechiel-fishery-farm`

**Why GitHub is great:**
- Free forever hosting
- Easy to update — just re-upload new files
- Anyone can download your code
- Perfect for adding interactive features later

## File Structure
```
website-folder/
├── index.html              (Main website file)
├── README.md               (This file)
└── uploads/                (All images)
    ├── front cover.png
    ├── back cover.png
    ├── map 2.png
    ├── image 5.png
    ├── image 6.png
    ├── image 7 - עותק.png
    ├── 1777484822428.jpeg
    ├── IMG_20230915_111641.jpg
    └── IMG_20230915_111649 - עותק-4af708a0.jpg
```

## Customization

**To edit the website**, open `index.html` in any text editor and find:
- Book titles/descriptions → Search for `<h3>` tags in the Books section
- Character names → Search for "Meet the Characters"
- Newsletter email signup → Look for `handleNewsletter` function
- Colors → Look for color codes like `#1a5f7a` (dark teal) and `#2b9db8` (light teal)

## Support
If your tech team needs help:
- Check the HTML comments in the file for section markers
- All styling is in the `<style>` tag at the top
- All images use relative paths (`uploads/image.png`) so they work anywhere

## Future Enhancements
The website is ready for:
- ✅ Interactive character map (clickable locations)
- ✅ Activity PDF downloads
- ✅ Affiliate links to book retailers
- ✅ Contact/email forms
- ✅ Blog or news updates section

---

**Created with ❤️ for Yechiel's Fishery Farm**
Website version: 1.0
Last updated: 2024
