# Student Portfolio Website

A beautiful, modern portfolio website showcasing academic achievements, coding projects, music, and extracurricular activities.

## 🌐 Deploying to GitHub Pages

Follow these steps to host your website for free on GitHub Pages:

### Step 1: Create a GitHub Account
1. Go to [https://github.com](https://github.com)
2. Click "Sign up" and create your free account
3. Verify your email address

### Step 2: Create a New Repository
1. Click the "+" icon in the top right corner
2. Select "New repository"
3. Name it: `student-portfolio` (or any name you prefer)
4. Set it to **Public**
5. **DO NOT** check "Add a README file" (we already have one)
6. Click "Create repository"

### Step 3: Upload Your Files
You have two options:

#### Option A: Upload via Web Interface (Easier for beginners)
1. On your new repository page, click "uploading an existing file"
2. Drag and drop ALL these files:
   - `index.html`
   - `math-coding.html`
   - `music.html`
   - `activities.html`
   - `styles.css`
   - `student-photo.jpg` (or your image file)
   - `README.md`
3. Add a commit message like "Initial commit - Upload portfolio website"
4. Click "Commit changes"

#### Option B: Use Git Command Line (if you're comfortable with terminal)
```bash
cd "/Users/kaushikmittra/Library/CloudStorage/OneDrive-NVIDIACorporation/Adrita-Web-Page"
git init
git add .
git commit -m "Initial commit - Upload portfolio website"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/student-portfolio.git
git push -u origin main
```

### Step 4: Enable GitHub Pages
1. In your repository, click "Settings" (top menu)
2. Scroll down and click "Pages" in the left sidebar
3. Under "Source", select:
   - Branch: **main**
   - Folder: **/ (root)**
4. Click "Save"
5. Wait 1-2 minutes for deployment

### Step 5: Access Your Website
Your website will be live at:
```
https://YOUR-USERNAME.github.io/student-portfolio/
```

🎉 **Your website is now live and accessible to anyone!**

## 📝 Making Updates

To update your website after it's deployed:

1. Make changes to your HTML/CSS files locally
2. Go to your GitHub repository
3. Click on the file you want to update
4. Click the pencil icon (Edit)
5. Make your changes
6. Scroll down and click "Commit changes"
7. Your website will automatically update in 1-2 minutes!

## 🎨 Files in This Project

- `index.html` - Main homepage with navigation
- `math-coding.html` - Math and coding accomplishments
- `music.html` - Musical achievements
- `activities.html` - Extracurricular activities
- `styles.css` - Styling for all pages
- `student-photo.jpg` - Profile image
- `README.md` - This file

## 💡 Tips

- **Custom Domain:** You can add a custom domain (like yourname.com) in the GitHub Pages settings
- **HTTPS:** GitHub Pages automatically provides HTTPS for security
- **Updates:** Any changes you push to the main branch will automatically update your live site
- **Share:** Share your website URL on your resume, college applications, or social media!

## 🔧 Troubleshooting

**Website not loading?**
- Wait 2-3 minutes after enabling GitHub Pages
- Make sure `index.html` is in the root folder (not in a subfolder)
- Check that all files are uploaded

**Images not showing?**
- Make sure your image file is uploaded to the repository
- Verify the filename matches exactly what's in `index.html`

**Links not working?**
- Ensure all HTML files are in the same folder
- Check that filenames match exactly (case-sensitive)

## 📞 Need Help?

If you run into any issues, GitHub has excellent documentation:
- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [GitHub Getting Started Guide](https://docs.github.com/en/get-started)

---

Built with HTML, CSS, and ❤️

