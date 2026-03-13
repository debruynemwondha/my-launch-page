# My Launch Page – 20 Videos

This is a **launch page** where users can **click images to watch 20 different videos**.  
It is fully optimized for **GitHub Pages** and **mobile-friendly**.  

---

## Features
- Click any image → corresponding video plays below.  
- Supports **20 videos** with thumbnails.  
- Simple, clean, and responsive layout.  
- Works with **HTTPS** on GitHub Pages.  
- Easy to update: add more images and videos if needed.

---

## Files
- `index.html` → main launch page  
- `poster1.jpg` → thumbnail for video 1  
- `poster2.jpg` → thumbnail for video 2  
- … up to `poster20.jpg`  
- `clip1.mp4` → video 1  
- `clip2.mp4` → video 2  
- … up to `clip20.mp4`  

All files are placed inside the `/docs` folder for GitHub Pages.  

---

## How to View the Launch Page
1. Go to the live site (GitHub Pages URL):

   2. Click any image → the corresponding video will play below.  

---

## How to Add More Videos
1. Add your new images and videos inside `/docs`.  
2. Update `index.html` by adding a new line for the new image, e.g.:

```html
<img src="poster21.jpg" alt="Clip 21" data-video="clip21.mp4">
