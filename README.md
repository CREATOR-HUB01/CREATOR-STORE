# CREATOR STORE - Website Files

This folder contains all files needed to host the website on GitHub Pages.

## Files in this folder:

- `index.html` - Main HTML file
- `styles.css` - All CSS styling (IMPORTANT: Make sure this is named `styles.css` with an 's')
- `app.js` - All JavaScript functionality
- `products.json` - Product data (categories, products, kits)
- `images/` - Images folder with subfolders for categories, products, and kits

## How to Upload to GitHub:

### Option 1: Upload this entire folder contents to GitHub root

1. Go to your GitHub repository
2. Upload all files from this `website` folder
3. **Important**: Upload files directly to root, NOT inside a `website` subfolder
4. So your GitHub repo structure should be:
   ```
   your-repo/
   ├── index.html
   ├── styles.css
   ├── app.js
   ├── products.json
   └── images/
   ```

### Option 2: Drag and drop

1. Open your GitHub repository
2. Click "uploading an existing file"
3. Drag and drop all files from this `website` folder:
   - index.html
   - styles.css
   - app.js
   - products.json
   - images/ (entire folder)
4. Click "Commit changes"

### Important Notes:

- ✅ Make sure `styles.css` is named correctly (with 's')
- ✅ All files should be in root of repository, not in a subfolder
- ✅ `images/` folder should include all subfolders
- ✅ After uploading, wait 2-5 minutes for GitHub Pages to update
- ✅ Use hard refresh: Ctrl+Shift+R after uploading

## Verify Upload:

Check that your repository has these files at the root:
- index.html
- styles.css
- app.js  
- products.json
- images/ folder

Your website should be live at: `https://yourusername.github.io/repository-name/`



# Contact form setup
1. Apps Script deployed at: https://script.google.com/macros/s/AKfycbyih5_cKug0reBvJNNObqu3TI1BA22R1OMq6JiDdeQ2ElDWVOMR5X0y3oeHeosHNnhiTg/exec
2. Ensure Project Properties in Apps Script include:
   CONTACT_SECRET = 9f3d7f2b-1c6a-4f9e-a2b5-8b2d9c6f3e7a
   OWNER_EMAIL = your-email@example.com
3. Upload these files to your repo root and publish via GitHub Pages.
