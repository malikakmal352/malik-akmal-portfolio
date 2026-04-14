# Deploy Portfolio to GitHub Pages

## Quick Setup Commands

1. **Initialize Git repository:**
```bash
git init
git add .
git commit -m "Initial portfolio commit"
```

2. **Connect to GitHub repository:**
```bash
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git
git branch -M main
git push -u origin main
```

3. **For future updates:**
```bash
git add .
git commit -m "Update portfolio"
git push origin main
```

## GitHub Pages Setup

1. Go to repository Settings → Pages
2. Source: Deploy from a branch
3. Branch: main
4. Folder: / (root)
5. Save

## Your Live URL
https://YOUR_USERNAME.github.io/YOUR_REPOSITORY_NAME/

## Important Notes

- **Images**: Make sure to add your actual project images to the `images/` folder
- **Profile Photo**: Add your profile photo as `images/profile.jpg`
- **Updates**: Any changes pushed to the main branch will automatically update your live site
- **Custom Domain**: You can add a custom domain later in Pages settings

## File Checklist

- ✅ index.html
- ✅ styles.css
- ✅ README.md
- ⚠️ images/profile.jpg (add your photo)
- ⚠️ images/housing/ (add project screenshots)
- ⚠️ Other project images (loomcentric.jpg, etc.)

## Troubleshooting

- **404 Error**: Make sure `index.html` is in the root directory
- **Images Not Loading**: Check file paths and ensure images are uploaded
- **Changes Not Showing**: GitHub Pages can take 5-10 minutes to update
- **CSS Not Loading**: Verify `styles.css` is in the same directory as `index.html`