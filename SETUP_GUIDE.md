# Windows Server Website - Setup Guide

## Repository Information
- **Username**: M0rwen
- **Repository**: OS-Website
- **Repository URL**: https://github.com/M0rwen/OS-Website

## Step-by-Step Setup Guide

### Step 1: Enable GitHub Pages
1. Go to your repository: https://github.com/M0rwen/OS-Website
2. Click on the **Settings** tab
3. Scroll down to the **Pages** section in the left sidebar
4. Under "Build and deployment", select **Deploy from a branch**
5. Under "Branch", select **main**
6. Under "Folder", select **/(root)**
7. Click **Save**

### Step 2: Wait for Deployment
- GitHub will take 1-2 minutes to deploy your site
- You'll see a green checkmark when it's ready
- Your site will be available at: **https://m0rwen.github.io/OS-Website/**

### Step 3: Verify Your Website
1. Visit: https://m0rwen.github.io/OS-Website/
2. Check that all pages load correctly
3. Test the dropdown menus
4. Verify all navigation links work

## Website Features
✅ **Main Page**: Your name (Yunice Jam Matabile) and section (BSIT-S-2A)
✅ **Windows 2008 Dropdown**: Detailed sections (Overview, Features, Editions, System Requirements, Installation)
✅ **Windows Server Dropdown**: Links to all Windows versions (95, 98, ME, 2008, Vista, 8, 10, 11)
✅ **Design**: Minimalist with cream, soft mauve, and white colors
✅ **Responsive**: Works on desktop and mobile devices

## File Structure
```
OS-Website/
├── index.html              # Main homepage
├── windows95.html          # Windows 95 page
├── windows98.html          # Windows 98 page
├── windowsme.html          # Windows ME page
├── windows2008.html        # Windows 2008 page
├── windowsvista.html       # Windows Vista page
├── windows8.html           # Windows 8 page
├── windows10.html          # Windows 10 page
├── windows11.html          # Windows 11 page
└── SETUP_GUIDE.md          # This setup guide
```

## Making Updates
To update your website:
1. Make changes to any HTML file
2. Commit changes: `git add . && git commit -m "Your update message"`
3. Push to GitHub: `git push`
4. GitHub Pages will automatically update within 1-2 minutes

## Troubleshooting

### If Site Doesn't Load
- Wait 2-3 minutes after enabling GitHub Pages
- Check the Settings > Pages section for deployment status
- Make sure you selected the correct branch (main) and folder (/(root))

### If Links Don't Work
- Verify all HTML files are in the repository
- Check that file names match exactly (case-sensitive)
- Ensure all files are in the root directory

### If Design Looks Wrong
- GitHub Pages serves files correctly
- All CSS is embedded in HTML files
- Design should work exactly as intended

## Live URL
Once deployed, your website will be live at:
**https://m0rwen.github.io/OS-Website/**

## Alternative: Local Testing
If you want to test locally before deploying:
1. Open command prompt in the OS-Website folder
2. Run: `python -m http.server 8000`
3. Open browser and go to: `http://localhost:8000`

## Support
If you encounter any issues:
1. Check that all files are uploaded to GitHub
2. Verify GitHub Pages is enabled in Settings
3. Wait a few minutes for deployment to complete
4. Check the GitHub Pages deployment logs in your repository

---

**Your Windows Server documentation website is now ready to share with the world!** 🚀
